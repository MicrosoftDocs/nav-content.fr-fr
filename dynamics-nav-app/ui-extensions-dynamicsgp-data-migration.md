---
title: "Migrer des données de Dynamics GP avec l'extension Data Migration"
description: Utilisez l'extension Dynamics GP Data Migration pour migrer des clients, des fournisseurs, des articles en stock, et des comptes de Dynamics GP vers Dynamics NAV.
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 0156ec040b96f007674161361e4368b81f7c42d9
ms.contentlocale: fr-fr
ms.lasthandoff: 10/16/2017

---
# <a name="the-dynamics-gp-data-migration-extension-for-dynamics-nav"></a>L'extension Dynamics GP Data Migration pour Dynamics NAV
Cette extension facilite la migration des clients, des fournisseurs, des articles en stock et des comptes à partir de Dynamics GP vers [!INCLUDE[d365fin](includes/d365fin_md.md)]. Si votre entreprise utilise Dynamics GP aujourd'hui, vous pouvez exporter les principaux enregistrements appropriés, puis ouvrir un guide de configuration assistée pour ajouter les données vers [!INCLUDE[d365fin](includes/d365fin_md.md)]. Pour plus d'informations, voir [Migrer des données métier à partir d'autres systèmes financiers](upload-data.md).

## <a name="exporting-data-from-dynamics-gp"></a>Exportation de données à partir de Dynamics GP
Vous devez avoir exporté certains ou tous vos clients, fournisseurs, articles de stock, et comptes dans un fichier à l'aide de la fonctionnalité Dynamics GP pour l'exportation de données. Pour les besoins de [!INCLUDE[d365fin](includes/d365fin_md.md)], vous pouvez exporter les types de données suivants :

* Compte  
* Client  
* Article  
* Fournisseur  

L'extension Dynamics GP Data Migration mappe automatiquement les données exportées afin qu'elles soient rapidement disponibles dans votre nouvelle société [!INCLUDE[d365fin](includes/d365fin_md.md)]. Au cours de ce processus, la prise en charge des informations de configuration est créée, comme des groupes comptabilisation. Les articles en stock sont transmis au système avec FIFO comme méthode d'évaluation du coût. Les comptes sont configurés comme segment principal à partir de Dynamics GP avec des axes, car [!INCLUDE[d365fin](includes/d365fin_long_md.md)] n'a pas de segments de compte.

## <a name="see-also"></a>Voir aussi
[Importation des données métier à partir d'autres systèmes financiers](upload-data.md)  
[Personnalisation de [!INCLUDE[d365fin](includes/d365fin_md.md)] à l'aide des extensions ](ui-extensions.md)  

