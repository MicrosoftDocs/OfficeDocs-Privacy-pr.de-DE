---
title: Datenüberbelichtungsrichtlinien im Datenschutz-Risikomanagement
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
description: Erfahren Sie, wie Sie eine Richtlinie zur Datenüberbelichtung in Microsoft Priva Privacy Risk Management erstellen, um personenbezogene Daten zu identifizieren und zu sichern, die möglicherweise übermäßig zugänglich sind.
ms.openlocfilehash: a0c87a84a78206862d9a79e1c16d17a90de5f040
ms.sourcegitcommit: b5f7dcb73c0e3f677981e80106769cb546d00af4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/21/2022
ms.locfileid: "65014505"
---
# <a name="data-overexposure-policies-in-privacy-risk-management"></a>Datenüberbelichtungsrichtlinien im Datenschutz-Risikomanagement

In Ihrer Organisation können Inhalte auf verschiedenen Zugriffsebenen gespeichert werden, darunter Bereiche, auf die öffentlich zugegriffen werden kann, und andere, die eingeschränkt sind. Datenüberbelichtungsrichtlinien können Ihnen helfen, Situationen zu erkennen und zu behandeln, in denen von Ihrer Organisation gespeicherte Daten nicht ausreichend sicher sind. Wenn beispielsweise der Zugriff auf eine interne Website für zu viele Personen geöffnet ist oder Ihre Berechtigungseinstellungen nicht beibehalten wurden, können personenbezogene Daten, die auf dieser Website gespeichert sind, anfällig für eine Verletzung sein. Datenüberbelichtungsrichtlinien können Ihre Daten für diese Risiken auswerten und Sie auf potenzielle Probleme aufmerksam machen.

Wenn eine Richtlinienübereinstimmung erkannt wird, können Sie Benutzern E-Mail-Benachrichtigungen senden, die Korrekturoptionen enthalten, um Probleme zu beheben. Bei der Datenüberbelichtung umfassen dies das Privatemachen von Inhaltselementen, das Benachrichtigen von Inhaltsbesitzern oder das Kategorisieren von Elementen zur weiteren Überprüfung.

Unser Richtlinieneinrichtungsprozess erleichtert das Festlegen von Richtlinienbedingungen. Sie haben vollumfängliche Kontrolle über die Anzeigedauer und Häufigkeit von E-Mails, die die Aufmerksamkeit der Benutzer auf sichere Datenverarbeitungspraktiken lenken.

Es gibt zwei Möglichkeiten, wie Sie eine Richtlinie erstellen können: aus einer **Vorlage**, bei der es sich um unsere schnelle "out-of-box"-Option mit Standardeinstellungen handelt. oder die **benutzerdefinierte** Option, bei der es sich um einen geführten Prozess zum Festlegen von Bedingungen, Warnungen und Benachrichtigungen handelt.

## <a name="quick-setup-use-a-template-with-default-settings"></a>Schnelleinrichtung: Verwenden einer Vorlage mit Standardeinstellungen

Die Standardrichtlinie für die Überbelichtung von Daten wertet personenbezogene Daten auf allen drei Zugriffsebenen aus: öffentlich, extern und intern.

Führen Sie die folgenden Schritte aus, um eine Standardrichtlinie für die Datenübertragung zu erstellen:

1. Suchen Sie im [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) priva Privacy Risk Management im linken Navigationsbereich, und wählen Sie **"Richtlinien"** aus.

2. Wählen Sie in der oberen rechten Ecke des Bildschirms die Option **"Richtlinie erstellen** " aus, in dem ein Flyoutbereich mit allen Richtlinienerstellungsoptionen angezeigt wird.

3. Wählen Sie im Feld **"Datenüberbelichtung** " die Option " **Erstellen**" aus.

4. Ein Flyoutbereich enthält Richtliniendetails. Wenn Sie **"Ansichtseinstellungen"** auswählen, werden die Standardeinstellungen angezeigt. Sie können Einstellungen von hier aus bearbeiten, wodurch Sie in den unten beschriebenen geführten Prozess gelangen. Wenn Sie ihre Richtlinie weiterhin mithilfe der Standardeinstellungen erstellen möchten, geben Sie einfach einen beschreibenden Namen ein, und wählen Sie dann **"Richtlinie erstellen"** aus.

Ihre Richtlinie wird erstellt, und Sie finden sie auf Ihrer Seite " **Richtlinien** ". Sie beginnt im [Testmodus](risk-management-policies.md#testing-a-policy) , sodass Sie die Leistung überwachen können, bevor Sie sie aktivieren.

#### <a name="default-data-overexposure-policy-settings"></a>Standardrichtlinieneinstellungen für die Überbelichtung von Daten

Eine aus der Vorlage erstellte Datenüberbelichtungsrichtlinie erkennt Folgendes:

- Wenn ein Benutzer einen überdimensionalen Zugriff auf Elemente bietet, die personenbezogene Daten enthalten, die in den OneDrive oder SharePoint Ihrer Organisation gespeichert sind. Die Richtlinie erkennt beispielsweise die Freigabe personenbezogener Daten auf folgende Weise:
    - Über einen Link, auf den jeder in der Öffentlichkeit zugreifen kann
    - Über einen Link oder aufgrund von Berechtigungen, mit denen jeder in der Organisation auf den Zugriff zugreifen kann
    - Gewähren von Zugriffsrechten für externe Benutzer oder Gäste für OneDrive oder SharePoint Dateien
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

Führen Sie die folgenden Schritte aus, um eine neue Richtlinie für die Datenüberbelichtung zu erstellen:

1. Suchen Sie im [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) priva Privacy Risk Management im linken Navigationsbereich, und wählen Sie **"Richtlinien"** aus.

2. Wählen Sie oben rechts auf dem Bildschirm die Schaltfläche " **Richtlinie erstellen** " aus, in der ein Flyoutbereich mit allen Richtlinienerstellungsoptionen angezeigt wird.

3. Wählen Sie im Feld **"Benutzerdefiniert** " die Option **"Erstellen**" aus.

4. Wählen Sie auf der Seite **"Name und Typ** " die Richtlinienvorlage " **Datenüberbelichtung** " aus. Geben Sie auf der Seite **"Richtlinien** " einen Richtliniennamen ein, mit dem Sie ihn ganz einfach aus Ihrer Liste identifizieren können, geben Sie eine optionale Beschreibung ein, und wählen Sie dann **"Weiter**" aus.

5. Wählen Sie auf der Seite **"Zu überwachenden Daten** " den Typ der personenbezogenen Daten aus, die Ihre Richtlinie überwachen soll. Es gibt zwei Möglichkeiten:
    - **Klassifizierungsgruppen**: Gruppierungen vertraulicher Informationstypen, die verwendet werden, um Inhalte im Zusammenhang mit personenbezogenen Daten oder bestimmten Vorschriften zu erkennen. Wenn Sie diese Option auswählen, müssen Sie dann **+Klassifizierungsgruppen hinzufügen** auswählen, um eine oder mehrere Gruppen aus der bereitgestellten Liste auszuwählen.
    - **Einzelne Typen vertraulicher Informationen**: Wählen Sie diese Option aus, um aus einer Liste einzelner [vertraulicher Informationstypen](/microsoft-365/compliance/sensitive-information-type-entity-definitions) auszuwählen.

    Erfahren Sie mehr über die [Auswahl der zu überwachenden Daten](risk-management-policies.md#choose-data-to-monitor). Wenn Sie mit der Auswahl der zu überwachenden Daten fertig sind, wählen Sie **"Weiter**" aus.

6. Wählen Sie auf der Seite **"Benutzer und Gruppen** " aus, für welche Benutzer in Ihrer Organisation die Richtlinie gelten soll. Sie können alle einzelnen Benutzer und alle Office 365 Verteilergruppen oder bestimmte Benutzer und Gruppen auswählen. Erfahren Sie mehr über die [Auswahl von Benutzern und Gruppen](risk-management-policies.md#choose-users-and-groups). Wenn Sie fertig sind, wählen Sie **Weiter**.

7. Wählen Sie auf der Seite "**Speicherorte**" alle Datenspeicherorte in Microsoft 365 aus, die von der Richtlinie abgedeckt werden sollen. Wählen Sie aus OneDrive Konten und SharePoint Websites aus.

    Innerhalb SharePoint können Sie alle Websites oder bestimmte Websites festlegen. Wenn Sie **"Bestimmte SharePoint Websites**" auswählen, können Sie die Website-URL in das URL-Feld eingeben. Sie können auch **"Websites auswählen**" auswählen und dann im Flyoutbereich das Kontrollkästchen links neben dem Websitenamen aktivieren, den Sie auswählen möchten.

    Weitere Informationen zum [Auswählen von Speicherorten](risk-management-policies.md#choose-locations). Wenn Sie mit der Auswahl von Speicherorten fertig sind, wählen Sie **"Weiter**" aus.

8. Wählen Sie auf der Seite **"Bedingungen"** den Typ der Datenüberbelichtungsbedingung aus, die von der Richtlinie erkannt wird:
    - **Öffentlich**: Jeder Mit einem Link kann auf Inhalte zugreifen.
    - **Extern**: Bestimmte Personen außerhalb der Organisation haben Zugriff.
    - **Intern**: Alle Benutzer in Ihrer Organisation haben Zugriff.
    
    Wenn Sie mehr als eine Zugriffsebene auswählen, erweitert sich der Umfang der Daten und kann zu erheblich größeren Mengen an Warnungen und Benutzerbenachrichtigungen führen.

    Aktivieren Sie das Kontrollkästchen neben Ihren Auswahlmöglichkeiten, und wählen Sie dann **"Weiter**" aus.

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