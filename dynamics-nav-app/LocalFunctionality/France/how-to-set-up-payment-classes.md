---
title: "Procédure de paramétrage des types de règlement"
description: "Pour utiliser le module Gestion des paiements, vous devez paramétrer des types de règlement pour définir des types d'opération, tels que des lettres de change, des paiements électroniques ou des chèques."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 549b0a4d3fdb789988bcb3f971c7b0b6c8f6893e
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-payment-classes"></a>Procédure : paramétrer des types de règlement
Pour utiliser le module Gestion des paiements, vous devez paramétrer des types de règlement pour définir des types d'opération, tels que des lettres de change, des paiements électroniques ou des chèques.  

## <a name="to-set-up-a-payment-class"></a>Pour paramétrer un type de règlement  

1.  Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Paramètres bordereau paiement**, puis sélectionnez le lien approprié.  
2.  Dans la fenêtre **Type règlement**, sélectionnez l'action **Nouveau**.  
3.  Renseignez les champs comme indiqué dans le tableau suivant.  

    |Champ|Désignation|  
    |---------------------------------|---------------------------------------|  
    |**Activer**|Permet d'activer l'utilisation du type de règlement.|  
    |**Code**|Code d'identification unique du type de règlement.|  
    |**Nom**|Description du type de règlement.|  
    |**N° de souche en-tête**|Code souche de numéros pour l'en-tête du bordereau paiement.|  
    |**N° de souche lignes**|Code souche de numéros pour les lignes du bordereau paiement. Si vous laissez ce champ vide, le numéro de chaque ligne paiement est créé en se basant sur le numéro d'en-tête du bordereau paiement.|  
    |**Propositions**|Type de proposition de règlement qui peut être créé automatiquement sur un bordereau paiement.|  
    |**Contrepassation de TVA sur encaissement**|Spécifiez la méthode pour gérer la TVA sur encaissement.<br /><br /> Si vous sélectionnez **Lettrage**, la TVA sera réalisée lors de la validation du lettrage de la facture et du paiement.<br /><br /> Si vous sélectionnez **En retard**, vous devez définir l'étape de règlement au cours de laquelle la TVA doit être réalisée, en sélectionnant le champ **Réaliser TVA** dans la fenêtre **Fiche étape règlement**. Pour plus d'informations, voir Réaliser TVA et Étape règlement.|  
    |**Type transfert SEPA**|Spécifiez le format d'exportation SEPA, **Virement** ou **Prélèvement**.|  

4.  Cliquez sur le bouton **OK**.  

## <a name="see-also"></a>Voir aussi  
 [Gestion des paiements](payment-management.md)   
 [Procédure : paramétrer des statuts règlement](how-to-set-up-payment-statuses.md)   
 [Procédure : paramétrer des étapes règlement](how-to-set-up-payment-steps.md)   
 [Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md)   
 [Procédure : exporter ou importer les paramètres de configuration de la gestion des paiements](how-to-export-or-import-payment-management-setup-parameters.md)   
 [Procédure : créer des bordereaux paiement](how-to-create-payment-slips.md)   
 [Procédure : valider des bordereaux paiement](how-to-post-payment-slips.md)   
 [Procédure : archiver des bordereaux paiement](how-to-archive-payment-slips.md)

