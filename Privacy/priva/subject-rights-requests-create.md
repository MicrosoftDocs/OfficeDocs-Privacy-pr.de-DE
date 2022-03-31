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
ms.openlocfilehash: 9de1047950a556b4456fd4453ea8d860a0a01c38
ms.sourcegitcommit: 16dd1c0320bf1c58ad75edbbe2113fc79013f504
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/25/2022
ms.locfileid: "64404609"
---
# <a name="create-a-subject-rights-request"></a>Erstellen einer Anforderung für Antragstellerrechte

Administratoren der Rechteverwaltung von Antragstellern können neue Anforderungen über privas Hauptseite für Anträge betroffener Personen öffnen. Ein Assistent führt Sie durch den Prozess der Suche nach personenbezogenen Daten über eine betroffene Person und beginnt mit dem Prozess der Erfüllung ihres Antrags.

Sie können auch zusätzliches Material hochladen, damit Priva betroffene Personen basierend auf genau angegebenen Datenwerten identifizieren kann. Weitere Informationen finden Sie unter ["Datenabgleich für Anträge betroffener Personen"](subject-rights-requests-data-match.md).

## <a name="request-types"></a>Anforderungstypen

Priva Subject Rights Requests unterstützt drei verschiedene Arten von Anforderungen:

1. **Zugriff**: Bietet eine Zusammenfassung der persönlichen Informationen der betroffenen Person, die von Ihrer Organisation in Microsoft 365 gespeichert sind.

2. **Export**: Enthält eine Zusammenfassung und eine exportierte Datei mit Inhaltselementen, die die persönlichen Informationen der betroffenen Person enthalten. Dies sind die Elemente, die während der Überprüfung der von Ihren Sucheinstellungen gesammelten Daten überprüft und als **eingeschlossen** markiert wurden.

3. **Markierte Liste für die Nachverfolgung**: Generiert eine Zusammenfassung aller Dateien, die während der Datenüberprüfung markiert wurden, die möglicherweise zusätzliche Aktionen außerhalb von Priva erfordern. Beispielsweise müssen Sie möglicherweise die Löschung der personenbezogenen Informationen der betroffenen Person gemäß ihrem Antrag vereinfachen. Sie können die enthaltenen Tags anzeigen und benutzerdefinierte Tags für Ihre Organisation in [den Priva-Einstellungen](priva-settings.md) einrichten.

## <a name="use-the-subject-rights-request-creation-wizard"></a>Verwenden des Assistenten zum Erstellen von Antragstellerrechten

1. Wählen Sie im [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) im linken Navigationsbereich **"Priva-Antragstellerrechteanforderungen**" aus.

2. Wählen Sie in der oberen rechten Ecke die Option **"Anforderung erstellen"** aus.

3. Fügen Sie auf der Seite " **Informationen zur betroffenen Person** " den Vor- und Nachnamen der betroffenen Person, die E-Mail-Adresse, das Wohnsitzland und ihre Beziehung zu Ihrem Unternehmen an. Wählen Sie dann **Weiter** aus.

4. Wählen Sie auf der Seite "**Speicherorte**" die Microsoft 365 Speicherorte aus, an denen Sie nach den personenbezogenen Daten der betroffenen Person suchen möchten. Abrufen von Details zu [Standorteinstellungen](#choose-locations). Wenn Sie mit der Auswahl von Speicherorten fertig sind, wählen Sie **"Weiter" aus.**

5. Auf der Seite **"Sucheinstellungen"** können Sie die Sucheinstellungen ändern, um ihre Suche zu verfeinern und auszuwählen, ob Sie zuerst eine Schätzung erhalten möchten, bevor Sie Daten abrufen. Sie müssen keine Optionen auf dieser Seite auswählen, was zu einer Standardsuche basierend auf den Speicherorten führt, die Sie im vorherigen Schritt angegeben haben. Weitere Informationen zu Ihren Optionen finden Sie unter [Definieren von Sucheinstellungen](#define-search-settings). Klicken Sie auf **Weiter**, wenn Sie bereit sind fortzufahren.

6. Wählen Sie auf der Seite " **Anforderungstyp** " einen [Anforderungstyp](#request-types) aus, basierend auf dem, was die betroffene Person mit ihren Daten tun möchte: **Zugreifen**, **Exportieren** oder **Tagged-Liste zur Nachverfolgung**. Wenn sich ihr Antrag auf eine bestimmte Datenschutzbestimmungen bezieht, können Sie sie auch aus einer bereitgestellten Liste auswählen, um mehr Kontext hinzuzufügen. Das Festlegen eines Stichtags (erforderlich) erleichtert die Sortierung nach eingehenden oder überfälligen Anforderungen und deren zeitnahe Lösung. Wenn Sie fertig sind, wählen Sie **Weiter**.

7. Bestätigen oder bearbeiten Sie im **Anforderungsnamen** den Namen für diese Anforderung, und fügen Sie eine optionale Beschreibung für den Verweis hinzu. Wählen Sie dann **Weiter** aus.

8. Überprüfen Sie auf der Seite **"Überprüfen" und "Ende** " Ihre Auswahl. Jeder Abschnitt kann bearbeitet werden. Wenn Sie fertig sind, wählen Sie **"Anforderung erstellen"** aus.

Ihre Anforderung verfügt über eine eigene Detailseite und wird auf der Hauptseite "Antragstellerrechte anfordern" aufgeführt. Nach dem Erstellen Ihrer Anforderung sucht Priva nach Übereinstimmungen mit den Informationen der betroffenen Person, die Sie an den von Ihnen angegebenen Speicherorten angegeben haben. Je nach Umfang der Suche kann es mehrere Minuten dauern, bis eine Datenvorkalkulation auf der Detailseite der Anforderung angezeigt wird.

## <a name="choose-locations"></a>Speicherorte wählen

Für jede Anforderung von Betreffrechten können Sie festlegen, dass ihre Suche nach Daten an allen oder bestimmten Speicherorten innerhalb Exchange und SharePoint sucht. Wählen Sie eine Position aus, indem Sie den Umschalter **zur Ein-Position** verschieben. Sie können alle Konten und Websites durchsuchen oder bestimmte Konten oder Websites an jedem Standort festlegen. Lesen Sie unten Details dazu, was an den einzelnen Speicherorten behandelt wird.

- **Exchange**: Diese Option sucht nach Daten in Exchange Postfächern und in einzelnen oder Gruppen-Teams Chats. Sie können alle Exchange Konten in Ihrer Organisation durchsuchen oder **"Konten** auswählen" auswählen, um einzelne Benutzer im Flyoutbereich **Exchange Postfächer** auszuwählen.

- **SharePoint**: Diese Option sucht nach Daten in SharePoint Websites, OneDrive for Business Websites und Teams Kanälen. Sie können alle SharePoint Websites in Ihrer Organisation durchsuchen oder **Websites** auswählen, um einzelne Benutzer im **Flyoutbereich SharePoint Websites** auszuwählen.

Hilfe zum Identifizieren der entsprechenden Suchbegriffe finden Sie in den folgenden Themen:

- **SharePoint Websites und URLs**: [Verwalten von Websites im SharePoint Admin Center](/sharepoint/manage-sites-in-new-admin-center) bietet Anleitungen zum Sortieren und Filtern von Websites und zum Suchen nach einer SharePoint Website. Verwenden Sie dies, um URLs zu suchen, die in das Suchfeld im **Flyoutbereich SharePoint Websites** eingegeben werden.

- **Teams Chats und Kanäle**: [Get-Team](/powershell/module/teams/get-team) zeigt, wie Teams in Microsoft Teams gefunden werden, indem bestimmte Eigenschaften oder Informationen bereitgestellt werden.

- **OneDrive Websites und URLs**: [Informationen zu OneDrive URLs](/onedrive/list-onedrive-urls#about-onedrive-urls) enthält Informationen zum richtigen Format und zu den Eigenschaften für die OneDrive-URL eines Benutzers. Verwenden Sie dies, um OneDrive Websites in Ihrer Suche zu identifizieren.

Wir empfehlen, Ihre Auswahl sorgfältig zu überprüfen, um sicherzustellen, dass Sie die richtige betroffene Person identifizieren. Wenn Sie beispielsweise Postfächer nach Namen durchsuchen und nach mehreren Personen mit ähnlichen Namen suchen, überprüfen Sie den richtigen, bevor Sie sie zu Ihrer Anforderung hinzufügen.

## <a name="define-search-settings"></a>Definieren von Sucheinstellungen

Wenn Sie eine Anforderung für Betreffrechte erstellen, wird basierend auf Ihrer Auswahl auf der Seite " **Speicherorte** " des Erstellungs-Assistenten eine Standardsuche ausgeführt. Wenn Sie eine gezieltere Suche durchführen möchten oder eine Schätzung Ihrer Daten abrufen möchten, bevor Inhaltselemente abgerufen werden, können Sie diese Auswahl auf der Seite **"Sucheinstellungen"** des Assistenten zum Erstellen von Anforderungen treffen.

### <a name="advanced-search-options"></a>Erweiterte Suchoptionen

- **Verfeinern Sie Ihre Suche**: Mit dieser Option können Sie zusätzliche Eigenschaften angeben, um die betroffene Person unter den Daten Ihrer Organisation zu identifizieren. Nachdem Sie diese Option ausgewählt haben, werden Sie aufgefordert, weitere Suchparameter hinzuzufügen. Dies wird unten unter ["Verfeinern Ihrer Suche](#refine-your-search)" erläutert.
- **Von der betroffenen Person erstellte Inhalte einschließen**: Diese Option sucht nach Inhalten, die von der betroffenen Person erstellt wurden. Beispiele hierfür sind Dateien, die von der betroffenen Person erstellt oder in SharePoint hochgeladen wurden. Wenn Sie diese Option auswählen, kann die Zurückgegebene Datenmenge erheblich erhöht werden.
- **Alle Versionen von Elementen** einschließen: Wenn Sie SharePoint als Suchspeicherort ausgewählt haben, gibt die Standardsuchabfrage nur die aktuelle Version von SharePoint Elementen zurück. Wenn Sie dieses Kontrollkästchen aktivieren, werden die aktuelle und alle vorherigen Versionen von SharePoint Elementen zurückgegeben, wodurch eine wesentlich größere Menge an Daten zurückgegeben wird, die Sie überprüfen können.

### <a name="data-estimate"></a>Datenvoranschlag

Die Option **"Erste Schätzung abrufen** " enthält eine Schätzung darüber, wie viele Daten wir erwarten, bevor Ihre Daten automatisch abgerufen werden. Wenn Ihre Schätzung auf der Detailseite der Anforderung angezeigt wird, können Sie die Suchergebnisse anzeigen und eine Vorschau einer Stichprobe der gefundenen Elemente anzeigen. Wenn die Elemente die erwarteten Ergebnisse darstellen, müssen Sie **"Daten abrufen"** auswählen, um mit dem tatsächlichen Abruf von Inhaltselementen fortzufahren.

## <a name="refine-your-search"></a>Verfeinern Der Suchbegriff

Wenn Sie die Suche auf der Seite mit den **Sucheinstellungen** **verfeinern** auswählen, werden Sie bei Auswahl von **"Weiter**" aufgefordert, Details zu persönlichen Attributen und Bedingungen anzugeben, um Ihre Suchergebnisse weiter zu adressieren. Sie können Ergänzungen in einer oder beiden Kategorien vornehmen. Wenn Sie die Auswahl in diesem Abschnitt abgeschlossen haben, basiert der Datenabruf für die Anforderung auf Ihren Sucheinstellungen.

#### <a name="add-personal-attributes"></a>Hinzufügen persönlicher Attribute

Geben Sie Werte in die Textfelder für die Namen, Spitznamen, E-Mail-Adressen und Adressen der betroffenen Person ein. Sie können weitere Bezeichner hinzufügen, z. B. Geburtsdatum oder Telefonnummer, und Textfelder unterstützen mehrere Einträge, die durch ein Semikolon getrennt sind. Wenn Sie fertig sind, wählen Sie **Weiter** aus, um mit der Seite **"Bedingungen"** fortzufahren.

#### <a name="conditions"></a>Bedingungen

Wählen Sie die Schaltfläche " **Bedingung hinzufügen** " aus, um eine Reihe von Bedingungen auszuwählen, um ihre Suche weiter zu adressieren, einschließlich Elementname, Absender- und Empfängernamen, persönlicher Datentyp und ob das Element extern außerhalb Ihrer Organisation freigegeben wurde. Die Textfelder unterstützen mehrere Einträge, die durch ein Semikolon getrennt sind. Wenn Sie fertig sind, wählen Sie **"Weiter** " aus, um Die Sucheinstellungen zu speichern und den Status der Anforderungstypeinstellung zu ändern.

## <a name="next-steps"></a>Nächste Schritte

Nachdem Sie Ihre Anforderung erstellt haben, wird sie auf der Seite für die Anforderung von Antragstellerrechten aufgeführt. Weitere Informationen dazu, wie Sie mit der Überprüfung fortfahren können, finden Sie unter ["Überprüfen von Daten und Zusammenarbeit bei Anforderungen"](subject-rights-requests-data-review.md).

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
