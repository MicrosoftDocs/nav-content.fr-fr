---
title: "Périodes fiscales et exercices comptables"
description: "Un exercice comptable est généralement divisé en 12 périodes fiscales mensuelles. Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], deux exercices comptables peuvent être ouverts en même temps."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: c7c79cd2a33bb2018f18b01112828d31d94ee771
ms.contentlocale: fr-fr
ms.lasthandoff: 10/26/2017

---
# <a name="fiscal-periods-and-fiscal-years"></a>Périodes fiscales et exercices comptables
Un exercice comptable est généralement divisé en 12 périodes fiscales mensuelles. Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], deux exercices comptables peuvent être ouverts en même temps. Vous ne pouvez pas créer un troisième exercice comptable si deux exercices comptables sont ouverts.  

Pour clôturer un exercice comptable, vous devez clôturer les périodes comptables de cet exercice.  

Vous ne pouvez rouvrir une période comptable clôturée que si elle fait partie d'un exercice comptable ouvert. Pour plus d'informations, voir [Procédure : clôturer des exercices](how-to-close-years.md). Vous ne pouvez pas rouvrir un exercice comptable clôturé.  

## <a name="closing-fiscal-periods-and-fiscal-years"></a>Clôture de périodes fiscales et d'exercices comptables  
À la fin d'un exercice comptable, vous devez clôturer les périodes comptables de cet exercice comptable. Cela garantit que des écritures comptables ne sont pas validées pour cette période. Pour plus d'informations, voir [Procédure : clôturer fiscalement des périodes comptables](how-to-fiscally-close-years.md).  

Un exercice comptable peut être clôturé si tous les critères suivants sont remplis :  

- Les dates comptabilisation dans la fenêtre **Paramètres utilisateur** et la fenêtre **Paramètres comptabilité** ne font pas partie de l'exercice que vous clôturez. Pour plus d'informations, voir Paramètres utilisateur et Paramètres comptabilité.  

- L'exercice comptable a été clôturé à l'aide de la fonction **Clôturer exercice** dans la fenêtre **Périodes comptables**. Pour plus d'informations, voir [Clôture des exercices et des périodes](../../year-close-years-periods.md).  

- Toutes les lignes feuille non validées et les écritures de simulation de l'exercice ont été validées ou supprimées.  

- Toutes les écritures de clôture sont à jour.  

Lorsque vous clôturez une période fiscale, la plus ancienne période fiscale ouverte est clôturée. Le champ **Début période validation** dans la fenêtre **Paramètres comptabilité** est mis à jour avec la date de début de la période ouverte suivante, si la date existante dans ce champ n'est pas déjà une date postérieure. Si le champ **Fin période validation** dans la fenêtre **Paramètres comptabilité** se situe dans la période clôturée, la valeur du champ **Fin période validation** est mise à jour avec la date de fin de la première période fiscale ouverte. Pour plus d'informations, voir Paramètres comptabilité.  

À la fin de l'exercice, vous devez effectuer les opérations suivantes :  

- clôturer l'exercice comptable à l'aide de la fonction **Clôturer exercice** ;  
- générer une écriture de clôture d'exercice ;  
- valider l'écriture de clôture d'exercice et compenser les écritures comptables de fonds propres ;  
- clôturer l'exercice comptable à l'aide de la fonction **Clôturer l'exercice fiscalement**.  

## <a name="see-also"></a>Voir aussi  
 [Procédure : valider l'écriture de clôture d'exercice](how-to-post-the-year-end-closing-entry.md)   
 [Procédure : clôturer fiscalement des périodes comptables](how-to-fiscally-close-accounting-periods.md)   
 [Clôture des exercices et des périodes](../../year-close-years-periods.md)   
 [Procédure : valider l'écriture de clôture d'exercice](how-to-post-the-year-end-closing-entry.md)   
 [Procédure : clôturer fiscalement des exercices](how-to-fiscally-close-years.md)   
 [Procédure : rouvrir des périodes comptables](how-to-reopen-accounting-periods.md)   
 [Procédure : Clôturer les comptes de gestion](how-to-close-income-statement-accounts.md)   
 [Fonctionnalité locale, France](france-local-functionality.md)

