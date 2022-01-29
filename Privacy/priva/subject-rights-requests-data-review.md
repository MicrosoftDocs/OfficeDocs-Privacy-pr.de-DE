---
title: Überprüfen von Daten für eine Anforderung zu Betreffrechten
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
description: Erfahren Sie, wie Sie von Microsoft Priva gesammelte Daten zu Anträgen von Antragstellerrechten überprüfen und an der Erledigung der Anforderung zusammenarbeiten.
ms.openlocfilehash: cac4064a1e0dc2860d061748793a91c0b86e0896
ms.sourcegitcommit: f145dff5e387a8e26db2f3a2c7de125978fbacc9
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/28/2022
ms.locfileid: "62249043"
---
# <a name="review-data-for-a-subject-rights-request"></a>Überprüfen von Daten für eine Anforderung zu Betreffrechten

Nachdem Sie in Microsoft Priva eine Anforderung zu Betreffrechten ([weitere Informationen](subject-rights-requests-create.md)) erstellt haben, verwendet die Lösung für Anträge betroffener Personen Ihre Eingaben, um nach Übereinstimmungen über Ihre betroffene Person in der Microsoft 365 Umgebung Ihrer Organisation zu suchen. Sobald diese Daten kompiliert wurden, können Sie die Ergebnisse überprüfen, Entscheidungen darüber treffen, was einbezogen werden soll, und Informationen nach Bedarf bearbeiten. Diese Schritte können von mehreren Benutzern über die Priva-Schnittstelle gemeinsam ausgeführt werden.

## <a name="step-1-review-request-details-and-monitor-progress"></a>Schritt 1: Überprüfen von Anforderungsdetails und Überwachen des Fortschritts

Um die ersten Ergebnisse Ihrer Suche anzuzeigen, wechseln Sie zum Priva-Bereich des [Microsoft 365 Compliance Center](https://compliance.microsoft.com/), und öffnen **Sie Antragstellerrechteanforderungen**. Eine Liste aller offenen Antragstellerberechtigungsanforderungen finden Sie auf dieser Hauptseite.

Wählen Sie Ihre Anforderung in der Liste aus, um die Anforderungsdetails anzuzeigen. Hier erfahren Sie mehr über die Eigenschaften der Anforderung, die Suchergebnisse und den Status der Anforderung. Diese Seite wird zu Ihrem Hub, um an der Verwaltung der gefundenen Dateien, dem Erstellen von Berichten und Exporten und dem Abschließen der Anforderung zu arbeiten und zusammenzuarbeiten.

Zu den Kacheln auf der Seite mit den Anforderungsdetails gehören:

- **Details**: Die wesentlichen Details zu der Anforderung, einschließlich der Frist und des Anforderungsdatums, der Beschreibung und der zugehörigen Datenschutzbestimmungen.
- **Fortschritt**: Eine Zeitachse, die die abgeschlossenen Schritte und alle noch zu erledigenden Aufgaben angibt.
- Statistiken zur aktuellen Statusstufe. Diese Kachel enthält möglicherweise Informationen wie eine Datenvorkalkulationszusammenfassung, wie viele Elemente in Ihrer Suche und deren Speicherorte in Microsoft 365 gefunden wurden, oder den Status Ihrer Exporte.
- **Zu überprüfende Prioritätselemente**: Diese Kachel enthält Informationen zu allen wichtigen Elementen, die Priva für Sie erkannt hat. Dies kann beispielsweise vertrauliche Informationen umfassen, die bereits eine Microsoft-Vertraulichkeitsbezeichnung aufweisen, oder Elemente mit Daten über mehrere Personen, die möglicherweise eine Bearbeitung erfordern. Dies hilft Administratoren zu wissen, wo sie mit ihrer Rezension beginnen können. Prioritätselemente finden Sie unter Daten, die durch Filtern nach der Spalte "Prioritätstypen" gesammelt werden.

### <a name="understand-progress-stages"></a>Grundlegendes zu Statusphasen

Anträge auf Antragstellerrechte durchlaufen mehrere Phasen. Einige werden automatisch während der Datenauswertung von Priva ausgeführt, und andere gehen weiter, wenn Antragstellerrechte Administratoren und Mitwirkende auffordern, wichtige Schritte wie das Überprüfen, Auswählen und Bearbeiten von Dateien auszuführen.

Da Anforderungen möglicherweise im Laufe der Zeit oder von mehreren Mitwirkenden bearbeitet werden müssen, bietet Priva kontinuierliche Updates zum Status und Anleitungen zu den nächsten schritten. Diese Updates können auf der Übersichtsseite der Anforderung für Antragstellerrechte angezeigt werden.

1. **Datenvorkalkulation**: Nachdem eine Anforderung erstellt wurde, identifiziert Priva Elemente, die potenzielle Übereinstimmungen mit Ihrer betroffenen Person enthalten, und macht Notizen zu ihren Speicherorten in Microsoft 365. Wenn die Datenvorkalkulation abgeschlossen ist, werden Sie automatisch weiterkommen, um **Daten abzurufen**, es sei denn, es liegen Fehler vor oder Ihre Anforderung ist so eingestellt, dass sie hier angehalten wird, um die Überprüfung durch den Administrator durchzuführen.
   - Ihre Anforderung kann so festgelegt werden, dass in dieser Phase eine Administratorüberprüfung erforderlich ist. Wenn Ihr Administrator feststellt, dass die ersten Ergebnisse Ihrer Suchabfrage zufriedenstellend aussehen, können Sie mit dem Abrufen von Daten fortfahren. Wenn Sie vor dem Fortfahren Änderungen vornehmen möchten, können Sie ihre Suchabfrage zuerst bearbeiten. Weitere Informationen finden Sie in Schritt 2. Sie können Ihre Suchabfrage nicht mehr bearbeiten, nachdem Sie die Phase zum Abrufen von Daten initiiert haben.
   - Wenn Ihre Suchabfrage eine Schätzung großer Daten zurückgibt, d. h., sie liegt oberhalb des empfohlenen Schwellenwerts für die Dateigröße oder -anzahl von Priva, können Sie versuchen, die Suche zu überarbeiten, um den Bereich zu verfeinern. Beachten Sie, dass Dateien, die einem übereinstimmenden Element zugeordnet sind (z. B. Dateianlagen in einer E-Mail), auf Ihre Gesamtsumme angerechnet werden können. Für Daten, die den Höchstwert für große Daten überschreiten, ist eine Suchrevision erforderlich, um fortzufahren.
1. **Abrufen von Daten**: Diese Phase gibt an, dass Priva gerade dabei ist, Ihre Daten abzurufen. Nach Abschluss des Vorgangs wird automatisch eine **Überprüfung der Daten durchgeführt**.
1. **Überprüfen von Daten**: In dieser Phase sollten Ihre Mitwirkenden die Ergebnisse auf der Registerkarte **"Gesammelte Daten** " überprüfen und alle anwendbaren Aufgaben wie Redaction, Anwenden von Tags und Hinzufügen von Notizen ausführen. Wenn Sie mit der Rezension fertig sind, wählen Sie " **Rezension abschließen**" aus.
1. **Berichte generieren**: Ihre Berichte werden in dieser Phase generiert. Wenn Sie fertig sind, finden Sie diese auf der Registerkarte " **Berichte** ". Ihre fertig gestellten Dateien können zur endgültigen Überprüfung und Übermittlung an die betroffene Person exportiert werden, die den Antrag gestellt hat.

## <a name="step-2-optional-view-and-edit-search-queries"></a>Schritt 2 (optional): Anzeigen und Bearbeiten von Suchabfragen

Um detaillierte Informationen zur Datensuche hinter einer Anforderung für Betreffrechte anzuzeigen, wählen Sie **Suchabfragedetails anzeigen** aus. Dadurch wird ein Bereich geöffnet, in dem die Abfrage zusammengefasst und weitere Details zu den Gefundenen angezeigt werden.

Hier haben Sie die Möglichkeit, **eine Vorschau der Suchergebnisse** anzuzeigen, um zu sehen, welcher Inhaltstyp für diese Abfrage zurückgegeben wird. Wenn Sie die Eigenschaften dieser Suche ändern möchten und die Phase "Daten abrufen" noch nicht begonnen haben, können Sie die **Suchabfrageoption** bearbeiten verwenden.

Der Assistent zum Bearbeiten von Suchabfragen bietet die Möglichkeit, Eigenschaften für die Identifizierung betroffener Personen, Ihre Suchfilter und -bedingungen sowie die Speicherorte, an denen nach Daten gesucht werden soll (einschließlich Exchange, SharePoint, OneDrive und/oder Teams) zu ändern oder hinzuzufügen. Verwenden Sie diese Optionen, um den gewünschten Grad an Spezifität zu erreichen. Sie können die endgültige Version Der neuen Abfrage überprüfen, bevor Sie auf **"Speichern**" drücken.

Wenn Sie die Bearbeitung der Suchabfrage abgeschlossen haben, wird eine neue Suche ausgeführt, um Ihre vorherigen Suchergebnisse zu ersetzen. Dadurch wird Ihr Status im Abschnitt **"Fortschritt** " auf den ersten Schritt, **die Datenvorkalkulation**, zurückgesetzt. Die neue Suche kann bis zu 60 Minuten dauern. Sobald dies abgeschlossen ist, werden auf der Detailseite der Anforderung aktualisierte Ergebnisse angezeigt.

## <a name="step-3-review-data"></a>Schritt 3: Überprüfen von Daten

In dieser Phase sollten Ihre Mitwirkenden die Ergebnisse auf der Registerkarte **"Gesammelte Daten** " überprüfen. Zu den wesentlichen Aufgaben gehören:

1. Überprüfen Sie die Liste der identifizierten Elemente, und wählen Sie aus, ob jede Datei in Ihre Zusammenfassungen und/oder Exporte aufgenommen werden soll. Wenn Sie keine gemeldete Übereinstimmung einschließen müssen, wählen Sie die Option "Ausschließen" aus. Wenn der Inhalt ein falsch positives Ergebnis zu sein scheint, können Sie "Keine Übereinstimmung" auswählen, um die Datei aus Ihren Endgültigen Berichten auszuschließen und das Element als etwas zu kennzeichnen, das von der Anforderung nicht angenommen werden sollte. Um den Status eines Elements festzulegen, verwenden Sie das Aktionsmenü (vertikale Ellipsen) neben seinem Namen, und wählen Sie die gewünschte Auswahl aus. Wenn Sie dazu aufgefordert werden, fügen Sie einen Hinweis für einen internen Verweis hinzu, um Ihre Entscheidung zu erläutern. Notizen sind erforderlich, wenn Dateien ausgeschlossen werden.
1. Verwenden Sie die Option **"Tags anwenden** ", um Elemente zu identifizieren, die Aufmerksamkeit erfordern. Die verfügbaren Tags umfassen vom System bereitgestellte Optionen, z. B. das Markieren eines Elements für die Nachverfolgung, und können benutzerdefinierte Tags enthalten, wie unter globalen Einstellungen definiert.
1. Verwenden Sie **Anmerkungen** , um Inlinemarkups zu erstellen oder Daten in einer ausgewählten Datei zu bearbeiten. Wenn Sie z. B. eine Datei für eine Person einschließen müssen, die auch die persönlichen Informationen anderer enthält, können Sie die **Bereichsrotaktion** (unter der Zeichnungsschaltfläche in der Befehlsleiste) verwenden, um alle Informationen zu schwarz zu machen, die sich nicht auf die Person beziehen, die die Anforderung gestellt hat. Wenn Ihre Bearbeitungen abgeschlossen sind, wählen Sie **"Einschließen** " aus, um der Anforderung die bearbeitete Datei hinzuzufügen. Annotation erstellt eine Kopie der Datei, sodass nichts in der Originaldatei geändert wird und an ihrem ursprünglichen Speicherort verbleibt. Die Kopie wird in Ihrem Azure-Blob gespeichert.
1. Um Notizen zu einem Element zu überprüfen, wählen Sie es aus, und wechseln Sie zur Registerkarte **"Dateinotizen** ". Sie können auch die Option **"Dateinotiz hinzufügen** " verwenden, um einen neuen Kommentar zu erstellen. Wenn Sie Notizen auf gesamter Fallebene überprüfen oder hinzufügen möchten, wechseln Sie zur Hauptregisterkarte **"Notizen** " oben, und verwenden **Sie "Fallnotiz hinzufügen"**. Diese Hinweise sind für Benutzer sichtbar, die an der Anforderung arbeiten, werden jedoch nicht in den  Finalbericht aufgenommen oder anderweitig für die betroffene Person freigegeben.
1. Wenn alle Elemente überprüft und ihre Status festgelegt wurden, wählen Sie **"Überprüfung abschließen**" aus. Dadurch wird ein Flyoverbereich geöffnet, in dem Sie eine Zusammenfassung der Daten überprüfen und alle relevanten Notizen hinzufügen können. Diese Hinweise dienen der internen Datensatzführung und werden nicht für die betroffene Person freigegeben.
1. Wählen Sie "Überprüfung abschließen" erneut aus, um fortzufahren. Zusammenfassungen Ihrer Entscheidungen werden später auf der Registerkarte " **Berichte** " bereitgestellt.

### <a name="collaborate-on-data-review"></a>Zusammenarbeit bei der Datenüberprüfung

Priva unterstützt die Zusammenarbeit über Microsoft Teams, damit Ihre Gruppe an Anträgen von Antragstellerrechten zusammenarbeiten kann. Wenn Sie eine neue Anforderung erstellen, wird automatisch ein Teams Kanal erstellt und ihrer Anforderung standardmäßig zugeordnet. Hier können Sie die Anforderung besprechen und Eingaben und Beiträge sicher teilen. Um an der Unterhaltung teilzunehmen, öffnen Sie Ihre Anforderung, und verwenden Sie die Option **"Mit Mitarbeitern chatten** ". Dies öffnet Microsoft Teams und platziert Sie im Kanal "Allgemein" für die Teamwebsite Ihrer Antragstellerrechte.

Um die Liste der aktiven Mitarbeiter zu überprüfen, die Ihre Teamwebsite anzeigen und dazu beitragen können, öffnen Sie in Ihrer Anfrage zu den Betreffrechten die Registerkarte **"Mitarbeiter** ". Um weitere Benutzer hinzuzufügen, die an dieser Anforderung zusammenarbeiten sollen, wählen Sie die Option zum **Hinzufügen eines Mitarbeiters** aus.

Um das Standardverhalten des Generierens von Teams Websites beim Erstellen einer Anforderung für Betreffrechte zu ändern, wechseln **Sie zu Einstellungen** in der oberen Navigationsleiste, und wählen Sie **Teams Zusammenarbeit** aus, um die Einstellung zu ändern.

Sie können auch die Option **"Freigeben"** in der oberen rechten Ecke innerhalb einer Anforderung für ein Betreffrecht verwenden, um Personen über Teams oder E-Mail einzugeben oder den Link auf die Seite in Priva zu kopieren. Mit der Freigabe über Teams können Sie eine vorhandene Teams Website und einen Kanal auswählen, die für Ihr Konto verfügbar sind, wo sie einen Link zu diesem Fall zusammen mit allen von Ihnen bereitgestellten Nachrichten bereitstellen.

## <a name="step-4-close-the-request"></a>Schritt 4: Schließen der Anforderung

Wenn Sie alle erforderlichen Aktionen ausgeführt haben, um Ihre Anforderung zu Den Betreffrechten zu lösen, wählen Sie **"Anforderung schließen**" aus. Dadurch wird der endgültige Bericht erstellt, der verschlüsselt und auf der **Registerkarte "Berichte"** zur Verfügung gestellt wird. Der Abschluss kann je nach Anzahl der Dateien in der Anforderung eine Weile dauern.

## <a name="next-steps"></a>Nächste Schritte
Weitere Informationen zum Arbeiten mit Berichten und zum Abschließen von Anträgen auf Antragstellerrechte finden Sie unter ["Erstellen von Berichten und Erfüllen einer Anforderung zu Betreffrechten"](subject-rights-requests-reports.md).

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
