---
title: "Procédure de paramétrage des types de règlement"
description: "Pour utiliser le module Gestion des paiements, vous devez paramétrer des types de règlement pour définir des types d'opération, tels que des lettres de change, des paiements électroniques ou des chèques."
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
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 5288f930e175456ad2a302f5eb80d42d0eae9978
ms.contentlocale: fr-fr
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-payment-classes"></a><span data-ttu-id="89229-103">Procédure : paramétrer des types de règlement</span><span class="sxs-lookup"><span data-stu-id="89229-103">How to: Set Up Payment Classes</span></span>
<span data-ttu-id="89229-104">Pour utiliser le module Gestion des paiements, vous devez paramétrer des types de règlement pour définir des types d'opération, tels que des lettres de change, des paiements électroniques ou des chèques.</span><span class="sxs-lookup"><span data-stu-id="89229-104">To use payment management, you must set up payment classes to define operation types, such as bills of exchange, electronic payments, or checks.</span></span>  

## <a name="to-set-up-a-payment-class"></a><span data-ttu-id="89229-105">Pour paramétrer un type de règlement</span><span class="sxs-lookup"><span data-stu-id="89229-105">To set up a payment class</span></span>  

1.  <span data-ttu-id="89229-106">Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Paramètres bordereau paiement**, puis sélectionnez le lien approprié.</span><span class="sxs-lookup"><span data-stu-id="89229-106">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Slip Setup**, and then choose the relevant link.</span></span>  
2.  <span data-ttu-id="89229-107">Dans la fenêtre **Type règlement**, sélectionnez l'action **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="89229-107">In the **Payment Class** window, choose the **New** action.</span></span>  
3.  <span data-ttu-id="89229-108">Renseignez les champs comme indiqué dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="89229-108">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="89229-109">Champ</span><span class="sxs-lookup"><span data-stu-id="89229-109">Field</span></span>|<span data-ttu-id="89229-110">Désignation</span><span class="sxs-lookup"><span data-stu-id="89229-110">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="89229-111">**Activer**</span><span class="sxs-lookup"><span data-stu-id="89229-111">**Enable**</span></span>|<span data-ttu-id="89229-112">Permet d'activer l'utilisation du type de règlement.</span><span class="sxs-lookup"><span data-stu-id="89229-112">Select to enable usage of the payment class.</span></span>|  
    |<span data-ttu-id="89229-113">**Code**</span><span class="sxs-lookup"><span data-stu-id="89229-113">**Code**</span></span>|<span data-ttu-id="89229-114">Code d'identification unique du type de règlement.</span><span class="sxs-lookup"><span data-stu-id="89229-114">The unique identification code for the payment class.</span></span>|  
    |<span data-ttu-id="89229-115">**Nom**</span><span class="sxs-lookup"><span data-stu-id="89229-115">**Name**</span></span>|<span data-ttu-id="89229-116">Description du type de règlement.</span><span class="sxs-lookup"><span data-stu-id="89229-116">The payment class description.</span></span>|  
    |<span data-ttu-id="89229-117">**N° de souche en-tête**</span><span class="sxs-lookup"><span data-stu-id="89229-117">**Header No. Series**</span></span>|<span data-ttu-id="89229-118">Code souche de numéros pour l'en-tête du bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="89229-118">The number series code for the payment slip header.</span></span>|  
    |<span data-ttu-id="89229-119">**N° de souche lignes**</span><span class="sxs-lookup"><span data-stu-id="89229-119">**Line No. Series**</span></span>|<span data-ttu-id="89229-120">Code souche de numéros pour les lignes du bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="89229-120">The number series code for the payment slip lines.</span></span> <span data-ttu-id="89229-121">Si vous laissez ce champ vide, le numéro de chaque ligne paiement est créé en se basant sur le numéro d'en-tête du bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="89229-121">If you leave this field blank, the number for each payment line is created based on the payment header number.</span></span>|  
    |<span data-ttu-id="89229-122">**Propositions**</span><span class="sxs-lookup"><span data-stu-id="89229-122">**Suggestions**</span></span>|<span data-ttu-id="89229-123">Type de proposition de règlement qui peut être créé automatiquement sur un bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="89229-123">The type of payment proposals that can be created automatically on a payment slip.</span></span>|  
    |<span data-ttu-id="89229-124">**Contrepassation de TVA sur encaissement**</span><span class="sxs-lookup"><span data-stu-id="89229-124">**Unrealized VAT Reversal**</span></span>|<span data-ttu-id="89229-125">Spécifiez la méthode pour gérer la TVA sur encaissement.</span><span class="sxs-lookup"><span data-stu-id="89229-125">Specify the method to handle unrealized VAT.</span></span><br /><br /> <span data-ttu-id="89229-126">Si vous sélectionnez **Lettrage**, la TVA sera réalisée lors de la validation du lettrage de la facture et du paiement.</span><span class="sxs-lookup"><span data-stu-id="89229-126">If you select **Application**, VAT will be realized when you post the invoice application and payment application.</span></span><br /><br /> <span data-ttu-id="89229-127">Si vous sélectionnez **En retard**, vous devez définir l'étape de règlement au cours de laquelle la TVA doit être réalisée, en sélectionnant le champ **Réaliser TVA** dans la fenêtre **Fiche étape règlement**.</span><span class="sxs-lookup"><span data-stu-id="89229-127">If you select **Delayed**, you must define the payment step during which VAT must be realized, by selecting the **Realize VAT** field in the **Payment Step Card** window.</span></span> <span data-ttu-id="89229-128">Pour plus d'informations, voir Réaliser TVA et Étape règlement.</span><span class="sxs-lookup"><span data-stu-id="89229-128">For more information, see Realize VAT and Payment Step.</span></span>|  
    |<span data-ttu-id="89229-129">**Type transfert SEPA**</span><span class="sxs-lookup"><span data-stu-id="89229-129">**SEPA Transfer Type**</span></span>|<span data-ttu-id="89229-130">Spécifiez le format d'exportation SEPA, **Virement** ou **Prélèvement**.</span><span class="sxs-lookup"><span data-stu-id="89229-130">Specify the SEPA export format, either **Credit Transfer** or **Direct Debit**.</span></span>|  

4.  <span data-ttu-id="89229-131">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="89229-131">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="89229-132">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="89229-132">See Also</span></span>  
 <span data-ttu-id="89229-133">[Gestion des paiements](payment-management.md) </span><span class="sxs-lookup"><span data-stu-id="89229-133">[Payment Management](payment-management.md) </span></span>  
 <span data-ttu-id="89229-134">[Procédure : paramétrer des statuts règlement](how-to-set-up-payment-statuses.md) </span><span class="sxs-lookup"><span data-stu-id="89229-134">[How to: Set Up Payment Statuses](how-to-set-up-payment-statuses.md) </span></span>  
 <span data-ttu-id="89229-135">[Procédure : paramétrer des étapes règlement](how-to-set-up-payment-steps.md) </span><span class="sxs-lookup"><span data-stu-id="89229-135">[How to: Set Up Payment Steps](how-to-set-up-payment-steps.md) </span></span>  
 <span data-ttu-id="89229-136">[Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md) </span><span class="sxs-lookup"><span data-stu-id="89229-136">[How to: Set Up Payment Addresses](how-to-set-up-payment-addresses.md) </span></span>  
 <span data-ttu-id="89229-137">[Procédure : exporter ou importer les paramètres de configuration de la gestion des paiements](how-to-export-or-import-payment-management-setup-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="89229-137">[How to: Export or Import Payment Management Setup Parameters](how-to-export-or-import-payment-management-setup-parameters.md) </span></span>  
 <span data-ttu-id="89229-138">[Procédure : créer des bordereaux paiement](how-to-create-payment-slips.md) </span><span class="sxs-lookup"><span data-stu-id="89229-138">[How to: Create Payment Slips](how-to-create-payment-slips.md) </span></span>  
 <span data-ttu-id="89229-139">[Procédure : valider des bordereaux paiement](how-to-post-payment-slips.md) </span><span class="sxs-lookup"><span data-stu-id="89229-139">[How to: Post Payment Slips](how-to-post-payment-slips.md) </span></span>  
 [<span data-ttu-id="89229-140">Procédure : archiver des bordereaux paiement</span><span class="sxs-lookup"><span data-stu-id="89229-140">How to: Archive Payment Slips</span></span>](how-to-archive-payment-slips.md)

