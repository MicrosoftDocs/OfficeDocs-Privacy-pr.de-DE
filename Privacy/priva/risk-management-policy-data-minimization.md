---
title: Datenminimierungsrichtlinien im Datenschutzrisikomanagement
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
description: Erfahren Sie, wie Sie eine Richtlinie zur Datenminimierung in Microsoft Priva Datenschutz-Risikomanagement erstellen, um die Menge nicht verwendeter personenbezogener Daten in Ihrer Organisation zu reduzieren.
ms.openlocfilehash: 251bd0ad73c840f818c945b7f68e4557299ad406
ms.sourcegitcommit: 3c83e8133a5a71f4e1d76a0b2981ab3ec9cd6602
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/13/2022
ms.locfileid: "66046619"
---
# <a name="data-minimization-policies-in-privacy-risk-management"></a>Datenminimierungsrichtlinien im Datenschutzrisikomanagement

Richtlinien für die Datenminimierung konzentrieren sich auf das Alter Ihrer Inhalte und auf die Dauer, seit sie zuletzt geändert wurde. Die Überwachung auf personenbezogene Daten, die in älteren, ungenutzten Inhalten noch aufbewahrt werden, kann Ihnen helfen, Ihre gespeicherten Daten besser zu verwalten und Risiken zu reduzieren.

Mit dem Datenschutzrisikomanagement können Sie Richtlinien erstellen, um Daten zu überwachen, die nicht innerhalb eines von Ihnen ausgewählten Zeitraums geändert wurden. Wenn eine Richtlinienübereinstimmung erkannt wird, können Sie Benutzern E-Mail-Benachrichtigungen mit Korrekturoptionen senden, z. B. das Markieren von Elementen zum Löschen, das Benachrichtigen von Inhaltsbesitzern oder das Kategorisieren von Elementen zur weiteren Überprüfung.

Unser Richtlinieneinrichtungsprozess erleichtert das Festlegen von Richtlinienbedingungen. Sie haben vollumfängliche Kontrolle über die Anzeigedauer und Häufigkeit von E-Mails, die die Aufmerksamkeit der Benutzer auf sichere Datenverarbeitungspraktiken lenken.

Es gibt zwei Möglichkeiten, wie Sie eine Richtlinie erstellen können: aus einer **Vorlage**, bei der es sich um unsere schnelle "out-of-box"-Option mit Standardeinstellungen handelt. oder die **benutzerdefinierte** Option, bei der es sich um einen geführten Prozess zum Festlegen von Bedingungen, Warnungen und Benachrichtigungen handelt.

## <a name="quick-setup-use-a-template-with-default-settings"></a>Schnelleinrichtung: Verwenden einer Vorlage mit Standardeinstellungen

Die Standardrichtlinie zur Datenminimierung erkennt Inhalte, die personenbezogene Daten enthalten, die vor mindestens 30 Tagen erstellt oder geändert wurden.

Führen Sie die folgenden Schritte aus, um eine Standardrichtlinie für die Datenübertragung zu erstellen:

1. Suchen Sie im [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/) im linken Navigationsbereich nach Priva Datenschutz-Risikomanagement, und wählen Sie **"Richtlinien"** aus.

2. Wählen Sie in der oberen rechten Ecke des Bildschirms die Option **"Richtlinie erstellen** " aus, in dem ein Flyoutbereich mit allen Richtlinienerstellungsoptionen angezeigt wird.

3. Wählen Sie im Feld **"Datenminimierung** " die Option " **Erstellen**" aus.

4. Ein Flyoutbereich enthält Richtliniendetails. Wenn Sie **"Ansichtseinstellungen"** auswählen, werden die Standardeinstellungen angezeigt. Sie können Einstellungen von hier aus bearbeiten, wodurch Sie in den unten beschriebenen geführten Prozess gelangen. Wenn Sie ihre Richtlinie weiterhin mithilfe der Standardeinstellungen erstellen möchten, geben Sie einfach einen beschreibenden Namen ein, und wählen Sie dann **"Richtlinie erstellen"** aus.

Ihre Richtlinie wird erstellt, und Sie finden sie auf Ihrer Seite " **Richtlinien** ". Sie beginnt im [Testmodus](risk-management-policies.md#testing-a-policy) , sodass Sie die Leistung überwachen können, bevor Sie sie aktivieren.

#### <a name="default-data-minimization-policy-settings"></a>Standardrichtlinieneinstellungen für die Datenminimierung

Eine datenminimierungsrichtlinie, die anhand der Vorlage erstellt wurde, erkennt Folgendes:
- Inhaltselemente mit personenbezogenen Daten, die in den letzten 30 Tagen nicht geändert wurden.
- Daten, die an einem dieser Speicherorte in Ihrer Organisation gespeichert sind: Exchange, OneDrive, SharePoint, Teams.
- Datentypen, die auf den folgenden [Klassifizierungsgruppen](risk-management-policies.md#classification-groups) basieren:
    - EU-Datenschutz-Grundverordnung (DSGVO)
    - Persönlich identifizierbare Informationen in den USA
    - US Patriot Act
    - US State Breach Notification Law
    - US Gramm-Leach-Bliley Act (GLBA)
    - US Health Insurance Portability and Accountability Act (HIPAA)
    - Australia Health Records Act (HRIP)
    - Datenschutzgesetz – Australien
    - Japan – persönlich identifizierbare Informationen
    - Schutz persönlicher Informationen – Japan

## <a name="custom-setup-guided-policy-creation-process"></a>Benutzerdefiniertes Setup: Geführter Richtlinienerstellungsprozess

Die benutzerdefinierte Richtlinienoption ist ein geführter Prozess zum Erstellen einer neuen Richtlinie durch Festlegen von Bedingungen, Festlegen des Schweregrads und der Häufigkeit von Warnungen und Aktivieren von Benutzer-E-Mail-Benachrichtigungen.

Führen Sie die folgenden Schritte aus, um eine neue Datenübertragungsrichtlinie zu erstellen:

1. Suchen Sie im [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/) im linken Navigationsbereich nach Priva Datenschutz-Risikomanagement, und wählen Sie **"Richtlinien"** aus.

2. Wählen Sie oben rechts auf dem Bildschirm die Schaltfläche " **Richtlinie erstellen** " aus, in der ein Flyoutbereich mit allen Richtlinienerstellungsoptionen angezeigt wird.

3. Wählen Sie im Feld **"Benutzerdefiniert** " die Option **"Erstellen**" aus.

4. Wählen Sie auf der Seite **"Name und Typ** " die Richtlinienvorlage " **Datenminimierung"** aus. Geben Sie auf der Seite **"Richtlinien** " einen Richtliniennamen ein, mit dem Sie ihn ganz einfach aus Ihrer Liste identifizieren können, geben Sie eine optionale Beschreibung ein, und wählen Sie dann **"Weiter**" aus.

5. Wählen Sie auf der Seite **"Zu überwachenden Daten** " den Typ der personenbezogenen Daten aus, die Ihre Richtlinie überwachen soll. Es gibt zwei Möglichkeiten:
    - **Klassifizierungsgruppen**: Gruppierungen vertraulicher Informationstypen, die verwendet werden, um Inhalte im Zusammenhang mit personenbezogenen Daten oder bestimmten Vorschriften zu erkennen. Wenn Sie diese Option auswählen, müssen Sie dann **+Klassifizierungsgruppen hinzufügen** auswählen, um eine oder mehrere Gruppen aus der bereitgestellten Liste auszuwählen.
    - **Einzelne Typen vertraulicher Informationen**: Wählen Sie diese Option aus, um aus einer Liste einzelner [vertraulicher Informationstypen](/microsoft-365/compliance/sensitive-information-type-entity-definitions) auszuwählen.

    Erfahren Sie mehr über die [Auswahl der zu überwachenden Daten](risk-management-policies.md#choose-data-to-monitor). Wenn Sie mit der Auswahl der zu überwachenden Daten fertig sind, wählen Sie **"Weiter**" aus.

6. Wählen Sie auf der Seite **"Benutzer und Gruppen** " aus, für welche Benutzer in Ihrer Organisation die Richtlinie gelten soll. Sie können alle einzelnen Benutzer und alle Office 365 Verteilergruppen oder bestimmte Benutzer und Gruppen auswählen. Erfahren Sie mehr über die [Auswahl von Benutzern und Gruppen](risk-management-policies.md#choose-users-and-groups). Wenn Sie fertig sind, wählen Sie **Weiter**.

7. Wählen Sie auf der Seite "**Speicherorte**" alle Datenspeicherorte in Microsoft 365 aus, die von der Richtlinie abgedeckt werden sollen. Wählen Sie aus Exchange E-Mail-Konten, OneDrive Konten, Teams Chat- und Kanalnachrichten sowie SharePoint Websites aus.

    Innerhalb SharePoint können Sie alle Websites oder bestimmte Websites festlegen. Wenn Sie **"Bestimmte SharePoint Websites**" auswählen, können Sie die Website-URL in das URL-Feld eingeben. Sie können auch **"Websites auswählen**" auswählen und dann im Flyoutbereich das Kontrollkästchen links neben dem Websitenamen aktivieren, den Sie auswählen möchten.

    Weitere Informationen zum [Auswählen von Speicherorten](risk-management-policies.md#choose-locations). Wenn Sie mit der Auswahl von Speicherorten fertig sind, wählen Sie **"Weiter**" aus.

8. Verwenden Sie auf der Seite **"Bedingungen"** das Dropdownmenü, um auszuwählen, wie viele Tage seit der letzten Änderung eines Elements von der Richtlinie erkannt werden:
    - 30 Tage
    - 60 Tage
    - 90 Tage
    - 120 Tage
    
     Wenn Sie fertig sind, wählen Sie **Weiter**.

9. Entscheiden Sie auf der Seite **"Ergebnisse** ", ob Benutzer benachrichtigt werden sollen, wenn sie die in der Richtlinie festgelegten Bedingungen erfüllen. Wenn Sie das Kontrollkästchen für E-Mail-Benachrichtigungen aktivieren, erhalten Benutzer eine E-Mail-Benachrichtigung, wenn ihre Aktionen den Richtlinienbedingungen entsprechen. E-Mails enthalten Anweisungen, um Abhilfemaßnahmen direkt aus der E-Mail zu ergreifen, zusammen mit einem Link zu Datenschutzschulungen. Sie bestimmen die Häufigkeit von E-Mails und die URL für Ihre bevorzugte Datenschutzschulung.
     
    Erfahren Sie mehr über das Einrichten von [Benutzerbenachrichtigungen](risk-management-notifications.md). Wenn Sie mit der Auswahl der Ergebnisse fertig sind, wählen Sie **"Weiter**" aus.

10. Verwenden Sie auf der Seite **"Warnungen** " den Umschalter, um Warnungen zu aktivieren, die einem Administrator auf der Seite **"Warnungen** " im Abschnitt **"Richtlinien** " des Datenschutzrisikomanagements angezeigt werden. Sie werden festlegen, wie häufig Warnungen generiert werden, Schwellenwerte für Übereinstimmungen, bevor Warnungen generiert werden, und den Warnungsschweregrad. Weitere Informationen zum [Festlegen von Warnungen für Richtlinienübereinstimmungen](risk-management-policies.md#set-alerts). Wenn Sie fertig sind, wählen Sie **Weiter**.

11. Entscheiden Sie auf der Seite **"Modus** ", ob Sie Ihre Richtlinie beim ersten Erstellen im Testmodus ausführen möchten, was bedeutet, dass keine Benachrichtigungen oder Benachrichtigungen gesendet werden. Um Ihre Richtlinie im Testmodus zu halten, den wir empfehlen, wählen Sie den Umschalter **auf die** Ein-Position aus. Erfahren Sie mehr über [das Testen einer Richtlinie](risk-management-policies.md#testing-a-policy).

> [!NOTE]
> Wenn Sie den Schalter " **Im Testmodus ausführen** " auf die " **Aus** "-Position umschalten, *wird Ihre Richtlinie aktiviert* , wenn Sie die Erstellung abgeschlossen haben. Dies bedeutet, dass alle von Ihnen eingerichteten Benachrichtigungen oder Benutzerbenachrichtigungen generiert werden, sobald eine Übereinstimmung erkannt wird.

12. Überprüfen Sie auf der Seite **"Fertig stellen** " Ihre Auswahlmöglichkeiten. Wählen Sie unter einem der Abschnitte " **Bearbeiten** " aus, um die Einstellungen anzupassen. Wenn Sie mit den Einstellungen Ihrer Richtlinie zufrieden sind, wählen Sie **"Absenden** " aus, um die Richtlinie zu erstellen.

Nach ein paar Sekunden wird eine Bestätigung angezeigt, dass die Richtlinie erstellt wurde. Wählen Sie " **Fertig** " auf der Bestätigungsseite aus, auf der Sie zur Seite **"Richtlinien** " gelangen, auf der die neue Richtlinie oben in der Tabelle angezeigt wird.

## <a name="next-steps"></a>Nächste Schritte

Weitere Informationen zum Bearbeiten und Verwalten von Richtlinien finden Sie in den [Richtlinien des Datenschutzrisikomanagements](risk-management-policies.md) .