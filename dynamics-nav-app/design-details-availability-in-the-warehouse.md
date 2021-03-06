---
title: "Détails de conception - Disponibilité dans l'entrepôt"
description: "Le système doit conserver un contrôle constant de la disponibilité des articles dans l'entrepôt, afin que les commandes sortantes puissent s'écouler efficacement et fournir des livraisons optimales."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 875286386168fea79f47dfdf0c78ef202cc21da0
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-availability-in-the-warehouse"></a>Détails de conception : disponibilité dans l'entrepôt
Le système doit conserver un contrôle constant de la disponibilité des articles dans l'entrepôt, afin que les commandes sortantes puissent s'écouler efficacement et fournir des livraisons optimales.  

 La disponibilité varie selon les affectations au niveau de l'emplacement quand des activités entrepôt, par exemple des prélèvements et des mouvements défectueux, se produisent et quand le système de réservation de stock impose des restrictions à respecter. Un algorithme plutôt complexe vérifie que toutes les conditions sont remplies avant d'affecter des quantités aux prélèvements pour les flux sortants.  

## <a name="bin-content-and-reservations"></a>Contenu et réservations d'emplacement  
 Dans n'importe quelle installation de gestion d'entrepôt, les quantités d'articles ont été créés à la fois en tant qu'écritures entrepôt, dans le module Entrepôt, et en tant qu'écritures comptables article, dans le module Stock. Ces deux types d'écritures contiennent différentes informations à propos de l'endroit où se trouvent les articles et s'ils sont disponibles. Les écritures d'entrepôt définissent la disponibilité d'un article par emplacement et type d'emplacement, qui est appelée contenu d'emplacement. Les écritures comptables article définissent la disponibilité d'un article par sa réservation aux documents sortants.  

 Une fonctionnalité spéciale dans l'algorithme de prélèvement permet de calculer la quantité disponible à prélever lorsque le contenu de l'emplacement est couplé avec les réservations.  

## <a name="quantity-available-to-pick"></a>Quantité disponible pour prélèvement  
 Si, par exemple, l'algorithme de prélèvement ne prend pas en compte les quantités d'article réservées pour une expédition de commande vente en attente, ces articles peuvent être prélevés pour une autre commande vente expédiée à une date antérieure, ce qui empêche de satisfaire les premières ventes. Pour éviter cette situation, l'algorithme de prélèvement soustrait les quantités qui sont réservées pour d'autres documents sortants, quantités figurant dans les documents de prélèvement existants, et quantités qui sont prélevées mais pas encore livrées ni consommées.  

 Le résultat est affiché dans le champ **Qté disponible à prélever** de la fenêtre **Feuille prélèvement**, où le champ est calculé dynamiquement. La valeur est également calculée lorsque les utilisateurs créent les prélèvements entrepôt directement pour les documents sortants. Ces documents sortants peuvent être des commandes vente, une consommation de production ou des désenlogements transfert, dans lesquels le résultat est visible dans les champs quantité liés, tels que **Qté à traiter**.  

> [!NOTE]  
>  En ce qui concerne la priorité des réservations, la quantité à réserver est soustraite de la quantité disponible à prélever. Par exemple, si la quantité disponible dans les emplacements prélèvement est 5 unités, mais que 100 unités sont dans les emplacements de rangement, alors, lorsque vous tentez de réserver plus de 5 unités pour une autre commande, un message d'erreur s'affiche, car la quantité supplémentaire doit être disponible dans les emplacements prélèvement.  

### <a name="calculating-the-quantity-available-to-pick"></a>Calcul de la quantité disponible à prélever  
 La quantité disponible à prélever est calculée de la façon suivante :  

 quantité disponible pour prélèvement = quantité dans les emplacements prélèvement - quantité sur des prélèvements et des mouvements – (quantité réservée dans des emplacements prélèvement + quantité réservée sur des prélèvements et des mouvements)  

 Le schéma suivant montre les différents éléments du calcul.  

 ![Disponible à prélever, avec le chevauchement Réserver](media/design_details_warehouse_management_availability_2.png "design_details_warehouse_management_availability_2")  

## <a name="quantity-available-to-reserve"></a>Quantité disponible à réserver  
 Dans la mesure où les concepts de la valeur et de la réservation d'emplacement coexistent, le nombre d'articles disponibles pour réserver doit être aligné avec les affectations aux documents de désenlogement.  

 Il doit être possible de réserver tous les articles en stock, à l'exception de ceux qui ont lancé un traitement sortant. Par conséquent, la quantité disponible à réserver est définie comme la quantité de tous les documents et tous les types d'emplacement, à l'exception des quantités sortantes suivantes :  

-   Quantité dans les documents prélèvement non enregistrés  
-   Quantité dans les emplacements d'expédition  
-   Quantité dans les emplacements avant production  
-   Quantité dans les emplacements atelier ouverts  
-   Quantité dans les emplacements avant assemblage  
-   Quantité dans les emplacements ajustement  

 Le résultat est affiché dans le champ **Quantité totale disponible** de la fenêtre **Réservation**.  

 Sur une ligne réservation, la quantité qui ne peut pas être réservée, parce qu'elle est affectée dans l'entrepôt, est affichée dans le champ **Qté affectée à l'entrepôt** de la fenêtre **Réservation**.  

### <a name="calculating-the-quantity-available-to-reserve"></a>Calcul de la quantité disponible à réserver  
 La quantité disponible à réserver est calculée de la façon suivante :  

 quantité disponible à réserver = quantité totale en stock - quantité sur des prélèvements et des mouvements pour des documents origine - quantité réservée - quantité dans des emplacements désenlogement  

 Le schéma suivant montre les différents éléments du calcul.  

 ![Disponible pour réserver, par affectations entrepôt](media/design_details_warehouse_management_availability_3.png "design_details_warehouse_management_availability_3")  

## <a name="see-also"></a>Voir aussi  
 [Détails de conception : gestion d'entrepôt](design-details-warehouse-management.md)

