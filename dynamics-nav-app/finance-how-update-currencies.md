---
title: "Mise à jour des taux de change devise"
description: "Pour utiliser plusieurs devises dans votre société, vous pouvez définir un code pour chaque devise et utiliser un service externe de taux de change, par exemple Yahoo."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, Yahoo
ms.date: 07/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 50603747629eee61f9bdaed900dcfc0dfc96ab3b
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-update-currency-exchange-rates"></a>Procédure : mettre à jour les taux de change des devises
Vous devez définir un code pour chaque devise utilisée si vous achetez ou vendez dans des devises différentes de votre devise locale, si vous disposez de comptes client ou fournisseur dans d'autres devises, ou si vous enregistrez des transactions comptables dans des devises différentes.  

Les sociétés opérant dans un nombre croissant de pays/régions, il est de plus en plus important qu'elles puissent consulter ou générer des états financiers dans plusieurs devises. Le programme prend en charge l'utilisation de plusieurs devises. Dans le programme, la comptabilité est configurée pour utiliser votre devise société (DS) et une autre devise est configurée comme devise supplémentaire, à laquelle est affecté un taux de change courant.  

 Si vous désignez une deuxième devise comme Devise report supplémentaire, [!INCLUDE[d365fin](includes/d365fin_md.md)] enregistre automatiquement les montants d'état en DS et dans cette devise supplémentaire pour chaque écriture comptable, ainsi que pour d'autres écritures, telles que les écritures TVA. Lorsque les montants écriture sont calculés dans une devise report supplémentaire, les informations de la fenêtre **Taux de change devise** permettent de rechercher le taux de change approprié.  

> [!WARNING]  
>  Il est déconseillé d'utiliser la fonctionnalité de devise report comme base pour une conversion d'état financier. Cet outil ne permet pas d'effectuer une conversion d'états financiers de filiale étrangère dans le cadre d'une consolidation de société. La fonctionnalité de devise report permet uniquement de préparer des états dans une autre devise, comme s'il s'agissait de la devise société.

## <a name="adjusting-exchange-rates"></a>Ajustement des taux de change  
Comme les taux de change ne cessent de fluctuer, il convient d'ajuster périodiquement les équivalents devise supplémentaires de votre système. À défaut d'effectuer ces ajustements, les montants convertis à partir de devises étrangères (ou supplémentaires) et publiés dans la comptabilité en DS risquent d'être erronés. En outre, les écritures quotidiennes validées avant la saisie d'un taux de change quotidien dans le programme doivent être mises à jour après la saisie des informations de taux de change quotidienne. Le traitement par lots Ajuster taux de change permet d'ajuster les taux de change d'écritures client, fournisseur et compte bancaire validées. Il peut également mettre à jour d'autres montants en devise report dans des écritures comptables.  

## <a name="displaying-reports-and-amounts-in-the-additional-reporting-currency"></a>Affichage d'états et de montants dans la devise report  
L'utilisation d'une devise report peut faciliter le processus de génération d'états d'une société dans les cas suivants :  

- Sociétés situées dans des pays/régions extérieur(e)s à l'UE qui effectuent un grand nombre de transactions avec des sociétés situées dans des pays/régions de l'UE. Dans ce cas, la société extérieure à l'UE peut vouloir générer des états financiers en euros afin qu'ils soient plus lisibles pour ses partenaires commerciaux de l'UE.  

- Sociétés qui souhaitent pouvoir générer des états financiers dans une devise davantage utilisée au niveau international que leur devise société.  

Plusieurs états dans le module Comptabilité sont basés sur les écritures comptables. Pour afficher les données financières dans les états en devise report, sélectionnez simplement le champ **Afficher dans la devise suppl.** dans la fenêtre de l'état comptable approprié.  

## <a name="to-set-up-a-currency-exchange-rate-service"></a>Configurer un service de taux de change des devises
Vous pouvez utiliser un service externe pour tenir vos taux de change des devises à jour. Le service Configuration des taux de change devise Yahoo est préinstallé et prêt à être activé.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Services de taux de change devise**, puis sélectionnez le lien connexe.
2. Sélectionnez l'action **Nouveau**.
3. Dans la fenêtre **Service de taux de change devise**, renseignez les champs selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Activez la case à cocher **Activé** pour activer le service.

## <a name="to-update-currency-exchange-rates-through-a-service"></a>Pour mettre à jour les taux de change des devises à partir d'un service
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Devises**, puis sélectionnez le lien connexe.
2. Choisissez l'option **Mettre à jour les taux de change**.

La valeur dans le champ **Taux de change** de la fenêtre **Devises** est mise à jour avec le dernier taux de change des devises.

## <a name="see-also"></a>Voir aussi
[Clôture des exercices et des périodes](year-close-years-periods.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

