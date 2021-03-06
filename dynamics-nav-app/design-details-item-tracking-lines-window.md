---
title: "Détails de conception - Fenêtre Lignes traçabilité"
description: "Découvrez comment gérer le flux de numéros de série et de lot dans votre stock."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, inventory, item, tracking, serial number, lot number
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 43885603315a0e0d008dfc522ee92d221d1ba958
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-item-tracking-lines-window"></a>Détails de conception : fenêtre Lignes traçabilité
Les enregistrements de traçabilité et de réservation sont créés dans le système de réservation, et leur disponibilité est calculée de façon dynamique. Les données qui sont saisies dans la fenêtre **Lignes traçabilité** sont gérées dans une version temporaire de la table **Spécification traçabilité**. Lorsque la fenêtre est fermée, les données actives sont validées dans le tableau **Reservation Entry** et les données historiques sont validées dans le tableau **Tracking Specification**. Pour plus d'informations, voir [Détails de conception : comparaison entre écritures traçabilité actives et historiques](design-details-active-versus-historic-item-tracking-entries.md).  
  
Les recherches sur les champs **N° de série** et **N° lot** montrent une disponibilité sur la base des deux tables **Écriture comptable article** et **Ecriture réservation**, sans le filtre date. La matrice des champs de quantité figurant dans l'en\-tête de la fenêtre **Lignes traçabilité** affiche de façon dynamique les quantités et les sommes des numéros traçabilité qui sont saisis dans les lignes de la fenêtre. Les quantités doivent être égales à celles qui figurent dans la ligne document, comme l'indique la valeur **0** dans les champs **Non défini** de l'en-tête de la fenêtre.  
  
Pour coordonner le flux des numéros de série et de lot par le stock, les règles suivantes existent pour saisir des données dans la fenêtre **Lignes traçabilité** :  
  
* Pour les lignes traçabilité entrantes et sortantes, vous ne pouvez pas entrer de numéro de série, avec ou sans numéro de lot, plusieurs fois dans la même instance de la fenêtre **Lignes traçabilité**. Si vous essayez de saisir une combinaison de numéros de série ou de numéros de lot qui est déjà présente dans la fenêtre, un message d'erreur bloque la saisie de données.  
* Pour les lignes traçabilité entrantes, vous ne pouvez pas valider le document connexe si un article de la même variante et avec le même numéro de série est déjà en stock. Si vous essayez de valider une ligne positive pour un article de stock avec une variante et un n° de série identiques, un message d'erreur bloque la validation. Toutefois, pour les lignes traçabilité entrantes et sortantes sur les documents en cours, vous pouvez prendre la même combinaison de numéros de série ou de numéros de lot qui se rapportent à différentes lignes document origine, c.\-à\-d., existant dans différentes instances de la fenêtre **Lignes traçabilité** jusqu'à ce que le document connexe soit validé.  
* Si l'article est configuré pour la traçabilité spécifique au numéro de série ou de lot, vous ne pouvez pas valider une ligne de document sortant sauf si un article avec le numéro de série ou de lot défini apparaît dans le stock. Si vous essayez de valider une ligne de document sortant pour un article avec un n° de série lot non présent dans le stock, un message d'erreur bloque la validation.  
  
Les règles de saisie des données de la fenêtre **Lignes traçabilité** prennent également en charge les principes de couplage qui gouvernent le chaînage, la planification et la réservation. Pour plus d'informations, reportez\-vous à [Détails de conception : traçabilité et réservations](design-details-item-tracking-and-planning.md).  
  
## <a name="see-also"></a>Voir aussi  
[Détails de conception : traçabilité](design-details-item-tracking.md)
