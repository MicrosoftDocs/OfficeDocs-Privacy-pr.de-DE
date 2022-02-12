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
ms.openlocfilehash: d8420667d3ad9bd2e42a1d6fc34b4681d7166452
ms.sourcegitcommit: 1f3f2757f456628ec904bc3df985b00ffba8f892
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 02/11/2022
ms.locfileid: "62542843"
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

#### <a name="data-estimate"></a>Datenvoranschlag
Nachdem Sie eine Anforderung erstellt haben, beginnt Priva sofort mit der Suche nach potenziellen Übereinstimmungen mit der betroffenen Person in Ihrer Microsoft 365 Umgebung. Nachdem wir alle Elemente identifiziert haben, von denen wir glauben, dass sie Ihren Kriterien entsprechen, wird die Schätzung auf der Übersichtsseite **der** Anforderung auf der **Datenvorkalkulationskarte** angezeigt. Die Datenmenge innerhalb des Umfangs Ihrer Suche wirkt sich auf die Zeitspanne aus, die zum Abschließen der Schätzung benötigt wird.

Ihre Anforderung wechselt automatisch zur nächsten Phase des Datenabrufs, in der alle Inhaltselemente gesammelt werden, damit Ihre Beteiligten an ihrer Datenüberprüfung zusammenarbeiten können. In einigen Fällen unterbrechen wir jedoch die Datenvorkalkulation, bevor wir zum Abruf wechseln, und benachrichtigen Sie über die nächsten Schritte, die Sie ausführen müssen, bevor Sie fortfahren.

Sie können auch festlegen, dass die Datenvorkalkulationsphase automatisch angehalten wird, wenn Sie zum ersten Mal einen Antrag auf Antragstellerrechte erstellen. Wählen Sie während des Erstellungsprozesses die Option **"Erste Schätzung abrufen** " während des **Schritts "Sucheinstellungen** " aus. Überprüfen Sie Details zum Schritt mit den [Sucheinstellungen](subject-rights-requests-create.md#define-search-settings).

#### <a name="pause-in-data-estimate-for-large-search-results"></a>Anhalten der Datenvorkalkulation für große Suchergebnisse

Priva wird feststellen, ob Ihre Daten schätzungsweise eine große Menge von zu überprüfenden Elementen zurückgibt (über 10.000 Elemente). Die Schätzung wird angehalten, sodass Sie eine Vorschau der Ergebnisse anzeigen und entscheiden können, ob [Die Suchabfrage](subject-rights-requests-create.md#refine-your-search) für spezifischere Speicherorte oder Bedingungen bearbeitet oder die identifizierten Elemente weiterhin abgerufen werden sollen.  Wir zeigen Ihnen auf dem Bildschirm die Anzahl der Elemente und das Datenvolumen, die ihrer Suche entsprechen. Sie haben eine oder beide der folgenden Optionen in einer Meldungsleiste am oberen Rand des Bildschirms:

- Eine Schaltfläche " **Suchabfrage bearbeiten** " führt Sie direkt in die Sucheinstellungen der Anforderung, um strengere Parameter festzulegen und eine neue Schätzung zu generieren.
- Solange Ihre Suchabfrage nicht mehr als 300.000 Elemente enthält, wird auch eine Option zum **Abrufen von Daten** angezeigt. Auf diese Weise können Sie auswählen, dass Sie Ihre Suche nicht bearbeiten und die Daten weiterhin sammeln möchten.

#### <a name="retrieve-data"></a>Abrufen von Daten
Die Datenabrufphase ist der Zeitpunkt, an dem alle Dateien, E-Mails, Chats, Bilder und anderen Inhaltselemente, die die personenbezogenen Daten der betroffenen Person enthalten, abgerufen und in einem Azure Blob Storage-Container zur Überprüfung zusammengestellt werden. Der Datenabruf kann je nach Datenmenge einige Minuten oder deutlich länger dauern. Wenn diese Phase abgeschlossen ist, wird die Anforderung automatisch zur nächsten Phase der **Überprüfungsdaten** verschoben.

#### <a name="review-data"></a>Überprüfen von Daten
 In dieser Phase sollten Ihre Mitwirkenden die Ergebnisse auf der Registerkarte **"Gesammelte Daten** " überprüfen und alle anwendbaren Aufgaben wie Redaction, Anwenden von Tags und Hinzufügen von Notizen ausführen. Wenn Sie mit der Rezension fertig sind, wählen Sie " **Rezension abschließen**" aus.

#### <a name="generate-reports"></a>Generieren von Berichten
Ihre Berichte werden in dieser Phase generiert. Wenn Sie fertig sind, finden Sie diese auf der Registerkarte " **Berichte** ". Ihre fertig gestellten Dateien können zur endgültigen Überprüfung und Übermittlung an die betroffene Person exportiert werden, die den Antrag gestellt hat.

#### <a name="close-the-request"></a>Schließen der Anforderung
Eine geschlossene Anforderung gibt an, dass alle Arbeiten abgeschlossen wurden, um diese Anforderung für Die Rechte des Betreffs zu erfüllen. Alle gesammelten Daten und Berichte werden gemäß Ihren [Einstellungen für die Datenaufbewahrung](priva-settings.md#data-retention-periods) aufbewahrt.

## <a name="step-2-optional-view-and-edit-search-queries"></a>Schritt 2 (optional): Anzeigen und Bearbeiten von Suchabfragen

Um detaillierte Informationen zur Datensuche hinter einer Anforderung für Betreffrechte anzuzeigen, wählen Sie **Suchabfragedetails anzeigen** aus. Dadurch wird ein Bereich geöffnet, in dem die Abfrage zusammengefasst und weitere Details zu den Gefundenen angezeigt werden.

Hier haben Sie die Möglichkeit, **eine Vorschau der Suchergebnisse** anzuzeigen, um zu sehen, welcher Inhaltstyp für diese Abfrage zurückgegeben wird. Wenn Sie die Eigenschaften dieser Suche ändern möchten und die Phase "Daten abrufen" noch nicht begonnen haben, können Sie die **Suchabfrageoption** bearbeiten verwenden.

Mit dem geführten Bearbeitungsabfrageprozess können Sie Eigenschaften für die Identifizierung betroffener Personen, Ihre Suchfilter und -bedingungen sowie die Speicherorte ändern oder hinzufügen, an denen nach Daten gesucht werden soll (einschließlich Exchange, SharePoint, OneDrive und/oder Teams). Verwenden Sie diese Optionen, um den gewünschten Grad an Spezifität zu erreichen. Sie können die endgültige Version Der neuen Abfrage überprüfen, bevor Sie auf **"Speichern**" drücken.

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

Priva unterstützt die Zusammenarbeit über Microsoft Teams, damit Ihre Gruppe bei Anträgen auf Rechte von Antragstellern zusammenarbeiten kann. Wenn Sie eine neue Anforderung erstellen, wird automatisch ein Teams Kanal erstellt und ihrer Anforderung standardmäßig zugeordnet. Hier können Sie die Anforderung besprechen und Eingaben und Beiträge sicher teilen. Um an der Unterhaltung teilzunehmen, öffnen Sie Ihre Anforderung, und verwenden Sie die Option **"Mit Mitarbeitern chatten** ". Dadurch werden Microsoft Teams geöffnet und Sie in den Kanal "Allgemein" für die Teamwebsite Ihrer Antragstellerrechte-Anforderung platziert.

Um die Liste der aktiven Mitarbeiter zu überprüfen, die Ihre Teamwebsite anzeigen und dazu beitragen können, öffnen Sie in Ihrer Anfrage zu den Betreffrechten die Registerkarte **"Mitarbeiter** ". Um weitere Benutzer hinzuzufügen, die an dieser Anforderung zusammenarbeiten sollen, wählen Sie die Option zum **Hinzufügen eines Mitarbeiters** aus.

Um das Standardverhalten des Generierens von Teams Websites beim Erstellen einer Anforderung für Betreffrechte zu ändern, wechseln **Sie zu Einstellungen** in der oberen Navigationsleiste, und wählen Sie **Teams Zusammenarbeit** aus, um die Einstellung zu ändern.

Sie können auch die Option **"Freigeben"** in der oberen rechten Ecke innerhalb einer Anforderung für das Betreffsrecht verwenden, um Personen über Teams oder E-Mail in eine Schleife einzuschleiern oder den Link auf die Seite in Priva zu kopieren. Die Freigabe über Teams ermöglicht es Ihnen, eine vorhandene Teams Website und einen Kanal auszuwählen, die für Ihr Konto verfügbar sind. Dort wird ein Link zu diesem Fall zusammen mit allen von Ihnen bereitgestellten Nachrichten bereitgestellt.

## <a name="step-4-close-the-request"></a>Schritt 4: Schließen der Anforderung

Wenn Sie alle erforderlichen Aktionen ausgeführt haben, um Ihre Anforderung zu Den Betreffrechten zu lösen, wählen Sie **"Anforderung schließen**" aus. Dadurch wird der Finalbericht erstellt, der auf der **Registerkarte "Berichte"** zu finden ist. Der Abschluss kann je nach Anzahl der Dateien in der Anforderung eine Weile dauern.

## <a name="next-steps"></a>Nächste Schritte
Weitere Informationen zum Arbeiten mit Berichten und zum Abschließen von Anträgen auf Antragstellerrechte finden Sie unter ["Erstellen von Berichten und Erfüllen einer Anforderung zu Betreffrechten"](subject-rights-requests-reports.md).

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
