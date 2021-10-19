---
title: Erstellen und Anpassen von Richtlinien in der Datenschutzverwaltung
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
description: Erfahren Sie, wie Sie Datenschutzrichtlinien für die Verarbeitung der personenbezogenen Daten Ihrer Organisation in Microsoft 365 erstellen und anpassen.
ms.openlocfilehash: 2e130e59cc860094f64a0b09fbbdf8c565ebf167
ms.sourcegitcommit: 85e085eb17af8b4efd1f45207445e1b3c3679600
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/19/2021
ms.locfileid: "60478262"
---
# <a name="create-and-customize-privacy-management-policies"></a>Erstellen und Anpassen von Datenschutzverwaltungsrichtlinien

Sie können neue Richtlinien in der Datenverwaltung erstellen, um Datenschutzrisikoszenarien zu behandeln, die für Ihre Organisation wichtig sind. Verwenden Sie für einen Schnellstart die Standardvorlagen, um neue Richtlinien für Datenüberlagerungen, Datenübertragungen, Datenminimierung und -szenarien zu erstellen. Sie können auch Ihre eigenen Richtlinien anpassen, indem Sie eine dieser Vorlagen als Ausgangspunkt verwenden.

Beim Erstellen oder Bearbeiten von Richtlinien können Sie E-Mail-Benachrichtigungen oder, sofern verfügbar, Richtlinientipps für Teams konfigurieren, um Richtlinienübersprechungen für die Behebung auf Ihre Benutzer aufmerksam zu machen.

## <a name="create-a-policy-from-a-template"></a>Erstellen einer Richtlinie anhand einer Vorlage

Führen Sie die folgenden Schritte aus, um eine Richtlinie mithilfe einer der Standardvorlagen zu erstellen.

1. Wechseln [Sie](https://compliance.microsoft.com/)im Microsoft 365 Compliance Center zum Abschnitt "Datenschutzverwaltung", und wählen Sie **"Richtlinien"** aus.
1. Wählen Sie **Richtlinie erstellen** aus.
1. Wählen Sie den gewünschten Vorlagentyp aus. Dadurch wird ein Flyoutbereich mit Informationen zur Vorlage geöffnet.
1. Wählen Sie zum Überprüfen der Standardeinstellungen der Vorlage, einschließlich Datentypen, Datenspeicherorten und bedingungen, die Richtlinienüberstimmungen auslösen, die **Einstellungen anzeigen** aus.
     - Hier haben Sie die Möglichkeit, **"Einstellungen bearbeiten"** auszuwählen, um Änderungen vorzunehmen. Dadurch gelangen Sie zum Assistenten zum Anpassen von Einstellungen.
1. Wenn Sie bereit sind, die Standardeinstellungen zu verwenden, geben Sie Ihrer Richtlinie einen beschreibenden Namen, und wählen Sie **"Richtlinie erstellen" aus.**

Wenn Sie eine Richtlinie direkt aus einer Vorlage erstellen, werden viele Einstellungen automatisch für Sie ausgewählt. Es wird auch standardmäßig im Testmodus gestartet, was bedeutet, dass keine Warnungen oder Benachrichtigungen generiert werden. Wenn Sie bereit sind, Ihre Richtlinie vollständig zu aktivieren, nachdem Sie sie im Testmodus ausgeführt und die Ergebnisse der Richtlinie überprüft haben, können Sie sie in Ihrer Richtlinienliste finden und die Richtlinie bearbeiten, um sie einzuschalten.

## <a name="create-a-custom-privacy-management-policy"></a>Erstellen einer benutzerdefinierten Datenschutzverwaltungsrichtlinie

Um die Einstellungen einer Richtlinie präzise zu steuern, können Sie eine angepasste Richtlinie mithilfe einer der vorhandenen Vorlagen als Basislinie erstellen. Die Datenschutzverwaltung bietet einen Assistenten, der Sie durch diese Schritte führt.

Alle Richtlinientypen folgen diesem grundlegenden Ablauf. Bestimmte Einstellungen und Optionen ändern sich je nach der gewählten Richtlinie.

1. Wechseln [Sie](https://compliance.microsoft.com/)im Microsoft 365 Compliance Center zum Abschnitt "Datenschutzverwaltung", und wählen Sie **"Richtlinien"** aus.
1. Wählen Sie **Richtlinie erstellen** aus.
1. Wählen Sie die **Option "Benutzerdefiniert"** aus, um mit der Verwendung des Assistenten zu beginnen.
1. Wählen Sie den Basisvorlagentyp aus: **Datenüberlastung,** **Datenübertragung** oder **Datenminimierung.** Jede option gibt Ihnen bestimmte Optionen während der Richtlinienerstellung.
1. Benennen und beschreiben Sie Ihre Richtlinie. Es wird empfohlen, klare, beschreibende Namen zu verwenden, um Ihre Richtlinien zu identifizieren, da diese Namen später in Warnungen zu Richtlinienüberstimmungen angezeigt werden.
1. Fahren Sie mit dem Assistenten fort, und wählen Sie die gewünschten Einstellungen aus. Die folgenden Optionen stehen zur Verfügung:
    - **Zu überwachende Daten:** Wählen Sie den Typ der personenbezogenen Daten aus, die Ihre Richtlinie überwacht.
    - **Benutzer und Gruppen:** Wenden Sie Ihre Richtlinie auf alle Benutzer oder ausgewählten Benutzer an.
    - **Speicherorte:** Wenden Sie Ihre Richtlinie auf ausgewählte Bereiche in Microsoft 365 an.
    - **Bedingungen:** Legen Sie die Bedingungen für Ihre Richtlinie fest. Diese Optionen variieren je nach Ihrem Richtlinientyp.
    - **Ergebnisse:** Definieren Sie die Ergebnisse, wenn eine Richtlinienübersprechung gefunden wird, z. B. Benutzerbenachrichtigungen.
    - **Warnungen:** Festlegen der Häufigkeit von Warnungen an Administratoren, wenn eine Richtlinienüberstimmung gefunden wird.
    - **Modus:** Wählen Sie aus, ob Die Richtlinie zuerst im Testmodus ausgeführt werden soll.
1. Wenn alle Einstellungen abgeschlossen sind, überprüfen Sie Ihre Auswahl, nehmen Sie alle gewünschten Änderungen vor, und wählen Sie dann **"Absenden"** aus, um die Richtlinie zu erstellen.

## <a name="learn-about-key-settings-for-all-policies"></a>Erfahren Sie mehr über die wichtigsten Einstellungen für alle Richtlinien

### <a name="choose-data-to-monitor"></a>Zu überwachende Daten auswählen

Beim Bearbeiten oder Einrichten einer beliebigen Art von benutzerdefinierter Richtlinie werden Sie aufgefordert, auszuwählen, welche Datentypen Ihre Richtlinie überwachen soll. Folgende Optionen stehen zur Verfügung:

- **Klassifizierungsgruppen:** Eine durchsuchbare Liste von Datensätzen basierend auf wichtigen Datenschutzbestimmungen, z. B. DSGVO oder HIPAA. Zeigen Sie Details zu einer beliebigen Gruppe an, um zu sehen, welche Arten von vertraulichen Informationen behandelt werden. Wählen Sie eine oder mehrere dieser Gruppen aus, um sie wie besehen zu verwenden.
- **Einzelne Typen vertraulicher Informationen:** Indem Sie bestimmte Typen vertraulicher Informationen selbst auswählen, z. B. Sozialversicherungsnummern oder Führerscheininformationen, können Sie Ihre eigene Gruppe oder Gruppen von Daten anpassen, nach denen Sie suchen sollten. Mit diesem Assistenten können Sie aus der vollständigen Liste der Typen vertraulicher Informationen innerhalb der Datenschutzverwaltung auswählen. Jeder Informationstyp hat seine eigenen Eigenschaften. Verwenden Sie die Infoschaltfläche neben einer dieser Schaltflächen, um Details und Hinweise zu den empfohlenen Einstellungen zu erhalten. Wenn Sie mehrere Gruppen erstellen, können Sie mit dem Assistenten boolesche Operatoren anwenden, um diese zu verknüpfen und deren Reihenfolge der Vorgänge zu definieren.

Wenn Sie aus den vorhandenen Klassifizierungsgruppen auswählen, können Sie nicht auch einzelne Typen auswählen oder eigene Gruppen erstellen. Wählen Sie aus Gründen der Flexibilität individuelle Typen vertraulicher Informationen aus. Um die gängigsten Standards zu verwenden, wählen Sie aus den Klassifizierungsgruppen aus.

### <a name="set-user-email-notifications"></a>Festlegen von Benutzer-E-Mail-Benachrichtigungen

Mit [E-Mail-Benachrichtigungen](privacy-management-policies-notifications.md)können Sie Benachrichtigungen zu Richtlinienüberstimmungen direkt an Ihre Inhaltsbesitzer senden. Diese E-Mails fassen zusammen, welche Daten überprüft werden müssen und welche Maßnahmen ergriffen werden müssen, z. B. privates Erstellen von Dokumenten, Aufbewahren von Dateien, Melden falsch positiver Übereinstimmungen und Hinzufügen von Notizen für zukünftige Verweise. Diese E-Mails enthalten auch Links für Schulungsempfänger zum Umgang mit diesen Fällen. Die Bereitstellung dieser Links ist erforderlich und sollte auf Ihre eigene interne Dokumentation zu Prozessen und bewährten Methoden verweisen.

Benachrichtigungen können für einzelne Richtlinien während der Erstellung einer benutzerdefinierten Richtlinie oder beim Bearbeiten einer Richtlinie aktiviert werden. Legen Sie Ihre Einstellungen im Abschnitt **"Ergebnisse"** fest.

Erforderliche Einstellungen umfassen die Häufigkeit Ihrer Benachrichtigungen und Ihren Link zum Datenschutztraining.

Optionale Einstellungen umfassen bestimmte anpassbare Felder für Ihre E-Mails. Wählen Sie die Option **"Vorschau" und "Benachrichtigungs-E-Mail bearbeiten"** aus, um einen Flyoutbereich zu öffnen, in dem eine Beispielbenachrichtigung angezeigt wird. Hier können Sie die Betreffzeile der E-Mail, den Kopf- und Textkörper sowie den Anzeigenamen und die URL für Ihre Datenschutzschulung bearbeiten.

Beachten Sie, dass die allgemeine Fähigkeit der Datenschutzverwaltung zum Senden von E-Mail-Benachrichtigungen in **Einstellungen** gesteuert wird. Diese Anwendung ist standardmäßig aktiviert. Wenn Sie diese Einstellung deaktivieren, werden alle E-Mails beendet, auch wenn Benachrichtigungen auf einer einzelnen Richtlinienebene konfiguriert wurden.

## <a name="learn-about-settings-for-data-minimization-policies"></a>Informationen zu Einstellungen für Richtlinien zur Datenminimierung

Richtlinien zur Datenminimierung konzentrieren sich auf das Alter Ihrer Inhalte und deren Dauer seit der letzten Änderung. Die Überwachung auf personenbezogene Daten, die noch in älteren, nicht verwendeten Inhalten aufbewahrt werden, kann Ihnen helfen, Ihre gespeicherten Daten besser zu verwalten und Risiken zu verringern. Diese Einstellung wird auf dem Bildschirm **"Bedingungen"** behandelt.

Standardmäßig suchen Richtlinien zur Datenminimierung nach Inhalten, die personenbezogene Daten enthalten, die vor mindestens 60 Tagen erstellt oder zuletzt geändert wurden. Beim Bearbeiten oder Erstellen einer benutzerdefinierten Richtlinie können Sie aus anderen vordefinierten Zeitrahmen auswählen.

## <a name="learn-about-settings-for-data-transfer-policies"></a>Informationen zu Einstellungen für Datenübertragungsrichtlinien

Richtlinien für die Datenübertragung ermöglichen es Ihnen, Daten zu überwachen, die zwischen bestimmten Regionen der Welt oder zwischen verschiedenen Abteilungen Ihrer Organisation übertragen werden. Auf dem Bildschirm **"Bedingungen"** können Sie auswählen, nach welchen Arten von Übertragungen datenschutzverwaltung gesucht werden soll.

Standardmäßig suchen Datenübertragungsrichtlinien nach Übertragungen zwischen Nordamerika und anderen Regionen. Beim Bearbeiten oder Erstellen einer benutzerdefinierten Richtlinie können Sie den Übertragungstyp auswählen und dann eine Auswahl für die Regionen oder Abteilungen von Absender und Empfänger treffen.

Richtlinien für die Datenübertragung unterstützen auch die Bereitstellung von Richtlinientipps und Empfehlungen für Ihre Benutzer in Teams, damit sie über bewährte Methoden für den Umgang mit Daten auf dem Laufenden bleiben können. Dies kann auf dem **Ergebnisbildschirm** umgeschaltet werden.

## <a name="learn-about-settings-for-data-overexposure-policies"></a>Informationen zu Einstellungen für Datenüberlastungsrichtlinien

Ihre Organisation kann Inhalte auf verschiedenen Zugriffsebenen speichern, darunter Bereiche, die öffentlich zugänglich sind, und andere, die eingeschränkt sind. Auf dem Bildschirm **"Bedingungen"** können Sie festlegen, dass die Datenschutzverwaltung nach potenzieller Datenüberlastung für Inhalte sucht, die auf einer der folgenden Zugriffsebenen gespeichert sind:

- **Öffentlich:** Jeder Benutzer mit einem Link kann diesen Inhalt anzeigen.
- **Extern:** Bestimmte Personen außerhalb der Organisation haben Zugriff.
- **Intern:** Benutzer in Ihrer Organisation haben Zugriff.

Standardmäßig bewerten Datenüberbelichtungsrichtlinien alle drei Zugriffsebenen. Beim Bearbeiten oder Erstellen einer benutzerdefinierten Richtlinie können Sie alle oder eine dieser Ebenen auswählen.

## <a name="next-steps"></a>Nächste Schritte

Weitere Informationen dazu, wie Sie Ihre Richtlinien verwalten und Änderungen vornehmen, nachdem sie erstellt wurden, finden Sie unter [Verwalten von Richtlinien.](privacy-management-policies-manage.md)

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Datenschutzverwaltung](privacy-management-disclaimer.md)
