---
title: Festlegen von Benutzerberechtigungen und Zuweisen von Rollen in Microsoft Priva
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
- M365-priva-subject-rights-requests
search.appverid:
- MOE150
- MET150
description: Erfahren Sie, wie Sie Microsoft Priva Berechtigungen einrichten und Benutzer Rollengruppen zuweisen.
ms.openlocfilehash: eca08327e2db909475dbf4c072b8f6843de3d57b
ms.sourcegitcommit: 3c27ecf7c86c8a3db38cae8819fc090eed192b4f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/25/2022
ms.locfileid: "65678222"
---
# <a name="set-user-permissions-and-assign-roles-in-microsoft-priva"></a>Festlegen von Benutzerberechtigungen und Zuweisen von Rollen in Microsoft Priva

Um Mitgliedern Ihrer Organisation Berechtigungen zur Verwendung von Microsoft Priva zu erteilen, weisen Sie sie den entsprechenden Rollengruppen im Microsoft Purview-Complianceportal zu.

> [!NOTE]
> Die meisten Priva Rollen sind derzeit als "Datenschutzverwaltung" festgelegt. Eine vollständige Liste finden Sie unten. Rollen, die für Priva spezifisch sind, werden in Azure Active Directory nicht angezeigt.

## <a name="sign-in-and-set-permissions"></a>Anmelden und Festlegen von Berechtigungen

1. Wechseln Sie zum [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/), und wählen Sie im linken Navigationsbereich **"Berechtigungen**" aus.  
2. Wählen Sie im Dropdownmenü **Microsoft Purview Lösungen** **die Option "Rollen" aus**. Die vollständige Liste der Rollengruppen wird angezeigt.
3. Suchen Sie die Rollengruppe, der Sie einen oder mehrere Benutzer hinzufügen möchten (siehe Beschreibungen der Rollengruppe unten), und aktivieren Sie das Kontrollkästchen links neben dem Gruppennamen.
4. Wählen Sie im Flyoutbereich für diese Gruppe unter der Kopfzeile " **Mitglieder** " die Option **"Bearbeiten"** aus.  
5. Wählen Sie im Flyoutbereich im linken Navigationsbereich " **Mitglieder auswählen** " aus. Ein weiteres Flyoutfenster wird angezeigt.
6. Wählen Sie **+Hinzufügen** aus, um einen oder mehrere Benutzer auszuwählen, die der Gruppe hinzugefügt werden sollen.  
7. Aktivieren Sie das Kontrollkästchen neben den Namen, die Sie hinzufügen möchten, und wählen Sie dann unten die Schaltfläche **"Hinzufügen** " aus.  
8. Wenn Sie mit dem Zuweisen von Benutzern fertig sind, wählen Sie **"Fertig**", dann **"Speichern"** und dann **"Schließen**" aus.

## <a name="learn-more-about-role-groups-and-roles"></a>Weitere Informationen zu Rollengruppen und Rollen

Je nach Struktur Ihres Teams haben Sie Optionen, um Benutzern bestimmte Rollengruppen zuzuweisen, um verschiedene Gruppen von Priva-Features zu verwalten. Mitglieder sollten Rollengruppen zugewiesen werden, je nachdem, welche Aufgaben sie ausführen müssen und welche Ebene des Dateizugriffs geeignet ist. Jede Rollengruppe enthält eine oder mehrere Rollen. Diese Rollen können sich auf bestimmte Priva Aufgaben oder Schlüsselfunktionen beziehen, die für die Mitglieder dieser Gruppe aktiviert oder eingeschränkt sind. Verschiedene Benutzer können daher unterschiedliche Ebenen der Sichtbarkeit und des Zugriffs auf bestimmte Priva Features haben.

Rollengruppen können bei Bedarf angepasst werden. Um versehentlichen Zugriffsverlust zu vermeiden, empfiehlt es sich, eine Kopie der vorhandenen Rollengruppe zu erstellen, die Sie anpassen möchten, der Kopie einen identifizierbaren Namen zu geben, Ihre Änderungen an der neuen Gruppe vorzunehmen und zu überprüfen und ihr entsprechend Personen zuzuweisen.

## <a name="privacy-management-role-group"></a>Rollengruppe "Datenschutzverwaltung"

Diese Gruppe enthält alle Priva Berechtigungsrollen in einer einzelnen Gruppe. Diese Rollengruppe eignet sich möglicherweise gut für Organisationen, in denen dieselbe Person möglicherweise alle Aufgaben erfüllt. Wenn Sie die Mitgliedschaft in dieser Rollengruppe bereitstellen, erhält dieses Konto vollumfänglichen Zugriff auf alle Features von Priva, für die Sie eine Lizenz besitzen.

Es wird empfohlen sicherzustellen, dass immer mindestens ein aktives Mitglied dieser Gruppe vorhanden ist.

Zu den Rollen gehören:

- Fallverwaltung  
- Inhaltsanzeige der Datenklassifizierung  
- Datenklassifizierungslistenanzeige  
- Datenschutzverwaltung Admin  
- Analyse des Datenschutzmanagements  
- Datenschutzverwaltungsuntersuchung  
- Permanenter Beitrag zur Datenschutzverwaltung  
- Temporärer Beitrag zur Datenschutzverwaltung  
- Datenschutzverwaltungsanzeige  
- Antrag auf Rechte betroffener Personen Admin  
- View-Only Fall

## <a name="privacy-management-administrators-role-group"></a>Rollengruppe "Datenschutzverwaltungsadministratoren"

Mitglieder dieser Rollengruppe haben umfassenden Zugriff auf Priva Funktionen, einschließlich Erstellen, Lesen, Aktualisieren und Löschen von Richtlinien für das Datenschutzrisikomanagement, Anfragen zu Rechten betroffener Personen, Berechtigungen und Einstellungen.

Zu den Rollen gehören:

- Fallverwaltung  
- Datenschutzverwaltung Admin  
- View-Only Fall

## <a name="privacy-management-analysts-role-group"></a>Rollengruppe "Datenschutzverwaltungsanalysten"

Mitglieder dieser Rollengruppe fungieren als Fallanalysten. Sie können Richtlinienübereinstimmungen untersuchen, Dateimetadaten anzeigen und Abhilfemaßnahmen ergreifen. Diese Gruppe kann nicht über den Inhalts-Explorer auf vollständige Dateien zugreifen.

Zu den Rollen gehören:

- Fallverwaltung  
- Datenklassifizierungslistenanzeige  
- Analyse des Datenschutzmanagements  
- View-Only Fall

### <a name="privacy-management-investigators-role-group"></a>Rollengruppe "Datenschutzverwaltungsermittler"

Mitglieder dieser Gruppe fungieren als Datenermittler. Sie können Richtlinienübereinstimmungen untersuchen, den zugehörigen Dateiinhalt anzeigen und Abhilfemaßnahmen ergreifen. Diese Gruppe kann über den Inhalts-Explorer auf Dateien zugreifen.

Zu den Rollen gehören:

- Fallverwaltung  
- Inhaltsanzeige der Datenklassifizierung  
- Datenklassifizierungslistenanzeige  
- Datenschutzverwaltungsuntersuchung  
- View-Only Fall

## <a name="privacy-management-viewer-role-group"></a>Rollengruppe "Datenschutzverwaltungsanzeige"

Mitglieder dieser Gruppe können analytische Informationen in Priva anzeigen, z. B. die Übersicht, das Datenprofil und die Berichte zu Anträgen betroffener Personen.

Zu den Rollen gehören:

- Datenschutzverwaltungsanzeige

## <a name="subject-rights-request-administrators-role-group"></a>Rollengruppe "Antragstellerberechtigungsanforderungsadministratoren"

Mitglieder dieser Gruppe haben Vollzugriff auf die Verwaltung und Erstellung von Anfragen zu Rechten betroffener Personen.

Zu den Rollen gehören:

- Antrag auf Rechte betroffener Personen Admin

## <a name="privacy-management-contributors-role-group"></a>Rollengruppe "Datenschutzverwaltungsmitwirkende"

Mitglieder dieser Gruppe haben Zugriff auf Anträge betroffener Rechte, für die sie als Mitarbeiter hinzugefügt wurden.  

Zu den Rollen gehören:

- Temporärer Beitrag zur Datenschutzverwaltung  
- Permanenter Beitrag zur Datenschutzverwaltung

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)