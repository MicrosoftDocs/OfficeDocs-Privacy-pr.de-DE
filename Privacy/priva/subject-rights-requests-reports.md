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
ms.openlocfilehash: 8a6a41188de78508401b0dfffb3d7cdefb2320a5
ms.sourcegitcommit: 4965df24fdc907f7a6e397f2c78019aaf72c7580
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/17/2022
ms.locfileid: "63564445"
---
# <a name="generate-reports-and-fulfill-a-subject-rights-request"></a>Generieren von Berichten und Erfüllen einer Anforderung zu Betreffrechten

Nachdem Sie Ihre Datenüberprüfung für eine Anforderung zu Betreffrechten in Microsoft Priva abgeschlossen haben, können Sie die Erfüllung anfordern. Priva erstellt Berichte und erfasst die Dateien, die während des Datenüberprüfungsprozesses für **"Einschließen** " markiert sind. Ausgewählte Dateien aus diesen Datenpaketen können an Ihre betroffene Person übermittelt werden, um ihren Antrag zu erfüllen. Priva unterstützt auch die Nutzung der API für anträge von Microsoft 365 Betreffrechten, um Automatisierungsfunktionen einzuführen.

## <a name="understanding-reports"></a>Grundlegendes zu Berichten

Nachdem Sie die **Option "Vollständige Überprüfung** " in der **Überprüfungsdatenstufe** der Anforderung für Betreffrechte ausgewählt haben, werden die endgültigen Berichte für die Anforderung automatisch generiert. Auf der Registerkarte **"Berichte** " auf der Seite "Details zu Anträgen betroffener Personen" gibt die Spalte **"Status** " an, wann die Berichtsgenerierung **ausgeführt** wird und wann ein Bericht **zum Herunterladen bereit** ist. Es kann bis zu 30 Minuten dauern, bis die Erstellung der Berichte abgeschlossen ist.

Berichte sind in zwei Abschnitte unterteilt:
1. **Berichte für die betroffene Person**: Diese Berichte enthalten Informationen, die im Rahmen der Anforderungserfüllung an die betroffene Person zurückgegeben werden können. Hier finden Sie das **Datenpaket** , das Dateien enthält, die Sie an die betroffene Person senden können.
   > [!IMPORTANT]
   > Ein Datenpaket wird nur generiert, wenn Sie Elemente während der Datenüberprüfung als **"Einschließen"** markieren.

   > [!IMPORTANT]
   > Ein Datenpaket wird nur für **Export-** und **Zugriffstypen** von Anforderungen generiert. Ein Datenpaket wird für eine **Tagged-Liste zur Nachverfolgungsanforderung** nicht generiert. Überprüfen Sie Details zu [Anforderungstypen für Betreffrechte](subject-rights-requests-create.md#use-the-subject-rights-request-creation-wizard).

2. **Berichte für die interne Verwendung**: Diese Berichte beziehen sich auf die internen Datensätze Ihrer Organisation im Zusammenhang mit der Anforderung von Antragstellerrechten. Sie enthalten ein Überwachungsprotokoll und eine Liste aller Dateien, auf die Sie tags während der Datenüberprüfung angewendet haben, um nachzuschlagen oder weitere Maßnahmen zu ergreifen.

## <a name="prepare-final-reports-for-the-data-subject"></a>Vorbereiten von Abschlussberichten für die betroffene Person

Das Anforderungsdatenpaket für Betreffrechte wird als ZIP-Datei generiert. Es kann bis zu 30 Minuten dauern, bis dieses Paket generiert wurde. Wenn sie fertig ist, öffnen Sie Ihre Anforderung von Betreffrechten auf der Seite "Antragstellerrechteanforderungen", öffnen Sie die Registerkarte **"Berichte** ", suchen Sie Ihren Download, und öffnen Sie die ZIP-Datei.

Das Datenpaket enthält eine Vielzahl von Dateien. Die Dateien außerhalb des Azure-Ordners werden als Referenz bereitgestellt und sollten in erster Linie von den Administratoren verwendet werden. Die wichtigsten Materialien für Ihre betroffene Person sind im **Azure-Ordner** enthalten.

Wir empfehlen, den Inhalt dieses Ordners sorgfältig zu überprüfen und nur die erforderlichen Dateien an Ihre betroffene Person zu übermitteln. Sie sollten Ihre Antwort auswerten, um sicherzustellen, dass sie auf die Anforderungen des geltenden Rechts zugeschnitten ist.

### <a name="azure-folder-contents"></a>Azure-Ordnerinhalte

Öffnen Sie diesen Ordner, und öffnen Sie dann die **AEDExport.zip** Datei. Zu den Inhalten gehören:

- Der **Extracted_text_files** Ordner enthält Text, der aus den systemeigenen Dateien extrahiert wurde (sofern unterstützt).
- Der Ordner **"NativeFiles** " enthält alle **enthaltenen** Elemente in ihrem systemeigenen Dateiformat.
- Bearbeitete Dateien befinden sich im Ordner **"NativeFiles** " und weisen das Suffix "_burn.pdf" auf.
- Die exportierten Dateien werden mit eindeutigen Bezeichnern umbenannt, um personenbezogene Daten zu schützen. Sie können mithilfe der **Export_load_file.csv** auf die eindeutigen Namen mit den ursprünglichen Dateinamen verweisen. Da die ursprünglichen Dateinamen vertrauliche Informationen enthalten können, sollten Sie Ihre Richtlinien befolgen, die für diese Informationen gelten.

Nachdem Sie den Inhalt Ihrer ZIP-Datei überprüft haben, ändern Sie sie nach Bedarf, um alle Inhalte zu entfernen, die Sie nicht in das endgültige Paket aufnehmen möchten. Sobald sie abgeschlossen ist, senden Sie sie sicher an Ihre betroffene Person.

## <a name="integrate-with-partner-solutions"></a>Integration in Partnerlösungen

Sie können die Lösung "Priva Subject Rights Requests" mit Ihren vorhandenen Geschäftsprozessen und Tools integrieren, indem Sie die API für Microsoft 365 Anforderung von Antragstellerrechten verwenden. Die Verwendung der API bietet Ihnen eine einfache, aber leistungsstarke Möglichkeit, Automatisierung in Ihre Strategie für Die Rechte von Antragstellern einzuführen.

Wenn betroffene Personen Informationen von Ihrer Organisation anfordern, können unsere APIs helfen, diese Anforderungen innerhalb Microsoft 365 basierend auf den eindeutigen Kriterien der Anforderung zu erstellen. Sie können die Anforderung von Betreffrechten in Microsoft 365 erstellen, den Fortschritt der Anforderung während der Phasen nachverfolgen und bestätigen, wann die Verarbeitung der Anforderung abgeschlossen ist und der Inhalt abgerufen werden kann. Unsere APIs stehen für jeden zur Verfügung, um ihre Lösungen erweiterbarer zu machen: ob für ISVs, Partner, die für Microsoft 365 in ihren Lösungen geeignet sind, oder für Organisationen, die mit ihren Branchenanwendungen arbeiten können.

Weitere Informationen finden Sie unter ["Verwenden der Microsoft Graph-Api für Anträge betroffener Personen](/graph/api/resources/subjectrightsrequest-subjectrightsrequestapioverview)".

## <a name="manage-data-retention"></a>Verwalten der Datenaufbewahrung

Berichte, die über dieses Tool generiert werden, und zugehörige Daten, z. B. kommentierte Dateien, die in Azure gespeichert sind, werden für einen bestimmten Zeitraum gespeichert. Der Aufbewahrungszeitraum für Daten ist in Priva **Einstellungen** definiert und gilt für alle Anträge betroffener Personen. Führen Sie die folgenden Schritte aus, um Ihre Datenaufbewahrungszeiträume anzuzeigen oder zu ändern:

1. Wählen Sie von überall in Priva Subject Rights Requests **in** der oberen rechten Ecke des Bildschirms Einstellungen (das Zahnradsymbol) aus.
2. Wählen Sie im linken Navigationsbereich **Datenaufbewahrungszeiträume** aus.
3. Wählen Sie im Dropdownmenü entweder 30 Tage oder 90 Tage als Aufbewahrungszeitraum aus.

Stellen Sie sicher, dass die von Ihnen gewählten Datenaufbewahrungszeiträume den Richtlinien und gesetzlichen Verpflichtungen Ihrer Organisation entsprechen.

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Microsoft Priva](priva-disclaimer.md)
