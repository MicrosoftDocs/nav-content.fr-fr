---
title: "Procédure de paramétrage des statuts règlement"
description: "Pour utiliser le module de gestion des paiements, vous devez paramétrer des statuts règlement pour définir les niveaux de progression des documents règlement. Vous devez définir un ensemble de statuts pour chaque type de règlement."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 051d30fab662e117790ce33113f137934f98b8e3
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-payment-statuses"></a>Procédure : paramétrer des statuts règlement
Pour utiliser le module de gestion des paiements, vous devez paramétrer des statuts règlement pour définir les niveaux de progression des documents règlement. Vous devez définir un ensemble de statuts pour chaque type de règlement. Pour plus d'informations, voir [Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md).  

## <a name="to-set-up-payment-statuses"></a>Pour paramétrer des statuts règlement  

1.  Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Paramètres bordereau paiement**, puis sélectionnez le lien associé.  
2.  Sélectionnez un type de règlement, puis cliquez sur **Statut**.  
3.  Dans la fenêtre **Statut règlement**, sélectionnez l'action **Nouveau**.  
4.  Renseignez les champs comme indiqué dans le tableau suivant.  

    |Champ|Désignation|  
    |---------------------------------|---------------------------------------|  
    |**Nom**|Description du statut de règlement.|  
    |**RIB**|Permet d'indiquer que les informations relatives au Relevé d'Identité Bancaire (RIB) du client ou du fournisseur doivent être affichées dans les lignes paiement. Les informations du RIB incluent le code établissement, le code agence, le numéro de compte bancaire, le nom de la banque, la clé RIB et la clé de vérification.|  
    |**Consultation**|Permet d'indiquer que les lignes document de règlement qui ont atteint ce statut peuvent être modifiées et affichées dans la fenêtre **Afficher/Éditer ligne paiement**.<br /><br /> Pour plus d'informations, voir Afficher/Éditer ligne paiement.|  
    |**ReportMenu**|Permet d'indiquer que les documents de règlement qui ont atteint ce statut peuvent être imprimés.|  
    |**Montant**|Permet d'afficher le montant dans les lignes règlement.|  
    |**Paiement en cours**|Permet d'indiquer que toutes les lignes de facturation et paiement ayant ce statut doivent être prises en compte lors du calcul des paiements en cours.|  
    |**Archivage autorisé**|Permet d'indiquer que les bordereaux avec ce statut peuvent être archivés.|  

5.  Cliquez sur le bouton **OK**.  

## <a name="see-also"></a>Voir aussi  
 [Gestion des paiements](payment-management.md)   
 [Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md)   
 [Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md)   
 [Procédure : créer des bordereaux paiement](how-to-create-payment-slips.md)   
 [Procédure : valider des bordereaux paiement](how-to-post-payment-slips.md)   
 [Procédure : archiver des bordereaux paiement](how-to-archive-payment-slips.md)   
 [Procédure : exporter ou importer les paramètres de configuration de la gestion des paiements](how-to-export-or-import-payment-management-setup-parameters.md)

