---
title: "Tâches de rapprochement de comptes bancaires et de lettrage de paiements d'écritures connexes"
description: "Décrit les tâches de rapprochement de vos comptes bancaires, client, et fournisseur, valider des règlements ou des frais, et lettrer des paiements automatiquement."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment process, direct payment posting, reconcile payment, expenses, cash receipts
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 33c0661a2ebf9b8d9b817c026a8c9abf0f0eff91
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---
# <a name="applying-payments-automatically-and-reconciling-bank-accounts"></a>Lettrage automatique des paiements et rapprochement des comptes bancaires
Vous devez régulièrement rapprocher vos comptes bancaires, créances client et créances fournisseur dans Project en lettrant les paiements enregistrés au niveau de la banque à leurs factures impayées et avoirs associés ou à d'autres écritures ouvertes dans [!INCLUDE[d365fin](includes/d365fin_long_md.md)].  

Vous pouvez effectuer cette tâche dans la fenêtre **Feuille rapprochement bancaire** en important un fichier ou un flux de relevé bancaire pour enregistrer rapidement les paiements. Les paiements sont lettrés pour ouvrir des écritures client ou fournisseur selon les correspondances entre le texte de paiement et les informations d'écriture. Vous pouvez réviser et modifier les lettrages automatiques avant de valider la feuille. Vous pouvez choisir de clôturer les écritures comptables compte bancaire ouvertes associées aux écritures comptables lettrées lorsque vous validez la feuille. Le compte bancaire est automatiquement rapproché lorsque tous les paiements sont lettrés.  

Pour importer des relevés bancaires sous forme de flux bancaire, vous devez d'abord configurer et activer le service de conversion des données bancaires. Pour plus d'informations, reportez-vous à [Procédure : configurer le service de conversion de données bancaires](bank-how-setup-bank-data-conversion-service.md).  

Le tableau suivant décrit une série de tâches et inclut des liens vers les rubriques qui les décrivent.  

| Pour | Voir |
| --- | --- |
| Lettrer des paiements aux écritures comptables client ou fournisseur ouvertes en important un relevé bancaire, et rapprocher le compte bancaire lorsque tous les paiements sont lettrés. |[Procédure : rapprocher les paiements à l'aide du lettrage automatique](receivables-how-reconcile-payments-auto-application.md) |
| Appliquer manuellement les paiements en affichant les informations détaillées sur les données de correspondance et des suggestions d'écritures ouvertes candidates à l'application des paiements. |[Procédure : réviser ou lettrer les paiements après un lettrage automatique](receivables-how-review-apply-payments-auto-application.md) |
| Résoudre les paiements qui ne peuvent pas être lettrés automatiquement à leurs écritures comptables ouvertes associées. Par exemple si les montants sont différents ou si une écriture comptable associée n'existe pas. |[Procédure : rapprocher les paiements qui ne peuvent pas être lettrés automatiquement](receivables-how-reconcile-payments-cannot-apply-auto.md) |
| Lier le texte des paiements à un client spécifique, fournisseur ou comptes généraux pour toujours valider les réceptions récurrentes en liquide ou les dépenses vers ces comptes quand ils ne peuvent être appliqués à aucun document. |[Procédure : mapper du texte sur les paiements récurrents aux comptes pour un rapprochement automatique](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md) |

## <a name="see-also"></a>Voir aussi
[Gestion des comptes client](receivables-manage-receivables.md)  
[Ventes](sales-manage-sales.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

