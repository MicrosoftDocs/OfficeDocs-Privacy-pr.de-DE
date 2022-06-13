---
title: Datenschätzung und -abruf in Anträgen betroffener Personen
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
description: Verstehen, wie Daten abgerufen werden und wie Sucheinstellungen in Microsoft Priva Anfragen zu Betroffenenrechten geändert werden.
ms.openlocfilehash: 9d35a7f37861d7d3ecc5d1bac7db92c75939b4c3
ms.sourcegitcommit: 3c83e8133a5a71f4e1d76a0b2981ab3ec9cd6602
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/13/2022
ms.locfileid: "66046732"
---
# <a name="data-estimate-and-retrieval"></a>Datenschätzung und -abruf

**In diesem Artikel**: Verstehen der Datenschätzungs- und Datenabrufstufen einer Anfrage zu Rechten betroffener Personen. Erfahren Sie, wie Sie die Suchabfrage einer Anforderung anzeigen und Änderungen vornehmen, um die Suche zu verfeinern.

## <a name="data-estimate"></a>Datenschätzung
Nachdem Sie eine Anforderung erstellt haben, beginnt Priva sofort mit der Suche nach Übereinstimmungen mit der betroffenen Person in Inhalten in Ihrer Microsoft 365 Umgebung. Nachdem wir alle Elemente identifiziert haben, die ihrer Meinung nach Ihren Kriterien entsprechen, wird die Schätzung auf der **Zusammenfassungskarte "Datenschätzung** " auf der **Seite "Übersicht** " der Anforderung angezeigt. Die Datenmenge innerhalb des Suchbereichs wirkt sich auf die Dauer aus, die zum Abschließen der Schätzung benötigt wird.

Ihre Anforderung wird automatisch in die nächste Phase des **Datenabrufs** verschoben, in der alle Inhaltselemente gesammelt werden, damit die Projektbeteiligten an der Überprüfung der Daten zusammenarbeiten können. In einigen Fällen unterbrechen wir die Datenschätzung, bevor wir zum Abruf übergehen, und benachrichtigen Sie über die nächsten Schritte, die Sie ausführen müssen, bevor Sie fortfahren.

### <a name="pause-in-data-estimate"></a>Anhalten der Datenschätzung

Es gibt zwei Gründe, warum eine Anforderung in der **Datenschätzungsphase** angehalten wird:

1. Wenn Sie eine Anforderung zum ersten Mal erstellen, können Sie auswählen, ob Sie zuerst eine Schätzung erhalten möchten. Weitere Informationen finden Sie in Schritt 5 in ["Erstellen einer Anforderung](subject-rights-requests-create.md#create-a-request) ".

2. Wenn die Schätzung so projiziert wird, dass eine große Anzahl von zu überprüfenden Elementen (über 10 KB Elemente) zurückgegeben wird, wird der Workflow angehalten. An diesem Punkt können Sie eine Vorschau der Ergebnisse anzeigen und entscheiden, ob [Sie Ihre Suchabfrage bearbeiten](subject-rights-requests-create.md#refining-your-search) oder die identifizierten Elemente weiterhin abrufen möchten.

Wenn die Anforderung bei " **Datenschätzung**" angehalten wird, wird auf der Detailseite Ihrer Anforderung eine Karte mit Zusammenfassungsinformationen zur Anzahl der Elemente, zum Volumen, zum Standort und zu einem Link angezeigt, über den Sie **Suchabfragedetails anzeigen** können.

![Datenschätzungskarte.](../media/priva-srr-data-estimate.png)

## <a name="view-and-edit-search-queries"></a>Anzeigen und Bearbeiten von Suchabfragen

Um detaillierte Informationen zur Suche der Anforderung anzuzeigen, wählen Sie auf der **Zusammenfassungskarte "Datenvoranschlag**" die Option "**Suchabfragedetails anzeigen**" aus. Ein Flyoutbereich wird geöffnet, in dem die Abfrage zusammengefasst und weitere Details zu den gefundenen Informationen angezeigt werden. Von hier aus haben Sie die folgenden Optionen:

- Wählen Sie **"Vorschauergebnisse** " aus, um eine Vorschau des Inhaltstyps zu erhalten, der unter den aktuellen Sucheinstellungen zurückgegeben wird.
- Wählen Sie **"Suchabfrage bearbeiten** " aus, um die Sucheinstellungen zu ändern.

Wenn Sie die **Suchabfrage bearbeiten** auswählen, werden Sie durch einen geführten Prozess geführt, um Eigenschaften zu ändern oder hinzuzufügen, um die betroffene Person zu identifizieren, Bedingungen zu ändern und die Speicherorte anzupassen, die die Suche abdecken soll. Befolgen Sie die Anweisungen unter [Verfeinern Ihrer Suche](subject-rights-requests-create.md#refining-your-search) , um detailliertere Informationen zu erhalten. Sie können die endgültige Version Ihrer neuen Suchabfrage überprüfen und dann **"Speichern"** auswählen, um die Suche erneut zu starten.

Es wird eine neue Schätzung generiert, und der Status der Anforderung wird zurück zur **Datenschätzung** gehen. Der Abschluss der neuen Suche kann bis zu 60 Minuten dauern. Sobald dies abgeschlossen ist, werden aktualisierte Ergebnisse auf der Detailseite der Anforderung angezeigt.

Wenn Sie bereit sind, fortzufahren, wählen Sie oben rechts auf dem Bildschirm die Option **"Daten abrufen** " aus, um zur Datenempfangsphase zu gelangen.

## <a name="retrieve-data"></a>Abrufen von Daten

Die Datenempfangsphase ist, wenn alle Dateien, E-Mails, Chats, Bilder und anderen Inhaltselemente, die die personenbezogenen Daten der betroffenen Person enthalten, abgerufen werden. Die Elemente werden zur Überprüfung in einem Azure-BLOB-Speichercontainer zusammengestellt. Der Datenabruf kann je nach Datenvolumen einige Minuten oder erheblich länger dauern.

Wenn diese Phase abgeschlossen ist, wird die Anforderung automatisch zur nächsten Phase der **Überprüfungsdaten** verschoben.

## <a name="next-steps"></a>Nächste Schritte

Besuchen Sie ["Prüfdaten" für eine Anfrage zu Rechten betroffener Personen](subject-rights-requests-data-review.md) , um mehr über die wichtigsten Aufgaben zu erfahren und mit den Beteiligten zusammenzuarbeiten, um den **Schritt "Daten überprüfen"** zu erhalten.

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)