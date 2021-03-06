---
title: Herstellen einer Verbindung mit dem Dashboard für regionale Notfallreaktion
description: In diesem Artikel erfahren Sie, wie Sie das Supportdashboard für Entscheidungen in Bezug auf COVID-19 für die Vorlagen-App für die regionale Notfallreaktion abrufen und installieren, und wie Sie eine Verbindung mit Daten herstellen.
author: paulinbar
ms.service: powerbi
ms.subservice: powerbi-template-apps
ms.topic: conceptual
ms.date: 04/24/2020
ms.author: painbar
LocalizationGroup: Connect to services
ms.openlocfilehash: 52522c03a285290fbc01da49328516f62ddfc60a
ms.sourcegitcommit: 0e9e211082eca7fd939803e0cd9c6b114af2f90a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/13/2020
ms.locfileid: "83279225"
---
# <a name="connect-to-the-regional-emergency-response-dashboard"></a>Herstellen einer Verbindung mit dem Dashboard für regionale Notfallreaktion
Das Dashboard für regionale Notfallreaktion ist die Berichtskomponente der [Lösung für die regionale Notfallreaktion von Microsoft Power Platform](https://docs.microsoft.com/powerapps/sample-apps/regional-emergency-response/overview). Administratoren regionaler Organisationen können das Dashboard in ihrem Power BI-Mandanten anzeigen, was ihnen ermöglicht, schnell wichtige Daten und Metriken abzurufen, die sie beim Treffen effizienter Entscheidungen unterstützen.

![App-Bericht des Dashboards für die regionale Notfallreaktion](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-report.png)

In diesem Artikel erfahren Sie, wie Sie die App für die regionale Notfallreaktion mithilfe der Vorlagen-App für die regionale Notfallreaktion installieren und wie Sie eine Verbindung mit den Datenquellen herstellen.

Ausführliche Informationen über die im Dashboard gezeigten Informationen finden Sie unter [Abrufen von Erkenntnissen](https://docs.microsoft.com/powerapps/sample-apps/regional-emergency-response/portals-admin-reporting#get-insights).

Nachdem Sie die Vorlagen-App installiert und eine Verbindung mit den Datenquellen hergestellt haben, können Sie den Bericht gemäß Ihren Anforderungen anpassen. Anschließend können Sie sie als App an Kollegen in Ihrer Organisation verteilen.

## <a name="prerequisites"></a>Voraussetzungen

Bevor Sie diese Vorlagen-App installieren können, müssen Sie erst die [Lösung für die regionale Notfallreaktion](https://docs.microsoft.com/powerapps/sample-apps/regional-emergency-response/deploy) installieren und einrichten. Durch die Installation dieser Lösung werden die zum Befüllen der App mit Daten erforderlichen Datenquellenverweise erstellt.

Achten Sie beim Installieren der Lösung für die regionale Notfallreaktion auf die [URL Ihrer Common Data Service-Umgebungsinstanz](https://docs.microsoft.com/powerapps/sample-apps/regional-emergency-response/deploy#step-5-configure-and-publish-power-bi-dashboard). Diese benötigen Sie zum Herstellen einer Verbindung zwischen der Vorlagen-App und den Daten.

## <a name="install-the-app"></a>Installieren der App

1. Klicken Sie auf den folgenden Link, um die App zu erhalten: [Vorlagen-App für das Dashboard für regionale Notfallreaktion](https://appsource.microsoft.com/product/power-bi/powerapps_cxo.regional_response)

1. Klicken Sie auf der AppSource-Seite für die App auf [**JETZT HOLEN**](https://appsource.microsoft.com/product/power-bi/powerapps_cxo.regional_response).

    [![App für das Dashboard für regionale Notfallreaktion in AppSource](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-appsource-get-it-now.png)](https://appsource.microsoft.com/product/power-bi/powerapps_cxo.regional_response)

1. Wählen Sie **Installieren** aus. 

    ![App für das Dashboard für regionale Notfallreaktion installieren](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-select-install.png)

    Nachdem die App installiert wurde, wird sie auf der Seite „Apps“ angezeigt.

   ![App für das Dashboard für die regionale Notfallreaktion auf der App-Seite](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-apps-page-icon.png)

## <a name="connect-to-data-sources"></a>Verbinden mit Datenquellen

1. Klicken Sie auf das Symbol auf der Seite „Apps“, um die App zu öffnen.

1. Klicken Sie auf dem Begrüßungsbildschirm auf **Erkunden**.

   ![Begrüßungsbildschirm der Vorlagen-App](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-splash-screen.png)

   Die App wird geöffnet, und es werden Beispieldaten angezeigt.

1. Klicken Sie auf dem Banner oben auf der Seite auf **Ihre Daten verbinden**.

   ![Link „Ihre Daten verbinden“ der App für das Dashboard für die regionale Notfallreaktion](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-connect-data.png)

1. Geben Sie im angezeigten Dialogfeld die [URL Ihrer Common Data Service-Umgebungsinstanz](https://docs.microsoft.com/powerapps/sample-apps/emergency-response/deploy-configure#publish-the-power-bi-dashboard) ein, z. B.: https://[myenv].crm.dynamics.com. Klicken Sie anschließend auf **Weiter**.

   ![URL-Dialogfeld der App für das Dashboard für die regionale Notfallreaktion](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-url-dialog.png)

1. Legen Sie im nächsten Dialogfeld, das angezeigt wird, die Authentifizierungsmethode auf **OAuth2** fest. Sie müssen nichts an den Datenschutzeinstellungen ändern.

   Wählen Sie **Anmelden**.

   ![Authentifizierungsdialogfeld der App für das Dashboard für die regionale Notfallreaktion](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-authentication-dialog.png)

1. Melden Sie sich auf dem Microsoft-Anmeldebildschirm bei Power BI an.

   ![Anmeldeseite von Microsoft](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-microsoft-login.png)

   Nachdem Sie sich angemeldet haben, stellt der Bericht eine Verbindung mit den Datenquellen her und wird mit aktuellen Daten befüllt. Währenddessen verändert sich der Aktivitätsmonitor.

   ![App für das Dashboard für die regionale Notfallreaktion mit aktivem Aktualisierungsvorgang](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-refresh-monitor.png)

## <a name="schedule-report-refresh"></a>Planen der Berichtsaktualisierung

Wenn die Daten vollständig aktualisiert wurden, [richten Sie einen Aktualisierungszeitplan ein](../connect-data/refresh-scheduled-refresh.md), um die Berichtsdaten aktuell zu halten.

1. Klicken Sie im oberen Header auf **Power BI**.

   ![Power BI-Breadcrumb](media/service-connect-to-regional-emergency-response/service-regional-emergency-response-app-powerbi-breadcrumb.png)

1. Suchen Sie im linken Navigationsbereich unter **Arbeitsbereiche** nach dem Arbeitsbereich „Dashboard für die regionale Notfallreaktion“, und befolgen Sie die im Artikel [Konfigurieren von geplanten Aktualisierungen](../connect-data/refresh-scheduled-refresh.md) beschriebenen Anweisungen.

## <a name="customize-and-share"></a>Anpassen und freigeben

Weitere Informationen finden Sie unter [Anpassen und Freigeben der App](../connect-data/service-template-apps-install-distribute.md#customize-and-share-the-app). Lesen Sie sich unbedingt die [Haftungsausschlüsse zum Bericht](https://docs.microsoft.com/powerapps/sample-apps/regional-emergency-response/overview#disclaimer) durch, bevor Sie die App veröffentlichen oder verteilen.

## <a name="next-steps"></a>Nächste Schritte
* [Informationen zum Dashboard für regionale Notfallreaktion](https://docs.microsoft.com/powerapps/sample-apps/regional-emergency-response/portals-admin-reporting#get-insights)
* [Einrichten und Kennenlernen der Beispielvorlage für die Krisenkommunikation in Power Apps](https://docs.microsoft.com/powerapps/maker/canvas-apps/sample-crisis-communication-app)
* Haben Sie Fragen? [Stellen Sie Ihre Frage in der Power BI-Community.](https://community.powerbi.com/)
* [Was sind Power BI-Vorlagen-Apps?](../connect-data/service-template-apps-overview.md)
* [Installieren und Verteilen von Vorlagen-Apps in Ihrer Organisation](../connect-data/service-template-apps-install-distribute.md)
