---
title: "Prélèvement d'articles"
description: "L'activité entrepôt consistant à prélever les articles avant leur expédition ou consommation s'exécute différemment selon la configuration des fonctionnalités du module Gestion d'entrepôt. Le niveau de complexité du [paramétrage](../configure-warehouse-processes.md) varie : aucune fonctionnalité entrepôt, configurations de stockage de base pour le traitement par commande dans une ou plusieurs activités uniquement, configurations avancées dans lesquelles toutes les activités entrepôt doivent être exécutées dans un flux suggéré."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a00a6b2740bb55352dfbe8e6ac4fd3d72870608e
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="pick-items"></a>Prélèvement d'articles
L'activité entrepôt consistant à prélever les articles avant leur expédition ou consommation s'exécute différemment selon la configuration des fonctionnalités du module Gestion d'entrepôt. Le niveau de complexité du paramétrage varie : aucune fonctionnalité entrepôt, configurations de stockage de base pour le traitement par commande dans une ou plusieurs activités uniquement, configurations avancées dans lesquelles toutes les activités entrepôt doivent être exécutées dans un flux suggéré. Pour plus d'informations, voir [Configuration de la gestion des entrepôts](warehouse-setup-warehouse.md).

Si vous décidez d'organiser et d'enregistrer votre activité de prélèvement avec des documents entrepôt, activez le champ **Prélèvement requis** dans la fiche magasin. Ceci indique que lorsque vous avez des articles devant être prélevés pour un document origine sortant, vous souhaitez que le prélèvement de ces articles soit contrôlé par le système. Un document origine sortant peut être une commande vente, un retour achat, une commande désenlogement transfert, une commande service ou un ordre de fabrication dont les composants doivent être prélevés.

> [!NOTE]
> Bien que le paramétrage soit appelé **Prélèvement requis**, vous pouvez quand même valider les expéditions directement à partir des documents commerciaux origine où vous cochez cette case.

Si votre magasin est configuré pour nécessiter un traitement des prélèvements, mais pas un traitement des expéditions, vous utilisez la fenêtre **Prélèvement stock** pour organiser les informations de prélèvement, les imprimer, entrer le résultat du prélèvement effectif et valider les informations de prélèvement, ce qui valide les informations d'expédition des articles. Dans le cas du prélèvement de composants pour un ordre de fabrication, la validation du prélèvement valide également la consommation.

Si votre emplacement est configuré pour qu'il exige le traitement des prélèvements et celui des expéditions (ce qui implique que vous avez activé les champs **Prélèvement requis** et **Expédition requise** dans la fiche magasin), vous utilisez la fenêtre **Prélèvement entrepôt** pour gérer le prélèvement. Le prélèvement entrepôt fonctionne de manière similaire au prélèvement stock, si ce n'est qu'au lieu de valider les informations de prélèvement, vous enregistrez le prélèvement. Ce processus d'enregistrement ne valide pas l'expédition, mais assure simplement la disponibilité des articles pour expédition. En tant qu'administrateur entrepôt, vous pouvez utiliser des feuilles prélèvement pour organiser les informations de prélèvement avant de créer des instructions de prélèvement entrepôt.

Le tableau suivant décrit une série de tâches et inclut des liens vers les rubriques qui les décrivent.   

|**Pour**|**Voir**|
|------------|-------------|  
|Valider l'expédition d'articles directement dans le document commande sortante car aucune fonctionnalité entrepôt n'existe. (Valable également pour les commandes vente, les ordres de transfert sortants et les expéditions retour.)|[Procédure : Expédier des articles](warehouse-how-ship-items.md)|  
|Prélever les articles par commande et valider l'expédition dans la même activité dans une configuration entrepôt de base.|[Procédure : prélever des articles avec les prélèvements stock](warehouse-how-to-pick-items-with-inventory-picks.md)|
|Prélever les articles de plusieurs commandes dans une configuration entrepôt avancée.|[Procédure : prélever des articles avec les prélèvements entrepôt](warehouse-how-to-pick-items-for-warehouse-shipment.md)|  
|Prélever les composants pour la fabrication ou l'assemblage dans une configuration de stockage de base ou avancée.|[Procédure : Prélever pour la fabrication et l'assemblage](warehouse-how-to-pick-for-production.md)|  
|Planifier des instructions de prélèvement optimisées pour plusieurs expéditions. Dans ce cas, les magasiniers n'ont pas à agir directement sur les expéditions validées.|[Procédure : planifier des prélèvements dans des feuilles](warehouse-how-to-plan-picks-in-worksheets.md)|  
|Prélever des articles techniquement dans un but spécifique, par exemple une unité de production nécessitant des composants supplémentaires, de sorte que les articles ne quittent pas techniquement l'entrepôt.|[Procédure : Prélever et ranger sans document origine](warehouse-how-to-create-put-aways-from-internal-put-aways.md)|
|Sachez comment prélever automatiquement des articles en fonction de leur date d'échéance, par exemple des denrées périssables.|[Prélèvement par FEFO](warehouse-picking-by-fefo.md)|
|Divisez une ligne prélèvement en plusieurs lignes, par exemple si l'emplacement désigné ne contient pas suffisamment d'articles à prélever.|[Procédure : répartir des lignes activité entrepôt](warehouse-how-to-split-warehouse-activity-lines.md)|
|Accéder immédiatement aux prélèvements qui vous ont été affectés en tant que magasinier.|[Procédure : trouver vos affectations d'entrepôt](warehouse-how-to-find-your-warehouse-assignments.md)|  

## <a name="see-also"></a>Voir aussi  
[Gestion d'entrepôt](warehouse-manage-warehouse.md)  
[STOCKS ET EN-COURS](inventory-manage-inventory.md)  
[Configuration de la gestion des entrepôts](warehouse-setup-warehouse.md)     
[Gestion des assemblages](assembly-assemble-items.md)    
[Détails de conception : gestion d'entrepôt](design-details-warehouse-management.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

