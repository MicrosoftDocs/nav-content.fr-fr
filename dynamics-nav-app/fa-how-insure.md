---
title: "Procédure : garantir des immobilisations"
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
ms.openlocfilehash: a3a59bc091042f72775b56fdd5bbe37ffa1a6d80
ms.contentlocale: fr-fr
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-insure-fixed-assets"></a>Procédure : garantir des immobilisations
Une police d'assurance pour une immobilisation est représentée par une fiche assurance. Vous pouvez attribuer une immobilisation ou plusieurs immobilisations à une police d'assurance.

Vous attribuez une immobilisation à une police d'assurance lors de la validation sur les écritures couverture assurance à partir de la fenêtre **Feuille assurance**.

En outre, vous pouvez attribuer une immobilisation à une police d'assurance et créer des écritures comptables de couverture lorsque vous validez son coût d'acquisition. Pour ce faire, validez un coût d'acquisition à partir de la feuille immobilisation où le champ **N° assurance** est renseigné. La case **Compta. assurance auto.** de la fenêtre **Paramètres immobilisations** doit être cochée. Pour en savoir plus, voir la section « Valider manuellement une acquisition d'immobilisation avec la feuille validation immobilisation » dans [Procédure : acquérir des immobilisations](fa-how-acquire.md).

Si la case **Compta. assurance auto.** n'est pas cochée dans la fenêtre **Paramètres immobilisations**, la validation des acquisitions à partir de la feuille immobilisation créera des lignes dans la fenêtre **Feuille assurance**, que vous devrez ensuite valider manuellement.

**Avertissement** : si vous ne cochez pas la case **Compta. assurance auto.** dans la fenêtre **Paramètres immobilisations**, votre feuille assurance devrait être basée sur un modèle feuille sans souche de numéros. En effet, les numéros de document insérés à partir de la ligne feuille immobilisation entreront sinon en conflit avec les souches de numéros de la feuille assurance. Pour en savoir plus concernant les modèles feuille et lots, voir [Procédure : configurer les informations générales relatives aux immobilisations](fa-how-setup-general.md).

Après avoir attribué une immobilisation à une police d'assurance, la case **Assuré** est cochée sur la fiche immobilisation. Lors de la vente de l'immobilisation, la case est automatiquement décochée.

## <a name="to-create-or-modify-an-insurance-card"></a>Pour créer ou modifier une fiche assurance
Une police d'assurance pour une immobilisation doit être représentée par une fiche assurance.

Lorsque vous recevez des informations concernant les modifications du montant de la couverture, vous pouvez saisir les nouvelles informations sur la **fiche assurance** afin de vous garantir que vous avez analysé correctement la couverture de la police d'assurance.  

1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, saisissez **Assurance**, puis sélectionnez le lien connexe.
2. Choisissez l'action **Nouveau** pour créer une fiche pour une police d'assurance. Choisissez un champ pour lire une brève description du champ ou du lien vers plus d'informations.
3. Sinon, sélectionnez la police d'assurance que vous souhaitez modifier, puis sélectionnez l'action **Modifier**.

## <a name="to-assign-a-fixed-asset-to-an-insurance-policy-by-posting-from-the-insurance-journal"></a>Pour affecter une immobilisation à une police d'assurance en effectuant une validation à partir de la feuille assurance
Vous affectez une immobilisation à une police d'assurance en validant sur les écritures couverture assurance.

La procédure suivante explique comment créer une ligne feuille assurance manuellement. Si la case **Compta. assurance auto.** est cochée dans la fenêtre **Paramètres immobilisations**, les lignes feuille assurance sont ensuite créées automatiquement lorsque vous validez des coûts d'acquisition. Dans ce cas, tout ce que vous avez à faire consiste à valider la feuille.

1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, entrez **Feuilles assurance**, puis sélectionnez le lien connexe.
2. Ouvrez la feuille pertinente, puis complétez les lignes feuille, le cas échéant.
3. Pour affecter plusieurs immobilisations à une police d'assurance, créez des lignes feuille avec la même valeur dans le champ **N° assurance** et différentes valeurs dans le champ **N° immo.** .
4. Sélectionnez l'action **Valider**.

**Remarque** : les écritures d'une feuille assurance sont uniquement validées en écritures couverture assurance.  

## <a name="to-update-the-insurance-value-of-a-fixed-asset"></a>Pour mettre à jour la valeur assurance d'une immobilisation
Vous pouvez utiliser le traitement par lots **Réévaluer assurance** pour mettre à jour la valeur des immobilisations couvertes.

1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, saisissez **Actualiser assurance**, puis sélectionnez le lien connexe.
2. Renseignez les champs selon vos besoins.

    **Remarque** : dans le champ **Taux de réévaluation**, vous saisissez une baisse de 5 %, par exemple, soit 95, tout en saisissant une hausse de 2 %, soit 102.  
3.  Cliquez sur le bouton **OK**.  

    Le traitement par lots calcule le nouveau montant en tant que pourcentage de la valeur totale assurée à partir de la fenêtre **Statistiques assurance**, puis crée une ligne dans la feuille assurance.  
4. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, entrez **Feuilles assurance**, puis sélectionnez le lien connexe.
5. Ouvrez la feuille assurance pertinente, examinez les valeurs créées, puis validez-les sur les écritures couverture assurance.

## <a name="to-monitor-insurance-coverage"></a>Pour surveiller la couverture assurance
Dynamics NAV fournit des rapports dédiés et des fenêtres de statistiques à utiliser pour analyser les polices d'assurance et si vos immobilisations sont sur- ou sous-assurées.

### <a name="overview-of-insurance-policies"></a>Aperçu des polices d'assurance  
Pour obtenir un aperçu de vos polices d'assurance, vous pouvez afficher un aperçu ou imprimer l'état **Assurances - Liste** qui vous indique toutes les polices et les champs les plus importants des fiches assurance.  

### <a name="insurance-coverage"></a>Couverture d'assurance
Pour visualiser les immobilisations couvertes par une assurance et à quelle hauteur, vous pouvez afficher l'aperçu ou imprimer l'état **Assurances - Valeur totale**.

### <a name="overunder-coverage"></a>Sur-assurance et sous-assurance
Vous pouvez vérifier si les immobilisations sont sur- ou sous-assurées comme suit :
- La fenêtre **Statistiques assurance**. Un montant positif dans le champ **Sur/Sous-assuré** signifie que l'immobilisation est sur-assurée. Un montant négatif signifie qu'elle est sous-assurée.
- La fenêtre **Statistiques immobilisation**. Choisissez le champ **Valeur totale assurée** pour afficher la fenêtre **Écritures comptables couverture assur.**.  
- L'état **Sur-assurance et sous-assurance**.  
- L'état **Assurance - Analyse**.

### <a name="uninsured-fixed-assets"></a>Immobilisations non assurées
Pour vérifier que toutes les immobilisations sont attribuées à une police d'assurance, vous pouvez imprimer ou afficher l'aperçu de l'état **Assurances - Immo. non assurées**. Cet état affiche les immobilisations pour lesquelles aucun montant n'a été validé sur des écritures couverture d'assurance.

## <a name="to-view-insurance-coverage-ledger-entries"></a>Pour visualiser des écritures comptables couverture assurance
Vous pouvez visualiser les écritures comptables couverture assurance que vous avez créées.  

1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, saisissez **Assurance**, puis sélectionnez le lien connexe.  
2. Sélectionnez la police d'assurance appropriée, puis sélectionnez l'action **Écritures comptables couverture**.

## <a name="to-view-the-total-insurance-value-of-fixed-assets"></a>Pour afficher la valeur d'assurance totale des immobilisations
Une fenêtre de matrice dédiée affiche les valeurs d'assurance qui sont enregistrées pour chaque police d'assurance pour chaque immobilisation suite aux montants d'assurance que vous avez validés.

1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, saisissez **Assurance**, puis sélectionnez le lien connexe.  
2. Sélectionnez la police d'assurance appropriée, puis sélectionnez l'action **Valeur totale assurée par immo.**.
3. Renseignez les champs selon vos besoins  
4. choisissez l'action **Afficher matrice**.  
5. Pour visualiser les écritures comptables couverture d'assurance, sélectionnez une valeur dans la matrice.

## <a name="to-correct-insurance-coverage-entries"></a>Pour corriger des écritures couverture assurance  
Si une immobilisation a été jointe à la mauvaise police d'assurance, vous pouvez y remédier en créant deux écritures de reclassement à partir de la feuille assurance.  

1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, entrez **Feuilles assurance**, puis sélectionnez le lien connexe.
2. Créez une ligne feuille pour l'immobilisation et la police d'assurance appropriée lorsque la valeur du champ **Montant** est positive.
3. Créez une autre ligne feuille pour l'immobilisation et la police d'assurance incorrecte lorsque la valeur du champ **Montant** est négative.  
4. Sélectionnez l'action **Valider**.

L'immobilisation sera détachée de la police d'assurance incorrecte, sur la seconde ligne, et rattachée à la police d'assurance correcte, sur la première ligne.

## <a name="see-also"></a>Voir aussi
[Gérer des immobilisations](fa-manage.md)  
[Configurer des immobilisations](fa-setup.md)  
[Finance](finance-setup.md)  
[Bienvenue dans Dynamics NAV](across-get-started.md)
