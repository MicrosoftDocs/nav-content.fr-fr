---
title: Utilisation de l'extension d'analyseur Image
description: Cette extension vous permet d'analyser des photos des contacts et des articles permettant de rechercher des attributs, afin de les trouver rapidement dans Dynamics NAV.
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: API, extension, Cognitive Services, image, computer vision, attribute, tag, recognition
ms.date: 06/19/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 08a832708dcbb550e880d2a669af265b2fb670b5
ms.contentlocale: fr-fr
ms.lasthandoff: 10/23/2017

---

# <a name="the-image-analyzer-extension-for-includenavnowincludesnavnowmdmd"></a>L'extension d'analyseur Image pour [!INCLUDE[navnow](includes/navnow_md.md)]
L'extension d'analyseur Image utilise les analyses d'image puissantes fournies par l'API Vision par ordinateur de Microsoft Cognitive Services pour détecter des attributs dans les images que vous importez pour des articles et des contacts, afin de les examiner et de les affecter facilement. Pour les articles, les attributs peuvent être si l'article est une table ou une voiture et, s'il est rouge ou bleu. Pour les contacts, les attributs peuvent être le sexe ou l'âge.

L'analyseur Image propose des attributs basés sur des balises trouvées par l'API Vision par ordinateur et un niveau de confiance. Par défaut, il propose des attributs uniquement s'il est sûr à au moins 80 % que l'attribut est correct. Vous pouvez définir un autre niveau de confiance, si nécessaire. Pour en savoir plus sur la manière dont les balises et le niveau de confiance sont déterminés, voir [API Vision par ordinateur](https://go.microsoft.com/fwlink/?linkid=851476).  

L'analyseur Image est gratuit dans [!INCLUDE[d365fin](includes/d365fin_md.md)], mais il existe une limite au nombre d'articles que vous pouvez analyser pendant une période donnée. Par défaut, vous pouvez analyser 100 images par mois.

Après avoir activé l'extension, l'analyseur Image fonctionne chaque fois que vous importez une image à un article ou à un contact. Vous pourrez consulter les attributs, le niveau de confiance et les détails immédiatement, et décider de gérer chaque attribut. Si vous avez importé des images avant d'activer l'extension d'analyseur Image, vous devez consulter la fiche article ou contact et choisir l'action **Analyser l'image**.  

>   [!NOTE]  
>   En activant cette extension, vous convenez que Microsoft peut enregistrer vos données et les utiliser pour améliorer les services de Microsoft, tels qu'améliorer l'API Vision par ordinateur. Pour vous aider à protéger votre confidentialité, nous prenons des mesures pour déclarer vos données de manière anonymes et de les sécuriser. Nous ne publierons pas vos données, ni ne laissons d'autres personnes les utiliser. Vous pouvez supprimer l'image de l'article dans [!INCLUDE[d365fin](includes/d365fin_md.md)], cependant, l'API Vision par ordinateur aura toujours l'image dans son formulaire qui n'est plus identifié. Pour plus d'informations, voir [Microsoft Trust Center](https://go.microsoft.com/fwlink/?linkid=851463).

## <a name="requirements"></a>Conditions requises
Certaines exigences s'appliquent aux images :

* Formats des images : JPEG, PNG, GIF, BMP  
* Taille maxi. de fichier : inférieure à 4 Mo  
* Dimensions des images : supérieure à 50 x 50 pixels  

## <a name="blacklisting-suggested-attributes"></a>Placement des attributs suggérés sur la liste noire
Si l'analyse suggère un attribut que vous ne souhaitez pas voir, vous pouvez le mettre sur la liste noire. Faites attention, cependant. Les attributs mis sur la liste noire ne sont pas proposés pour d'autres articles ou contacts. Si vous regrettez d'avoir placé un attribut sur la liste noire, vous pouvez choisir **Attributs mis sur la liste noire**, puis supprimer l'attribut de la liste.

## <a name="to-enable-image-analyzer"></a>Pour activer l'analyseur Image
L'extension d'analyseur Image est intégrée à [!INCLUDE[d365fin](includes/d365fin_md.md)]. Vous devez juste l'activer.

> [!NOTE]  
> Pour activer l'extension d'analyseur Image, vous devez être un administrateur. Assurez-vous que vous disposez de l'ensemble d'autorisations d'utilisateur **SUPER**.

1. Pour activer l'extension d'analyseur Image, effectuez l'une des actions suivantes :

* Ouvrez une fiche Article ou Contact. Dans la barre de notification, choisissez **Analyser les images**, puis suivez la procédure du guide de configuration assistée.  
* Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Connexions au service**, puis sélectionnez **Configuration de l’analyse de l’image**. Activez la case à cocher **Activer l'analyseur Image**, puis suivez la procédure du guide de configuration assistée.  

>   [!TIP]  
>   La page **Configuration de l’analyse de l’image** vous permet également de modifier le degré de confiance des suggestions d'attribut. Par exemple, si vous souhaitez avoir besoin d'un niveau de confiance supérieur, vous pouvez saisir un pourcentage plus élevé.

## <a name="to-analyze-an-image-of-an-item"></a>Pour analyser la photo d'un article
Les étapes suivantes décrivent comment analyser une image importée avant que vous ayez activé l'extension d'analyseur Image.  

1. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Articles**, puis sélectionnez le lien connexe.  
2. Sélectionnez l'article, puis cliquez sur **Analyser l'image**.  
3. La page **Attributs d'analyseur Image** affiche les attributs détectés, le niveau de confiance, et d'autres détails sur l'attribut. Utilisez les options **Action à effectuer** pour définir quelle action exécuter avec l'attribut.  

>   [!TIP]  
>   Vous pouvez ajouter le nom de l'attribut à la description de l'article en choisissant **Ajouter à la description de l'article**. Par exemple, cela peut être utile pour ajouter rapidement un détail.  

## <a name="to-analyze-a-picture-of-a-contact-person"></a>Pour analyser la photo d'un contact
Les étapes suivantes décrivent comment analyser une image importée avant que vous ayez activé l'extension d'analyseur Image.  

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Contacts**, puis sélectionnez le lien connexe.  
2. Sélectionnez le contact, puis cliquez sur **Analyser l'image**.  
3. Sur le raccourci **Questionnaire profil**, consultez les suggestions, et faites des corrections si nécessaire.  

## <a name="to-use-your-own-account-for-the-computer-vision-api"></a>Pour utiliser vôtre propre compte pour l'API Vision par ordinateur
Vous pouvez également utiliser votre propre compte pour l'API Vision par ordinateur, par exemple, si vous souhaitez analyser plus d'images qu'autorisé.  

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Configuration de l'analyseur Image**, puis sélectionnez le lien connexe.  
2. Entrez l'**URI d'API** et la **clé d'API** que vous avez reçus pour l'API Vision par ordinateur.  

>   [!NOTE]  
>   Vous devez ajouter **/analyze** à la fin de l'URI d'API, si ce n'est pas déjà le cas. Par exemple : ```https://cronus.api.cognitive.microsoft.com/vision/v1.0/analyze```

## <a name="to-see-how-many-analyses-you-have-left-in-the-current-period"></a>Pour visualiser le nombre d'analyses restant pour la période en cours
Vous pouvez afficher le nombre d'analyses effectué, et le nombre restant, pour la période actuelle.  

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Configuration de l'analyseur Image**, puis sélectionnez le lien connexe.  
2. **Type limite**, **Valeur limite** et **Analyses effectuées** vous fournissent des informations sur l'utilisation.  

## <a name="to-stop-using-the-image-analyzer-extension"></a>Pour arrêter d'utiliser l'extension d'analyseur Image
1. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Connexions au service**, puis sélectionnez **Configuration de l’analyseur Image**.  
2. Désactivez la case à cocher **Activer l'analyseur Image**.  

## <a name="see-also"></a>Voir aussi
[Procédure : utilisation des attributs d'article](inventory-how-work-item-attributes.md)  
[Personnalisation de [!INCLUDE[d365fin](includes/d365fin_md.md)] à l'aide des extensions](ui-extensions.md)  
[Bienvenue dans [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)  

