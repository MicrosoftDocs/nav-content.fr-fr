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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3a00334c7cd41d897b369d943b6809c256e4e4a7
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-payment-classes"></a><span data-ttu-id="401a3-103">Procédure : paramétrer des types de règlement</span><span class="sxs-lookup"><span data-stu-id="401a3-103">How to: Set Up Payment Classes</span></span>
<span data-ttu-id="401a3-104">Pour utiliser le module Gestion des paiements, vous devez paramétrer des types de règlement pour définir des types d'opération, tels que des lettres de change, des paiements électroniques ou des chèques.</span><span class="sxs-lookup"><span data-stu-id="401a3-104">To use payment management, you must set up payment classes to define operation types, such as bills of exchange, electronic payments, or checks.</span></span>  
  
### <a name="to-set-up-a-payment-class"></a><span data-ttu-id="401a3-105">Pour paramétrer un type de règlement</span><span class="sxs-lookup"><span data-stu-id="401a3-105">To set up a payment class</span></span>  
  
1.  <span data-ttu-id="401a3-106">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Paramètres bordereau paiement**, puis sélectionnez le lien approprié.</span><span class="sxs-lookup"><span data-stu-id="401a3-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Slip Setup**, and then choose the relevant link.</span></span>  
  
2.  <span data-ttu-id="401a3-107">Dans la fenêtre **Type de règlement**, sous l'onglet **Accueil**, choisissez **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="401a3-107">In the **Payment Class** window, on the **Home** tab, choose **New**.</span></span>  
  
3.  <span data-ttu-id="401a3-108">Renseignez les champs comme indiqué dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="401a3-108">Fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="401a3-109">Champ</span><span class="sxs-lookup"><span data-stu-id="401a3-109">Field</span></span>|<span data-ttu-id="401a3-110">Désignation</span><span class="sxs-lookup"><span data-stu-id="401a3-110">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="401a3-111">**Activer**</span><span class="sxs-lookup"><span data-stu-id="401a3-111">**Enable**</span></span>|<span data-ttu-id="401a3-112">Permet d'activer l'utilisation du type de règlement.</span><span class="sxs-lookup"><span data-stu-id="401a3-112">Select to enable usage of the payment class.</span></span>|  
    |<span data-ttu-id="401a3-113">**Code**</span><span class="sxs-lookup"><span data-stu-id="401a3-113">**Code**</span></span>|<span data-ttu-id="401a3-114">Code d'identification unique du type de règlement.</span><span class="sxs-lookup"><span data-stu-id="401a3-114">The unique identification code for the payment class.</span></span>|  
    |<span data-ttu-id="401a3-115">**Nom**</span><span class="sxs-lookup"><span data-stu-id="401a3-115">**Name**</span></span>|<span data-ttu-id="401a3-116">Description du type de règlement.</span><span class="sxs-lookup"><span data-stu-id="401a3-116">The payment class description.</span></span>|  
    |<span data-ttu-id="401a3-117">**N° de souche en-tête**</span><span class="sxs-lookup"><span data-stu-id="401a3-117">**Header No. Series**</span></span>|<span data-ttu-id="401a3-118">Code souche de numéros pour l'en-tête du bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="401a3-118">The number series code for the payment slip header.</span></span>|  
    |<span data-ttu-id="401a3-119">**N° de souche lignes**</span><span class="sxs-lookup"><span data-stu-id="401a3-119">**Line No. Series**</span></span>|<span data-ttu-id="401a3-120">Code souche de numéros pour les lignes du bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="401a3-120">The number series code for the payment slip lines.</span></span> <span data-ttu-id="401a3-121">Si vous laissez ce champ vide, le numéro de chaque ligne paiement est créé en se basant sur le numéro d'en-tête du bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="401a3-121">If you leave this field blank, the number for each payment line is created based on the payment header number.</span></span>|  
    |<span data-ttu-id="401a3-122">**Propositions**</span><span class="sxs-lookup"><span data-stu-id="401a3-122">**Suggestions**</span></span>|<span data-ttu-id="401a3-123">Type de proposition de règlement qui peut être créé automatiquement sur un bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="401a3-123">The type of payment proposals that can be created automatically on a payment slip.</span></span>|  
    |<span data-ttu-id="401a3-124">**Contrepassation de TVA sur encaissement**</span><span class="sxs-lookup"><span data-stu-id="401a3-124">**Unrealized VAT Reversal**</span></span>|<span data-ttu-id="401a3-125">Spécifiez la méthode pour gérer la TVA sur encaissement.</span><span class="sxs-lookup"><span data-stu-id="401a3-125">Specify the method to handle unrealized VAT.</span></span><br /><br /> <span data-ttu-id="401a3-126">Si vous sélectionnez **Lettrage**, la TVA sera réalisée lors de la validation du lettrage de la facture et du paiement.</span><span class="sxs-lookup"><span data-stu-id="401a3-126">If you select **Application**, VAT will be realized when you post the invoice application and payment application.</span></span><br /><br /> <span data-ttu-id="401a3-127">Si vous sélectionnez **En retard**, vous devez définir l'étape de règlement au cours de laquelle la TVA doit être réalisée, en sélectionnant le champ **Réaliser TVA** dans la fenêtre **Fiche étape règlement**.</span><span class="sxs-lookup"><span data-stu-id="401a3-127">If you select **Delayed**, you must define the payment step during which VAT must be realized, by selecting the **Realize VAT** field in the **Payment Step Card** window.</span></span> <span data-ttu-id="401a3-128">Pour plus d'informations, voir Réaliser TVA et Étape règlement.</span><span class="sxs-lookup"><span data-stu-id="401a3-128">For more information, see Realize VAT and Payment Step.</span></span>|  
    |<span data-ttu-id="401a3-129">**Type transfert SEPA**</span><span class="sxs-lookup"><span data-stu-id="401a3-129">**SEPA Transfer Type**</span></span>|<span data-ttu-id="401a3-130">Spécifiez le format d'exportation SEPA, **Virement** ou **Prélèvement**.</span><span class="sxs-lookup"><span data-stu-id="401a3-130">Specify the SEPA export format, either **Credit Transfer** or **Direct Debit**.</span></span>|  
  
     <span data-ttu-id="401a3-131">Pour plus d'informations, voir Type de règlement.</span><span class="sxs-lookup"><span data-stu-id="401a3-131">For more information, see Payment Class.</span></span>  
  
4.  <span data-ttu-id="401a3-132">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="401a3-132">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="401a3-133">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="401a3-133">See Also</span></span>  
 <span data-ttu-id="401a3-134">[Gestion des paiements](payment-management.md) </span><span class="sxs-lookup"><span data-stu-id="401a3-134">[Payment Management](payment-management.md) </span></span>  
 <span data-ttu-id="401a3-135">[Procédure : paramétrer des statuts règlement](how-to-set-up-payment-statuses.md) </span><span class="sxs-lookup"><span data-stu-id="401a3-135">[How to: Set Up Payment Statuses](how-to-set-up-payment-statuses.md) </span></span>  
 <span data-ttu-id="401a3-136">[Procédure : paramétrer des étapes règlement](how-to-set-up-payment-steps.md) </span><span class="sxs-lookup"><span data-stu-id="401a3-136">[How to: Set Up Payment Steps](how-to-set-up-payment-steps.md) </span></span>  
 <span data-ttu-id="401a3-137">[Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md) </span><span class="sxs-lookup"><span data-stu-id="401a3-137">[How to: Set Up Payment Addresses](how-to-set-up-payment-addresses.md) </span></span>  
 <span data-ttu-id="401a3-138">[Procédure : exporter ou importer les paramètres de configuration de la gestion des paiements](how-to-export-or-import-payment-management-setup-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="401a3-138">[How to: Export or Import Payment Management Setup Parameters](how-to-export-or-import-payment-management-setup-parameters.md) </span></span>  
 <span data-ttu-id="401a3-139">[Procédure : créer des bordereaux paiement](how-to-create-payment-slips.md) </span><span class="sxs-lookup"><span data-stu-id="401a3-139">[How to: Create Payment Slips](how-to-create-payment-slips.md) </span></span>  
 <span data-ttu-id="401a3-140">[Procédure : valider des bordereaux paiement](how-to-post-payment-slips.md) </span><span class="sxs-lookup"><span data-stu-id="401a3-140">[How to: Post Payment Slips](how-to-post-payment-slips.md) </span></span>  
 <span data-ttu-id="401a3-141">[Procédure : archiver des bordereaux paiement](how-to-archive-payment-slips.md) </span><span class="sxs-lookup"><span data-stu-id="401a3-141">[How to: Archive Payment Slips](how-to-archive-payment-slips.md) </span></span>  
 <span data-ttu-id="401a3-142">Types de règlement</span><span class="sxs-lookup"><span data-stu-id="401a3-142">Payment Class</span></span>   
 <span data-ttu-id="401a3-143">Types de règlement</span><span class="sxs-lookup"><span data-stu-id="401a3-143">Payment Class</span></span>   
 <span data-ttu-id="401a3-144">Réaliser TVA</span><span class="sxs-lookup"><span data-stu-id="401a3-144">Realize VAT</span></span>   
 <span data-ttu-id="401a3-145">Étape règlement</span><span class="sxs-lookup"><span data-stu-id="401a3-145">Payment Step</span></span>
