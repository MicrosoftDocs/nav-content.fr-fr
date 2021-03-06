---
title: "Procédure : configuration d'un diagramme des types de coûts"
description: "Le plan des types de coûts a la même fonction que le plan comptable général."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cost types, general ledger, accounts
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 104b057639090bd9797f06ebcc6b573899b9f87c
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-cost-types"></a>Procédure : configuration des types de coûts
Le plan des types de coûts a la même fonction que le plan comptable général. Vous pouvez configurer le plan des types de coûts comme suit :  

-   La structure du plan des types de coûts a la même fonction que les comptes de gestion dans le plan comptable général. Vous pouvez ensuite transférer le plan comptable général vers le plan des types de coûts. Vous pouvez effectuer tous les ajustements nécessaires après le transfert.  
-   Créez le plan des types de coûts ou ajoutez de nouveaux types de coûts au plan comptable existant des types de coûts. Vous devez créer chaque type de coûts individuellement.  

## <a name="to-transfer-the-general-ledger-chart-of-accounts-to-the-chart-of-cost-types"></a>Pour transférer le plan comptable général vers le plan des types de coûts  
1.  Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Plan comptable des types de coûts**, puis sélectionnez le lien connexe.  
2.  Choisissez l'action **Obtenir les types de coûts à partir du plan comptable**. Dans la boîte de dialogue, cliquez sur **Oui** pour confirmer le transfert. La fonction utilise le plan comptable général pour créer le plan des types de coûts.  

    Le plan des types de coûts contient désormais tous les comptes de gestion en comptabilité, et comprend les titres et les totaux. Vous pouvez modifier le plan des types de coûts, selon vos besoins. Par exemple, vous pouvez supprimer les types de coûts existants en double.  

    > [!IMPORTANT]  
    >  La fonction **Enregistrer les types de coûts dans le plan comptable** met à jour la relation entre le plan comptable et le plan des types de coûts. Le champ **N°** est renseigné et vérifié pour s'assurer que chaque compte général est lié à un seul type de coût. La fonction est automatiquement exécutée avant le transfert des écritures comptables vers la comptabilité analytique.  

## <a name="to-set-up-new-cost-types-in-the-chart-of-cost-types-window"></a>Pour configurer de nouveaux types de coût dans la fenêtre Plan comptable des types de coûts  
1.  Ouvrez la fenêtre **Plan comptable des types de coûts** en mode édition.  
2.  Renseignez les champs comme décrit selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    > [!NOTE]  
    >  Vous pouvez configurer et gérer les types de coût, soit dans la fenêtre **Fiche type de coût**, soit dans la fenêtre **Plan comptable des types de coûts**. Dans cette procédure, vous configurez de nouveaux types de coût dans la fenêtre **Plan comptable des types de coûts**.

3.  Après avoir créé tous les types de coûts, choisissez l'action **Indenter les types de coûts**. Dans la boîte de dialogue, cliquez sur **Oui**.  
4.  Liez le nouveau type de coût au compte général correspondant.  

    > [!IMPORTANT]  
    >  Si vous avez entré des définitions dans les champs **Totalisation** pour le type de ligne **Fin total** avant d'exécuter la fonction **Indenter les types de coûts**, vous devez les entrer à nouveau car cette fonction remplace les valeurs de tous les champs **Fin total**.  

## <a name="to-update-cost-types"></a>Pour mettre à jour les types de coûts  
1.  Dans la fenêtre **Paramètres comptabilité analytique**, indiquez si vous souhaitez que le plan des types de coûts soit mis à jour automatiquement lorsque le plan comptable est modifié.  
2.  Dans le champ **Aligner compte général**, vous pouvez choisir les options suivantes.  

- **Pas d'alignement** - Il n'existe aucune modification correspondante dans le plan des types de coûts lorsque vous modifiez le plan comptable.  
- **Automatique** - Une modification correspondante est apportée dans le plan des types de coûts lorsque vous modifiez le plan comptable.  
- **Invite** - Un message s'affiche et vous demande si vous voulez apporter une modification correspondante dans le plan des types de coûts lorsque vous modifiez le plan comptable.  

## <a name="see-also"></a>Voir aussi  
[Comptabilité pour les coûts](finance-manage-cost-accounting.md)  
[Définition de la relation entre les types de coûts et les comptes généraux](finance-defining-the-relationship-between-cost-types-and-general-ledger-accounts.md)   
[Définition des centres de coûts et des coûts associés pour le plan comptable](finance-defining-cost-centers-and-cost-objects-for-chart-of-accounts.md)   
[Soldes entre le type de coût, un centre de coûts et les coûts associés](finance-balances-between-cost-type-cost-center-and-cost-object.md)   
[Paramétrage du contrôle de gestion](finance-set-up-cost-accounting.md)   
[Terminologie en comptabilité analytique](finance-terminology-in-cost-accounting.md)   
[À propos de la comptabilité analytique](finance-about-cost-accounting.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

