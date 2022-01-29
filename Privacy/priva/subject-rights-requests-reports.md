---
title: Generieren von Berichten und Erfüllen einer Anforderung zu Betreffrechten
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
description: Erfahren Sie, wie Sie die von Microsoft Priva erstellten Datenpakete für Anträge auf Rechte betroffener Personen verwalten und den Antrag an die betroffene Person erfüllen.
ms.openlocfilehash: 861a08b1f2ca5b3f82546c54db16c4518a8e9a70
ms.sourcegitcommit: f145dff5e387a8e26db2f3a2c7de125978fbacc9
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/28/2022
ms.locfileid: "62249046"
---
# <a name="generate-reports-and-fulfill-a-subject-rights-request"></a>Generieren von Berichten und Erfüllen einer Anforderung zu Betreffrechten

Nachdem Sie Ihre Datenüberprüfung für eine Anforderung zu Betreffrechten in Microsoft Priva abgeschlossen haben, können Sie die Erfüllung anfordern. Priva erstellt Berichte und erfasst die Dateien, die während des Datenüberprüfungsprozesses für **"Einschließen** " markiert sind. Ausgewählte Dateien aus diesen Datenpaketen können an Ihre betroffene Person übermittelt werden, um ihren Antrag zu erfüllen. Priva unterstützt auch die Microsoft 365-API für Anträge betroffener Personen, um Automatisierungsfunktionen einzuführen.

## <a name="prepare-final-reports-for-the-data-subject"></a>Vorbereiten von Abschlussberichten für die betroffene Person

Das Anforderungsdatenpaket für Betreffrechte wird als ZIP-Datei generiert. Es kann bis zu 30 Minuten dauern, bis dieses Paket generiert wurde. Wenn sie fertig ist, öffnen Sie Ihre Anforderung von Betreffrechten auf der Seite "Antragstellerrechteanforderungen", öffnen Sie die Registerkarte **"Berichte** ", suchen Sie Ihren Download, und öffnen Sie die ZIP-Datei.

Das Datenpaket enthält eine Vielzahl von Dateien. Die Dateien außerhalb des Azure-Ordners werden als Referenz bereitgestellt und sollten in erster Linie von den Administratoren verwendet werden. Die wichtigsten Materialien für Ihre betroffene Person sind im **Azure-Ordner** enthalten.

Wir empfehlen, den Inhalt dieses Ordners sorgfältig zu überprüfen und nur die erforderlichen Dateien an Ihre betroffene Person zu übermitteln. Sie sollten Ihre Antwort auswerten, um sicherzustellen, dass sie auf die Anforderungen des geltenden Rechts zugeschnitten ist.

### <a name="azure-folder-contents"></a>Azure-Ordnerinhalte

Öffnen Sie diesen Ordner, und öffnen Sie dann die **dateiAEDExport.zip** . Zu den Inhalten gehören:

- Der **Extracted_text_files** Ordner enthält Text, der aus den systemeigenen Dateien extrahiert wurde (sofern unterstützt).
- Der Ordner **"NativeFiles** " enthält alle **enthaltenen** Elemente in ihrem systemeigenen Dateiformat.
- Bearbeitete Dateien befinden sich im Ordner **"NativeFiles** " und weisen das Suffix "_burn.pdf" auf.
- Die exportierten Dateien werden mit eindeutigen Bezeichnern umbenannt, um personenbezogene Daten zu schützen. Sie können mithilfe der **Export_load_file.csv** auf die eindeutigen Namen mit den ursprünglichen Dateinamen verweisen. Da die ursprünglichen Dateinamen vertrauliche Informationen enthalten können, sollten Sie Ihre Richtlinien befolgen, die für diese Informationen gelten.

Nachdem Sie den Inhalt Ihrer ZIP-Datei überprüft haben, ändern Sie sie nach Bedarf, um alle Inhalte zu entfernen, die Sie nicht in das endgültige Paket aufnehmen möchten. Sobald sie abgeschlossen ist, senden Sie sie sicher an Ihre betroffene Person.

## <a name="integrate-with-partner-solutions"></a>Integration in Partnerlösungen

Sie können die Lösung "Priva Subject Rights Requests" mit Ihren vorhandenen Geschäftsprozessen und Tools integrieren, indem Sie die API für Microsoft 365 Anforderung von Antragstellerrechten nutzen. Dies bietet Ihnen eine einfache, aber leistungsstarke Möglichkeit, Automatisierung in Ihre Strategie für Die Rechte von Antragstellern einzuführen.

Wenn betroffene Personen Informationen von Ihrer Organisation anfordern, können Sie unsere APIs nutzen, um diese Anforderungen innerhalb Microsoft 365 basierend auf den für diese Anforderung benutzerdefinierten Kriterien zu erstellen. Sie können die Anforderung von Betreffrechten in Microsoft 365 erstellen, den Fortschritt der Anforderung während der Phasen nachverfolgen und bestätigen, wann die Verarbeitung der Anforderung abgeschlossen ist und der Inhalt abgerufen werden kann. Unsere APIs stehen für jeden zur Verfügung, um ihre Lösungen erweiterbarer zu machen: ob für ISVs, Partner, die für Microsoft 365 in ihren Lösungen geeignet sind, oder für Organisationen, die ihre Branchenanwendungen verwenden können.

Weitere Informationen finden Sie unter [Verwenden der Microsoft Graph-Api für Anträge betroffener Personen](/graph/api/resources/subjectrightsrequest-subjectrightsrequestapioverview).

## <a name="manage-data-retention"></a>Verwalten der Datenaufbewahrung

Berichte, die über dieses Tool generiert werden, und zugehörige Daten, z. B. kommentierte Dateien, die in Azure gespeichert sind, werden für einen bestimmten Zeitraum gespeichert. Diese Dauer wird über **Einstellungen** im Abschnitt "**Datenaufbewahrungszeiträume**" global definiert, sodass Sie zwischen 30 und 90 Tagen wählen können. Überprüfen Sie, ob diese Datenaufbewahrungszeiträume Ihren Richtlinien und gesetzlichen Verpflichtungen entsprechen.

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
