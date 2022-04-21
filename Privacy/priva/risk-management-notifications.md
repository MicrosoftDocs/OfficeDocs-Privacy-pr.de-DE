---
title: Senden von Benutzerbenachrichtigungen im Datenschutzrisikomanagement
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
search.appverid:
- MOE150
- MET150
description: Erfahren Sie, wie Sie Inhaltsbesitzer über Richtlinienübereinstimmungen informieren, die von Microsoft Priva Privacy Risk Management gefunden wurden, und wie sie diese E-Mail-Benachrichtigungen verwenden können, um Probleme zu beheben.
ms.openlocfilehash: 8969e1cd4d5859102b18bd46723d1be6e85d35f6
ms.sourcegitcommit: b5f7dcb73c0e3f677981e80106769cb546d00af4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/21/2022
ms.locfileid: "65014375"
---
# <a name="user-notifications-in-privacy-risk-management"></a>Benutzerbenachrichtigungen im Datenschutzrisikomanagement

Wenn Sie eine Richtlinie im Datenschutzrisikomanagement einrichten, können Sie benutzer benachrichtigen, wenn ihre Aktionen die in der Richtlinie festgelegten Bedingungen erfüllen. Es gibt zwei Arten von Benachrichtigungen: E-Mails, die für alle drei Richtlinientypen verfügbar sind, und Tipps, die in Teams angezeigt werden, die nur für den Richtlinientyp für die Datenübertragung verfügbar sind. Wenn Sie eine Richtlinie erstellen oder bearbeiten, können Sie entscheiden, ob Sie diese Benachrichtigungen aktivieren, wie häufig sie gesendet werden sollen, und Sie können deren Inhalte anpassen.

Das Senden von Benachrichtigungen an Benutzer kann eine wichtige Komponente sein, um Ihrer Organisation dabei zu helfen, die Datenschutzziele zu erreichen. Die Benachrichtigungen sind für Folgendes ausgelegt:

- Sorgen Sie dafür, dass Benutzer sofort darauf aufmerksam gemacht werden, wann ihre Aktionen personenbezogene Daten Datenschutzrisiken aussetzen könnten.
- Stellen Sie Korrekturmethoden direkt in den E-Mails bereit, damit Benutzer schnell maßnahmen können, um gefährdete Daten zu schützen.
- Leiten Sie Benutzer an die Datenschutzrichtlinien und bewährten Methoden Ihrer Organisation weiter.

Benutzer über potenzielle Probleme im Moment zu informieren und sie in die Lage zu versetzen, Probleme zu beheben und ihre Fähigkeiten zu aktualisieren, kann leistungsstarke Tools für die Erstellung solider Datenverarbeitungspraktiken in Ihrer Organisation sein.

Lesen Sie die folgenden Abschnitte, um Benutzerbenachrichtigungen für Richtlinienübereinstimmungen vorzubereiten und zu verwalten.

## <a name="prepare-training-content-for-notifications"></a>Vorbereiten von Schulungsinhalten für Benachrichtigungen

Ein Link zu Datenschutzschulungen ist erforderlich, wenn Sie benutzerbenachrichtigungen senden möchten, wenn Richtlinienübereinstimmungen erkannt werden. Durch den Zugriff auf die Datenschutzrichtlinien Ihrer Organisation können Sie Ihre Benutzer über Ihre eigenen bewährten Methoden und Richtlinien auf dem Laufenden halten. Es kann auch Kontext für die vorgeschlagenen Abhilfemaßnahmen in der E-Mail bereitstellen und Ihren Benutzern dabei helfen, sich in Zukunft auf gute Entscheidungen im Zusammenhang mit der Datenverwaltung vorzubereiten.

Bevor Sie Ihre Richtlinie einrichten, entscheiden Sie sich für die Schulungs-URL, die Sie einschließen möchten. Pro Richtlinie kann ein Link bereitgestellt werden, daher wird empfohlen, für jedes Szenario spezifische Verweise auszuwählen.

## <a name="set-user-email-notifications"></a>Festlegen von Benutzer-E-Mail-Benachrichtigungen

Sie können E-Mail-Benachrichtigungen für alle Richtlinientypen einrichten, wenn Sie eine neue Richtlinie erstellen oder eine vorhandene Richtlinie bearbeiten. Diese Einstellungen finden Sie auf der Seite **"Ergebnisse** " des Richtlinienerstellungs-Assistenten. Besuchen [Sie "Ergebnisse definieren": Benutzerbenachrichtigungen und Tipps](risk-management-policies.md#define-outcomes-user-email-notifications-and-tips) für die vollständigen Anweisungen.

> [!NOTE]
> Die Allgemeine Fähigkeit des Privacy Risk Management zum Senden von E-Mail-Benachrichtigungen wird in Priva **Einstellungen** gesteuert. Diese Anwendung ist standardmäßig aktiviert. Wenn Sie diese Einstellung deaktivieren, werden alle E-Mails beendet, auch wenn Benachrichtigungen auf einer einzelnen Richtlinienebene konfiguriert wurden. Erfahren Sie mehr über die [E-Mail-Einstellungen für Benutzerbenachrichtigungen](priva-settings.md#user-notification-emails).

## <a name="send-notifications-in-teams"></a>Senden von Benachrichtigungen in Teams

Für Datenübertragungsrichtlinien können Sie festlegen, dass Benutzer Richtlinientipps und Empfehlungen in sicheren Teams Kanälen erhalten, wenn eine Richtlinienübereinstimmung erkannt wird. Diese Tipps informieren die Benutzer über die verantwortungsvolle Verwendung personenbezogener Daten. Tipps werden auch Links zu verwandten Schulungen enthalten.

Weitere Informationen zum Einrichten dieser Benachrichtigungen finden Sie unter [Definieren von Ergebnissen: Benutzerbenachrichtigungen und Tipps](risk-management-policies.md#define-outcomes-user-email-notifications-and-tips).

## <a name="preview-and-customize-email-content"></a>Anzeigen einer Vorschau und Anpassen von E-Mail-Inhalten

Wenn Benutzer E-Mail-Benachrichtigungen zu Richtlinienübereinstimmungen erhalten, können sie den Anweisungen in den E-Mails folgen, um sofort Korrekturmaßnahmen zu ergreifen. Wenn beispielsweise eine Datenüberbelichtungsrichtlinie eine Übereinstimmung für personenbezogene Daten findet, die möglicherweise zu weit zugänglich ist, enthält die Benachrichtigungs-E-Mail einen Link zum Inhaltselement, damit der Benutzer es überprüfen kann, und Schaltflächen, mit denen der Benutzer das Element als privat markieren oder seine aktuelle Zugriffsebene beibehalten kann. Die vorgeschlagenen Aktionen sind für jeden verschiedenen Richtlinientyp relevant.

Sie können eine Vorschau der E-Mail-Inhalte anzeigen und ihre eigenen Änderungen vornehmen, wenn Sie diese Einstellung im Richtlinienerstellungs- oder -bearbeitungsprozess anpassen. Führen Sie die folgenden Schritte aus, um eine Vorschau ihrer E-Mail-Inhalte für Benachrichtigungen anzuzeigen und zu bearbeiten:

1. Erstellen oder bearbeiten Sie Ihre Richtlinie, indem Sie die im [geführten Richtlinienerstellungsprozess](risk-management-policies.md#custom-setup-guided-process-to-choose-all-settings) beschriebenen Schritte starten.

2. Aktivieren **Sie im** Ergebnisschritt des Prozesses das Kontrollkästchen neben " **Benachrichtigungs-E-Mail an Benutzer senden", wenn eine Richtlinienübereinstimmung auftritt**.

3. Wählen Sie die Schaltfläche " **Benachrichtigungs-E-Mail in der Vorschau anzeigen und bearbeiten** " aus, die unterhalb des Benachrichtigungs-E-Mail-Kontrollkästchens angezeigt wird.

4. Ein Flyoutbereich wird mit Textfeldern angezeigt, die mit dem Standardmäßigen E-Mail-Inhalt ausgefüllt sind. Sie können beliebige oder alle Felder bearbeiten, einschließlich: Betreffzeile der E-Mail, Textkopfzeile, Textkörperinhalt, Anzeigename der Datenschutzschulung und Schulungs-URL. Die Vorschau der E-Mail befindet sich am unteren Rand des Flyoutbereichs und ändert sich, wenn Sie Änderungen am Standardtext vornehmen. Wenn Sie mit dem E-Mail-Inhalt zufrieden sind, wählen Sie **"Speichern"** aus, um Ihre Einstellungen zu speichern. Um alle Änderungen an der Standard-E-Mail zu verwerfen, wählen Sie das **X** in der oberen rechten Ecke des Flyoutbereichs aus, um es zu schließen und zum Standardinhalt zurückgesetzt zu werden.

5. Wählen Sie auf der Seite **"Ergebnisse** " die Option **"Weiter**" aus. Fahren Sie mit dem Assistenten fort, und wenn Sie auf der letzten Seite **"Fertig stellen** " ankommen, überprüfen Sie Ihre Einstellungen, und wählen Sie **"Absenden**" aus.

Ihre Benachrichtigungseinstellungen sind jetzt für diese Richtlinie in Kraft. Wenn Ihre Richtlinie getestet wird, werden keine Benachrichtigungen gesendet. Wenn Ihre Richtlinie aktiviert ist, werden Benachrichtigungen gesendet. Zeigen Sie weitere Details zum [Erstellen und Verwalten von Richtlinien an](risk-management-policies.md).


## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
