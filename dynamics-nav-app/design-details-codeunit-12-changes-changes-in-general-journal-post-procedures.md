---
title: "Détails de conception : modifications du codeunit 12 dans les procédures de validation de feuille comptabilité"
description: "Les modifications suivantes ont été mises en œuvre dans cette version de [!INCLUDE[d365fin](includes/d365fin_md.md)]."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 19bbc6eb4939fa7f4e0180a62b03998cd2f386b6
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="codeunit-12-changes-changes-in-general-journal-post-procedures"></a>Codeunit 12 modifications : modifications dans les procédures de validation de feuille comptabilité
Les modifications suivantes ont été mises en œuvre dans cette version de [!INCLUDE[d365fin](includes/d365fin_md.md)].  

|**Microsoft Dynamics NAV 2009 R2**|**Microsoft Dynamics NAV 2013 R2**|**Commentaires**|  
|----------------------------------------|----------------------------------------|-----------------|  
|GetGLReg|GetGLReg|Mise à jour|  
|RunWithCheck|RunWithCheck|Mis à jour|  
|RunWithoutCheck|RunWithoutCheck|Mis à jour|  
|Code|Code|Mis à jour|  
||PostGenJnlLine|Ajouté|  
||InitAmounts|Ajouté|  
||InitLastDocDate|Ajouté|  
|InitVAT|InitVAT|Mis à jour|  
|PostVAT|PostVAT|Mis à jour|  
|InsertVAT|InsertVAT|Mis à jour|  
|SummarizeVAT|SummarizeVAT|Mis à jour|  
|InsertSummarizedVAT|InsertSummarizedVAT|Mis à jour|  
|PostGLAcc|PostGLAcc|Mis à jour|  
|PostCust|PostCust|Mis à jour|  
|PostVend|PostVend|Mis à jour|  
|PostBankAcc|PostBankAcc|Mis à jour|  
|PostFixedAsset|PostFixedAsset|Mis à jour|  
|PostICPartner|PostICPartner|Mis à jour|  
|InitCodeUnit|StartPosting|Mis à jour|  
||ContinuePosting|Ajouté|  
|FinishCodeunit|FinishPosting|Mis à jour|  
||PostUnrealizedVAT|Ajouté|  
||CheckPostUnrealizedVAT|Ajouté|  
||ExchangeAccounts|Ajouté|  
|InitGLEntry|InitGLEntry|Mis à jour|  
||InitGLEntryVAT|Ajouté|  
||InitGLEntryVATCopy|Ajouté|  
|InsertGLEntry|InsertGLEntry|Mis à jour|  
||CreateGLEntry|Ajouté|  
||CreateGLEntryBalAcc|Ajouté|  
||CreateGLEntryVAT|Ajouté|  
||CreateGLEntryVATCollectAdj|Ajouté|  
||CreateGLEntryFromVATEntry|Ajouté|  
||UpdateCheckAmounts|Ajouté|  
|ApplyCustLedgEntry|ApplyCustLedgEntry|Mis à jour|  
||CalcPmtDiscPossible|Ajouté|  
||CalcPmtTolerancePossible|Ajouté|  
|CalcPmtTolerance|CalcPmtTolerance|Mis à jour|  
|CalcPmtDisc|CalcPmtDisc|Mis à jour|  
|CalcPmtDiscIfAdjVAT|CalcPmtDiscIfAdjVAT|Mis à jour|  
|CalcPmtDiscTolerance|CalcPmtDiscTolerance|Mis à jour|  
||CalcPmtDiscVATBases|Ajouté|  
||CalcPmtDiscVATAmounts|Ajouté|  
||InsertPmtDiscVATForVATEntry|Ajouté|  
||InsertPmtDiscVATForGLEntry|Ajouté|  
|CalcCurrencyApplnRounding|CalcCurrencyApplnRounding|Mis à jour|  
|FindAmtForAppln|FindAmtForAppln|Mis à jour|  
|CalcCurrencyUnrealizedGainLoss|CalcCurrencyUnrealizedGainLoss|Mis à jour|  
|CalcCurrencyRealizedGainLoss|CalcCurrencyRealizedGainLoss|Mis à jour|  
|CalcApplication|CalcApplication|Mis à jour|  
|CalcRemainingPmtDisc|CalcRemainingPmtDisc|Déplacé dans Codeunit 426 Gestion d'écart de paiement|  
|CalcAmtLCYAdjustment|CalcAmtLCYAdjustment|Ajouté|  
|InitNewCVLedgEntry|InitFromGenJnlLine|Déplacé dans le tableau 383 Tampon écriture comptable CF détaillée|  
|InitOldCVLedgEntry|CopyFromCVLedgEntryBuf|Déplacé dans le tableau 383 Tampon écriture comptable CF détaillée|  
|InsertDtldCVLedgEntry|InsertDtldCVLedgEntry|Déplacé dans le tableau 383 Tampon écriture comptable CF détaillée|  
||InitBankAccLedgEntry|Ajouté|  
||InitCheckLedgEntry|Ajouté|  
||InitCustLedgEntry|Ajouté|  
||InitVendLedgEntry|Ajouté|  
||InsertDtldCustLedgEntry|Ajouté|  
||InsertDtldVendLedgEntry|Ajouté|  
|CustUnrealizedVAT|CustUnrealizedVAT|Mis à jour|  
|CustPostApplyCustLedgEntry|CustPostApplyCustLedgEntry|Mis à jour|  
||PrepareTempCustLedgEntry|Ajouté|  
|UnapplyCustLedgEntry|UnapplyCustLedgEntry|Mis à jour|  
|TransferCustLedgEntry|CopyFromGenJnlLine|Déplacé dans le tableau 21 Écriture comptable client|  
|PostDtldCustLedgEntries|PostDtldCustLedgEntries|Mis à jour|  
||PostDtldCustLedgEntry|Ajouté|  
||PostDtldCustLedgEntryUnapply|Ajouté|  
||GetDtldCustLedgEntryAccNo|Ajouté|  
|ZeroTransNoDtldCustLedgEntries|SetZeroTransNo|Déplacé dans le tableau 379 Écriture comptable client détaillée|  
|AutoEntrForDtldCustLedgEntries||Remanié vers PostDtldCustLedgEntryUnapply|  
|CustUpdateDebitCredit|UpdateDebitCredit|Déplacé dans le tableau 379 Écriture comptable client détaillée|  
|ApplyVendLedgEntry|ApplyVendLedgEntry|Mis à jour|  
||PrepareTempVendLedgEntry|Ajouté|  
|VendPostApplyVendLedgEntry|VendPostApplyVendLedgEntry|Mis à jour|  
|UnapplyVendLedgEntry|UnapplyVendLedgEntry|Mis à jour|  
|TransferVendLedgEntry|CopyFromGenJnlLine|Déplacé dans le tableau 25 Écriture comptable fournisseur|  
|PostDtldVendLedgEntries|PostDtldVendLedgEntries|Mis à jour|  
||PostDtldVendLedgEntry|Ajouté|  
||PostDtldVendLedgEntryUnapply|Ajouté|  
||GetDtldVendLedgEntryAccNo|Ajouté|  
||PostDtldCVLedgEntry|Ajouté|  
||PostDtldCustVATAdjustment|Ajouté|  
||PostDtldVendVATAdjustment|Ajouté|  
|ZeroTransNoDtldVendLedgEntries|SetZeroTransNo|Déplacé dans le tableau 380 Écriture comptable fournisseur détaillée|  
|AutoEntrForDtldVendLedgEntries||Remanié vers PostDtldVendLedgEntryUnapply|  
|VendUpdateDebitCredit|UpdateDebitCredit|Déplacé dans le tableau 380 Écriture comptable fournisseur détaillée|  
|VendUnrealizedVAT|VendUnrealizedVAT|Mis à jour|  
||PostUnrealVATEntry|Ajouté|  
||PostApply|Ajouté|  
|PostUnrealVATByUnapply|PostUnrealVATByUnapply|Mis à jour|  
||PostUnapply|Ajouté|  
||InsertDtldCustLedgEntryUnapply|Ajouté|  
||InsertDtldVendLedgEntryUnapply|Ajouté|  
||InsertTempVATEntry|Ajouté|  
||ProcessTempVATEntry|Ajouté|  
||UpdateCustLedgEntry|Ajouté|  
||UpdateVendLedgEntry|Ajouté|  
|UpdateCalcInterest|UpdateCalcInterest|Mis à jour|  
|UpdateCalcInterest2|UpdateCalcInterest2|Mis à jour|  
|GLCalcAddCurrency|GLCalcAddCurrency|Mis à jour|  
|HandleAddCurrResidualGLEntry|HandleAddCurrResidualGLEntry|Mis à jour|  
|CalcLCYToAddCurr|CalcLCYToAddCurr|Mis à jour|  
|CalcAddCurrFactor||Supprimée|  
|GetCurrencyExchRate|GetCurrencyExchRate|Mis à jour|  
|ExchAmount|ExchangeAmount|Déplacé dans le tableau 330 Taux de change devise|  
|ExchangeAmtLCYToFCY2|ExchangeAmtLCYToFCY2|Mis à jour|  
|CalcAddCurrForUnapplication|CalcAddCurrForUnapplication|Mis à jour|  
|CheckNonAddCurrCodeOccurred|CheckNonAddCurrCodeOccurred|Mis à jour|  
|CheckCalcPmtDisc||Déplacé dans Codeunit 426 Gestion d'écart de paiement|  
|CheckCalcPmtDiscCVCust||Déplacé dans Codeunit 426 Gestion d'écart de paiement|  
|CheckCalcPmtDiscCust||Déplacé dans Codeunit 426 Gestion d'écart de paiement|  
|CheckCalcPmtDiscGenJnlCust||Déplacé dans Codeunit 426 Gestion d'écart de paiement|  
|CheckCalcPmtDiscCVVend||Déplacé dans Codeunit 426 Gestion d'écart de paiement|  
|CheckCalcPmtDiscVend||Déplacé dans Codeunit 426 Gestion d'écart de paiement|  
|CheckCalcPmtDiscGenJnlVend||Déplacé dans Codeunit 426 Gestion d'écart de paiement|  
|Reverse|Reverse|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|ReverseCustLedgEntry|ReverseCustLedgEntry|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|ReverseVendLedgEntry|ReverseVendLedgEntry|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|ReverseBankAccLedgEntry|ReverseBankAccLedgEntry|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|ReverseVAT|ReverseVAT|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|SetReversalDescription|SetReversalDescription|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|ApplyCustLedgEntryByReversal|ApplyCustLedgEntryByReversal|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|ApplyVendLedgEntryByReversal|ApplyVendLedgEntryByReversal|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|PostPmtDiscountVATByUnapply|PostPmtDiscountVATByUnapply|Déplacé dans Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
||CheckDimComb|Ajouté dans le Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
||CopyCustLedgEntry|Ajouté dans le Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
||CopyVendLedgEntry|Ajouté dans le Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
||CopyBankAccLedgEntry|Ajouté dans le Codeunit 17 Gen. Jnl.-Valeur en comptabilité|  
|HandlDtlAddjustment|HandleDtldAdjustment|Mis à jour|  
|CollectAddjustment|CollectAdjustment|Mis à jour|  
|SetOverDimErr|SetOverDimErr|Mis à jour|  
|PostJob|PostJob|Mis à jour|  
|InsertVATEntriesFromTemp|InsertVATEntriesFromTemp|Mis à jour|  
|CaptureOrRefundCreditCardPmnt|CaptureOrRefundCreditCardPmnt|Mis à jour|  
|UpdateDOPaymentTransactEntry|UpdateDOPaymentTransactEntry|Mis à jour|  
|ABSMin|ABSMin|Mis à jour|  
|GetApplnRoundPrecision|GetApplnRoundPrecision|Mis à jour|  
|CheckDimValueForDisposal|CheckDimValueForDisposal|Mis à jour|  
|CalculateCurrentBalance|CalculateCurrentBalance|Mis à jour|  
|IncludeVATAmount||Déplacé dans le tableau 81 Ligne feuille comptabilité|  
|CalcVATAmountFromVATEntry|CalcVATAmountFromVATEntry|Mis à jour|  
||TotalVATAmountOnJnlLines|Ajouté|  
||SetGLRegReverse|Ajouté|  
||GetGLSetup|Ajouté|  
||ReadGLSetup|Ajouté|  
||CheckSalesExtDocNo|Ajouté|  
||CheckPurchExtDocNo|Ajouté|  
||CheckGLAccDimError|Ajouté|  
||GetCurrency|Ajouté|  
||PostDtldAdjustment|Ajouté|  
||GetNextEntryNo|Ajouté|  
||GetNextTransactionNo|Ajouté|  
||GetNextVATEntryNo|Ajouté|  
||IncrNextVATEntryNo|Ajouté|  
||IsNotPayment|Ajouté|  
||IsTempGLEntryBufEmpty|Ajouté|  
||IsVATAdjustment|Ajouté|  
||IsVATExcluded|Ajouté|  
||Mettre à jour dimensions|Ajouté|  
||UpdateDimensionsFromCustLedgEntry|Ajouté|  
||UpdateDimensionsFromVendLedgEntry|Ajouté|  
||UpdateTotalAmounts|Ajouté|  
||CreateGLEntriesForTotalAmounts|Ajouté|  

## <a name="see-also"></a>Voir aussi  
 [Détails de conception : modifications du codeunit 12 : variables globales de mappage pour la ligne de validation de feuille comptabilité](design-details-codeunit-12-changes-mapping-global-variables-for-general-journal-post-line.md)

