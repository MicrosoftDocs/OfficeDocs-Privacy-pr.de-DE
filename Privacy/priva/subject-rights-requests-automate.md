---
title: Integration in Microsoft Graph-API und Power Automate
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
search.appverid:
- MOE150
- MET150
description: Erfahren Sie, wie Sie Priva Anfragen zu Betroffenenrechten Funktionen durch Integration in Microsoft Graph-API und Power Automate erweitern.
ms.openlocfilehash: e4fcad2067ece3d1a6338e6d4891c59d91205a33
ms.sourcegitcommit: 9315064bf5bb9e889318e61ec5f082f36c815e1e
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/02/2022
ms.locfileid: "65851640"
---
# <a name="integrate-and-extend-through-microsoft-graph-api-and-power-automate"></a>Integration und Erweiterung über Microsoft Graph-API und Power Automate

Sie können Priva Anfragen zu Betroffenenrechten mit ihren vorhandenen Geschäftsprozessen und Tools integrieren, indem Sie die Microsoft Graph-API zur Anforderung von Rechten betroffener Personen verwenden.You can integrate Priva Anfragen zu Betroffenenrechten with your existing business processes and tools by using the Microsoft Graph Subject Rights Request API. Sie können auch die Automatisierungsfunktionen von Anträgen betroffener Personen erweitern, indem Sie integrierte Power Automate-Flüsse für Aufgaben wie das Festlegen von Kalendererinnerungen und das Erstellen von Fällen in ServiceNow verwenden.

## <a name="microsoft-graph-subject-rights-requests-api"></a>Microsoft Graph-API für Anfragen zu Rechten betroffener Personen

Die Microsoft 365 Subject Rights Request-API bietet eine einfache, aber leistungsstarke Möglichkeit zur Einführung einer Automatisierung Ihrer bestehenden Strategie für Rechte betroffener Personen. Wenn ein Einzelner Informationen von Ihrer Organisation anfordert, ermöglichen ihnen unsere APIs, diese Anforderungen innerhalb Microsoft 365 basierend auf den Kriterien für diese Anforderung zu erstellen. Sie können die Anforderung der Betroffenenrechte in Microsoft 365 erstellen, den Fortschritt nachverfolgen und bestätigen, wenn die Verarbeitung der Anforderung abgeschlossen ist und der Inhalt abgerufen werden kann.

Unsere APIs stehen jedem zur Verfügung, um seine Lösungen erweiterbarer zu machen, z. B. ISVs, Partner, die Microsoft 365 in ihren Lösungen berücksichtigen möchten, und Organisationen, die die APIs mit ihren Branchenanwendungen verwenden möchten.

Sehen Sie sich die vollständige Dokumentation unter [Verwendung der Microsoft Graph Api zur Anforderung von Rechten betroffener Personen](/graph/api/resources/subjectrightsrequest-subjectrightsrequestapioverview) an.

## <a name="power-automate-templates-for-subject-rights-requests"></a>Power Automate Vorlagen für Anträge betroffener Personen

Microsoft Power Automate ist ein Workflowdienst, der Aktionen anwendungs- und dienstübergreifend automatisiert. Anfragen zu Rechten betroffener Personen enthalten integrierte Power Automate Vorlagen, die Benutzern bei der Verwaltung von Anfragen zu Rechten betroffener Personen helfen. Benutzer können Automatisierungsabläufe für Prozesse wie das Erstellen von Tickets in ServiceNow und das Hinzufügen von Kalendererinnerungen zu Fälligkeitsdaten einrichten. Weitere Informationen zu Power Automate finden Sie in der [Power Automate Dokumentation](/power-automate/getting-started).

Wenn Sie ein Abonnement für Anträge betroffener Personen erworben haben, benötigen Sie keine separate Power Automate Lizenz, um die empfohlenen Power Automate-Vorlagen verwenden zu können. Diese Vorlagen können angepasst werden, um Ihre Organisation zu unterstützen und die wichtigsten Szenarien zur Anforderung von Rechten betroffener Personen abzudecken. Möglicherweise benötigen Sie jedoch zusätzliche Lizenzen, um Premium-Power Automate-Features in diesen Vorlagen zu verwenden oder eine eigene Vorlage zu erstellen.

### <a name="available-templates"></a>Verfügbare Vorlagen

- **Erstellen eines Datensatzes für Priva Datenschutzverwaltungsfall in ServiceNow**: Diese Vorlage richtet sich an Organisationen, die ihre ServiceNow-Lösung verwenden möchten, um Anfragen von Betroffenenrechten nachzuverfolgen. Sie werden aufgefordert, Ihre ServiceNow-Instanzdetails einzugeben, einschließlich eines Kontos zum Herstellen einer Verbindung mit ServiceNow. Dieses Konto muss in der Lage sein, einen Vorfall in ServiceNow zu erstellen und Vorfalldetails auszufüllen. Nachdem die Verbindung mit Ihrer Instanz hergestellt wurde, können Administratoren von Antragstellerrechten einen Datensatz für den Fall in ServiceNow erstellen und bei Bedarf anpassen, was die Vorlage in ausgewählte Felder auffüllt. Weitere Informationen zum Connector finden Sie in der [ServiceNow-Connectordokumentation](/connectors/service-now/).

- **Fügen Sie eine Kalendererinnerung hinzu, um einen Priva Datenschutzverwaltungsfall zu verfolgen**: Diese Vorlage dient zum Festlegen von Erinnerungen am Fälligkeitsdatum in Ihrem Outlook Kalenders für Anfragen zu Rechten betroffener Personen. Das Tool füllt bestimmte Details für Sie aus den Eigenschaften der Anforderung auf, z. B. den Namen der Anforderung und das Fälligkeitsdatum. Sie können beschreibende Details hinzufügen, Empfänger angeben und andere erweiterte Einstellungen anpassen.

- **Abrufen von Dateien nach Tag für eine Priva Anforderung von Rechten betroffener Personen**: Mit dieser Vorlage können Sie nach Dateien für Ihre Anfrage zu Rechten betroffener Personen suchen, die ein bestimmtes Tag erhalten haben. Sie können den Fluss bearbeiten, um benutzerdefinierte Aktionen auszuführen, oder die Liste der zurückgegebenen Dateien anzeigen, die für interne Prozesse oder Tools verwendet werden sollen.

### <a name="create-a-new-power-automate-flow-from-a-template"></a>Erstellen eines neuen Power Automate Flusses aus einer Vorlage

1. Wählen Sie im [Microsoft Purview-Complianceportal](https://compliance.microsoft.com/) im linken Navigationsbereich **Priva Anfragen zu Betroffenenrechten** aus.

2. Suchen Sie die Anfrage zu Rechten betroffener Personen, an der Sie arbeiten möchten, und wählen Sie sie aus der Liste aus, um die Detailseite zu öffnen.

3. Wählen Sie in der oberen rechten Ecke **"Automatisieren**" und dann **"Power Automate Flüsse verwalten**" aus, um den Flyoutbereich "Flüsse" zu öffnen.

4. Wählen Sie **"Neu** " aus, und wählen Sie unter den verfügbaren Optionen die Vorlage aus, die Sie verwenden möchten. Folgen Sie hier den Anweisungen zum Anpassen und Hinzufügen von Schritten, um die Erstellung des Flusses abzuschließen. Die Optionen variieren je nach verwendeter Vorlage (siehe Vorlagentypen unten).

5. Wenn Sie fertig sind, wählen Sie **Speichern** aus.

Nachdem Sie eine Instanz der Vorlage gespeichert haben, müssen Sie sie auf der Detailseite der Anforderung ausführen, damit die Ablaufinstanz den richtigen Kontext und die richtige ID hat. Öffnen Sie die Anforderung, kehren Sie zum Menü **"Automatisieren** " zurück, wählen Sie die Vorlage aus, und wählen Sie **"Ablauf ausführen" aus**. Sie können Ihre früheren Aktivitäten anzeigen, indem Sie " **Ablaufausführungsaktivität anzeigen**" auswählen.

### <a name="share-a-power-automate-flow"></a>Freigeben eines Power Automate-Flusses

Wenn Sie einen Power Automate Fluss freigeben, können Sie einen weiteren Besitzer hinzufügen und den Fluss bearbeiten, aktualisieren und löschen. Alle Besitzer können auf den Ausführungsverlauf zugreifen und andere Besitzer hinzufügen oder entfernen. 

Um einen Fluss freizugeben, öffnen Sie die Anforderung für Die Betroffenenrechte, mit der Sie arbeiten möchten, wählen Sie **"Automatisieren**" und dann **"Power Automate Flüsse verwalten**" aus. In diesem Bereich können Sie einen vorhandenen Fluss auswählen und dann die Option **"Freigeben** " verwenden, um einen Benutzer oder eine Gruppe hinzuzufügen.

In diesem Bereich können Sie auch die eingebetteten Verbindungen zu Diensten verwalten, die im Power Automate-Fluss verwendet werden. Das Ändern dieser Einstellungen kann sich auf Ihre Fähigkeit auswirken, den Fluss auszuführen.

### <a name="edit-or-delete-power-automate-flow"></a>Bearbeiten oder Löschen Power Automate Flusses

Um Details eines Power Automate Flusses anzupassen, wählen Sie in der oberen rechten Ecke der Detailseite einer Anforderung die Option **"Automatisieren**" und dann **"Power Automate Flüsse verwalten**" aus.

Wählen Sie im **Bereich Power Automate Flüssen** den Fluss aus, den Sie bearbeiten möchten, und wählen Sie **in** der Befehlsleiste "Bearbeiten" aus, um Schritte zu bearbeiten oder hinzuzufügen. Wenn Sie fertig sind, wählen Sie **"Speichern" aus**.

Um einen Fluss zu löschen, wählen Sie ihn aus der Liste im **Bereich Power Automate Flüsse** aus, und wählen Sie in der Befehlsleiste "**Löschen**" aus. Der Fluss wird für alle Besitzer entfernt und für alle Benutzer deinstalliert. Frühere Ablaufinstanzen werden weiterhin ausgeführt, um Datenverluste zu vermeiden. Sie werden aufgefordert, dies zu bestätigen, bevor der Löschvorgang abgeschlossen ist.

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
