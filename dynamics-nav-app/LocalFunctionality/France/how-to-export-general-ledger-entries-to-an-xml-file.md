---
title: "Procédure d'exportation des écritures comptables vers un fichier XML"
description: "Pour l'archivage externe, et pour une période donnée, vous pouvez exporter des transactions financières vers un fichier XML. À la fin de l'exercice comptable, vous pouvez exporter les transactions comptables pour l'année clôturée en appliquant le filtre de date approprié et en exportant les transactions financières dans la période indiquée vers le fichier XML. Le fichier XML ../../ inclut toutes les informations de la transaction comptable, comme la date de validation du document, le type et le numéro du document, le type et le numéro de compte, les montants en crédit et en débit extraits de la fenêtre **Feuille comptabilité**."
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
ms.openlocfilehash: 6adcc30d843dc5203283e4d5824fdb8f63dc0989
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-general-ledger-entries-to-an-xml-file"></a><span data-ttu-id="3e2b3-105">Procédure d'exportation des écritures comptables vers un fichier XML</span><span class="sxs-lookup"><span data-stu-id="3e2b3-105">How to: Export General Ledger Entries to an XML File</span></span>
<span data-ttu-id="3e2b3-106">Pour l'archivage externe, et pour une période donnée, vous pouvez exporter des transactions financières vers un fichier XML.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-106">You can export financial transactions for a particular period to an XML file for external archiving.</span></span> <span data-ttu-id="3e2b3-107">À la fin de l'exercice comptable, vous pouvez exporter les transactions comptables pour l'année clôturée en appliquant le filtre de date approprié et en exportant les transactions financières dans la période indiquée vers le fichier XML.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-107">After the closing of the fiscal year, you can export the general ledger transactions for the closed year by applying the correct date filter and then exporting the financial transactions within the specified period to the XML file.</span></span> <span data-ttu-id="3e2b3-108">Le fichier XML ../../ inclut toutes les informations de la transaction comptable, comme la date de validation du document, le type et le numéro du document, le type et le numéro de compte, les montants en crédit et en débit extraits de la fenêtre **Feuille comptabilité**.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-108">The XML file ../../includes all the general ledger transaction information, such as document posting date, document type, document number, account type, account number, credit amount, and debit amount retrieved from the **General Journal** window.</span></span>  
  
### <a name="to-export-general-ledger-entries-to-an-xml-file"></a><span data-ttu-id="3e2b3-109">Pour exporter des écritures comptables vers un fichier XML</span><span class="sxs-lookup"><span data-stu-id="3e2b3-109">To export general ledger entries to an XML file</span></span>  
  
1.  <span data-ttu-id="3e2b3-110">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Exporter écritures comptables vers un fichier XML**, puis choisissez le lien approprié.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Export G/L Entries to XML**, and then choose the relevant link.</span></span>  
  
2.  <span data-ttu-id="3e2b3-111">Dans la fenêtre **Exporter écritures comptables vers un fichier XML**, sur le raccourci **Options**, renseignez les champs comme indiqué dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-111">In the **Export G/L Entries to XML** window, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="3e2b3-112">Champ</span><span class="sxs-lookup"><span data-stu-id="3e2b3-112">Field</span></span>|<span data-ttu-id="3e2b3-113">Désignation</span><span class="sxs-lookup"><span data-stu-id="3e2b3-113">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="3e2b3-114">**Date début**</span><span class="sxs-lookup"><span data-stu-id="3e2b3-114">**Starting Date**</span></span>|<span data-ttu-id="3e2b3-115">Définit la date de début pour exporter les transactions financières.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-115">Sets the starting date to export the financial transactions.</span></span>|  
    |<span data-ttu-id="3e2b3-116">**Date fin**</span><span class="sxs-lookup"><span data-stu-id="3e2b3-116">**Ending Date**</span></span>|<span data-ttu-id="3e2b3-117">Définit la date de fin pour exporter les transactions financières.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-117">Sets the ending date to export the financial transactions.</span></span>|  
  
3.  <span data-ttu-id="3e2b3-118">Pour exporter le fichier, cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-118">To export the file, choose the **OK** button.</span></span>  
  
     <span data-ttu-id="3e2b3-119">Vous pouvez enregistrer le fichier généré dans un emplacement spécifié, ou vous pouvez ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-119">You can save the generated file to a specified location, or you can open the file.</span></span>  
  
    > [!WARNING]  
    >  <span data-ttu-id="3e2b3-120">Si vous avez défini les dates de début et de fin pour inclure l'exercice comptable complet, le processus peut prendre quelques minutes.</span><span class="sxs-lookup"><span data-stu-id="3e2b3-120">If you have set the start date and end date to include the entire fiscal year, the process can take several minutes.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="3e2b3-121">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="3e2b3-121">See Also</span></span>  
 [<span data-ttu-id="3e2b3-122">Procédure : imprimer des états comptables</span><span class="sxs-lookup"><span data-stu-id="3e2b3-122">How to: Print General Ledger Reports</span></span>](how-to-print-general-ledger-reports.md)
