---
title: Erstellen einer Anfrage zu Rechten betroffener Personen
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
description: Erfahren Sie, wie Sie eine neue Anfrage zu Rechten betroffener Personen in Microsoft Priva erstellen.
ms.openlocfilehash: b2d846aa4020be315705bbd16e00378c7514146c
ms.sourcegitcommit: 09ecdaded9a9f8f79587f2acb978dc53b83e5c01
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/19/2022
ms.locfileid: "64930606"
---
# <a name="create-a-subject-rights-request"></a>Erstellen einer Anfrage zu Rechten betroffener Personen

Administratoren von Themenrechten können neue Anfragen über privas Hauptseite für Anfragen zu Rechten betroffener Personen öffnen. Ein Assistent führt Sie durch den Prozess der Suche nach personenbezogenen Daten zu einer betroffenen Person und startet den Prozess der Erfüllung ihrer Anforderung.

Sie können auch zusätzliches Material hochladen, um Priva die Identifizierung von betroffenen Personen basierend auf genau angegebenen Datenwerten zu ermöglichen. Weitere Informationen finden Sie unter [Datenabgleich für Anfragen zu Rechten betroffener Personen](subject-rights-requests-data-match.md).

## <a name="request-types"></a>Anforderungstypen

Priva Subject Rights Requests unterstützt drei verschiedene Arten von Anforderungen:

1. **Zugriff**: Bietet eine Zusammenfassung der persönlichen Daten der betroffenen Person, die von Ihrer Organisation in Microsoft 365 aufbewahrt werden.

2. **Export**: Enthält eine Zusammenfassung und eine exportierte Datei mit Inhaltselementen, die die persönlichen Informationen der betroffenen Person enthalten. Dies sind die Elemente, die während der Überprüfung der von Ihren Sucheinstellungen gesammelten Daten überprüft und als **enthalten** gekennzeichnet wurden.

3. **Tagged list for follow up**: Generates a summary of any files that were tagged during data review that may require additional action outside of Priva. Möglicherweise müssen Sie die Löschung der personenbezogenen Daten der betroffenen Person gemäß deren Anfrage vereinfachen. Sie können die enthaltenen Tags anzeigen und benutzerdefinierte Tags für Ihre Organisation in den [Priva-Einstellungen](priva-settings.md) einrichten.

## <a name="use-the-subject-rights-request-creation-wizard"></a>Verwenden des Assistenten zum Erstellen von Anträgen auf Antragstellerrechte

1. Wechseln Sie im [Microsoft Purview Compliance-Portal](https://compliance.microsoft.com/) zum Abschnitt "Priva", und wählen Sie **"Priva Subject Rights Requests"** aus.
1. Um eine neue Anforderung zu starten, wählen Sie " **Anforderung erstellen"** aus.
1. Identifizieren Sie die betroffene Person, die die Anforderung gestellt hat, und geben Sie deren Beziehung zu Ihrem Unternehmen an.
1. Wir führen eine Standardsuche nach Elementen aus, die sich auf die betroffene Person beziehen. Wenn Sie Ihre Suche verfeinern oder eine Schätzung abrufen möchten, bevor wir Daten abrufen, können Sie diese Auswahl in dieser Phase treffen. Sie können auch alle Elemente leer lassen und mit dem nächsten Schritt fortfahren. Weitere Informationen zu Ihren Optionen finden Sie unter [Definieren von Sucheinstellungen](#define-search-settings) und [Verfeinern der Suche](#refine-your-search).
1. Wählen Sie einen Anforderungstyp basierend darauf aus, was die betroffene Person mit ihren Daten tun soll. Wenn sich ihre Anforderung auf eine bestimmte Datenschutzverordnung bezieht, können Sie sie auch aus einer bereitgestellten Liste auswählen, um weiteren Kontext hinzuzufügen. Das Festlegen eines Stichtags (erforderlich) erleichtert das Sortieren von anstehenden oder überfälligen Anforderungen und deren zeitnahe Lösung. Zu den Anforderungstypen gehören:
   - **Zugriff**: Bietet eine Zusammenfassung der persönlichen Daten der betroffenen Person, die von Ihrer Organisation in Microsoft 365 aufbewahrt werden.
   - **Export**: Enthält eine Zusammenfassung und einen Export der personenbezogenen Daten der betroffenen Person, wie sie während der Überprüfung gesammelt und kommentiert werden.
   - **Tagged list for follow up**: Generates a summary of any files that users tag during review that may require additional action outside of Priva. Beispielsweise müssen Sie möglicherweise die Löschung der personenbezogenen Daten der betroffenen Person anhand ihrer Anfrage erleichtern. Benutzerdefinierte Datenüberprüfungstags für Anfragen zu Rechten betroffener Personen können in globalen Einstellungen verwaltet werden **.**
1. Bestätigen Sie den Namen dieser Anforderung, und fügen Sie eine optionale Beschreibung zur Referenz hinzu.
1. Überprüfen Sie die Zusammenfassung der Informationen, die Sie in den vorherigen Schritten eingegeben haben. Jedes Feld kann bearbeitet werden, bevor Sie **"Anforderung erstellen"** auswählen.

Für jede Anforderung von Rechten betroffener Personen können Sie festlegen, dass ihre Suche nach Daten an allen oder bestimmten Speicherorten innerhalb von Exchange und SharePoint sucht. Wählen Sie eine Position aus, indem Sie den Umschalter **auf die** Ein-Position verschieben. Sie können auswählen, ob Sie alle Konten und Websites durchsuchen oder bestimmte Konten oder Websites an jedem Speicherort festlegen möchten. Lesen Sie unten Details zu den Informationen, die an den einzelnen Speicherorten behandelt werden.

- **Exchange**: Diese Option sucht nach Daten in Exchange Postfächern und in Einzel- oder Gruppenchats Teams. Sie können alle Exchange Konten in Ihrer Organisation durchsuchen oder **"Konten auswählen**" auswählen, um einzelne Benutzer aus dem **Flyoutbereich Exchange Postfächer** auszuwählen.

- **SharePoint**: Diese Option sucht nach Daten in SharePoint Websites, OneDrive for Business Websites und Teams Kanälen. Sie können alle SharePoint Websites in Ihrer Organisation durchsuchen oder **Websites auswählen**, um einzelne Benutzer aus dem **Flyoutbereich SharePoint Websites** auszuwählen.

Hilfe zum Identifizieren der entsprechenden Suchbegriffe finden Sie in den folgenden Themen:

- **SharePoint Websites und URLs**: [Verwalten von Websites im SharePoint Admin Center](/sharepoint/manage-sites-in-new-admin-center) bietet Anleitungen zum Sortieren und Filtern von Websites und zum Suchen nach einer SharePoint Website. Verwenden Sie diese Option, um IM Suchfeld im **Flyoutbereich SharePoint Websites** NACH URLs zu suchen.

- **Teams Chats und Kanäle**: [Get-Team](/powershell/module/teams/get-team) zeigt, wie Sie Teams in Microsoft Teams finden, indem bestimmte Eigenschaften oder Informationen bereitgestellt werden.

- **OneDrive Websites und URLs**: [Informationen zu OneDrive URLs](/onedrive/list-onedrive-urls#about-onedrive-urls) enthält Informationen über das richtige Format und die Eigenschaften für die OneDrive-URL eines Benutzers. Verwenden Sie diese Informationen, um OneDrive Websites in Ihrer Suche zu identifizieren.

Wir empfehlen, Ihre Auswahl sorgfältig zu überprüfen, um sicherzustellen, dass Sie die richtige betroffene Person identifizieren. Wenn Sie z. B. Postfächer nach Namen durchsuchen und mehrere Personen mit ähnlichen Namen suchen, überprüfen Sie das richtige, bevor Sie sie zu Ihrer Anforderung hinzufügen.

## <a name="define-search-settings"></a>Definieren von Sucheinstellungen

Wenn Sie eine Anforderung zu Rechten betroffener Personen erstellen, wird eine Standardsuche basierend auf Ihrer Auswahl auf der Seite " **Speicherorte** " des Erstellungs-Assistenten ausgeführt. Wenn Sie eine gezieltere Suche durchführen möchten oder eine Schätzung Ihrer Daten abrufen möchten, bevor Inhaltselemente abgerufen werden, können Sie diese Auswahl auf der Seite " **Sucheinstellungen"** des Assistenten zum Erstellen von Anforderungen treffen.

### <a name="advanced-search-options"></a>Erweiterte Suchoptionen

- **Verfeinern Sie Ihre Suche**: Mit dieser Option können Sie zusätzliche Eigenschaften angeben, um die betroffene Person unter den Daten Ihrer Organisation zu identifizieren. Nachdem Sie diese Option ausgewählt haben, werden Sie aufgefordert, weitere Suchparameter hinzuzufügen, die unten unter ["Verfeinern" der Suche](#refine-your-search) erläutert werden.
- **Inhalte einschließen, die von der betroffenen Person erstellt wurden**: Diese Option sucht nach Inhalten, die von der betroffenen Person erstellt wurden. Beispiele hierfür sind Dateien, die von der betroffenen Person erstellt oder in SharePoint hochgeladen wurden. Wenn Sie diese Option auswählen, kann die Menge der zurückgegebenen Daten erheblich erhöht werden.
- **Alle Versionen von Elementen einschließen**: Wenn Sie SharePoint als Suchspeicherort ausgewählt haben, gibt die Standardsuchabfrage nur die aktuelle Version SharePoint Elemente zurück. Wenn Sie dieses Kontrollkästchen aktivieren, werden die aktuellen und alle vorherigen Versionen von SharePoint Elementen zurückgegeben, wodurch eine wesentlich größere Menge an Daten zur Überprüfung zur Verfügung stehen.

### <a name="data-estimate"></a>Datenschätzung

Die Option " **Erste Schätzung** abrufen" enthält eine Schätzung, wie viele Daten wir erwarten, bevor Ihre Daten automatisch abgerufen werden. Wenn Ihre Schätzung auf der Detailseite der Anforderung angezeigt wird, können Sie die Suchergebnisse anzeigen und eine Vorschau der gefundenen Elemente anzeigen. Wenn die Elemente die erwarteten Ergebnisse darstellen, müssen Sie " **Daten abrufen** " auswählen, um mit dem tatsächlichen Abrufen von Inhaltselementen fortzufahren.

## <a name="refine-your-search"></a>Verfeinern der Suche

Wenn Sie auf der Seite "**Sucheinstellungen**" die Option "**Suche verfeinern**" auswählen, werden Sie bei Auswahl von **"Weiter**" aufgefordert, Details zu persönlichen Attributen und Bedingungen anzugeben, um Ihre Suchergebnisse weiter zu adressieren. Sie können Ergänzungen in einer oder beiden Kategorien vornehmen. Wenn Sie mit der Auswahl in diesem Abschnitt fertig sind, basiert der Datenabruf für die Anforderung auf Ihren Sucheinstellungen.

#### <a name="add-personal-attributes"></a>Persönliche Attribute hinzufügen

Geben Sie Werte in die Textfelder für die Namen, Spitznamen, E-Mail-Adressen und Adressen der betroffenen Person ein. Sie können weitere Bezeichner wie Geburtsdatum oder Telefonnummer hinzufügen, und Textfelder unterstützen mehrere Einträge, die durch ein Semikolon getrennt sind. Wenn Sie fertig sind, wählen Sie **"Weiter** " aus, um mit der Seite **"Bedingungen"** fortzufahren.

#### <a name="conditions"></a>Bedingungen

Wählen Sie die Schaltfläche " **Bedingung hinzufügen** " aus, um zwischen einem Bereich von Bedingungen zu wählen, um Ihre Suche weiter zu adressieren, einschließlich Elementname, Absender- und Empfängernamen, typ des persönlichen Datentyps und ob das Element extern außerhalb Ihrer Organisation freigegeben wurde. Die Textfelder unterstützen mehrere Einträge, die durch ein Semikolon getrennt sind. Wenn Sie fertig sind, wählen Sie **"Weiter** " aus, um Ihre Sucheinstellungen und den Status der Anforderungstypeinstellung zu speichern.

## <a name="next-steps"></a>Nächste Schritte

Nachdem Sie Ihre Anforderung erstellt haben, wird sie auf der Seite mit der Anforderung von Rechten für Betroffene aufgelistet. Weitere Informationen dazu, wie Sie mit der Überprüfung fortfahren können, finden [Sie unter "Daten überprüfen" und "Zusammenarbeiten an Anforderungen](subject-rights-requests-data-review.md)".

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
