---
title: "Procédure : Vente simultanée d'articles à assembler pour commande et d'articles en stock"
description: "Si l'élément d'assemblage est configuré pour l'assemblage pour stock, le processus par défaut de commande vente se base sur l'hypothèse que l'article est déjà assemblé et peut être prélevé du stock, s'il est disponible. Mais si une partie (ou la totalité) de la quantité n'est pas disponible, vous avez la possibilité de créer un ordre d'assemblage pour la quantité restante à la volée."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3c03adc34e009bada13f0f4ff36267d39a987749
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-sell-assemble-to-order-items-and-inventory-items-together"></a>Procédure : Vente simultanée d'articles à assembler pour commande et d'articles en stock
Si le champ **Stratégie d'assemblage** de la fiche article d'un élément d'assemblage indique **Assembler pour stock**, le processus par défaut de commande vente se base sur l'hypothèse que l'article est déjà assemblé et peut être prélevé du stock, s'il est disponible. Par conséquent, aucun ordre d'assemblage n'est automatiquement créé et n'est lié à la ligne commande vente. Toutefois, si une partie (ou la totalité) de la quantité n'est pas disponible, vous avez la possibilité de créer un ordre d'assemblage pour la quantité restante lorsque vous renseignez le champ **Quantité à assembler pour commande** de la ligne commande vente. De cette manière, vous pouvez assembler l'article à commander même s'il est configuré pour être assemblé pour stock par défaut.  

Une flexibilité similaire existe lorsque vous vendez des articles à assembler pour la commande et qu'une partie de la quantité est en stock, à déduire de l'ordre de assemblage. Pour plus d’informations, reportez-vous à la section [Procédure : Vente d'articles en stock dans des flux à assembler pour commande](assembly-how-to-sell-inventory-items-in-assemble-to-order-flows.md).  

> [!NOTE]  
>  Certaines règles s'appliquent au champ **Qté à expédier** sur les lignes commande vente qui contiennent une combinaison des quantités à assembler pour commande et les quantités en stock. Pour plus d'informations, voir la section Scénarios de combinaison dans [Description des processus Assembler pour commande et Assembler pour stock](assembly-assemble-to-order-or-assemble-to-stock.md).  

> [!NOTE]  
>  La procédure suivante n'inclut pas les étapes standard de commande vente que vous devez suivre avant de créer un ordre d'assemblage pour les quantités indisponibles.

## <a name="to-sell-assemble-to-order-items-and-inventory-items-together"></a>Pour vendre des articles à assembler pour commande et des articles de stock ensemble  
1.  Sur une ligne de commande vente pour un article qui est configuré pour un assemblage pour stock, entrez une quantité dans le champ **Quantité** qui est supérieure au stock. La fenêtre **Vérifier disponibilité** s'affiche. Pour plus d'informations, voir [Procédure : voir la disponibilité des articles](inventory-how-availability-overview.md). 
2.  Notez le champ **Quantité totale** (une valeur négative), que vous entrerez dans l'étape suivante.  
3.  Dans le champ **Quantité à assembler pour commande**, entrez la valeur de l'étape précédente.  
4.  Exécutez toutes les modifications dans les composants d'assemblage. Pour plus d'informations sur le paramétrage des éléments d'assemblage, voir [Procédure : Vente d'articles à assembler pour commande](assembly-how-to-sell-items-assembled-to-order.md).  
5.  Lancez la commande vente, pour la préparer au prélèvement des articles en stock et à l'assemblage des articles indisponibles. Pour plus d'informations sur les étapes d'assemblage standard, voir [Comment assembler des articles](assembly-how-to-assemble-items.md).  

> [!CAUTION]  
>  Le champ **Code emplacement** de la commande vente peut être prérempli en fonction du champ **Code empl. exp. ass. pr comm.** ou du champ **Code empl. depuis assemblage** de la fiche magasin. Dans ce cas, le champ **Code emplacement** de la ligne commande vente peut être incorrect dans cette combinaison des quantités à assembler pour commande et à assembler pour stock. Il est judicieux de consulter le champ **Code emplacement** et de s'assurer que le placement fonctionne pour toutes les quantités. Sinon, entrez les deux quantités différentes sur des lignes commande vente distinctes.  

## <a name="see-also"></a>Voir aussi  
[Gestion des assemblages](assembly-assemble-items.md)  
[Procédure : utiliser les nomenclatures](inventory-how-work-BOMs.md)  
[STOCKS ET EN-COURS](inventory-manage-inventory.md)  
[Détails de conception : gestion d'entrepôt](design-details-warehouse-management.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

