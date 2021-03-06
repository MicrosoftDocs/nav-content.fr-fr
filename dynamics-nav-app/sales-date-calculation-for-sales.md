---
title: Calcul de la date des ventes
description: "Le programme calcule automatiquement la date à laquelle vous devez commander un article pour l'avoir en stock à une certaine date. Il s'agit de la date à laquelle des articles commandés à une date donnée devraient être disponibles pour le prélèvement."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 72e8f2a2f1d2d6427c716205da7ecee58b85bcc6
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="date-calculation-for-sales"></a>Calcul de la date des ventes
[!INCLUDE[d365fin](includes/d365fin_md.md)] calcule automatiquement la première date possible à laquelle un article d'une ligne commande vente peut être expédié.

Si le client a demandé une date livraison particulière, alors la date à laquelle les articles doivent pouvoir être prélevés est calculée pour permettre une livraison à cette date.

Si le client ne demande pas de date livraison particulière, alors la date à laquelle les articles peuvent être livrés, à partir de la date à laquelle les articles peuvent être prélevés, est calculée.

## <a name="calculating-a-requested-delivery-date"></a>Calcul d'une date de livraison demandée
Si vous spécifiez une date de livraison demandée sur la ligne vente, alors cette date est utilisée comme point de départ du calcul suivant :

- Date livraison demandée - délai d'expédition = date d'expédition planifiée
- Date d'expédition + délai désenlogement = date d'expédition planifiée

Si les articles peuvent être prélevés à la date d'expédition, alors le processus vente peut continuer.

Si les articles ne peuvent pas être prélevés à la date d'expédition, alors une alerte rupture de stock est affichée.

## <a name="calculating-the-earliest-possible-delivery-date"></a>Calcul de la première date de livraison possible
Si vous ne spécifiez aucune date livraison demandée sur la ligne de commande vente ou si la date livraison demandée ne peut pas être respectée, alors la première date à laquelle les articles sont disponibles est calculée. Cette date est ensuite renseignée dans le champ Date d'expédition sur la ligne, et la date à laquelle vous prévoyez d'expédier les articles, ainsi que la date à laquelle ces derniers seront livrés au client sont calculées via les formules suivantes.

- Date d'expédition + délai désenlogement = date d'expédition planifiée
- Date livraison planifiée - délai d'expédition = date expédition planifiée


## <a name="see-also"></a>Voir aussi  
 [Calcul de la date des achats](purchasing-date-calculation-for-purchases.md)   
 [Comment calculer des dates promesse livraison](sales-how-to-calculate-order-promising-dates.md)  
 [Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

