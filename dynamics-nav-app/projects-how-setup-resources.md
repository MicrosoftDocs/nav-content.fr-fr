---
title: "Paramétrer les coûts, prix, et capacité des ressources"
description: "Pour utiliser des ressources et faciliter la gestion de projets, vous spécifiez les coûts et les prix des différents ressources ou groupes de ressources, et définissez la capacité ressource."
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
ms.openlocfilehash: e1c2f8f41bb493c4ce2efa2156631c6d9d273439
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-resources"></a>Procédure : Paramétrer des ressources
Pour gérer correctement les activités liées aux ressources, vous devez configurer ces dernières, ainsi que les coûts et prix associés. Les prix, remises et règles de facteur coût associés au projet, sont définis dans la fiche projet. Vous pouvez spécifier les coûts et prix pour des ressources individuelles, des groupes de ressources, ou toutes les ressources disponibles de la société.

Lorsque des ressources sont utilisées ou vendues dans le cadre d'un projet, les prix et les coûts qui leur sont associés sont récupérés à l'aide des informations de configuration.

Vous spécifiez le montant horaire par défaut lors de la création de la ressource. Par exemple, si vous utilisez une machine spécifique pour un projet de cinq heures, le projet sera calculé sur la base du montant horaire.

## <a name="to-set-up-a-resource"></a>Pour paramétrer une ressource
Créez une fiche pour chaque ressource à utiliser dans les projets.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Ressources**, puis sélectionnez le lien connexe.
2. Sélectionnez l'action **Nouveau**.
3. Renseignez les champs selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

## <a name="to-set-up-a-resource-group"></a>Pour configurer un groupe de ressources
Vous pouvez combiner plusieurs ressources dans un groupe ressources. Toutes les capacités et tous les budgets du groupe ressources sont additionnés à partir des ressources. Il est également possible de saisir des capacités pour les groupes ressource, indépendamment des valeurs cumulées ou en plus de ces valeurs.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Ressources**, puis sélectionnez le lien connexe.
2. Sélectionnez l'action **Nouveau**.
3. Renseignez les champs selon vos besoins.

## <a name="to-set-capacity-for-a-resource"></a>Pour définir la capacité d'une ressource
Pour calculer le temps qu'une ressource peut passer sur des projets, leur capacité doit d'abord être configurée comme temps disponible par période sur le calendrier de travail. Cette configuration est utilisée lorsque vous renseignez les lignes planning projet qui contiennent la ressource. Pour plus d'informations, reportez-vous à [Procédure : Créer des projets](projects-how-create-jobs.md).

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Ressources**, puis sélectionnez le lien connexe.
2. Ouvrez la fiche ressource appropriée, puis cliquez sur **Capacité ressource**.
3. Dans la fenêtre **Capacité ressource**, dans le champ **Afficher par**, précisez la durée de la période (par exemple **Jour**) qui est indiquée dans le raccourci **Matrice Capacité ressource**.
4. Pour chaque ressource sur une ligne, spécifiez pour chaque période sur les colonnes le nombre d'heures pendant lesquelles la ressource est disponible.
5. Sinon, pour détailler la capacité hebdomadaire de la ressource dans un certain intervalle de temps, cliquez sur **Paramétrage capacité ressource**.
6. Dans la fenêtre **Paramétrage capacité ressource**, renseignez les champs sur une ligne selon vos besoins.
7. Cliquez sur **Mettre à jour la capacité**. La fenêtre **Capacité ressource** est mise à jour avec la capacité saisie.
8. Fermez la fenêtre.

## <a name="to-set-up-alternate-resource-costs"></a>Pour configurer des coûts ressource secondaires
Outre le coût spécifié sur la fiche ressource, vous pouvez configurer des coûts secondaires pour chaque ressource. Par exemple, si le taux horaire d'un employé augmente en raison d'heures supplémentaires, vous pouvez configurer un coût ressource pour le taux lié aux heures supplémentaires. Le coût secondaire que vous avez configuré pour la ressource remplace le coût de la fiche ressource lorsque vous utilisez la ressource dans la feuille ressource.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Ressources**, puis sélectionnez le lien connexe.  
2. Sélectionnez la ressource pour laquelle vous souhaitez configurer un ou plusieurs coûts secondaires, puis cliquez sur **Coûts**.  
3. Dans la fenêtre **Coûts ressource**, renseignez les champs sur une ligne selon vos besoins.  
4. Répétez l'étape 3 pour chaque autre coût ressource à configurer.

**Remarque**. Pour configurer les coûts des ressources s'appliquant à toutes les ressources et à tous les groupes ressources, ouvrez la fenêtre **Coûts ressource**, puis renseignez les champs.

## <a name="to-set-up-alternate-resource-prices"></a>Pour configurer le prix des ressources secondaires
Outre le prix spécifié sur la fiche ressource, vous pouvez configurer des prix secondaires pour chaque ressource. Ces prix secondaires peuvent être conditionnels. Ils peuvent être liés à l'utilisation de la ressource avec un projet ou un type travail donné.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Ressources**, puis sélectionnez le lien connexe.
2. Sélectionnez la ressource pour laquelle vous souhaitez configurer un ou plusieurs prix secondaires, puis sélectionnez l'action **Prix**.
3. Dans la fenêtre **Prix ressource**, renseignez les champs sur une ligne selon vos besoins.
4. Répétez l'étape 3 pour chaque autre prix ressource à configurer.

## <a name="see-also"></a>Voir aussi
[Configuration de la gestion de projet](projects-setup-projects.md)  
[Gestion de projets](projects-manage-projects.md)  
[Finances](finance.md)  
[Achats](purchasing-manage-purchasing.md)         
[Ventes](sales-manage-sales.md)      
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

