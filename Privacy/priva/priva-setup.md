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
ms.openlocfilehash: 8df9367bd88fe9a8feecdbb00110345aae7a3d79
ms.sourcegitcommit: a76dec53605c963d9bc134a26b7e09f600d6e940
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/31/2022
ms.locfileid: "62280247"
---
# <a name="get-started-with-priva"></a>Erste Schritte mit Priva

Wenn Sie bereit sind, Microsoft Priva zur Unterstützung bei der Identifizierung und Minderung von Datenschutzrisiken zu nutzen, folgen Sie diesen Schritten, um die Voraussetzungen zu schaffen und mit der Erkundung von Datenschutzerkenntnissen zu beginnen.

## <a name="step-1-confirm-subscriptions-and-licensing"></a>Schritt 1: Bestätigen von Abonnements und Lizenzierung

Priva ist im [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) verfügbar und kann von Organisationen mit den folgenden Lizenzen erworben werden:

- Microsoft 365 E3, E5, A3, A5
- Office 365 E1, E3, E5, A1, A3, A5

Priva bietet Lizenzierungsoptionen für zwei verschiedene Lösungen: Priva Privacy Risk Management und Priva Subject Rights Requests. Diese können einzeln oder zusammen erworben werden. Beim Abrufen von Lizenzen für Antragstellerberechtigungsanforderungen können Sie die entsprechende Lizenzierungsstufe für die Anzahl der Anforderungen auswählen, die Sie behandeln müssen. Sie können jederzeit zusätzliche Anforderungen erwerben.

Ausführliche Informationen zur Lizenzierung finden Sie unter: [Microsoft 365-Lizenzierungsrichtlinien für Sicherheit und Compliance](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#microsoft-priva).

> [!Note]
> Priva steht nicht für Kunden von US Government Community (GCC) Moderate, GCC High oder Department of Defense (DoD) zur Verfügung.

### <a name="get-free-trial-license"></a>Kostenlose Testlizenz abrufen

Für die ersten Schritte mit Priva steht eine kostenlose Testlizenz zur Verfügung. Informationen zur Berechtigung und zum Beitreten finden [Sie unter "Informationen zur kostenlosen Priva-Testversion](priva-trial.md)".

## <a name="step-2-enable-the-microsoft-365-audit-log"></a>Schritt 2: Aktivieren des Microsoft 365 Überwachungsprotokolls

Microsoft 365 Überwachungsprotokolle sind eine Zusammenfassung aller Aktivitäten in Ihrer Organisation. Richtlinien für das Datenschutzrisikomanagement können diese Aktivitäten verwenden, um Richtlinienerkenntnisse zu generieren.

In Ihrer Organisation sind möglicherweise bereits Überwachungsprotokolle aktiviert. Wenn Sie damit beginnen müssen, sie zum ersten Mal zu verwenden, finden Sie unter [Aktivieren oder Deaktivieren der Überwachungsprotokollsuche](/microsoft-365/compliance/turn-audit-log-search-on-or-off) Schritt-für-Schritt-Anleitungen zum Aktivieren der Überwachung. Daraufhin teilt Ihnen eine Meldung mit, dass das Überwachungsprotokoll vorbereitet wird und Sie in ein paar Stunden nach Abschluss der Vorbereitung eine Suche durchführen können. Sie müssen diese Aktion nur einmal ausführen. Weitere Informationen zur Verwendung des Microsoft 365 Überwachungsprotokolls finden Sie unter [Durchsuchen des Überwachungsprotokolls](/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance).

## <a name="step-3-set-user-permissions-and-assign-roles"></a>Schritt 3: Festlegen von Benutzerberechtigungen und Zuweisen von Rollen

Priva verwendet ein rollenbasiertes Zugriffssteuerungsmodell (RBAC). Nur Benutzer, denen eine Rolle zugewiesen ist, können auf Priva zugreifen, und die von jedem Benutzer zugelassenen Aktionen sind nach Rollentyp eingeschränkt.

Ihr globaler Administrator verfügt über Berechtigungen für den Zugriff auf Priva und das Zuweisen anderer Benutzer zu Rollen. Sie können sich anmelden und Benutzerberechtigungen im [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) für Priva festlegen. Für einen Schnellstart verfügt die Rollengruppe "Datenschutzverwaltung" über Berechtigungen für den Zugriff auf alle Features von Priva. Diese Gruppe eignet sich möglicherweise gut für Organisationen, in denen dieselbe Person alle Aufgaben ausführen kann. Andere Datenschutzrollen ermöglichen es Ihnen, eine präzisere Kontrolle zu übernehmen und ausgewählten Features oder Funktionen Benutzer zuzuweisen.

Weitere Informationen zu Rollengruppen und zum Gewähren von Zugriff finden Sie unter [Festlegen von Benutzerberechtigungen und Zuweisen von Rollen in Priva](priva-permissions.md).

## <a name="step-4-start-finding-and-visualizing-your-data"></a>Schritt 4: Suchen und Visualisieren Ihrer Daten

Nachdem Sie sich bei Priva angemeldet haben, wird die **Übersichtsseite** angezeigt. Diese Seite bietet dynamische Einblicke darüber, wie sich personenbezogene Daten in Ihrer Microsoft 365 Umgebung weiterentwickeln, um Probleme schnell zu erkennen, Risikoindikatoren zu identifizieren und Maßnahmen zur Behebung von Problemen zu ergreifen. Ihre Übersicht sollte innerhalb der ersten 24 Stunden nach der Registrierung mit ersten Erkenntnissen aufgefüllt werden. Während Sie Priva weiterhin verwenden, wird die Übersichtsseite aktualisiert, um weiterhin aktuelle Informationen bereitzustellen.

Für weitere Einblicke in Ihre Daten im Laufe der Zeit bietet Ihre **Datenprofilseite** mehr Visualisierungen und Analysen und bietet Ihnen einen ganzheitlichen Überblick über die Daten Ihrer Organisation nach geografischem Standort und nach Microsoft 365 Standort.

Weitere Informationen zu diesen Seiten finden Sie unter ["Suchen und Visualisieren personenbezogener Daten" in Priva](priva-data-profile.md).

## <a name="step-5-start-managing-risks-with-default-policies"></a>Schritt 5: Starten der Verwaltung von Risiken mit Standardrichtlinien

Das Datenschutzrisikomanagement beginnt mit der Auswertung Ihrer Daten und gibt Ihnen einen Einblick in die wichtigsten Risikoszenarien für die Minimierung von Daten, datenüberlastung und Datenübertragungen. Diese Richtlinien sind standardmäßig aktiviert. Sie können diese Richtlinien verwenden, um zu bewerten, wo Ihre Risiken liegen, und dann Benutzer-E-Mail-Benachrichtigungen für Ihre Benutzer aktivieren, um Probleme auf ihre Aufmerksamkeit zu lenken und die Behebung dieser Risiken zu leiten. Darüber hinaus können Sie ihre eigenen Richtlinien anhand der bereitgestellten Richtlinienvorlagen erstellen und anpassen. Sie können Ihre Richtlinien so anpassen, dass sie den rechtlichen und behördlichen Compliance-Anforderungen Ihrer Organisation entsprechen, wie in Abstimmung mit Rechtsberatern identifiziert werden kann. Weitere Informationen finden Sie unter ["Erstellen von Richtlinien im Datenschutzrisikomanagement"](risk-management-policies.md).

## <a name="step-6-get-started-with-subject-rights-requests"></a>Schritt 6: Erste Schritte mit Antragstellerrechten

Priva Subject Rights Requests automatisiert den Prozess zur Erfüllung von Anträgen betroffener Personen und bietet einfachen Zugriff auf Daten und anpassbare Workflows, die in vorhandene Geschäftsprozesse passen. Sie können die relevanten Daten leicht finden, die Ergebnisse überprüfen und Berichte erstellen. Auf diese Weise können Sie sicher mit anderen Experten in Ihrer Organisation zusammenarbeiten, um die Anforderung der Betreffrechte abzuschließen. Sie können Ihre Geschäftsworkflows auch mit integrierten Vorlagen verwalten und anpassen. Weitere Informationen zur Verwendung dieser Features finden Sie unter ["Informationen zu Anforderungen für Priva-Rechte"](subject-rights-requests.md).

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
