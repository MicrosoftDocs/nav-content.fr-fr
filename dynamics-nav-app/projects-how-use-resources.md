---
title: Enregistrer et ajuster l'utilisation et les prix des ressources
description: "Décrit la manière dont vous pouvez enregistrer l'utilisation ou la consommation ressource associée à un projet, de garder la trace et de gérer les coûts, les prix, ainsi que les types de travaux."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, capacity, staff
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3ee2af302aa75f091d85a2667e53d69ea8ed9ea8
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-use-resources-for-jobs"></a>Procédure : Utiliser des ressources pour des projets
Vous devez enregistrer l'utilisation des ressources dans la feuille projet pour suivre les coûts et les prix, ainsi que les types de travaux associés aux projets. Pour plus d'informations, reportez-vous à [Procédure : Enregistrer l'utilisation pour les projets](projects-how-record-job-usage.md).

Vous pouvez aussi valider l'utilisation d'une ressource sur une feuille ressource. Les écritures validées sur une feuille ressource n'ont aucune incidence sur la comptabilité.

## <a name="to-assign-resources-to-jobs"></a>Pour affecter des ressources aux projets
Vous pouvez affecter des ressources aux projets en créant des lignes planning projet pour le projet. Pour plus d'informations, reportez-vous à [Procédure : Créer des projets](projects-how-create-jobs.md).

## <a name="to-record-resource-usage-for-a-job"></a>Pour enregistrer l'utilisation des ressources pour un projet
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuilles projet**, puis sélectionnez le lien connexe.
2. Ouvrez la feuille projet appropriée, puis complétez les champs selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Lorsque la feuille est renseignée, cliquez sur **Valider**.

## <a name="to-adjust-resource-prices"></a>Pour ajuster le prix des ressources
Si vous souhaitez modifier le coût ou le prix d'un grand nombre de ressources, vous pouvez utiliser un traitement par lots.  

1. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Ajuster coûts/prix ressource**, puis sélectionnez le lien connexe.
2. Renseignez les autres champs selon vos besoins, puis cliquez sur le bouton **OK**.

> [!NOTE]  
>   Ce traitement par lots ne crée pas et n'ajuste pas les nouveaux coûts ou prix des ressources. Il modifie uniquement le contenu du champ de la fiche ressource correspondant au champ **Champ à modifier** que vous avez sélectionné dans le traitement par lots. L'ajustement s'appliquant immédiatement aux ressources, vérifiez les facteurs d'ajustement avant de lancer le traitement par lots.

## <a name="to-get-resource-price-change-suggestions-based-on-existing-alternate-prices"></a>Pour obtenir des propositions de modification des prix ressource basées sur les prix secondaires existants
Si vous avez déjà configuré des prix secondaires pour un certain nombre de ressources, vous pouvez utiliser le traitement par lots pour configurer des prix ressource secondaires.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Nouv. prix ressource proposés**, puis sélectionnez le lien connexe.
2. Sélectionnez l'action **Prop. modif. prix ress. (prix)**, puis renseignez les champs selon vos besoins.
3. Cliquez sur le bouton **OK**.  
4. Lorsque le traitement par lots est terminé, la fenêtre **Nouv. prix ressource proposés** affiche les résultats du traitement par lots.

## <a name="to-get-resource-price-change-suggestions-based-on-standard-prices"></a>Pour obtenir des propositions de modification des prix ressource basées sur les prix standard :
Si vous souhaitez configurer des prix ressource secondaires basés sur les prix standard des fiches ressource, vous pouvez utiliser un traitement par lots.  

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Nouv. prix ressource proposés**, puis sélectionnez le lien connexe.
2. Sélectionnez l'action **Prop. modif. prix ress. (ress)**, puis renseignez les champs selon vos besoins.  
3. Cliquez sur le bouton **OK**.  
4. Lorsque le traitement par lots est terminé, ouvrez la fenêtre **Nouv. prix ressource proposés** pour visualiser les résultats du traitement par lots.

## <a name="to-get-resource-price-change-suggestions-based-on-alternate-prices"></a>Pour obtenir des propositions de modification des prix ressource basées sur les prix standard
Si vous avez déjà configuré des prix secondaires pour un certain nombre de ressources, vous pouvez utiliser le traitement par lots pour configurer des prix ressource secondaires.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Prop. modif. prix ress. (prix)**, puis sélectionnez le lien connexe.  
2. Renseignez les champs selon vos besoins.
3. Cliquez sur le bouton **OK**.  
4. Lorsque le traitement par lots est terminé, ouvrez la fenêtre **Nouv. prix ressource proposés** pour visualiser les résultats du traitement par lots.

## <a name="see-also"></a>Voir aussi
[Gestion de projets](projects-manage-projects.md)  
[Finances](finance.md)  
[Achats](purchasing-manage-purchasing.md)         
[Ventes](sales-manage-sales.md)     
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

