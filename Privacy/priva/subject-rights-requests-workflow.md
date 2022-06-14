---
title: Workflow für Anfragen zu Rechten betroffener Personen
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
description: Grundlegendes zur Seite "Workflowschritte und Anforderungsdetails" in Microsoft Priva Anfragen zu Betroffenenrechten.
ms.openlocfilehash: 794176260f6377862d34a66dc71cef1e811188b9
ms.sourcegitcommit: fe651dab4c89e67b21d37531c04e3996b7af1138
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/14/2022
ms.locfileid: "66060087"
---
# <a name="understand-the-workflow-and-request-details-pages"></a>Grundlegendes zu Den Workflow- und Anforderungsdetailseiten

**In diesem Artikel**: Erfahren Sie mehr über die Fortschrittsschritte, während Sie eine Anforderung erstellen und bearbeiten. Erfahren Sie, wie Sie mit den Erkenntnissen und Features auf der Detailseite jeder Anforderung arbeiten.

Wenn Sie [eine Anforderung](subject-rights-requests-create.md) in der Lösung für Anträge betroffener Personen erstellen, werden die von Ihnen bereitgestellten Informationen verwendet, um nach Übereinstimmungen zu Ihrer betroffenen Person in der Microsoft 365 Umgebung Ihrer Organisation zu suchen. Übereinstimmenden Elementen werden eingehalten, damit Sie dies überprüfen, Auswahlmöglichkeiten treffen und Informationen nach Bedarf bearbeiten können. Mehrere Benutzer können an diesen Schritten innerhalb der Benutzeroberfläche für Anträge betroffener Personen zusammenarbeiten. Auf der Seite ["Übersicht](#overview-tab) " der Anforderung finden Sie Status zu den Statusstufen und Anleitungen zu den nächsten Schritten.

## <a name="progress-stages-for-requests"></a>Statusstufen für Anforderungen

Jede Anforderung durchläuft mehrere Phasen. Einige Stufen werden automatisch ausgeführt, und andere Stufen werden nach Abschluss bestimmter Schritte wie dem Überprüfen von Dateien manuell erweitert.

- **Datenschätzung**: Vor dem Abrufen der Daten schätzt Priva die Datenmenge, die sie finden wird. Je nach Datenmenge kann die Anforderung automatisch in die nächste Phase des Datenabrufs verschoben werden oder nicht. Sie können eine Anforderung festlegen, in der Schätzungsphase anzuhalten, bevor Sie Daten sammeln. weitere Informationen finden Sie unter [Datenschätzung und -abruf](subject-rights-requests-data-retrieval.md).

- **Abrufen von Daten**: Alle Dateien, E-Mails, Chats, Bilder und anderen Inhaltselemente werden zusammengezogen. Wenn diese Phase abgeschlossen ist, wird die Anforderung automatisch zur nächsten Phase der Überprüfung von Daten verschoben. Weitere Informationen finden Sie unter [Datenschätzung und -abruf](subject-rights-requests-data-retrieval.md).

- **Überprüfen von Daten**: Mitarbeiter überprüfen alle gesammelten Daten, entscheiden, welche daten zu der Anforderung gehören, und führen Aufgaben wie das Bearbeiten von Dateien und das Hinzufügen von Fallnotizen aus. Erfahren Sie mehr über [das Überprüfen von Daten für eine Anfrage zu Rechten](subject-rights-requests-data-review.md) betroffener Personen. Nach abschluss der Datenüberprüfung wechseln Sie manuell zur nächsten Phase, um Berichte zu generieren.

- **Berichte generieren**: Wenn die Datenüberprüfung abgeschlossen ist, geht ein Benutzer manuell zu diesem Schritt über. Priva generiert die Abschlussberichte, die das für die betroffene Person freizugebenden Datenpaket sowie interne Berichte für die Datensätze Ihrer Organisation enthalten. Erfahren Sie mehr über das [Generieren von Berichten](subject-rights-requests-reports.md).

- **Schließen Sie die Anforderung**: Wenn alle Arbeiten abgeschlossen sind, schließen Sie die Anforderung, um anzugeben, dass sie als abgeschlossen betrachtet wird. Erfahren Sie mehr über das [Generieren von Berichten](subject-rights-requests-reports.md) , damit Sie die Anforderung erfüllen und schließen können.

## <a name="understanding-the-request-details-page"></a>Grundlegendes zur Seite "Anforderungsdetails"

Wählen Sie im linken Navigationsbereich des Microsoft Purview Compliance-Portals **Priva Anfragen zu Betroffenenrechten** aus, um auf die von Ihrer Organisation erstellten Anforderungen zuzugreifen und deren Status anzuzeigen. Die Statuskarten auf der Hauptseite "Anfragen zu Rechten betroffener Personen", die unten angezeigt werden, zeigen die Anzahl der aktiven, geschlossenen und überfälligen Anforderungen sowie die wichtigsten Anforderungstypen an. In der Tabelle unter den Statuskarten sind alle von Ihrer Organisation erstellten Anforderungen aufgeführt, wobei die zuletzt erstellte Anforderung oben aufgeführt ist.

**Hauptseite für Anfragen zu Rechten betroffener Personen:** 
![ Hauptseite für Anfragen zu Rechten betroffener Personen.](../media/priva-srr-overview.png)

Um die Detailseite einer Anforderung zu öffnen, wählen Sie den Anforderungsnamen aus der Tabelle aus. Hier erfahren Sie mehr über die Eigenschaften der Anforderung, die Suchergebnisse und den Status der Anforderung. Die unten angezeigte Detailseite wird zu Ihrem Hub, um die gefundenen Dateien zu verwalten, Berichte und Exporte zu erstellen und die Anforderung abzuschließen.

**Eine Anforderungsdetailseite:**
![ Seite "Details zur Anforderung von Rechten betroffener Personen".](../media/priva-srr-detailspage.png)

### <a name="overview-tab"></a>Registerkarte „Übersicht“

Die Registerkarte " **Übersicht** " auf der Seite "Anforderungsdetails" enthält Details zur Anforderung, eine Statusanzeige mit Ihrem aktuellen Schritt und wichtige Informationen zu den gefundenen Daten. Diese Seite enthält einzelne Statuskarten, die unten erläutert werden.

##### <a name="details"></a>Details

Auf der Karte " **Details** " werden grundlegende Informationen angezeigt, um Sie an der Anforderung zu orientieren, z. B. dem Stichtag, dem Erstellungsdatum, der Beschreibung und der zugehörigen Datenschutzbestimmungen.

##### <a name="progress"></a>Status

Die **Statuskarte** listet jeden Schritt des Prozesses auf: Datenschätzung, Abrufen von Daten, Überprüfen von Daten, Generieren von Berichten und Schließen der Anforderung. Ein ausgefüllter blauer Kreis neben dem Schritt gibt den Schritt an, auf dem Sie sich gerade befinden. Ein Häkchen innerhalb des blauen Kreises bedeutet, dass der Schritt abgeschlossen ist. Ein leerer Kreis bedeutet, dass der Schritt noch nicht begonnen hat.

##### <a name="data-estimate-summary"></a>Datenschätzungszusammenfassung

Die **Zusammenfassungskarte "Datenschätzung** " wird angezeigt, wenn die Anforderung in der [Datenschätzungsphase](subject-rights-requests-data-retrieval.md#data-estimate) angehalten wird. Es zeigt den Speicherort und die Anzahl der Elemente an, die ihre Suche voraussichtlich abrufen wird.

##### <a name="total-number-of-items-found"></a>Gesamtzahl der gefundenen Elemente

Die **Karte "Gesamtzahl der gefundenen Elemente**" zeigt die Anzahl der gefundenen Inhaltselemente und deren Speicherorte in Microsoft 365 an.

##### <a name="priority-items-to-review"></a>Zu überprüfenden Prioritätselemente

In der Kachel " **Prioritätselemente zum Überprüfen** " werden Elemente angezeigt, die Sie beim Starten der Überprüfung möglicherweise priorisieren möchten. Die Kachel zeigt eine Anzahl von Elementen an, die zu den folgenden Kategorien gehören:
- **Vertraulich**: Auf diese Elemente wurde eine [Microsoft-Vertraulichkeitsbezeichnung](/microsoft-365/compliance/sensitivity-labels) angewendet. Beispielsweise ein Word-Dokument mit der Bezeichnung "Streng vertraulich". 
- **Mehrpersonendaten**: Diese Elemente enthalten die personenbezogenen Daten von mehr als einer Person. Wenn Sie diese Elemente als Teil des endgültigen Datenpakets einschließen möchten, müssen Sie die irrelevanten Daten in den Dateien bearbeiten. Erhalten Sie [Details zum Überprüfen von Daten](subject-rights-requests-data-review.md). Damit Priva Elemente mit Mehrpersonendaten identifizieren können, muss Ihre Organisation [den Datenabgleich für Anträge](subject-rights-requests-data-match.md) betroffener Personen einrichten.

**So suchen Sie Ihre Prioritätselemente:**

Stellen Sie zunächst sicher, dass Sie ihre Ansicht dieser Elemente in Ihrer Tabelle mit **den gesammelten Daten** aktiviert haben, indem Sie die folgenden Schritte ausführen:

- Wählen Sie auf der Registerkarte **"Gesammelte Daten** " oben in der Liste der Elemente die **Option "Spalten anpassen** " aus.
- **Platzieren Sie** im Flyoutbereich "Spalten bearbeiten" eine Überprüfung neben "**Prioritätstypen"**.
- Wählen Sie **Anwenden** aus. Ihre Liste der Elemente enthält jetzt eine Spalte " **Prioritätstypen** ".

Jetzt können Sie die Prioritätselemente identifizieren und finden, indem Sie die Spalte " **Prioritätstyp** " sortieren, um ähnliche Typen zu gruppieren.

### <a name="data-collected-tab"></a>Registerkarte "Gesammelte Daten"

Wenn alle Elemente, die Ihren Sucheinstellungen entsprechen, identifiziert wurden, werden sie gesammelt und auf der Registerkarte " **Gesammelte Daten** " angezeigt. Neben der Liste der Elemente befindet sich ein Vorschaubildschirm zum Überprüfen jedes Elements, zum Ausführen von Bearbeitungen und zum Markieren von Elementen als ein- oder ausgeschlossen als Teil der Anforderung. Erfahren Sie mehr über den [Schritt zur Datenüberprüfung und -zusammenarbeit](subject-rights-requests-data-review.md).

### <a name="notes-tab"></a>Registerkarte "Notizen"

Auf der Registerkarte **"Notizen"** können Mitarbeiter Notizen über die arbeit an der Anforderung eingeben. Diese Notizen sind für alle Personen sichtbar, die an der Anforderung arbeiten, werden jedoch nicht in den Abschlussbericht aufgenommen oder anderweitig an die betroffene Person weitergegeben.

### <a name="collaborators-tab"></a>Registerkarte "Mitarbeiter"

Auf der Registerkarte "Mitarbeiter" werden alle Benutzer angezeigt, die zur Zusammenarbeit an den gesammelten Daten eingeladen wurden, sowie alle zugehörigen Teams Kanals für die Anforderung. Der Ersteller der Anforderung wird automatisch als Mitarbeiter aufgelistet. Laden Sie neue Mitarbeiter ein, indem Sie den Befehl " **Mitarbeiter hinzufügen"** auswählen und den Namen eines Benutzers eingeben, um sie aus einer Liste auszuwählen. Weitere Details zur [Zusammenarbeit für die Datenüberprüfung](subject-rights-requests-data-review.md#collaboration-for-data-review)

### <a name="reports-tab"></a>Registerkarte "Berichte"

Auf der Registerkarte " **Berichte** " werden alle Berichte angezeigt, die automatisch generiert werden, wenn Sie zur Phase **"Berichte generieren"** wechseln. Berichte sind in zwei Kategorien unterteilt: Berichte, die Sie für die betroffene Person freigeben können, und Berichte, die für die interne Verwendung In Ihrer Organisation vorgesehen sind. Erhalten Sie Details zum [Arbeiten mit Berichten](subject-rights-requests-reports.md).

### <a name="history-tab"></a>Registerkarte "Verlauf"

Auf der Registerkarte " **Verlauf** " werden Ereignisse der obersten Ebene für die Anforderung zusammengefasst, einschließlich Statusstufenänderungen und Aggregaten für die Anzahl der enthaltenen, ausgeschlossenen und bearbeiteten Elemente.

## <a name="next-steps"></a>Nächste Schritte

Besuchen [Sie "Erstellen einer Anfrage zu Themenrechten](subject-rights-requests-create.md) ", um zu erfahren, wie Sie mit Ihrer ersten Anfrage angegeben werden.

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)