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
ms.openlocfilehash: a6f2fe55600d6cc3018c9d15f05a6d9e459a1486
ms.sourcegitcommit: 3c83e8133a5a71f4e1d76a0b2981ab3ec9cd6602
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/13/2022
ms.locfileid: "66046599"
---
# <a name="configure-priva-settings"></a>Priva-Einstellungen konfigurieren

Sie können einstellungen für Microsoft Priva verwalten, indem Sie das Zahnradsymbol in der oberen rechten Ecke des Bildschirms auswählen. Mit den hier aufgeführten Optionen können Sie allgemeine Einstellungen festlegen und wichtige Eigenschaften anpassen. Diese Seite bietet eine Übersicht über die wichtigsten Einstellungen Kategorien.

## <a name="anonymization"></a>Anonymisierung

Sie können benutzern in bestimmten Rollen anonymisierte Versionen von Benutzernamen innerhalb der Funktionen des Datenschutzrisikomanagements anzeigen. Das Anonymisierungsfeature ersetzt identifizierbare Anzeigenamen durch eine generische Bezeichnung, um die Identitäten Ihrer Benutzer beim Überprüfen vertraulicher Daten zu maskieren. Diese Option gilt nicht für die Lösung "Anfragen zu Rechten betroffener Personen".

## <a name="user-notification-emails"></a>Benutzerbenachrichtigungs-E-Mails  

Mithilfe von Richtlinien im Datenschutzrisikomanagement können Sie Parameter für die Bewertung potenzieller Datenschutzrisiken in Ihrer Umgebung festlegen. Wenn eine Richtlinienübereinstimmung erkannt wird, kann das Datenschutzrisikomanagement eine E-Mail an Ihre Benutzer senden, in der Empfehlungen zu Korrekturmaßnahmen und ein Link zu Datenschutzschulungen angezeigt werden. In **Einstellungen** können Sie die E-Mail-Benachrichtigungsfunktion des Datenschutzrisikomanagements als Ganzes aktivieren oder deaktivieren. Wenn die Benachrichtigungsfunktion in Einstellungen deaktiviert ist, werden alle E-Mails deaktiviert. Weitere Informationen zu Richtlinien finden [Sie unter Erstellen von Richtlinien im Datenschutzrisikomanagement](risk-management-policies.md).

## <a name="teams-collaboration"></a>Zusammenarbeit in Teams  

Integrieren Sie Microsoft Teams Funktionen in Priva Anfragen zu Betroffenenrechten, um die Zusammenarbeit mit den Projektbeteiligten zu verbessern. Wenn Sie das Kontrollkästchen aktivieren, um **Microsoft Teams Funktionen für Anträge betroffener Personen zu aktivieren**, wird automatisch ein zugeordneter Teams Kanal für jede Anforderung erstellt. Benutzer können dem Teams Kanal über die Registerkarte **"Mitarbeiter**" der Anforderung hinzugefügt werden.

Wenn Sie dieses Feature aktivieren, werden Teams Funktionen auf alle Anforderungen angewendet. Wenn Sie das Kontrollkästchen deaktivieren, werden diese Funktionen für alle Anforderungen deaktiviert. Erfahren Sie mehr über [die Zusammenarbeit während des Datenüberprüfungsprozesses](subject-rights-requests-data-review.md#collaboration-for-data-review).

## <a name="data-matching"></a>Datenabgleich  

In diesem Abschnitt können Sie Datenschemas hochladen, die Attribute Ihrer betroffenen Personen beschreiben, wodurch die richtige betroffene Person bei der Suche nach personenbezogenen Daten in Ihrer Microsoft 365 Umgebung identifiziert wird. Schemas und Regelpakete werden im XML-Format erstellt und hochgeladen. Unter **"Hochladen personenbezogener Daten**" können Sie auch personenbezogene Daten übermitteln, die einem bereitgestellten Schema entsprechen. Sie können Eine eigene Datei erstellen und hochladen oder persönliche Daten aus Azure hochladen. Erfahren Sie mehr über [den Datenabgleich für Anträge](subject-rights-requests-data-match.md) betroffener Personen.

## <a name="data-retention-periods"></a>Aufbewahrungszeiträume für Daten

Diese Einstellung bezieht sich auf Priva Anfragen zu Betroffenenrechten. Es ermöglicht Ihnen, Ihre Einstellung für die Dauer zu steuern, wie lange Sie gesammelte Daten und Berichte aufbewahren möchten, die nach dem Schließen der Anforderung generiert wurden. Dies kann auf 30 oder 90 Tage festgelegt werden und gilt für alle von Ihnen erstellten Anfragen zu Rechten betroffener Personen. Es wird empfohlen, zu überprüfen, ob ihre Aufbewahrungszeiträume den Richtlinien und gesetzlichen Verpflichtungen Ihrer Organisation entsprechen. Erfahren Sie mehr über die [Datenaufbewahrung für Anfragen zu Rechten betroffener Personen](subject-rights-requests-reports.md#retention-periods-for-reports-and-data).

## <a name="data-review-tags"></a>Datenüberprüfungstags

Datenüberprüfungstags können verwendet werden, um Inhaltselemente zu markieren, die in einer Anforderung zu Rechten betroffener Personen abgerufen werden. Mit diesem Einstellungsbereich können Sie Ihre Tags verwalten. Priva stellt drei Standardtags bereit: **"Nachverfolgung**", **"Löschen"** und **"Aktualisieren**". Diese Tagnamen können nicht bearbeitet werden, Aber Sie können eine Beschreibung für diese Tags bereitstellen, die für Ihre Organisation von Bedeutung ist.

Priva bietet auch zwei benutzerdefinierte Tags, die Sie für die Verwendung Ihrer Organisation benennen und definieren können. Diese werden als **benutzerdefiniertes Tag 1** und **benutzerdefiniertes Tag 2** aufgeführt, bis Sie die Namen bearbeiten.

Führen Sie die folgenden Schritte aus, um Tagnamen und Beschreibungen zu bearbeiten:

- Wählen Sie auf der Seite Priva **Einstellungen** die Option **"Datenüberprüfungstags**" aus.
- Suchen Sie das Tag in der Liste, die Sie bearbeiten möchten, und wählen Sie das Symbol "Bleistift **bearbeiten** " neben dem Namen aus.
- Nehmen Sie im Flyoutbereich Ihre Änderungen in den verfügbaren Feldern vor. Für Systemtags können Sie nur die Beschreibung bearbeiten. Bei benutzerdefinierten Tags können Sie den Namen und die Beschreibung bearbeiten.
- Wenn Sie fertig sind, wählen Sie **"Absenden** " aus, um Ihre Änderungen zu speichern.

Tageinstellungen gelten für alle Anfragen zu Rechten betroffener Personen.

Erfahren Sie mehr über [das Anwenden von Tags beim Überprüfen von Daten für eine Anfrage zu Rechten betroffener Personen](subject-rights-requests-data-review.md#apply-tags).