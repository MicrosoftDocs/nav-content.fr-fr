---
title: "Procédure : déplacer les composants vers une zone opérations dans les configurations de stockage de base"
description: "Si des opérations de traitement d'articles se produisent dans votre entrepôt, vous pouvez être amené à déplacer des articles entre différents emplacements internes pour satisfaire aux documents origine internes, tels que la production, l'assemblage ou les commandes service dans le magasin."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c1ee0394b835827eee3394a4bea3171d9294208c
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-move-components-to-an-operation-area-in-basic-warehouse-configurations"></a>Procédure : déplacer les composants vers une zone opérations dans les configurations de stockage de base
Si des opérations de traitement d'articles se produisent dans votre entrepôt, vous pouvez être amené à déplacer des articles entre différents emplacements internes pour satisfaire aux documents origine internes, tels que la production, l'assemblage ou les commandes service dans le magasin.  

> [!NOTE]  
>  Pour plus d'informations sur le déplacement d'articles d'un emplacement à l'autre sans documents origine, reportez\-vous à Mouvement interne.  

Dans les configurations d'entrepôt avancées, qui correspondent à des magasins qui utilisent le champ de configuration **Prélèv. et rangement suggérés**, vous pouvez utiliser la fenêtre **Feuille mouvement** pour déplacer des articles d'un emplacement à l'autre. Pour plus d'informations, voir [Procédure : déplacer des articles dans les configurations de stockage avancées](warehouse-how-to-move-items-in-advanced-warehousing.md).  

Dans les configurations d'entrepôt de base, où les magasins utilisent les champs de configuration **Emplacement obligatoire** et **Prélèvement requis**, vous pouvez enregistrer des mouvements d'articles vers des zones Opérations internes sur la base de documents origine internes en procédant comme suit :  

-   À l'aide de la fenêtre **Mouvement de stock**.  
-   Avec la fenêtre **Prélèvement stock**.  

> [!NOTE]  
>  Les prélèvements stock valident également les écritures comptables article négatives en tant que consommation et ne sont pris en charge que pour les composants de production. Pour plus d'informations, voir la fenêtre Feuille prélèvement.  

Pour obtenir des informations détaillées sur des mouvements de stock, reportez\-vous à la fenêtre Mouvement de stock.  

Deux différents rôles peuvent créer le mouvement de stock d'origine. Un ouvrier d'assemblage, par exemple, peut le créer à partir d'un ordre d'assemblage lancé de façon à ce qu'il s'affiche sur la liste du travail à accomplir du magasinier. Pour créer un mouvement de stock pour les lignes d'ordre d'assemblage prêtes à voir des composants déplacés dans leurs emplacements spécifiés, l'ouvrier d'assemblage utilise la fonction **Créer mouvement de stock** .  

Sinon, un magasinier peut le créer en pointant l'ordre d'assemblage lancé en question. Ceci est décrit dans la procédure suivante.  

> [!NOTE]  
>  Si le mouvement concerne un ordre d'assemblage pour lequel l'article est assemblé à une commande vente, vous pouvez définir que le document mouvement de stock est automatiquement créé lorsque vous créez le document prélèvement stock qui prend l'élément d'assemblage terminé et valide l'expédition. Pour configurer cela, sélectionnez le champ **Créer des mouvements automatiquement** dans la fenêtre **Paramètres d'assemblage**  
>   
>  Pour plus d'informations sur les ordres d'assemblage et les configurations entrepôt de base, reportez-vous à la section « Traitement des articles à assembler pour commande dans les prélèvements stock » dans [Procédure : prélever pour la fabrication et l'assemblage](warehouse-how-to-pick-for-production.md).  

Cette procédure explique comment créer un mouvement de stock à partir de la fenêtre **Mouvement de stock** en référençant un ordre d'assemblage lancé en tant que document origine. La procédure est la même lorsque vous déplacez les composants pour les ordres de fabrication et les commandes service.  

## <a name="to-move-components-to-an-operation-area-in-basic-warehouse-configurations"></a>Pour déplacer les composants vers une zone opérations dans les configurations de stockage de base  
1.  Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Mouvement de stock**, puis sélectionnez le lien approprié.  
2.  Sur le raccourci **Général**, renseignez le champ **N°**. . Vous pouvez appuyer sur la touche Entrée pour effectuer une sélection parmi la souche de numéros.  
3.  Dans le champ **Code magasin** , entrez le magasin où le mouvement a lieu.  
4.  Choisissez l'action **Extraire documents origine**. Sinon, renseignez le champ **Document origine** , et cliquez ensuite sur le bouton **AssistEdit** dans le champ **N° origine** .  
5.  Dans la fenêtre **Documents origine** , sélectionnez l'ordre d'assemblage pour lequel vous souhaitez déplacer des composants, puis choisissez le bouton **OK** .  

    Pour chaque composant nécessaire pouvant être déplacé, une ligne prélèvement et une ligne d'emplacement sont générées dans la fenêtre **Mouvements de stock** . Tous les champs à l'exception du champ **Qté à traiter** sont préremplis en fonction des lignes document origine. Le champ **Qté à traiter** est défini sur zéro jusqu'à ce que vous entriez la quantité que vous avez réellement déplacée.  

    Vous pouvez modifier le code emplacement de la ligne prélèvement mais uniquement en fonction de la disponibilité. Si vous choisissez le bouton **AssistEdit** dans le champ **Code emplacement** sur une ligne prélèvement, la fenêtre **Contenu emplacement** s'ouvre et affiche uniquement les emplacements où le composant est disponible.  

    Vous ne pouvez pas modifier le code emplacement sur une ligne d'emplacement. Seul le code emplacement qui est défini sur la ligne composant du document origine est accepté. Cela se base sur le principe que le rôle demandant un composant, qui est un ouvrier d'assemblage dans cette procédure, sait où doit être placé le composant. Si vous souhaitez placer les composants dans un autre emplacement, vous devez d'abord modifier le code emplacement de la ligne composant puis recréer les lignes mouvement de stock.  
6.  Dans le champ **Qté à traiter**, entrez la quantité totale ou partielle que vous avez réellement déplacée. La valeur sur les lignes prélèvement et emplacement doit être la même. Sinon, vous ne pouvez pas enregistrer le mouvement.  

    > [!NOTE]  
    >  Comme pour d'autres activités entrepôt, vous pouvez éclater la ligne d'emplacement en sélectionnant l'action **Actions**, puis en choisissant l'action **Eclater ligne**. Dans ce cas, la somme des deux lignes d'emplacement éclatées doit être égale à la quantité de la ligne prélèvement.  

7.  Lorsque vous êtes prêt à enregistrer les mouvements que vous avez exécutés, choisissez l'action **Enregistrer mouvement de stock** .  

    Les écritures entrepôt sont créées, reflétant que les composants existent désormais dans les emplacements spécifiés sur les lignes d'ordre d'assemblage.  

    > [!NOTE]  
    >  Contrairement au déplacement de composants à l'aide d'un prélèvement stock, la consommation n'est pas validée lorsque vous enregistrez un mouvement de stock. Cette étape doit être réalisée séparément en validant la production et la consommation de l'ordre d'assemblage. Pour plus d'informations, reportez\-vous à Ordre d'assemblage.  

## <a name="see-also"></a>Voir aussi  
[Gestion d'entrepôt](warehouse-manage-warehouse.md)  
[STOCKS ET EN-COURS](inventory-manage-inventory.md)  
[Configuration de la gestion des entrepôts](warehouse-setup-warehouse.md)     
[Gestion des assemblages](assembly-assemble-items.md)    
[Détails de conception : gestion d'entrepôt](design-details-warehouse-management.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

