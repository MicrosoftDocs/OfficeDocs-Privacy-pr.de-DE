---
title: Datenschutz-Risikomanagementrichtlinien
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
description: Erfahren Sie, wie Sie Richtlinien in Microsoft Priva Privacy Risk Management zum Umgang mit den personenbezogenen Daten Ihrer Organisation in Microsoft 365 erstellen und verwalten.
ms.openlocfilehash: 87671cedc8c6cba75d5ad207b52831cdd2467187
ms.sourcegitcommit: b5f7dcb73c0e3f677981e80106769cb546d00af4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/21/2022
ms.locfileid: "65014495"
---
# <a name="privacy-risk-management-policies"></a>Datenschutz-Risikomanagementrichtlinien

Datenschutz-Risikomanagementrichtlinien können Ihnen dabei helfen, Risikoszenarien zu beheben, die für Ihre Organisation wichtig sind. Unsere Richtlinienvorlagen konzentrieren sich auf die Förderung solider Datenverarbeitungspraktiken.  Benachrichtigungen informieren Administratoren, wenn Richtlinienübereinstimmungen erkannt werden und möglicherweise weitere Untersuchungen erforderlich sind. E-Mail-Benachrichtigungen und Tipps in Microsoft Teams helfen Benutzern zu verstehen, welche Aktivitäten Datenschutzrisiken mit sich bringen, ermöglicht es Benutzern, Probleme sofort zu beheben, und verweist auf Datenschutzschulungen.

Verwenden Sie für einen Schnellstart eine Vorlage mit Standardeinstellungen, um neue Richtlinien für die Überbelichtung von Daten, Datenübertragungen und Datenminimierung und Szenarien zu erstellen. Sie können auch Vorlageneinstellungen anpassen, um Richtlinien zu erstellen, die den Anforderungen Ihrer Organisation entsprechen.

## <a name="policy-template-types"></a>Richtlinienvorlagentypen

Das Datenschutzrisikomanagement verfügt über drei Richtlinienvorlagen, die Ihnen dabei helfen sollen, wichtige Problembereiche im Bereich des Schutzes personenbezogener Daten zu behandeln. Jede Vorlage verfügt über Standardeinstellungen, die Sie im Schnelleinrichtungsprozess akzeptieren oder mithilfe eines geführten Prozesses anpassen können. Wenn Sie eine neue Richtlinie erstellen, besteht Ihre erste Aufgabe darin, eine der drei unten aufgeführten Vorlagen auszuwählen:

- **Datenüberbelichtung**: Diese Richtlinie identifiziert Inhaltselemente, die personenbezogene Daten enthalten, auf die andere Personen möglicherweise zu allgemein zugreifen können. Wenn Übereinstimmungen gefunden werden, können Sie Benachrichtigungen einrichten, in denen Inhaltsbesitzer aufgefordert werden, schnell Schutz anzuwenden.

- **Datenübertragungen**: Diese Richtlinie kann personenbezogene Datenübertragungen über von Ihnen festgelegte Grenzen hinweg erkennen, was übertragungen außerhalb Ihrer Organisation oder interne Übertragungen über Abteilungen oder geografische Regionen hinweg umfassen kann. Wenn Übereinstimmungen gefunden werden, können Sie Benachrichtigungen einrichten, die Absender ermutigen, den Zugriff auf den Inhalt zu widerrufen.

- **Datenminimierung**: Diese Richtlinie identifiziert Inhaltselemente, die personenbezogene Daten enthalten, die über einen längeren Zeitraum nicht betroffen sind. Wenn Übereinstimmungen gefunden werden, können Sie Benachrichtigungen an Inhaltsbesitzer senden, die sie auffordern, schnelle Maßnahmen zu ergreifen, um das Element zu behalten oder zu löschen.

## <a name="quick-setup-using-a-template-with-default-settings"></a>Schnelleinrichtung: Verwenden einer Vorlage mit Standardeinstellungen

Wenn Sie eine Richtlinie direkt aus einer Vorlage erstellen, werden die meisten Einstellungen automatisch ausgewählt, damit Sie schnell loslegen können. Führen Sie die folgenden Schritte aus, um eine Richtlinie mit Standardeinstellungen mithilfe einer unserer Vorlagen zu erstellen:

1. Suchen Sie im [Microsoft Purview Compliance Center](https://compliance.microsoft.com/) im linken Navigationsbereich nach Priva Privacy Risk Management, und wählen Sie **"Richtlinien**" aus.

2. Wählen Sie in der oberen rechten Ecke des Bildschirms die Option **"Richtlinie erstellen** " aus, in dem ein Flyoutbereich mit allen Richtlinienerstellungsoptionen angezeigt wird.

3. Suchen Sie den Typ der Richtlinie, die Sie erstellen möchten, und wählen Sie auf seiner Karte " **Erstellen"** aus.

4. Ein Flyoutbereich enthält Richtliniendetails. Wenn Sie **"Ansichtseinstellungen"** auswählen, werden die Standardeinstellungen angezeigt. Sie können Einstellungen von hier aus bearbeiten, wodurch Sie in den unten beschriebenen geführten Prozess gelangen. Wenn Sie ihre Richtlinie weiterhin mithilfe der Standardeinstellungen erstellen möchten, geben Sie einfach einen beschreibenden Namen ein, und wählen Sie dann **"Richtlinie erstellen"** aus.

Ihre Richtlinie wird erstellt, und Sie finden sie auf Ihrer Seite **"Richtlinien** ".

Die Richtlinie wird im Testmodus ausgeführt, was bedeutet, dass keine Warnungen oder Benachrichtigungen generiert werden, und Sie können die Leistung überwachen. Wenn Sie bereit sind, Ihre Richtlinie zu aktivieren, wählen Sie Ihre Richtlinie aus, und bearbeiten Sie sie, um sie zu aktivieren.

## <a name="custom-setup-guided-process-to-choose-all-settings"></a>Benutzerdefiniertes Setup: Geführter Prozess zum Auswählen aller Einstellungen

Die benutzerdefinierte Richtlinienoption ist ein geführter Prozess zum Erstellen einer Richtlinie. Sie beginnen mit der Auswahl einer Vorlage und durchlaufen dann jede Einstellung, um Ihre Richtlinie anzupassen. Die nachstehenden Anweisungen enthalten Details zu grundlegenden Einstellungen, die für jeden der drei Richtlinientypen gelten. Wenn sich die Einstellungen je nach Richtlinientyp unterscheiden, verknüpfen wir sie mit bestimmten Anweisungen.

Führen Sie die folgenden Schritte aus, um eine Richtlinie zu erstellen:

1. Suchen Sie im [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) priva Privacy Risk Management im linken Navigationsbereich. Wählen Sie im Dropdownmenü " **Richtlinien**" aus.

2. Wählen Sie **Richtlinie erstellen** aus.

3. Wählen Sie die Option **"Benutzerdefiniert** " aus, um Ihre Richtlinie mithilfe des Richtlinienerstellungs-Assistenten im Datenschutzrisikomanagement zu erstellen.

4. Wählen Sie den Typ der Richtlinie aus: **Datenüberbelichtung,** **Datenübertragung** oder **Datenminimierung**.

5. Geben Sie Ihrer Richtlinie einen aussagekräftigen Namen, damit Sie sie in Ihrer Liste der Richtlinien identifizieren können. Geben Sie eine optionale Beschreibung an, und wählen Sie dann **"Weiter**" aus.

6. Mit den nächsten Schritten können Sie alle Richtlinieneinstellungen definieren. Sie können zu Beschreibungen in diesem Artikel springen, um weitere Details zu erhalten. Die folgenden Optionen stehen zur Verfügung:
    - [**Zu überwachenden Daten**](#choose-data-to-monitor): Wählen Sie den Typ der personenbezogenen Daten aus, die Ihre Richtlinie überwacht.
    - [**Benutzer und Gruppen**](#choose-users-and-groups): Wenden Sie Ihre Richtlinie auf alle Benutzer oder ausgewählten Benutzer an.
    - [**Speicherorte**](#choose-locations): Wenden Sie Ihre Richtlinie auf ausgewählte Bereiche in Microsoft 365 an.
    - [**Bedingungen**](#set-conditions): Legen Sie die Bedingungen für Ihre Richtlinie fest. Diese Optionen variieren je nach Richtlinientyp.
    - [**Ergebnisse**](#define-outcomes-user-email-notifications-and-tips): Definieren Sie die Ergebnisse, wenn eine Richtlinienübereinstimmung gefunden wird, z. B. Benutzer-E-Mail-Benachrichtigungen.
    - [**Warnungen**](#set-alerts): Entscheiden Sie die Häufigkeit von Warnungen für Administratoren, wenn eine Richtlinienübereinstimmung gefunden wird.
    - [**Modus**](#testing-a-policy): Wählen Sie aus, ob Ihre Richtlinie zuerst im Testmodus ausgeführt werden soll.
7. Wenn alle Einstellungen abgeschlossen sind, überprüfen Sie Ihre Auswahl, nehmen Sie alle gewünschten Änderungen vor, und wählen Sie dann **"Absenden** " aus, um die Richtlinie zu erstellen.

Nach ein paar Sekunden wird eine Bestätigung angezeigt, dass die Richtlinie erstellt wurde. Wählen Sie " **Fertig** " auf der Bestätigungsseite aus, auf der Sie zur Seite **"Richtlinien** " gelangen, auf der die neue Richtlinie oben in der Tabelle angezeigt wird.

Die folgenden Abschnitte enthalten weitere Details zu den einzelnen Richtlinieneinstellungen.

## <a name="choose-data-to-monitor"></a>Daten auswählen, die überwacht werden sollen

Beim Erstellen oder Bearbeiten einer Richtlinie werden Sie aufgefordert, auszuwählen, welche Datentypen die Richtlinie überwachen soll. Es gibt zwei Möglichkeiten:

- **Klassifizierungsgruppen**: Eine durchsuchbare Liste von Gruppierungen vertraulicher Informationstypen; Beispielsweise eine Gruppe, die auf dem Australia Health Records Act basiert, oder eine Gruppe, die auf persönlich identifizierbaren US-Informationen basiert, z. B. eine US-Reisepassnummer.

- **Einzelne Typen vertraulicher Informationen**: Eine durchsuchbare Liste vertraulicher Informationstypen; z. B. Sozialversicherungsnummern oder Führerscheinnummern.

Wenn Sie aus den vorhandenen Klassifizierungsgruppen auswählen, können Sie nicht auch einzelne Typen auswählen oder eigene Gruppen erstellen. Um die größtmögliche Flexibilität zu bieten, wählen Sie einzelne Typen vertraulicher Informationen aus. Um die gängigsten Standards zu verwenden, wählen Sie aus den Klassifizierungsgruppen aus. Weitere Informationen zu den einzelnen Datentypen finden Sie unten.

### <a name="classification-groups"></a>Klassifizierungsgruppen

Klassifizierungsgruppen sind Gruppierungen vertraulicher [Informationstypen](/microsoft-365/compliance/sensitive-information-type-entity-definitions) , die verwendet werden, um Inhalte im Zusammenhang mit personenbezogenen Daten oder bestimmten Vorschriften zu erkennen.

Wenn Sie diese Option auf der Seite " **Zu überwachende Daten** " auswählen, müssen Sie **"+Klassifizierungsgruppen hinzufügen"** auswählen und eine oder mehrere Gruppen aus der Liste auswählen, die in einem Flyoutbereich angezeigt wird.

### <a name="individual-sensitive-information-types"></a>Einzelne Typen vertraulicher Informationen

Indem Sie bestimmte [Typen vertraulicher Informationen](/microsoft-365/compliance/sensitive-information-type-entity-definitions) auswählen, z. B. Sozialversicherungsnummern oder Führerscheininformationen, können Sie Ihre eigene Gruppe oder Gruppen von Daten anpassen, um nach ihnen zu suchen. Sie können aus der vollständigen Liste der Typen vertraulicher Informationen innerhalb des Datenschutzrisikomanagements auswählen. Jeder Informationstyp verfügt über eigene Eigenschaften.

Wenn Sie diese Option auf der Seite " **Zu überwachenden Daten** " auswählen, wird eine Auswahl mit **der Standardeinstellung** als Name für die Gruppe der typen vertraulicher Informationen angezeigt, die Sie auswählen. Behalten Oder bearbeiten Sie diesen Gruppennamen, und wählen Sie dann **"Hinzufügen"** aus, um einen oder mehrere Typen vertraulicher Informationen aus der vollständigen Liste im Datenschutzrisikomanagement auszuwählen. Jeder Informationstyp verfügt über eigene Eigenschaften und empfohlene Einstellungen, die Sie ermitteln können, indem Sie das Infosymbol rechts neben dem Dropdownmenü "Konfidenz" auswählen, nachdem Sie den Infotyp hinzugefügt haben. Sie können auch die Instanzanzahl für jeden vertraulichen Informationstyp ändern. Diese Einstellung gibt die Anzahl der eindeutigen Instanzen jedes vertraulichen Informationstyps an, den Ihre Richtlinie erkennen soll.

Wenn Sie mehr als eine Gruppe erstellen, können Sie mit dem Assistenten auswählen, wie die Gruppen in Beziehung stehen sollen (eine "und"- oder "oder"-Beziehung) und deren Reihenfolge der Vorgänge definieren.

## <a name="choose-users-and-groups"></a>Auswählen von Benutzern und Gruppen

Sie haben zwei Optionen, um zu entscheiden, welche Benutzer eine Richtlinie abdecken soll: alle Benutzer und Gruppen oder bestimmte Benutzer und Gruppen.

- **Alle Benutzer und Gruppen**: Diese Option wendet die Richtlinie auf alle Benutzer und Office 365 Gruppen in Ihrer Organisation an.

- **Bestimmte Benutzer oder Gruppen**: Mit dieser Option können Sie einzelne Benutzer, einzelne Office 365 Gruppen oder eine Kombination aus beidem auswählen.
  - **So wählen Sie Benutzer** aus: Wählen **Sie "Benutzer auswählen** " aus, und suchen Sie im Flyoutbereich nach einem Benutzer, indem Sie eine E-Mail-Adresse in das Suchfeld eingeben. Oder suchen Sie den Benutzer aus der Liste, und aktivieren Sie das Kontrollkästchen links neben dem Namen. Sie können bis zu 100 Benutzer auswählen. Wenn Sie fertig sind, wählen Sie **"Hinzufügen" aus.**
  - **Zum Auswählen von Gruppen**: Wählen Sie **"Gruppen auswählen** " aus, und aktivieren Sie im Flyoutbereich das Kontrollkästchen links neben den einzelnen Gruppennamen. Sie können bis zu zehn Gruppen auswählen. Wenn Sie fertig sind, wählen Sie **"Hinzufügen"** aus.

Nachdem Sie Benutzer und Gruppen festgelegt haben, wählen Sie **"Weiter** " aus, um zum nächsten Schritt zu wechseln.

## <a name="choose-locations"></a>Speicherorte wählen

In diesem Schritt bestimmen Sie, wo in Ihrer Microsoft 365 Umgebung die Richtlinie nach Übereinstimmungen mit personenbezogenen Daten suchen soll. Die Standortoptionen hängen vom Richtlinientyp ab, und Sie können mehrere auswählen. Jeder der Standorte wird im Folgenden erläutert.

- **Exchange**: Die Richtlinie identifiziert Übereinstimmungen in den Exchange Konten von Benutzern, die Inhalte im Textkörper von E-Mails und in Anlagen enthalten, die von Exchange Postfächern gesendet oder empfangen werden.

- **OneDrive**: Die Richtlinie identifiziert Übereinstimmungen in Dateien, die im OneDrive for Business Konto des Benutzers gespeichert sind.

- **Teams**: Die Richtlinie identifiziert Übereinstimmungen in den Nachrichten von Benutzern in Teams Kanälen und Chats.

- **SharePoint**: Die Richtlinie identifiziert Übereinstimmungen in Dateien, die auf SharePoint Websites von Benutzern gespeichert sind. Wenn Sie diese Option auswählen, wählen Sie zwischen den folgenden Optionen aus:
    - **Alle SharePoint Websites**: Diese Auswahl deckt alle Websites für alle Benutzer in Ihrer Organisation ab.

    - **Bestimmte SharePoint Websites**: Diese Auswahl fordert Sie auf, bestimmte Websites für die Richtlinie festzulegen, auf die sie angewendet werden soll. Sie können die URL einer bestimmten Website direkt in das URL-Feld eingeben und dann das **+** Zeichen auswählen, um es Ihrer Liste der Websites hinzuzufügen. Sie können auch **"Websites auswählen**" auswählen und im Flyoutbereich in der Liste der Websites, auf die Sie Zugriff haben, suchen und auswählen. Aktivieren Sie das Kontrollkästchen, das angezeigt wird, wenn Sie mit der Maus auf die Website zeigen, die Sie auswählen möchten. Nachdem Sie Ihre Auswahl getroffen haben, wählen Sie **"Hinzufügen"** aus.  Alle von Ihnen ausgewählten Websites werden unten auf der Seite " **Speicherorte** " aufgelistet.
    
    > [!TIP]
    > Wenn Sie Hilfe beim Identifizieren der SharePoint Websites in Ihrer Organisation benötigen, besuchen Sie ["Websites verwalten" im SharePoint Admin Center](/sharepoint/manage-sites-in-new-admin-center).

Nachdem Sie die Standortdefinierung abgeschlossen haben, wählen Sie **"Weiter**" aus.

## <a name="set-conditions"></a>Festlegen von Bedingungen

Die Bedingungen für das Erkennen von Richtlinienübereinstimmungen unterscheiden sich je nach Richtlinienvorlage.

- **Datenüberbelichtung**: Verweisen Sie auf den Bedingungsschritt in den [benutzerdefinierten Einrichtungsanweisungen der Datenbelichtungsrichtlinie](risk-management-policy-data-overexposure.md#custom-setup-guided-policy-creation-process).
- **Datenübertragungen**: Lesen Sie den Bedingungsschritt in den [benutzerdefinierten Einrichtungsanweisungen für die Datenübertragungsrichtlinie](risk-management-policy-data-transfer.md#custom-setup-guided-policy-creation-process).
- **Datenminimierung**: Lesen Sie den Bedingungsschritt in den [benutzerdefinierten Setupanweisungen der Datenminimierungsrichtlinie](risk-management-policy-data-minimization.md#custom-setup-guided-policy-creation-process).

## <a name="define-outcomes-user-email-notifications-and-tips"></a>Definieren von Ergebnissen: E-Mail-Benachrichtigungen und Tipps für Benutzer

Die Ergebniseinstellungen werden auf der Seite **"Ergebnisse** " des Richtlinienerstellungs-Assistenten behandelt. Auf dieser Seite können Sie eine E-Mail-Benachrichtigung an Benutzer senden, wenn diese eine Aktion ausführen, die den Bedingungen einer Richtlinie entspricht.

Datenübertragungsrichtlinien haben eine zusätzliche Option, um Benutzern in Teams Tipps anzuzeigen, wenn ihre Aktionen eine Richtlinienübereinstimmung generieren. Diese Tipps enthalten Links zu Datenschutzschulungen, die Sie bereitstellen, sowie Mechanismen zur Behebung potenzieller Risiken.

Diese Benachrichtigungen können hilfreiche Möglichkeiten sein, um zu verhindern, dass Probleme eskalieren, und um die Fähigkeiten und das Vertrauen der Benutzer in die Einführung sicherer Datenverarbeitungspraktiken zu stärken.

Besuchen Sie [Benutzerbenachrichtigungen im Datenschutzrisikomanagement](risk-management-notifications.md) , um mehr über das Arbeiten mit Benutzerbenachrichtigungen zu erfahren.

## <a name="set-alerts"></a>Festlegen von Warnungen

Benachrichtigungen helfen Administratoren zu wissen, wann ein Benutzerereignis den Bedingungen einer Richtlinie entspricht. Das Einrichten von Warnungen ist optional, und Sie steuern, wie oft Warnungen generiert werden, den Schwellenwert, der erreicht werden muss, bevor eine Warnung generiert wird, und den Schweregrad der Warnung. Warnungen werden auf der Karte **"Warnungen** " auf der Seite **"Richtlinien"** angezeigt. Erfahren Sie mehr über [das Anzeigen, Untersuchen und Beheben von Warnungen](risk-management-alerts.md).

#### <a name="turn-on-alerts"></a>Aktivieren von Warnungen

Sie können Warnungen aktivieren, wenn Sie eine Richtlinie zum ersten Mal erstellen, oder die Richtlinie später bearbeiten, um sie zu aktivieren. Legen Sie auf der Seite **"Warnungen** " des Richtlinienerstellungs-Assistenten den Umschalter " **Warnungen erstellen** " auf die Position " **Ein** " fest.

#### <a name="alert-frequency-and-thresholds"></a>Warnungshäufigkeit und Schwellenwerte
Nachdem Sie Warnungen aktiviert haben, entscheiden Sie, wie oft sie generiert werden.

- **Warnung jedes Mal, wenn eine Richtlinienübereinstimmung auftritt**: Wenn Sie diese Option auswählen, kann dies zu einer hohen Anzahl von Warnungen führen.
- **Warnung, wenn ein bestimmter Schwellenwert erreicht ist**: Sie legen Schwellenwerte basierend auf der Anzahl und Häufigkeit der erkannten Benutzerereignisse fest.

#### <a name="alert-severity-level"></a>Warnungsschweregrad
Wählen Sie den Schweregrad "Niedrig", "Mittel" oder "Hoch" aus. Wir empfehlen Ihrer Organisation, zu definieren, was jede Ebene für Sie darstellt.

## <a name="testing-a-policy"></a>Testen einer Richtlinie

Wenn Sie eine Richtlinie erstellen, wird sie standardmäßig im Testmodus gestartet. Dies bedeutet, dass nach der Erstellung der Richtlinie Folgendes gilt:

- Es werden keine Warnungen generiert. Auf der Detailseite der Richtlinie werden jedoch Erkenntnisse angezeigt, wenn Übereinstimmungen erkannt werden, einschließlich der erkannten Datentypen und deren Speicherorte.

- Wenn Richtlinienübereinstimmungen erkannt werden, werden keine Benutzer-E-Mail-Benachrichtigungen gesendet. Auf der Detailseite der Richtlinie werden jedoch Einblicke angezeigt, die zeigen, welche Benutzer Richtlinienübereinstimmungen zugeordnet sind.

Im Testmodus können Sie nach Übereinstimmungen aus den letzten 30 Tagen der Benutzeraktivität suchen. Mit diesen Erkenntnissen können Sie das Verhalten der Richtlinie messen und die Arten von Warnungen überprüfen, die möglicherweise generiert werden, wenn die Richtlinie aktiviert ist.

Es wird empfohlen, Ihre Richtlinie mindestens fünf Tage lang zu testen, um den Typ und das Volumen der übereinstimmungen zu verstehen, die generiert werden. Sie können [die Richtlinie im](#edit-a-policy) Testmodus bearbeiten, damit Sie überwachen können, wie sich die Änderungen auf die Leistung auswirken, bevor Sie sie aktivieren. Sie können z. B. feststellen, dass die Richtlinie zu breit ist und ihre Bedingungen angepasst werden müssen. Oder Sie erkennen anhand von Aktivitäten, die erkannt werden, dass Warnungen nicht in einem zeitrahmen generiert werden, der für Sie nützlich ist.

Die Detailseite der Richtlinie gibt an, wie viele Tage der Test ausgeführt wurde. Sie werden sehen, wie viele Übereinstimmungen nach Speicherort gefunden wurden, wie viele Benutzerereignisse, die den Bedingungen der Richtlinie entsprechen, erkannt wurden und welche persönlichen Datentypen von Richtlinienübereinstimmungen erkannt wurden.

> [!NOTE]
> Wenn Sie den Schalter " **Im Testmodus ausführen** " auf die " **Aus** "-Position umschalten, *wird Ihre Richtlinie aktiviert* , wenn Sie die Erstellung abgeschlossen haben. Dies bedeutet, dass alle von Ihnen eingerichteten Benachrichtigungen oder Benutzerbenachrichtigungen generiert werden, wenn Übereinstimmungen erkannt werden.

Wenn Sie mit den Einstellungen Ihrer Richtlinie zufrieden sind und bereit sind, sie zu aktivieren, wählen Sie die blaue Schaltfläche " **Richtlinie aktivieren** " aus. Die Richtlinie ist jetzt aktiv und generiert alle von Ihnen eingerichteten Benachrichtigungen und Benutzerbenachrichtigungen.

## <a name="turn-on-a-policy"></a>Aktivieren einer Richtlinie

Sie können eine Richtlinie so festlegen, dass sie aktiviert wird, sobald Sie die Erstellung abgeschlossen haben. Dies wird nicht empfohlen, da es am besten ist, die Leistung und Einstellungen zu überwachen, indem Sie die Richtlinie in den Testmodus versetzen, bevor Sie sie aktivieren (siehe [Testen einer Richtlinie](#testing-a-policy)).

Wenn Sie Ihre Richtlinie im Testmodus erstellt haben, können Sie sie schnell aktivieren, indem Sie die folgenden Schritte ausführen:

1. Suchen Sie auf der Seite **"Richtlinien** " die Richtlinie, und wählen Sie ihren Namen aus, um die Detailseite zu öffnen.
2. Wählen Sie auf der **Richtlinienstatuskarte** " **Richtlinie aktivieren**" aus.

Die Richtlinie ist jetzt aktiv und generiert alle von Ihnen eingerichteten Benachrichtigungen und Benutzerbenachrichtigungen.

## <a name="turn-off-a-policy"></a>Deaktivieren einer Richtlinie

Sie können eine Richtlinie jederzeit deaktivieren, indem Sie in der oberen rechten Ecke der Detailseite einer Richtlinie die Option **"Richtlinie deaktivieren** " auswählen. Wenn eine Richtlinie deaktiviert ist, erkennt sie keine Übereinstimmungen und generiert keine Benachrichtigungen oder E-Mail-Benachrichtigungen. Durch das Deaktivieren einer Richtlinie wird keine Richtlinie gelöscht. Sie können eine Richtlinie wieder aktivieren, indem Sie in der oberen rechten Ecke der Seite mit den Richtliniendetails die Option **"Richtlinie aktivieren** " auswählen.

## <a name="view-details-and-activity-from-the-policy-details-page"></a>Anzeigen von Details und Aktivitäten auf der Seite "Richtliniendetails"

Jede Richtlinie verfügt über eine Detailseite mit Aktivitäten, die von der Richtlinie erkannt wurden, und Einblicke, die Ihnen bei der Bewältigung von Risiken helfen.

Nachdem Ihre Richtlinie erstellt wurde, wählen Sie ihren Namen in der Tabelle auf der Hauptseite **"Richtlinien"** aus. Die Registerkarte " **Übersicht** " auf der Seite "Richtliniendetails" informiert Sie über den Status Ihrer Richtlinie, bietet Einblicke in Ihre Daten und hebt Richtlinienübereinstimmungen hervor. Hier können Sie Details zu bestimmten Richtlinienübereinstimmungen anzeigen und mehr über die nächsten Schritte erfahren. Wenn Ihre Richtlinie im Testmodus ausgeführt wird, werden die empfohlenen nächsten Schritte auf dieser Seite und eine Schaltfläche zum Aktivieren der Richtlinie angezeigt.

Wenn die Richtlinie aktiviert ist, können Sie die Seite mit den Richtliniendetails weiterhin überprüfen, um fortlaufende Einblicke in Problembereiche, Warnungsschweregrad und Trends sowie ergriffene Korrekturmaßnahmen zu erhalten.

### <a name="overview-tab"></a>Registerkarte „Übersicht“

Auf der Registerkarte " **Übersicht** " auf der Seite "Richtliniendetails" finden Sie Details dazu, was die Richtlinie in Bezug auf Typen und Speicherorte von Daten und Benutzeraktivitäten erkennt. Die Einblicke auf der Detailseite der Richtlinie werden unten beschrieben. Nach dem Aktivieren einer Richtlinie kann es bis zu 48 Stunden dauern, bis Daten durchkommen.

#### <a name="policy-status"></a>Richtlinienstatus

Die Richtlinienstatuskarte gibt an, ob sich Ihre Richtlinie in einem von drei Zuständen befindet: **Testen**, **Aktivieren** oder **Deaktivieren**.

**Testen**: In diesem Abschnitt wird die Anzahl der Tage angezeigt, die Ihre Richtlinie im Testmodus ausgeführt hat. Dies bedeutet, dass sie nach Richtlinienübereinstimmungen basierend auf den von Ihnen festgelegten Bedingungen sucht, aber keine Warnungen oder Benutzerbenachrichtigungen generiert. Wir geben Eine Empfehlung, wenn es ein guter Zeitpunkt ist, Ihre Richtlinie zu aktivieren. Sie können sie jederzeit aktivieren, indem Sie auf dieser Karte die Schaltfläche " **Richtlinie aktivieren** " auswählen.

**Ein**: Wenn Ihre Richtlinie aktiviert ist, zeigt die Statuskarte Metriken an, die hervorheben, wenn nach einer Richtlinienübereinstimmung Benachrichtigungen und Benutzerbenachrichtigungen generiert wurden.

- **Ausgeführte Benutzeraktionen**: Diese Metrik zeigt die Anzahl der Wartungsaktionen an, die von Benutzern ausgeführt werden, wenn sie von einer Benachrichtigungs-E-Mail zur Gesamtzahl der gesendeten Benachrichtigungen aufgefordert werden. Beispielsweise würde 8/10 bedeuten, dass von 10 gesendeten Benutzerbenachrichtigungen Benutzer in 8 Instanzen eine Korrekturaktion ausgeführt haben.

- **Benutzerauflösungsrate**: Diese Metrik ist die Rate, mit der Wartungsaktionen von Benutzern basierend auf der Anzahl der generierten Benachrichtigungen ausgeführt werden. Wenn der Prozentsatz niedrig ist, können Sie [den E-Mail-Inhalt bearbeiten](risk-management-notifications.md#preview-and-customize-email-content) oder die Übereinstimmungen genau untersuchen, um festzustellen, ob die Richtlinie die beabsichtigte Aktivität erkennt.

- **Ausgeführte Administratoraktionen**: Diese Metrik zeigt die Anzahl der Wartungsaktionen an, die von Administratoren ausgeführt werden, wenn eine Warnung durch die Richtlinie generiert wird. Erfahren Sie mehr darüber [, wie Sie Aktionen für Warnungen ausführen](risk-management-alerts.md#manage-alerts).

- **Administratorauflösungsrate**: Diese Metrik ist die Rate, mit der Wartungsaktionen von Administratoren basierend auf der Anzahl der Warnungen ausgeführt werden.

#### <a name="matches-by-location"></a>Übereinstimmungen nach Speicherort

Auf der **Karte "Übereinstimmungen nach Standort**" wird die Anzahl der von der Richtlinie erkannten Inhaltselemente entsprechend Microsoft 365 Speicherorts angezeigt.

#### <a name="user-notifications"></a>Benutzerbenachrichtigungen

Auf der **Karte "Benutzerbenachrichtigungen** " wird ein Balkendiagramm mit der Anzahl der E-Mails mit Benutzerbenachrichtigungen angezeigt, die von der Richtlinie generiert wurden, wenn diese Funktionen aktiviert sind.

#### <a name="matches-by-user"></a>Übereinstimmungen nach Benutzer

Die Karte **"Übereinstimmungen nach Benutzer" listet** die wichtigsten Benutzer auf, deren Aktionen eine Richtlinienübereinstimmung ausgelöst haben. Sie sehen die Anzahl der von der Richtlinie für jeden Benutzer erkannten Ereignisse sowie die Anzahl der Wartungsaktionen, die aus E-Mail-Benachrichtigungen ausgeführt werden. Wählen Sie " **Alle Benutzer** auf dieser Karte anzeigen" aus, um die vollständige Liste der von der Richtlinie erkannten Benutzer zu überprüfen.

#### <a name="matches-by-data-type"></a>Übereinstimmungen nach Datentyp

Auf der Karte " **Übereinstimmungen nach Datentyp** " werden die Typen personenbezogener Daten angezeigt, die von Richtlinienübereinstimmungen erkannt wurden, und die Menge der einzelnen Typen. Das Kreisdiagramm hilft visuell zu veranschaulichen, ob eine bestimmte Art von personenbezogenen Daten, z. B. Sozialversicherungsnummern oder Kreditkartennummern, in den Risikoszenarien, die Sie identifizieren möchten, überwiegend dargestellt wird.

> [!TIP]
> Wenn Sie einen ganzheitlichen Blick auf die Standorte, Datentypen und die Anzahl der Benutzer werfen, die an Richtlinienübereinstimmungen beteiligt sind, erhalten Sie möglicherweise einen besseren Überblick über die Arten von Schulungen und Datenschutzmaßnahmen, die erforderlich sind, um Ihrer Organisation zu helfen, die gespeicherten personenbezogenen Daten zu schützen.

### <a name="matched-items-tab"></a>Registerkarte "Übereinstimmenden Elementen"

Auf der Registerkarte **"Übereinstimmende Elemente** " wird eine Liste aller Inhaltselemente angezeigt, die einer in der Richtlinie festgelegten Bedingung entsprechen. In dieser Ansicht können Sie ein Element aus seiner Zeile auswählen, um eine Vorschau im Fenster rechts neben der Elementliste anzuzeigen.

Im Vorschaufenster finden Sie die folgenden Registerkarten, die Details zu den einzelnen Elementen enthalten:
- **Quelle**: Zeigt die persönlichen Daten an, die die Übereinstimmung ausgelöst haben.
- **Details**: Zeigt den Inhaltsbesitzer (Benutzer in Ihrer Organisation) für das Element, den Microsoft 365 Speicherort des Elements, die Anzahl der persönlichen Datentypen innerhalb des Elements und die spezifischen persönlichen Datentypen an.
- **Dateiaktivitäten**: Zeigt alle Bezeichnungen oder Klassifizierungen an, die auf das Element angewendet wurden.
- **Wartungsverlauf**: Zeigt Informationen zu Wartungsaktionen an, die von Benutzern oder Administratoren für das Element ausgeführt wurden.

## <a name="edit-a-policy"></a>Bearbeiten einer Richtlinie 

Sie können die Einstellungen für eine Richtlinie jederzeit bearbeiten, unabhängig davon, ob sie sich im Testmodus befinden oder aktiviert sind. Sie können die meisten Richtlinieneinstellungen aktualisieren, z. B. eine Richtlinie wieder in den Testmodus versetzen, nachdem Sie sie aktiviert haben. Die einzigen Einstellungen, die Sie nicht bearbeiten können, sind die Richtlinienvorlage und der Richtlinienname.

Führen Sie die folgenden Schritte aus, um eine Richtlinie zu bearbeiten:

1. Suchen Sie im [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) priva Privacy Risk Management im linken Navigationsbereich. Wählen Sie im Dropdownmenü " **Richtlinien**" aus.

2. Wählen Sie die Richtlinie, die Sie bearbeiten möchten, aus ihrer Zeile auf der Seite **"Richtlinien** " aus, auf der die Detailseite dieser Richtlinie angezeigt wird.

3. Wählen Sie auf der Seite "Richtliniendetails" den Befehl **"Bearbeiten"** in der oberen rechten Ecke der Seite aus. Diese Aktion führt Sie in die Richtlinienerstellung im Datenschutzrisikomanagement ein.

4. Fahren Sie mit den Schritten fort, um zu den Einstellungen zu gelangen, die Sie ändern möchten. Sie können alle Einstellungen mit Ausnahme von Richtlinienvorlage und Richtlinienname bearbeiten. Wählen Sie **"Weiter** " aus, um zu jedem nächsten Schritt zu wechseln.

5. Überprüfen Sie auf der Seite **"Fertig stellen** " Ihre Einstellungen, und wählen Sie dann **"Absenden** " aus, um die von Ihnen vorgenommenen Änderungen zu speichern.

## <a name="delete-a-policy"></a>Löschen einer Richtlinie

Wenn Sie eine vorhandene Richtlinie für das Datenschutzrisikomanagement entfernen müssen, suchen Sie sie in der Liste auf der Seite **"Richtlinien** ", wählen Sie das Aktionsmenü (vertikale Auslassungszeichen) und dann die **Aktion "Richtlinie löschen" aus** . Sie können auch die Detailseite der Richtlinie öffnen und in der oberen rechten Ecke " **Löschen"** auswählen.

Sie werden aufgefordert, Ihre Auswahl zu bestätigen, bevor der Löschvorgang abgeschlossen ist und die Richtlinie endgültig entfernt wird. Das Löschen einer Richtlinie wirkt sich nicht auf Dateien aus, die zuvor von der Richtlinie ausgewertet wurden. Von der Richtlinie generierte Probleme und Warnungen werden weiterhin auf den Seiten " **Warnungen** und **Probleme** " aufgeführt.

## <a name="next-steps"></a>Nächste Schritte

Sobald Ihre Richtlinie aktiviert ist und mit dem Generieren von Warnungen beginnt, sollten Sie verstehen, welche Risiken sie für Ihre Organisation darstellen können. Erfahren Sie, wie Sie Warnungen verwalten, Ereignisse untersuchen und Abhilfemaßnahmen im Datenschutzrisikomanagement ergreifen, indem Sie [Warnungen untersuchen und beheben](risk-management-alerts.md).

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
