---
title: "Procédure de création des bordereaux paiement"
description: "Vous pouvez créer des bordereaux paiement pour gérer les paiements fournisseur et client. Avant de créer des bordereaux paiement, vous devez paramétrer des types de règlement."
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
ms.openlocfilehash: b3e0f7435e5e1afdbbb410e99e7b5481f6a54640
ms.contentlocale: fr-fr
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-create-payment-slips"></a><span data-ttu-id="5efb0-104">Procédure : créer des bordereaux paiement</span><span class="sxs-lookup"><span data-stu-id="5efb0-104">How to: Create Payment Slips</span></span>
<span data-ttu-id="5efb0-105">Vous pouvez créer des bordereaux paiement pour gérer les paiements fournisseur et client.</span><span class="sxs-lookup"><span data-stu-id="5efb0-105">You can create payments slips to manage vendor and customer payments.</span></span> <span data-ttu-id="5efb0-106">Avant de créer des bordereaux paiement, vous devez paramétrer des types de règlement.</span><span class="sxs-lookup"><span data-stu-id="5efb0-106">Before you create payment slips, you must set up payment classes.</span></span> <span data-ttu-id="5efb0-107">Pour plus d'informations, voir [Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md).</span><span class="sxs-lookup"><span data-stu-id="5efb0-107">For more information, see [How to: Set Up Payment Classes](how-to-set-up-payment-classes.md).</span></span>  

<span data-ttu-id="5efb0-108">La procédure suivante décrit comment créer des bordereaux paiement pour les règlements fournisseur, mais les mêmes étapes s'appliquent également à la création des bordereaux paiement pour les règlements client.</span><span class="sxs-lookup"><span data-stu-id="5efb0-108">The following procedure describes how to create payment slips for vendor payments, but the same steps also apply to creating payment slips for customer payments.</span></span>  

## <a name="to-create-a-payment-slip-for-vendors"></a><span data-ttu-id="5efb0-109">Pour créer un bordereau de paiement pour les fournisseurs</span><span class="sxs-lookup"><span data-stu-id="5efb0-109">To create a payment slip for vendors</span></span>  

1.  <span data-ttu-id="5efb0-110">Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Bordereaux paiement**, puis sélectionnez le lien approprié.</span><span class="sxs-lookup"><span data-stu-id="5efb0-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Slips**, and then choose the relevant link.</span></span>  
2.  <span data-ttu-id="5efb0-111">Sélectionnez l'action **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-111">Choose the **New** action.</span></span>  
3.  <span data-ttu-id="5efb0-112">Dans la fenêtre **Bordereau paiement**, sélectionnez un champ pour ouvrir la fenêtre **Liste des types de règlement**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-112">In the **Payment Slip** window, choose a field to open the **Payment Class List** window.</span></span>  
4.  <span data-ttu-id="5efb0-113">Sélectionnez un type de règlement, puis choisissez le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-113">Select a payment class, and then choose the **OK** button.</span></span>  
5.  <span data-ttu-id="5efb0-114">Sous le raccourci **Général**, renseignez les champs comme indiqué dans le tableau ci-dessous.</span><span class="sxs-lookup"><span data-stu-id="5efb0-114">On the **General** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="5efb0-115">Champ</span><span class="sxs-lookup"><span data-stu-id="5efb0-115">Field</span></span>|<span data-ttu-id="5efb0-116">Désignation</span><span class="sxs-lookup"><span data-stu-id="5efb0-116">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="5efb0-117">**Code devise**</span><span class="sxs-lookup"><span data-stu-id="5efb0-117">**Currency Code**</span></span>|<span data-ttu-id="5efb0-118">Spécifiez le code devise à utiliser pour les lignes paiement.</span><span class="sxs-lookup"><span data-stu-id="5efb0-118">Specify the currency code to be used for the payment lines.</span></span>|  
    |<span data-ttu-id="5efb0-119">**Date de validation**</span><span class="sxs-lookup"><span data-stu-id="5efb0-119">**Posting Date**</span></span>|<span data-ttu-id="5efb0-120">Spécifiez une date comptabilisation.</span><span class="sxs-lookup"><span data-stu-id="5efb0-120">Specify the posting date.</span></span>|  
    |<span data-ttu-id="5efb0-121">**Date document**</span><span class="sxs-lookup"><span data-stu-id="5efb0-121">**Document Date**</span></span>|<span data-ttu-id="5efb0-122">Spécifiez la date du document.</span><span class="sxs-lookup"><span data-stu-id="5efb0-122">Specify the document date.</span></span>|  
    |<span data-ttu-id="5efb0-123">**Montant DS**</span><span class="sxs-lookup"><span data-stu-id="5efb0-123">**Amount (LCY)**</span></span>|<span data-ttu-id="5efb0-124">Montant total des lignes paiement.</span><span class="sxs-lookup"><span data-stu-id="5efb0-124">The total amount from the payment lines.</span></span> <span data-ttu-id="5efb0-125">Ce champ est mis à jour automatiquement à chaque modification des montants nets des lignes.</span><span class="sxs-lookup"><span data-stu-id="5efb0-125">This field is updated automatically when the net line amounts are changed.</span></span><br /><br />|  

6.  <span data-ttu-id="5efb0-126">Sous le raccourci **Lignes**, renseignez les champs comme indiqué dans le tableau ci-dessous.</span><span class="sxs-lookup"><span data-stu-id="5efb0-126">On the **Lines** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="5efb0-127">Champ</span><span class="sxs-lookup"><span data-stu-id="5efb0-127">Field</span></span>|<span data-ttu-id="5efb0-128">Désignation</span><span class="sxs-lookup"><span data-stu-id="5efb0-128">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="5efb0-129">**Type compte**</span><span class="sxs-lookup"><span data-stu-id="5efb0-129">**Account Type**</span></span>|<span data-ttu-id="5efb0-130">Type de compte sur lequel la ligne bordereau est validée.</span><span class="sxs-lookup"><span data-stu-id="5efb0-130">The account type to which the payment line is posted.</span></span>|  
    |<span data-ttu-id="5efb0-131">**N° compte**</span><span class="sxs-lookup"><span data-stu-id="5efb0-131">**Account No.**</span></span>|<span data-ttu-id="5efb0-132">Numéro d'identification unique pour le compte sur lequel l'écriture est validée.</span><span class="sxs-lookup"><span data-stu-id="5efb0-132">The unique identification number for the account to which the entry will be posted.</span></span>|  

7.  <span data-ttu-id="5efb0-133">Dans le champ **Code compte bancaire**, sélectionnez un nom bancaire dans la liste, puis choisissez **Avancé**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-133">In the **Bank Account Code** field, select a bank name from the list, and then choose **Advanced**.</span></span>  
8.  <span data-ttu-id="5efb0-134">Éventuellement, pour SEPA, dans la fenêtre **Sélectionner – Liste des comptes fournisseur**, puis cliquez sur l'action **Modifier**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-134">Optionally, for SEPA, in the **Select – Vendor Account List** window, and then choose the **Edit** action.</span></span>  

    <span data-ttu-id="5efb0-135">Renseignez les champs suivants, si nécessaire :</span><span class="sxs-lookup"><span data-stu-id="5efb0-135">Fill in the following fields if needed:</span></span>  

    - <span data-ttu-id="5efb0-136">**Code pays/région**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-136">**Country/Region Code**.</span></span> <span data-ttu-id="5efb0-137">Dans la liste, choisissez **Avancé**, puis assurez-vous que la case à cocher **SEPA autorisé** est sélectionnée pour le code que vous sélectionnez.</span><span class="sxs-lookup"><span data-stu-id="5efb0-137">In the list, choose **Advanced**, and make sure that the **SEPA Allowed** check box is selected for the code that you select.</span></span>  
    - <span data-ttu-id="5efb0-138">**Code SWIFT**</span><span class="sxs-lookup"><span data-stu-id="5efb0-138">**Swift Code**</span></span>  
    - <span data-ttu-id="5efb0-139">**IBAN**</span><span class="sxs-lookup"><span data-stu-id="5efb0-139">**IBAN**</span></span>  

    <span data-ttu-id="5efb0-140">Cliquez sur le bouton **OK** pour fermer la fenêtre.</span><span class="sxs-lookup"><span data-stu-id="5efb0-140">Choose the **OK** button to close the window.</span></span>  

9. <span data-ttu-id="5efb0-141">Éventuellement, pour SEPA, choisissez l'action **Relevé d'identité bancaire**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-141">Optionally, for SEPA, choose the **Header RIB** action.</span></span> <span data-ttu-id="5efb0-142">Sélectionnez le champ **Code pays/région banque**, puis choisissez **Avancé**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-142">Select the **Bank Country/Region Code** field, and then choose **Advanced**.</span></span> <span data-ttu-id="5efb0-143">Assurez-vous que la case à cocher **SEPA autorisé** est sélectionnée.</span><span class="sxs-lookup"><span data-stu-id="5efb0-143">Make sure the **SEPA Allowed** check box is selected.</span></span> <span data-ttu-id="5efb0-144">Assurez-vous également que les champs **IBAN** et **Code SWIFT** sont renseignés.</span><span class="sxs-lookup"><span data-stu-id="5efb0-144">Also make sure that the **IBAN** and **SWIFT Code** fields are filled in.</span></span>  

10. <span data-ttu-id="5efb0-145">Choisissez l'action **Proposer paiements fournisseur**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-145">Choose the **Suggest Vendor Payments** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="5efb0-146">Vous pouvez également renseigner manuellement les lignes paiement.</span><span class="sxs-lookup"><span data-stu-id="5efb0-146">You can also manually fill in the payment lines.</span></span>  

11. <span data-ttu-id="5efb0-147">Dans le traitement par lots **Proposer paiements fournisseur**, sur le raccourci **Options**, renseignez les champs comme indiqué dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="5efb0-147">In the **Suggest Vendor Payments** batch job, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="5efb0-148">Champ</span><span class="sxs-lookup"><span data-stu-id="5efb0-148">Field</span></span>|<span data-ttu-id="5efb0-149">Désignation</span><span class="sxs-lookup"><span data-stu-id="5efb0-149">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="5efb0-150">**Dernière date échéance**</span><span class="sxs-lookup"><span data-stu-id="5efb0-150">**Last Payment Date**</span></span>|<span data-ttu-id="5efb0-151">Dernière date de paiement pour les écritures comptables fournisseur à inclure dans le traitement par lots.</span><span class="sxs-lookup"><span data-stu-id="5efb0-151">The last payment date for the vendor ledger entries that are to be included in the batch job.</span></span>|  
    |<span data-ttu-id="5efb0-152">**Rechercher les escomptes**</span><span class="sxs-lookup"><span data-stu-id="5efb0-152">**Find Payment Discounts**</span></span>|<span data-ttu-id="5efb0-153">Sélectionnez d'inclure les écritures comptables fournisseur pour lesquelles vous pouvez obtenir un escompte.</span><span class="sxs-lookup"><span data-stu-id="5efb0-153">Select to include vendor ledger entries for which you can receive a payment discount.</span></span>|  
    |<span data-ttu-id="5efb0-154">**Totaliser par**</span><span class="sxs-lookup"><span data-stu-id="5efb0-154">**Summarize per**</span></span>|<span data-ttu-id="5efb0-155">Critères de totalisation de la ligne paiement.</span><span class="sxs-lookup"><span data-stu-id="5efb0-155">The criteria for summarizing the payment line.</span></span>|  
    |<span data-ttu-id="5efb0-156">**Utiliser priorité fournisseur**</span><span class="sxs-lookup"><span data-stu-id="5efb0-156">**Use Vendor Priority**</span></span>|<span data-ttu-id="5efb0-157">Sélectionnez de trier les paiements proposés en fonction de la valeur du champ **Priorité** sur les fiches fournisseur.</span><span class="sxs-lookup"><span data-stu-id="5efb0-157">Select to sort the suggested payments based on the value in the **Priority** field on the vendor cards.</span></span> <span data-ttu-id="5efb0-158">Pour plus d'informations, voir Priorité.</span><span class="sxs-lookup"><span data-stu-id="5efb0-158">For more information, see Priority.</span></span>|  
    |<span data-ttu-id="5efb0-159">**Montant disponible DS**</span><span class="sxs-lookup"><span data-stu-id="5efb0-159">**Available Amount (LCY)**</span></span>|<span data-ttu-id="5efb0-160">Montant maximal qui est disponible pour les paiements en devise société.</span><span class="sxs-lookup"><span data-stu-id="5efb0-160">The maximum amount that is available for payments in local currency.</span></span>|  
    |<span data-ttu-id="5efb0-161">**Filtre devise**</span><span class="sxs-lookup"><span data-stu-id="5efb0-161">**Currency Filter**</span></span>|<span data-ttu-id="5efb0-162">Code de la devise à inclure dans le traitement par lots.</span><span class="sxs-lookup"><span data-stu-id="5efb0-162">The code for the currency to be included in the batch job.</span></span>|  

12. <span data-ttu-id="5efb0-163">Sur le raccourci **Fournisseur**, sélectionnez les filtres appropriés.</span><span class="sxs-lookup"><span data-stu-id="5efb0-163">On the **Vendor** FastTab, select the appropriate filters.</span></span>  
13. <span data-ttu-id="5efb0-164">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-164">Choose the **OK** button.</span></span>  

    <span data-ttu-id="5efb0-165">Les lignes paiement sont automatiquement créées.</span><span class="sxs-lookup"><span data-stu-id="5efb0-165">The payment lines are automatically created.</span></span>  

14. <span data-ttu-id="5efb0-166">Dans la fenêtre **Bordereau paiement**, sous le raccourci **Validation**, renseignez les champs comme indiqué dans le tableau ci-dessous.</span><span class="sxs-lookup"><span data-stu-id="5efb0-166">In the **Payment Slip** window, on the **Posting** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="5efb0-167">Champ</span><span class="sxs-lookup"><span data-stu-id="5efb0-167">Field</span></span>|<span data-ttu-id="5efb0-168">Désignation</span><span class="sxs-lookup"><span data-stu-id="5efb0-168">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="5efb0-169">**Code journal**</span><span class="sxs-lookup"><span data-stu-id="5efb0-169">**Source Code**</span></span>|<span data-ttu-id="5efb0-170">Code source du bordereau paiement.</span><span class="sxs-lookup"><span data-stu-id="5efb0-170">The source code for the payment slip.</span></span>|  
    |<span data-ttu-id="5efb0-171">**Code emplacement immo**</span><span class="sxs-lookup"><span data-stu-id="5efb0-171">**Department Code**</span></span>|<span data-ttu-id="5efb0-172">Code axe analytique approprié.</span><span class="sxs-lookup"><span data-stu-id="5efb0-172">The relevant dimension code.</span></span>|  
    |<span data-ttu-id="5efb0-173">**Code projet**</span><span class="sxs-lookup"><span data-stu-id="5efb0-173">**Project Code**</span></span>|<span data-ttu-id="5efb0-174">Code axe analytique approprié.</span><span class="sxs-lookup"><span data-stu-id="5efb0-174">The relevant dimension code.</span></span>|  
    |<span data-ttu-id="5efb0-175">**Type compte**</span><span class="sxs-lookup"><span data-stu-id="5efb0-175">**Account Type**</span></span>|<span data-ttu-id="5efb0-176">Type de compte vers et à partir duquel les paiements seront transférés.</span><span class="sxs-lookup"><span data-stu-id="5efb0-176">The account type to which or from which the payments will be transferred.</span></span>|  
    |<span data-ttu-id="5efb0-177">**N° compte**</span><span class="sxs-lookup"><span data-stu-id="5efb0-177">**Account No.**</span></span>|<span data-ttu-id="5efb0-178">Numéro de compte vers et à partir duquel les paiements seront transférés.</span><span class="sxs-lookup"><span data-stu-id="5efb0-178">The account number to which or from which the payments will be transferred.</span></span>|  

15. <span data-ttu-id="5efb0-179">Éventuellement, pour SEPA, dans le champ **N° compte**, choisissez l'option **Avancé**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-179">Optionally, for SEPA, in the **Account No.** field, choose the **Advanced** option.</span></span>  

    1. <span data-ttu-id="5efb0-180">Dans la fenêtre **Liste des comptes bancaires**, sélectionnez l'action **Modifier**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-180">In the **Bank Account List** window, choose the **Edit** action.</span></span>  
    2. <span data-ttu-id="5efb0-181">Renseignez les champs suivants, si nécessaire :</span><span class="sxs-lookup"><span data-stu-id="5efb0-181">Fill in the following fields if needed:</span></span>  

        - <span data-ttu-id="5efb0-182">Raccourci **Général**</span><span class="sxs-lookup"><span data-stu-id="5efb0-182">**General** FastTab</span></span>  
        - <span data-ttu-id="5efb0-183">**Code pays/région**</span><span class="sxs-lookup"><span data-stu-id="5efb0-183">**Country/Region Code**</span></span>  
        - <span data-ttu-id="5efb0-184">Raccourci **Transfert**</span><span class="sxs-lookup"><span data-stu-id="5efb0-184">**Transfer**  FastTab</span></span>  
        - <span data-ttu-id="5efb0-185">**Code SWIFT**</span><span class="sxs-lookup"><span data-stu-id="5efb0-185">**Swift Code**</span></span>  
        - <span data-ttu-id="5efb0-186">**IBAN**</span><span class="sxs-lookup"><span data-stu-id="5efb0-186">**IBAN**</span></span>  
        - <span data-ttu-id="5efb0-187">Raccourci **RIB**</span><span class="sxs-lookup"><span data-stu-id="5efb0-187">**RIB** FastTab</span></span>  
        - <span data-ttu-id="5efb0-188">**Format exportation paiement** : SEPA</span><span class="sxs-lookup"><span data-stu-id="5efb0-188">**Payment Export Format**: SEPA</span></span>  
        - <span data-ttu-id="5efb0-189">**Souches de n° ID Msg Virement SEPA** : Banque</span><span class="sxs-lookup"><span data-stu-id="5efb0-189">**SEPA CT Msg. ID No. Series**: Bank</span></span>  

16. <span data-ttu-id="5efb0-190">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-190">Choose the **OK** button.</span></span>  

<span data-ttu-id="5efb0-191">Après avoir créé un bordereau de paiement, vous pouvez générer des fichiers de paiement et les envoyer à la banque par voie électronique.</span><span class="sxs-lookup"><span data-stu-id="5efb0-191">After you create a payment slip, you can generate payment files and send them to the bank electronically.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="5efb0-192">Un fichier de paiement peut être créé si le bordereau de paiement affiche **Fichier** dans le champ **Type action**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-192">A payment file can be created if the payment slip displays **File** for the **Action Type** field.</span></span>

## <a name="to-create-a-payment-file"></a><span data-ttu-id="5efb0-193">Pour créer un fichier de paiement</span><span class="sxs-lookup"><span data-stu-id="5efb0-193">To create a payment file</span></span>  

1.  <span data-ttu-id="5efb0-194">Sélectionnez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Bordereaux paiement**, puis sélectionnez le lien approprié.</span><span class="sxs-lookup"><span data-stu-id="5efb0-194">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Slips**, and then choose the relevant link.</span></span>  
2.  <span data-ttu-id="5efb0-195">Sélectionnez un bordereau paiement, puis cliquez sur **Modifier**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-195">Select a payment slip, and then choose the **Edit** action.</span></span>  
3.  <span data-ttu-id="5efb0-196">Dans la fenêtre **Bordereau paiement**, sélectionnez **Générer fichier**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-196">In the **Payment Slip** window, choose the **Generate file** action.</span></span>  
4.  <span data-ttu-id="5efb0-197">Cliquez sur le bouton **Oui**, puis sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-197">Choose the **Yes** button, and then choose the **OK** button.</span></span>  

    <span data-ttu-id="5efb0-198">Le fichier de paiement est généré et exporté en fonction du type d'exportation spécifié dans la fenêtre **Étape règlement**.</span><span class="sxs-lookup"><span data-stu-id="5efb0-198">The payment file is generated and exported according to the export type that is specified in the **Payment Step** window.</span></span>  

5.  <span data-ttu-id="5efb0-199">En cas d'erreur, consultez les erreurs répertoriées dans le récapitulatif **Erreurs exportation fichier** et prenez la mesure appropriée.</span><span class="sxs-lookup"><span data-stu-id="5efb0-199">In the case of error, review the errors listed in the **File Export Errors** FactBox, and take the appropriate action.</span></span>  

## <a name="see-also"></a><span data-ttu-id="5efb0-200">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="5efb0-200">See Also</span></span>  
 <span data-ttu-id="5efb0-201">[Gestion des paiements](payment-management.md) </span><span class="sxs-lookup"><span data-stu-id="5efb0-201">[Payment Management](payment-management.md) </span></span>  
 <span data-ttu-id="5efb0-202">[Procédure : paramétrer des types de règlement](how-to-set-up-payment-classes.md) </span><span class="sxs-lookup"><span data-stu-id="5efb0-202">[How to: Set Up Payment Classes](how-to-set-up-payment-classes.md) </span></span>  
 <span data-ttu-id="5efb0-203">[Procédure : paramétrer des statuts règlement](how-to-set-up-payment-statuses.md) </span><span class="sxs-lookup"><span data-stu-id="5efb0-203">[How to: Set Up Payment Statuses](how-to-set-up-payment-statuses.md) </span></span>  
 <span data-ttu-id="5efb0-204">[Procédure : paramétrer des étapes règlement](how-to-set-up-payment-steps.md) </span><span class="sxs-lookup"><span data-stu-id="5efb0-204">[How to: Set Up Payment Steps](how-to-set-up-payment-steps.md) </span></span>  
 <span data-ttu-id="5efb0-205">[Procédure : paramétrer des adresses de règlement](how-to-set-up-payment-addresses.md) </span><span class="sxs-lookup"><span data-stu-id="5efb0-205">[How to: Set Up Payment Addresses](how-to-set-up-payment-addresses.md) </span></span>  
 <span data-ttu-id="5efb0-206">[Procédure : valider des bordereaux paiement](how-to-post-payment-slips.md) </span><span class="sxs-lookup"><span data-stu-id="5efb0-206">[How to: Post Payment Slips](how-to-post-payment-slips.md) </span></span>  
 <span data-ttu-id="5efb0-207">[Procédure : archiver des bordereaux paiement](how-to-archive-payment-slips.md) </span><span class="sxs-lookup"><span data-stu-id="5efb0-207">[How to: Archive Payment Slips](how-to-archive-payment-slips.md) </span></span>  
 [<span data-ttu-id="5efb0-208">Procédure : exporter ou importer les paramètres de configuration de la gestion des paiements</span><span class="sxs-lookup"><span data-stu-id="5efb0-208">How to: Export or Import Payment Management Setup Parameters</span></span>](how-to-export-or-import-payment-management-setup-parameters.md)

