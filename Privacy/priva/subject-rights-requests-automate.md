---
title: 'Automatisieren von Aufgaben in Anträgen betroffener Personen '
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
description: Erfahren Sie, wie Sie Microsoft Power Automate verwenden, um wichtige Aufgaben für Anfragen zu Rechten betroffener Personen in Priva zu automatisieren.
ms.openlocfilehash: ec9edde16b60c2326ca899e587dfe5dc7a1e32f5
ms.sourcegitcommit: 09ecdaded9a9f8f79587f2acb978dc53b83e5c01
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/19/2022
ms.locfileid: "64930496"
---
# <a name="automate-tasks-in-subject-rights-requests"></a>Automatisieren von Aufgaben in Anträgen betroffener Personen 

Microsoft Power Automate ist ein Workflowdienst, der Aktionen anwendungs- und dienstübergreifend automatisiert. Wenn Sie Power Automate Flüsse für Microsoft Priva-Anträge auf Rechte betroffener Personen aktivieren, können Sie wichtige Aufgaben für Fälle und Benutzer automatisieren, z. B. das Erstellen von Tickets in ServiceNow oder das Hinzufügen von Kalendererinnerungen zu Fälligkeitsdaten. Weitere Informationen zu Power Automate finden Sie auf ihrer [Dokumentationswebsite](/power-automate/getting-started).

Kunden mit Abonnements für Anträge betroffener Rechte benötigen keine weitere Power Automate Lizenz, um die empfohlenen Power Automate Vorlagen für Priva zu verwenden. Diese Vorlagen können angepasst werden, um Ihre Organisation zu unterstützen und die wichtigsten Szenarien zur Anforderung von Rechten betroffener Personen abzudecken. Wenn Sie premium Power Automate-Features in diesen Vorlagen verwenden, eine benutzerdefinierte Vorlage mit dem Microsoft 365 Compliance Connector erstellen oder Power Automate Vorlagen für andere Compliancebereiche in Microsoft 365 verwenden, benötigen Sie möglicherweise mehr Power Automate Lizenzen.

## <a name="create-a-new-power-automate-flow-from-a-template"></a>Erstellen eines neuen Power Automate Flusses aus einer Vorlage

1. Wechseln Sie im [Microsoft Purview Compliance-Portal](https://compliance.microsoft.com/) zum Abschnitt "Priva" der Navigation, und wählen Sie **"Priva Subject Rights Requests**" aus.
1. Öffnen Sie die Anforderung für Die Rechte der Betroffenen, mit der Sie arbeiten möchten, aus der Liste, und wählen Sie **"Automatisieren**" aus, und **verwalten Sie dann Power Automate Flüsse**. Dadurch wird der Flyoutbereich "Flüsse" geöffnet.
1. Verwenden Sie die Option **"Neu** ", und wählen Sie die gewünschte Vorlage aus den verfügbaren Optionen aus. Folgen Sie hier den Anweisungen im Assistenten, um die Einrichtung abzuschließen. Die Optionen variieren je nach Vorlagentyp.

Nachdem Sie eine Instanz der Vorlage gespeichert haben, müssen Sie sie auf der Detailseite der Anforderung für Die Rechte betroffener Personen ausführen, damit die Ablaufinstanz den richtigen Kontext und die richtige ID hat. Öffnen Sie die Anforderung, kehren Sie zum Menü **"Automatisieren** " zurück, wählen Sie die Vorlage aus, und wählen Sie **"Ablauf ausführen" aus**. Sie können Ihre früheren Aktivitäten anzeigen, indem Sie " **Ablaufausführungsaktivität anzeigen**" auswählen.

### <a name="power-automate-templates-in-priva"></a>Power Automate Vorlagen in Priva

- **Erstellen eines Datensatzes für Datenschutzverwaltungsfälle in ServiceNow**: Diese Vorlage richtet sich an Organisationen, die ihre ServiceNow-Lösung verwenden möchten, um Anfragen von Betroffenenrechten nachzuverfolgen. Sie werden aufgefordert, Ihre ServiceNow-Instanzdetails einzugeben, einschließlich eines Kontos, um eine Verbindung mit ServiceNow herzustellen. Dieses Konto muss in der Lage sein, einen Vorfall in ServiceNow zu erstellen und Vorfalldetails auszufüllen. Nachdem die Verbindung mit Ihrer Instanz hergestellt wurde, können Administratoren von Antragstellerrechten einen Datensatz für den Fall in ServiceNow erstellen und bei Bedarf anpassen, was die Vorlage in ausgewählte Felder auffüllt. Weitere Informationen zum Connector finden Sie auf der [ServiceNow Connector-Referenzseite](/connectors/service-now/).
- **Erstellen einer Kalendererinnerung**: Diese Vorlage dient zum Festlegen von Erinnerungen am Fälligkeitsdatum in Ihrem Outlook Kalender für Anfragen zu Rechten betroffener Personen. Das Tool füllt bestimmte Details für Sie aus den Eigenschaften der Anforderung auf, z. B. den Namen der Anforderung und das Fälligkeitsdatum. Sie können beschreibende Details hinzufügen, Empfänger angeben und andere erweiterte Einstellungen anpassen.
- **Abrufen von Dateien nach Tag für eine Anforderung von Rechten betroffener Personen**: Mit dieser Vorlage können Sie nach Dateien für Ihre Anfrage zu Rechten betroffener Personen suchen, die ein bestimmtes Tag erhalten haben. Sie können den Fluss bearbeiten, um benutzerdefinierte Aktionen auszuführen, oder die Liste der zurückgegebenen Dateien anzeigen, die für interne Prozesse oder Tools verwendet werden sollen.

## <a name="share-a-power-automate-flow"></a>Freigeben eines Power Automate-Flusses

Wenn Sie einen Power Automate Fluss freigeben, können Sie einen weiteren Besitzer hinzufügen und zulassen, dass er den Fluss bearbeiten, aktualisieren und löschen kann. Alle Besitzer können auch auf den Ausführungsverlauf zugreifen und andere Besitzer hinzufügen oder entfernen. Um einen Fluss freizugeben, öffnen Sie die Anforderung für Die Betroffenenrechte, mit der Sie arbeiten möchten, wählen Sie **"Automatisieren**" und dann **"Power Automate Flüsse verwalten**" aus. In diesem Bereich können Sie einen vorhandenen Fluss auswählen und dann die Option "Freigeben" verwenden, um einen Benutzer oder eine Gruppe hinzuzufügen.

In diesem Bereich können Sie auch die eingebetteten Verbindungen zu Diensten verwalten, die im Power Automate-Fluss verwendet werden. Das Ändern dieser Einstellungen kann sich auf Ihre Fähigkeit auswirken, den Fluss auszuführen.

## <a name="edit-or-delete-power-automate-flow"></a>Bearbeiten oder Löschen Power Automate Flusses

Wenn Sie Details eines Power Automate Flusses anpassen möchten, öffnen Sie die Anforderung der Betroffenenrechte, wählen **Sie "Automatisieren**" aus, und wählen Sie **"Power Automate Flüsse verwalten**" aus. In diesem Bereich können Sie einen vorhandenen Fluss auswählen, um Details anzuzeigen. Verwenden Sie "Bearbeiten" in einem beliebigen Abschnitt, um die Eigenschaften zu ändern und dann zu speichern.

Um den Fluss vollständig zu entfernen, verwenden Sie die Option **"Löschen** ". Es entfernt den Fluss für alle Besitzer und deinstalliert ihn für alle Benutzer. Frühere Ablaufinstanzen werden weiterhin ausgeführt, um Datenverluste zu vermeiden. Sie können Ihre Auswahl bestätigen, bevor die Löschung abgeschlossen ist.

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
