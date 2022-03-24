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
ms.openlocfilehash: 7e9222a67d2f7b7e81141d1ec9a65688800f436e
ms.sourcegitcommit: 02921b2dd438a517191522567908046b136a89e2
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/23/2022
ms.locfileid: "63758434"
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

Anträge auf Antragstellerrechte durchlaufen mehrere Phasen. Einige Zustände werden automatisch ausgeführt, und andere Phasen werden nach vorne ausgeführt, wenn Administratoren und Mitwirkende administratoren und Mitwirkende auffordern, wichtige Schritte wie das Überprüfen von Dateien auszuführen.

Da Anforderungen möglicherweise im Laufe der Zeit oder von mehreren Mitwirkenden bearbeitet werden müssen, bietet Priva kontinuierliche Updates zum Status und Anleitungen zu den nächsten schritten. Diese Updates können auf der Registerkarte **"Übersicht** " auf der Detailseite einer Anforderung für Betreffrechte angezeigt werden.

#### <a name="data-estimate"></a>Datenvoranschlag
Nachdem Sie eine Anforderung erstellt haben, beginnt Priva sofort mit der Suche nach potenziellen Übereinstimmungen mit der betroffenen Person in Ihrer Microsoft 365 Umgebung. Nachdem wir alle Elemente identifiziert haben, von denen wir glauben, dass sie Ihren Kriterien entsprechen, wird die Schätzung auf der Übersichtsseite **der** Anforderung auf der **Datenvorkalkulationskarte** angezeigt. Die Datenmenge innerhalb des Umfangs Ihrer Suche wirkt sich auf die Dauer aus, die zum Abschließen der Schätzung benötigt wird.

Ihre Anforderung wechselt automatisch zur nächsten Phase des Datenabrufs, in der alle Inhaltselemente gesammelt werden, damit die Beteiligten an der Datenüberprüfung zusammenarbeiten können. In einigen Fällen unterbrechen wir die Datenvorkalkulation, bevor wir zum Abruf wechseln, und benachrichtigen Sie über die nächsten Schritte, die sie ausführen müssen, bevor Sie fortfahren.

Sie können auch festlegen, dass die Datenvorkalkulationsphase automatisch angehalten wird, wenn Sie zum ersten Mal einen Antrag auf Antragstellerrechte erstellen. Wählen Sie während des Erstellungsprozesses die Option **"Erste Schätzung abrufen** " während des **Schritts "Sucheinstellungen** " aus. Überprüfen Sie Details zum Schritt mit den [Sucheinstellungen](subject-rights-requests-create.md#define-search-settings).

#### <a name="pause-in-data-estimate-for-large-search-results"></a>Anhalten der Datenvorkalkulation für große Suchergebnisse

Priva wird feststellen, ob Ihre Daten schätzungsweise eine große Anzahl von zu überprüfenden Elementen zurückgibt (über 10.000 Elemente). Die Schätzung wird angehalten, sodass Sie eine Vorschau der Ergebnisse anzeigen und entscheiden können, ob [Die Suchabfrage](subject-rights-requests-create.md#refine-your-search) für spezifischere Speicherorte oder Bedingungen bearbeitet oder die identifizierten Elemente weiterhin abgerufen werden sollen.  Wir zeigen Ihnen auf dem Bildschirm die Anzahl der Elemente und das Datenvolumen, die ihrer Suche entsprechen. Sie haben eine oder beide der folgenden Optionen in einer Meldungsleiste am oberen Rand des Bildschirms:

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

In dieser Phase sollten Ihre Mitwirkenden die Ergebnisse auf der Registerkarte **"Gesammelte Daten**" überprüfen. Ein Teams Kanal wird automatisch eingerichtet, um die Inhaltsüberprüfung durch alle Beteiligten zu vereinfachen. Weitere Informationen finden Sie [unter "Zusammenarbeit bei der Datenüberprüfung](#collaborate-on-data-review) ". Die wesentlichen Aufgaben für den Datenüberprüfungsschritt werden unten beschrieben.

#### <a name="mark-items-as-include-or-exclude-and-add-notes"></a>Markieren von Elementen als "Einschließen" oder "Ausschließen" und Hinzufügen von Notizen

Überprüfen Sie die Liste der identifizierten Elemente, die von Ihrer Suche zurückgegeben werden. Wenn Sie entscheiden, dass das Element als Teil des endgültigen Berichts an die betroffene Person aufgenommen werden soll, wählen Sie " **Einschließen** " in der Befehlsleiste oben in der Liste der Elemente aus. Sie können auch die blaue Schaltfläche **"Einschließen** " im Inhaltsprüfungsbereich rechts neben der Liste der Elemente auswählen. Wenn Sie **"Einschließen"** auswählen, wird ein Flyoutbereich mit einer Option zum Hinzufügen von Notizen angezeigt. Wenn Sie fertig sind, wählen Sie **"Übermitteln** " aus, um den Rezensionsstatus des Elements als **"Einschließen**" zu speichern.

Wenn das Element nicht als Teil der Anforderung gehört, wählen Sie " **Ausschließen** " in der Befehlsleiste oder die Schaltfläche " **Ausschließen"** im Inhaltsprüfungsbereich aus. Das Ausschließen eines Elements bedeutet, dass es nicht in die [endgültigen Berichte einbezogen wird, die für die betroffene Person generiert werden](subject-rights-requests-reports.md).

> [!NOTE]
> Wenn Sie ein Element als **"Ausschließen**" markieren, müssen Sie eine Notiz als Begründung hinzufügen, warum sie sich nicht auf die Anforderung von Betreffrechten bezieht. Notizen dienen internen Zwecken und sind nicht in  Fertigberichten enthalten.

Wenn der Inhalt als falsch positiv erscheint, wählen Sie **"Keine Übereinstimmung** " aus, und wählen Sie im Flyoutbereich " **Bestätigen**" aus. Diese Aktion schließt die Datei aus Ihren  Finalberichten aus und kennzeichnet das Element als etwas, das bei der Suche nicht erkannt worden sein sollte.

#### <a name="apply-tags"></a>Apply tags

Tags können verwendet werden, um Elemente zu identifizieren, die weitere Aufmerksamkeit erfordern. Priva bietet drei Standardtags – **Nachverfolgung**, **Löschung** und **Aktualisierung** –, für die Sie eine Beschreibung festlegen können. Priva bietet auch zwei benutzerdefinierte Tags, die Sie benennen und beschreiben können.

Wenn Sie beispielsweise während der Datenüberprüfung feststellen, dass ein Inhaltselement nicht von Ihrer Organisation aufbewahrt werden muss, können Sie das **Tag "Löschen"** anwenden und dann eine Liste aller markierten Dateien exportieren, damit Sie die identifizierten Elemente löschen können, wenn Sie mit der Anforderung fertig sind.

Die fünf Tags, die Sie in **Einstellungen** verwalten, gelten für alle Ihre Antragstellerrechteanforderungen.

**So fügen Sie Tags hinzu oder entfernen sie:**

- Wählen Sie das Element aus der Liste auf der Registerkarte **"Daten gesammelt** " der Anforderung aus.
- Wählen Sie im Elementvorschaubereich rechts neben der Liste die Schaltfläche " **Tags anwenden"** in der unteren Zeile aus. Sie können auch die drei Punkte rechts neben dem Elementnamen und die Option **"Tags anwenden** " auswählen.
- Ein Flyoutbereich wird mit der Liste der Tags angezeigt. Aktivieren Sie das Kontrollkästchen neben einem der Tags, die Sie auf das Element anwenden möchten. Wenn Sie das Kontrollkästchen deaktivieren, wird das Tag entfernt.
- Wenn Sie fertig sind, wählen Sie **Speichern** aus, wodurch Ihre Tagauswahl gespeichert und der Flyoutbereich geschlossen wird.

**So fügen Sie benutzerdefinierte Tags hinzu oder aktualisieren Tagbeschreibungen:**
- Wählen Sie auf der Seite "Antragstellerrechteanforderungen **" in** der oberen rechten Ecke des Bildschirms Einstellungen aus, um zu Ihren Priva-Einstellungen zu gelangen.
- Wechseln Sie zur Seite " **Datenüberprüfungstags** ", und wählen Sie das Tag aus, um eine Beschreibung und für die benutzerdefinierten Tags einen Namen einzugeben. Weitere Informationen zu [Tag-Einstellungen](priva-settings.md#data-review-tags).

**So exportieren Sie eine Liste der markierten Elemente:**
- Wechseln Sie zu der Seite **"Daten, die gesammelt werden** " in einer Anforderung zu Den Rechten des Betreffs.
- Wählen Sie oberhalb der Liste der Elemente das Nach-unten-Pfeilsymbol mit der Meldung **"Exportieren** " aus, wenn Sie darauf zeigen.
- Eine Excel Datei wird heruntergeladen, die die Eigenschaften für alle Elemente anzeigt, die von der Suche nach der Anforderung erfasst werden. Suchen Sie die Spalte **"Tags** ", um die Elemente nach Tag zu identifizieren und zu sortieren.

#### <a name="use-the-annotate-command-to-redact-text"></a>Verwenden des Befehls "Kommentieren" zum Bearbeiten von Text
Mit dem Befehl **"Kommentieren** " im Inhaltsprüfungsbereich können Sie Inlinemarkups erstellen und Daten innerhalb eines Inhaltselements bearbeiten. Wenn Sie beispielsweise eine Datei für eine Person einschließen müssen, die auch die persönlichen Informationen einer anderen betroffenen Person enthält, können Sie die **Bereichsrotaktion** unter der Schaltfläche "Zeichnen" in der Befehlsleiste verwenden, um alle Informationen zu schwarz zu machen, die sich nicht auf die Person beziehen, die den Antrag gestellt hat. Wenn Ihre Bearbeitungen abgeschlossen sind, wählen Sie **"Einschließen** " aus, um der Anforderung die bearbeitete Datei hinzuzufügen. Annotation erstellt eine Kopie der Datei, die in Ihrem Azure-Blob gespeichert ist. Die ursprüngliche Datei bleibt unverändert und wird an ihrem ursprünglichen Speicherort gespeichert.

#### <a name="enter-notes-about-a-file"></a>Eingeben von Notizen zu einer Datei
Um Notizen zu einem Element hinzuzufügen oder zu überprüfen, wählen Sie das Element aus der Zeile aus, und wechseln Sie zur Registerkarte **"Dateinotizen** " im Inhaltsprüfungsbereich auf der rechten Seite. Sie können auch die Option **"Dateinotiz hinzufügen** " verwenden, um einen neuen Kommentar zu erstellen. Wenn Sie Notizen auf gesamter Fallebene überprüfen oder hinzufügen möchten, wechseln Sie zur Hauptregisterkarte **"Notizen** " oben, und verwenden **Sie "Fallnotiz hinzufügen"**. Diese Hinweise sind für Benutzer sichtbar, die an der Anforderung arbeiten, werden jedoch nicht in den  Finalbericht aufgenommen oder anderweitig für die betroffene Person freigegeben.

#### <a name="complete-the-review"></a>Abschließen der Überprüfung

Wenn alle Elemente überprüft wurden und Sie ihren Status als **"Einschließen**", " **Ausschließen"** oder **"Keine Übereinstimmung** " festgelegt haben, ist es an der Zeit, den Prüfschritt zu schließen, indem Sie die Schaltfläche "  **Vollständige Rezension** " in der oberen rechten Ecke der Anforderung auswählen. Ein Flyoutbereich zeigt eine Zusammenfassung der Daten an und fügt alle zugehörigen Notizen hinzu. Diese Hinweise dienen der internen Datensatzführung und werden nicht für die betroffene Person freigegeben.

Wählen Sie im Flyoutbereich " **Rezension abschließen** " aus, um den Überprüfungsschritt abzuschließen. Zusammenfassungen Ihrer Entscheidungen werden später auf der Registerkarte " **Berichte** " bereitgestellt.

### <a name="collaborate-on-data-review"></a>Zusammenarbeit bei der Datenüberprüfung

Priva unterstützt die Zusammenarbeit über Microsoft Teams, damit Ihre Gruppe bei Anträgen auf Rechte von Antragstellern zusammenarbeiten kann. Wenn Sie eine neue Anforderung erstellen, wird automatisch ein Teams Kanal erstellt und ihrer Anforderung standardmäßig zugeordnet. Hier können Sie die Anforderung besprechen und Eingaben und Beiträge sicher teilen. Um an der Unterhaltung teilzunehmen, öffnen Sie Ihre Anforderung, und verwenden Sie die Option **"Mit Mitarbeitern chatten** ". Dies öffnet Microsoft Teams und platziert Sie im Kanal "Allgemein" für die Teamwebsite Ihrer Antragstellerrechte.

Um die Liste der aktiven Mitarbeiter zu überprüfen, die Ihre Teamwebsite anzeigen und dazu beitragen können, öffnen Sie in Ihrer Anfrage zu den Betreffrechten die Registerkarte **"Mitarbeiter** ". Um weitere Benutzer hinzuzufügen, die an dieser Anforderung zusammenarbeiten sollen, wählen Sie die Option zum **Hinzufügen eines Mitarbeiters** aus.

Um das Standardverhalten des Generierens von Teams Websites beim Erstellen einer Anforderung für Betreffrechte zu ändern, wechseln **Sie zu Einstellungen** in der oberen Navigationsleiste, und wählen Sie **Teams Zusammenarbeit** aus, um die Einstellung zu ändern.

Sie können auch die Option **"Freigeben"** in der oberen rechten Ecke innerhalb einer Anforderung für ein Betreffrecht verwenden, um Personen über Teams oder E-Mail einzugeben oder den Link auf die Seite in Priva zu kopieren. Mithilfe der Freigabe über Teams können Sie eine vorhandene Teams Website und einen Kanal auswählen, die für Ihr Konto verfügbar sind. Dort wird ein Link zu diesem Fall zusammen mit allen von Ihnen bereitgestellten Nachrichten bereitgestellt.

## <a name="step-4-close-the-request"></a>Schritt 4: Schließen der Anforderung

Wenn Sie alle erforderlichen Aktionen ausgeführt haben, um Ihre Anforderung zu Den Betreffrechten zu lösen, wählen Sie **"Anforderung schließen**" aus. Dadurch wird der Finalbericht erstellt, der auf der **Registerkarte "Berichte"** zu finden ist. Der Abschluss kann je nach Anzahl der Dateien in der Anforderung eine Weile dauern.

## <a name="next-steps"></a>Nächste Schritte
Weitere Informationen zum Arbeiten mit Berichten und zum Abschließen von Anträgen auf Antragstellerrechte finden Sie unter ["Erstellen von Berichten und Erfüllen einer Anforderung zu Betreffrechten"](subject-rights-requests-reports.md).

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
