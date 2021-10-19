---
title: Überprüfen von Daten und Zusammenarbeit an Anträgen auf Rechte betroffener Personen im Datenschutzmanagement
f1.keywords:
- CSH
ms.author: v-jgriffee
author: jmgriffee
manager: laurawi
audience: Admin
ms.topic: article
ms.service: O365-seccomp
ms.localizationpriority: medium
ms.collection:
- M365-security-compliance
- M365-privacy-management
search.appverid:
- MOE150
- MET150
description: Erfahren Sie, wie Sie die von der Datenschutzverwaltung gesammelten Daten zu Betreffrechten überprüfen und an der Erledigung der Anforderung zusammenarbeiten.
ms.openlocfilehash: 7f0754007c70ef7836abf13ec0dbd50e9d9c8958
ms.sourcegitcommit: 85e085eb17af8b4efd1f45207445e1b3c3679600
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/19/2021
ms.locfileid: "60478249"
---
# <a name="review-data-and-collaborate-on-subject-rights-requests"></a>Überprüfen von Daten und Zusammenarbeit an Anträgen auf Rechte betroffener Personen

Nachdem Sie eine Anforderung zu Betreffrechten[(weitere Informationen)](privacy-management-subject-rights-requests-create.md)erstellt haben, verwendet die Datenschutzverwaltung Ihre Eingaben zu Ihrem Thema, um in der Microsoft 365 Umgebung Ihrer Organisation nach Übereinstimmungen zu suchen. Sobald diese Daten kompiliert wurden, können Sie die Ergebnisse überprüfen, Entscheidungen darüber treffen, was sie enthalten sollen, und Informationen nach Bedarf bearbeiten. Diese Schritte können von mehreren Benutzern über die Datenschutzverwaltungsschnittstelle gemeinsam ausgeführt werden.

## <a name="step-1-review-request-details-and-monitor-progress"></a>Schritt 1: Überprüfen von Anforderungsdetails und Überwachen des Fortschritts

Um die ersten Ergebnisse Ihrer Suche anzuzeigen, wechseln Sie zum Bereich "Datenschutzverwaltung" des [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) und öffnen **Sie Anträge von Antragstellerrechten.** Eine Liste aller offenen Antragstellerberechtigungsanforderungen finden Sie auf dieser Hauptseite.

Wählen Sie Ihre Anforderung in der Liste aus, um die Anforderungsdetails anzuzeigen. Hier erfahren Sie mehr über die Eigenschaften der Anforderung, die Suchergebnisse und den Status der Anforderung. Diese Seite wird zu Ihrem Hub, um an der Verwaltung der gefundenen Dateien, dem Erstellen von Berichten und Exporten und dem Abschließen der Anforderung zu arbeiten und zusammenzuarbeiten.

Zu den Kacheln auf der Seite mit den Anforderungsdetails gehören:

- **Details:** Die wesentlichen Details zu der Anforderung, einschließlich des Stichtags und des Anforderungsdatums, der Beschreibung und der zugehörigen Datenschutzbestimmungen.
- **Fortschritt:** Eine Zeitachse, die die abgeschlossenen Schritte und alle noch zu erledigenden Aufgaben angibt.
- Statistiken zur aktuellen Statusstufe. Diese Kachel enthält möglicherweise Informationen wie eine Datenvorkalkulationszusammenfassung, wie viele Elemente in Ihrer Suche und deren Speicherorte in Microsoft 365 gefunden wurden, oder den Status Ihrer Exporte.
- **Zu überprüfende Prioritätselemente:** Diese Kachel enthält Informationen zu wichtigen Elementen, die die Datenschutzverwaltung für Sie erkannt hat. Dies kann beispielsweise vertrauliche Informationen umfassen, die bereits eine Microsoft-Vertraulichkeitsbezeichnung aufweisen, oder Elemente mit Daten über mehrere Personen, die möglicherweise eine Bearbeitung erfordern. Dies hilft Administratoren zu wissen, wo sie mit ihrer Rezension beginnen können. Prioritätselemente finden Sie unter Daten, die durch Filtern nach der Spalte "Prioritätstypen" gesammelt werden.

### <a name="understand-progress-stages"></a>Grundlegendes zu Statusphasen

Anträge auf Antragstellerrechte durchlaufen mehrere Phasen. Einige werden automatisch weiter ausgeführt, während die Datenverwaltung ihre Datenauswertung durchführt, und andere, wenn Antragstellerrechte Administratoren und Mitwirkende auffordern, wesentliche Schritte wie das Überprüfen, Auswählen und Bearbeiten von Dateien durchzuführen.

Da Anforderungen möglicherweise im Laufe der Zeit oder von mehreren Mitwirkenden bearbeitet werden müssen, bietet das Datenschutzmanagement kontinuierliche Aktualisierungen des Status und Anleitungen zu den nächsten schritten. Diese Updates können auf der Übersichtsseite der Anforderung für Antragstellerrechte angezeigt werden.

1. **Datenvoranschlag:** Nachdem eine Anforderung erstellt wurde, identifiziert die Datenschutzverwaltung Elemente, die potenzielle Übereinstimmungen mit Ihrer betroffenen Person enthalten, und macht Notizen zu ihren Speicherorten in Microsoft 365. Wenn die Datenvorkalkulation abgeschlossen ist, werden Sie automatisch weiterkommen, um **Daten abzurufen,** es sei denn, es liegen Fehler vor oder Ihre Anforderung ist so eingestellt, dass sie hier zur Überprüfung durch den Administrator angehalten wird.
   - Ihre Anforderung kann so festgelegt werden, dass in dieser Phase eine Administratorüberprüfung erforderlich ist. Wenn Ihr Administrator feststellt, dass die ersten Ergebnisse Ihrer Suchabfrage zufriedenstellend aussehen, können Sie mit dem Abrufen von Daten fortfahren. Wenn Sie vor dem Fortfahren Änderungen vornehmen möchten, können Sie ihre Suchabfrage zuerst bearbeiten. Weitere Informationen finden Sie in Schritt 2. Sie können ihre Suchabfrage nicht mehr bearbeiten, nachdem Sie die Phase zum Abrufen von Daten initiiert haben.
   - Wenn Ihre Suchabfrage eine Schätzung großer Daten zurückgibt, d. h., sie liegt oberhalb des empfohlenen Schwellenwerts für die Dateigröße oder -anzahl der Datenverwaltung, können Sie versuchen, die Suche zu überarbeiten, um ihren Umfang zu verfeinern. Beachten Sie, dass Dateien, die einem übereinstimmenden Element zugeordnet sind (z. B. Dateianlagen in einer E-Mail), auf Ihre Gesamtsumme angerechnet werden können. Für Daten, die den Höchstwert für große Daten überschreiten, ist eine Suchrevision erforderlich, um fortzufahren.
1. **Abrufen von Daten:** Diese Phase gibt an, dass die Datenschutzverwaltung gerade dabei ist, Ihre Daten abzurufen. Sobald es abgeschlossen ist, wird es automatisch zum Überprüfen der **Daten** voran.
1. **Überprüfen Sie die Daten:** In dieser Phase sollten Ihre Mitwirkenden die Ergebnisse auf der Registerkarte **"Gesammelte Daten"** überprüfen und alle anwendbaren Aufgaben wie Redaction, Anwenden von Tags und Hinzufügen von Notizen ausführen. Wenn Sie mit der Rezension fertig sind, wählen Sie **"Rezension abschließen"** aus.
1. **Berichte generieren:** Ihre Berichte werden in dieser Phase generiert. Wenn Sie fertig sind, finden Sie diese auf der Registerkarte **"Berichte".** Ihre fertig gestellten Dateien können zur endgültigen Überprüfung und Übermittlung an die betroffene Person exportiert werden, die den Antrag gestellt hat.

## <a name="step-2-optional-view-and-edit-search-queries"></a>Schritt 2 (optional): Anzeigen und Bearbeiten von Suchabfragen

Wenn Sie detaillierte Informationen zur Datensuche hinter einer Anforderung für Betreffrechte anzeigen möchten, wählen Sie **Suchabfragedetails anzeigen** aus. Dadurch wird ein Bereich geöffnet, in dem die Abfrage zusammengefasst und weitere Details zu den Gefundenen angezeigt werden.

Hier haben Sie die Möglichkeit, **eine Vorschau** der Suchergebnisse anzuzeigen, um zu sehen, welcher Inhaltstyp für diese Abfrage zurückgegeben wird. Wenn Sie die Eigenschaften dieser Suche ändern möchten und die Phase "Daten abrufen" noch nicht begonnen haben, können Sie die **Suchabfrageoption** bearbeiten verwenden.

Der Assistent zum Bearbeiten von Suchabfragen bietet die Möglichkeit, Eigenschaften für die Identifizierung betroffener Personen, Ihre Suchfilter und -bedingungen sowie die Speicherorte, an denen nach Daten gesucht werden soll (einschließlich Exchange, SharePoint, OneDrive und/oder Teams) zu ändern oder hinzuzufügen. Verwenden Sie diese Optionen, um den gewünschten Grad an Spezifität zu erreichen. Sie können die endgültige Version der neuen Abfrage überprüfen, bevor Sie auf **"Speichern"** drücken.

Wenn Sie die Bearbeitung der Suchabfrage abgeschlossen haben, wird eine neue Suche ausgeführt, um Ihre vorherigen Suchergebnisse zu ersetzen. Dadurch wird Der Status im Abschnitt **"Fortschritt"** auf den ersten Schritt, die Schätzung der **Daten,** zurückgesetzt. Die neue Suche kann bis zu 60 Minuten dauern. Sobald dies abgeschlossen ist, werden auf der Detailseite der Anforderung aktualisierte Ergebnisse angezeigt.

## <a name="step-3-review-data"></a>Schritt 3: Überprüfen von Daten

In dieser Phase sollten Ihre Mitwirkenden die Ergebnisse auf der Registerkarte **"Gesammelte Daten"** überprüfen. Zu den wesentlichen Aufgaben gehören:

1. Überprüfen Sie die Liste der identifizierten Elemente, und wählen Sie aus, ob jede Datei in Ihre Zusammenfassungen und/oder Exporte aufgenommen werden soll. Wenn Sie keine gemeldete Übereinstimmung einschließen müssen, wählen Sie die Option "Ausschließen" aus. Wenn der Inhalt ein falsch positives Ergebnis zu sein scheint, können Sie "Keine Übereinstimmung" auswählen, um die Datei aus Ihren Endgültigen Berichten auszuschließen und das Element als etwas zu kennzeichnen, das von der Anforderung nicht hätte aufgenommen werden dürfen. Um den Status eines Elements festzulegen, verwenden Sie das Aktionsmenü (vertikale Ellipsen) neben seinem Namen, und wählen Sie ihre gewünschte Auswahl aus. Wenn Sie dazu aufgefordert werden, fügen Sie einen Hinweis für einen internen Verweis hinzu, um Ihre Entscheidung zu erläutern. Notizen sind erforderlich, wenn Dateien ausgeschlossen werden.
1. Verwenden Sie die Option **"Tags anwenden",** um Elemente zu identifizieren, die Aufmerksamkeit erfordern. Die verfügbaren Tags umfassen Optionen, die vom System bereitgestellt werden, z. B. das Markieren eines Elements für die Nachverfolgung, und können benutzerdefinierte Tags enthalten, wie unter den globalen Einstellungen definiert.
1. Verwenden Sie **Anmerkungen,** um Inlinemarkups zu erstellen oder Daten in einer ausgewählten Datei zu bearbeiten. Wenn Sie z. B. eine Datei für eine Person einschließen müssen, die auch die persönlichen Informationen anderer enthält, können Sie die **Bereichsrotierung** (unter der Zeichnungsschaltfläche in der Befehlsleiste) verwenden, um alle Informationen zu schwarz zu machen, die sich nicht auf die Person beziehen, die die Anforderung gestellt hat. Wenn Ihre Bearbeitungen abgeschlossen sind, wählen Sie **"Einschließen"** aus, um der Anforderung die bearbeitete Datei hinzuzufügen. Annotation erstellt eine Kopie der Datei, sodass nichts in der Originaldatei geändert wird und an ihrem ursprünglichen Speicherort verbleibt. Die Kopie wird in Ihrem Azure-Blob gespeichert.
1. Um Notizen zu einem Element zu überprüfen, wählen Sie es aus, und wechseln Sie zur Registerkarte **"Dateinotizen".** Sie können auch die Option **"Dateinotiz hinzufügen"** verwenden, um einen neuen Kommentar zu erstellen. Wenn Sie Notizen auf einer allgemeinen Fallebene überprüfen oder hinzufügen möchten, wechseln Sie zur Registerkarte **"Notizen"** oben, und verwenden **Sie "Fallnotiz hinzufügen".** Diese Hinweise sind für Benutzer sichtbar, die an der Anforderung arbeiten, werden jedoch nicht in den Finalbericht aufgenommen oder anderweitig für die betroffene Person freigegeben.
1. Wenn alle Elemente überprüft und ihre Status festgelegt wurden, wählen Sie **"Überprüfung abschließen"** aus. Dadurch wird ein Flyoverbereich geöffnet, in dem Sie eine Zusammenfassung der Daten überprüfen und alle relevanten Notizen hinzufügen können. Diese Hinweise dienen der internen Datensatzführung und werden nicht für die betroffene Person freigegeben.
1. Wählen Sie "Überprüfung abschließen" erneut aus, um fortzufahren. Zusammenfassungen Ihrer Entscheidungen werden später auf der Registerkarte **"Berichte"** bereitgestellt.

### <a name="collaborate-on-data-review"></a>Zusammenarbeit bei der Datenüberprüfung

Das Datenschutzmanagement unterstützt die Zusammenarbeit über Microsoft Teams, damit Ihre Gruppe bei Anträgen auf Rechte von Antragstellern zusammenarbeiten kann. Wenn Sie eine neue Anforderung erstellen, wird automatisch ein Teams Kanal erstellt und ihrer Anforderung standardmäßig zugeordnet. Hier können Sie die Anforderung besprechen und Eingaben und Beiträge sicher teilen. Um an der Unterhaltung teilzunehmen, öffnen Sie Ihre Anforderung, und verwenden Sie die Option **"Mit Mitarbeitern chatten".** Dadurch werden Microsoft Teams geöffnet und Sie in den Kanal "Allgemein" für die Teamwebsite Ihrer Antragstellerrechte-Anforderung platziert.

Um die Liste der aktiven Mitarbeiter zu überprüfen, die Ihre Teamwebsite anzeigen und dazu beitragen können, öffnen Sie in Ihrer Anfrage zu den Betreffrechten die Registerkarte **"Mitarbeiter".** Um weitere Benutzer zur Zusammenarbeit an dieser Anforderung hinzuzufügen, wählen Sie die Option zum **Hinzufügen eines Mitarbeiters** aus.

Um das Standardverhalten des Generierens von Teams Websites beim Erstellen einer Anforderung für Betreffrechte zu ändern, wechseln Sie zu **Einstellungen** in der oberen Navigationsleiste, und wählen Sie **Teams Zusammenarbeit** aus, um die Einstellung zu ändern.

Sie können auch die Option **"Freigeben"** in der oberen rechten Ecke in einem Antrag auf Subjektrechte verwenden, um Personen über Teams oder E-Mail einzugeben oder den Link zu der Seite in der Datenschutzverwaltung zu kopieren. Mithilfe der Freigabe über Teams können Sie eine vorhandene Teams Website und einen Kanal auswählen, die für Ihr Konto verfügbar sind. Dort wird ein Link zu diesem Fall zusammen mit allen von Ihnen bereitgestellten Nachrichten bereitgestellt.

## <a name="step-4-close-the-request"></a>Schritt 4: Schließen der Anforderung

Wenn Sie alle erforderlichen Aktionen ausgeführt haben, um die Anforderung zu Den Betreffrechten aufzulösen, wählen Sie **"Anforderung schließen"** aus. Dadurch wird der Finalbericht erstellt, der verschlüsselt und auf der **Registerkarte "Berichte"** zur Verfügung gestellt wird. Der Abschluss kann je nach Anzahl der Dateien in der Anforderung eine Weile dauern.

## <a name="next-steps"></a>Nächste Schritte
Weitere Informationen zum Arbeiten mit Berichten und zum Abschließen von Anträgen auf Rechte von Antragstellern finden Sie unter "Erfüllen von [Anträgen auf Antragstellerrechte".](privacy-management-subject-rights-requests-fulfill.md)

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Datenschutzverwaltung](privacy-management-disclaimer.md)
