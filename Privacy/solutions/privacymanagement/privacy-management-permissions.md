---
title: Festlegen von Benutzerberechtigungen und Zuweisen von Rollen in der Datenschutzverwaltung
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
description: Erfahren Sie, wie Sie Berechtigungen für die Datenschutzverwaltung einrichten und Benutzern Rollengruppen zuweisen.
ms.openlocfilehash: 52ffb6ee47aea93f906e1356abf61979eca34787
ms.sourcegitcommit: 85e085eb17af8b4efd1f45207445e1b3c3679600
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/19/2021
ms.locfileid: "60478257"
---
# <a name="set-user-permissions-and-assign-roles-in-privacy-management"></a>Festlegen von Benutzerberechtigungen und Zuweisen von Rollen in der Datenschutzverwaltung

Um Mitgliedern Ihrer Organisation Berechtigungen für die Verwendung der Datenschutzverwaltung zu erteilen, weisen Sie sie den entsprechenden Rollengruppen im Microsoft 365 Compliance Center zu. Beachten Sie, dass Rollen, die für die Datenschutzverwaltung spezifisch sind, nicht in Azure Active Directory angezeigt werden.

## <a name="sign-in-and-set-permissions"></a>Anmelden und Festlegen von Berechtigungen

1. Wechseln Sie zum [Microsoft 365 Compliance Center,](https://compliance.microsoft.com/) und wählen Sie im linken Navigationsbereich **Berechtigungen aus.**  
2. Wählen Sie im Compliance **Center-Dropdown** die Option **"Rollen"** aus. Die vollständige Liste der Rollengruppen wird angezeigt.
3. Suchen Sie die Rollengruppe, der Sie einen oder mehrere Benutzer hinzufügen möchten, und aktivieren Sie das Kontrollkästchen links neben dem Gruppennamen. Eine Liste der Datenschutzverwaltungsrollen finden Sie unten.  
4. Wählen Sie im Flyoutbereich für diese Gruppe unter der Kopfzeile **"Mitglieder"** die Option **"Bearbeiten"** aus.  
5. Wählen Sie **"Mitglieder auswählen" aus.** Ein weiteres Flyoutfenster wird angezeigt.
6. Wählen Sie **+Hinzufügen aus,** um einen oder mehrere Benutzer auszuwählen, die der Gruppe hinzugefügt werden sollen.  
7. Aktivieren Sie das Kontrollkästchen neben den Namen, die Sie hinzufügen möchten, und klicken Sie dann unten auf die Schaltfläche **"Hinzufügen".**  
8. Wenn Sie mit dem Zuweisen von Benutzern fertig sind, wählen Sie **"Fertig",** dann **"Speichern"** und dann **"Schließen"** aus.

## <a name="learn-more-about-role-groups-and-roles"></a>Weitere Informationen zu Rollengruppen und Rollen

Abhängig von der Struktur Ihres Teams können Sie Benutzern bestimmte Rollengruppen zuweisen, um unterschiedliche Gruppen von Datenschutzverwaltungsfunktionen zu verwalten. Mitglieder sollten Rollengruppen zugewiesen werden, je nachdem, welche Aufgaben sie ausführen müssen und welche Ebene des Dateizugriffs geeignet ist. Jede Rollengruppe enthält eine oder mehrere Rollen. Diese Rollen können bestimmte Datenschutzverwaltungsaufgaben oder Schlüsselfunktionen betreffen, die für die Mitglieder dieser Gruppe aktiviert oder eingeschränkt sind. Unterschiedliche Benutzer haben daher möglicherweise unterschiedliche Ebenen der Sichtbarkeit und des Zugriffs auf bestimmte Datenschutzverwaltungsfunktionen.

Rollengruppen können bei Bedarf angepasst werden. Um versehentlichen Verlust des Zugriffs zu vermeiden, empfehlen wir, eine Kopie der vorhandenen Rollengruppe zu erstellen, die Sie anpassen möchten, der Kopie einen identifizierbaren Namen zu geben, Ihre Änderungen an der neuen Gruppe vorzunehmen und zu überprüfen und ihr Personen je nach Bedarf zuzuweisen.

## <a name="privacy-management-role-group"></a>Rollengruppe "Datenschutzverwaltung"

Diese Gruppe enthält alle Berechtigungsrollen für die Datenschutzverwaltung in einer einzigen Gruppe. Diese Rollengruppe eignet sich möglicherweise gut für Organisationen, in denen dieselbe Person möglicherweise alle Aufgaben innerhalb der Datenschutzverwaltungslösung ausführt. Die Bereitstellung der Mitgliedschaft in dieser Rollengruppe gewährt diesem Konto vollen Zugriff auf alle Features der Datenschutzverwaltungslösung.

Es wird empfohlen, sicherzustellen, dass immer mindestens ein aktives Mitglied dieser Gruppe vorhanden ist.

Zu den Rollen gehören:

- Fallverwaltung  
- Inhaltsanzeige für Datenklassifizierung  
- Datenklassifizierungslistenanzeige  
- Datenschutzverwaltungsadministrator  
- Analyse des Datenschutzmanagements  
- Untersuchung des Datenschutzmanagements  
- Permanenter Beitrag zum Datenschutzmanagement  
- Temporärer Beitrag zur Datenschutzverwaltung  
- Privacy Management Viewer  
- Administrator für Antragstellerrechteanforderung  
- View-Only Fall

## <a name="privacy-management-administrators-role-group"></a>Rollengruppe "Datenschutzverwaltungsadministratoren"

Mitglieder dieser Rollengruppe haben umfassenden Zugriff auf Datenschutzverwaltungsfunktionen, einschließlich erstellung, Lesen, Aktualisieren und Löschen von Datenschutzverwaltungsrichtlinien, Anträgen auf Rechte betroffener Personen, Berechtigungen für die Datenschutzverwaltung und Datenschutzverwaltungseinstellungen.

Zu den Rollen gehören:

- Fallverwaltung  
- Datenschutzverwaltungsadministrator  
- View-Only Fall

## <a name="privacy-management-analysts-role-group"></a>Rollengruppe "Datenverwaltungsanalysten"

Mitglieder dieser Rollengruppe fungieren als Fallanalysten für das Datenschutzmanagement. Sie können Richtlinienüberstimmungen untersuchen, Dateimetadaten anzeigen und Korrekturmaßnahmen ergreifen. Diese Gruppe kann nicht über den Inhalts-Explorer auf vollständige Dateien zugreifen.

Zu den Rollen gehören:

- Fallverwaltung  
- Datenklassifizierungslistenanzeige  
- Analyse des Datenschutzmanagements  
- View-Only Fall

### <a name="privacy-management-investigators-role-group"></a>Rollengruppe "Datenschutzverwaltungsermittler"

Mitglieder dieser Gruppe fungieren als Datenermittler für die Datenschutzverwaltung. Sie können Richtlinienüberstimmungen untersuchen, den zugehörigen Dateiinhalt anzeigen und Korrekturmaßnahmen ergreifen. Diese Gruppe kann über den Inhalts-Explorer auf Dateien zugreifen.

Zu den Rollen gehören:

- Fallverwaltung  
- Inhaltsanzeige für Datenklassifizierung  
- Datenklassifizierungslistenanzeige  
- Untersuchung des Datenschutzmanagements  
- View-Only Fall

## <a name="privacy-management-viewer-role-group"></a>Rollengruppe "Datenschutzverwaltungsanzeige"

Mitglieder dieser Gruppe können analysebasierte Informationen in der Datenschutzverwaltung anzeigen, z. B. die Übersicht, das Datenprofil und die Berichte zu Antragstelleranfragen.

Zu den Rollen gehören:

- Privacy Management Viewer

## <a name="subject-rights-request-administrators-role-group"></a>Rollengruppe "Administratoren von Antragstellerrechten anfordern"

Mitglieder dieser Gruppe haben Vollzugriff zum Verwalten und Erstellen von Anträgen auf Antragstellerrechte.

Zu den Rollen gehören:

- Administrator für Antragstellerrechteanforderung

## <a name="privacy-management-contributors-role-group"></a>Rollengruppe "Mitwirkende im Datenschutzmanagement"

Mitglieder dieser Gruppe haben Zugriff auf Anträge von Antragstellerrechten, für die sie als Mitarbeiter hinzugefügt wurden.  

Zu den Rollen gehören:

- Temporärer Beitrag zur Datenschutzverwaltung  
- Permanenter Beitrag zum Datenschutzmanagement

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Datenschutzverwaltung](privacy-management-disclaimer.md)