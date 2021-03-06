---
title: "Spécifier des indicateurs en couleur pour personnaliser les signaux visuels à propos de l'activité d'une pile"
description: "Configurez un indicateur en couleur sur une vignette de la pile pour fournir un signal visuel personnalisé de l'activité de la pile."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: personalize, customize
ms.date: 03/29/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 6a2b7deb2f256e3b6bf52f1b0a66fe47d049c452
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-a-colored-indicator-on-cues"></a>Procédure : configurer un indicateur coloré sur des piles
Vous pouvez configurer des piles qui apparaissent sur la page **Accueil** afin d'inclure un indicateur qui change de couleur en fonction des valeurs de données dans les piles.

L'indicateur apparait sous forme d'une barre de couleur le long de la bordure supérieure de la mosaïque Pile. Il offre un signal visuel du statut de l'activité de la pile, ce qui peut indiquer des conditions favorables ou défavorables pour inviter l'utilisateur à prendre des mesures. Par exemple, si une pile affiche les factures vente en cours, vous pouvez définir l'indicateur pour qu'il apparaisse vert (favorable) lorsque le nombre total des factures vente en cours est inférieur à 10, et apparaisse rouge (défavorable) lorsque le total est supérieur à 20.

Dans la fenêtre **Paramètres pile**, vous configurez des indicateurs pour toutes les piles disponibles dans la base de données de la société.

Pour configurer l'indicateur, vous pouvez spécifier jusqu'à deux valeurs de seuil qui définissent trois plages de valeurs de données (basse, moyenne et haute) à laquelle vous pouvez appliquer une couleur différente (ou un style différent).

## <a name="to-set-up-colored-indicators-on-cues"></a>Pour paramétrer des indicateurs colorés sur des piles
1. Sous **Activités** sur votre page **Accueil**, sélectionnez **Paramétrer piles**.  
   La fenêtre **Paramètres pile** s'affiche. La fenêtre répertorie les indicateurs actuellement paramétrés sur des piles.
2. Pour modifier un indicateur, modifiez les champs et modifiez, par exemple, les valeurs pour des seuils différents.  

Le tableau suivant répertorie les couleurs correspondant aux options des champs **Style bas de gamme**, **Style milieu de gamme** et **Style haut de gamme**.

| Option | Couleur |
| --- | --- |
| **Aucune** |Aucune couleur (même couleur que la mosaïque Pile )|
| **Favorable** |Vert |
| **Défavorable** |Rouge |
| **Ambigu** |Jaune |
| **Subordonné** |Gris |

## <a name="see-also"></a>Voir aussi
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

