---
title: Abonnieren von Berichten und Dashboards für sich selbst und andere
description: Hier erfahren Sie, wie Sie für sich selbst und für andere eine Momentaufnahme einer Power BI-Berichtsseite, eines Dashboards oder eines paginierten Berichts abonnieren.
author: maggiesMSFT
ms.reviewer: ''
featuredvideoid: ''
ms.service: powerbi
ms.subservice: powerbi-service
ms.topic: conceptual
ms.date: 05/15/2020
ms.author: maggies
LocalizationGroup: Common tasks
ms.openlocfilehash: f057395361840b7b16fa8a7cde5a6d2513196845
ms.sourcegitcommit: 6ba7cc9afaf91229f717374bc0c12f0b8201d15e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/16/2020
ms.locfileid: "83438221"
---
# <a name="subscribe-yourself-and-others-to-reports-and-dashboards-in-the-power-bi-service"></a>Abonnieren von Berichten und Dashboards im Power BI-Dienst für sich selbst und andere

Sie können für sich und Ihre Kollegen Berichtsseiten, Dashboards und paginierte Berichte, die Sie besonders interessieren, abonnieren. Power BI-E-Mail-Abonnements ermöglichen Ihnen Folgendes:

- Festlegen, wie oft Sie E-Mails von Power BI erhalten möchten: täglich, wöchentlich, monatlich oder einmal am Tag nach der anfänglichen Datenaktualisierung
- Auswählen der Zeit, zu der Sie die E-Mail täglich, wöchentlich, stündlich oder monatlich erhalten möchten
- Einrichten von 24 verschiedenen Abonnements pro Power BI-Bericht oder -Dashboard.  Es gibt keine Beschränkung für die Anzahl der Abonnements, die Sie für paginierte Berichte einrichten können.
- Beauftragen der Sendung einer E-Mail mit einem Berichtsimage und einem Link zum Bericht im Dienst  Wenn Sie diesen Link auf mobilen Geräten auswählen, auf denen Power BI-Apps installiert sind, wird die Power BI-App gestartet und nicht der Bericht oder das Dashboard auf der Power BI-Website geöffnet.
- Anfügen des vollständigen Berichts als Anlage, wenn Sie einen paginierten Bericht abonnieren
- Senden von E-Mails an Benutzer außerhalb Ihres Mandanten, wenn Ihre Power BI-Inhalte in einer Premium-Kapazität gehostet werden  Administratoren können mithilfe der vorhandenen externen Freigabesteuerungseinstellungen in Power BI Admin Center den Zugriff darauf steuern, wer E-Mail-Abonnements an externe Benutzer senden darf.

![E-Mail mit einer Momentaufnahme des Dashboards](media/service-report-subscribe/power-bi-dashboard-email-new.jpg) 

## <a name="requirements"></a>Anforderungen

Das **Erstellen** eines Abonnements kann erfolgen durch:

- Benutzer mit einer Power BI Pro-Lizenz 
- Benutzer, die Inhalte in einem Premium-Arbeitsbereich oder einer Premium-App anzeigen, können auch ohne Power BI Pro-Lizenz dort befindliche Inhalte abonnieren. 

Sie müssen nicht über Berechtigungen zum Bearbeiten des Inhalts (Dashboard oder Bericht) verfügen, um ein Abonnement für sich selbst zu erstellen. Sie müssen jedoch über Berechtigungen zum Bearbeiten verfügen, um ein Abonnement für eine andere Person zu erstellen.

## <a name="subscribe-to-a-dashboard-report-page-or-paginated-report"></a>Abonnieren eines Dashboards, einer Berichtsseite oder eines paginierten Berichts

Gleich, ob Sie ein Dashboard, einen Bericht oder einen paginierten Bericht abonnieren, der Vorgang ist ähnlich. Sie können Dashboards und Berichte im Power BI-Dienst über dieselbe Schaltfläche abonnieren.

Das Abonnieren von paginierten Berichten unterscheidet sich etwas. Details finden Sie unter [Abonnieren eines paginierten Berichts im Power BI-Dienst für sich selbst und andere](../consumer/paginated-reports-subscriptions.md).
 
![Das Symbol „Abonnieren“ auswählen](media/service-report-subscribe/power-bi-subscribe-orientation.png).

1. Öffnen Sie das Dashboard oder den Bericht.
2. Klicken Sie in der oberen Menüleiste auf **Abonnieren**, oder klicken Sie auf das Briefumschlagsymbol ![Symbol „Abonnieren“](media/service-report-subscribe/power-bi-icon-envelope.png).
   
    ![Symbol „Abonnieren“](media/service-report-subscribe/power-bi-subscribe-icon.png)

1. Mithilfe des gelben Schiebereglers können Sie das Abonnement aktivieren und deaktivieren. Wenn Sie den Schieberegler auf **Aus** stellen, wird das Abonnement nicht gelöscht. Verwenden Sie zum Löschen des Abonnements das Papierkorbsymbol.

2. Ihre E-Mail-Adresse befindet sich bereits im Feld **Abonnieren**. Sie können dem Abonnement weitere E-Mail-Adressen aus derselben Domäne hinzufügen. Wenn der Bericht oder das Dashboard in einer [Premium-Kapazität](https://docs.microsoft.com/power-bi/service-premium-what-is) gehostet wird, können Sie Abonnements für andere einzelne E-Mail-Adressen und Gruppenaliase abschließen, unabhängig davon, ob sich diese in Ihrer Domäne befinden oder nicht. Wenn der Bericht oder das Dashboard nicht in einer Premium-Kapazität gehostet wird, können Sie Abonnements für andere Personen abschließen. Diese Personen müssen jedoch ebenfalls über eine Power BI Pro-Lizenz verfügen. Weitere Informationen finden Sie im Folgenden unter [Zu beachtende Aspekte und Problembehandlung](#considerations-and-troubleshooting).

3. Füllen Sie den **Betreff** und die **Nachricht** der E-Mail aus.

4. Wählen Sie für Ihr Abonnement eine **Frequenz** aus:  **Täglich**, **Stündlich**, **Wöchentlich**, **Monatlich** oder **Nach Datenaktualisierung (einmal täglich)** . Wenn Sie die Abonnement-E-Mail nur an bestimmten Tagen erhalten möchten, können Sie **Stündlich** oder **Wöchentlich** und dann die konkreten Tage auswählen. Wenn Sie die Abonnement-E-Mail zum Beispiel nur an Werktagen erhalten möchten, können Sie **Wöchentlich** auswählen und die Kontrollkästchen bei **Sa** und **So** deaktivieren. Wenn Sie **Monatlich** auswählen, müssen Sie eingeben, wie oft Sie die Abonnement-E-Mail pro Monat erhalten möchten.

5. Wenn Sie **Täglich**, **Stündlich**, **Monatlich** oder **Wöchentlich** auswählen, können Sie auch eine **Geplante Zeit** für das Abonnement angeben. Sie müssen es zur vollen Stunde oder zur Minute 15, 30 oder 45 ausführen. Wählen Sie Vormittag (AM) oder Nachmittag/Abend (PM) aus. Sie können auch die Zeitzone angeben. Wenn Sie **Stündlich** auswählen, müssen Sie auch die **Geplante Zeit** festlegen, zu der das Abonnement gestartet werden soll. Anschließend wird es stündlich ausgeführt.

6. Standardmäßig ist das Startdatum für Ihr Abonnement das Datum, an dem Sie es erstellen. Sie haben die Möglichkeit, ein Enddatum auszuwählen. Wenn Sie kein Enddatum festlegen, ist das Enddatum automatisch ein Jahr nach dem Startdatum. Sie können es zu einem beliebigen Zeitpunkt vor dem Ablauf des Abonnements in ein beliebiges Datum in der Zukunft (bis zum Jahr 9999) ändern. Wenn ein Abonnement ein Enddatum erreicht, wird es deaktiviert, bis Sie es erneut aktivieren. Vor dem geplanten Enddatum werden Sie per Benachrichtigung(en) gefragt, ob Sie das Abonnement verlängern möchten.

    Im Screenshot unten sehen Sie, dass Sie beim Abonnieren eines Berichts eigentlich eine _Berichtseite_ abonnieren. Klicken Sie auf **Weiteres Abonnement hinzufügen**, und wählen Sie eine weitere Seite aus, um mehrere Seiten eines Berichts zu abonnieren.
     
    ![Bereich „Abonnieren“](media/service-report-subscribe/power-bi-subscribe-pane.png)  

1. (Optional) Legen Sie fest, ob ein Link eingefügt werden soll, der zurück zum ursprünglichen Inhalt in Power BI führt, und ob Benutzern Zugriff auf den Inhalt gewährt werden soll, den Sie für sie abonnieren.  Wenn Sie sich für den Link entscheiden, sollten Sie sicherstellen, dass alle Benutzer auf den Bericht zugreifen können.
2. Klicken Sie auf **Speichern und schließen**. Die Abonnenten erhalten eine E-Mail und eine Momentaufnahme des Dashboards oder der Berichtseite mit der Häufigkeit und zu der Uhrzeit, die Sie ausgewählt haben. Insgesamt können Sie bis zu 24 Abonnements pro Bericht oder Dashboard erstellen und für jedes Abonnement eigene Empfänger, Uhrzeiten und Häufigkeiten angeben. Für alle Abonnements, für die **Nach der Datenaktualisierung** für das Dashboard oder den Bericht festgelegt wurde, wird dennoch nur nach der ersten geplanten Aktualisierung eine E-Mail versendet.

    > [!TIP]
    > Möchten Sie die E-Mail zu einem Abonnement sofort oder zu einem beliebigen Zeitpunkt senden? Klicken Sie bei den Abonnements für das Dashboard oder den Bericht, für die Sie eine E-Mail senden möchten, auf **Jetzt ausführen**. Es wird eine Benachrichtigung angezeigt, die angibt, dass alle Benutzer dieses Abonnements eine E-Mail erhalten. Diese Aktion zählt nicht zum täglichen Limit von 24 geplanten Ausführungen von Abonnements pro Bericht oder Dashboard. Dies löst KEINE Datenaktualisierung für das zugrunde liegende Dataset aus.
    >

## <a name="manage-your-subscriptions"></a>Verwalten Ihrer Abonnements

Nur der Ersteller eines Abonnements kann dieses auch verwalten. Die Anzeige der Abonnementverwaltung kann auf zwei Arten aufgerufen werden. Wählen Sie im Dialogfeld **E-Mails abonnieren** die Option **Alle Abonnements verwalten** aus (siehe Schritt 4 weiter oben). Klicken Sie anschließend in der oberen Menüleiste auf das Power BI-Zahnradsymbol ![Zahnradsymbol](media/service-report-subscribe/power-bi-settings-icon.png) und dann auf **Einstellungen**.

![„Einstellungen“ auswählen](media/service-report-subscribe/power-bi-subscribe-settings.png)

Welche Abonnements hier angezeigt werden, hängt vom aktiven Arbeitsbereich ab. Wenn alle Ihre Abonnements für alle Arbeitsbereiche angezeigt werden sollen, muss **Mein Arbeitsbereich** aktiv sein. Grundlegende Informationen zu Arbeitsbereichen finden Sie unter [Erstellen von klassischen Arbeitsbereichen in Power BI](service-create-workspaces.md).

![Alle Abonnements unter „My Workspace“ (Mein Arbeitsbereich) anzeigen](media/service-report-subscribe/power-bi-subscriptions.png)

Ein Abonnement endet in einem der folgenden Fälle:

- Die Pro-Lizenz läuft ab.
- Der Besitzer löscht das Dashboard oder den Bericht.
- Das Benutzerkonto, mit dem das Abonnement erstellt wurde, wird gelöscht.

Power BI-Administratoren können mit den Power BI-Überwachungsprotokollen Details zu Abonnements einsehen. Hierzu zählen:

- Created By
- Erstellungsdatum
- Wer einen Inhalt abonniert hat
- Empfänger
- Häufigkeit
- Wer einen Inhalt geändert hat
- Änderungsdatum

## <a name="considerations-and-troubleshooting"></a>Zu beachtende Aspekte und Problembehandlung

### <a name="general"></a>Allgemein

- Wie bei anderen BI-Produkten beginnt die Verarbeitung des Abonnements zu dem Zeitpunkt, für den Sie Ihr Abonnement festlegen.  Wenn die Berichtsverarbeitung abgeschlossen ist, wird das Abonnement in eine Warteschlange eingereiht und per E-Mail an die Empfänger gesendet.  Wir bemühen uns, alle Abonnements schnellstmöglich zu verarbeiten und bereitzustellen. Allerdings können zu Bedarfsspitzen aufgrund der Anzahl von Abonnements, die Power BI gleichzeitig übermitteln kann, längere Verzögerungen auftreten. Für die meisten Kunden sollten jedoch keine Verzögerungen von mehr als 15 Minuten beim Verarbeiten und Senden von Berichten auftreten. Zu bestimmten Zeiten und für bestimmte Mandanten mit erheblicher Nutzung kann es bis zu 30 Minuten dauern.  Es wird jedoch in keinem Fall eine Bereitstellungsverzögerung von mehr als 60 Minuten nach Planung des Abonnements erwartet.  Wenn bei Ihnen eine so lange Verzögerung auftritt, sollten Sie zunächst sicherstellen, dass die Adresse `no-reply-powerbi@microsoft.com` sich auf der Whitelist Ihres E-Mail-Anbieters befindet.  Wenn das der Fall ist, wenden Sie sich an den Power BI-Support.
- Sie können aktuell keine E-Mail-Abonnements von Berichten und Dashboards für andere Personen abschließen, wenn die Berichte und Dashboards Datasets mit Liveverbindung enthalten. Dies gilt nicht für paginierte Berichte. Sie können Abonnements von paginierten Berichten für andere Benutzer abschließen, indem Sie Ihren Sicherheitskontext verwenden. Weitere Informationen finden Sie unter [Abonnieren von paginierten Berichten für sich selbst und andere im Power BI-Dienst](../consumer/paginated-reports-subscriptions.md).
- Die Aktualisierung von Datasets, die mit Dashboards und Berichten verknüpft sind und seit mehr als zwei Monaten nicht besucht wurden, wird von Power BI automatisch ausgesetzt. Wenn Sie jedoch einem Dashboard oder Bericht ein Abonnement hinzufügen, wird die Aktualisierung nicht ausgesetzt, auch wenn das Dashboard oder der Bericht längere Zeit nicht besucht wurde.
- Wenn Sie die E-Mails des Abonnements nicht erhalten, vergewissern Sie sich, dass Ihr Benutzerprinzipalname (User Principal Name, UPN) E-Mails empfangen kann.
- Wenn Ihr Dashboard oder Bericht sich in einer Premium-Kapazität befindet, können Sie E-Mail-Aliase von Gruppen für Abonnements verwenden, statt für jeden Kollegen einzeln mit dessen E-Mail-Adresse ein Abonnement abschließen zu müssen. Die Aliase basieren auf dem aktuellen Verzeichnis der aktiven Benutzer.
- Wenn Ihre Inhalte sich nicht in einer Premium-Kapazität befinden, können nur Power BI Pro-Benutzer E-Mail-Abonnements empfangen. 
- Abonnements unterstützen derzeit keine Lesezeichen.

### <a name="dashboards"></a>Dashboards

- Dashboards mit mehr als 25 angehefteten Kacheln oder vier angehefteten Berichtsseiten werden in an Benutzer gesendeten Abonnement-E-Mails möglicherweise nicht vollständig dargestellt. Abonnements von Dashboards mit mehr als dieser Anzahl Kacheln werden nicht blockiert. Sie werden jedoch beim Auftreten von Problemen als nicht unterstützt angesehen. Erwägen Sie, sie entsprechend zu ändern, damit sie in einen unterstützten Bereich fallen.
- In seltenen Fällen kann es länger als 15 Minuten dauern, bis E-Mail-Abonnements an ihre Empfänger übermittelt werden. In diesem Fall empfehlen wir, Ihre Datenaktualisierung und Ihr E-Mail-Abonnement zu verschiedenen Zeiten auszuführen, um eine zeitnahe Übermittlung sicherzustellen. Wenn das Problem weiterhin besteht, wenden Sie sich an den Power BI-Support.
- Wenn auf Kacheln Sicherheit auf Zeilenebene (Row Level Security, RLS) angewendet wurde, werden diese Kacheln bei Dashboard-E-Mail-Abonnements nicht angezeigt.
- Für Abonnements von Dashboards werden bestimmte Typen von Kacheln noch nicht unterstützt. Dazu zählen Streamingkacheln, Videokacheln und benutzerdefinierte Kacheln mit Webinhalten.
- Wenn Sie ein Dashboard für einen Kollegen außerhalb Ihres Mandanten freigeben, können Sie nicht zusätzlich ein Abonnement für diesen Kollegen erstellen, *es sei denn*, das Dashboard befindet sich in einem Premium-Arbeitsbereich oder einer App. Wenn Sie `aaron@contoso.com` sind, können Sie es für `anyone@fabrikam.com` freigeben, aber es kann dafür derzeit kein Abonnement für `anyone@fabrikam.com` abgeschlossen werden.

### <a name="reports"></a>Berichte

- Wenn das Dataset RLS verwendet, können Sie ein Berichts-E-Mail-Abonnement für sich erstellen. Für Berichte, in denen die Sicherheit auf Zeilenebene verwendet wird, können Sie kein Abonnement für andere Benutzer abschließen. Sie können Abonnements von paginierten Berichten für andere Benutzer abschließen, indem Sie Ihren Sicherheitskontext verwenden. Weitere Informationen finden Sie unter [Abonnieren von paginierten Berichten für sich selbst und andere im Power BI-Dienst](../consumer/paginated-reports-subscriptions.md).
- Abonnements von Berichtseiten sind mit dem Namen der Berichtseite verknüpft. Wenn Sie eine Berichtseite abonnieren und dann umbenennen, müssen Sie das Abonnement erneut erstellen.
- Ihre Organisation kann möglicherweise bestimmte Einstellungen in Azure Active Directory konfigurieren, wodurch die Möglichkeit zur Verwendung von E-Mail-Abonnements in Power BI eingeschränkt werden kann. Dies umfasst unter anderem das Vorhandensein von Einschränkungen durch mehrstufige Authentifizierung oder IP-Adressbereiche beim Zugriff auf Ressourcen.
- E-Mail-Abonnements bieten keine Unterstützung für die meisten [benutzerdefinierten Visuals](../developer/power-bi-custom-visuals.md). Die einzige Ausnahme sind benutzerdefinierte Visuals, die [zertifiziert](../developer/power-bi-custom-visuals-certified.md) wurden.
- E-Mail-Abonnements bieten aktuell keine Unterstützung für R-gestützte benutzerdefinierte Visuals.
- E-Mail-Abonnements werden mit Standardzuständen für Filter und Slicer des Berichts gesendet. Alle Änderungen der Standardwerte, die Sie nach dem Abonnieren vornehmen, werden nicht in der E-Mail angezeigt. Paginierte Berichte unterstützen diese Funktion und ermöglichen es Ihnen, die spezifischen Parameterwerte für jedes Abonnement festzulegen.

## <a name="next-steps"></a>Nächste Schritte

- [Abonnieren eines paginierten Berichts im Power BI-Dienst für sich selbst und andere](../consumer/paginated-reports-subscriptions.md)
- Weitere Fragen? [Stellen Sie Ihre Frage in der Power BI-Community.](https://community.powerbi.com/)    
- [Blogbeitrag lesen](https://powerbi.microsoft.com/blog/introducing-dashboard-email-subscriptions-a-360-degree-view-of-your-business-in-your-inbox-every-day/)
