---
title: "Importer vos données métier héritées dans Dynamics NAV"
description: "Vous pouvez migrer les données des clients, des fournisseurs et du stock, par exemple, à partir d'Excel, QuickBooks ou Dynamics GP vers Dynamics NAV."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: migrate, initialize, implement
ms.date: 09/25/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b19a05fba8a940dad4dcb6c8aebbefdcae67c324
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="importing-business-data-from-other-finance-systems"></a>Importation des données métier à partir d'autres systèmes financiers
Lorsque vous effectuez votre inscription à [!INCLUDE[d365fin](includes/d365fin_md.md)], vous pouvez choisir de créer une société vierge afin d'être en mesure de télécharger vos propres données et de tester votre société [!INCLUDE[d365fin](includes/d365fin_md.md)]. En fonction de la solution financière qu'utilise votre société aujourd'hui, vous pouvez transférer des informations sur les clients, les fournisseurs, le stock et les comptes bancaires.  

À partir de la page d'accueil, vous pouvez lancer un guide de configuration assistée qui vous aide à transférer les données d'entreprise à partir d'un fichier Excel ou d'autres formats. Le type de fichiers que vous pouvez télécharger dépend des extensions disponibles. Par exemple, vous pouvez migrer des données à partir de QuickBooks, car [!INCLUDE[d365fin](includes/d365fin_md.md)] comprend une extension qui gère la conversion à partir de QuickBooks. Si vous souhaitez migrer des données à partir d'autres solutions financières, vous devez vérifier qu'une extension est disponible pour cette solution ou effectuer l'importation à partir d'Excel.  

[!INCLUDE[d365fin](includes/d365fin_md.md)] n'inclut pas de modèles pour les comptes, les clients, les fournisseurs ni les articles en stock que vous pouvez choisir d'appliquer lorsque vous importez vos données.  

## <a name="importing-data-from-quickbooks-or-dynamics-gp"></a>Importation des données à partir de QuickBooks ou Dynamics GP
Si votre entreprise utilise QuickBooks ou Dynamics GP, vous pouvez exporter les informations appropriées vers un fichier. Vous pouvez ensuite ouvrir le guide de configuration assistée pour transférer les données.
Par exemple, si votre fichier inclut les clients et les fournisseurs, vous pouvez choisir de transférer uniquement les données client. Vous pouvez alors transférer le reste des informations ultérieurement.  

La configuration assistée comprend une option permettant de modifier la configuration par défaut du transfert, mais nous vous recommandons de vous attaquer à cette configuration avancée si vous êtes familier des tables de base de données. Pour l'immense majorité des sociétés, le mappage par défaut à partir de QuickBooks ou Dynamics GP vers [!INCLUDE[d365fin](includes/d365fin_md.md)] transfère les informations que vous souhaitez.  

Pour plus d'informations, voir [Migration des données QuickBooks Desktop](ui-extensions-quickbooks-data-migration.md), [Migration des données QuickBooks Online](ui-extensions-quickbooks-online-data-migration.md), ou [Migration des données Dynamics GP](ui-extensions-dynamicsgp-data-migration.md).  

## <a name="importing-data-from-configuration-packages"></a>Importation des données à partir des packages configuration
[!INCLUDE[d365fin](includes/d365fin_md.md)] inclut un package de configuration que vous pouvez exporter vers Excel et y installe vos données. Vous pouvez alors importer les données à nouveau à partir d'Excel. Le package se compose de 27 tables, notamment des données de base telles que les clients, les fournisseurs, les articles, et les comptes, d'autres tables de configuration de base telles que les méthodes d'expédition, et les tables de transactions telles que l'en-tête vente et les lignes.  

> [!NOTE]  
>   L'utilisation des packages de configuration est une fonctionnalité avancée, et il est préférable de contacter votre administrateur. Pour plus d'informations, voir [Importation des données à partir du logiciel de comptabilité hérité à l'aide d'un package de configuration](across-import-data-configuration-packages.md).  

## <a name="see-also"></a>Voir aussi
[Finance](finance.md)  
[Importation des données à partir du logiciel de comptabilité hérité à l'aide d'un package de configuration](across-import-data-configuration-packages.md)  
[Migration des données QuickBooks Desktop](ui-extensions-quickbooks-data-migration.md)  
[Extension QuickBooks Online Data Migration](ui-extensions-quickbooks-online-data-migration.md)  
[Extension Dynamics GP Data Migration](ui-extensions-dynamicsgp-data-migration.md)  
[Personnalisation de [!INCLUDE[d365fin](includes/d365fin_md.md)] à l'aide des extensions](ui-extensions.md)   
[Configuration de [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md)

## 

