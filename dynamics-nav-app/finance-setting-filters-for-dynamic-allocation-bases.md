---
title: "Définition de filtres pour les bases de ventilation dynamique"
description: "Le mode de ventilation dynamique dépend des valeurs modifiables. Par exemple, le nombre de salariés dans un centre de coûts ou le nombre d'articles vendus d'un coût associé pour une période donnée. Il existe neuf bases de ventilation prédéfinies et douze plages de dates dynamiques. Vous définissez plusieurs filtres en fonction de la base de ventilation."
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
ms.openlocfilehash: 8372f855cfaa19456ab597e163006ae20411defd
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="setting-filters-for-dynamic-allocation-bases"></a>Définition de filtres pour les bases de ventilation dynamique
Le mode de ventilation dynamique dépend des valeurs modifiables. Par exemple, le nombre de salariés dans un centre de coûts ou le nombre d'articles vendus d'un coût associé pour une période donnée. Il existe neuf bases de ventilation prédéfinies et douze plages de dates dynamiques. Vous définissez plusieurs filtres en fonction de la base de ventilation.  

## <a name="setting-filters-for-dynamic-allocation-bases"></a>Définition de filtres pour les bases de ventilation dynamique  
 Le tableau suivant affiche les filtres applicables aux diverses bases de ventilation et les valeurs valides dans les champs **Filtre n°** et **Filtre groupe**. Appuyez sur F1 dans le champ **Code filtre date** pour lire les descriptions détaillées.  

|**Base**|**Filtre n°**|**Code filtre date**|**Filtre centre de coûts**|**Filtre coûts associés**|**Filtre groupe**|  
|--------------|----------------------------------------|----------------------------------------------|------------------------------------------------|------------------------------------------------|------------------------------------------|  
|Écritures comptables|Compte général|Oui|Oui|Oui|N/A|  
|Écritures budget|Compte général|Oui|Oui|Oui|Nom budget comptable|  
|Écritures du type de coût|Type coût|Oui|Oui|Oui|N/A|  
|Écritures budget des coûts|Type coût|Oui|Oui|Oui|Nom du budget|  
|Nombre de salariés|N/A|Oui|Oui|Oui|N/A|  
|Articles vendus (qté)|N° article|Oui|Oui|Oui|Groupe compta. stock|  
|Articles achetés (qté)|N° article|Oui|Oui|Oui|Groupe compta. stock|  
|Articles vendus (montant)|N° article|Oui|Oui|Oui|Groupe compta. stock|  
|Articles achetés (montant)|N° article|Oui|Oui|Oui|Groupe compta. stock|  

## <a name="see-also"></a>Voir aussi  
 [Exemple de scénario : définition des ventilations dynamiques sur la base des articles vendus](finance-scenario-example-defining-dynamic-allocations-based-on-items-sold.md)   
 [Procédure : configurer la source d'affectation et ses cibles](finance-how-to-set-up-allocation-source-and-targets.md)   
 [Définition et répartition des coûts](finance-define-and-allocate-costs.md)

