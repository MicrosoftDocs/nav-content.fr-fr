---
title: "Créer des documents entrants à partir de documents"
description: "Vous pouvez créer des enregistrements de documents entrants, tels que des factures électroniques, et gérer des tâches OCR, du commerce électronique, et de l'échange de documents."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fd8eba03f98d4d667a25639c1c958edf6936b0cb
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-incoming-document-records-directly-from-documents-and-entries"></a>Créer des enregistrements document entrant directement à partir de documents et d'écritures
Vous pouvez enregistrer des documents commerciaux externes dans [!INCLUDE[d365fin](includes/d365fin_md.md)] en liant des fichiers document aux enregistrements document entrant associées. Si le document, une facture achat par exemple, n'était pas dès le départ un enregistrement document entrant, vous pouvez toujours créer et le lier à un enregistrement document entrant ultérieurement. Vous pouvez également joindre des fichiers document entrant à des documents achat et vente validés et à des écritures fournisseur, client et comptables à l'aide du récapitulatif **Fichiers document entrant** dans, par exemple, les fenêtres **Factures achat enregistrées** et **Écritures comptables fournisseur**.

Depuis les fenêtres **Plan comptable** et **Écritures comptables**, vous pouvez utiliser la fonction de recherche pour rechercher les écritures comptables pour des documents achat et vente validés qui n'ont pas d'enregistrement de document entrant, puis les lier de façon centralisée à des enregistrements existants ou en créer de nouveaux avec des fichiers joints. Pour plus d'informations, reportez-vous à [Procédure : Rechercher des enregistrements validés sans enregistrements document entrant](across-how-find-posted-documents-without-income-document-records.md).

Les procédures suivantes indiquent comment joindre un fichier à une facture achat existante qui n'a pas été créée à partir d'un enregistrement document entrant et comment joindre un fichier à une écriture comptable fournisseur. La même action permet de joindre un fichier à des documents achat ou vente validés.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-purchase-invoice"></a>Créer et lier un enregistrement document entrant à partir d'une facture achat
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Factures achat**, puis sélectionnez le lien connexe.
2. Sélectionnez la ligne de la facture achat à laquelle vous souhaitez joindre un fichier, puis sélectionnez l'action **Créer un document entrant à partir d'un fichier**.
3. Vous pouvez également sélectionner la ligne de la facture achat à laquelle vous souhaitez joindre un fichier, puis sélectionner l'action **Joindre fichier**.
4. Dans la fenêtre **Insérer un fichier**, sélectionnez le fichier qui représente le document entrant concerné, puis choisissez le bouton **Ouvrir**.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-vendor-ledger-entry"></a>Créer et lier un enregistrement document entrant à partir d'une écriture comptable fournisseur
1. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Écritures comptables fournisseur**, puis sélectionnez le lien connexe.
2. Sélectionnez une ligne d'une écriture comptable fournisseur à laquelle vous souhaitez joindre un fichier, puis sélectionnez l'action **Créer un document entrant à partir d'un fichier**.
3. Vous pouvez également sélectionner une ligne d'une une écriture comptable fournisseur à laquelle vous souhaitez joindre un fichier, puis sélectionner l'action **Joindre fichier**.
4. Dans la fenêtre **Insérer un fichier**, sélectionnez le fichier qui représente le document entrant concerné, puis choisissez le bouton **Ouvrir**.

## <a name="to-remove-a-connection-from-an-incoming-document-record-to-a-posted-document"></a>Pour supprimer la connexion d'un enregistrement document entrant à un document validé
Vous pouvez supprimer des fichiers joints de documents non validés à tout moment en supprimant l'enregistrement document entrant associé. Si le document est validé, vous devez d'abord supprimer la connexion de l'enregistrement document entrant.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Documents entrants**, puis sélectionnez le lien connexe.
2. Sélectionnez la ligne correspondant à un enregistrement document entrant lié à un document validé que vous souhaitez supprimer, puis sélectionnez **Supprimer la référence à l'enregistrement**.

La connexion au document validé est supprimée. Vous pouvez maintenant connecter un autre enregistrement document entrant au document validé, comme cela est décrit dans cette rubrique.

## <a name="see-also"></a>Voir aussi
[Traiter les documents entrants](across-process-income-documents.md)  
[Documents entrants](across-income-documents.md)  
[Achats](purchasing-manage-purchasing.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

