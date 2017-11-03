---
title: Vue d'ensemble des processus de fin d'exercice
description: "Une clôture d'exercice dans [!INCLUDE[navnow](../../includes/navnow_md.md)] implique trois étapes."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 1ff74b6ca32e43db742097bf21095cdf3c6c5198
ms.contentlocale: fr-fr
ms.lasthandoff: 10/26/2017

---
# <a name="year-end-processes-overview"></a><span data-ttu-id="90850-103">Vue d'ensemble des processus de fin d'exercice</span><span class="sxs-lookup"><span data-stu-id="90850-103">Year End Processes Overview</span></span>
<span data-ttu-id="90850-104">Une clôture d'exercice dans [!INCLUDE[navnow](../../includes/navnow_md.md)] implique trois étapes :</span><span class="sxs-lookup"><span data-stu-id="90850-104">Year end closing in [!INCLUDE[navnow](../../includes/navnow_md.md)] involves three steps:</span></span>  

1.  <span data-ttu-id="90850-105">Clôture de l'exercice comptable.</span><span class="sxs-lookup"><span data-stu-id="90850-105">Closing the fiscal year.</span></span> <span data-ttu-id="90850-106">Pour plus d'informations, voir [Procédure : clôturer fiscalement des périodes comptables](how-to-fiscally-close-accounting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="90850-106">For more information, see [How to: Fiscally Close Accounting Periods](how-to-fiscally-close-accounting-periods.md).</span></span>  
2.  <span data-ttu-id="90850-107">Générer une écriture de clôture d'exercice via l'option **Clôturer exercice comptable** avec la compensation des écritures de compte de fonds propres.</span><span class="sxs-lookup"><span data-stu-id="90850-107">Generating a year-end closing entry using the **Close Income Statement** option along with the offsetting equity account entries.</span></span> <span data-ttu-id="90850-108">Pour plus d'informations, reportez-vous à [Validation de l'écriture de clôture d'exercice](how-to-post-the-year-end-closing-entry.md).</span><span class="sxs-lookup"><span data-stu-id="90850-108">For more information, see [Posting the year-end closing entry](how-to-post-the-year-end-closing-entry.md).</span></span>  
3.  <span data-ttu-id="90850-109">Clôture de l'exercice comptable.</span><span class="sxs-lookup"><span data-stu-id="90850-109">Fiscally closing the fiscal year.</span></span> <span data-ttu-id="90850-110">Pour plus d'informations, voir [Procédure : clôturer fiscalement des périodes comptables](how-to-fiscally-close-accounting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="90850-110">For more information, see [How to: Fiscally Close Accounting Periods](how-to-fiscally-close-accounting-periods.md).</span></span>  

<span data-ttu-id="90850-111">Selon la norme française *NF Logiciel compatibilité informatisée*, le système doit refuser la création d'un troisième exercice comptable ouvert. Seuls deux exercices comptables peuvent donc être ouverts en même temps.</span><span class="sxs-lookup"><span data-stu-id="90850-111">According to the French law *NF Logiciel compatibilité informatisée* the system has to refuse the creation of a third open fiscal year, so only two open fiscal years are allowed at the same time.</span></span>  

<span data-ttu-id="90850-112">Vous devez dès lors clôturer l'exercice en temps voulu.</span><span class="sxs-lookup"><span data-stu-id="90850-112">So in time you are required to close a year.</span></span> <span data-ttu-id="90850-113">Les détails des transactions ne risquent pas d'être perdus lorsque vous clôturez l'exercice, puisqu'ils sont tous mémorisés, même après avoir clôturé fiscalement l'exercice.</span><span class="sxs-lookup"><span data-stu-id="90850-113">You also do not have to worry about losing details of transactions when you close because all details are retained, even after you (fiscally) close the year.</span></span>  

<span data-ttu-id="90850-114">Lors de la clôture en fin d'exercice, le système déplace vos bénéfices des bénéfices calculés, ou du compte Bénéfices actuels, vers un compte validé, ou le compte Bénéfices non répartis.</span><span class="sxs-lookup"><span data-stu-id="90850-114">When you close at the end of the year, the system moves your earnings from calculated earnings, or the Current Earnings account, to a posted account, or the Retained Earnings account.</span></span> <span data-ttu-id="90850-115">Le système indique également que l'exercice comptable est « clôturé » et renseigne toutes les entrées suivantes pour l'exercice clôturé comme « écritures de l'exercice précédent ».</span><span class="sxs-lookup"><span data-stu-id="90850-115">The system also marks the fiscal year as "closed," and marks all subsequent entries for the closed year as "prior year entries."</span></span>  

<span data-ttu-id="90850-116">Le système génère ensuite une écriture de clôture mais ne la valide pas automatiquement.</span><span class="sxs-lookup"><span data-stu-id="90850-116">The system then generates a closing entry, but it does not post the entry automatically.</span></span> <span data-ttu-id="90850-117">Vous avez la possibilité de créer les écritures comptables de fonds propres de décalage qui vous permettent de choisir la manière dont vous voulez affecter votre écriture de clôture.</span><span class="sxs-lookup"><span data-stu-id="90850-117">You are given the opportunity to make the offsetting equity account entry or entries, which allows you to decide how to allocate your closing entry.</span></span> <span data-ttu-id="90850-118">Par exemple, si votre société comprend plusieurs départements, vous pouvez laisser le système générer une écriture de clôture unique pour tous les départements et créer une écriture de décalage pour le compte de fonds propres de chaque département.</span><span class="sxs-lookup"><span data-stu-id="90850-118">For example, if your company has several divisions, you can let the system generate a single closing entry for all the divisions, and you can then make an offsetting entry for each division's equity account.</span></span>  

<span data-ttu-id="90850-119">Après avoir clôturé fiscalement un exercice, vous ne pourrez plus rien comptabiliser dans cet exercice.</span><span class="sxs-lookup"><span data-stu-id="90850-119">Once a year has been fiscally closed you will not be able to post in this fiscal year.</span></span>  

## <a name="see-also"></a><span data-ttu-id="90850-120">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="90850-120">See Also</span></span>  
 <span data-ttu-id="90850-121">[Périodes fiscales et exercices comptables](fiscal-periods-and-fiscal-years.md) </span><span class="sxs-lookup"><span data-stu-id="90850-121">[Fiscal Periods and Fiscal Years](fiscal-periods-and-fiscal-years.md) </span></span>  
 [<span data-ttu-id="90850-122">Clôture des exercices et des périodes</span><span class="sxs-lookup"><span data-stu-id="90850-122">Closing Years and Periods</span></span>](../../year-close-years-periods.md)

