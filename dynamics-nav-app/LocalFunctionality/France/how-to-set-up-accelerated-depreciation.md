---
title: "Procédure de paramétrage de l'amortissement accéléré"
description: "Pour utiliser la fonction de calcul de l'amortissement accéléré, vous devez configurer les lois d'amortissement pour les immobilisations."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 6dcee004d82b837e283c01d28dcaea11853a8366
ms.contentlocale: fr-fr
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-set-up-accelerated-depreciation"></a>Procédure : paramétrer l'amortissement accéléré
Pour utiliser la fonction de calcul de l'amortissement accéléré, vous devez configurer les lois d'amortissement suivantes pour les immobilisations :  

- la loi d'amortissement comptable (intégrée à la comptabilité) ;  
- la loi d'amortissement fiscal (non intégrée à la comptabilité).  

> [!NOTE]  
>  Lorsque vous validez une acquisition, un amortissement ou une cession pour la loi d'amortissement comptable, la transaction est automatiquement dupliquée et validée dans la loi d'amortissement fiscal lorsque la feuille immobilisation est validée.  

## <a name="to-set-up-the-accounting-depreciation-book"></a>Pour configurer la loi d'amortissement comptable  

1.  Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), saisissez **Lois d'amortissement**, puis sélectionnez le lien approprié.  
2.  Dans la fenêtre **Liste des lois d'amortissement**, sélectionnez l'action **Nouveau**.  
3.  Sous le raccourci **Général**, renseignez les champs obligatoires comme indiqué dans le tableau ci-dessous.  

    |Champ|Désignation|  
    |---------------------------------|---------------------------------------|  
    |**Code**|Code d'identification unique de la loi d'amortissement comptable. Vous pouvez entrer 10 caractères alphanumériques maximum.|  
    |**Description**|Description des lois d'amortissement.|  

    > [!IMPORTANT]  
    >  Laissez le champ **Calcul dérogatoire** vide.  

4.  Dans le raccourci **Intégration**, sélectionnez la case à cocher **Dérogatoire** pour intégrer l'amortissement accéléré dans la comptabilité.  

    Pour en savoir plus, voir [Procédure : configurer l'amortissement d'immobilisation](../../fa-how-setup-depreciation.md).  

5.  Cliquez sur le bouton **OK**.  

## <a name="to-set-up-the-tax-depreciation-book"></a>Pour configurer la loi d'amortissement fiscal  

1.  Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), saisissez **Lois d'amortissement**, puis sélectionnez le lien approprié.  
2.  Dans la fenêtre **Liste des lois d'amortissement**, sélectionnez l'action **Nouveau**.  
3.  Sous le raccourci **Général**, renseignez les champs obligatoires comme indiqué dans le tableau ci-dessous.  

    |Champ|Désignation|  
    |---------------------------------|---------------------------------------|  
    |**Code**|Code d'identification unique de la loi d'amortissement fiscal. Vous pouvez entrer 10 caractères alphanumériques maximum.|  
    |**Description**|Description des lois d'amortissement fiscal.|  

4.  Dans le champ **Calcul dérogatoire**, sélectionnez une loi d'amortissement comptable pour indiquer qu'il s'agit d'une loi d'amortissement fiscal pour le calcul de l'amortissement dérogatoire.  

    Pour en savoir plus, voir [Procédure : configurer l'amortissement d'immobilisation](../../fa-how-setup-depreciation.md).  

5.  Cliquez sur le bouton **OK**.  

Le champ **Utilisé avec la loi dérogatoire** dans la loi d'amortissement comptable est mis à jour avec le code de la loi d'amortissement fiscal.  

## <a name="see-also"></a>Voir aussi  
 [Amortissement accéléré](accelerated-depreciation.md)   
 [Procédure : calculer l'amortissement accéléré](how-to-calculate-accelerated-depreciation.md)   
[Procédure : configurer un amortissement immobilisation](../../fa-how-setup-depreciation.md)

