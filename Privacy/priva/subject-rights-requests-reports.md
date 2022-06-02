---
title: Generieren von Berichten zum Erfüllen einer Anfrage zu Rechten betroffener Personen
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
description: Erfahren Sie, wie Sie die von Microsoft Priva erstellten Datenpakete für Anträge betroffener Personen verwalten und die Anforderung an die betroffene Person erfüllen.
ms.openlocfilehash: 999de2aecefab2c1685967d197839fbb72938f8a
ms.sourcegitcommit: 9315064bf5bb9e889318e61ec5f082f36c815e1e
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/02/2022
ms.locfileid: "65851661"
---
# <a name="generate-reports-to-fulfill-a-subject-rights-request"></a>Generieren von Berichten zum Erfüllen einer Anfrage zu Rechten betroffener Personen

Nachdem Sie Ihre Datenüberprüfung für eine Anfrage zu Rechten betroffener Personen in Microsoft Priva abgeschlossen haben, können Sie mit der Erfüllung der Anforderung fortarbeiten. Priva erstellt Berichte und sammelt die Dateien, die während des Datenüberprüfungsprozesses als **"Einschließen"** gekennzeichnet sind. Ausgewählte Dateien aus diesen Datenpaketen können an Ihre betroffene Person übermittelt werden, um deren Anforderung abzuschließen.

## <a name="understanding-reports"></a>Grundlegendes zu Berichten

Nachdem Sie in der Phase "**Prüfdaten**" der Anforderung für Die Rechte betroffener Personen die Option "**Vollständige Überprüfung**" ausgewählt haben, werden die endgültigen Berichte für die Anforderung automatisch generiert. Auf der Registerkarte " **Berichte** " auf der Seite "Details zu Anfragen zu Rechten betroffener Personen" gibt die Spalte **"Status** " an, wann die Berichtsgenerierung **ausgeführt** wird und wann ein Bericht **zum Herunterladen bereit** ist. Es kann bis zu 30 Minuten dauern, bis die Erstellung der Berichte abgeschlossen ist.

Berichte sind in zwei Abschnitte unterteilt:
1. **Berichte für die betroffene Person**: Diese Berichte enthalten Informationen, die im Rahmen der Anforderungserfüllung an die betroffene Person zurückgegeben werden können. Hier finden Sie das **Datenpaket** , das Dateien enthält, die Sie an die betroffene Person senden möchten.
   > [!IMPORTANT]
   > Ein Datenpaket wird nur generiert, wenn Sie Elemente während der Datenüberprüfung als **"Einschließen** " markieren.

   > [!IMPORTANT]
   > Ein Datenpaket wird nur für **Export**- und Access-Anforderungstypen generiert. Es wird kein Datenpaket für eine **Liste mit Tags für die Nachverfolgungsanforderung** generiert. Überprüfen Sie Details zu [Anforderungstypen für Rechte betroffener Personen](subject-rights-requests-create.md#use-the-subject-rights-request-creation-wizard).

2. **Berichte zur internen Verwendung**: Diese Berichte gelten für die internen Datensätze Ihrer Organisation im Zusammenhang mit der Anforderung von Rechten betroffener Personen. Sie enthalten ein Überwachungsprotokoll und eine Liste aller Dateien, auf die Sie während der Datenüberprüfung Tags angewendet haben, um weitere Maßnahmen zu ergreifen oder nachzuverfolgen.

> [!NOTE]
> Wenn Berichte generiert werden, schließt die Organisation die Anforderung ab, indem die entsprechenden Berichte auf sichere Weise an die betroffene Person gesendet werden, um die Anforderung der Betroffenenrechte zu erfüllen. Wenn die betroffene Person eine Löschung ihrer Daten angefordert hat, liegt es in der Verantwortung der Organisation, Elemente für die Löschung zu identifizieren und die Löschung durchzuführen.

## <a name="data-package"></a>Datenpaket

Das Datenpaket zur Anforderung von Rechten betroffener Personen enthält Elemente, die während der Datenüberprüfungsphase des Prozesses als **"Einschließen** " gekennzeichnet sind. Das Datenpaket wird als ZIP-Datei generiert. Wenn sie zum Download bereit ist, wählen Sie die Zeile des Berichts auf der Registerkarte " **Berichte** " auf der Seite "Details zur Anforderung von Rechten betroffener Personen" aus. Ein Flyoutbereich wird mit einer Schaltfläche zum **Herunterladen** des Berichts geöffnet. Die **nächsten** Schritte im Flyoutbereich bieten eine Kurzübersicht über die Arbeit mit den Inhalten.

Wenn Sie bereit sind, das Datenpaket herunterzuladen, wählen Sie **"Herunterladen**", suchen Sie Ihren Download, und öffnen Sie dann die heruntergeladene ZIP-Datei.

### <a name="contents-of-the-data-package"></a>Inhalt des Datenpakets

Die ZIP-Datei des Datenpakets enthält die folgenden Elemente:

- Ein Ordner mit dem Namen **Azure**: Dieser Ordner enthält die wichtigsten Materialien für Ihre betroffene Person. Weitere Informationen finden Sie unten in der ausführlichen Erläuterung.
- Dateien außerhalb des **Azure-Ordners** : Dazu können zwei Tabellen mit dem Namen **"Ergebnisse** " und " **Zusammenfassung**" gehören. Diese Dateien außerhalb des Azure-Ordners werden als Referenz bereitgestellt und sollten in erster Linie von den Administratoren Ihrer Organisation verwendet werden.

Wenn Priva Dateien für eine Anforderung von Rechten betroffener Personen identifiziert und abruft, werden die in diesem Prozess exportierten Dateien mithilfe eindeutiger Bezeichner umbenannt, um personenbezogene Daten zu schützen. Sie können mithilfe der **Export_load_file.csv** Datei auf die eindeutigen Namen mit den ursprünglichen Dateinamen verweisen. Da die ursprünglichen Dateinamen vertrauliche Informationen enthalten können, sollten Sie Ihre Richtlinien befolgen, die für solche Informationen gelten.

> [!NOTE]
> Wir empfehlen, den Inhalt dieses Ordners sorgfältig zu überprüfen und nur die erforderlichen Dateien an Ihre betroffene Person zu übermitteln. Sie sollten Ihre Antwort bewerten, um sicherzustellen, dass sie auf die Anforderungen des anwendbaren Rechts zugeschnitten ist.

### <a name="azure-folder-contents"></a>Azure-Ordnerinhalte

Öffnen Sie den **Azure-Ordner** , und öffnen Sie dann die **AEDExport.zip** Datei, die einen anderen Dateiordner mit einem langen Namen enthält, der aus Zahlen und Buchstaben besteht. Öffnen Sie den Ordner mit dem langen Namen, um die unten beschriebenen Inhalte anzuzeigen:

- **Extracted_text_files** Ordner: Enthält Text, der aus den systemeigenen Dateien extrahiert wurde (sofern unterstützt).
- **Ordner "NativeFiles** ": Enthält alle Elemente, die während der Datenüberprüfung im nativen Dateiformat als **enthalten** markiert wurden. Jedes Element in diesem Ordner erhält einen eindeutigen Dateinamen, um personenbezogene Daten zu schützen. Sie können diese eindeutigen Namen mit ihrem ursprünglichen Dateinamen mithilfe der Export_load_file.csv Datei querverweisen, die unten erläutert wird.
  - Dateien, die während des Datenüberprüfungsprozesses mithilfe der **Annotate-Funktion** bearbeitet wurden, befinden sich im Ordner **"NativeFiles** " und weisen das Suffix "_burn.pdf" auf.
- **Export_load_file.csv** Datei: Enthält die ursprünglichen Dateinamen, sodass Sie mit den eindeutigen Dateinamen im Ordner "NativeFiles" querverweisen können.
- **Zusammenfassungstextdatei** : Enthält eine Zusammenfassung der Dateitypen im Datenpaket, der Anzahl der Dateien und deren Größe.

##### <a name="what-to-do-with-the-folder-contents"></a>Vorgehensweise mit dem Ordnerinhalt

Öffnen Sie den **Azure-Ordner** und die ZIP-Dateien wie oben erläutert. Ihre nächste Aufgabe besteht darin, die Elemente zu überprüfen, zu bestimmen, was an die betroffene Person gesendet werden soll, und zip-Dateiinhalte bei Bedarf zu ändern.

For example, for an export request where the data subject want to receive a copy of all the items containing their personal data held by the organization, you'll want to closely review items in the **NativeFiles** folder and remove any item you don't want to send back to the data subject.

Für eine Zugriffsanforderung, bei der die betroffene Person eine Zusammenfassung aller von der Organisation gespeicherten persönlichen Informationen erhalten möchte, sollten Sie sich auf die **Zusammenfassungstextdatei** konzentrieren.

Ändern Sie die ZIP-Datei, um alle Inhalte zu entfernen, die Sie nicht in das endgültige Paket aufnehmen möchten. Sobald Sie fertig sind, senden Sie die ZIP-Datei auf sichere Weise an die betroffene Person, die den Antrag auf Rechte der betroffenen Person gestellt hat.

## <a name="audit-log"></a>Überwachungsprotokoll

Das Überwachungsprotokoll ist eine CSV-Datei, die einen Datensatz über den Fortschritt der Phasen für jede Anforderung von Rechten betroffener Personen bereitstellt. Es listet jede Phase des Prozesses zusammen mit dem Datum und der Uhrzeit des Abschlusses sowie den Benutzernamen der Person auf, die den Schritt abgeschlossen hat.

## <a name="tagged-files-reports"></a>Berichte zu markierten Dateien

Die Berichte, die als **"Dateien" gekennzeichnet sind,** sind CSV-Dateien, die die Inhaltselemente auflisten, auf die während des Datenüberprüfungsprozesses Tags angewendet wurden. Kategorien werden verwendet, um Inhaltselemente für weitere Aufmerksamkeit oder Aktionen durch die Organisation zu kennzeichnen. Erfahren Sie mehr über [Die Einstellungen für Tags](priva-settings.md#data-review-tags).

## <a name="retention-periods-for-reports-and-data"></a>Aufbewahrungszeiträume für Berichte und Daten

Berichte, die von Anträgen betroffener Personen und zugehöriger Daten generiert werden, z. B. in Azure gespeicherte kommentierte Dateien, werden für einen bestimmten Zeitraum gespeichert. Der Standardaufbewahrungszeitraum beträgt 30 Tage ab dem Datum, an dem eine Anfrage zu Rechten betroffener Personen geschlossen wird.

Der Zeitraum für die Datenaufbewahrung ist in Priva **Einstellungen** definiert und gilt für alle Anträge betroffener Personen. Führen Sie die folgenden Schritte aus, um den Aufbewahrungszeitraum für Daten anzuzeigen oder zu ändern:

1. Wählen Sie an einer beliebigen Stelle in Priva Anfragen zu Betroffenenrechten in der oberen rechten Ecke des Bildschirms **Einstellungen** (zahnradsymbol) aus.
2. Wählen Sie im linken Navigationsbereich " **Datenaufbewahrungszeiträume** " aus.
3. Wählen Sie im Dropdownmenü " **Gesammelte Daten und Berichte** " entweder 30 Tage oder 90 Tage als Aufbewahrungszeitraum aus.
4. Wählen Sie **"Speichern"** aus, um Ihre Einstellungen zu speichern.

Stellen Sie sicher, dass die von Ihnen ausgewählten Aufbewahrungszeiträume den Richtlinien und gesetzlichen Verpflichtungen Ihrer Organisation entsprechen.

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
