---
title: "Déplacement d'articles"
description: "Lorsque les articles sont en stock, il peut être nécessaire de les déplacer entre plusieurs emplacements pour prendre en charge les activités entrepôt quotidiennes permettant de conserver le flux d'articles dans l'entrepôt. Certains mouvements se produisent en relation directe avec les opérations internes ; par exemple, lorsqu'un ordre de fabrication impose que des composants soient livrés ou que des produits finis soient rangés. D'autres mouvements se produisent dans le cadre d'une simple optimisation de l'espace des entrepôts ou en tant que mouvements ad-hoc depuis ou vers des opérations."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/22/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ce2e6f176d2eb13c74e54e903d284a41948d87b8
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="moving-items"></a>Déplacement d'articles
L'activité entrepôt consistant à déplacer les articles dans l'entrepôt s'exécute différemment selon la configuration des fonctionnalités du module Gestion d'entrepôt. Le niveau de complexité du paramétrage varie : aucune fonctionnalité entrepôt, configurations de stockage de base pour le traitement par commande dans une ou plusieurs activités uniquement, configurations avancées dans lesquelles toutes les activités entrepôt doivent être exécutées dans un flux suggéré. Pour plus d'informations, voir [Configuration de la gestion des entrepôts](warehouse-setup-warehouse.md).

Dans un entrepôt, il peut être nécessaire de les déplacer entre plusieurs emplacements pour prendre en charge les activités entrepôt quotidiennes permettant de conserver le flux d'articles dans l'entrepôt. Certains mouvements se produisent en relation directe avec les opérations internes ; par exemple, lorsqu'un ordre de fabrication impose que des composants soient livrés ou que des produits finis soient rangés. D'autres mouvements se produisent dans le cadre d'une simple optimisation de l'espace des entrepôts ou en tant que mouvements ad-hoc depuis ou vers des opérations.

Si le déplacement a lieu vers d'autres magasins, il a une incidence sur les écritures comptables article et doit donc être effectué dans le cadre d'un ordre de transfert. Pour plus d'informations, voir [Procédure : Transfert de stock entre des magasins](inventory-how-transfer-between-locations.md).  

Des tâches de mouvement ont lieu régulièrement afin de réapprovisionner les emplacements prélèvement et atelier et modifier les informations relatives au contenu des emplacements.  

 Le tableau suivant décrit une série de tâches et inclut des liens vers les rubriques qui les décrivent.   

|**Pour**|**Voir**|  
|------------|-------------|  
|Déplacer des articles d'un emplacement à l'autre dans des configurations entrepôt de base à tout moment et sans documents origine.|[Procédure : déplacer des articles dans les configurations de stockage de base](warehouse-how-to-move-items-ad-hoc-in-basic-warehousing.md)|
|Utiliser la feuille mouvement entrepôt pour déplacer des articles dans des configurations d'entrepôt avancées, pour les documents origine et ad hoc.|[Procédure : déplacer des articles dans les configurations de stockage avancées](warehouse-how-to-move-items-in-advanced-warehousing.md)|  
|Ajouter des articles de composant à des opérations internes dans des configurations entrepôt de base en fonction des demandes issues des documents origine de ces opérations.|[Procédure : déplacer les composants vers une zone opérations dans les configurations de stockage de base](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)|
|Planifier les emplacements à remplir ou vider pour maintenir un flux efficace (par exemple, vidage d'une zone de stockage en vrac avant une réception importante).|[Comment planifier des mouvements entrepôt dans la feuille](warehouse-how-to-plan-warehouse-movements-in-worksheets.md)|
|Mettre à jour la fréquence de réapprovisionnement des emplacements (emplacements prélèvement, etc.) suite aux fluctuations de la demande.|[Procédure : calculer réappro. emplacement](warehouse-how-to-calculate-bin-replenishment.md)|
|Restructurez votre entrepôt avec de nouveaux codes et caractéristiques emplacement et déplacez-les potentiellement autour.|[Comment restructurer les entrepôts](warehouse-how-to-restructure-warehouses.md)|  

## <a name="see-also"></a>Voir aussi  
[Gestion d'entrepôt](warehouse-manage-warehouse.md)  
[STOCKS ET EN-COURS](inventory-manage-inventory.md)  
[Configuration de la gestion des entrepôts](warehouse-setup-warehouse.md)     
[Gestion des assemblages](assembly-assemble-items.md)    
[Détails de conception : gestion d'entrepôt](design-details-warehouse-management.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

