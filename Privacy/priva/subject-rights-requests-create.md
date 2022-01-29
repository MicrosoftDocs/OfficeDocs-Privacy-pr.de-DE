---
title: Erstellen einer Anforderung für Antragstellerrechte
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
description: Erfahren Sie, wie Sie eine neue Anforderung für Antragstellerrechte in Microsoft Priva erstellen.
ms.openlocfilehash: b906fbc3a07ac67cec2c2a4b0433065d42c665e2
ms.sourcegitcommit: f145dff5e387a8e26db2f3a2c7de125978fbacc9
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/28/2022
ms.locfileid: "62249034"
---
# <a name="create-a-subject-rights-request"></a>Erstellen einer Anforderung für Antragstellerrechte

Administratoren der Rechteverwaltung von Antragstellern können neue Anforderungen über privas Hauptseite für Anträge betroffener Personen öffnen. Ein Assistent führt Sie durch den Prozess der Suche nach personenbezogenen Daten über eine betroffene Person und beginnt mit dem Prozess der Erfüllung ihres Antrags.

Sie können auch zusätzliches Material hochladen, damit Priva betroffene Personen basierend auf genau angegebenen Datenwerten identifizieren kann. Weitere Informationen finden Sie unter ["Datenabgleich für Anträge betroffener Personen"](subject-rights-requests-data-match.md).

## <a name="use-the-subject-rights-request-creation-wizard"></a>Verwenden des Assistenten zum Erstellen von Antragstellerrechten

1. Wechseln [Sie im Microsoft 365 Compliance Center](https://compliance.microsoft.com/) zum Abschnitt "Priva", und wählen Sie **"Priva-Antragstellerrechteanforderungen" aus**.
1. Um eine neue Anforderung zu starten, wählen Sie " **Anforderung erstellen" aus**.
1. Identifizieren Sie die betroffene Person, die den Antrag gestellt hat, und geben Sie ihre Beziehung zu Ihrem Unternehmen an.
1. Wir führen eine Standardsuche für Elemente aus, die sich auf die betroffene Person beziehen. Wenn Sie Ihre Suche verfeinern oder eine Schätzung erhalten möchten, bevor wir Daten abrufen, können Sie diese Auswahl in dieser Phase treffen. Sie können auch alle Elemente leer lassen und mit dem nächsten Schritt fortfahren. Weitere Informationen zu Ihren Optionen finden Sie unter [Definieren von Sucheinstellungen](#define-search-settings) und [Verfeinern der Suche](#refine-your-search).
1. Wählen Sie einen Anforderungstyp basierend auf dem, was die betroffene Person mit ihren Daten tun möchte. Wenn sich ihr Antrag auf eine bestimmte Datenschutzbestimmungen bezieht, können Sie sie auch aus einer bereitgestellten Liste auswählen, um mehr Kontext hinzuzufügen. Das Festlegen eines Stichtags (erforderlich) erleichtert die Sortierung nach eingehenden oder überfälligen Anforderungen und deren zeitnahe Lösung. Anforderungstypen umfassen:
   - **Access**: Bietet eine Zusammenfassung der persönlichen Informationen der betroffenen Person, die von Ihrer Organisation in Microsoft 365 gespeichert sind.
   - **Export**: Enthält eine Zusammenfassung und einen Export der persönlichen Informationen der betroffenen Person, die während der Überprüfung erfasst und kommentiert werden.
   - **Markierte Liste für die Nachverfolgung**: Generiert eine Zusammenfassung aller Dateien, die Benutzer während der Überprüfung markieren, die möglicherweise zusätzliche Aktionen außerhalb von Priva erfordern. Möglicherweise müssen Sie z. B. die Löschung der personenbezogenen Daten der betroffenen Person gemäß deren Anforderung vereinfachen. Benutzerdefinierte Datenüberprüfungstags für Anträge betroffener Personen können in globalen **Einstellungen** verwaltet werden.
1. Bestätigen Sie den Namen dieser Anforderung, und fügen Sie eine optionale Beschreibung für den Verweis hinzu.
1. Überprüfen Sie die Zusammenfassung der Eingaben, die Sie in den vorherigen Schritten eingegeben haben. Jedes Feld kann bearbeitet werden, bevor Sie **"Anforderung erstellen**" auswählen.

### <a name="define-search-settings"></a>Definieren von Sucheinstellungen

Beim Erstellen einer Anforderung für Betreffrechte können Sie eine oder alle dieser Suchoptionen auswählen, um Daten über den Betreff zu finden:

- **Von der betroffenen Person verfasste Inhalte** einschließen: Dies umfasst von der betroffenen Person verfasste Inhalte und kann ein höheres Datenvolumen zurückgeben.
- **Verfeinern Sie Ihre Suche**: Auf diese Weise können Sie zusätzliche Eigenschaften angeben, mit denen Sie die betroffene Person identifizieren können. Hier können Sie ihre Suche auf bestimmte Microsoft 365 Dienste oder Ressourcen beschränken oder andere Bedingungen auswählen, um den Umfang der Anforderung anzupassen. Nachdem Sie diese Option ausgewählt haben, werden Sie aufgefordert, Ihre benutzerdefinierten Suchparameter einzugeben.
- **Erhalten Sie zuerst eine Schätzung**: Auf diese Weise können Sie sehen, wie viele Daten wir erwarten, bevor Ihre Daten automatisch abgerufen werden.

### <a name="refine-your-search"></a>Verfeinern Der Suchbegriff

Wenn Sie sich für eine Verfeinerung Der Suche während der Definition Ihrer Sucheinstellungen entschieden haben, werden Sie aufgefordert, Ihre erweiterten Suchparameter auszufüllen. Sie können **Bezeichner hinzufügen,** **Bedingungen** festlegen und bestimmte **Speicherorte** innerhalb Microsoft 365 für die Suche auswählen.

- **Hinzufügen von Bezeichnern**: Stellen Sie weitere identifizierende Informationen über die betroffene Person bereit, z. B. Namen, E-Mail-Adressen und/oder andere Optionen. Trennen Sie mehrere Werte in jedem Feld durch ein Semikolon.
- **Bedingungen**: Beginnen Sie mit dem Hinzufügen von Bedingungen für Ihre Suche, indem Sie einen Typ aus der Dropdownliste auswählen. Diese Typen entsprechen möglichen Eigenschaften der Daten, z. B. Zeitrahmen, Größe, Aufbewahrungsbezeichnungen, Absendern und Empfängern und vielen anderen. Wählen Sie einen beliebigen Typ aus, um ihn hinzuzufügen, und legen Sie dann die gewünschten Eigenschaften fest. Bei Textfeldeinträgen können Sie mehrere Schlüsselwörter hinzufügen, die durch Semikolons getrennt sind. Sie können beliebig viele Inhaltstypen hinzufügen.
- **Speicherorte**: Sie können ihre Suche auf bestimmte SharePoint Websites, Teams Kanäle und OneDrive for Business Speicherorte beschränken. Für jeden Speicherort können Sie alle Instanzen auswählen, z. B. alle Exchange Postfächer oder bestimmte Instanzen, z. B. das Postfach eines Benutzers. Wählen Sie für jede Standortoption den Link **Auswählen...** aus, um Informationen zu bestimmten Instanzen einzugeben. Hilfe zum Identifizieren der entsprechenden Suchbegriffe finden Sie in den folgenden Themen:
  - [Verwalten von Websites im neuen SharePoint Admin Center](/sharepoint/manage-sites-in-new-admin-center): Enthält Anleitungen zum Sortieren und Filtern von Websites und zum Suchen nach einer SharePoint Website. Verwenden Sie diese Option, um URLs für das suchfeld SharePoint zu suchen.
  - [Get-Team](/powershell/module/teams/get-team): Enthält Informationen dazu, wie Sie Teams in Microsoft Teams anhand bestimmter Eigenschaften/Informationen finden. Verwenden Sie dies, um Teams Chats und Kanäle zu identifizieren.
  - [Informationen zu OneDrive URLs](/onedrive/list-onedrive-urls#about-onedrive-urls): Enthält Informationen zum richtigen Format und zu den Eigenschaften für die OneDrive-URL eines Benutzers. Verwenden Sie dies, um OneDrive Websites in Ihrer Suche zu identifizieren.

Wir empfehlen, Ihre Auswahl sorgfältig zu überprüfen, um sicherzustellen, dass Sie die richtige betroffene Person identifizieren. Wenn Sie beispielsweise Postfächer nach Namen durchsuchen und nach mehreren Personen mit ähnlichen Namen suchen, überprüfen Sie den richtigen, bevor Sie sie zu Ihrer Anforderung hinzufügen.

## <a name="next-steps"></a>Nächste Schritte

Nachdem Sie Ihre Anforderung erstellt haben, wird sie auf der Seite für die Anforderung von Antragstellerrechten aufgeführt. Weitere Informationen dazu, wie Sie mit der Überprüfung fortfahren können, finden Sie unter ["Überprüfen von Daten und Zusammenarbeit bei Anforderungen"](subject-rights-requests-data-review.md).

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
