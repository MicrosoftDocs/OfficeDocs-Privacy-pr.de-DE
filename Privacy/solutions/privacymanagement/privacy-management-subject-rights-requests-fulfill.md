---
title: Verwalten von Berichten zu Antragstellerrechten und Erfüllen von Anforderungen in der Datenschutzverwaltung
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
description: Erfahren Sie, wie Sie die von der Datenverwaltung erstellten Datenpakete für Anträge betroffener Personen verwalten und die Anforderung an die betroffene Person erfüllen.
ms.openlocfilehash: 424bb4edc6ddcab86200d76cee767bc9699b281a
ms.sourcegitcommit: 85e085eb17af8b4efd1f45207445e1b3c3679600
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/19/2021
ms.locfileid: "60478197"
---
# <a name="manage-subject-rights-requests-reports-and-fulfill-requests"></a>Verwalten von Berichten zu Antragstellerrechten und Erfüllen von Anforderungen

Nach Abschluss der Datenüberprüfung für eine Anforderung von Betreffrechten können Sie die Erfüllung anfordern. Die Datenschutzverwaltung erstellt Berichte und erfasst die Dateien, die während des Datenüberprüfungsprozesses für **"Einschließen"** markiert sind. Ausgewählte Dateien aus diesen Datenpaketen können an Ihre betroffene Person übermittelt werden, um ihren Antrag zu erfüllen. Das Datenschutzmanagement unterstützt auch die Nutzung der API für anträge betroffener Personen Microsoft 365, um Automatisierungsfunktionen einzuführen.

## <a name="prepare-final-reports-for-the-data-subject"></a>Vorbereiten von Abschlussberichten für die betroffene Person

Das Anforderungsdatenpaket für Betreffrechte wird als ZIP-Datei generiert. Es kann bis zu 30 Minuten dauern, bis dieses Paket generiert wurde. Wenn sie fertig ist, öffnen Sie Ihre Anforderung von Betreffrechten auf der Seite "Antragstellerrechteanforderungen", öffnen Sie die Registerkarte **"Berichte",** suchen Sie Ihren Download, und öffnen Sie die ZIP-Datei.

Das Datenpaket enthält eine Vielzahl von Dateien. Die Dateien außerhalb des Azure-Ordners werden als Referenz bereitgestellt und sollten in erster Linie von den Administratoren verwendet werden. Die wichtigsten Materialien für Ihre betroffene Person sind im **Azure-Ordner** enthalten.

Wir empfehlen, den Inhalt dieses Ordners sorgfältig zu überprüfen und nur die erforderlichen Dateien an Ihre betroffene Person zu übermitteln. Sie sollten Ihre Antwort auswerten, um sicherzustellen, dass sie auf die Anforderungen des geltenden Rechts zugeschnitten ist.

### <a name="azure-folder-contents"></a>Azure-Ordnerinhalte

Öffnen Sie diesen Ordner, und öffnen Sie dann die **dateiAEDExport.zip.** Zu den Inhalten gehören:

- Der **Extracted_text_files** Ordner enthält Text, der aus den systemeigenen Dateien extrahiert wurde (sofern unterstützt).
- Der Ordner **"NativeFiles"** enthält alle **enthaltenen** Elemente in ihrem systemeigenen Dateiformat.
- Bearbeitete Dateien befinden sich im Ordner **"NativeFiles"** und weisen das Suffix "_burn.pdf" auf.
- Die exportierten Dateien werden mit eindeutigen Bezeichnern umbenannt, um personenbezogene Daten zu schützen. Sie können mithilfe der **Export_load_file.csv** auf die eindeutigen Namen mit den ursprünglichen Dateinamen verweisen. Da die ursprünglichen Dateinamen vertrauliche Informationen enthalten können, sollten Sie Ihre Richtlinien befolgen, die für diese Informationen gelten.

Nachdem Sie den Inhalt Ihrer ZIP-Datei überprüft haben, ändern Sie sie nach Bedarf, um alle Inhalte zu entfernen, die Sie nicht in das endgültige Paket aufnehmen möchten. Sobald sie abgeschlossen ist, senden Sie sie sicher an Ihre betroffene Person.

## <a name="integrate-with-partner-solutions"></a>Integration in Partnerlösungen

Sie können das Modul Microsoft 365 Anforderung von Antragstellerrechten in Ihre vorhandenen Geschäftsprozesse und Tools integrieren, indem Sie die api für Microsoft 365 Anforderung von Antragstellerrechten nutzen. Dies bietet Ihnen eine einfache, aber leistungsstarke Möglichkeit, Automatisierung in Ihre Strategie für Die Rechte von Antragstellern einzuführen.

Wenn betroffene Personen Informationen von Ihrer Organisation anfordern, können Sie unsere APIs nutzen, um diese Anforderungen innerhalb Microsoft 365 basierend auf den für diese Anforderung benutzerdefinierten Kriterien zu erstellen. Sie können die Anforderung für Betreffrechte in Microsoft 365 erstellen, den Fortschritt der Anforderung während ihrer Phasen nachverfolgen und bestätigen, wann die Verarbeitung der Anforderung abgeschlossen ist und der Inhalt abgerufen werden kann. Unsere APIs stehen für jeden zur Verfügung, um ihre Lösungen erweiterbarer zu machen: ob für ISVs, Partner, die für Microsoft 365 in ihren Lösungen geeignet sind, oder für Organisationen, die mit ihren Branchenanwendungen arbeiten.

Weitere Informationen finden Sie unter ["Verwenden der Microsoft Graph-Api für Anträge betroffener Personen".](/graph/api/resources/subjectrightsrequest-subjectrightsrequestapioverview)

## <a name="manage-data-retention"></a>Verwalten der Datenaufbewahrung

Berichte, die über dieses Tool generiert werden, und zugehörige Daten, z. B. kommentierte Dateien, die in Azure gespeichert sind, werden für einen bestimmten Zeitraum gespeichert. Diese Dauer wird auf globaler Ebene über **Einstellungen** im Abschnitt **"Datenaufbewahrungszeiträume"** definiert, sodass Sie zwischen 30 und 90 Tagen wählen können. Überprüfen Sie, ob diese Datenaufbewahrungszeiträume Ihren Richtlinien und gesetzlichen Verpflichtungen entsprechen.

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Datenschutzverwaltung](privacy-management-disclaimer.md)
