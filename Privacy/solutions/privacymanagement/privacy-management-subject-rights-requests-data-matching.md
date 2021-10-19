---
title: Verwalten des Datenabgleichs für Anträge betroffener Personen in der Datenschutzverwaltung
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
description: Erfahren Sie, wie Sie zusätzliche Informationen zum Datenschutzmanagement über Ihre betroffenen Personen hochladen.
ms.openlocfilehash: 00a902705336d766993e805d78609a48334b2bf6
ms.sourcegitcommit: 85e085eb17af8b4efd1f45207445e1b3c3679600
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/19/2021
ms.locfileid: "60478274"
---
# <a name="manage-data-matching-for-subject-rights-requests"></a>Verwalten des Datenabgleichs für Anträge betroffener Personen

Mit dem Datenabgleich können Organisationen die Datenverwaltung aktivieren, um betroffene Personen basierend auf genau angegebenen Datenwerten zu identifizieren. Dies kann dazu beitragen, die Genauigkeit der Suche nach Inhalten betroffener Personen zu erhöhen, die diesen Datenwerten sowohl für Ihr internes Personal als auch für externe Benutzer, mit denen Sie interagieren, entspricht. Außerdem vereinfacht es die Notwendigkeit, Felder während der Erstellung von Anträgen auf Antrag einer Betroffenen manuell zur Verfügung zu stellen, und bietet Kontext innerhalb von Anträgen von Betreffrechten und für die Kachel "Übersicht", die Ihre Elemente mit den meisten Inhalten betroffener Personen anzeigt. Weitere Informationen zu dieser Ansicht finden Sie unter [Suchen und Visualisieren Ihrer Daten.](privacy-management-data-profile.md#items-with-the-most-data-subject-content)

Um die Datenabgleichsfunktion zu verwenden, müssen Sie Mitglied der Rollengruppe "Datenschutzverwaltung" sein. Wählen Sie in der Datenverwaltung im [Microsoft 365 Compliance Center](https://compliance.microsoft.com/) **im** oberen Navigationsbereich Einstellungen und dann **Daten ab.** Von hier aus müssen Sie das Schema für personenbezogene Daten definieren und einen Upload personenbezogener Daten bereitstellen, wie unten dargestellt. Beachten Sie, dass Sie Elemente hinzufügen und Elemente löschen können, die Sie über die Benutzeroberfläche hinzufügen. Sie können jedoch derzeit kein Element über die Benutzeroberfläche ändern.

## <a name="prepare-for-data-import"></a>Vorbereiten des Datenimports

Bevor Sie das Schema definieren oder Daten hochladen, müssen Sie die Quelle der Informationen der betroffenen Person identifizieren. Das erforderliche Dateiformat ist .csv, das von einer Anwendung wie Microsoft Excel gelesen werden kann. Strukturieren Sie diesen Export so, dass die Spaltenüberschriften in der ersten Zeile angezeigt werden. Diese Header sollten die Namen der Attribute für Ihr Schema für personenbezogene Daten enthalten. Überprüfen Sie das Format der Daten in den einzelnen Feldern. Wenn eines der Daten Kommas enthält, umgeben Sie diese Werte mit doppelten Anführungszeichen, um sicherzustellen, dass sie nicht in separate Felder analysiert werden.

## <a name="define-the-personal-data-schema"></a>Definieren des Schemas für personenbezogene Daten

Das Schema für personenbezogene Daten beschreibt die Attribute für Ihre betroffenen Personen. Hochladen dieses Schema auf der ersten Registerkarte des Einstellungsbereichs für datenübereinstimmungen. Die erforderlichen Dateien umfassen eine XML-Datei mit dem Schema für **personenbezogene Daten** und eine REGELpaket-XML-Datei. 

### <a name="personal-data-schema-xml"></a>XML des Schemas für personenbezogene Daten

Die Schemadatei für personenbezogene Daten ist eine XML-Datei, die definiert, welche Spaltennamen erwartet werden.

- Benennen Sie diese Schemadatei *pdm.xml*.
- Definieren Sie jeden Spaltennamen mithilfe des Feldnamentags, wie im folgenden Beispiel dargestellt.
- Verwenden Sie durchsuchbar = "true" für Felder, die durchsuchbar sein sollen, bis zu maximal fünf Felder. Mindestens einer ihrer Feldnamen muss durchsuchbar sein. Beispielsyntax: `\<Field name="" searchable=""/>` .
- Das Schema für personenbezogene Daten verfügt über einen DataStore-Tag-Abschnitt. Den Feldnamen müssen vier Pflichtfelder zugeordnet werden: primaryKeyField, upnField, firstNameField, lastNameField.

Die folgende XML-Datei definiert beispielsweise ein Beispielschema, wobei fünf Felder als durchsuchbar angegeben sind: PatientID, MRN, SSN, Telefon und DOB. The primaryKeyField is mapped to PatientID, upnField is mapped to MRN, firstNameField is mapped to FirstName, and lastNameField is mapped to LastName.

Sie können das Beispiel kopieren, ändern und verwenden.

 ```xml
<PdmSchema xmlns="http://schemas.microsoft.com/office/2020/pdm">
      <DataStore name="Patientrecords" description="Schema for patient records" version="1" primaryKeyField="PatientID" upnField="MRN" firstNameField="FirstName" lastNameField="LastName">
            <Field name="PatientID" searchable="true"/>
            <Field name="MRN" searchable="true" />
            <Field name="FirstName" />
            <Field name="LastName" />
            <Field name="SSN" searchable="true" />
            <Field name="Phone" searchable="true" />
            <Field name="DOB" searchable="true" />
            <Field name="Gender" />
            <Field name="Address" />
      </DataStore>
</PdmSchema>
 ```

### <a name="rule-package-xml"></a>Regelpaket-XML

Wenn Sie das Regelpaket einrichten, müssen Sie die oben erstellte Schemadatei für personenbezogene Daten korrekt referenzieren: pdm.xml. Im folgenden Beispiel für das Regelpaket-XML müssen die folgenden Felder angepasst werden, um Daten mit dem vertraulichen Typ zu erstellen:

- **RulePack-ID**  &  **PrivacyMatch-ID:** Verwenden Sie "New-GUID", um eine GUID zu generieren.
- **Datenspeicher:** Dieses Feld gibt den zu verwendenden Nachschlagedatenspeicher für personenbezogene Daten an. Geben Sie den definierten DataStore-Namen eines konfigurierten Schemas für personenbezogene Daten an.
- **idMatch:** Dieses Feld verweist auf das primäre Element für die Übereinstimmung mit personenbezogenen Daten.
  - **Übereinstimmungen:** Gibt das Feld an, das bei der genauen Suche verwendet werden soll. Geben Sie einen durchsuchbaren Feldnamen aus dem Schema für personenbezogene Daten an.
  - **Klassifizierung:** Dieses Feld gibt die Übereinstimmung des vertraulichen Typs an, die die Suche nach Übereinstimmungen mit personenbezogenen Daten auslöst. Sie können den Namen oder die GUID eines vorhandenen integrierten oder benutzerdefinierten vertraulichen Informationstyps angeben. Um Leistungsprobleme zu vermeiden, sollten Sie, wenn Sie einen benutzerdefinierten vertraulichen Informationstyp als Klassifizierungselement in der Übereinstimmung mit personenbezogenen Daten verwenden, keinen benutzerdefinierten vertraulichen Informationstyp verwenden, der einem großen Prozentsatz des Inhalts entspricht (z. B. "beliebige Zahl" oder "ein beliebiges Fünf-Buchstaben-Wort"). Es wird empfohlen, unterstützende Schlüsselwörter hinzuzufügen oder Formatierungen in die Definition des benutzerdefinierten Vertraulichen Informationstyps für Klassifizierungen aufzunehmen.
- **Übereinstimmung:** Dieses Feld verweist auf zusätzliche Nachweise, die in der Nähe von idMatch gefunden wurden.
  - **Übereinstimmungen:** Geben Sie einen beliebigen Feldnamen im Schema für personenbezogene Daten für DataStore an.
- **Ressource:** In diesem Abschnitt werden der Name und die Beschreibung für den vertraulichen Typ in mehreren Gebietsschemas angegeben.
  - **idRef:** Geben Sie GUID für ExactMatch-ID an.
  - **Name & Beschreibungen:** Nach Bedarf anpassen.

In unserem xml-Beispiel für das Regelpaket unten verweisen wir auf die pdm.xml Beispieldatei aus dem vorherigen Schritt, die das XML-Schema für personenbezogene Daten erstellt:

- **Datastore**: Der DataStore-Name verweist auf die Schemadatei, die wir zuvor erstellt haben: dataStore = "PatientRecords".
- **idMatch**: Der idMatch-Wert verweist auf ein durchsuchbares Feld, das in der zuvor erstellten pdm.xml Datei aufgeführt ist: idMatch matches = "SSN".
  - **Klassifizierung:** Der Klassifizierungswert verweist auf einen vorhandenen oder benutzerdefinierten vertraulichen Informationstyp: Klassifizierung = "U.S. Sozialversicherungsnummer (SSN)". (In diesem Fall wird der vorhandene vertrauliche Informationstyp "US-Sozialversicherungsnummer" verwendet.)

Erstellen Sie ein Regelpaket im XML-Format (mit Unicode-Codierung), wie im folgenden Beispielcode. Sie können dieses Beispiel kopieren, ändern und verwenden.

 ```xml
<RulePackage xmlns="http://schemas.microsoft.com/office/2020/pdm">
  <RulePack id="fd098e03-1796-41a5-8ab6-198c93c62b21">
    <Version build="0" major="2" minor="0" revision="0" />
    <Publisher id="eb553734-8306-44b4-9ad5-c388ad970528" />
    <Details defaultLangCode="en-us">
      <LocalizedDetails langcode="en-us">
        <PublisherName>IP DLP</PublisherName>
        <Name>Health Care PDM Rulepack</Name>
        <Description>This rule package contains the Personal Data Match sensitive type for health care sensitive types.</Description>
      </LocalizedDetails>
    </Details>
  </RulePack>
  <Rules>
    <PrivacyMatch id = "E1CC861E-3FE9-4A58-82DF-4BD259EAB381" patternsProximity = "300" dataStore ="PatientRecords" recommendedConfidence = "65" >
      <Pattern confidenceLevel="65">
        <idMatch matches = "SSN" classification = "U.S. Social Security Number (SSN)" />
      </Pattern>
      <Pattern confidenceLevel="75">
        <idMatch matches = "SSN" classification = "U.S. Social Security Number (SSN)" />
        <Any minMatches ="3" maxMatches ="6">
          <match matches="PatientID" />
          <match matches="MRN"/>
          <match matches="FirstName"/>
          <match matches="LastName"/>
          <match matches="Phone"/>
          <match matches="DOB"/>
        </Any>
      </Pattern>
    </PrivacyMatch>
    <LocalizedStrings>
      <Resource idRef="E1CC861E-3FE9-4A58-82DF-4BD259EAB381">
        <Name default="true" langcode="en-us">Patient SSN Exact Match.</Name>
        <Description default="true" langcode="en-us">PDM Sensitive type for detecting Patient SSN.</Description>
      </Resource>
    </LocalizedStrings>
  </Rules>
</RulePackage>
 ```

## <a name="upload-personal-data"></a>Hochladen personenbezogener Daten
Nachdem Sie das Schema für personenbezogene Daten definiert haben, können Sie den **Upload personenbezogener Daten** auf der zweiten Registerkarte der Einstellungsseite für datenübereinstimmungen durchführen. Wenn Sie **"Hinzufügen"** auswählen, wählen Sie das persönliche Schema aus, das Sie im ersten Schritt definiert haben, und laden Sie dann die Datei hoch, die die personenbezogenen Daten enthält.

Sie können diese personenbezogenen Daten hochladen, indem Sie eine lokale Datei auswählen oder eine SAS-URL zu einem vorhandenen Microsoft Azure Storage Speicherort angeben, der Ihre persönliche Datendatei enthält.
Wenn Sie als ersten Schritt in diesem Prozess eine Datei vorbereitet haben, die dem erstellten Schema entspricht, können Sie diese Datei für den Upload verwenden.

## <a name="legal-disclaimer"></a>Haftungsausschluss

[Haftungsausschluss für Datenschutzverwaltung](privacy-management-disclaimer.md)
