---
title: "Créer une commande vente et vendre des produits"
description: "Décrit comment créer une commande vente pour enregistrer votre contrat avec un client pour vendre ou commercialiser des produits dans des conditions spécifiques."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: trade
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1371f7a1d1e5b5c9bd0add845d37e194db86218d
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-sell-products"></a>Procédure : vendre des produits
Vous créez une commande vente ou une facture vente pour enregistrer votre accord avec un client pour vendre certains produits selon certaines conditions de livraison et de paiement.

> [!NOTE]  
>   Vous utilisez des commandes vente si votre processus de vente requiert que vous expédiiez des parties d'une quantité de commande, par exemple, si la quantité totale est pas disponible d'un coup. Si vous commercialisez des articles en les livrant directement du fournisseur au client, vous devez également utiliser les commandes vente. Pour plus d'informations, voir [Procédure : effectuer des livraisons directes](sales-how-drop-shipment.md). Pour tous les autres aspects, les commandes vente fonctionnent de la même manière que les factures vente. Pour plus d'informations, reportez-vous à [Procédure : facturer des ventes](sales-how-invoice-sales.md).

Vous pouvez négocier avec le client en créant d'abord un devis, que vous pouvez convertir en commande vente lorsque vous êtes d'accord sur la vente. Pour plus d'informations, voir [Procédure : créer des offres](sales-how-make-offers.md).

Une fois que le client a confirmé l'accord, par exemple après une procédure de devis, vous pouvez envoyer une confirmation de commande pour enregistrer votre obligation de fournir les produits comme convenu.

Lorsque vous fournissez les produits, entièrement ou partiellement, vous validez la commande vente comme étant expédiée ou expédiée et facturée pour créer l'article et les écritures comptables client associés dans votre système. Lorsque vous validez la commande vente, vous pouvez également envoyer par e-mail le document en pièce jointe au format PDF. Vous pouvez faire en sorte que le corps du message soit prérempli avec un résumé des informations de commande et de paiement, par exemple un lien vers Paypal. Pour plus d'informations, reportez vous à [Procédure : envoyer des documents par e-mail](ui-how-send-documents-email.md).

Dans les environnements d'entreprise où le client doit payer avant la livraison des produits vendus (par exemple la vente au détail), vous devez attendre la réception du paiement avant de fournir les produits. Dans la plupart des cas, vous traitez les paiements entrants plusieurs semaines après la livraison en lettrant les paiements à leurs factures vente validées et impayées associées. Pour plus d'informations, reportez-vous à [Procédure : rapprocher les paiements à l'aide de l'application automatique](receivables-how-reconcile-payments-auto-application.md).

Vous pouvez facilement corriger ou annuler une facture vente validée qui résulte d'une commande vente avant qu'elle soit payée. Cela est utile si vous souhaitez corriger une erreur de saisie, ou si le client demande une modification tôt dans le processus de commande. Pour plus d'informations, reportez-vous à [Procédure : corriger ou annuler des factures vente impayées](sales-how-correct-cancel-sales-invoice.md). Si la facture vente validée est payée, vous devez créer un avoir vente pour contrepasser la vente. Pour plus d'informations, reportez-vous à [Procédure : traiter les retours ou annulations de ventes](sales-how-process-sales-returns-cancellations.md).

Vous pouvez remplir les champs relatifs au client sur la commande vente de deux façons selon que le client est déjà enregistré ou non. Reportez-vous aux étapes 2 et 3 de la procédure ci-dessous.

## <a name="to-create-a-sales-order"></a>Pour créer une commande vente
1. Sur la page d'accueil, sélectionnez l'action **Commande vente**.  
2. Dans le champ **Client**, entrez le nom d'un client existant.

    D'autres champs de la fenêtre **Commande vente** sont désormais renseignés avec les informations standard sur le client sélectionné. Si le client n'est pas enregistré, procédez comme suit :
3. Dans le champ **Client**, entrez le nom du nouveau client.
4. Dans la boîte de dialogue d'enregistrement du nouveau client, cliquez sur le bouton **Oui**.
5. Dans la fenêtre **Sélectionnez un modèle pour un nouveau client**, sélectionnez un modèle sur lequel baser la nouvelle fiche client, puis cliquez sur le bouton **OK**.

    Une nouvelle fiche client préremplie avec les informations sur le modèle client sélectionné s'ouvre. Le champ **Nom** est prérempli avec le nom du nouveau client que vous avez saisi sur la commande vente.
6. Renseignez les autres champs de la fiche client. Pour plus d'informations, reportez vous à [Procédure : enregistrer de nouveaux clients](sales-how-register-new-customers.md).  
7. Lorsque vous avez terminé la fiche client, cliquez sur le bouton **OK** pour revenir à la fenêtre **Commande vente**.

    Plusieurs champs de la commande vente sont désormais renseignés avec les informations que vous avez spécifiées sur la nouvelle fiche client.
8. Renseignez les champs restants de la fenêtre **Commande vente**, selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    Vous êtes maintenant prêt à renseigner les lignes commande vente avec les articles en stock ou les services que vous voulez vendre au client.

    Si vous avez défini des lignes vente récurrentes pour le client, tel qu'un ordre de réapprovisionnement mensuel, vous pouvez insérer ces lignes sur la commande par l'intermédiaire de l'action **Extraire les lignes vente récurrentes**.
9. Dans le raccourci **Lignes**, dans le champ **Article**, entrez le numéro d'un article en stock ou d'un service.  
10. Dans le champ **Quantité**, saisissez le nombre d'articles à vendre.

    Le champ **Montant ligne** est mis à jour pour indiquer la valeur du champ **Prix unitaire** multipliée par la valeur du champ **Quantité**.

    Le prix et les montants ligne sont affichés avec ou sans la Sales Tax en fonction de la valeur que vous avez sélectionné dans le champ **Prix incluant les taxes** de la fiche client.
11. Dans le champ **% remise ligne**, saisissez un pourcentage si vous souhaitez accorder au client une remise sur le produit. La valeur du champ **Montant ligne** est mise à jour en conséquence.

    Si vous avez défini des prix article spéciaux sur le raccourci **Prix vente et remises ligne vente** dans la fiche client ou article, le prix et le montant de la ligne devis sont automatiquement mis à jour si les critères de prix convenus sont réunis. Pour plus d'informations, reportez-vous à [Enregistrement des prix de vente, des remises et des accords sur les paiements](sales-how-record-sales-price-discount-payment-agreements.md).
12. Pour ajouter un commentaire sur la ligne devis que le client peut afficher dans le devis vente imprimé, saisissez un texte dans le champ **Description** sur une ligne vierge.  
13. Répétez les étapes 10 à 13 pour chaque article que vous souhaitez proposer au client.

    Les totaux sous les lignes sont calculés automatiquement au fur et à mesure que vous créez ou modifiez des lignes.
6. Une nouvelle fiche client affiche des informations sur le modèle client sélectionné. Renseignez les champs restants. Pour plus d'informations, reportez vous à [Procédure : enregistrer de nouveaux clients](sales-how-register-new-customers.md).  
7. Lorsque vous avez terminé la fiche client, cliquez sur le bouton **OK** pour revenir à la fenêtre **Commande vente**.

   Plusieurs champs de la commande vente sont désormais renseignés avec les informations que vous avez spécifiées sur la nouvelle fiche client.  
8. Renseignez les champs restants de la fenêtre **Commande vente**, selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

   Vous êtes maintenant prêt à renseigner les lignes commande vente pour les produits que vous vendez au client ou pour toute transaction avec le client que vous souhaitez enregistrer dans un compte général.   

   Si vous avez défini des lignes vente récurrentes pour le client, tel qu'un ordre de réapprovisionnement mensuel, vous pouvez insérer ces lignes sur la commande par l'intermédiaire de l'action **Extraire les lignes vente récurrentes**.  
9. Sous le raccourci **Lignes**, dans le champ **Type**, sélectionnez le type de produit, de frais ou de transaction à valider pour le client avec la ligne vente.
10. Dans le champ **N°**, sélectionnez un enregistrement à valider en fonction de la valeur du champ **Type**.

    Laissez le champ **N°** vide dans les cas suivants : - Si la ligne est destinée à un commentaire. Saisissez le commentaire dans le champ **Description**.
    -Si la ligne est destinée à un article non stocké. Sélectionnez l'action **Sélectionner articles non stockés**. Pour en savoir plus, voir [Procédure : utiliser des articles non stockés](inventory-how-work-nonstock-items.md).

11. Dans le champ **Quantité**, entrez le nombre d'unités du produit, de frais ou de la transaction que la ligne enregistre pour le client.  

    > [!NOTE]  
>   Si l'article est de type **Article - Service** ou **Ressource**, la quantité est une unité de temps, telle que les heures, comme indiqué dans le champ **Code unité de la ligne**.  

    La valeur du champ **Montant ligne** est calculée comme suit : *Prix unitaire* x *Quantité*.  

    Le prix et les montants ligne sont affichés avec ou sans la taxe de vente en fonction de la valeur que vous avez sélectionnée dans le champ **Prix incluant les taxes** de la fiche client.  
12. Si vous souhaitez accorder une remise, saisissez un pourcentage dans le champ **% remise ligne**. La valeur du champ **Montant ligne** est mise à jour en conséquence.  

    Si des prix article spéciaux sont définis sur le raccourci **Prix vente et remises ligne vente** dans la fiche client ou article, le prix et le montant de la ligne vente sont automatiquement mis à jour si les critères de prix convenus sont réunis. Pour plus d'informations, reportez-vous à [Enregistrement des prix de vente, des remises et des accords sur les paiements](sales-how-record-sales-price-discount-payment-agreements.md).  
13. Répétez les étapes 9 à 12 pour chaque produit ou frais que vous souhaitez vendre au client.  

    Les totaux sous les lignes sont calculés automatiquement au fur et à mesure que vous créez ou modifiez des lignes.  
14. Dans le champ **Montant remise facture**, entrez un montant qui doit être déduit de la valeur indiquée dans le champ **Total TTC**.

    Si vous avez défini des remises facture pour le client, le pourcentage spécifié est automatiquement inséré dans le champ **% remise facture** si les critères sont réunis, et le montant associé est inséré dans le champ **Montant remise facture sans TVA**. Pour plus d'informations, reportez-vous à [Enregistrement des prix de vente, des remises et des accords sur les paiements](sales-how-record-sales-price-discount-payment-agreements.md).
15. Pour expédier seulement une partie de la quantité commandée, entrez la quantité dans le champ **Qté à expédier**. La valeur est copiée dans le champ **Qté à facturer**.
16. Pour facturer seulement une partie de la quantité expédiée, entrez la quantité dans le champ **Qté à facturer**. La quantité doit être inférieure à la valeur du champ **Qté à expédier**.   
17. Lorsque les lignes commande vente sont renseignées, sélectionnez l'action **Valider et envoyer**.

La boîte de dialogue **Valider et envoyer la confirmation** s'ouvre et indique le mode de réception de documents par défaut du client. Vous pouvez modifier le mode d'envoi en cliquant sur le bouton de recherche pour le champ **Envoyer le document à**. Pour plus d'informations, reportez vous à [Procédure : configurer des profils d'envoi de documents](sales-how-setup-document-send-profiles.md).

Les écritures comptables article et client associés sont à présent créés dans votre système, et la commande vente est sortie en tant que document au format PDF. Lorsque la commande vente est entièrement validée, elle est supprimée de la liste des commandes vente et remplacée par de nouveaux documents dans la liste des factures vente validées et la liste des expéditions vente enregistrées.

## <a name="see-also"></a>Voir aussi
[Ventes](sales-manage-sales.md)  
[Définition des ventes](sales-setup-sales.md)  
[Stock](inventory-manage-inventory.md)  
[Procédure : envoyer des documents par e-mail](ui-how-send-documents-email.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

