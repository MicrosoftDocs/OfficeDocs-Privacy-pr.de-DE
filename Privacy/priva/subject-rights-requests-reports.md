---
title: Generieren von Berichten und Erfüllen einer Anforderung zu Betreffrechten
f1.keywords:
- CSH
ms.author: chvukosw
author: chvukosw
manager: laurawi
audience: Admin
ms.topic: article
ms.service: O365-seccomp
ms.localizationpriority: medium
ms.collection:
- M365-security-compliance
- M365-priva-subject-rights-requests
search.appverid:
- MOE150
- MET150
description: Erfahren Sie, wie Sie die von Microsoft Priva erstellten Datenpakete für Anträge auf Rechte betroffener Personen verwalten und den Antrag an die betroffene Person erfüllen.
ms.openlocfilehash: a72dfb53e4f642cd2c567896c854af2beaedd416
ms.sourcegitcommit: beeb693075ef692e95d679f366301df8517b2ac3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/23/2022
ms.locfileid: "63765518"
---
# <a name="generate-reports-and-fulfill-a-subject-rights-request"></a>Generieren von Berichten und Erfüllen einer Anforderung zu Betreffrechten

Nachdem Sie Ihre Datenüberprüfung für eine Anforderung zu Betreffrechten in Microsoft Priva abgeschlossen haben, können Sie den Antrag erfüllen. Priva erstellt Berichte und erfasst die Dateien, die während des Datenüberprüfungsprozesses als **"Einschließen"** gekennzeichnet sind. Ausgewählte Dateien aus diesen Datenpaketen können an Ihre betroffene Person übermittelt werden, um ihren Antrag zu erfüllen. Priva unterstützt auch die Nutzung der API für anträge von Microsoft 365 Betreffrechten, um Automatisierungsfunktionen einzuführen.

## <a name="understanding-reports"></a>Grundlegendes zu Berichten

Nachdem Sie die **Option "Vollständige Überprüfung** " in der **Überprüfungsdatenstufe** der Anforderung für Betreffrechte ausgewählt haben, werden die endgültigen Berichte für die Anforderung automatisch generiert. Auf der Registerkarte **"Berichte** " auf der Seite "Details zu Anträgen betroffener Personen" gibt die Spalte **"Status** " an, wann die Berichtsgenerierung **ausgeführt** wird und wann ein Bericht **zum Herunterladen bereit** ist. Es kann bis zu 30 Minuten dauern, bis die Erstellung der Berichte abgeschlossen ist.

Berichte sind in zwei Abschnitte unterteilt:
1. **Berichte für die betroffene Person**: Diese Berichte enthalten Informationen, die im Rahmen der Anforderungserfüllung an die betroffene Person zurückgegeben werden können. Hier finden Sie das **Datenpaket** , das Dateien enthält, die Sie an die betroffene Person senden können.
   > [!IMPORTANT]
   > Ein Datenpaket wird nur generiert, wenn Sie Elemente während der Datenüberprüfung als **"Einschließen"** markieren.

   > [!IMPORTANT]
   > Ein Datenpaket wird nur für **Export-** und **Zugriffstypen** von Anforderungen generiert. Ein Datenpaket wird für eine **Tagged-Liste zur Nachverfolgungsanforderung** nicht generiert. Überprüfen Sie Details zu [Anforderungstypen für Betreffrechte](subject-rights-requests-create.md#use-the-subject-rights-request-creation-wizard).

2. **Berichte für die interne Verwendung**: Diese Berichte beziehen sich auf die internen Datensätze Ihrer Organisation im Zusammenhang mit der Anforderung von Antragstellerrechten. Sie enthalten ein Überwachungsprotokoll und eine Liste aller Dateien, auf die Sie tags während der Datenüberprüfung angewendet haben, um nachzuschlagen oder weitere Maßnahmen zu ergreifen.

> [!NOTE]
> Wenn Berichte generiert werden, schließt die Organisation die Anforderung ab, indem sie die entsprechenden Berichte auf sichere Weise an die betroffene Person sendet, um die Anforderung der Antragstellerrechte zu erfüllen. Wenn die betroffene Person die Löschung ihrer Daten angefordert hat, liegt es in der Verantwortung der Organisation, Elemente für die Löschung zu identifizieren und die Löschung durchzuführen.

## <a name="data-package"></a>Datenpaket

Das Anforderungsdatenpaket für Betreffrechte enthält Elemente, die während der Datenüberprüfungsphase des Prozesses als **"Einschließen** " gekennzeichnet sind. Das Datenpaket wird als ZIP-Datei generiert. Wenn sie zum Download bereit ist, wählen Sie die Zeile des Berichts auf der Registerkarte **"Berichte** " auf der Seite "Details zur Anforderung von Antragstellerrechten" aus. Ein Flyout-Bereich wird mit einer Schaltfläche zum **Herunterladen** des Berichts geöffnet. Die **Anweisungen** für die nächsten Aktionen im Flyout-Bereich bieten eine Kurzübersicht für die Arbeit mit den Inhalten.

Wenn Sie zum Herunterladen des Datenpakets bereit sind, wählen Sie **"Herunterladen**" aus, suchen Sie Ihren Download, und öffnen Sie dann die heruntergeladene ZIP-Datei.

### <a name="contents-of-the-data-package"></a>Inhalt des Datenpakets

Die ZIP-Datei des Datenpakets enthält die folgenden Elemente:

- Ein Ordner mit dem Namen **Azure**: Dieser Ordner enthält die wichtigsten Materialien für Ihre betroffene Person. Weitere Informationen finden Sie unten in der ausführlichen Erläuterung.
- Dateien außerhalb des **Azure-Ordners** : Diese können zwei Tabellen mit dem Namen " **Ergebnisse** " und " **Zusammenfassung**" enthalten. Diese Dateien außerhalb des Azure-Ordners werden als Referenz bereitgestellt und sollten in erster Linie von den Administratoren Ihrer Organisation verwendet werden.

Wenn Priva Dateien für eine Anforderung zu Betreffrechten identifiziert und abruft, werden die dateien, die in diesem Prozess exportiert werden, mit eindeutigen Bezeichnern umbenannt, um personenbezogene Daten zu schützen. Sie können mithilfe der **Export_load_file.csv** Datei auf die eindeutigen Namen mit den ursprünglichen Dateinamen verweisen. Da die ursprünglichen Dateinamen vertrauliche Informationen enthalten können, sollten Sie Ihre Richtlinien befolgen, die für diese Informationen gelten.

> [!NOTE]
> Wir empfehlen, den Inhalt dieses Ordners sorgfältig zu überprüfen und nur die erforderlichen Dateien an Ihre betroffene Person zu übermitteln. Sie sollten Ihre Antwort auswerten, um sicherzustellen, dass sie auf die Anforderungen des geltenden Rechts zugeschnitten ist.

### <a name="azure-folder-contents"></a>Azure-Ordnerinhalte

Öffnen Sie den **Azure-Ordner** , und öffnen Sie dann die **AEDExport.zip** Datei, die einen anderen Dateiordner mit einem langen Namen enthält, der aus Zahlen und Buchstaben besteht. Öffnen Sie den Ordner mit dem langen Namen, um den unten beschriebenen Inhalt anzuzeigen:

- **Extracted_text_files** Ordner: Enthält Text, der aus den systemeigenen Dateien extrahiert wurde (sofern unterstützt).
- **NativeFiles-Ordner** : Enthält alle Elemente, die während der Datenüberprüfung als **eingeschlossen markiert wurden**, in ihrem nativen Dateiformat. Jedes Element in diesem Ordner erhält einen eindeutigen Dateinamen, um personenbezogene Daten zu schützen. Sie können mithilfe der unten erläuterten Export_load_file.csv datei auf diese eindeutigen Namen mit ihrem ursprünglichen Dateinamen verweisen.
  - Dateien, die während der Datenüberprüfung mithilfe der **Funktion "Annotate** " bearbeitet wurden, befinden sich im Ordner **"NativeFiles** " und weisen das Suffix "_burn.pdf" auf.
- **Export_load_file.csv** Datei: Enthält die ursprünglichen Dateinamen, damit Sie mit den eindeutigen Dateinamen im NativeFiles-Ordner querverweisen können.
- **Zusammenfassungstextdatei** : Enthält eine Zusammenfassung der Dateitypen im Datenpaket, der Anzahl der Dateien und ihrer Größe.

##### <a name="what-to-do-with-the-folder-contents"></a>Was mit den Ordnerinhalten zu tun ist

Öffnen Sie den **Azure-Ordner** und die ZIP-Dateien wie oben erläutert. Ihre nächste Aufgabe besteht darin, die Elemente zu überprüfen, zu bestimmen, was an die betroffene Person gesendet werden soll, und zip-Dateiinhalte bei Bedarf zu ändern.

Bei einem Exportantrag, bei dem die betroffene Person eine Kopie aller Elemente mit ihren personenbezogenen Daten erhalten möchte, die sich im Besitz der Organisation befinden, sollten Sie die Elemente im Ordner **"NativeFiles** " genau überprüfen und alle Elemente entfernen, die Sie nicht an die betroffene Person zurücksenden möchten.

Bei einer Zugriffsanforderung, bei der die betroffene Person eine Zusammenfassung aller ihrer persönlichen Informationen im Besitz der Organisation erhalten möchte, sollten Sie sich auf die **Textdatei "Zusammenfassung** " konzentrieren.

Ändern Sie die ZIP-Datei, um alle Inhalte zu entfernen, die Sie nicht in das endgültige Paket einschließen möchten. Sobald sie fertig ist, senden Sie die ZIP-Datei auf sichere Weise an die betroffene Person, die die Berechtigungsanforderung gestellt hat.

## <a name="audit-log"></a>Überwachungsprotokoll

Das Überwachungsprotokoll ist eine CSV-Datei, die einen Datensatz des Verlaufs der Phasen für jede Anforderung von Betreffrechten bereitstellt. Sie listet jede Phase des Prozesses zusammen mit dem Datum und der Uhrzeit auf, die abgeschlossen wurde, sowie den Benutzernamen der Person, die den Schritt abgeschlossen hat.

## <a name="tagged-files-reports"></a>Berichte mit markierten Dateien

Die Berichte, die als **"Dateien" gekennzeichnet sind,** sind CSV-Dateien, die die Inhaltselemente auflisten, auf die Tags während des Datenüberprüfungsprozesses angewendet wurden. Tags werden verwendet, um Inhaltselemente zur weiteren Aufmerksamkeit oder Aktion durch die Organisation zu kennzeichnen. Erfahren Sie mehr über [die Einstellungen für Tags](priva-settings.md#data-review-tags).

## <a name="retention-periods-for-reports-and-data"></a>Aufbewahrungszeiträume für Berichte und Daten

Berichte, die von Anträgen betroffener Personen und zugehörigen Daten generiert werden, z. B. kommentierte Dateien, die in Azure gespeichert sind, werden für einen bestimmten Zeitraum gespeichert. Der Standardaufbewahrungszeitraum beträgt 30 Tage ab dem Datum, an dem eine Anforderung für Betreffrechte geschlossen wird.

Der Aufbewahrungszeitraum für Daten wird in Priva **Einstellungen** definiert und gilt für alle Anträge betroffener Personen. Führen Sie die folgenden Schritte aus, um Den Aufbewahrungszeitraum für Daten anzuzeigen oder zu ändern:

1. Wählen Sie von überall in Priva Subject Rights Requests **in** der oberen rechten Ecke des Bildschirms Einstellungen (das Zahnradsymbol) aus.
2. Wählen Sie im linken Navigationsbereich **Datenaufbewahrungszeiträume** aus.
3. Wählen Sie im Dropdownmenü **"Gesammelte Daten und Berichte** " entweder 30 Tage oder 90 Tage als Aufbewahrungszeitraum aus.
4. Wählen Sie **"Speichern** " aus, um Ihre Einstellungen zu speichern.

Stellen Sie sicher, dass die von Ihnen gewählten Datenaufbewahrungszeiträume den Richtlinien und gesetzlichen Verpflichtungen Ihrer Organisation entsprechen.

## <a name="integrate-with-partner-solutions"></a>Integration in Partnerlösungen

Sie können die Lösung "Priva Subject Rights Requests" mit Ihren vorhandenen Geschäftsprozessen und Tools integrieren, indem Sie die API für Microsoft 365 Anforderung von Antragstellerrechten nutzen. Dies bietet Ihnen eine einfache, aber leistungsstarke Möglichkeit, Automatisierung in Ihre Strategie für Die Rechte von Antragstellern einzuführen.

Wenn betroffene Personen Informationen von Ihrer Organisation anfordern, können Sie unsere APIs nutzen, um diese Anforderungen innerhalb Microsoft 365 basierend auf den für diese Anforderung benutzerdefinierten Kriterien zu erstellen. Sie können die Anforderung von Betreffrechten in Microsoft 365 erstellen, den Fortschritt der Anforderung während der Phasen nachverfolgen und bestätigen, wann die Verarbeitung der Anforderung abgeschlossen ist und der Inhalt abgerufen werden kann. Unsere APIs stehen für jeden zur Verfügung, um ihre Lösungen erweiterbarer zu machen: ob für ISVs, Partner, die für Microsoft 365 in ihren Lösungen geeignet sind, oder für Organisationen, die mit ihren Branchenanwendungen arbeiten können.

Weitere Informationen finden Sie unter ["Verwenden der Microsoft Graph-Api für Anträge betroffener Personen](/graph/api/resources/subjectrightsrequest-subjectrightsrequestapioverview)".

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
