---
title: Erstellen von Richtlinien im Datenschutzrisikomanagement
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
description: Erfahren Sie, wie Sie Datenschutzrichtlinien für den Umgang mit den personenbezogenen Daten Ihrer Organisation in Microsoft 365 erstellen und anpassen.
ms.openlocfilehash: 2b655d778e73e2107c289988966fb491bf3ebb2e
ms.sourcegitcommit: 09ecdaded9a9f8f79587f2acb978dc53b83e5c01
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/19/2022
ms.locfileid: "64930506"
---
# <a name="create-policies-in-privacy-risk-management"></a>Erstellen von Richtlinien im Datenschutzrisikomanagement

Sie können neue Richtlinien im Datenschutzrisikomanagement erstellen, um Risikoszenarien zu behandeln, die für Ihre Organisation wichtig sind. Verwenden Sie für einen Schnellstart die Standardvorlagen, um neue Richtlinien für Datenüberbelichtung, Datenübertragungen sowie Datenminimierung und Szenarien zu erstellen. Sie können auch Ihre eigenen Richtlinien anpassen, indem Sie eine dieser Vorlagen als Ausgangspunkt verwenden.

Beim Erstellen oder Bearbeiten von Richtlinien können Sie E-Mail-Benachrichtigungen konfigurieren oder, sofern verfügbar, Richtlinientipps für Teams, um Ihre Benutzer auf Richtlinienübereinstimmungen zur Behebung aufmerksam zu machen.

## <a name="create-a-policy-from-a-template"></a>Erstellen einer Richtlinie aus einer Vorlage

Führen Sie die folgenden Schritte aus, um eine Richtlinie mithilfe einer der Standardvorlagen zu erstellen.

1. Wechseln Sie im [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/) zum Abschnitt "Priva Privacy Risk Management", und wählen Sie **"Richtlinien**" aus.
1. Wählen Sie **Richtlinie erstellen** aus.
1. Wählen Sie den gewünschten Vorlagentyp aus. Dadurch wird ein Flyoutbereich mit Informationen zur Vorlage geöffnet.
1. Um die Standardeinstellungen der Vorlage zu überprüfen, einschließlich Datentypen, Datenspeicherorten und bedingungen, die Richtlinienübereinstimmungen auslösen, wählen Sie **"Ansichtseinstellungen"** aus.
     - Sie haben hier die Möglichkeit, **"Einstellungen bearbeiten"** auszuwählen, um Änderungen vorzunehmen. Dadurch gelangen Sie zum Assistenten zum Anpassen von Einstellungen.
1. Wenn Sie bereit sind, die Standardeinstellungen zu verwenden, geben Sie Ihrer Richtlinie einen aussagekräftigen Namen, und wählen Sie **"Richtlinie erstellen" aus.**

Wenn Sie eine Richtlinie direkt aus einer Vorlage erstellen, werden automatisch viele Einstellungen für Sie ausgewählt. Es wird auch standardmäßig im Testmodus gestartet, was bedeutet, dass keine Warnungen oder Benachrichtigungen generiert werden. Wenn Sie bereit sind, Ihre Richtlinie vollständig zu aktivieren, nachdem Sie sie im Testmodus ausgeführt und die Ergebnisse der Richtlinie überprüft haben, können Sie sie in Ihrer Richtlinienliste finden und die Richtlinie bearbeiten, um sie einzuschalten.

## <a name="create-a-custom-policy"></a>Erstellen einer benutzerdefinierten Richtlinie

Um die Einstellungen einer Richtlinie präzise zu steuern, können Sie eine angepasste Richtlinie mithilfe einer der vorhandenen Vorlagen als Basisplan erstellen. Priva bietet einen Assistenten, der Sie durch diese Schritte führt.

Alle Richtlinientypen folgen diesem grundlegenden Fluss. Bestimmte Einstellungen und Optionen ändern sich je nach ausgewählter Richtlinie.

1. Wechseln Sie im [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/) zum Abschnitt "Priva Privacy Risk Management", und wählen Sie **"Richtlinien**" aus.
1. Wählen Sie **Richtlinie erstellen** aus.
1. Wählen Sie die Option **"Benutzerdefiniert** " aus, um mit der Verwendung des Assistenten zu beginnen.
1. Wählen Sie ihren Basisvorlagentyp aus: **Datenüberbelichtung,** **Datenübertragungen** oder **Datenminimierung**. Jede dieser Optionen gibt Ihnen während der Richtlinienerstellung bestimmte Optionen.
1. Benennen und beschreiben Sie Ihre Richtlinie. Es wird empfohlen, klare, beschreibende Namen zu verwenden, um Ihre Richtlinien zu identifizieren, da diese Namen später in Warnungen zu Richtlinienübereinstimmungen angezeigt werden.
1. Fahren Sie mit dem Assistenten fort, und wählen Sie die gewünschten Einstellungen aus. Die folgenden Optionen stehen zur Verfügung:
    - **Zu überwachenden Daten**: Wählen Sie den Typ der personenbezogenen Daten aus, die Ihre Richtlinie überwacht.
    - **Benutzer und Gruppen**: Wenden Sie Ihre Richtlinie auf alle Benutzer oder ausgewählten Benutzer an.
    - **Speicherorte**: Wenden Sie Ihre Richtlinie auf ausgewählte Bereiche in Microsoft 365 an.
    - **Bedingungen**: Legen Sie die Bedingungen für Ihre Richtlinie fest. Diese Optionen variieren je nach Richtlinientyp.
    - **Ergebnisse**: Definieren Sie die Ergebnisse, wenn eine Richtlinienübereinstimmung gefunden wird, z. B. Benutzerbenachrichtigungen.
    - **Warnungen**: Entscheiden Sie die Häufigkeit von Warnungen für Administratoren, wenn eine Richtlinienübereinstimmung gefunden wird.
    - **Modus**: Wählen Sie aus, ob Ihre Richtlinie zuerst im Testmodus ausgeführt werden soll.
1. Wenn alle Einstellungen abgeschlossen sind, überprüfen Sie Ihre Auswahl, nehmen Sie alle gewünschten Änderungen vor, und wählen Sie dann **"Absenden** " aus, um die Richtlinie zu erstellen.

## <a name="learn-about-key-settings-for-all-policies"></a>Informationen zu den wichtigsten Einstellungen für alle Richtlinien

### <a name="choose-data-to-monitor"></a>Daten auswählen, die überwacht werden sollen

Beim Bearbeiten oder Einrichten einer beliebigen Art von benutzerdefinierter Richtlinie werden Sie aufgefordert, auszuwählen, welche Datentypen Ihre Richtlinie überwachen soll. Folgende Optionen stehen zur Verfügung:

- **Klassifizierungsgruppen**: Eine durchsuchbare Liste von Datensätzen basierend auf wichtigen Datenschutzbestimmungen, z. B. DSGVO oder HIPAA. Zeigen Sie Details einer Gruppe an, um zu sehen, welche Typen vertraulicher Informationen behandelt werden. Wählen Sie einen oder mehrere dieser Sätze aus, um sie in der vorliegenden Weise zu verwenden.
- **Einzelne Typen vertraulicher Informationen**: Indem Sie bestimmte Typen vertraulicher Informationen selbst auswählen, z. B. Sozialversicherungsnummern oder Führerscheininformationen, können Sie Ihre eigene Gruppe oder Gruppen von Daten anpassen, nach der Sie suchen können. Mit diesem Assistenten können Sie aus der vollständigen Liste vertraulicher Informationstypen innerhalb des Datenschutzrisikomanagements auswählen. Jeder Informationstyp verfügt über eigene Eigenschaften. Verwenden Sie die Schaltfläche "Info" neben einer dieser Einstellungen, um Details und Hinweise zu empfohlenen Einstellungen zu erhalten. Wenn Sie mehr als eine Gruppe erstellen, können Sie mit dem Assistenten boolesche Operatoren anwenden, um sie in Beziehung zu setzen und deren Reihenfolge der Vorgänge zu definieren.

Wenn Sie aus den vorhandenen Klassifizierungsgruppen auswählen, können Sie nicht auch einzelne Typen auswählen oder eigene Gruppen erstellen. Um die größtmögliche Flexibilität zu bieten, wählen Sie einzelne Typen vertraulicher Informationen aus. Um die gängigsten Standards zu verwenden, wählen Sie aus den Klassifizierungsgruppen aus.

### <a name="set-user-email-notifications"></a>Festlegen von Benutzer-E-Mail-Benachrichtigungen

Mit [E-Mail-Benachrichtigungen](risk-management-notifications.md) können Sie Benachrichtigungen zu Richtlinienübereinstimmungen direkt an Ihre Inhaltsbesitzer senden. Diese E-Mails fassen zusammen, welche Daten überprüft werden müssen, und mögliche Aktionen, wie z. B. das Privatemachen von Dokumenten, das Speichern der Dateien, das Melden falsch positiver Übereinstimmungen und das Hinzufügen von Notizen für zukünftige Verweise. Diese E-Mails enthalten auch Links für Schulungsempfänger zur Behandlung dieser Fälle. Die Bereitstellung dieser Links ist erforderlich und sollte auf Ihre eigene interne Dokumentation zu Prozessen und bewährten Methoden verweisen.

Benachrichtigungen können für einzelne Richtlinien während der Erstellung benutzerdefinierter Richtlinien oder beim Bearbeiten einer Richtlinie aktiviert werden. Legen Sie Ihre Einstellungen im Abschnitt **"Ergebnisse" fest** .

Zu den erforderlichen Einstellungen gehören die Häufigkeit Ihrer Benachrichtigungen und Ihr Link zu Datenschutzschulungen.

Optionale Einstellungen umfassen bestimmte anpassbare Felder für Ihre E-Mails. Wählen Sie die **Option "Vorschau und Benachrichtigungs-E-Mail bearbeiten** " aus, um einen Flyoutbereich zu öffnen, in dem eine Beispielbenachrichtigung angezeigt wird. Hier können Sie die Betreffzeile der E-Mail, die Kopfzeile und den Textkörper sowie den Anzeigenamen und die URL für Ihre Datenschutzschulung bearbeiten.

Beachten Sie, dass die Allgemeine Fähigkeit des Datenschutzrisikomanagements zum Senden von E-Mail-Benachrichtigungen in **Einstellungen** gesteuert wird. Diese Anwendung ist standardmäßig aktiviert. Wenn Sie diese Einstellung deaktivieren, werden alle E-Mails beendet, auch wenn Benachrichtigungen auf einer einzelnen Richtlinienebene konfiguriert wurden.

## <a name="learn-about-settings-for-data-minimization-policies"></a>Informationen zu Einstellungen für Datenminimierungsrichtlinien

Richtlinien für die Datenminimierung konzentrieren sich auf das Alter Ihrer Inhalte und auf die Dauer, seit sie zuletzt geändert wurde. Die Überwachung auf personenbezogene Daten, die in älteren, ungenutzten Inhalten noch aufbewahrt werden, kann Ihnen helfen, Ihre gespeicherten Daten besser zu verwalten und Risiken zu reduzieren. Diese Einstellung wird auf dem Bildschirm **"Bedingungen"** behandelt.

Standardmäßig suchen Richtlinien zur Datenminimierung nach Inhalten, die personenbezogene Daten enthalten, die vor mindestens 30 Tagen erstellt oder zuletzt geändert wurden. Beim Bearbeiten oder Erstellen einer benutzerdefinierten Richtlinie können Sie aus anderen voreingestellten Zeitrahmen auswählen.

## <a name="learn-about-settings-for-data-transfer-policies"></a>Informationen zu Einstellungen für Datenübertragungsrichtlinien

Mithilfe von Datenübertragungsrichtlinien können Sie die Übertragung personenbezogener Daten außerhalb Ihrer Organisation sowie interne Übertragungen zwischen verschiedenen Abteilungen oder Ländern oder Regionen überwachen. Auf dem Bildschirm **"Bedingungen"** können Sie auswählen, nach welchen Arten von Übertragungen das Datenschutzrisikomanagement suchen soll.

Standardmäßig erkennen Datenübertragungsrichtlinien, wann personenbezogene Daten innerhalb Ihrer Organisation an einen Empfänger oder Standort außerhalb Ihrer Organisation übertragen oder für sie freigegeben werden. Beim Bearbeiten oder Erstellen einer benutzerdefinierten Richtlinie können Sie den Übertragungstyp auswählen und dann die Auswahl für die Absender- und Empfängerbereiche oder -abteilungen treffen.

Richtlinien für die Datenübertragung unterstützen auch die Bereitstellung von Richtlinientipps und Empfehlungen für Ihre Benutzer in Teams, damit sie über bewährte Methoden für den Umgang mit Daten informiert bleiben können. Dies kann **auf dem** Ergebnisbildschirm umgeschaltet werden.

## <a name="learn-about-settings-for-data-overexposure-policies"></a>Informationen zu Einstellungen für Datenüberbelichtungsrichtlinien

In Ihrer Organisation können Inhalte auf verschiedenen Zugriffsebenen gespeichert werden, darunter Bereiche, auf die öffentlich zugegriffen werden kann, und andere, die eingeschränkt sind. Auf dem Bildschirm **"Bedingungen"** können Sie festlegen, dass das Datenschutzrisikomanagement nach potenziellen Datenüberbelichtung für Inhalte sucht, die auf einer der folgenden Zugriffsebenen gespeichert sind:

- **Öffentlich**: Jeder Mit einem Link kann diesen Inhalt anzeigen.
- **Extern**: Bestimmte Personen außerhalb der Organisation haben Zugriff.
- **Intern**: Benutzer in Ihrer Organisation haben Zugriff.

Standardmäßig werten Datenüberbelichtungsrichtlinien alle drei Zugriffsebenen aus. Beim Bearbeiten oder Erstellen einer benutzerdefinierten Richtlinie können Sie alle oder eine dieser Ebenen auswählen.

## <a name="next-steps"></a>Nächste Schritte

Weitere Informationen dazu, wie Sie Ihre Richtlinien verwalten und Änderungen vornehmen, nachdem sie erstellt wurden, finden [Sie unter Verwalten von Richtlinien](risk-management-policies-manage.md).

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
