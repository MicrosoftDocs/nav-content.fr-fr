---
title: "Procédure de définition des périodes de validation"
description: "En définissant des périodes de validation, vous limitez la période durant laquelle la validation est autorisée."
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
ms.openlocfilehash: 95870af2244c28ab75b98335b3550cf139d94c4c
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-specify-posting-periods"></a><span data-ttu-id="ad286-103">Procédure : définir des périodes de validation</span><span class="sxs-lookup"><span data-stu-id="ad286-103">How to: Specify Posting Periods</span></span>
<span data-ttu-id="ad286-104">En définissant des périodes de validation, vous limitez la période durant laquelle la validation est autorisée.</span><span class="sxs-lookup"><span data-stu-id="ad286-104">When you specify posting periods, you limit the period in which posting is allowed.</span></span>  

## <a name="to-specify-posting-periods"></a><span data-ttu-id="ad286-105">Pour définir des périodes de validation</span><span class="sxs-lookup"><span data-stu-id="ad286-105">To specify posting periods</span></span>  

1.  <span data-ttu-id="ad286-106">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Paramètres comptabilité**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="ad286-106">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Ledger Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="ad286-107">Dans la fenêtre **Paramètres comptabilité**, sous l'onglet **Général**, dans le champ **Début période validation**, spécifiez la date de début de la période de validation.</span><span class="sxs-lookup"><span data-stu-id="ad286-107">In the **General Ledger Setup** window, on the **General** tab, in the **Allow Posting From** field, specify the start date of the posting period.</span></span>  
3.  <span data-ttu-id="ad286-108">Dans le champ **Fin période validation**, spécifiez la date de fin de la période de validation.</span><span class="sxs-lookup"><span data-stu-id="ad286-108">In the **Allow Posting To** field, specify the end date of the posting period.</span></span>  

    <span data-ttu-id="ad286-109">Les dates sont validées dans les plages de validation autorisées pour garantir leur appartenance aux exercices comptables ouverts.</span><span class="sxs-lookup"><span data-stu-id="ad286-109">The dates are validated against the allowed posting ranges to make sure that they belong to open fiscal years.</span></span> <span data-ttu-id="ad286-110">Pour plus d'informations, voir Plage de validation autorisée.</span><span class="sxs-lookup"><span data-stu-id="ad286-110">For more information, see Allowed Posting Range.</span></span>  

4.  <span data-ttu-id="ad286-111">Pour vérifier quelle est la plage de validation autorisée, choisissez l'action **Extraire plage de validation autorisée**.</span><span class="sxs-lookup"><span data-stu-id="ad286-111">To verify what the allowed posting range is, choose the **Get Allowed Posting Range** action.</span></span>  

<span data-ttu-id="ad286-112">Les dates définies ici s'appliquent à l'ensemble de la société, c'est-à-dire à tous les utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="ad286-112">The dates that you define here apply to the whole company, that is, to all users.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="ad286-113">Vous pouvez définir différentes périodes de comptabilisation pour divers utilisateurs et appliquer une période de validation à un utilisateur dans la fenêtre **Paramètres utilisateur**.</span><span class="sxs-lookup"><span data-stu-id="ad286-113">You can define different posting periods for different users and apply a posting period to a user in the **User Setup** window.</span></span>

<span data-ttu-id="ad286-114">Si vous entrez des dates ici, les dates entrées sous l'onglet **Général** de la fenêtre **Paramètres comptabilité** ne s'appliquent pas à ces utilisateurs.</span><span class="sxs-lookup"><span data-stu-id="ad286-114">If you enter dates here, the dates entered on the **General** tab in the **General Ledger Setup** window will not apply to these users.</span></span>  

## <a name="see-also"></a><span data-ttu-id="ad286-115">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="ad286-115">See Also</span></span>  
 [<span data-ttu-id="ad286-116">Périodes fiscales et exercices comptables</span><span class="sxs-lookup"><span data-stu-id="ad286-116">Fiscal Periods and Fiscal Years</span></span>](fiscal-periods-and-fiscal-years.md)

