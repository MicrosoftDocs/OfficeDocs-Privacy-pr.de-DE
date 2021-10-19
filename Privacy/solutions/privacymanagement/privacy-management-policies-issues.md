---
title: Grundlegendes zu Warnungen und Problemen bei der Datenschutzverwaltung
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
description: Erfahren Sie, wie Sie Warnungen und Probleme verwalten, die von Richtlinienüberstimmungen in der Datenschutzverwaltung ausgelöst werden.
ms.openlocfilehash: a5dcdc78484f664249578475326ad9d39c1cd381
ms.sourcegitcommit: 85e085eb17af8b4efd1f45207445e1b3c3679600
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/19/2021
ms.locfileid: "60478256"
---
# <a name="understand-policy-alerts-and-issues-in-privacy-management"></a>Grundlegendes zu Richtlinienwarnungen und Problemen bei der Datenschutzverwaltung

Die Datenverwaltung kann dazu beitragen, wichtige Erkenntnisse aus Ihrer Datenüberlastung, Datenminimierung oder Datenübertragungsrichtlinien sichtbar zu machen. Innerhalb der Datenschutzverwaltungslösung können Administratoren **Warnungen** zu Inhalten überprüfen, die Ihren Richtlinienbedingungen entsprechen. Mit der Überprüfung von Warnungen können Sie Fälle identifizieren, die nachgesehen werden müssen. Sie können dies tun, indem Sie **Probleme erstellen.** Probleme bieten Ihren Benutzern eine strukturierte Möglichkeit, Inhalte zu überprüfen, den Schweregrad des Problems zuzuweisen und gemeinsam an der Behebung von Problemen zu arbeiten.

Wenn Ihre Richtlinie so eingerichtet wurde, dass Benachrichtigungen an Ihre Benutzer gesendet werden, können Inhaltsbesitzer auch bestimmte Korrekturmaßnahmen direkt über diese E-Mails oder über Teams ergreifen. Weitere Informationen finden Sie unter [Senden von Benutzerrichtlinienbenachrichtigungen.](privacy-management-policies-notifications.md)

## <a name="view-current-alerts-and-issues"></a>Anzeigen aktueller Warnungen und Probleme

**Die Übersichtsseite** des Datenschutzmanagements bietet einen Überblick über die neuesten Ergebnisse mit Updates zu wichtigen Bereichen, z. B. die Richtlinien mit den meisten Übereinstimmungen und Ihre derzeit aktiven Richtlinienwarnungen. Weitere Informationen zu den Informationen, die diese Ansicht bereitstellt, finden Sie unter [Suchen und Visualisieren Ihrer Daten.](privacy-management-data-profile.md)

Sie können auch über die Hauptseite **"Richtlinien"** auf Visualisierungen und Details zu Ihren Warnungen und Problemen zugreifen. Wählen Sie **Warnungen anzeigen** und **Probleme anzeigen** aus, um Details anzuzeigen.

## <a name="manage-alerts"></a>Verwalten von Warnungen

Um Ihre aktiven Warnungen auszuwerten und anzugeben, welche nachverfolgungsbereit sein müssen, greifen Sie auf die Seite **"Warnungen"** zu. Es stellt eine filterbare Liste von Warnungen bereit, die von Ihren Richtlinien generiert werden. Sie können diese einzeln überprüfen, um die Umstände zu ermitteln, unter denen sie ausgelöst wurden.

Wenn Sie eine Warnung auswählen, wird ein Flyover-Bereich mit zusätzlichen Details geöffnet, wie z. B. die Anzahl der übereinstimmenden Elemente und der Schweregrad, der von Ihren Richtlinieneinstellungen als unerwähnt eingestuft wird. Auf der Registerkarte **"Inhalt"** können Sie überprüfen, welche Dateien an dieser Warnung beteiligt sind. Diese Informationen können zusätzliche Einblicke in das spezifische Ereignis liefern, das die Warnung ausgelöst hat, wo sich die Dateien befinden und welche Arten von personenbezogenen Daten beteiligt sind. Trigger für Warnungen werden durch die spezifischen Bedingungen der einzelnen Richtlinien bestimmt. Beispielsweise kann eine Warnung für eine Datenübertragungsrichtlinie ausgelöst werden, wenn die Datenverwaltung eine Übertragung zwischen den angegebenen Abteilungen oder Regionen der Richtlinie erkennt.

Nachdem Sie eine Warnung in der Liste bewertet haben, können Sie **"Problem erstellen"** auswählen, um weitere Untersuchungen und Aktionen durch Ihre Benutzer zu veranlassen. Sie werden aufgefordert, das Problem zu benennen und alle relevanten Kommentare für den Kontext hinzuzufügen. Sie können Warnungen hier auch schließen, wenn keine Nachverfolgung erforderlich ist.

## <a name="manage-issues"></a>Verwalten von Problemen

Probleme werden von Administratoren erstellt, während Warnungen zu Richtlinienüberstimmungen bewertet werden. Um die angegebenen Bedenken zu verfolgen und zu beheben, können Benutzer die Seite **"Probleme"** besuchen. Von hier aus können Sie einzelne Probleme überprüfen, die anstiftenden Bedingungen untersuchen, die Daten überprüfen und die erforderlichen Schritte ausführen, um den Fall zu schließen.

Diese Seite enthält eine Liste aller offenen Probleme. Sie werden nach Namen aufgelistet und nach Schweregrad sortiert, damit Sie Fälle priorisieren können, einschließlich der Kategorien "Hoch", "Mittel" und "Niedrig" sowie "Nicht zugewiesen". Wählen Sie ein Problem in der Liste aus, um dessen Inhalt zu überprüfen, und ergreifen Sie Maßnahmen, um es zu beheben. Sie können nicht zugewiesenen Problemen während der Überprüfung eine Bewertung des Schweregrads zuweisen.

### <a name="review-issue-details"></a>Überprüfen von Problemdetails

Seiten mit Problemdetails helfen Ihnen dabei, die identifizierten Datenschutzrisiken zu behandeln und die angegebenen Dateien zu behandeln.

Die Registerkarten auf Problemdetailseiten enthalten Informationen zu den zugehörigen Warnungen und Inhalten, einschließlich:

- **Übersicht:** Enthält wichtige Informationen zu dem Problem. Sehen Sie sich den aktuellen Status des Problems und die nächsten empfohlenen Aktionen an. Sie können auch eine Übersicht über den Inhalt, die zugeordnete Richtlinie, Details zur Warnung und die Zeitachse anzeigen. Die Zeitachse zeigt an, wo Sie Inhalte abrufen. Heruntergeladene Inhalte werden vorübergehend zur Überprüfung aufbewahrt.
- **Warnungen:** Eine detaillierte Liste der Warnungen im Zusammenhang mit dem Problem.
- **Inhalt:** Eine filterbare Liste der zugeordneten Inhaltselemente. Wählen Sie ein beliebiges Element aus, um Details dazu anzuzeigen, einschließlich aller aktivitäten, die aufgetreten sind, und des Wartungsverlaufs, wenn jemand bereits Aktionen in der Datenverwaltung zur Verwaltung der Daten ausgeführt hat. Sie können auch neue Korrekturmaßnahmen ergreifen.
- **Hinweise:** Wählen Sie diese Option aus, um Notizen zu dem Problem für Ihr Team hinzuzufügen oder anzuzeigen.
- **Mitarbeiter:** Anzeigen und Verwalten der Liste der Mitarbeiter, die zur Lösung dieses Problems beitragen können.

### <a name="share-the-issue"></a>Freigeben des Problems

Wenn Sie Personen als Mitarbeiter hinzufügen, können Sie das Problem mit zusätzlichen Mitgliedern Ihres Unternehmens über einen sicheren Microsoft Teams Kanal, eine Unternehmens-E-Mail oder durch direktes Freigeben eines Links zur Seite des Problems in der Datenschutzverwaltung teilen. Diese Optionen sind unter der Schaltfläche **"Freigeben"** verfügbar. Bei der Freigabe über Teams werden Sie aufgefordert, aus den verfügbaren Teams in Ihrer Organisation auszuwählen, den spezifischen Kanal auszuwählen und eine Nachricht zu dem Problem zu hinterlassen, das für den angegebenen Kanal freigegeben wird.

## <a name="review-content-and-remediate-issues"></a>Überprüfen von Inhalten und Beheben von Problemen

Wenn Sie den mit einem Problem verbundenen Inhalt überprüfen möchten, wählen Sie die **Aktion "Inhalt überprüfen"** aus, wenn Sie dazu aufgefordert werden, oder öffnen Sie die Registerkarte **"Inhalt".** Wählen Sie eine beliebige Datei in der Liste aus, um sie vollständig anzuzeigen. Hier sehen Sie Details zu der Datei, zu allen aufgezeichneten Aktivitäten und zum Wartungsverlauf, wenn vorherige Schritte zum Verwalten dieser Datei ausgeführt wurden.

Verwenden Sie die Schaltfläche **"Korrigieren",** um ihre eigenen Entscheidungen zur Datenverarbeitung für diese Inhalte im Datenschutzmanagement zu treffen. Wenn Sie die Schaltfläche auswählen, können Sie eine oder mehrere Korrekturaktionen auswählen. Die folgenden Optionen stehen zur Verfügung:

**Alle Richtlinien**

- **Besitzer benachrichtigen:** Benachrichtigen Sie den Inhaltsbesitzer über das erkannte Problem.
- Anwenden einer **Aufbewahrungsbezeichnung:** Fügen Sie eine Bezeichnung zur Datenaufbewahrung für dieses Element hinzu. [Weitere Informationen zu Aufbewahrungsbezeichnungen.](/microsoft-365/compliance/create-apply-retention-labels)
- Anwenden einer **Vertraulichkeitsbezeichnung:** Fügen Sie eine Bezeichnung zur Vertraulichkeit der Daten dieses Elements hinzu. [Weitere Informationen zu Vertraulichkeitsbezeichnungen.](/microsoft-365/compliance/sensitivity-labels)
- **Als keine Übereinstimmung kennzeichnen:** Identifizieren Sie ein Suchergebnis als falsch positives Ergebnis, um das Inhaltselement aus der Überlegung zu entfernen.

**Datenminimierung**

- **Löschen:** Verwenden Sie diese Option zum vorläufigen Löschen der Daten. Inhalte werden in den Ordner "Gelöschte Elemente" oder "Wiederverwenden" (Exchange, SharePoint, OneDrive) verschoben oder mit einer Option zum Wiederherstellen (Teams Nachrichten) gelöscht. Der Löschvorgang kann innerhalb eines festgelegten Zeitraums rückgängig gemacht werden, abhängig von den Einstellungen des Diensts.

**Datenüberlastung und Datenübertragung**

- **Privat:** Entfernen sie den offenen Zugriff für dieses Inhaltselement.

Bei jeder Option werden Sie aufgefordert, Kommentare und alle anderen erforderlichen unterstützenden Informationen für den Inhaltsbesitzer zu hinterlassen, bevor Sie Ihre Auswahl bestätigen.

Nachdem alle Korrekturschritte ausgeführt wurden (einschließlich aller Aktionen, die Sie zusätzlich zu den Optionen, die Ihnen in der Datenschutzverwaltung zur Verfügung stehen), als ratsam eingestuft haben und das Problem geschlossen werden kann, verwenden Sie die Schaltfläche **"Auflösen",** und fügen Sie Ihre endgültigen Kommentare hinzu, bevor Sie sie übermitteln.

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Datenschutzverwaltung](privacy-management-disclaimer.md)
