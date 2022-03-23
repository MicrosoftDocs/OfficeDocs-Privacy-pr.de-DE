---
title: Priva-Einstellungen konfigurieren
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
- M365-priva-privacy-risk-management
search.appverid:
- MOE150
- MET150
description: Erfahren Sie mehr über die globalen Einstellungsoptionen für Microsoft Priva.
ms.openlocfilehash: 49a6f2112e584ef72bcc0f0433b09a21ccac194c
ms.sourcegitcommit: a9ad5185174a9e8a7eea7583d257e8535c96a2ed
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/23/2022
ms.locfileid: "63746778"
---
# <a name="configure-priva-settings"></a>Priva-Einstellungen konfigurieren

Sie können Einstellungen für Microsoft Priva verwalten, indem Sie das Zahnradsymbol in der oberen rechten Ecke des Bildschirms auswählen. Mit den hier aufgeführten Optionen können Sie allgemeine Einstellungen festlegen und wichtige Eigenschaften anpassen. Diese Seite enthält eine Übersicht über die wichtigsten Einstellungen Kategorien.

## <a name="anonymization"></a>Anonymisierung

Sie können anonymisierte Versionen von Benutzernamen innerhalb der Features für das Datenschutzrisikomanagement für Benutzer in bestimmten Rollen anzeigen. Das Anonymisierungsfeature ersetzt identifizierbare Anzeigenamen durch eine generische Bezeichnung, um die Identitäten Ihrer Benutzer beim Überprüfen vertraulicher Daten zu maskieren. Diese Option gilt nicht für die Lösung für Anträge betroffener Personen.

## <a name="user-notification-emails"></a>Benutzerbenachrichtigungs-E-Mails  

Richtlinien im Datenschutzrisikomanagement ermöglichen es Ihnen, Parameter für die Bewertung potenzieller Datenschutzrisiken in Ihrer Umgebung festzulegen. Wenn eine Richtlinienüberstimmung erkannt wird, kann das Datenschutzrisikomanagement Ihren Benutzern eine E-Mail mit Empfehlungen zu Korrekturmaßnahmen und einem Link zu Datenschutzschulungen senden. In **Einstellungen** können Sie die E-Mail-Benachrichtigungsfunktion des Datenschutzrisikomanagements als Ganzes aktivieren oder deaktivieren. Wenn die Benachrichtigungsfunktion in Einstellungen deaktiviert ist, werden alle E-Mails deaktiviert. Weitere Informationen zu Richtlinien finden Sie unter ["Erstellen von Richtlinien im Datenschutzrisikomanagement"](risk-management-policies.md).

## <a name="teams-collaboration"></a>Zusammenarbeit in Teams  

Integrieren Sie Microsoft Teams Funktionen in Priva-Anträge auf Rechte betroffener Personen, um die Zusammenarbeit mit Projektbeteiligten zu verbessern. Jedes Mal, wenn eine Antragstellerberechtigungsanforderung erstellt wird, wird in Teams ein zugeordnetes Team erstellt. Benutzer können einem Team über die Registerkarte "Mitarbeiter" der Anforderung hinzugefügt werden. Weitere Informationen zu Anträgen auf Rechte von Antragstellern finden [Sie unter "Informationen zu Anforderungen für Priva-Rechte"](subject-rights-requests.md).

## <a name="data-matching"></a>Datenabgleich  

Verwenden Sie diesen Abschnitt, um Datenschemas hochzuladen, die Attribute Ihrer betroffenen Personen beschreiben, wodurch die richtige betroffene Person bei der Suche nach personenbezogenen Daten in Ihrer Microsoft 365 Umgebung identifiziert wird. Schemas und Regelpakete werden im XML-Format erstellt und hochgeladen. Unter **"Hochladen personenbezogener Daten**" können Sie auch personenbezogene Daten übermitteln, die einem bereitgestellten Schema entsprechen. Sie können Eine eigene Datei erstellen und hochladen oder persönliche Daten aus Azure hochladen. Weitere Informationen zu Anträgen auf Rechte von Antragstellern finden [Sie unter "Informationen zu Anforderungen für Priva-Rechte"](subject-rights-requests.md).

## <a name="data-retention-periods"></a>Datenaufbewahrungszeiträume

Diese Einstellung bezieht sich auf Priva-Antragstellerrechteanforderungen. Damit können Sie steuern, wie lange Sie gesammelte Daten und Berichte aufbewahren möchten, die nach dem Schließen der Anforderung generiert wurden. Dies kann auf 30 oder 90 Tage festgelegt werden und gilt für alle von Ihnen erstellten Antragstellerrechteanforderungen. Wir empfehlen, zu überprüfen, ob Ihre Datenaufbewahrungszeiträume den Richtlinien und gesetzlichen Verpflichtungen Ihrer Organisation entsprechen. Erfahren Sie mehr über [das Festlegen der Datenaufbewahrung für Anträge betroffener Personen](subject-rights-requests-reports.md#manage-data-retention).

## <a name="data-review-tags"></a>Tags für die Datenüberprüfung

Datenüberprüfungstags können verwendet werden, um Inhaltselemente zu markieren, die in einer Anforderung zu Betreffrechten abgerufen werden. In diesem Einstellungsbereich können Sie Ihre Tags verwalten. Priva bietet drei Standardtags: **Nachverfolgung**, **Löschen** und **Aktualisieren**. Diese Tagnamen können nicht bearbeitet werden, Aber Sie können eine Beschreibung für diese Tags bereitstellen, die für Ihre Organisation von Bedeutung ist.

Priva bietet auch zwei benutzerdefinierte Tags, die Sie für die Verwendung in Ihrer Organisation benennen und definieren können. Diese werden als **benutzerdefiniertes Tag 1** und **benutzerdefiniertes Tag 2** aufgeführt, bis Sie die Namen bearbeiten.

Führen Sie die folgenden Schritte aus, um Tagnamen und Beschreibungen zu bearbeiten:

- Wählen Sie auf der Priva **Einstellungen** Seite **Datenüberprüfungstags** aus.
- Suchen Sie das Tag in der Liste, die Sie bearbeiten möchten, und wählen **Sie das** Stiftsymbol bearbeiten neben dem Namen aus.
- Nehmen Sie im Flyoutbereich Ihre Änderungen in den verfügbaren Feldern vor. Bei Systemtags können Sie nur die Beschreibung bearbeiten. Bei benutzerdefinierten Tags können Sie den Namen und die Beschreibung bearbeiten.
- Wenn Sie fertig sind, wählen Sie **"Übermitteln** " aus, um Ihre Änderungen zu speichern.

Tag-Einstellungen gelten für alle Antragstellerberechtigungsanforderungen.

Erfahren Sie mehr über [das Anwenden von Tags bei der Überprüfung von Daten für eine Anforderung zu Betreffrechten](subject-rights-requests-data-review.md#apply-tags).

Besuchen Sie **in Einstellungen** **Datenüberprüfungstags**, um Ihre Tags zu überprüfen und zu verwalten.
 
Diese Tags können verwendet werden, um Inhalte anzugeben, die weitere Aufmerksamkeit erfordern, z. B. Inhalte, die möglicherweise manuell gelöscht werden müssen. In diesem Abschnitt der Einstellungen können Sie die Namen und Beschreibungen für benutzerdefinierte Tags bearbeiten. Sie können auch Tagbeschreibungen für die integrierten Tags bearbeiten, die vom System bereitgestellt werden. Namen für Systemtags können nicht geändert werden. Weitere Informationen zu Anträgen auf Rechte von Antragstellern finden Sie unter ["Überprüfen von Daten für einen Antrag auf Rechte von Betroffenen"](subject-rights-requests-data-review.md#step-3-review-data).
