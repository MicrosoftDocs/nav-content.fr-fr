---
title: "Valider des paiements par prélèvement SEPA"
description: "Lorsqu'une collection prélèvement automatique est correctement traitée par votre banque, vous pouvez procéder à la validation de la réception du paiement pour les factures vente impliquées."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9b0e82feb77be2e66b618aab7322215637d4f89e
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-post-sepa-direct-debit-payment-receipts"></a>Procédure : valider des réceptions règlement de prélèvement SEPA
Lorsqu'une collection prélèvement automatique est correctement traitée par votre banque, vous pouvez procéder à la validation de la réception du paiement pour les factures vente impliquées. Pour plus d'informations, voir [Procédure : créer des écritures de collection prélèvement automatique SEPA et les exporter vers un fichier bancaire](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).  

Vous pouvez valider la réception paiement directement à partir de la fenêtre **Recouvrements prélèvement** ou de la fenêtre **Écritures recouvrement prélèvement**. Vous pouvez également relayer le travail à un autre utilisateur en préparant les lignes feuille associées.  

## <a name="to-post-a-direct-debit-payment-receipt-from-the-direct-debit-collections-window"></a>Pour valider une réception de paiement de prélèvement automatique à partir de la fenêtre Collections prélèvement automatique  
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Recouvrements prélèvement**, puis sélectionnez le lien connexe.  
2. Sélectionnez une ligne pour une collection prélèvement automatique qui a été exportée vers un fichier bancaire et traitée avec succès par la banque. Pour plus d'informations, voir [Procédure : créer des écritures de collection prélèvement automatique SEPA et les exporter vers un fichier bancaire](finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).  
3. Sélectionnez l'action **Valider reçus paiement**.  
4. Dans la fenêtre **Valider recouvrement prélèvement**, renseignez les champs comme indiqué dans le tableau suivant.  

    |Champ|Désignation|  
    |---------------------------------|---------------------------------------|  
    |**N° recouvrement prélèvement**|Spécifie la collection prélèvement automatique pour laquelle vous souhaitez valider la réception paiement.|  
    |**Modèle feuille comptabilité**|Spécifie le modèle de feuille comptabilité à utiliser pour la validation de la réception du paiement, comme le modèle pour les encaissements.|  
    |**Nom feuille comptabilité**|Spécifie la feuille comptabilité à utiliser pour la validation de la réception du paiement.|  
    |**Créer feuille uniquement**|Activez cette case à cocher si vous ne souhaitez pas valider la réception règlement lorsque vous cliquez sur le bouton **OK**. La réception de paiements est préparée dans la feuille spécifiée et n'est pas validée jusqu'à ce qu'une personne valide les lignes feuille en question.|  

5. Cliquez sur le bouton **OK**.  

## <a name="see-also"></a>Voir aussi  
 [Recouvrement de paiements par prélèvement automatique SEPA](finance-collect-payments-with-sepa-direct-debit.md)   
 [Ventes](sales-manage-sales.md)

