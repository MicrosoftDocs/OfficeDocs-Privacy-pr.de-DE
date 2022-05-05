---
title: Überprüfen von Daten für eine Anfrage zu Rechten betroffener Personen
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
description: Erfahren Sie, wie Sie die von Microsoft Priva gesammelten Daten zu Anträgen betroffener Personen überprüfen und gemeinsam an der Durchführung der Anforderung arbeiten.
ms.openlocfilehash: 3a1211d391ee196ad431fe19ab9134386c9803a4
ms.sourcegitcommit: 6b88d22d0250cbb9a4ba1f71665f29cb67939851
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/05/2022
ms.locfileid: "65059759"
---
# <a name="review-data-for-a-subject-rights-request"></a>Überprüfen von Daten für eine Anfrage zu Rechten betroffener Personen

Nachdem Sie eine Anfrage zu Rechten [betroffener Personen (weitere Informationen](subject-rights-requests-create.md)) in Microsoft Priva erstellt haben, verwendet die Lösung für Anträge betroffener Personen Ihre Eingaben, um nach Übereinstimmungen zu Ihrer betroffenen Person in der Microsoft 365 Umgebung Ihrer Organisation zu suchen. Nachdem diese Daten kompiliert wurden, können Sie die Ergebnisse überprüfen, Auswahlmöglichkeiten treffen, was eingeschlossen werden soll, und Informationen nach Bedarf bearbeiten. Diese Schritte können von mehreren Benutzern über die Priva-Schnittstelle gemeinsam ausgeführt werden.

## <a name="step-1-review-request-details-and-monitor-progress"></a>Schritt 1: Überprüfen der Anforderungsdetails und Überwachen des Fortschritts

Um die ersten Ergebnisse Ihrer Suche anzuzeigen, wechseln Sie zum Priva-Bereich des [Microsoft Purview Compliance-Portals](https://compliance.microsoft.com/) , und öffnen Sie **Anfragen zu Rechten betroffener Personen**. Eine Liste aller offenen Anfragen zu Rechten betroffener Personen finden Sie auf dieser Hauptseite.

Wählen Sie Ihre Anforderung in der Liste aus, um die Anforderungsdetails anzuzeigen. Hier erfahren Sie mehr über die Eigenschaften der Anforderung, die Suchergebnisse und den Status der Anforderung. Diese Seite wird zu Ihrem Hub, um die gefundenen Dateien zu verwalten, Berichte und Exporte zu erstellen und zusammenzuarbeiten und die Anforderung abzuschließen.

Die Registerkarte " **Übersicht** " Auf der Seite "Anforderungsdetails" finden Sie Details zur Anforderung, eine Statusanzeige mit Ihrem aktuellen Schritt und wichtige Informationen zu den gefundenen Daten. Die Kacheln auf dieser Seite umfassen Folgendes:

##### <a name="details"></a>Details

Auf der **Karte "Details** " werden grundlegende Informationen angezeigt, um Sie an der Anforderung zu orientieren, z. B. der Stichtag, das Erstellungsdatum, die Beschreibung und die Datenschutzbestimmungen im Zusammenhang mit der Anforderung.

##### <a name="progress"></a>Status

Die **Statuskarte** listet jeden Schritt des Prozesses auf: Datenschätzung, Abrufen von Daten, Überprüfen von Daten, Generieren von Berichten und Schließen der Anforderung. Ein ausgefüllter blauer Kreis neben dem Schritt gibt den Schritt an, auf dem Sie sich gerade befinden. Ein Häkchen innerhalb des blauen Kreises bedeutet, dass der Schritt abgeschlossen ist, und der nicht gefüllte Kreis bedeutet, dass der Schritt noch nicht begonnen hat.

##### <a name="total-number-of-items-found"></a>Gesamtzahl der gefundenen Elemente

Statistiken zu Ihrer aktuellen Statusstufe. Auf dieser Kachel werden möglicherweise Informationen wie eine Datenschätzungszusammenfassung, die Anzahl der in Der Suche gefundenen Elemente und deren Speicherorte in Microsoft 365 oder der Status Ihrer Exporte angezeigt.

##### <a name="priority-items-to-review"></a>Zu überprüfenden Prioritätselemente

In der Kachel " **Prioritätselemente zum Überprüfen** " werden Elemente angezeigt, die Sie beim Starten der Überprüfung möglicherweise priorisieren möchten. Die Kachel zeigt eine Anzahl von Elementen an, die zu den folgenden Kategorien gehören:
- **Vertraulich**: Dies sind Elemente, auf die eine [Microsoft-Vertraulichkeitsbezeichnung](/microsoft-365/compliance/sensitivity-labels) angewendet wurde. Beispielsweise ein Word-Dokument mit der Bezeichnung "Streng vertraulich". 
- **Mehrpersonendaten**: Diese Elemente enthalten die personenbezogenen Daten von mehr als einer Person. Wenn Sie diese Elemente als Teil des endgültigen Datenpakets einschließen möchten, müssen Sie die irrelevanten Daten in den Dateien bearbeiten. Weitere Informationen finden Sie weiter unten in [Schritt 3: Überprüfen von Daten](#step-3-review-data) . Beachten Sie, dass Ihre Organisation [Datenabgleich für Anträge](subject-rights-requests-data-match.md) betroffener Personen einrichten muss, damit Priva Elemente mit Mehrpersonendaten identifizieren kann.

**So suchen Sie Ihre Prioritätselemente:**

Stellen Sie zunächst sicher, dass Sie ihre Ansicht dieser Elemente in Ihrer Tabelle mit **den gesammelten Daten** aktiviert haben, indem Sie die folgenden Schritte ausführen:

- Wählen Sie auf der Registerkarte **"Gesammelte Daten** " oben in der Liste der Elemente die **Option "Spalten anpassen** " aus.
- **Platzieren Sie** im Flyoutbereich "Spalten bearbeiten" eine Überprüfung neben "**Prioritätstypen"**.
- Wählen Sie **Anwenden** aus. Ihre Liste der Elemente enthält jetzt eine Spalte " **Prioritätstypen** ".

Jetzt können Sie die Prioritätselemente identifizieren und finden, indem Sie die Spalte " **Prioritätstyp** " sortieren, um ähnliche Typen zu gruppieren.

### <a name="understand-progress-stages"></a>Grundlegendes zu Statusstufen

Anträge betroffener Personen durchlaufen mehrere Stufen. Einige Zustände werden automatisch ausgeführt, und andere Stufen werden weiter ausgeführt, wenn Administratoren und Mitwirkende von Rechten betroffener Personen wichtige Schritte wie das Überprüfen von Dateien ausführen.

Da Anforderungen möglicherweise im Laufe der Zeit oder von mehreren Mitwirkenden bearbeitet werden müssen, gibt Priva fortlaufende Aktualisierungen über den Status und Anleitungen zu den nächsten Schritten. Diese Updates können auf der Registerkarte " **Übersicht** " auf der Detailseite einer Anfrage zu Rechten betroffener Personen angezeigt werden.

#### <a name="data-estimate"></a>Datenschätzung
Nachdem Sie eine Anforderung erstellt haben, beginnt Priva sofort, nach potenziellen Übereinstimmungen mit der betroffenen Person in Ihrer Microsoft 365 Umgebung zu suchen. Nachdem wir alle Elemente identifiziert haben, die ihrer Meinung nach Ihren Kriterien entsprechen, wird die Schätzung auf der **Zusammenfassungskarte "Datenschätzung** " auf der **Seite "Übersicht** " der Anforderung angezeigt. Die Menge der Daten innerhalb des Umfangs Ihrer Suche wirkt sich auf die Dauer aus, die zum Abschließen der Schätzung dauert.

Ihre Anforderung wird automatisch in die nächste Phase des Datenabrufs verschoben, in der alle Inhaltselemente gesammelt werden, damit die Projektbeteiligten an der Datenüberprüfung zusammenarbeiten können. In einigen Fällen unterbrechen wir die Datenschätzung, bevor wir zum Abruf übergehen, und benachrichtigen Sie über die nächsten Schritte, die Sie ausführen müssen, bevor Sie fortfahren.

Sie können auch auswählen, dass die Datenschätzung automatisch angehalten wird, wenn Sie zum ersten Mal eine Anfrage zu Rechten betroffener Personen erstellen. Wählen Sie während des Erstellungsprozesses während des Sucheinstellungsschritts die Option " **Erste Schätzung** **abrufen"** aus. Überprüfen Sie Details zum [Schritt "Sucheinstellungen"](subject-rights-requests-create.md#define-search-settings).

#### <a name="pause-in-data-estimate-for-large-search-results"></a>Anhalten der Datenschätzung für große Suchergebnisse

Priva wird feststellen, ob Ihre Datenschätzung voraussichtlich eine große Anzahl von zu überprüfenden Elementen zurückgibt (über 10K-Elemente). Die Schätzung wird angehalten, sodass Sie eine Vorschau der Ergebnisse anzeigen und entscheiden können, ob [Sie Ihre Suchabfrage für](subject-rights-requests-create.md#refine-your-search) spezifischere Speicherorte oder Bedingungen bearbeiten oder die identifizierten Elemente weiterhin abrufen möchten.The estimate will pause so that you can can preview the results and decide whether to edit your search query to target more specific locations or conditions, or continue to retrieve the identified items.  Wir zeigen Ihnen auf dem Bildschirm die Anzahl der Elemente und das Datenvolumen, die Ihrer Suche entsprechen. Sie haben eine oder beide der folgenden Optionen in einer Meldungsleiste am oberen Rand des Bildschirms:

- Eine Schaltfläche " **Suchabfrage bearbeiten** " führt Sie direkt in die Sucheinstellungen der Anforderung, um strengere Parameter festzulegen und eine neue Schätzung zu generieren.
- Solange Ihre Suchabfrage nicht mehr als 300K-Elemente umfasst, wird auch eine Option zum **Abrufen von Daten angezeigt**. Auf diese Weise können Sie auswählen, dass Sie Ihre Suche nicht bearbeiten und die Daten weiterhin sammeln möchten.

#### <a name="retrieve-data"></a>Abrufen von Daten
Die Datenempfangsphase ist, wenn alle Dateien, E-Mails, Chats, Bilder und anderen Inhaltselemente, die die personenbezogenen Daten der betroffenen Person enthalten, abgerufen und zur Überprüfung in einem Azure-BLOB-Speichercontainer zusammengestellt werden. Der Datenabruf kann je nach Datenvolumen einige Minuten oder erheblich länger dauern. Wenn diese Phase abgeschlossen ist, wird die Anforderung automatisch zur nächsten Phase der **Überprüfungsdaten** verschoben.

#### <a name="review-data"></a>Überprüfen von Daten
 In dieser Phase sollten Ihre Mitwirkenden die Ergebnisse auf der Registerkarte **"Gesammelte Daten** " überprüfen und alle anwendbaren Aufgaben ausführen, z. B. Wiederholen, Anwenden von Tags und Hinzufügen von Notizen. Wenn Sie mit der Überprüfung fertig sind, wählen Sie " **Überprüfung abschließen**" aus.

#### <a name="generate-reports"></a>Generieren von Berichten
Ihre Berichte werden in dieser Phase generiert. Wenn sie fertig sind, finden Sie diese unter der Registerkarte " **Berichte** ". Ihre fertigen Dateien können zur endgültigen Überprüfung und Übermittlung an die betroffene Person exportiert werden, die die Anforderung gestellt hat.

#### <a name="close-the-request"></a>Schließen der Anforderung
Eine geschlossene Anforderung weist darauf hin, dass alle Arbeiten abgeschlossen wurden, um diese Anforderung zu erfüllen. Alle gesammelten Daten und Berichte werden gemäß Ihren [Datenaufbewahrungseinstellungen](priva-settings.md#data-retention-periods) aufbewahrt.

## <a name="step-2-optional-view-and-edit-search-queries"></a>Schritt 2 (optional): Anzeigen und Bearbeiten von Suchabfragen

Wenn Sie detaillierte Informationen zur Datensuche hinter einer Anfrage zu Rechten betroffener Personen anzeigen möchten, wählen Sie " **Suchabfragedetails anzeigen"** aus. Dadurch wird ein Bereich geöffnet, in dem die Abfrage zusammengefasst und weitere Details zu den gefundenen Informationen angezeigt werden.

Sie haben hier die Möglichkeit, eine **Vorschau der Suchergebnisse** anzuzeigen, um zu sehen, welcher Inhaltstyp für diese Abfrage zurückgegeben wird. Wenn Sie die Eigenschaften dieser Suche ändern möchten und noch nicht mit der Phase "Daten abrufen" begonnen haben, können Sie die **Suchabfrageoption bearbeiten** verwenden.

Mithilfe des prozesses zum Bearbeiten von Suchabfragen können Sie Eigenschaften für die Identifizierung der betroffenen Person, Ihre Suchfilter und -bedingungen sowie die Speicherorte ändern oder hinzufügen, an denen nach Daten gesucht werden soll (einschließlich Exchange, SharePoint, OneDrive und/oder Teams). Verwenden Sie diese Optionen, um die gewünschte Spezifität zu erreichen. Sie können die endgültige Version Ihrer neuen Abfrage überprüfen, bevor Sie " **Speichern" drücken**.

Wenn Sie die Bearbeitung ihrer Suchabfrage abgeschlossen haben, wird eine neue Suche ausgeführt, um Ihre vorherigen Suchergebnisse zu ersetzen. Dadurch wird Ihr Status im Abschnitt **"Fortschritt** " auf den ersten Schritt, " **Datenschätzung"**, zurückgesetzt. Der Abschluss der neuen Suche kann bis zu 60 Minuten dauern. Sobald dies abgeschlossen ist, werden aktualisierte Ergebnisse auf der Detailseite der Anforderung angezeigt.

## <a name="step-3-review-data"></a>Schritt 3: Überprüfen von Daten

In dieser Phase sollten Ihre Mitwirkenden die Ergebnisse auf der Registerkarte **"Gesammelte Daten**" überprüfen. Ein Teams Kanal wird automatisch eingerichtet, um die Inhaltsüberprüfung durch alle Beteiligten zu erleichtern. Weitere Details finden [Sie unter "Zusammenarbeit an Der Datenüberprüfung"](#collaborate-on-data-review) . Die wesentlichen Aufgaben für den Datenüberprüfungsschritt sind unten beschrieben.

#### <a name="mark-items-as-include-or-exclude-and-add-notes"></a>Markieren von Elementen als "Einschließen" oder "Ausschließen" und Hinzufügen von Notizen

Überprüfen Sie die Liste der von Ihrer Suche zurückgegebenen identifizierten Elemente. Wenn Sie beschließen, dass das Element als Teil des Abschlussberichts wieder an die betroffene Person einbezogen werden soll, wählen Sie oben in der Liste der Elemente auf der Befehlsleiste " **Einschließen"** aus. Sie können auch die blaue Schaltfläche **"Einschließen"** im Bereich "Inhaltsüberprüfung" rechts neben der Liste der Elemente auswählen. Wenn Sie **"Einschließen"** auswählen, wird ein Flyoutbereich mit einer Option zum Hinzufügen von Notizen angezeigt. Wenn Sie fertig sind, wählen Sie **"Absenden** " aus, um den Überprüfungsstatus des Elements als **"Einschließen**" zu speichern.

Wenn das Element nicht teil der Anforderung ist, wählen Sie " **Ausschließen** " auf der Befehlsleiste oder die Schaltfläche **"Ausschließen** " im Inhaltsprüfungsbereich aus. Das Ausschließen eines Elements bedeutet, dass es nicht in den [Abschlussberichten enthalten ist, die für die betroffene Person generiert werden](subject-rights-requests-reports.md).

> [!NOTE]
> Wenn Sie ein Element als **"Ausschließen**" markieren, müssen Sie eine Notiz als Begründung dafür hinzufügen, warum es sich nicht auf die Anforderung von Rechten betroffener Personen bezieht. Notizen dienen internen Zwecken und sind nicht in Abschlussberichten enthalten.

Wenn der Inhalt als falsch positiv angezeigt wird, wählen Sie **"Keine Übereinstimmung** " aus, und wählen Sie im Flyoutbereich " **Bestätigen**" aus. Diese Aktion schließt die Datei aus Ihren Abschlussberichten aus und kennzeichnet das Element als etwas, das bei der Suche nicht erkannt werden sollte.

#### <a name="apply-tags"></a>Apply tags

Kategorien können verwendet werden, um Elemente zu identifizieren, die weitere Aufmerksamkeit erfordern. Priva bietet drei Standardtags – **Follow-up**, **Delete** und **Update** –, für die Sie eine Beschreibung festlegen können. Priva bietet auch zwei benutzerdefinierte Tags, die Sie benennen und beschreiben können.

Wenn Sie z. B. während der Datenüberprüfung feststellen, dass ein Inhaltselement nicht von Ihrer Organisation aufbewahrt werden muss, können Sie das **Löschtag** anwenden und dann eine Liste aller markierten Dateien exportieren, sodass Sie zurückkehren und die identifizierten Elemente löschen können, wenn Sie mit der Anforderung fertig sind.

Die fünf Tags, die Sie in **Einstellungen** verwalten, gelten für alle Ihre Anfragen zu Rechten betroffener Personen.

**So fügen Sie Tags hinzu oder entfernen sie:**

- Wählen Sie das Element aus der Liste auf der Registerkarte " **Gesammelte Daten** " der Anforderung aus.
- Wählen Sie im Bereich "Elementvorschau" rechts neben der Liste in der unteren Zeile die Schaltfläche " **Tags anwenden** " aus. Sie können auch die drei Punkte rechts neben dem Elementnamen und die Option " **Tags übernehmen"** auswählen.
- Ein Flyoutbereich wird mit der Liste der Tags angezeigt. Aktivieren Sie das Kontrollkästchen neben einem der Tags, die Sie auf das Element anwenden möchten. Wenn Sie das Aktivieren eines aktivierten Kontrollkästchens aufheben, wird das Tag entfernt.
- Wenn Sie fertig sind, wählen Sie **"Speichern"** aus, wodurch ihre Markierungen gespeichert und der Flyoutbereich geschlossen wird.

**So fügen Sie benutzerdefinierte Tags hinzu oder aktualisieren Tagbeschreibungen:**
- Wählen Sie auf der Seite "Anträge betroffener Personen" **Einstellungen** in der oberen rechten Ecke des Bildschirms aus, um zu Ihren Priva-Einstellungen zu gelangen.
- Wechseln Sie zur Seite " **Datenüberprüfungstags** ", und wählen Sie das Tag aus, um eine Beschreibung und für die benutzerdefinierten Tags einen Namen einzugeben. Erfahren Sie mehr über [Tageinstellungen](priva-settings.md#data-review-tags).

**So exportieren Sie eine Liste mit markierten Elementen:**
- Wechseln Sie in einer Anfrage zu Rechten betroffener Personen zur Seite **"Gesammelte Daten** ".
- Wählen Sie oberhalb der Liste der Elemente das Nach-unten-Symbol mit der Meldung **"Exportieren** " aus, wenn Sie mit dem Mauszeiger darauf zeigen.
- Eine Excel Datei wird heruntergeladen, die die Eigenschaften für alle Elemente anzeigt, die bei der Suche nach der Anforderung gesammelt wurden. Suchen Sie die Spalte **"Kategorien** ", um die Elemente nach Tag zu identifizieren und zu sortieren.

#### <a name="use-the-annotate-command-to-redact-text"></a>Verwenden des Befehls "Anmerkungen" zum Bearbeiten von Text
Mit dem Befehl **"Anmerkungen** " im Inhaltsprüfungsbereich können Sie Inlinemarkups erstellen und Daten innerhalb eines Inhaltselements bearbeiten. Wenn Sie z. B. eine Datei für eine Person einschließen müssen, die auch die persönlichen Informationen einer anderen betroffenen Person enthält, können Sie unter der Schaltfläche "Zeichnen" in der Befehlsleiste die **Bearbeitung des Bereichs** verwenden, um alle Informationen auszublenden, die sich nicht auf die Person beziehen, die die Anforderung gestellt hat. Wenn Ihre Bearbeitungen abgeschlossen sind, wählen Sie **"Einschließen** " aus, um der Anforderung die bearbeitete Datei hinzuzufügen. Mit der Anmerkung wird eine Kopie der Datei erstellt, die in Ihrem Azure-Blob gespeichert ist. Die Originaldatei bleibt unverändert und wird an ihrem ursprünglichen Speicherort gespeichert.

#### <a name="enter-notes-about-a-file"></a>Eingeben von Notizen zu einer Datei
Um Notizen zu einem Element hinzuzufügen oder zu überprüfen, wählen Sie das Element aus seiner Zeile aus, und wechseln Sie zur Registerkarte **"Dateinotizen** " im Bereich "Inhaltsüberprüfung" rechts. Sie können auch die Option **"Dateinotiz hinzufügen** " verwenden, um einen neuen Kommentar zu erstellen. Wenn Sie Notizen auf gesamter Fallebene überprüfen oder hinzufügen möchten, wechseln Sie zur Hauptregisterkarte " **Notizen** " oben, und verwenden **Sie "Fallnotiz hinzufügen**". Diese Notizen sind für Benutzer sichtbar, die an der Anforderung arbeiten, werden jedoch nicht in den Abschlussbericht aufgenommen oder anderweitig an die betroffene Person weitergegeben.

#### <a name="complete-the-review"></a>Abschließen der Überprüfung

Wenn alle Elemente überprüft wurden und Sie deren Status als **"Einschließen**", " **Ausschließen**" oder " **Keine Übereinstimmung** " festgelegt haben, ist es an der Zeit, den Überprüfungsschritt zu schließen, indem Sie in der oberen rechten Ecke der Anforderung die Schaltfläche "  **Überprüfung abschließen** " auswählen. Ein Flyoutbereich zeigt eine Zusammenfassung der Daten an und fügt alle zugehörigen Notizen hinzu. Diese Notizen dienen der internen Aufzeichnung und werden nicht für die betroffene Person freigegeben.

Wählen Sie im Flyoutbereich " **Vollständige Überprüfung** " aus, um den Überprüfungsschritt abzuschließen. Zusammenfassungen Ihrer Entscheidungen werden später auf der Registerkarte " **Berichte** " angezeigt.

### <a name="collaborate-on-data-review"></a>Zusammenarbeiten bei der Datenüberprüfung

Priva unterstützt die Zusammenarbeit durch Microsoft Teams, damit Ihre Gruppe an Themenrechtsanfragen zusammenarbeiten kann. Wenn Sie eine neue Anforderung erstellen, wird automatisch ein Teams Kanal erstellt und ihrer Anforderung standardmäßig zugeordnet. Hier können Sie die Anfrage besprechen und Eingaben und Beiträge sicher teilen. Um an der Unterhaltung teilzunehmen, öffnen Sie Ihre Anfrage, und verwenden Sie die Option **"Mit Mitarbeitern chatten** ". Dadurch öffnen Sie Microsoft Teams und platzieren Sie im Kanal "Allgemein" für die Teamwebsite Ihrer Anfrage zu Rechten betroffener Personen.

Wenn Sie die Liste der aktiven Mitarbeiter überprüfen möchten, die Ihre Teamwebsite anzeigen und dazu beitragen können, öffnen Sie in Ihrer Anforderung für Die Rechte betroffener Personen die Registerkarte **"Mitarbeiter** ". Um weitere Benutzer für die Zusammenarbeit an dieser Anforderung hinzuzufügen, wählen Sie die Option zum **Hinzufügen eines Mitarbeiters** aus.

Um das Standardverhalten beim Generieren von Teams Websites beim Erstellen einer Anforderung für Rechte betroffener Personen zu ändern, wechseln Sie zu **Einstellungen** im oberen Navigationsbereich, und wählen Sie **Teams Zusammenarbeit** aus, um die Einstellung zu ändern.

Sie können auch die Option **"Freigeben"** oben rechts in einer Betreff-Rechts-Anforderung verwenden, um Personen per Teams oder E-Mail einzuschleifen oder den Link zu der Seite in Priva zu kopieren. Mithilfe der Freigabe über Teams können Sie eine vorhandene Teams Website und einen Kanal auswählen, die für Ihr Konto verfügbar sind. Dort wird zusammen mit einer von Ihnen bereitgestellten Nachricht ein Link zu diesem Fall bereitgestellt.

## <a name="step-4-close-the-request"></a>Schritt 4: Schließen der Anforderung

Wenn Sie alle erforderlichen Aktionen ausgeführt haben, um ihre Anfrage zu den Rechten betroffener Personen aufzulösen, wählen Sie **"Anfrage schließen**" aus. Dadurch wird der Abschlussbericht erstellt, der auf der **Registerkarte "Berichte"** zu finden ist. Der Abschluss kann je nach Anzahl der Dateien in der Anforderung eine Weile dauern.

## <a name="next-steps"></a>Nächste Schritte
Weitere Informationen zum Arbeiten mit Berichten und zum Abschließen von Anfragen zu Rechten betroffener Personen finden [Sie unter Generieren von Berichten und Erfüllen einer Anfrage zu Rechten betroffener Personen](subject-rights-requests-reports.md).

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
