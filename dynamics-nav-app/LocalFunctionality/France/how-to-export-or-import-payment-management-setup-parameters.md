---
title: "Procédure d'exportation ou d'importation des paramètres de configuration de la gestion des paiements"
description: "Vous pouvez exporter ou importer les paramètres de configuration de la gestion des paiements vers un disque externe afin de pouvoir utiliser les mêmes paramètres pour une autre société présentant les mêmes exigences."
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
ms.openlocfilehash: 85cc8388a40de928707b54026b9c3badf4d586c3
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-export-or-import-payment-management-setup-parameters"></a>Procédure : exporter ou importer les paramètres de configuration de la gestion des paiements
Vous pouvez exporter ou importer les paramètres de configuration de la gestion des paiements vers un disque externe afin de pouvoir utiliser les mêmes paramètres pour une autre société présentant les mêmes exigences.  

Vous pouvez utiliser les formats suivants pour exporter les paramètres de configuration de la gestion des paiements :  

- ETEBAC (XMLport 10860) – Permet de créer une remise de lettre de change.  
- Prélèvement (XMLport 10861) – Permet de créer un prélèvement de paiement client (débit direct).  
- Transfert (XMLport 10862) – Permet de créer un transfert de paiement fournisseur (transfert de crédit).  

Vous pouvez sélectionner ces formats lorsque vous configurez le statut de règlement pour votre type de règlement. Pour plus d'informations, voir [Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md).  

## <a name="to-export-or-import-payment-management-setup-parameters"></a>Pour exporter ou importer les paramètres de configuration de la gestion des paiements  

1.  Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Paramètres bordereau paiement**, puis sélectionnez le lien approprié.  
2.  Dans la fenêtre **Type règlement**, sélectionnez l'action **Exporter paramètres**.  

    Pour importer un paramètre, choisissez l'action **Importer paramètres**, sélectionnez le fichier, puis choisissez le bouton **Ouvrir**.  

3.  Choisissez le bouton **Enregistrer** pour ouvrir la fenêtre **Enregistrer sous** et accéder à l'emplacement où le fichier doit être enregistré.  
4.  Cliquez sur le bouton **OK**.  

## <a name="see-also"></a>Voir aussi  
 [Gestion des paiements](payment-management.md)   
 [Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md)   
 [Procédure : paramétrer des statuts règlement](how-to-set-up-payment-statuses.md)   
 [Procédure : paramétrer des étapes règlement](how-to-set-up-payment-steps.md)   
 [Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md)   
 [Procédure : créer des bordereaux paiement](how-to-create-payment-slips.md)   
 [Procédure : archiver des bordereaux paiement](how-to-archive-payment-slips.md)

