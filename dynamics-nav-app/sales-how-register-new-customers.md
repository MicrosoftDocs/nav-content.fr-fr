---
title: "Procédure : enregistrer de nouveaux clients"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 191a9d0b38425c2e36400050afa4fa89ccd2556a
ms.contentlocale: fr-fr
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-register-new-customers"></a>Procédure : enregistrer de nouveaux clients
Les clients sont l'origine de vos revenus. Chaque client auquel vous vendez un élément doit être enregistré en tant que fiche client.

Avant de pouvoir enregistrer de nouveaux clients, vous devez configurer divers codes vente que vous pouvez sélectionner lorsque vous renseignez les fiches client. Pour plus d'informations, reportez-vous à [Configuration des ventes](sales-setup-sales.md).

Les fiches client contiennent les informations nécessaires à la vente de biens au client. Pour plus d'informations, reportez-vous à [Procédure : facturation des ventes](sales-how-invoice-sales.md) et à [Procédure : enregistrer de nouveaux produits](inventory-how-register-new-products.md).

**Remarque**: si des modèles client existent pour différents types de clients, une fenêtre s'affiche lorsque vous créez une nouvelle fiche client à partir de laquelle vous pouvez sélectionner un modèle client approprié. Si un seul modèle client existe, les nouvelles fiches client utiliseront toujours ce modèle.

## <a name="to-create-a-new-customer-card"></a>Pour créer une fiche client
1. Sur la page d'accueil, sélectionnez l'action **Clients** pour ouvrir la liste des clients existants.  
2. Dans la fenêtre **Clients**, sélectionnez l'action **Nouveau**.

    Si un seul modèle client existe, une nouvelle fiche client avec certains champs renseignés à l'aide des informations provenant du modèle s'ouvre.

    Si plusieurs modèles client existent, une fenêtre s'affiche et vous permet de sélectionner un modèle client. Dans ce cas, suivez les deux étapes suivantes.
3. Dans la fenêtre **Sélectionnez un modèle pour un nouveau client**, sélectionnez le modèle que vous souhaitez utiliser pour la nouvelle fiche client.
4. Cliquez sur le bouton **OK**. Une fiche client avec certains champs contenant les informations provenant de ce modèle s'ouvre.  
5. Renseignez ou modifiez les champs de la fiche client selon vos besoins. Choisissez un champ pour lire une brève description du champ ou du lien vers plus d'informations.

Sur le raccourci **Prix vente**, vous pouvez afficher les prix spéciaux ou les remises accordées au client si certains critères sont réunis, par exemple l'article, la quantité minimum commande ou la date de fin. Chaque ligne représente un prix spécial ou une remise ligne. Chaque colonne représente un critère qui doit s'appliquer pour garantir le prix spécial que vous saisissez dans le champ **Prix** ou la remise ligne que vous saisissez dans le champ **% remise ligne**. Pour plus d'informations, reportez-vous à [Enregistrement des prix de vente, des remises et des accords sur les paiements](sales-how-record-sales-price-discount-payment-agreements.md).

Le client est désormais enregistré, et la fiche client est prête à être utilisée sur les documents vente.

Si vous souhaitez utiliser cette fiche client comme modèle lorsque vous créez de nouvelles fiches client, enregistrez-la comme modèle. Pour plus d'informations, reportez-vous à la section suivantes.

## <a name="to-save-the-customer-card-as-a-template"></a>Pour enregistrer la fiche client en tant que modèle
1. Dans la fenêtre **Fiche client**, sélectionnez l'action **Sauvegarder comme modèle**. La fenêtre **Modèle client** s'ouvre et affiche la fiche client comme modèle.
2. Renseignez les champs selon vos besoins. Choisissez un champ pour lire une brève description du champ ou du lien vers plus d'informations.
3. Pour réutiliser les axes analytiques dans les modèles **, sélectionnez l'action **Axes analytiques**. La fenêtre **Modèles axe** s'ouvre et affiche tous les codes axe qui sont définis pour le client.
4. Modifiez ou entrez les codes axe s'appliquant aux nouvelles fiches client créées à l'aide du modèle.  
5. Lorsque vous avez terminé le nouveau modèle client, cliquez sur le bouton **OK**.

Le modèle client est ajouté à la liste des modèles client. Vous pouvez ainsi l'utiliser pour créer des fiches client.

## <a name="see-also"></a>Voir aussi  
[Gestion des ventes](sales-manage-sales.md)    
[Configuration des ventes](sales-setup-sales.md)    
[Utiliser Dynamics NAV](ui-work-product.md)
