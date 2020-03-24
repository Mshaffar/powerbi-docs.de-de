---
title: Verwenden der erweiterten Datasetmetadaten in Power BI Desktop (Vorschau)
description: In diesem Artikel wird beschrieben, wie Sie erweiterte Dataset-Metadaten in Power BI verwenden.
author: davidiseminger
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 03/13/2020
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: 3812f16489d304912ec9574352897e1effb29d4a
ms.sourcegitcommit: 7e845812874b3347bcf87ca642c66bed298b244a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/13/2020
ms.locfileid: "79201399"
---
# <a name="using-enhanced-dataset-metadata-preview"></a>Verwenden erweiterter Dataset-Metadaten (Vorschauversion)

Wenn Power BI Desktop Berichte erstellt, werden dabei auch Dataset-Metadaten in den entsprechenden PBIX- und PBIT-Dateien erstellt. Bisher wurden die Metadaten in einem für Power BI Desktop spezifischen Format gespeichert. Dabei wurden Base64-codierte M-Ausdrücke und Datenquellen verwendet, wobei für Benutzer nicht erkennbar war, wie die Metadaten gespeichert wurden.

Mit der Veröffentlichung des Features für **erweiterte Dataset-Metadaten** werden viele dieser Einschränkungen aufgehoben. Wenn das Feature für **erweiterte Dataset-Metadaten** aktiviert ist, wird für die von Power BI Desktop erstellten Metadaten ein ähnliches Format verwendet wie bei tabellarischen Modellen in Analysis Services, basierend auf dem [Tabellenobjektmodell](https://docs.microsoft.com/bi-reference/tom/introduction-to-the-tabular-object-model-tom-in-analysis-services-amo).


Das Feature für **erweiterte Dataset-Metadaten** ist ein strategisches und grundlegendes Feature, da zukünftige Power BI-Funktionen auf den Metadaten aufbauen werden. Weitere Funktionen, die von erweiterten Dataset-Metadaten profitieren, sind z. B. [XMLA read/write](https://docs.microsoft.com/power-platform-release-plan/2019wave2/business-intelligence/xmla-readwrite) (XMLA Lesen/Schreiben) für die Verwaltung von Power BI-Datasets und die Migration von Analysis Services-Workloads zu Power BI, um von Features der nächsten Generation zu profitieren.

## <a name="enable-enhanced-dataset-metadata"></a>Aktivieren erweiterter Dataset-Metadaten

Das Feature für **erweiterte Dataset-Metadaten** befindet sich derzeit in der Vorschauphase. Klicken Sie in Power BI Desktop auf **Datei > Optionen und Einstellungen > Optionen > Vorschaufeatures**, und aktivieren Sie dann das Kontrollkästchen für **Store datasets using enhanced metadata format** (Datasets im erweiterten Metadatenformat speichern), wie in der folgenden Abbildung gezeigt, um erweiterte Dataset-Metadaten in Power BI Desktop zu aktivieren. 

![Aktivieren der Previewfunktion](media/desktop-enhanced-dataset-metadata/enhanced-dataset-metadata-01.png)

Sie werden dazu aufgefordert, Power BI Desktop neu zu starten.

![Aufforderung zum Neustarten](media/desktop-enhanced-dataset-metadata/enhanced-dataset-metadata-02.png)

Sobald die Previewfunktion aktiviert ist, versucht Power BI Desktop, PBIX- und PBIT-Dateien, die das vorherige Metadatenformat verwenden, zu aktualisieren. 

## <a name="considerations-and-limitations"></a>Überlegungen und Einschränkungen

In der Vorschauversion gelten die folgenden Einschränkungen, wenn die Previewfunktion aktiviert ist.

Beim Öffnen einer vorhandenen PBIX- oder PBIT-Datei, die nicht aktualisiert wurde, schlägt das Upgrade fehl, wenn das Dataset eines der folgenden Features oder einen der folgenden Connectors enthält. Wenn ein solcher Fehler auftritt, sollte dies keine unmittelbaren Auswirkungen auf das Benutzererlebnis haben, und Power BI Desktop verwendet weiterhin das vorherige Metadatenformat.

* Python-Skripts
* Benutzerdefinierte Connectors
* Azure DevOps Server
* BI-Connector
* Denodo
* Dremio
* Exasol
* Indexima
* Iris
* Jethro ODBC
* Kyligence Enterprise
* MarkLogic ODBC
* Qubole Presto
* TeamDesk
* M-Ausdrücke mit bestimmten Zeichenkombinationen wie „\\n“ in Spaltennamen
* Wenn Datasets verwendet werden, bei denen das Feature für **erweiterte Dataset-Metadaten** aktiviert ist, können im Power BI-Dienst keine Datenquellen für einmaliges Anmelden (SSO, Single Sign-On) eingerichtet werden.

Darüber hinaus können PBIX- und PBIT-Dateien, die bereits erfolgreich für die Verwendung von **erweiterten Dataset-Metadaten** aktualisiert wurden, die obigen Features und Connectors in der aktuellen Version *nicht* mehr verwenden.


## <a name="next-steps"></a>Nächste Schritte

Mit Power BI Desktop können Sie vielfältige Aufgaben ausführen. Weitere Informationen zu den Funktionen und Möglichkeiten finden Sie in den folgenden Ressourcen:

* [Was ist Power BI Desktop?](desktop-what-is-desktop.md)
* [Neuigkeiten in Power BI Desktop](desktop-latest-update.md)
* [Übersicht zu Abfragen mit Power BI Desktop](desktop-query-overview.md)
* [Datentypen in Power BI Desktop](desktop-data-types.md)
* [Strukturieren und Kombinieren von Daten mit Power BI Desktop](desktop-shape-and-combine-data.md)
* [Allgemeine Abfrageaufgaben in Power BI Desktop](desktop-common-query-tasks.md)
