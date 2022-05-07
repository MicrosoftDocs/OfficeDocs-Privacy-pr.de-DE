---
title: Untersuchen und Beheben von Warnungen im Datenschutzrisikomanagement
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
- M365-priva-privacy-risk-management
search.appverid:
- MOE150
- MET150
description: Erfahren Sie, wie Sie Warnungen und Probleme verwalten, die durch Richtlinienübereinstimmungen in Microsoft Priva Privacy Risk Management ausgelöst werden.
ms.openlocfilehash: a770a7b8d77e2d7792fc4ea8c68914dc62b48a27
ms.sourcegitcommit: 0e68501654f702d8b8b694ae696bb8bd7fa7cea6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/07/2022
ms.locfileid: "65268328"
---
# <a name="investigate-and-remediate-alerts-in-privacy-risk-management"></a>Untersuchen und Beheben von Warnungen im Datenschutzrisikomanagement

Microsoft Priva kann Ihnen dabei helfen, Einblicke in wichtige Entdeckungen aus Ihren Datenüberbelichtungs-, Datenminimierungs- oder Datenübertragungsrichtlinien zu bieten. Innerhalb der Privacy Risk Management-Lösung können Administratoren **Warnungen** zu Inhalten überprüfen, die Ihren Richtlinienbedingungen entsprechen. Durch das Überprüfen von Warnungen können Sie Fälle identifizieren, die nachverfolgt werden müssen. Sie können dies tun, indem Sie **Probleme** erstellen. Probleme bieten Ihren Benutzern eine strukturierte Möglichkeit, Inhalte zu überprüfen, den Schweregrad des Problems zuzuweisen und gemeinsam an der Behebung von Problemen zu arbeiten.

Wenn Ihre Richtlinie so eingerichtet wurde, dass Benachrichtigungen an Ihre Benutzer gesendet werden, können Inhaltsbesitzer bestimmte Korrekturmaßnahmen auch direkt aus diesen E-Mails oder aus Teams ausführen. Weitere Informationen finden [Sie unter "Senden von Benutzerbenachrichtigungen im Datenschutzrisikomanagement](risk-management-notifications.md)".

## <a name="view-current-alerts-and-issues"></a>Aktuelle Warnungen und Probleme anzeigen

Die Priva-Seite **"Übersicht** " bietet einen Einblick in aktuelle Ergebnisse mit Updates zu wichtigen Bereichen, z. B. den Richtlinien mit den meisten Übereinstimmungen und Ihren derzeit aktiven Richtlinienwarnungen. Weitere Informationen zu den in dieser Ansicht bereitgestellten Informationen finden [Sie unter Suchen und Visualisieren personenbezogener Daten in Priva](priva-data-profile.md).

Sie können auch über die Hauptseite " **Richtlinien** " auf Visualisierungen und Details zu Ihren Warnungen und Problemen zugreifen. Wählen Sie **"Warnungen anzeigen"** und **"Probleme anzeigen"** aus, um Details anzuzeigen.

## <a name="manage-alerts"></a>Verwalten von Warnungen

Um Ihre aktiven Warnungen auszuwerten und anzugeben, welche Warnungen nachverfolgt werden müssen, greifen Sie auf Ihre **Warnungsseite** zu. Es bietet eine filterbare Liste der Warnungen, die von Ihren Richtlinien generiert werden. Sie können sie einzeln überprüfen, um die Umstände zu ermitteln, unter denen sie ausgelöst wurden.

Wenn Sie eine Warnung auswählen, wird ein Flyoverbereich mit zusätzlichen Details geöffnet, z. B. die Anzahl der übereinstimmenden Elemente und der Schweregrad, wie sie anhand Ihrer Richtlinieneinstellungen beurteilt werden. Auf der Registerkarte **"Inhalt** " können Sie überprüfen, welche Dateien an dieser Warnung beteiligt sind. Diese Informationen können zusätzliche Einblicke in das spezifische Ereignis liefern, das die Warnung ausgelöst hat, wo sich die Dateien befinden und welche Arten von personenbezogenen Daten beteiligt sind. Trigger für Warnungen werden durch die spezifischen Bedingungen jeder Richtlinie bestimmt. Beispielsweise kann eine Warnung bei einer Datenübertragungsrichtlinie ausgelöst werden, wenn Priva eine Übertragung zwischen den angegebenen Abteilungen oder Regionen der Richtlinie erkennt.

Nachdem Sie eine Warnung in der Liste bewertet haben, können Sie " **Problem erstellen"** auswählen, um weitere Untersuchungen und Aktionen ihrer Benutzer zu veranlassen. Sie werden aufgefordert, das Problem zu benennen und relevante Kommentare für den Kontext hinzuzufügen. Sie können Benachrichtigungen auch hier schließen, wenn sie keine Nachverfolgung erfordern.

## <a name="manage-issues"></a>Verwalten von Problemen

Probleme werden von Administratoren bei der Bewertung von Warnungen zu Richtlinienübereinstimmungen erstellt. Um die angegebenen Bedenken zu verfolgen und zu beheben, können Benutzer die Seite **"Probleme** " besuchen. Von hier aus können Sie einzelne Probleme überprüfen, die anstiftenden Bedingungen untersuchen, die Daten überprüfen und die erforderlichen Schritte ausführen, um den Fall zu schließen.

Diese Seite enthält eine Liste aller offenen Probleme. Sie werden nach Namen aufgelistet und nach Schweregrad sortiert, damit Sie Fälle, einschließlich hoher, mittlerer und niedriger Kategorien, sowie nicht zugewiesener Fälle priorisieren können. Wählen Sie ein Beliebiges Problem in der Liste aus, um dessen Inhalt zu überprüfen und Maßnahmen zu ergreifen, um es zu beheben. Sie können nicht zugewiesenen Problemen während der Überprüfung eine Schweregradbewertung zuweisen.

### <a name="review-issue-details"></a>Problemdetails überprüfen

Problemdetailseiten helfen Ihnen, den Prozess der Behandlung der identifizierten Datenschutzrisiken und des Umgangs mit den angegebenen Dateien zu durchlaufen.

Die Registerkarten auf den Problemdetailseiten enthalten Informationen zu den zugehörigen Warnungen und Inhalten, einschließlich:

- **Übersicht**: Enthält wichtige Informationen zu dem Problem. Sehen Sie sich den aktuellen Status des Problems und die nächsten empfohlenen Maßnahmen an. Sie können auch eine Übersicht über den Inhalt, die zugeordnete Richtlinie, Details zur Warnung und die Zeitachse anzeigen. Auf der Zeitachse wird angezeigt, wo Sie Sich beim Abrufen von Inhalten befinden. Heruntergeladene Inhalte werden vorübergehend zur Überprüfung aufbewahrt.
- **Warnungen**: Eine detaillierte Liste der Warnungen, die mit dem Problem verbunden sind.
- **Inhalt**: Eine filterbare Liste der zugeordneten Inhaltselemente. Wählen Sie ein beliebiges Element aus, um Details darüber anzuzeigen, einschließlich aller aktivitäten, die aufgetreten sind, und des Zugehörigen Wartungsverlaufs, wenn jemand bereits Aktionen in Priva zum Verwalten der Daten ausgeführt hat. Sie können auch neue Korrekturaktionen ausführen.
- **Hinweise**: Wählen Sie diese Option aus, um Notizen für Ihr Team zu dem Problem hinzuzufügen oder anzuzeigen.
- **Mitarbeiter**: Anzeigen und Verwalten der Liste der Mitarbeiter, die zur Lösung dieses Problems beitragen können.

### <a name="share-the-issue"></a>Teilen des Problems

Wenn Sie Personen als Mitarbeiter hinzufügen, können Sie das Problem mit weiteren Mitgliedern Ihres Unternehmens über einen sicheren Microsoft Teams Kanal, E-Mail-Adresse des Unternehmens oder durch direkte Freigabe eines Links zur Seite des Problems in Priva teilen. Diese Optionen sind unter der Schaltfläche " **Freigeben** " verfügbar. Bei der Freigabe über Teams werden Sie aufgefordert, aus den verfügbaren Teams in Ihrer Organisation auszuwählen, den bestimmten Kanal auszuwählen und eine Meldung zu dem Problem zu hinterlassen, die für den angegebenen Kanal freigegeben wird.

## <a name="review-content-and-remediate-issues"></a>Überprüfen von Inhalten und Beheben von Problemen

Wenn Sie den inhalt überprüfen möchten, der einem Problem zugeordnet ist, wählen Sie die Aktion " **Inhalt überprüfen** " aus, wenn Sie dazu aufgefordert werden, oder öffnen Sie die Registerkarte **"Inhalt** ". Wählen Sie eine beliebige Datei in der Liste aus, um sie vollständig anzuzeigen. Hier können Sie Details zu der Datei, allen Aktivitäten auf dem Datensatz und deren Wartungsverlauf anzeigen, wenn vorherige Schritte zum Verwalten dieser Datei ausgeführt wurden. Wählen Sie **"Korrigieren"** aus, um eine oder mehrere der unten aufgeführten Aktionen auszuführen.

- **Besitzer benachrichtigen**: Benachrichtigen Sie den Inhaltsbesitzer über das erkannte Problem.

- **Aufbewahrungsbezeichnung anwenden**: Fügen Sie eine Bezeichnung für dieses Element hinzu, die es aufbewahren, löschen oder aufbewahren und dann nach einer bestimmten Zeit löschen kann. [Weitere Informationen zu Aufbewahrungsbezeichnungen](/microsoft-365/compliance/retention).

- **Vertraulichkeitsbezeichnung anwenden**: Fügen Sie eine Bezeichnung für dieses Element hinzu, die seine Vertraulichkeit identifiziert, und fügen Sie optional Schutz hinzu, der visuelle Markierungen und Verschlüsselung umfasst. [Erfahren Sie mehr über Vertraulichkeitsbezeichnungen](/microsoft-365/compliance/sensitivity-labels).

- **Als keine Übereinstimmung markieren**: Identifizieren Sie ein Suchergebnis als falsch positives Ergebnis, um das Inhaltselement zu entfernen.

- **Löschen** (nur für Datenminimierungsrichtlinien): Verwenden Sie diese Option für ein vorläufiges Löschen der Daten. Das Element wird in den Ordner "Gelöschte Elemente" oder den Papierkorb (Exchange, SharePoint, OneDrive) verschoben oder mit einer Option zum Wiederherstellen (Teams Nachrichten) gelöscht. Der Löschvorgang kann in Abhängigkeit von den Einstellungen des Diensts innerhalb eines festgelegten Zeitraums rückgängig gemacht werden.

- **Privat machen** (nur für Datenüberbelichtungs- und Datenübertragungsrichtlinien): Entfernen Sie den offenen Zugriff für dieses Inhaltselement.

Jede Option fordert Sie auf, Kommentare und andere erforderliche unterstützende Informationen für den Inhaltsbesitzer zu hinterlassen, bevor Sie Ihre Auswahl bestätigen.

Sobald alle Abhilfemaßnahmen (einschließlich aller Aktionen, die Sie zusätzlich zu den verfügbaren Optionen in Priva für ratsam halten) durchgeführt wurden und das Problem geschlossen werden kann, verwenden Sie die Schaltfläche " **Beheben** ", und fügen Sie Ihre abschließenden Kommentare hinzu, bevor Sie es übermitteln.

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
