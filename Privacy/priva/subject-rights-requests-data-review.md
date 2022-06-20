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
description: Erfahren Sie, wie Sie die von Microsoft Priva gesammelten Daten zu Anträgen betroffener Personen überprüfen und an der Durchführung der Anforderung zusammenarbeiten.
ms.openlocfilehash: 6120fdaa97cf79ac122f6992f9ce476fdc4c5da3
ms.sourcegitcommit: 8cbafebb1a1b26a0bd92e500a1e6d6c60243c64b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/20/2022
ms.locfileid: "66166644"
---
# <a name="review-data-for-a-subject-rights-request"></a>Überprüfen von Daten für eine Anfrage zu Rechten betroffener Personen

**In diesem Artikel**: Erfahren Sie, wie Sie die für eine Anforderung von Rechten betroffener Personen gesammelten Daten mithilfe von Bearbeitungstools, Dateitags, überprüfen. Grundlegendes zur Verwendung von Funktionen für die Zusammenarbeit, die einen dedizierten Teams-Kanal umfasst.

Nachdem Daten für eine Anfrage zu Rechten betroffener Personen gesammelt wurden, besteht die nächste Stufe darin, die Inhaltselemente zu überprüfen, zu entscheiden, welche Elemente als Teil der Anforderung eingeschlossen oder ausgeschlossen werden sollen, und informationen ggf. zu bearbeiten.

## <a name="tasks-for-completing-the-data-review"></a>Aufgaben zum Abschließen der Datenüberprüfung

In der **Phase "Daten überprüfen"** untersuchen Mitarbeiter die Inhaltselemente auf der Registerkarte **"Gesammelte Daten**". Ein Teams Kanal wird automatisch eingerichtet, um die Inhaltsüberprüfung durch alle Beteiligten zu erleichtern. Weitere Details finden Sie weiter unten unter ["Zusammenarbeit zur Datenüberprüfung](#collaboration-for-data-review) ". Die wesentlichen Aufgaben für den Datenüberprüfungsschritt sind unten beschrieben.

#### <a name="import-additional-files"></a>Importieren zusätzlicher Dateien

Möglicherweise möchten Sie zusätzliche Inhaltselemente in die Anforderung für Ihre Datenüberprüfung einbeziehen. Beispielsweise Dateien, die außerhalb der Microsoft 365 Umgebung Ihrer Organisation gespeichert sind, oder andere Elemente, die Ihrer Meinung nach relevant sind, aber nicht in die Suche eingegrenzt wurden. Sie können Dateien zusammen mit den anderen Elementen in die Registerkarte " **Gesammelte Daten** " einer einzelnen Anforderung importieren, die überprüft und bearbeitet werden soll. Importierte Dateien werden demselben Azure Blob Storage Container mit den anderen Inhaltselementen hinzugefügt, die aus Ihrer Suche abgerufen wurden.

Führen Sie die folgenden Schritte aus, um Dateien zu importieren:

1. Wählen Sie auf der Seite "Anforderungsdetails" in der Befehlsleiste oben auf der Seite " **Dateien importieren** " aus.

2.  Auf dem Bildschirm wird ein Feld " **Dateien importieren** " angezeigt. Wählen **Sie "Dateien auswählen**" aus, und wählen Sie in Ihrer Datei-Explorer-Ansicht eine oder mehrere zu importierenden Dateien aus.

3. Sie gelangen zurück zum Feld " **Dateien importieren** ", in dem die ausgewählten Dateien aufgelistet werden. Sie können **"Dateien** auswählen" erneut auswählen, um der Liste weitere Elemente hinzuzufügen. Wenn Sie eine der Dateien entfernen möchten, wählen Sie **"Löschen"** aus, wodurch alle Dateien entfernt werden, und wählen Sie die Dateien erneut aus.

4. Wenn alle gewünschten Dateien im Feld **"Dateien importieren** " aufgelistet sind, wählen Sie **"Importieren**" aus. Um den Vorgang ohne Hochladen zu beenden, wählen Sie **"Import abbrechen"** aus.

Wenn der Import beginnt, gelangen Sie zurück zur Registerkarte " **Gesammelte Daten** " der Anforderung. Eine Meldung über der Registerkarte gibt an, dass der Upload ausgeführt wird. Wenn ein Problem mit dem Upload vorliegt, werden Sie in der Nachricht informiert und eine Option zum Erneuten Versuchen bereitgestellt.

Wenn der Import abgeschlossen ist, wird über der Registerkarte " **Gesammelte Daten** " eine Bestätigungsmeldung angezeigt.

**Weitere Details zum Importieren von Dateien:**

- Die Größe einzelner Dateien darf 4 MB nicht überschreiten. Im Feld " **Dateien importieren** " wird eine Warnmeldung angezeigt, wenn eine Datei zu groß zum Hochladen ist.

- Es kann bis zu 20 Minuten dauern, bis die importierten Dateien auf der Registerkarte **"Gesammelte Daten** " verfügbar sind.

- Wenn bereits ein Import für einen Benutzer ausgeführt wird, kann derselbe Benutzer erst nach Abschluss des vorherigen Uploadvorgangs weitere Dateien hochladen. Mehrere Benutzer können Dateien gleichzeitig auf dieselbe Anforderung hochladen. Je mehr Uploads jedoch ausgeführt werden, desto länger dauert der Abschluss. Statusmeldungen auf der Anforderung informieren, wenn ein Upload abgeschlossen ist und Dateien zur Überprüfung bereit sind.

#### <a name="mark-items-as-include-or-exclude-and-add-notes"></a>Markieren von Elementen als "Einschließen" oder "Ausschließen" und Hinzufügen von Notizen

Überprüfen Sie die Elemente, die auf der Registerkarte " **Gesammelte Daten** " der Anforderung aufgeführt sind.  Wenn Sie beschließen, dass das Element als Teil des Abschlussberichts wieder an die betroffene Person einbezogen werden soll, wählen Sie oben in der Liste der Elemente auf der Befehlsleiste " **Einschließen"** aus. Sie können auch die blaue Schaltfläche **"Einschließen"** im Bereich "Inhaltsüberprüfung" rechts neben der Liste der Elemente auswählen. Wenn Sie **"Einschließen"** auswählen, wird ein Flyoutbereich mit einer Option zum Hinzufügen von Notizen angezeigt. Wenn Sie fertig sind, wählen Sie **"Absenden** " aus, um den Überprüfungsstatus des Elements als **"Einschließen**" zu speichern.

Wenn das Element nicht teil der Anforderung ist, können Sie " **Ausschließen** " auf der Befehlsleiste oder die Schaltfläche **"Ausschließen** " im Inhaltsprüfungsbereich auswählen. Das explizite Markieren eines Elements als **"Ausschließen"** ist häufig für interne Datensätze erforderlich.

Standardmäßig werden nur Elemente, die Sie als **"Einschließen** " markieren, in die [Endgültigen Berichte einbezogen, die für die betroffene Person generiert werden](subject-rights-requests-reports.md).

> [!NOTE]
> Wenn Sie ein Element als **"Ausschließen**" markieren, müssen Sie eine Notiz als Begründung dafür hinzufügen, warum es sich nicht auf die Anforderung von Rechten betroffener Personen bezieht. Notizen dienen internen Zwecken und sind nicht in Abschlussberichten enthalten.

Wenn der Inhalt für Ihre Suchabfrage als falsch positiv angezeigt wird, wählen Sie **"Keine Übereinstimmung** " aus, und wählen Sie im Flyoutbereich " **Bestätigen**" aus. Diese Aktion kennzeichnet das Element als etwas, das bei der Suche nicht erkannt worden sein sollte.

#### <a name="apply-tags"></a>Apply tags

Kategorien können verwendet werden, um Elemente zu identifizieren, die weitere Aufmerksamkeit erfordern. Priva stellt drei Standardtags bereit: **"Nachverfolgung**", "**Löschen**" und "**Aktualisieren**", für die Sie eine Beschreibung festlegen können. Priva bietet auch zwei benutzerdefinierte Tags, die Sie benennen und beschreiben können.

Wenn Sie z. B. während der Datenüberprüfung feststellen, dass ein Inhaltselement nicht von Ihrer Organisation aufbewahrt werden muss, können Sie das **Löschtag** anwenden und dann eine Liste aller markierten Dateien exportieren, sodass Sie zurückkehren und die identifizierten Elemente löschen können, wenn Sie mit der Anforderung fertig sind.

Die fünf Tags, die Sie in **Einstellungen** verwalten, gelten für alle Ihre Anfragen zu Rechten betroffener Personen.

**So fügen Sie Tags hinzu oder entfernen sie:**

- Wählen Sie das Element aus der Liste auf der Registerkarte " **Gesammelte Daten** " der Anforderung aus.
- Wählen Sie im Bereich "Elementvorschau" rechts neben der Liste in der unteren Zeile die Schaltfläche " **Tags anwenden** " aus. Sie können auch die drei Punkte rechts neben dem Elementnamen und die Option " **Tags übernehmen"** auswählen.
- Ein Flyoutbereich wird mit der Liste der Tags angezeigt. Aktivieren Sie das Kontrollkästchen neben einem der Tags, die Sie auf das Element anwenden möchten. Wenn Sie das Kontrollkästchen deaktivieren, wird das Tag entfernt.
- Wenn Sie fertig sind, wählen Sie **"Speichern"** aus, wodurch ihre Markierungen gespeichert und der Flyoutbereich geschlossen wird.

**So fügen Sie benutzerdefinierte Tags hinzu oder aktualisieren Tagbeschreibungen:**
- Wählen Sie auf der Seite "Anträge betroffener Personen" in der oberen rechten Ecke des Bildschirms **Einstellungen** aus, um zu Ihren Priva Einstellungen zu gelangen.
- Wechseln Sie zur Seite " **Datenüberprüfungstags** ", und wählen Sie das Tag aus, um eine Beschreibung und für die benutzerdefinierten Tags einen Namen einzugeben. Erfahren Sie mehr über [Tageinstellungen](priva-settings.md#data-review-tags).

**So exportieren Sie eine Liste mit markierten Elementen:**
- Wechseln Sie in einer Anfrage zu Rechten betroffener Personen zur Seite **"Gesammelte Daten** ".
- Wählen Sie oberhalb der Liste der Elemente den Befehl **"Exportieren** " aus.
- Eine Excel Datei wird heruntergeladen, die die Eigenschaften für alle Elemente anzeigt, die bei der Suche nach der Anforderung gesammelt wurden. Suchen Sie die Spalte **"Kategorien** ", um die Elemente nach Tag zu identifizieren und zu sortieren.

#### <a name="use-the-annotate-command-to-redact-text"></a>Verwenden des Befehls "Anmerkungen" zum Bearbeiten von Text
Mit dem Befehl **"Anmerkungen** " im Inhaltsprüfungsbereich können Sie Inlinemarkups erstellen und Daten innerhalb eines Inhaltselements bearbeiten. Wenn Sie z. B. eine Datei für eine Person einschließen müssen, die auch die persönlichen Informationen einer anderen betroffenen Person enthält, können Sie unter der Schaltfläche "Zeichnen" in der Befehlsleiste die **Bearbeitung des Bereichs** verwenden, um alle Informationen auszublenden, die sich nicht auf die Person beziehen, die die Anforderung gestellt hat. Wenn Ihre Bearbeitungen abgeschlossen sind, wählen Sie **"Einschließen** " aus, um der Anforderung die bearbeitete Datei hinzuzufügen. Mit der Anmerkung wird eine Kopie der Datei erstellt, die in Ihrem Azure-Blob gespeichert ist. Die Originaldatei bleibt unverändert und wird an ihrem ursprünglichen Speicherort gespeichert.

#### <a name="enter-notes-about-a-file"></a>Eingeben von Notizen zu einer Datei
Um Notizen zu einem Element hinzuzufügen oder zu überprüfen, wählen Sie das Element aus seiner Zeile aus, und wechseln Sie zur Registerkarte **"Dateinotizen** " im Bereich "Inhaltsüberprüfung" rechts. Sie können auch die Option **"Dateinotiz hinzufügen** " verwenden, um einen neuen Kommentar zu erstellen. Wenn Sie Notizen auf gesamter Fallebene überprüfen oder hinzufügen möchten, wechseln Sie zur Hauptregisterkarte " **Notizen** " oben, und verwenden **Sie "Fallnotiz hinzufügen**". Diese Notizen sind für Benutzer sichtbar, die an der Anforderung arbeiten, werden jedoch nicht in den Abschlussbericht aufgenommen oder anderweitig an die betroffene Person weitergegeben.

## <a name="collaboration-for-data-review"></a>Zusammenarbeit für die Datenüberprüfung

Antragstellerberechtigungsadministratoren können alle Anforderungen anzeigen. Sie können andere Benutzer hinzufügen, um an einer Anforderung zusammenzuarbeiten, wodurch sie Zugriff auf diese Anforderung erhalten und mit den darin gesammelten Daten arbeiten können, um die Anforderung bis zum Abschluss zu verschieben.

Wenn Sie eine Anforderung erstellen, wird automatisch ein dedizierter Teams Kanal erstellt, in dem die Projektbeteiligten die Anforderung besprechen und Eingaben und Beiträge sicher freigeben können. Auf der Registerkarte "Mitarbeiter" auf der Seite "**Anforderungsdetails**" werden alle Mitarbeiter angezeigt, die die Anforderung anzeigen und an ihr mitwirken können, sowie alle zugehörigen Teams Kanals.

Wenn Sie weitere Mitarbeiter hinzufügen möchten, wählen **Sie "Mitarbeiter hinzufügen"** aus, beginnen Sie mit der Eingabe des Benutzernamens, wählen Sie den Namen aus, sobald er angezeigt wird, und wählen Sie dann **"Hinzufügen"** aus.

Um einen Teams Chat zu starten, kann jeder Mitarbeiter oben rechts auf der Detailseite der Anforderung **"Chat mit Mitarbeitern**" auswählen. Diese Aktion öffnet Teams und platziert Sie im Kanal **"Allgemein**" für die Teamwebsite Ihrer Anfrage zu Rechten betroffener Personen.

Sie können das Standardverhalten beim Erstellen Teams Kanälen für Anfragen zu Rechten betroffener Personen ändern, indem Sie in der oberen rechten Ecke der Anfrage zu Rechten betroffener Personen zu **Priva Einstellungen** wechseln. Wählen Sie **Teams Zusammenarbeit** aus, und deaktivieren Sie dann das Kontrollkästchen auf der Seite, um Teams Funktionen für alle Anfragen zu Rechten betroffener Personen zu deaktivieren.

Der Befehl **"Freigeben"** oben rechts auf der Detailseite einer Anforderung erstellt einen freigabefähigen Link, der direkt zur Anforderung in Priva wechselt. Weisen Sie diesen Link Mitarbeitern zu, damit sie auf die Anforderung zugreifen können, der Sie sie hinzugefügt haben.

## <a name="complete-the-review"></a>Abschließen der Überprüfung

Wenn alle Elemente überprüft wurden und Sie deren Status als **"Einschließen**", " **Ausschließen**" oder " **Keine Übereinstimmung** " festgelegt haben, ist es an der Zeit, den Überprüfungsschritt zu schließen. Jeder mitarbeiter auf einer Anfrage kann die Überprüfung abschließen.

Wählen Sie in der oberen rechten Ecke der Anforderung die Schaltfläche " **Überprüfung abgeschlossen** " aus. Ein Flyoutbereich zeigt eine Zusammenfassung der Daten an und fügt alle zugehörigen Notizen hinzu. Diese Notizen dienen der internen Aufzeichnung und werden nicht für die betroffene Person freigegeben.

Wählen Sie im Flyoutbereich " **Vollständige Überprüfung** " aus, um den Überprüfungsschritt abzuschließen. Diese Aktion bereitet die Anforderung für die letzten Phasen des Prozesses vor: Generieren von Berichten und Schließen der Anforderung. Zusammenfassungen Ihrer Entscheidungen werden später auf der Registerkarte " **Berichte** " angezeigt.

## <a name="next-steps"></a>Nächste Schritte
Erfahren Sie, wie Sie den Abschlussbericht generieren und auf den Abschluss der Anforderung bei ["Berichte generieren" hinarbeiten und eine Anforderung schließen](subject-rights-requests-reports.md).

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
