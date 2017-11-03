---
title: "Procédure d'exportation des écritures comptables vers un fichier XML"
description: "Pour l'archivage externe, et pour une période donnée, vous pouvez exporter des transactions financières vers un fichier XML."
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
ms.openlocfilehash: 436a9ca6115c59f66e9047acd29c6ed7deaacbd7
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-export-general-ledger-entries-to-an-xml-file"></a><span data-ttu-id="ad3f9-103">Procédure d'exportation des écritures comptables de la comptabilité vers un fichier XML</span><span class="sxs-lookup"><span data-stu-id="ad3f9-103">How to: Export General Ledger Entries to an XML File</span></span>
<span data-ttu-id="ad3f9-104">Pour l'archivage externe, et pour une période donnée, vous pouvez exporter des transactions financières vers un fichier XML.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-104">You can export financial transactions for a particular period to an XML file for external archiving.</span></span> <span data-ttu-id="ad3f9-105">À la fin de l'exercice comptable, vous pouvez exporter les transactions comptables pour l'année clôturée en appliquant le filtre de date approprié et en exportant les transactions financières dans la période indiquée vers le fichier XML.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-105">After the closing of the fiscal year, you can export the general ledger transactions for the closed year by applying the correct date filter and then exporting the financial transactions within the specified period to the XML file.</span></span> <span data-ttu-id="ad3f9-106">Le fichier XML inclut toutes les informations de la transaction comptable, comme la date de validation du document, le type et le numéro du document, le type et le numéro de compte, les montants en crédit et en débit extraits de la fenêtre **Feuille comptabilité**.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-106">The XML file includes all the general ledger transaction information, such as document posting date, document type, document number, account type, account number, credit amount, and debit amount retrieved from the **General Journal** window.</span></span>  

## <a name="to-export-general-ledger-entries-to-an-xml-file"></a><span data-ttu-id="ad3f9-107">Pour exporter des écritures comptables vers un fichier XML</span><span class="sxs-lookup"><span data-stu-id="ad3f9-107">To export general ledger entries to an XML file</span></span>  

1.  <span data-ttu-id="ad3f9-108">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Exporter écritures comptables vers un fichier XML**, puis choisissez le lien approprié.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-108">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Export G/L Entries to XML**, and then choose the relevant link.</span></span>  
2.  <span data-ttu-id="ad3f9-109">Dans la fenêtre **Exporter écritures comptables vers un fichier XML**, sur le raccourci **Options**, renseignez les champs comme indiqué dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-109">In the **Export G/L Entries to XML** window, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="ad3f9-110">Champ</span><span class="sxs-lookup"><span data-stu-id="ad3f9-110">Field</span></span>|<span data-ttu-id="ad3f9-111">Désignation</span><span class="sxs-lookup"><span data-stu-id="ad3f9-111">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="ad3f9-112">**Date début**</span><span class="sxs-lookup"><span data-stu-id="ad3f9-112">**Starting Date**</span></span>|<span data-ttu-id="ad3f9-113">Définit la date de début pour exporter les transactions financières.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-113">Sets the starting date to export the financial transactions.</span></span>|  
    |<span data-ttu-id="ad3f9-114">**Date fin**</span><span class="sxs-lookup"><span data-stu-id="ad3f9-114">**Ending Date**</span></span>|<span data-ttu-id="ad3f9-115">Définit la date de fin pour exporter les transactions financières.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-115">Sets the ending date to export the financial transactions.</span></span>|  

3.  <span data-ttu-id="ad3f9-116">Pour exporter le fichier, cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-116">To export the file, choose the **OK** button.</span></span>  

<span data-ttu-id="ad3f9-117">Vous pouvez enregistrer le fichier généré dans un emplacement spécifié, ou vous pouvez ouvrir le fichier.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-117">You can save the generated file to a specified location, or you can open the file.</span></span>  

> [!WARNING]  
>  <span data-ttu-id="ad3f9-118">Si vous avez défini les dates de début et de fin pour inclure l'exercice comptable complet, le processus peut prendre quelques minutes.</span><span class="sxs-lookup"><span data-stu-id="ad3f9-118">If you have set the start date and end date to include the entire fiscal year, the process can take several minutes.</span></span>  

## <a name="see-also"></a><span data-ttu-id="ad3f9-119">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="ad3f9-119">See Also</span></span>  
[<span data-ttu-id="ad3f9-120">Procédure : imprimer des états comptables</span><span class="sxs-lookup"><span data-stu-id="ad3f9-120">How to: Print General Ledger Reports</span></span>](how-to-print-general-ledger-reports.md)

