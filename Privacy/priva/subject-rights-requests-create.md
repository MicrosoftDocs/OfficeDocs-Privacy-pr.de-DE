---
title: Erstellen einer Anforderung und Definieren von Sucheinstellungen in Anträgen betroffener Personen
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
description: Erfahren Sie, wie Sie eine neue Anforderung zu Rechten betroffener Personen erstellen und Sucheinstellungen in Microsoft Priva Anfragen zu Betroffenenrechten definieren.
ms.openlocfilehash: 7314fefa370b24bcb215a99b67b74c13b8b27613
ms.sourcegitcommit: 3c83e8133a5a71f4e1d76a0b2981ab3ec9cd6602
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/13/2022
ms.locfileid: "66046639"
---
# <a name="create-a-request-and-define-search-settings"></a>Erstellen einer Anforderung und Definieren von Sucheinstellungen

**In diesem Artikel**: Erfahren Sie, wie Sie eine Anforderung in Priva erstellen, um mit der Erfüllung einer Anfrage zu Rechten betroffener Personen zu beginnen. Grundlegendes zu den Sucheinstellungen für den Datenabruf und zum Verfeinern der Suche.

Benutzer, die eine Rolle in der Rollengruppe "Antragstellerberechtigungsadministratoren" außer der schreibgeschützten Rolle ([siehe Priva Berechtigungen](priva-permissions.md)) besitzen, können eine Anforderung in "Anfragen zu Rechten betroffener Personen" erstellen. Ein geführter Prozess führt Sie durch die Einstellungen für die Suche nach personenbezogenen Daten zu einer betroffenen Person und den Beginn des Prozesses zur Erfüllung ihrer Anfrage.

## <a name="request-types"></a>Anforderungstypen

Priva Anfragen zu Betroffenenrechten unterstützt drei verschiedene Arten von Anforderungen:

1. **Zugriff**: Bietet eine Zusammenfassung der persönlichen Daten der betroffenen Person, die von Ihrer Organisation in Microsoft 365 aufbewahrt werden.

2. **Export**: Enthält eine Zusammenfassung und eine exportierte Datei mit Inhaltselementen, die die persönlichen Informationen der betroffenen Person enthalten. Dies sind die Elemente, die während der Überprüfung der von Ihren Sucheinstellungen gesammelten Daten überprüft und als **enthalten** gekennzeichnet wurden.

3. **Tagged list for follow up**: Generates a summary of any files that were tagged during data review that may require additional action outside of Priva. Möglicherweise müssen Sie die Löschung der personenbezogenen Daten der betroffenen Person gemäß deren Anfrage vereinfachen. Sie können die enthaltenen Tags anzeigen und benutzerdefinierte Tags für Ihre Organisation in [Priva Einstellungen](priva-settings.md) einrichten.

## <a name="getting-started-with-your-first-request"></a>Erste Schritte mit Ihrer ersten Anforderung

Wenn Sie eine Testversion oder ein Abonnement von Anfragen zu Rechten betroffener Personen starten, bieten wir eine einfache, vordefinierte Einrichtung für Ihre erste Anforderung, die Standardeinstellungen verwendet. Dieses Setup kann Ihnen helfen, den Workflow für die Anforderung von Schutzrechten zu erkunden und sich mit dessen Funktionalität vertraut zu machen.

Wenn Sie zum ersten Mal auf der Seite "Anfragen zu Rechten betroffener Personen" eintreffen, wird oben ein Banner mit einer **Erste Schritte** Schaltfläche angezeigt. Wenn ein Benutzer diese Schaltfläche auswählt, wird ein Flyoutbereich mit den Informationen dieses Benutzers angezeigt, die in den Namen- und E-Mail-Feldern bereits ausgefüllt sind, und alle Standardeinstellungen werden angezeigt.

**Untersuchen der Anforderungsfunktionalität mit Ihren Informationen**: Das Ausprobieren einer Anfrage zu Rechten betroffener Personen basierend auf Ihren eigenen Informationen kann Ihnen dabei helfen, sich mit dem Navigieren in jeder Phase des Prozesses vertraut zu machen. Sie werden sehen, was eine Standardsuche ergibt, und können üben, die Ergebnisse zu verfeinern, indem Sie die Sucheinstellungen anpassen. Auf der Registerkarte **"Gesammelte Daten** " können Sie Elemente im Vorschaubereich rechts überprüfen und das Bearbeiten von Text, das Anwenden von Tags, das Eingeben von Notizen und das Markieren von Elementen üben, die für den Abschlussbericht ein- oder ausgeschlossen werden sollen (details finden Sie unter ["Daten überprüfen" für eine Anfrage zu Rechten](subject-rights-requests-data-review.md) betroffener Personen).

- Sie müssen Ihre Informationen nicht verwenden, um Ihre erste Anforderung zu erstellen. Wenn Sie bereit sind, eine Anforderung für eine betroffene Person zu starten, ersetzen Sie Ihren Namen und Ihre E-Mail-Adresse durch die Informationen der betroffenen Person.

Wenn Sie alle Einstellungen akzeptieren und die Anforderung erstellen möchten, wählen Sie **"Erstellen**" aus. Der Bereich wird geschlossen, und Ihre neue Anforderung wird auf der Seite **"Anfragen zu Rechten betroffener Personen"** aufgeführt. Um eine der Standardeinstellungen vor dem Erstellen der Anforderung zu ändern, wählen Sie **"Anforderungsdetails bearbeiten"** aus, wodurch Sie in den [Assistenten zum Erstellen von Anträgen für Antragstellerrechte](#create-a-request) gelangen.

> [!NOTE]
> Jede Anforderung, die Sie erstellen, zählt zu Ihrer Test- oder kostenpflichtigen Abonnementzuweisung, unabhängig davon, welche Informationen der betroffenen Person für die Anforderung verwendet werden. Der standardmäßige 30-Tage-Zeitraum für die Datenaufbewahrung gilt, nachdem die Anforderung geschlossen wurde. Erfahren Sie, wie Sie [Aufbewahrungszeiträume für Anfragen zu Rechten betroffener Personen](subject-rights-requests-reports.md#retention-periods-for-reports-and-data) ändern.

## <a name="create-a-request"></a>Erstellen einer Anforderung

Führen Sie die folgenden Schritte aus, um mit der Erfüllung einer Anfrage zu Rechten betroffener Personen zu beginnen:

1. Wählen Sie im [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/) im linken Navigationsbereich **Priva Anfragen zu Betroffenenrechten** aus.

2. Wählen Sie in der oberen rechten Ecke des Bildschirms die Option **"Anforderung erstellen" aus**.

3. Geben Sie auf der Seite " **Datensubjektinformationen** " die Vor- und Nachnamen und die E-Mail-Adresse der betroffenen Person ein. Wählen Sie **"Wohnsitz hinzufügen"** aus, um das Wohnsitzland der betroffenen Person auszuwählen. Wählen Sie die Option aus, die angibt, wie die betroffene Person mit Ihrer Organisation verknüpft ist (z. B. Kunde oder aktueller Mitarbeiter), und wählen Sie **"Weiter** " aus, um zum nächsten Schritt zu wechseln.

4. Entscheiden Sie auf der Seite **"Speicherorte** ", wo Sie nach den Informationen der betroffenen Person suchen möchten. Wählen Sie eine oder beide der folgenden Speicherorte aus, indem Sie den Statusschalter neben jeder Option **in die** Ein-Position verschieben:

   - **Exchange**: Suchen Sie in Exchange Postfächern und in Einzel- oder Gruppenchats Teams nach Daten. Sie können alle Exchange Konten in Ihrer Organisation durchsuchen oder **"Konten auswählen**" auswählen, um einzelne Benutzer aus dem **Flyoutbereich Exchange Postfächer** auszuwählen.

   - **SharePoint**: Suchen Sie nach Daten in SharePoint Websites, OneDrive for Business Websites und Teams Kanälen. Sie können alle SharePoint Websites in Ihrer Organisation durchsuchen oder **Websites auswählen**, um einzelne Benutzer aus dem **Flyoutbereich SharePoint Websites** auszuwählen.

> [!TIP]
> Hilfe zum Identifizieren der entsprechenden Suchbegriffe finden Sie in den folgenden Themen:
> - SharePoint Websites und URLs: [Verwalten von Websites im SharePoint Admin Center](/sharepoint/manage-sites-in-new-admin-center) bietet Anleitungen zum Sortieren und Filtern von Websites und zum Suchen nach einer SharePoint Website. Verwenden Sie diese Option, um IM Suchfeld im **Flyoutbereich SharePoint Websites** NACH URLs zu suchen.
> - Teams Chats und Kanäle: [Get-Team](/powershell/module/teams/get-team) zeigt, wie Sie Teams in Microsoft Teams finden, indem bestimmte Eigenschaften oder Informationen bereitgestellt werden.
> - OneDrive Websites und URLs: [Informationen zu OneDrive URLs](/onedrive/list-onedrive-urls#about-onedrive-urls) enthält Informationen über das richtige Format und die Eigenschaften für die OneDrive URL eines Benutzers. Verwenden Sie diese Informationen, um OneDrive Websites in Ihrer Suche zu identifizieren.

5. Auf der Seite **"Sucheinstellungen definieren** " können Sie Änderungen an der Standardsuche vornehmen, indem Sie unter verschiedenen erweiterten Suchoptionen auswählen. Hier können Sie auch auswählen, ob sie zuerst eine Schätzung erhalten möchten, bevor Daten automatisch zurückgegeben werden. Wenn Sie eine dieser Optionen auswählen, fahren Sie mit der Auswahl von **"Weiter** " mit weiteren Bildschirmen fort. Details finden Sie unten unter ["Sucheinstellungen definieren"](#defining-search-settings) . Wenn Sie Ihre Suche nicht ändern möchten, lassen Sie alle Optionen leer, und wählen Sie **"Weiter** " aus, um zur nächsten Stufe zu wechseln.

6. Wählen **Sie auf der Seite "Typ der Anforderung auswählen**" den Anforderungstyp aus: **Access**-, **Export****- oder Tagged-Liste zur Nachverfolgung** ([siehe Beschreibungen oben](#request-types)). Geben Sie an, ob sich die Anforderung auf eine Datenschutzverordnung bezieht. Überprüfen oder ändern Sie den Fertigstellungstermin, der standardmäßig zwei Wochen nach dem Erstellungsdatum der Anforderung endet. Wählen Sie dann **Weiter** aus.

7. Auf der Seite **"Bestätigen oder Bearbeiten des Namens dieser Anforderung** " können Sie den Anzeigenamen, der für die Anforderung bereitgestellt wird, beibehalten oder bearbeiten und eine optionale Beschreibung eingeben. Wählen Sie dann **Weiter** aus.

8. Überprüfen Sie auf der Seite **"Überprüfen und fertig stellen** " die Zusammenfassung der Informationen, die Sie während der vorherigen Schritte eingegeben haben. Jedes Feld kann bearbeitet werden, indem Sie in jedem Abschnitt den **Link "Bearbeiten"** auswählen. Wenn Sie fertig sind, wählen Sie **"Anforderung erstellen"** aus.

Nachdem die Anforderung erstellt wurde, wird ein Bestätigungsbildschirm angezeigt. Wählen Sie **"Fertig"** aus, um zum Hauptbildschirm "Anfragen zu Rechten betroffener Personen" zurückzukehren. Die neue Anforderung wird am Anfang Ihrer Liste der Anforderungen aufgeführt. Wählen Sie es aus der Liste aus, um mit dem Überprüfen und Durcharbeiten der Statusstufen zu beginnen.

#### <a name="what-happens-after-your-request-is-created"></a>Was geschieht, nachdem Ihre Anforderung erstellt wurde?

Wir berechnen eine Schätzung der Datenmenge, die basierend auf Ihren Suchparametern erwartet wird, beginnt sofort. Besuchen Sie die Detailseite Ihrer Anforderung in wenigen Minuten bis zu einer Stunde, um die Ergebnisse der Schätzung zu sehen und zu sehen, ob die Anforderung in die nächste Phase verschoben wurde. Ihre Anforderung wechselt automatisch von der **Datenschätzung** zum **Datenabruf** , mit Ausnahme der folgenden Umstände:

 - Wenn Sie in Schritt 5, **Definieren von Sucheinstellungen**, ausgewählt haben, dass sie zuerst eine Daten-Esimtae erhalten sollen, können Sie Details zu Ihrer Suche anzeigen und Änderungen an Ihrer Suche vornehmen, bevor alle Daten abgerufen werden. Wenn Sie bei der **Datenschätzung** angehalten haben, müssen Sie manuell zur nächsten Phase des **Datenabrufs** wechseln.
 
 - Wenn Sie sich nicht für die Datenschätzung entschieden haben, aber wir vorhersagen, dass Ihre Suche eine große Datenmenge ergeben wird, wird oben in Ihrer Anforderung eine Meldungsleiste mit einem Link zum Bearbeiten der Suche angezeigt, bevor Sie mit dem **Datenabruf** fortfahren.

Besuchen Sie [die Datenschätzung und den Abruf](subject-rights-requests-data-retrieval.md), um mehr über diese Phasen zu erfahren.

## <a name="defining-search-settings"></a>Definieren von Sucheinstellungen

Wenn Sie eine Anforderung zu Rechten betroffener Personen erstellen, wird eine Standardsuche basierend auf Ihrer Auswahl auf der Seite " **Speicherorte** " des Erstellungs-Assistenten ausgeführt. Wenn Sie eine gezieltere Suche durchführen möchten oder eine Schätzung Ihrer Daten abrufen möchten, bevor Inhaltselemente abgerufen werden, können Sie diese Auswahl auf der Seite " **Sucheinstellungen"** des Assistenten zum Erstellen von Anforderungen treffen.

### <a name="advanced-search-options"></a>Erweiterte Suchoptionen

- **Verfeinern Sie Ihre Suche**: Mit dieser Option können Sie zusätzliche Eigenschaften angeben, um die betroffene Person unter den Daten Ihrer Organisation zu identifizieren. Nachdem Sie diese Option ausgewählt haben, werden Sie aufgefordert, weitere Suchparameter hinzuzufügen, die unten unter ["Verfeinern der Suche](#refining-your-search)" erläutert werden.
- **Inhalte einschließen, die von der betroffenen Person erstellt wurden**: Diese Option sucht nach Inhalten, die von der betroffenen Person erstellt wurden. Beispiele hierfür sind Dateien, die von der betroffenen Person erstellt oder in SharePoint hochgeladen wurden. Wenn Sie diese Option auswählen, kann die Menge der zurückgegebenen Daten erheblich erhöht werden.
- **Alle Versionen von Elementen einschließen**: Wenn Sie SharePoint als Suchspeicherort ausgewählt haben, gibt die Standardsuchabfrage nur die aktuelle Version SharePoint Elemente zurück. Wenn Sie dieses Kontrollkästchen aktivieren, werden die aktuellen und alle vorherigen Versionen von SharePoint Elementen zurückgegeben, wodurch eine wesentlich größere Menge an Daten zur Überprüfung zur Verfügung stehen.

> [!TIP]
> Sie können zusätzliches Material hochladen, damit Priva betroffene Personen anhand exakter Datenwerte identifizieren können. Weitere Informationen finden Sie unter [Datenabgleich für Anfragen zu Rechten betroffener Personen](subject-rights-requests-data-match.md).

### <a name="data-estimate"></a>Datenschätzung

Die Option " **Erste Schätzung** abrufen" enthält eine Schätzung, wie viele Daten wir erwarten, bevor Ihre Daten automatisch abgerufen werden. Wenn Ihre Schätzung auf der Detailseite der Anforderung angezeigt wird, können Sie die Suchergebnisse anzeigen und eine Vorschau der gefundenen Elemente anzeigen. Wenn die Elemente die erwarteten Ergebnisse darstellen, müssen Sie " **Daten abrufen** " auswählen, um mit dem tatsächlichen Abrufen von Inhaltselementen fortzufahren. Erhalten Sie weitere Details zur [Datenschätzungsphase](subject-rights-requests-data-retrieval.md).

## <a name="refining-your-search"></a>Verfeinern der Suche

Wenn Sie auf der Seite "**Sucheinstellungen**" die Option "**Suche verfeinern**" auswählen oder wenn Sie in der **Datenschätzungsphase** angehalten haben und ihre Suchabfrage bearbeiten möchten, werden Sie aufgefordert, Details zu persönlichen Attributen und Bedingungen anzugeben, um Ihre Suchergebnisse weiter zu adressieren. Sie können Ergänzungen in einer oder beiden Kategorien vornehmen. Wenn Sie mit der Auswahl in diesem Abschnitt fertig sind, basiert der Datenabruf für die Anforderung auf Ihren Sucheinstellungen.

Die unten erläuterten Details sind auch das, was Sie angeben müssen, wenn Sie in der **Datenschätzungsphase** angehalten haben und ihre Suchabfrage bearbeiten möchten. 

#### <a name="add-personal-attributes"></a>Persönliche Attribute hinzufügen

Geben Sie Werte in die Textfelder für die Namen, Spitznamen, E-Mail-Adressen und Adressen der betroffenen Person ein. Sie können weitere Bezeichner wie Geburtsdatum oder Telefonnummer hinzufügen, und Textfelder unterstützen mehrere Einträge, die durch ein Semikolon getrennt sind. Wenn Sie fertig sind, wählen Sie **"Weiter** " aus, um mit der Seite **"Bedingungen"** fortzufahren.

#### <a name="conditions"></a>Bedingungen

Wählen Sie die Schaltfläche " **Bedingung hinzufügen** " aus, um zwischen einem Bereich von Bedingungen zu wählen, um Ihre Suche weiter zu adressieren, einschließlich Elementname, Absender- und Empfängernamen, typ des persönlichen Datentyps und ob das Element extern außerhalb Ihrer Organisation freigegeben wurde. Die Textfelder unterstützen mehrere Einträge, die durch ein Semikolon getrennt sind. Wenn Sie fertig sind, wählen Sie **"Weiter** " aus, um Ihre Sucheinstellungen und den Status der Anforderungstypeinstellung zu speichern.

## <a name="next-steps"></a>Nächste Schritte

Nachdem Sie Ihre Anforderung erstellt haben, wird sie auf der Seite mit der Anforderung von Rechten für Betroffene aufgelistet. Weitere Informationen dazu, wie Sie mit der Überprüfung fortfahren können, finden [Sie unter "Daten überprüfen" und "Zusammenarbeiten an Anforderungen](subject-rights-requests-data-review.md)".

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
