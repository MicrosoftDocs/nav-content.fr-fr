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
# <a name="how-to-export-or-import-payment-management-setup-parameters"></a><span data-ttu-id="72c59-103">Procédure : exporter ou importer les paramètres de configuration de la gestion des paiements</span><span class="sxs-lookup"><span data-stu-id="72c59-103">How to: Export or Import Payment Management Setup Parameters</span></span>
<span data-ttu-id="72c59-104">Vous pouvez exporter ou importer les paramètres de configuration de la gestion des paiements vers un disque externe afin de pouvoir utiliser les mêmes paramètres pour une autre société présentant les mêmes exigences.</span><span class="sxs-lookup"><span data-stu-id="72c59-104">You can export or import payment management setup parameters to an external disk so that you can use the same parameters for another company with similar requirements.</span></span>  

<span data-ttu-id="72c59-105">Vous pouvez utiliser les formats suivants pour exporter les paramètres de configuration de la gestion des paiements :</span><span class="sxs-lookup"><span data-stu-id="72c59-105">You can use the following formats to export payment setup parameters:</span></span>  

- <span data-ttu-id="72c59-106">ETEBAC (XMLport 10860) – Permet de créer une remise de lettre de change.</span><span class="sxs-lookup"><span data-stu-id="72c59-106">ETEBAC (XMLport 10860) – To create a bill of exchange remittance.</span></span>  
- <span data-ttu-id="72c59-107">Prélèvement (XMLport 10861) – Permet de créer un prélèvement de paiement client (débit direct).</span><span class="sxs-lookup"><span data-stu-id="72c59-107">Withdraw (XMLport 10861) – To create a customer payment withdrawal (direct debit).</span></span>  
- <span data-ttu-id="72c59-108">Transfert (XMLport 10862) – Permet de créer un transfert de paiement fournisseur (transfert de crédit).</span><span class="sxs-lookup"><span data-stu-id="72c59-108">Transfer (XMLport 10862) – To create a vendor payment transfer (credit transfer).</span></span>  

<span data-ttu-id="72c59-109">Vous pouvez sélectionner ces formats lorsque vous configurez le statut de règlement pour votre type de règlement.</span><span class="sxs-lookup"><span data-stu-id="72c59-109">You can select these formats when you set up the payment status for your payment class.</span></span> <span data-ttu-id="72c59-110">Pour plus d'informations, voir [Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md).</span><span class="sxs-lookup"><span data-stu-id="72c59-110">For more information, see [How to: Set Up Payment Classes](how-to-set-up-payment-classes.md).</span></span>  

## <a name="to-export-or-import-payment-management-setup-parameters"></a><span data-ttu-id="72c59-111">Pour exporter ou importer les paramètres de configuration de la gestion des paiements</span><span class="sxs-lookup"><span data-stu-id="72c59-111">To export or import payment management setup parameters</span></span>  

1.  <span data-ttu-id="72c59-112">Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Paramètres bordereau paiement**, puis sélectionnez le lien approprié.</span><span class="sxs-lookup"><span data-stu-id="72c59-112">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Slip Setup**, and then choose the relevant link.</span></span>  
2.  <span data-ttu-id="72c59-113">Dans la fenêtre **Type règlement**, sélectionnez l'action **Exporter paramètres**.</span><span class="sxs-lookup"><span data-stu-id="72c59-113">In the **Payment Class** window, choose the **Export Parameters** action.</span></span>  

    <span data-ttu-id="72c59-114">Pour importer un paramètre, choisissez l'action **Importer paramètres**, sélectionnez le fichier, puis choisissez le bouton **Ouvrir**.</span><span class="sxs-lookup"><span data-stu-id="72c59-114">To import a parameter, choose the **Import Parameter** action, select the file, and then choose the **Open** button.</span></span>  

3.  <span data-ttu-id="72c59-115">Choisissez le bouton **Enregistrer** pour ouvrir la fenêtre **Enregistrer sous** et accéder à l'emplacement où le fichier doit être enregistré.</span><span class="sxs-lookup"><span data-stu-id="72c59-115">Choose the **Save** button to open the **Save As** window and navigate to the location where the file should be saved.</span></span>  
4.  <span data-ttu-id="72c59-116">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="72c59-116">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="72c59-117">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="72c59-117">See Also</span></span>  
 <span data-ttu-id="72c59-118">[Gestion des paiements](payment-management.md) </span><span class="sxs-lookup"><span data-stu-id="72c59-118">[Payment Management](payment-management.md) </span></span>  
 <span data-ttu-id="72c59-119">[Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md) </span><span class="sxs-lookup"><span data-stu-id="72c59-119">[How to: Set Up Payment Classes](how-to-set-up-payment-classes.md) </span></span>  
 <span data-ttu-id="72c59-120">[Procédure : paramétrer des statuts règlement](how-to-set-up-payment-statuses.md) </span><span class="sxs-lookup"><span data-stu-id="72c59-120">[How to: Set Up Payment Statuses](how-to-set-up-payment-statuses.md) </span></span>  
 <span data-ttu-id="72c59-121">[Procédure : paramétrer des étapes règlement](how-to-set-up-payment-steps.md) </span><span class="sxs-lookup"><span data-stu-id="72c59-121">[How to: Set Up Payment Steps](how-to-set-up-payment-steps.md) </span></span>  
 <span data-ttu-id="72c59-122">[Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md) </span><span class="sxs-lookup"><span data-stu-id="72c59-122">[How to: Set Up Payment Addresses](how-to-set-up-payment-addresses.md) </span></span>  
 <span data-ttu-id="72c59-123">[Procédure : créer des bordereaux paiement](how-to-create-payment-slips.md) </span><span class="sxs-lookup"><span data-stu-id="72c59-123">[How to: Create Payment Slips](how-to-create-payment-slips.md) </span></span>  
 [<span data-ttu-id="72c59-124">Procédure : archiver des bordereaux paiement</span><span class="sxs-lookup"><span data-stu-id="72c59-124">How to: Archive Payment Slips</span></span>](how-to-archive-payment-slips.md)

