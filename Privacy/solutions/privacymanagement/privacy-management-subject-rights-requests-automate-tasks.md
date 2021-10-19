---
title: Automatisieren von Aufgaben zur Anforderung von Antragstellerrechten in der Datenschutzverwaltung
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
description: Erfahren Sie, wie Sie Microsoft Power Automate verwenden, um wichtige Aufgaben für Anträge betroffener Personen in der Datenverwaltung zu automatisieren.
ms.openlocfilehash: df76e87e3298b2ccc6c897d485e695d0f1ae35c9
ms.sourcegitcommit: 85e085eb17af8b4efd1f45207445e1b3c3679600
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/19/2021
ms.locfileid: "60478191"
---
# <a name="automate-subject-rights-requests-tasks"></a>Automatisieren von Aufgaben zur Anforderung von Antragstellerrechten

Microsoft Power Automate ist ein Workflowdienst, der Aktionen über Anwendungen und Dienste hinweg automatisiert. Wenn Sie Power Automate Flüsse für die Datenschutzverwaltung für Microsoft 365 aktivieren, können Sie wichtige Aufgaben für Fälle und Benutzer automatisieren, z. B. das Erstellen von Tickets in ServiceNow oder das Hinzufügen von Kalendererinnerungen zu Fälligkeitsdaten. Weitere Informationen zu Power Automate finden Sie auf der [Dokumentationswebsite.](/power-automate/getting-started)

Kunden mit Microsoft 365 Abonnements, die Datenschutzverwaltung enthalten, benötigen keine weiteren Power Automate Lizenzen, um die empfohlenen Datenverwaltungsvorlagen Power Automate verwenden zu können. Diese Vorlagen können angepasst werden, um Ihre Organisation zu unterstützen und die wichtigsten Datenschutzverwaltungsszenarien abzudecken. Wenn Sie premium Power Automate Features in diesen Vorlagen verwenden, eine benutzerdefinierte Vorlage mit dem Microsoft 365 Compliance Connector erstellen oder Power Automate Vorlagen für andere Compliancebereiche in Microsoft 365 verwenden, benötigen Sie möglicherweise mehr Power Automate Lizenzen.

## <a name="create-a-new-power-automate-flow-from-a-template"></a>Erstellen eines neuen Power Automate Flusses aus einer Vorlage

1. Wechseln [Sie](https://compliance.microsoft.com/)im Microsoft 365 Compliance Center zum Abschnitt "Datenschutzverwaltung" der Navigation, und wählen Sie **"Antragstellerrechteanforderungen" aus.**
1. Öffnen Sie die Anforderung für Betreffrechte, mit der Sie in der Liste arbeiten möchten, und wählen Sie **"Automatisieren"** aus, und verwalten Sie dann **Power Automate Flüsse.** Dadurch wird der Flyoutbereich Flows geöffnet.
1. Verwenden Sie die Option **"Neu",** und wählen Sie die Vorlage aus den verfügbaren Optionen aus, die Sie verwenden möchten. Folgen Sie hier den Anweisungen im Assistenten, um das Setup abzuschließen. Die Optionen variieren je nach Vorlagentyp.

Nachdem Sie eine Instanz der Vorlage gespeichert haben, müssen Sie sie auf der Detailseite der Anforderung für Betreffrechte ausführen, damit die Flussinstanz den richtigen Kontext und die richtige ID hat. Öffnen Sie die Anforderung, kehren Sie zum Menü **"Automatisieren"** zurück, wählen Sie die Vorlage aus, und wählen Sie **"Flow ausführen"** aus. Sie können Ihre früheren Aktivitäten anzeigen, indem Sie **"Aktivität zum Ausführen** des Flusses anzeigen" auswählen.

### <a name="power-automate-templates-in-privacy-management"></a>Power Automate Vorlagen in der Datenschutzverwaltung

- **Erstellen eines Datensatzes für den Fall der Datenschutzverwaltung in ServiceNow:** Diese Vorlage richtet sich an Organisationen, die ihre ServiceNow-Lösung verwenden möchten, um Anfragen von Antragstellerrechten nachzuverfolgen. Sie werden aufgefordert, Ihre Details zur ServiceNow-Instanz einzugeben, einschließlich eines Kontos, um eine Verbindung mit ServiceNow herzustellen. Dieses Konto muss in der Lage sein, einen Vorfall in ServiceNow zu erstellen und Vorfalldetails auszufüllen. Sobald eine Verbindung mit Ihrer Instanz hergestellt wurde, können Administratoren von Antragstellerrechten einen Datensatz für den Fall in ServiceNow erstellen und bei Bedarf anpassen, was die Vorlage in ausgewählte Felder auffüllt. Weitere Informationen zum Connector finden Sie auf der Referenzseite des [ServiceNow-Connectors.](/connectors/service-now/)
- **Erstellen Sie eine Kalendererinnerung:** Diese Vorlage dient zum Festlegen von Fälligkeitsdatumserinnerungen in Ihrem Outlook Kalenders für Anträge betroffener Personen. Das Tool füllt bestimmte Details für Sie aus den Eigenschaften der Anforderung auf, z. B. den Namen der Anforderung und das Fälligkeitsdatum. Sie können beschreibende Details hinzufügen, Empfänger angeben und andere erweiterte Einstellungen anpassen.
- **Abrufen von Dateien nach Tag für eine Anforderung von Betreffrechten:** Mit dieser Vorlage können Sie nach Dateien für Ihre Anforderung von Betreffrechten suchen, die mit einem bestimmten Tag versehen wurden. Sie können den Fluss bearbeiten, um benutzerdefinierte Aktionen auszuführen, oder die Liste der zurückgegebenen Dateien anzeigen, die für interne Prozesse oder Tools genutzt werden sollen.

## <a name="share-a-power-automate-flow"></a>Freigeben eines Power Automate Flusses

Durch die Freigabe eines Power Automate Flusses können Sie einen anderen Besitzer hinzufügen und es diesen ermöglichen, den Fluss zu bearbeiten, zu aktualisieren und zu löschen. Alle Besitzer können auch auf den Ausführungsverlauf zugreifen und andere Besitzer hinzufügen oder entfernen. Um einen Fluss freizugeben, öffnen Sie die Anforderung zu Den Betreffrechten, mit der Sie arbeiten möchten, wählen Sie **"Automatisieren"** aus, und wählen Sie dann **Power Automate Flüsse** verwalten aus. In diesem Bereich können Sie einen vorhandenen Fluss auswählen und dann die Option "Freigeben" verwenden, um einen Benutzer oder eine Gruppe hinzuzufügen.

In diesem Bereich haben Sie auch die Möglichkeit, die eingebetteten Verbindungen mit Diensten zu verwalten, die im Power Automate-Fluss verwendet werden. Wenn Sie diese Einstellungen ändern, kann sich dies auf Die Ausführung des Flusses auswirken.

## <a name="edit-or-delete-power-automate-flow"></a>Bearbeiten oder Löschen Power Automate Flusses

Um Details eines Power Automate Flusses anzupassen, öffnen Sie die Anforderung für Betreffrechte, wählen Sie **"Automatisieren"** aus, und wählen **Sie "Verwalten Power Automate Flüsse" aus.** In diesem Bereich können Sie einen vorhandenen Fluss auswählen, um Details anzuzeigen. Verwenden Sie "Bearbeiten" in einem beliebigen Abschnitt, um die Eigenschaften zu ändern und dann zu speichern.

Um den Fluss vollständig zu entfernen, verwenden Sie die Option **"Löschen".** Er entfernt den Fluss für alle Besitzer und deinstalliert ihn für alle Benutzer. Frühere Flussinstanzen werden weiterhin ausgeführt, um Datenverluste zu vermeiden. Sie können Ihre Auswahl bestätigen, bevor der Löschvorgang abgeschlossen ist.

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Datenschutzverwaltung](privacy-management-disclaimer.md)
