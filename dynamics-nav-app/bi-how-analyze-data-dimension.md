---
title: "Analyse des données par axe analytique"
description: "Décrit comment analyser les diverses données métier par axe analytique."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bi, power BI, analysis, KPI
ms.date: 06/13/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 2ea54861f8203406cf6c9d110ad2317b8f883dde
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---
#  <a name="how-to-analyze-data-by-dimensions"></a>Procédure : Analyse des données par axe analytique
En analyse financière, un axe correspond à des données que vous pouvez ajouter à une écriture comme une sorte de marqueur. Ces données permettent de regrouper des écritures dotées de caractéristiques similaires, telles que les clients, les régions, les produits et les commerciaux, et de récupérer facilement ces groupes à des fins d'analyse. Les axes peuvent être utilisés sur des écritures de feuilles, de documents et de budgets. Le terme Axe décrit la manière dont l'analyse est effectuée. Une analyse à deux axes, par exemple, est une analyse des ventes par zone. Cependant, si vous utilisez plus de deux axes analytiques lors de la création d'une écriture, vous pouvez mener une analyse plus complexe, telle que des ventes par campagne de vente, par groupe client et par zone. Pour plus d'informations, reportez-vous à [Utilisation des axes](finance-dimensions.md).

L'analyse de données par axes vous permet d'obtenir un meilleur aperçu de votre activité commerciale, ce qui vous permet d'évaluer les informations, telles que la mesure du bon fonctionnement de votre société, les domaines dans lesquels elle prospère ou non, et ceux dans lesquels il est nécessaire d'affecter davantage de ressources.

> [!TIP]
> Pour analyser rapidement les données transactionnelles par dimensions, vous pouvez filtrer les totaux du plan comptable et les entrées de toutes les fenêtres **Entrées** par dimensions. Recherchez l'action **Définir le filtre axe**.

## <a name="to-set-up-an-analysis-view"></a>Pour configurer une vue d'analyse :  
Les vues analytiques affichent une combinaison sélectionnée d'axes analytiques. Vous pouvez stocker et récupérer chaque analyse que vous avez configurée. Les informations de configuration des vues analytiques sont stockées sur des fiches **Vue d'analyse** afin de simplifier une éventuelle analyse ultérieure.  

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Vues d'analyse**, puis sélectionnez le lien connexe.  
2. Dans la fenêtre **Liste des vues d'analyse**, cliquez sur l'action **Nouveau**.
3. Renseignez les champs selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Pour ajouter des codes axe aux quatre codes du raccourci **Axes analytiques**, cliquez sur **Filtre**, renseignez les champs et cliquez sur **OK**.  
5. Pour mettre à jour la vue, choisissez l'action **Mettre à jour**.

## <a name="to-analyze-by-dimensions"></a>Pour effectuer une analyse par axe analytique
La matrice **Vues analytiques** peut vous permettre de consulter les montants de votre comptabilité à l'aide des vues d'analyse que vous avez déjà configurées. Complétez la fenêtre **Vues analytiques** pour définir les éléments affichés dans la matrice, puis choisissez l'action **Afficher matrice** pour afficher la matrice.  

- Les colonnes les plus à gauche contiennent des informations basées sur l'option sélectionnée dans le champ **Afficher lignes** de l'en-tête.  
- Les colonnes les plus à droite contiennent des informations basées sur l'option sélectionnée dans le champ **Afficher colonnes** de l'en-tête.  

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Vues analytiques**, puis sélectionnez le lien connexe.  
2. Sélectionnez la vue d'analyse appropriée et choisissez l'action **Modifier vue d'analyse**.
3. En haut de la fenêtre **Analyse vente par axe analytique**, renseignez les champs pour définir ce qui est affiché.
4. 5. Pour visualiser la spécification d'un montant affiché dans la fenêtre matricielle, sélectionnez le montant.  

> [!IMPORTANT]  
>   Vous ne pouvez pas sélectionner une période plus courte que celle indiquée en tant que compression date sur la fiche **Vue d'analyse**. Les commandes **Jeu suivant** et **Jeu précédent** ne sont pas actives si vous avez sélectionné **Période** dans le champ **Afficher lignes** ou **Afficher colonnes**.  

> [!NOTE]  
>   Vous pouvez utiliser l'état **Axes analytiques - Détail** pour répertorier de manière détaillée les différentes utilisations des axes analytiques sur les écritures au cours d'une période. Vous pouvez utiliser l'état **Axes analytiques - Total** pour afficher uniquement les montants totaux.  

> [!TIP]  
>   Vous pouvez également modifier la vue en changeant la valeur des champs **Afficher lignes** et **Afficher colonnes**. Pour contrepasser un paramètre de vue, choisissez l'action **Inverser lignes et colonnes**.

## <a name="to-update-an-analysis-view"></a>Pour mettre à jour une vue d'analyse  
Les montants affichés dans la fenêtre **Vues analytiques** offrent une image de l'état de la société au moment de la dernière mise à jour. Pour obtenir une image de l'état actuel, vous devez actualiser la vue d'analyse en exécutant l'option de mise à jour.

La procédure suivante permet de mettre à jour une vue d'analyse à partir de la fenêtre **Vues analytiques**. Les étapes sont similaires entre les fenêtres **Fiche vue d'analyse** et des fenêtres **Liste des vues d'analyse**.  

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Vues analytiques**, puis sélectionnez le lien connexe.  
2. Dans la fenêtre **Vues analytiques**, sélectionnez le champ **Code vue analytique**.  
3. Sélectionnez la ligne contenant la vue d'analyse appropriée.  
4. Cliquez sur **Mettre à jour**.  

> [!TIP]  
>   Si vous activez la case à cocher **Mise à jour à la validation** sur la fiche vue d'analyse, la vue est automatiquement mise à jour lorsqu'une transaction concernée est validée.

> [!NOTE]  
>   Pour mettre à jour tout ou partie des vues d'analyse en même temps, vous devez utiliser le traitement par lots **Mise à jour vues d'analyse**.  

## <a name="see-also"></a>Voir aussi
[Veille économique](bi.md)  
[Finances](finance.md)  
[Configuration de Finance](finance-setup-finance.md)  
[Les écritures comptables et le plan comptable](finance-general-ledger.md)  
[Utilisation des axes analytiques](finance-dimensions.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

