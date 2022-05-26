---
title: Erste Schritte mit Priva
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
- MET150fcf
description: Erfahren Sie, wie Sie Microsoft Priva für Ihre Organisation einrichten, Rollen und Berechtigungen festlegen und wichtige Einstellungen konfigurieren.
ms.openlocfilehash: 945cbfd2625be50cb89eeaa8fe09e0effaea79d5
ms.sourcegitcommit: 3c27ecf7c86c8a3db38cae8819fc090eed192b4f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/25/2022
ms.locfileid: "65678212"
---
# <a name="get-started-with-priva"></a>Erste Schritte mit Priva

Wenn Sie bereit sind, mit der Verwendung von Microsoft Priva zu beginnen, um Ihre Organisation bei der Identifizierung und Entschärfung von Datenschutzrisiken zu unterstützen, führen Sie die folgenden Schritte aus, um die Einrichtung zu erleichtern.

## <a name="confirm-subscriptions-and-licensing"></a>Bestätigen von Abonnements und Lizenzierung

Priva ist innerhalb der [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/) verfügbar und kann von Organisationen mit den folgenden Lizenzen erworben werden:

- Microsoft 365 E3, E5, A3, A5
- Office 365 E1, E3, E5, A1, A3, A5

Priva bietet Lizenzierungsoptionen für zwei verschiedene Lösungen: Priva Datenschutz-Risikomanagement und Priva Anfragen zu Betroffenenrechten. Diese können einzeln oder gemeinsam erworben werden. Beim Abrufen von Lizenzen für Anträge betroffener Personen können Sie die entsprechende Lizenzierungsstufe für die Anzahl der Anforderungen auswählen, die Sie behandeln müssen. Sie können jederzeit zusätzliche Anfragen erwerben.

Ausführliche Informationen zur Lizenzierung finden Sie unter: [Microsoft 365-Lizenzierungsrichtlinien für Sicherheit und Compliance](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#microsoft-priva).

> [!Note]
> Priva ist für Kunden von US Government Community (GCC) Moderate, GCC High oder Department of Defense (DoD) nicht verfügbar.

### <a name="start-a-free-trial"></a>Erste Schritte mit einer kostenlosen Testversion

Verwenden Sie ein kostenloses Testabonnement, um alle Features und Funktionen beider Priva-Lösungen zu erkunden. Erfahren Sie, wie Sie sich für die [Priva-Testversion](priva-trial.md) registrieren.

## <a name="enable-the-microsoft-365-audit-log"></a>Aktivieren des Microsoft 365 Überwachungsprotokolls

Microsoft 365 Überwachungsprotokolle sind eine Zusammenfassung aller Aktivitäten in Ihrer Organisation. Richtlinien für das Datenschutzrisikomanagement können diese Aktivitäten verwenden, um Richtlinieneinblicke zu generieren.

Möglicherweise sind in Ihrer Organisation überwachungsprotokolle bereits aktiviert. Wenn Sie sie zum ersten Mal verwenden müssen, finden [Sie unter Aktivieren oder Deaktivieren der Überwachungsprotokollsuche](/microsoft-365/compliance/turn-audit-log-search-on-or-off) schrittweise Anleitungen zum Aktivieren der Überwachung. Daraufhin teilt Ihnen eine Meldung mit, dass das Überwachungsprotokoll vorbereitet wird und Sie in ein paar Stunden nach Abschluss der Vorbereitung eine Suche durchführen können. Sie müssen diese Aktion nur einmal ausführen. Weitere Informationen zur Verwendung des Microsoft 365 Überwachungsprotokolls finden [Sie unter Durchsuchen des Überwachungsprotokolls](/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance).

## <a name="set-user-permissions-and-assign-roles"></a>Festlegen von Benutzerberechtigungen und Zuweisen von Rollen

Priva verwendet ein Berechtigungsmodell für die rollenbasierte Zugriffssteuerung (Role-Based Access Control, RBAC). Nur Benutzer, denen eine Rolle zugewiesen ist, können auf Priva zugreifen, und die von jedem Benutzer zulässigen Aktionen werden nach Rollentyp eingeschränkt.

Ihr globaler Administrator verfügt über Berechtigungen für den Zugriff auf Priva und das Zuweisen anderer Benutzer zu Rollen. Sie können sich anmelden und Benutzerberechtigungen im [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/) für Priva festlegen. Für einen schnellen Einstieg verfügt die Rollengruppe "Datenschutzverwaltung" über Berechtigungen für den Zugriff auf alle Features von Priva. Diese Gruppe eignet sich möglicherweise gut für Organisationen, in denen dieselbe Person möglicherweise alle Aufgaben wahrnimmt. Andere Datenschutzrollen ermöglichen es Ihnen, eine genauere Kontrolle zu übernehmen und Benutzern ausgewählte Features oder Funktionen zuzuweisen.

Weitere Informationen zu Rollengruppen und zum Gewähren des Zugriffs finden Sie unter [Festlegen von Benutzerberechtigungen und Zuweisen von Rollen in Priva](priva-permissions.md).

## <a name="start-finding-and-visualizing-your-data"></a>Beginnen Sie mit dem Suchen und Visualisieren Ihrer Daten

Nachdem Sie sich bei Priva angemeldet haben, wird die Seite **"Übersicht**" angezeigt. Diese Seite bietet dynamische Einblicke darüber, wie sich personenbezogene Daten in Ihrer Microsoft 365-Umgebung weiterentwickeln, um Probleme schnell zu erkennen, Risikoindikatoren zu identifizieren und Maßnahmen zur Behebung von Problemen zu ergreifen. Ihre Übersicht sollte innerhalb der ersten 24 Stunden nach der Registrierung mit ersten Erkenntnissen gefüllt werden. Während Sie Priva weiterhin verwenden, wird die Übersichtsseite aktualisiert, um weiterhin aktuelle Informationen bereitzustellen.

Für weitere Einblicke in Ihre Daten im Laufe der Zeit bietet Ihre **Datenprofilseite** mehr Visualisierungen und Analysen und bietet Ihnen eine ganzheitliche Ansicht der Daten Ihrer Organisation nach geografischem Standort und nach Microsoft 365 Standort.

Weitere Informationen zu diesen Seiten finden Sie [unter Suchen und Visualisieren personenbezogener Daten in Priva](priva-data-profile.md).

## <a name="start-managing-risks-with-default-policies"></a>Mit der Verwaltung von Risiken mit Standardrichtlinien beginnen

Privacy Risk Management beginnt mit der Auswertung Ihrer Daten und gibt Ihnen einen Einblick in wichtige Risikoszenarien für Datenminimierung, Datenüberbelichtung und Datenübertragung. Diese Richtlinien sind standardmäßig aktiviert. Sie können diese Richtlinien verwenden, um zu bewerten, wo Sich Ihre Risiken befinden, und dann E-Mail-Benachrichtigungen für Benutzer aktivieren, um Probleme auf ihre Benutzer aufmerksam zu machen und die Behebung dieser Risiken zu steuern. Darüber hinaus können Sie ihre eigenen Richtlinien anhand der bereitgestellten Richtlinienvorlagen erstellen und anpassen. Sie können Ihre Richtlinien so anpassen, dass sie den gesetzlichen und behördlichen Complianceanforderungen Ihrer Organisation entsprechen, wie dies in Absprache mit einem Rechtsberater ermittelt werden kann. Weitere Informationen finden [Sie unter Erstellen von Richtlinien im Datenschutzrisikomanagement](risk-management-policies.md).

## <a name="get-started-with-subject-rights-requests"></a>Erste Schritte mit Anträgen auf Rechte betroffener Personen

Priva Anfragen zu Betroffenenrechten automatisiert den Prozess zur Erfüllung von Anträgen auf Anträge betroffener Personen und bietet einfachen Zugriff auf Daten und anpassbare Workflows, die in vorhandene Geschäftsprozesse passen. Sie können die relevanten Daten leicht finden, die Ergebnisse überprüfen und Berichte erstellen. Auf dem Weg können Sie sicher mit anderen Experten in Ihrer Organisation zusammenarbeiten, um die Anfrage zu Den Schutzrechten abzuschließen. Sie können Ihre Geschäftsworkflows auch mit integrierten Vorlagen verwalten und anpassen. Weitere Informationen zur Verwendung dieser Features finden Sie unter ["Informationen zu Priva Anfragen zu Betroffenenrechten](subject-rights-requests.md)".

## <a name="priva-availability"></a>Priva Verfügbarkeit

Microsoft Priva steht Kunden weltweit zur Verfügung. Wenn Ihre Organisation ihren Mandanten in einem der unten aufgeführten lokalen Rechenzentren bereitgestellt hat, um die Anforderungen an die Datenaufbewahrung zu erfüllen, stehen Ihnen die Priva Lösungen im linken Navigationsbereich der Microsoft Purview-Complianceportal nicht zur Verfügung:

- Norwegen
- Polen
- Katar
- Singapur
- Südafrika
- Südkorea
- Spanien
- Schweden
- Schweiz
- Vereinigte Arabische Emirate

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
