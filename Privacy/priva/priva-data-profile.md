---
title: Suchen und Visualisieren personenbezogener Daten in Microsoft Priva
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
- M365-priva-subject-rights-requests
search.appverid:
- MOE150
- MET150
description: Erfahren Sie mehr über die Übersicht und das Datenprofil in Priva und wie Sie Einblicke in die personenbezogenen Daten in der Microsoft 365 Umgebung Ihrer Organisation erhalten.
ms.openlocfilehash: e09becfbbd64128f44ef6d1d29fc367850f13411
ms.sourcegitcommit: bbaa4400bc9c7db9bdb2784e3af160daf5d08290
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/26/2022
ms.locfileid: "65059749"
---
# <a name="find-and-visualize-personal-data-in-microsoft-priva"></a>Suchen und Visualisieren personenbezogener Daten in Microsoft Priva

Microsoft Priva hilft Ihnen, die in Ihrer Organisation gespeicherten Daten zu verstehen, indem die Ermittlung personenbezogener Datenobjekte automatisiert und Visualisierungen wichtiger Informationen bereitgestellt werden. Diese Visualisierungen finden Sie auf den **Übersichts** - und **Datenprofilseiten** . Sie können hier auf die Erkenntnisse reagieren, um den Datenschutzstatus Ihrer Organisation zu stärken und Risiken zu reduzieren.

Wechseln Sie zunächst zum Priva-Abschnitt des [Microsoft Purview Compliance-Portals](https://compliance.microsoft.com/) , und zeigen Sie diese Seiten an:

- **Übersicht**: Bietet einen Überblick über die Daten Ihrer Organisation in Microsoft 365. Datenschutzadministratoren können Trends und Aktivitäten überwachen, potenzielle Risiken im Zusammenhang mit personenbezogenen Daten identifizieren und untersuchen und wichtige Aktivitäten wie Richtlinienverwaltung oder Aktionen zur Anforderung von Rechten betroffener Personen umsetzen.
- **Datenprofil**: Stellt eine Momentaufnahme der personenbezogenen Daten bereit, die Ihre Organisation in Microsoft 365 speichert. Auf dieser Seite können Sie visualisieren, wo sich personenbezogene Daten befinden, welche Typen in Ihrer Organisation am häufigsten verwendet werden und wie viele verschiedene Typen standortübergreifend in Ihrer Microsoft 365-Umgebung vorhanden sind. Sie können auch personenbezogene Daten von diesem Ort aus erkunden.

Wenn sich Ihre Daten ändern und Priva neue Erkenntnisse macht, werden die auf diesen Seiten angezeigten Informationen aktualisiert. Beachten Sie, dass es bis zu 24 Stunden dauern kann, bis neue Daten in den Diagrammen dargestellt werden.

## <a name="explore-the-overview-page"></a>Erkunden der Übersichtsseite

Die Übersichtsseite besteht aus drei Hauptabschnitten. Kacheln am oberen Rand der Seite stellen wichtige aktuelle Statistiken zu Ihren Daten bereit. Der Abschnitt "Wichtige Einblicke" bietet Untersuchungsmöglichkeiten zu Trends und Bereichen von wichtigem Interesse. Weitere Perspektiven auf Ihre Datenumgebung finden Sie in den Trendliniendiagrammen. Weitere Informationen zu diesen Bereichen finden Sie in den folgenden Abschnitten.

![Beispielübersichtsseite.](../media/priva-overview.png)

### <a name="top-tiles"></a>Obere Kacheln

#### <a name="policy-matches-over-past-7-days"></a>Richtlinienübereinstimmungen in den letzten 7 Tagen

Wenn Richtlinien innerhalb von Priva Privacy Risk Management festgelegt werden, werden Ihre Daten basierend auf Ihren Richtlinien für bestimmte Bedingungen ausgewertet, die Datenschutzrisiken darstellen können. Richtlinienübereinstimmungen deuten auf Datenerhebungen hin, die möglicherweise noch überprüft oder behoben werden müssen. Diese Kachel zeigt, wie viele Richtlinienübereinstimmungen innerhalb der letzten sieben Tage aufgetreten sind. Hier werden Übereinstimmungen angezeigt, unabhängig davon, ob Richtlinien aktiviert sind oder im Testmodus ausgeführt werden, sodass Sie die Ergebnisse aller aktiven Richtlinien sehen können. Wenn Sie diese Kachel auswählen, gelangen Sie zu einer gefilterten Ansicht der Seite **"Richtlinien** " des Datenschutzrisikomanagements, in der die Richtlinien angezeigt werden, für die innerhalb der letzten sieben Tage eine Übereinstimmung aufgetreten ist.

#### <a name="items-with-personal-data"></a>Elemente mit personenbezogenen Daten

Um die automatisierten Ermittlungsfunktionen von Priva bei der Arbeit zu sehen, überprüfen Sie die Kachel **"Elemente mit personenbezogenen Daten** ". Diese Kachel zeigt, wie viele neue Elemente, die personenbezogene Daten basierend auf Ihren Einstellungen enthalten, in den letzten sieben Tagen in der Microsoft 365 Umgebung Ihrer Organisation ermittelt wurden. Wenn Sie diese Kachel auswählen, wird eine Ansicht der neuesten 100 ermittelten Elemente geladen.

#### <a name="subject-rights-requests"></a>Anträge betroffener Personen

Die Übersichtsseite enthält eine Kachel, die zeigt, wie viele Anfragen zu Rechten betroffener Personen in den letzten sieben Tagen erstellt wurden. Eine zweite Kachel zeigt ggf. an, wie viele Anforderungen basierend auf Ihren festgelegten Fristen überfällig sind und möglicherweise sofortige Aufmerksamkeit erfordern. Wenn Sie diese Kacheln auswählen, erhalten Benutzer die entsprechenden Berechtigungen für die Anforderungsseite für Rechte betroffener Personen von Priva.

### <a name="key-insights"></a>Wichtige Einblicke

#### <a name="content-items-with-the-most-personal-data"></a>Inhaltselemente mit den persönlichsten Daten

Inhalte, die eine große Menge an personenbezogenen Daten enthalten, können ein höheres Risiko der Gefährdung darstellen. Möglicherweise möchten Sie solche Elemente überprüfen, um sicherzustellen, dass sie von einer Richtlinie für das Datenschutzrisikomanagement abgedeckt sind. Um diese Elemente auf Sich aufmerksam zu machen, bietet die Übersichtsseite einen Einblick in Ihre Inhaltselemente, die die persönlichsten Daten gemäß Ihren Einstellungen enthalten. Hier sehen Sie die Anzahl der erkannten eindeutigen persönlichen Datentypen, wie viele eindeutige Inhaltsbesitzer identifiziert wurden und wie viele betroffene Personen gemäß den Datenabgleichseinstellungen für Anfragen von Betroffenenrechten identifiziert wurden.

Wählen Sie **"Zusammenfassung anzeigen"** für eine Zusammenfassungsansicht der gefundenen Elemente aus. Sie können diese Ergebnisse auch **durchsuchen** , um eine Vorschau einzelner Dateien anzuzeigen. In dieser Ansicht werden maximal 100 Elemente angezeigt. Benutzer in der Rollengruppe "Datenschutzverwaltung" können Dateien auswählen, um Details zu überprüfen und die Relevanz zu bestimmen, und die Liste zur Referenz in .csv Format exportieren.

#### <a name="policies-with-the-most-matches-in-the-last-week"></a>Richtlinien mit den meisten Übereinstimmungen in der letzten Woche

Dieser Einblick zeigt, welche Richtlinien in den letzten sieben Tagen am häufigsten abgeglichen wurden, ob im "Ein"-Modus oder im "Testen". Es hilft, die Leistung Ihrer Richtlinien und die Auswirkungen der laufenden Arbeit zu veranschaulichen, während Ihre Priva-Benutzer ihr Datenschutzverhalten verfeinern.

Wählen Sie **"Zusammenfassung anzeigen"** aus, um eine Zusammenfassung der 10 besten übereinstimmenden Richtlinien und der Inhaltsbesitzer der zugeordneten Inhalte anzuzeigen. Außerdem wird angezeigt, wie viele Benutzerbenachrichtigungen aufgrund dieser Richtlinienübereinstimmungen gesendet wurden und wie viele Benutzeraktionen ausgeführt wurden. Wählen Sie **"Untersuchen** " aus, um die Seite "Richtlinien" im Datenschutzrisikomanagement anzuzeigen, gefiltert, um die Richtlinien aus der Zusammenfassungsansicht anzuzeigen. In dieser Untersuchungsansicht werden Statistiken für die gesamte Lebensdauer der Richtlinie angezeigt. Wählen Sie sie aus, um Details anzuzeigen, z. B. wann übereinstimmende Elemente anfänglich erkannt wurden.

#### <a name="users-with-the-most-policy-matched-in-the-last-week"></a>Benutzer mit der am häufigsten übereinstimmenden Richtlinie in der letzten Woche

Dieser Einblick befasst sich auch mit Übereinstimmungen aus Richtlinien im Modus "Testen" oder "Ein". Sie können eine Zusammenfassung der Benutzer mit den meisten Richtlinienübereinstimmungen in der letzten Woche und den richtlinienübereinstimmungen anzeigen. Dazu gehören Summen der eindeutigen Inhaltsbesitzer, Benachrichtigungen, die an diese Benutzer gesendet wurden, und die Anzahl der Aktionen, die aus diesen Benachrichtigungen ausgeführt wurden. Wenn Sie **"Untersuchen** " auswählen, gelangen Sie zur Seite "Richtlinien", gefiltert, um die Richtlinien aus der Zusammenfassungsansicht anzuzeigen. In der Untersuchungsansicht finden Sie keine Benutzerinformationen, aber Sie können eine Richtlinie auswählen, um Richtliniendetails zu diesen Übereinstimmungen anzuzeigen.

#### <a name="items-with-the-most-data-subject-content"></a>Elemente mit den meisten Inhalten betroffener Personen

Dieser Einblick zeigt Inhaltselemente, die die personenbezogenen Daten der meisten betroffenen Personen enthalten. Um diese Erkenntnisse zu erhalten, muss Ihre Organisation [den Datenabgleich für Anfragen zu Rechten betroffener Personen](subject-rights-requests-data-match.md) einrichten.

Diese Elemente können ihnen helfen, ihre Datenabgleichskonfiguration zu bestätigen und Datenschutzrisiken im Zusammenhang mit diesen Elementen zu minimieren. Wählen Sie **"Zusammenfassung anzeigen"** für eine Zusammenfassungsansicht aus. Wählen Sie **"Durchsuchen** " aus, um eine detaillierte Ansicht von bis zu 100 dieser Elemente anzuzeigen. Hier können Sie eine Vorschau dieser Elemente anzeigen und die Relevanz bestimmen und die Liste in .csv Format exportieren.

### <a name="trendline-graphs"></a>Trendliniendiagramme

Dynamische Visualisierungen von Trends in den Daten Ihrer Organisation finden Sie in den Trendliniendiagrammen. Diese Diagramme können nach Merkmalen wie Zeiträumen, Datentypen oder Datenspeicherorten gefiltert werden. Verwenden Sie die bereitgestellten Dropdowns, um Ihre Ansicht anzupassen. Wenn Sie mit dem Mauszeiger auf Linien im Diagramm zeigen, können Sie Statistiken im Zusammenhang mit diesem bestimmten Zeitpunkt anzeigen.

Die Ergebnisse im Zusammenhang mit Richtlinien enthalten Daten aus Richtlinien sowohl im Testmodus als auch im "Ein"-Modus. Wenn keine Richtlinien eines bestimmten Typs aktiv sind, werden in den zugehörigen Diagrammen keine Ergebnisse angezeigt.

#### <a name="active-policy-alerts"></a>Aktive Richtlinienwarnungen

In diesem Bereich wird eine Momentaufnahme aktiver Warnungen angezeigt, die durch Richtlinienübereinstimmungen ausgelöst werden. Im Laufe der Zeit kann Ihnen diese Ansicht helfen, Anomalien wie große Volumenspitzen leichter zu erkennen. Wählen Sie **"Warnungen anzeigen** " aus, um zur Seite "Richtlinien" im Datenschutzrisikomanagement zu navigieren, auf der Sie Warnungen weiter untersuchen und Probleme zur Behebung erstellen können.

#### <a name="personal-data-found-in-organization"></a>In der Organisation gefundene personenbezogene Daten

Dieses Diagramm zeigt, wie viele personenbezogene Daten, die Ihren Einstellungen entsprechen, im Laufe der Zeit in Ihrer Microsoft 365 Umgebung ermittelt wurden und wo sie sich befinden. Es beginnt mit dem Auffüllen, nachdem Priva ausreichend lange ausgeführt wurde und inhalte mit personenbezogenen Daten in SharePoint, OneDrive, Teams und/oder Exchange gefunden wurden.

#### <a name="data-transfers-detected-in-organization"></a>In der Organisation erkannte Datenübertragungen

Dieses Diagramm bezieht sich auf Datenübertragungsrichtlinien. Es bietet eine Übersicht darüber, wie Daten innerhalb Ihrer Organisation verschoben werden, entweder zwischen Abteilungen oder zwischen Regionen für Multi-Geo-Organisationen.

#### <a name="unused-personal-data"></a>Nicht verwendete personenbezogene Daten

Dieses Diagramm bezieht sich auf Datenminimierungsrichtlinien. Es gibt Einblicke, wie Ihre Organisation Inhalte speichert, die personenbezogene Daten enthalten, und wie Ihre Richtlinien Ihren Umgang mit diesen Daten im Laufe der Zeit verbessern können.

#### <a name="overexposed-personal-data"></a>Überbelichtete personenbezogene Daten

Dieses Diagramm bezieht sich auf Datenüberbelichtungsrichtlinien. Es kann Ihnen dabei helfen, das Freigabeverhalten im Laufe der Zeit innerhalb Ihrer Organisation und an Orten zu identifizieren, an denen Inhalte mit personenbezogenen Daten möglicherweise überbelichtet sind, z. B. durch die öffentliche Freigabe, die Freigabe für einen externen Benutzer oder die gemeinsame Nutzung von Inhalten innerhalb Ihrer Organisation.

#### <a name="subject-rights-requests-by-regulation"></a>Anträge betroffener Personen nach Verordnung

Diese Ansicht bietet Einblicke in die Bestimmungen, die im Laufe der Zeit am häufigsten Anforderungen an Ihre Betroffenenrechte fördern. Die Legende dieses Diagramms zeigt die Namen der trendenden Vorschriften. Wenn Sie mit dem Mauszeiger auf die Trendlinien zeigen, werden die Summen der Anträge betroffener Personen angezeigt, die für diese Verordnung während des ausgewählten Zeitraums geöffnet sind.

#### <a name="subject-rights-requests-by-status"></a>Anträge betroffener Personen nach Status

Dieses Diagramm zeigt, wie Ihre Organisation mit dem Ausfüllen von Anfragen zu Rechten betroffener Personen umgeht, aufgeschlüsselt in Anforderungen, die entweder **aktiv**, **geschlossen** oder **überfällig** sind. Anhand der hier gezeigten Ergebnisse können Sie erkennen, wo Sie von der Zuweisung weiterer Ressourcen zum Schließen Ihrer Anforderungen und Besprechungsziele profitieren können.

### <a name="additional-data-views"></a>Zusätzliche Datenansichten

#### <a name="subject-rights-requests-at-a-glance"></a>Anträge betroffener Personen auf einen Blick

Diese Ansicht bietet eine allgemeine Übersicht über aktive Anträge betroffener Personen, einschließlich der verbleibenden Zeit zum Abschließen von Anträgen nach deren Fristen. Es fasst zusammen, wie viele Anforderungen Sie insgesamt haben, wie viele aktiv sind und wie viele geschlossen werden. Wählen Sie **"Alle Anforderungen anzeigen** " aus, um zur Anforderungsseite für Die Betroffenenrechte zu wechseln, auf der Sie weitere Details anzeigen und an den aktiven Anforderungen arbeiten können, um sie bis zum Abschluss fortzuentwickeln.

#### <a name="subject-rights-requests-by-residency"></a>Anträge betroffener Personen nach Wohnsitz

Diese Kartenansicht hilft Ihnen bei der Visualisierung Ihres Volumens von Anfragen zu Rechten betroffener Personen durch den Aufenthalt der betroffenen Personen. Wenn Sie mit dem Mauszeiger auf eine Blase zeigen, werden die Region und die Gesamtzahl der Anträge betroffener Personen identifiziert, die im Namen der Dort ansässigen Personen geöffnet wurden.

## <a name="explore-the-data-profile-page"></a>Erkunden der Datenprofilseite

Die Datenprofilseite in Priva bietet eine Momentaufnahme der personenbezogenen Daten, die Ihre Organisation in Microsoft 365 speichert und wo sie sich befinden. Es bietet auch Einblicke in die Arten von Daten, die Sie speichern. Die Hauptkacheln umfassen Folgendes:

![Beispieldatenprofilseite.](../media/priva-dataprofile.png)

### <a name="personal-data-type-instances-detected-in-microsoft-365"></a>In Microsoft 365 erkannte Instanzen des persönlichen Datentyps

Mithilfe dieser Kachel können Sie basierend auf Ihren Einstellungen visualisieren, wie viele personenbezogene Daten in Ihrer Microsoft 365-Umgebung vorhanden sind und wie diese Daten auf Exchange, OneDrive, SharePoint und Teams verteilt werden.

Das Balkendiagramm zeigt die ungefähre Aggregatanzahl der eindeutigen Instanzen des persönlichen Datentyps, die in Ihrem Inhalt gefunden wurden. Beispiele für Datentypen können Kreditkartennummern und Sozialversicherungsnummern sein. Daher würde eine ermittelte Datei, die drei Kreditkartennummern und eine Sozialversicherungsnummer enthält, zwei eindeutige persönliche Datentypen und vier Instanzen enthalten. Der untere Teil dieser Kachel zeigt die eindeutigen persönlichen Datentypen innerhalb jedes Microsoft 365 Speicherorts an. Es bietet einen Einblick in die Vielfalt der personenbezogenen Datentypen, die in den Inhalten Ihrer Organisation erkannt werden.

### <a name="top-personal-data-types-across-your-organization"></a>Die wichtigsten persönlichen Datentypen in Ihrer Organisation

Diese Kachel bietet eine Momentaufnahme der wichtigsten in Ihrer Umgebung erkannten persönlichen Datentypen sowie Informationen dazu, wie viele Elemente diesen persönlichen Datentyp enthalten und an welchen Orten.

### <a name="personal-data-type-instances-by-region"></a>Instanzen des persönlichen Datentyps nach Region

Bei Multi-Geo-Umgebungen aggregiert diese Kachel instanzen des persönlichen Datentyps, die in Ihren Inhalten gefunden werden, basierend auf den Regionen, in denen diese Inhalte gehostet werden. Bei Organisationen mit einer Region wird auf dieser Kachel ein Punkt angezeigt, der Ihren Microsoft 365 Standort darstellt. Wenn Sie mit dem Mauszeiger auf Punkte auf der Karte zeigen, wird die ungefähre Anzahl von Instanzen des persönlichen Datentyps angezeigt, die in dieser Region ermittelt wurden.

### <a name="exploring-content"></a>Erkunden von Inhalten

Wenn Sie **"Durchsuchen** " auf einer beliebigen Datenprofilkachel auswählen, wird der Inhalts-Explorer geöffnet. Derzeit können Sie nicht nach einem bestimmten Inhaltselement suchen, und in dieser Ansicht werden Teams Daten nicht angezeigt. Dies bedeutet, dass Zahlen im Inhalts-Explorer möglicherweise nicht mit den Zahlen übereinstimmen, die auf der Datenprofilseite angezeigt werden, da die Datenprofilseite Teams Inhalt enthält. Datenschutzadministratoren, die weitere Einblicke in ihre Datenschutzdaten wünschen, können dies hier basierend auf dem persönlichen Datentyp (Typ vertraulicher Informationen) oder nach Standort (Exchange, OneDrive oder SharePoint) tun.

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
