---
title: "Périodes fiscales et exercices comptables"
description: "Un exercice comptable est généralement divisé en 12 périodes fiscales mensuelles. Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], deux exercices comptables peuvent être ouverts en même temps. Vous ne pouvez pas créer un troisième exercice comptable si deux exercices comptables sont ouverts."
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
ms.openlocfilehash: cdcfd685487eddd8a442e5de2316902c656bc48d
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="fiscal-periods-and-fiscal-years"></a><span data-ttu-id="14d43-105">Périodes fiscales et exercices comptables</span><span class="sxs-lookup"><span data-stu-id="14d43-105">Fiscal Periods and Fiscal Years</span></span>
<span data-ttu-id="14d43-106">Un exercice comptable est généralement divisé en 12 périodes fiscales mensuelles.</span><span class="sxs-lookup"><span data-stu-id="14d43-106">A fiscal year is typically divided into 12 monthly fiscal periods.</span></span> <span data-ttu-id="14d43-107">Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], deux exercices comptables peuvent être ouverts en même temps.</span><span class="sxs-lookup"><span data-stu-id="14d43-107">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can have two fiscal years open at the same time.</span></span> <span data-ttu-id="14d43-108">Vous ne pouvez pas créer un troisième exercice comptable si deux exercices comptables sont ouverts.</span><span class="sxs-lookup"><span data-stu-id="14d43-108">You cannot create a third fiscal year if there are two fiscal years open.</span></span>  
  
 <span data-ttu-id="14d43-109">Pour clôturer un exercice comptable, vous devez clôturer les périodes comptables de cet exercice.</span><span class="sxs-lookup"><span data-stu-id="14d43-109">To close a fiscal year, you must close the accounting periods within that year.</span></span>  
  
 <span data-ttu-id="14d43-110">Vous ne pouvez rouvrir une période comptable clôturée que si elle fait partie d'un exercice comptable ouvert.</span><span class="sxs-lookup"><span data-stu-id="14d43-110">You can only reopen a closed accounting period if the period falls within an open fiscal year.</span></span> <span data-ttu-id="14d43-111">Pour plus d'informations, voir [Procédure : clôturer des exercices](how-to-close-years.md).</span><span class="sxs-lookup"><span data-stu-id="14d43-111">For more information, see [How to: Close Years](how-to-close-years.md).</span></span> <span data-ttu-id="14d43-112">Vous ne pouvez pas rouvrir un exercice comptable clôturé.</span><span class="sxs-lookup"><span data-stu-id="14d43-112">You cannot reopen a closed fiscal year.</span></span>  
  
## <a name="closing-fiscal-periods-and-fiscal-years"></a><span data-ttu-id="14d43-113">Clôture de périodes fiscales et d'exercices comptables</span><span class="sxs-lookup"><span data-stu-id="14d43-113">Closing Fiscal Periods and Fiscal Years</span></span>  
 <span data-ttu-id="14d43-114">À la fin d'un exercice comptable, vous devez clôturer les périodes comptables de cet exercice comptable.</span><span class="sxs-lookup"><span data-stu-id="14d43-114">After a fiscal year is complete, you must close the accounting periods within that fiscal year.</span></span> <span data-ttu-id="14d43-115">Cela garantit que des écritures comptables ne sont pas validées pour cette période.</span><span class="sxs-lookup"><span data-stu-id="14d43-115">This is to ensure that general ledger entries are not posted for that period.</span></span> <span data-ttu-id="14d43-116">Pour plus d'informations, voir [Procédure : clôturer fiscalement des périodes comptables](how-to-fiscally-close-years.md).</span><span class="sxs-lookup"><span data-stu-id="14d43-116">For more information, see [How to: Fiscally Close Accounting Periods](how-to-fiscally-close-years.md).</span></span>  
  
 <span data-ttu-id="14d43-117">Un exercice comptable peut être clôturé si tous les critères suivants sont remplis :</span><span class="sxs-lookup"><span data-stu-id="14d43-117">A fiscal year can be closed if all of the following criteria are met:</span></span>  
  
-   <span data-ttu-id="14d43-118">Les dates comptabilisation dans la fenêtre **Paramètres utilisateur** et la fenêtre **Paramètres comptabilité** ne font pas partie de l'exercice que vous clôturez.</span><span class="sxs-lookup"><span data-stu-id="14d43-118">The posting dates in the **User Setup** window and the **General Ledger Setup** window do not fall within the year that you are closing.</span></span> <span data-ttu-id="14d43-119">Pour plus d'informations, voir Paramètres utilisateur et Paramètres comptabilité.</span><span class="sxs-lookup"><span data-stu-id="14d43-119">For more information, see User Setup and General Ledger Setup.</span></span>  
  
-   <span data-ttu-id="14d43-120">L'exercice comptable a été clôturé à l'aide de la fonction **Clôturer exercice** dans la fenêtre **Périodes comptables**.</span><span class="sxs-lookup"><span data-stu-id="14d43-120">The fiscal year has been closed using the **Close Year** function in the **Accounting Periods** window.</span></span> <span data-ttu-id="14d43-121">Pour plus d'informations, reportez vous à [Procédure: Clôturer des périodes comptables](how-to-close-accounting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="14d43-121">For more information, see [How to: Close Accounting Periods](how-to-close-accounting-periods.md).</span></span>  
  
-   <span data-ttu-id="14d43-122">Toutes les lignes feuille non validées et les écritures de simulation de l'exercice ont été validées ou supprimées.</span><span class="sxs-lookup"><span data-stu-id="14d43-122">All of the unposted journal lines and simulation entries for the year have been posted or deleted.</span></span>  
  
-   <span data-ttu-id="14d43-123">Toutes les écritures de clôture sont à jour.</span><span class="sxs-lookup"><span data-stu-id="14d43-123">All closing entries are up to date.</span></span>  
  
 <span data-ttu-id="14d43-124">Lorsque vous clôturez une période fiscale, la plus ancienne période fiscale ouverte est clôturée.</span><span class="sxs-lookup"><span data-stu-id="14d43-124">When you close a fiscal period, the earliest open fiscal period is closed.</span></span> <span data-ttu-id="14d43-125">Le champ **Début période validation** dans la fenêtre **Paramètres comptabilité** est mis à jour avec la date de début de la période ouverte suivante, si la date existante dans ce champ n'est pas déjà une date postérieure.</span><span class="sxs-lookup"><span data-stu-id="14d43-125">The **Allow Posting From** field in the **General Ledger Setup** window is updated with the start date for the next open period, if the existing date in this field is not already a later date.</span></span> <span data-ttu-id="14d43-126">Si le champ **Fin période validation** dans la fenêtre **Paramètres comptabilité** se situe dans la période clôturée, la valeur du champ **Fin période validation** est mise à jour avec la date de fin de la première période fiscale ouverte.</span><span class="sxs-lookup"><span data-stu-id="14d43-126">If the **Allow Posting To** field in the **General Ledger Setup** window is within the closed period, then the value in the **Allow Posting To** field is updated with the end date for the first open fiscal period.</span></span> <span data-ttu-id="14d43-127">Pour plus d'informations, voir Paramètres comptabilité.</span><span class="sxs-lookup"><span data-stu-id="14d43-127">For more information, see General Ledger Setup.</span></span>  
  
 <span data-ttu-id="14d43-128">À la fin de l'exercice, vous devez effectuer les opérations suivantes :</span><span class="sxs-lookup"><span data-stu-id="14d43-128">At the end of the year, you must do the following:</span></span>  
  
-   <span data-ttu-id="14d43-129">clôturer l'exercice comptable à l'aide de la fonction **Clôturer exercice** ;</span><span class="sxs-lookup"><span data-stu-id="14d43-129">Close the fiscal year using the **Close Year** function.</span></span>  
  
-   <span data-ttu-id="14d43-130">générer une écriture de clôture d'exercice ;</span><span class="sxs-lookup"><span data-stu-id="14d43-130">Generate a year-end closing entry.</span></span>  
  
-   <span data-ttu-id="14d43-131">valider l'écriture de clôture d'exercice et compenser les écritures comptables de fonds propres ;</span><span class="sxs-lookup"><span data-stu-id="14d43-131">Post the year-end closing entry, along with the offset equity account entries.</span></span>  
  
-   <span data-ttu-id="14d43-132">clôturer l'exercice comptable à l'aide de la fonction **Clôturer l'exercice fiscalement**.</span><span class="sxs-lookup"><span data-stu-id="14d43-132">Close the fiscal year using the **Fiscally Close Year** function.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="14d43-133">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="14d43-133">See Also</span></span>  
 <span data-ttu-id="14d43-134">[Procédure : ouvrir un nouvel exercice comptable](how-to-open-a-new-fiscal-year.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-134">[How to: Open a New Fiscal Year](how-to-open-a-new-fiscal-year.md) </span></span>  
 <span data-ttu-id="14d43-135">[Procédure : définir des périodes de validation](how-to-specify-posting-periods.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-135">[How to: Specify Posting Periods](how-to-specify-posting-periods.md) </span></span>  
 <span data-ttu-id="14d43-136">[Procédure : valider l'écriture de clôture d'exercice](how-to-post-the-year-end-closing-entry.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-136">[How to: Post the Year-End Closing Entry](how-to-post-the-year-end-closing-entry.md) </span></span>  
 <span data-ttu-id="14d43-137">[Procédure : clôturer fiscalement des périodes comptables](how-to-fiscally-close-accounting-periods.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-137">[How to: Fiscally Close Accounting Periods](how-to-fiscally-close-accounting-periods.md) </span></span>  
 <span data-ttu-id="14d43-138">[Procédure : clôturer des exercices](how-to-close-years.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-138">[How to: Close Years](how-to-close-years.md) </span></span>  
 <span data-ttu-id="14d43-139">[Procédure : valider l'écriture de clôture d'exercice](how-to-post-the-year-end-closing-entry.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-139">[How to: Post the Year-End Closing Entry](how-to-post-the-year-end-closing-entry.md) </span></span>  
 <span data-ttu-id="14d43-140">[Procédure : clôturer fiscalement des exercices](how-to-fiscally-close-years.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-140">[How to: Fiscally Close Years](how-to-fiscally-close-years.md) </span></span>  
 <span data-ttu-id="14d43-141">[Procédure : rouvrir des périodes comptables](how-to-reopen-accounting-periods.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-141">[How to: Reopen Accounting Periods](how-to-reopen-accounting-periods.md) </span></span>  
 <span data-ttu-id="14d43-142">[Procédure : Clôturer les comptes de gestion](how-to-close-income-statement-accounts.md) </span><span class="sxs-lookup"><span data-stu-id="14d43-142">[How to: Close Income Statement Accounts](how-to-close-income-statement-accounts.md) </span></span>  
 <span data-ttu-id="14d43-143">Paramètres utilisateur</span><span class="sxs-lookup"><span data-stu-id="14d43-143">User Setup</span></span>   
 <span data-ttu-id="14d43-144">Paramètres comptabilité</span><span class="sxs-lookup"><span data-stu-id="14d43-144">General Ledger Setup</span></span>   
 [<span data-ttu-id="14d43-145">Fonctionnalité locale, France</span><span class="sxs-lookup"><span data-stu-id="14d43-145">France Local Functionality</span></span>](france-local-functionality.md)
