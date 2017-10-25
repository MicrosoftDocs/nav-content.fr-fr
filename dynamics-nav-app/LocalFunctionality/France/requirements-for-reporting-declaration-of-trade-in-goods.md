---
title: "Configuration requise pour la déclaration d'échanges de biens"
description: "Cette rubrique présente la liste des champs requis pour la déclaration d'échanges de biens (DEB) au format DTI+. Pour plus d'informations, voir Exporter DEB DTI."
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
ms.openlocfilehash: ecc6ddbcce1b65daebc91e2878ce889ff856bc53
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="requirements-for-reporting-declaration-of-trade-in-goods"></a><span data-ttu-id="eb073-104">Configuration requise pour la déclaration d'échanges de biens</span><span class="sxs-lookup"><span data-stu-id="eb073-104">Requirements for Reporting Declaration of Trade in Goods</span></span>
<span data-ttu-id="eb073-105">Cette rubrique présente la liste des champs requis pour la déclaration d'échanges de biens (DEB) au format DTI+.</span><span class="sxs-lookup"><span data-stu-id="eb073-105">This topic shows a list of required fields that are needed for reporting Declaration of Trade in Goods (DEB) based on the DTI+ format.</span></span> <span data-ttu-id="eb073-106">Pour plus d'informations, voir Exporter DEB DTI.</span><span class="sxs-lookup"><span data-stu-id="eb073-106">For more information, see Export DEB DTI.</span></span>  
  
 <span data-ttu-id="eb073-107">Les champs suivants sont requis pour la déclaration d'échanges de biens :</span><span class="sxs-lookup"><span data-stu-id="eb073-107">The following fields are required for reporting DEB:</span></span>  
  
-   <span data-ttu-id="eb073-108">**CISD** dans la table **Informations société**.</span><span class="sxs-lookup"><span data-stu-id="eb073-108">**CISD** from the **Company Information** table.</span></span>  
  
-   <span data-ttu-id="eb073-109">**N° SIRET** dans la table **Informations société**.</span><span class="sxs-lookup"><span data-stu-id="eb073-109">**Registration No.** from the **Company Information** table.</span></span>  
  
-   <span data-ttu-id="eb073-110">**N° identif. intracomm.** dans la table **Informations société**.</span><span class="sxs-lookup"><span data-stu-id="eb073-110">**VAT Registration No.** from the **Company Information** table.</span></span>  
  
-   <span data-ttu-id="eb073-111">**Nom** dans la table **Informations société**.</span><span class="sxs-lookup"><span data-stu-id="eb073-111">**Name** from the **Company Information** table.</span></span>  
  
-   <span data-ttu-id="eb073-112">**Date** de la période statistique dans la table **Ligne feuille intracomm**.</span><span class="sxs-lookup"><span data-stu-id="eb073-112">**Date** for the statistics period from the **Intrastat Jnl. Line** table.</span></span>  
  
-   <span data-ttu-id="eb073-113">**Régime** dans la table **Ligne feuille intracomm**.</span><span class="sxs-lookup"><span data-stu-id="eb073-113">**Transaction Specification** from the **Intrastat Jnl. Line** table.</span></span>  
  
-   <span data-ttu-id="eb073-114">La **Quantité** dans la table **Ligne feuille intracomm** doit être supérieure à 0.</span><span class="sxs-lookup"><span data-stu-id="eb073-114">**Quantity** from the **Intrastat Jnl. Line** table must be greater than 0.</span></span>  
  
-   <span data-ttu-id="eb073-115">La **Valeur statistique** dans la table **Ligne feuille intracomm** doit être supérieure à 0.</span><span class="sxs-lookup"><span data-stu-id="eb073-115">**Statistical Value** from the **Intrastat Jnl. Line** table must be greater than 0.</span></span>  
  
> [!NOTE]  
>  <span data-ttu-id="eb073-116">L'état **Exporter DEB DTI** exporte les expéditions et les réceptions dans un lot.</span><span class="sxs-lookup"><span data-stu-id="eb073-116">The **Export DEB DTI** report exports shipments and receipts in one batch.</span></span> <span data-ttu-id="eb073-117">Si vous souhaitez déclarer uniquement les expéditions ou les réceptions, vous devez définir un filtre pour supprimer les lignes qui ne sont pas nécessaires dans la table **Feuille intracomm**.</span><span class="sxs-lookup"><span data-stu-id="eb073-117">If you want to report only shipments or receipts, then you must set a filter to remove the lines that are not needed in the **Intrastat Journal** table.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="eb073-118">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="eb073-118">See Also</span></span>  
 <span data-ttu-id="eb073-119">Exporter DEB DTI</span><span class="sxs-lookup"><span data-stu-id="eb073-119">Export DEB DTI</span></span>   
 <span data-ttu-id="eb073-120">Informations société</span><span class="sxs-lookup"><span data-stu-id="eb073-120">Company Information</span></span>   
 <span data-ttu-id="eb073-121">Feuille intracomm.</span><span class="sxs-lookup"><span data-stu-id="eb073-121">Intrastat Journal</span></span>   
 <span data-ttu-id="eb073-122">CISD</span><span class="sxs-lookup"><span data-stu-id="eb073-122">CISD</span></span>   
 <span data-ttu-id="eb073-123">Ligne feuille intracomm.</span><span class="sxs-lookup"><span data-stu-id="eb073-123">Intrastat Jnl. Line</span></span>
