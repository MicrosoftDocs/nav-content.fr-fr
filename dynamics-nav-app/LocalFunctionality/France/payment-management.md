---
title: Gestion des paiements
description: "Vous pouvez gérer des lettres de change, des paiements électroniques et des paiements fournisseur à l'aide de la fonction de gestion des paiements."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: bed82ca36c483a70f9b5b1e5ac079bd2e8d5b6ac
ms.contentlocale: fr-fr
ms.lasthandoff: 10/26/2017

---
# <a name="payment-management"></a>Gestion des paiements
[!INCLUDE[navnow](../../includes/navnow_md.md)] vous permet de gérer des lettres de change, des paiements électroniques et des paiements fournisseur à l'aide de la fonction de gestion des paiements.  

Vous pouvez gérer les paiements fournisseur et client à l'aide des bordereaux paiement. Avant de créer un bordereau paiement, vous devez définir les paramétrages suivants :  

- Type de règlement – Type de règlement que vous souhaitez effectuer, comme par exemple, une lettre de change, un paiement électronique ou un chèque. Pour plus d'informations, voir [Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md).  

- Statut règlement – Niveau de progression d'un document règlement. Vous devez définir un ensemble de statuts pour chaque type de règlement. Pour plus d'informations, voir [Procédure : paramétrer des statuts règlement](how-to-set-up-payment-statuses.md).  

- Étapes de règlement – Paiement qui est exécuté à un moment spécifié. Une fois l'étape de règlement exécutée, vous pouvez passer d'un statut du document règlement à un autre. Si une étape nécessite la validation d'enregistrements débiteurs ou créditeurs, vous devez définir d'autres actions dans la table **Etape règlement : Comptabilisation**. Pour plus d'informations, voir [Procédure : paramétrer des étapes de règlement](how-to-set-up-payment-steps.md).  

- Adresse de règlement pour les fournisseurs et les clients – Adresse qui est utilisée pour un fournisseur ou un client au moment du règlement. L'adresse de règlement peut être différente de celle par défaut du client ou du fournisseur. Pour plus d'informations, voir [Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md).  

Vous pouvez également transférer vos informations de configuration de la gestion des paiements vers un disque externe afin de pouvoir utiliser les mêmes paramètres pour une autre société présentant les mêmes exigences. Vous pouvez exporter les données de paiement dans les formats suivants :  

- ETEBAC – Permet de créer une remise de lettre de change.  
- Prélèvement – Permet de créer un prélèvement de paiement client (débit direct).  
- Transfert – Permet de créer un transfert de paiement fournisseur (transfert de crédit).  

## <a name="managing-payment-slips-and-files"></a>Gestion des bordereaux et des fichiers paiement  
Vous pouvez créer des bordereaux paiement pour gérer les paiements client et fournisseur. Après avoir créé le bordereau paiement, vous devez le valider.  

Ces bordereaux paiement peuvent être convertis en fichiers de paiement, qui peuvent être envoyés à la banque par voie électronique.  

Pour plus d'informations, consultez [Procédure : créer des bordereaux paiement](how-to-create-payment-slips.md).  

## <a name="archiving-payment-slips"></a>Archivage des bordereaux paiement  
Vous pouvez séparer un bordereau paiement entièrement traité des bordereaux paiement actifs en l'archivant. Vous pouvez archiver un bordereau paiement manuellement ou vous pouvez archiver un lot de bordereaux automatiquement. Pour plus d'informations, voir [Procédure : archiver des bordereaux paiement](how-to-archive-payment-slips.md).  

## <a name="see-also"></a>Voir aussi  
 [Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md)   
 [Procédure : paramétrer des statuts règlement](how-to-set-up-payment-statuses.md)   
 [Procédure : paramétrer des étapes règlement](how-to-set-up-payment-steps.md)   
 [Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md)   
 [Procédure : créer des bordereaux paiement](how-to-create-payment-slips.md)   
 [Procédure : valider des bordereaux paiement](how-to-post-payment-slips.md)   
 [Procédure : archiver des bordereaux paiement](how-to-archive-payment-slips.md)   
 [Procédure : exporter ou importer les paramètres de configuration de la gestion des paiements](how-to-export-or-import-payment-management-setup-parameters.md)   
 [Fonctionnalité locale, France](france-local-functionality.md)

