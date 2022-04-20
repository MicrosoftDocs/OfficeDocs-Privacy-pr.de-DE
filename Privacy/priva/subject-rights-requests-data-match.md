---
title: Datenabgleich für Anträge betroffener Personen
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
description: Erfahren Sie, wie Sie zusätzliche Informationen zu Ihren betroffenen Personen in Microsoft Priva hochladen.
ms.openlocfilehash: 76bd16f99a4a8ff9733c37a5787113e96c76c31c
ms.sourcegitcommit: 09ecdaded9a9f8f79587f2acb978dc53b83e5c01
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/19/2022
ms.locfileid: "64930581"
---
# <a name="data-matching-for-subject-rights-requests"></a>Datenabgleich für Anträge betroffener Personen

Mit dem Datenabgleich können Organisationen Microsoft Priva ermöglichen, betroffene Personen basierend auf genau angegebenen Datenwerten zu identifizieren. Dies kann dazu beitragen, die Genauigkeit der Suche nach Inhalten betroffener Personen zu erhöhen, die diesen Datenwerten sowohl für Ihr internes Personal als auch für externe Benutzer, mit denen Sie interagieren, entsprechen. Es vereinfacht auch die Notwendigkeit, Felder manuell während der Erstellung von Anträgen auf Anträge betroffener Personen anzugeben, und bietet Kontext innerhalb von Anfragen zu Rechten betroffener Personen sowie für die Kachel "Übersicht", die Ihre Elemente mit den meisten Inhalten der betroffenen Person anzeigt. Weitere Informationen zu dieser Ansicht finden Sie [unter "Suchen und Visualisieren personenbezogener Daten in Priva](priva-data-profile.md#items-with-the-most-data-subject-content)".

Um das Datenabgleichsfeature verwenden zu können, müssen Sie Mitglied der Rollengruppe "Datenschutzverwaltung" sein. Wählen Sie in Priva im [Microsoft Purview Compliance-Portal](https://compliance.microsoft.com/) **Einstellungen** in der oberen Navigationsleiste und dann **den Datenabgleich** aus. Von hier aus müssen Sie das Schema für personenbezogene Daten definieren und einen Upload personenbezogener Daten bereitstellen, wie unten dargestellt. Beachten Sie, dass Sie Elemente hinzufügen und Elemente löschen können, die Sie über die Benutzeroberfläche hinzufügen. Derzeit können Sie jedoch kein element an Ort und Stelle über die Benutzeroberfläche ändern.

## <a name="prepare-for-data-import"></a>Vorbereiten des Datenimports

Bevor Sie das Schema definieren oder Daten hochladen, müssen Sie die Quelle der Daten der betroffenen Person identifizieren. Das erforderliche Dateiformat ist .csv, das von einer Anwendung wie Microsoft Excel gelesen werden kann. Strukturieren Sie diesen Export so, dass die Spaltenüberschriften in der ersten Zeile angezeigt werden. Diese Kopfzeilen sollten die Namen der Attribute für Ihr Schema für personenbezogene Daten enthalten. Überprüfen Sie das Format der Daten in den einzelnen Feldern. Wenn eine der Daten Kommas enthält, umgeben Sie diese Werte mit doppelten Anführungszeichen, um sicherzustellen, dass sie nicht in separate Felder analysiert werden.

## <a name="define-the-personal-data-schema"></a>Definieren des Schemas für personenbezogene Daten

Das Schema für personenbezogene Daten beschreibt die Attribute für Ihre betroffenen Personen. Hochladen dieses Schema auf der ersten Registerkarte des Einstellungsbereichs für den Datenabgleich. Zu den erforderlichen Dateien gehören eine **XML-Datei für das Schema personenbezogener Daten** und eine XML-Datei des **Regelpakets** .

### <a name="personal-data-schema-xml"></a>XML des Schemas für personenbezogene Daten

Die Schemadatei für personenbezogene Daten ist eine XML-Datei, die definiert, welche Spaltennamen erwartet werden.

- Nennen Sie diese Schemadatei *pdm.xml*.
- Definieren Sie jeden Spaltennamen mithilfe des Feldnamen-Tags, wie im folgenden Beispiel dargestellt.
- Verwenden Sie suchbar = "true" für Felder, die durchsuchbar sein sollen, bis zu maximal fünf Felder. Mindestens einer Ihrer Feldnamen muss durchsuchbar sein. Beispielsyntax: `\<Field name="" searchable=""/>`.
- Das Schema für personenbezogene Daten weist einen DataStore-Tagabschnitt auf. Vier obligatorische Felder müssen Ihren Feldnamen zugeordnet werden: primaryKeyField, upnField, firstNameField, lastNameField.

Als Beispiel definiert die folgende XML-Datei ein Beispielschema mit fünf Feldern, die als durchsuchbar angegeben sind: PatientID, MRN, SSN, Telefon und DOB. Das primaryKeyField ist PatientID zugeordnet, upnField ist MRN zugeordnet, firstNameField ist FirstName zugeordnet, und lastNameField ist Nachname zugeordnet.

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

### <a name="rule-package-xml"></a>Xml des Regelpakets

Achten Sie beim Einrichten des Regelpakets darauf, dass Sie korrekt auf die oben erstellte Schemadatei für personenbezogene Daten verweisen: pdm.xml. Im folgenden Beispielregelpaket-XML müssen die folgenden Felder angepasst werden, um den vertraulichen Typ der Daten zu erstellen:

- **RulePack-ID** &  **PrivacyMatch-ID**: Verwenden Sie "New-GUID", um eine GUID zu generieren.
- **Datastore**: Dieses Feld gibt den nachzuschlagenden Nachschlagedatenspeicher für personenbezogene Daten an. Geben Sie den definierten DataStore-Namen eines konfigurierten Schemas für personenbezogene Daten an.
- **idMatch**: Dieses Feld verweist auf das primäre Element für die Übereinstimmung mit personenbezogenen Daten.
  - **Übereinstimmungen**: Gibt das Feld an, das bei der genauen Suche verwendet werden soll. Geben Sie einen durchsuchbaren Feldnamen aus dem Schema für personenbezogene Daten an.
  - **Klassifizierung**: Dieses Feld gibt die Übereinstimmung vertraulicher Typen an, die die Suche nach übereinstimmungen mit personenbezogenen Daten auslöst. Sie können den Namen oder die GUID eines vorhandenen integrierten oder benutzerdefinierten vertraulichen Informationstyps angeben. Um Leistungsprobleme zu vermeiden, verwenden Sie, wenn Sie einen benutzerdefinierten vertraulichen Informationstyp als Klassifizierungselement in der Übereinstimmung mit personenbezogenen Daten verwenden, keinen benutzerdefinierten vertraulichen Informationstyp, der einem großen Prozentsatz des Inhalts entspricht (z. B. "beliebige Zahl" oder "beliebiges fünfstelliges Wort"). Es wird empfohlen, unterstützende Schlüsselwörter hinzuzufügen oder Formatierungen in die Definition des benutzerdefinierten Vertraulich-Informationstyps für Klassifizierungen aufzunehmen.
- **Übereinstimmung**: Dieses Feld verweist auf zusätzliche Nachweise, die in der Nähe von idMatch gefunden wurden.
  - **Übereinstimmungen**: Geben Sie einen beliebigen Feldnamen im Schema für personenbezogene Daten für DataStore an.
- **Ressource**: In diesem Abschnitt werden der Name und die Beschreibung für den vertraulichen Typ in mehreren Gebietsschemas angegeben.
  - **idRef**: Bereitstellen der GUID für ExactMatch-ID.
  - **Name & Beschreibungen**: Anpassen nach Bedarf.

Im folgenden Beispiel für das Regelpaket-XML verweisen wir auf die pdm.xml Beispieldatei aus dem vorherigen Schritt, die das XML-Schema für personenbezogene Daten erstellt:

- **Datastore**: Der DataStore-Name verweist auf die Schemadatei, die wir zuvor erstellt haben: dataStore = "PatientRecords".
- **idMatch**: Der idMatch-Wert verweist auf ein durchsuchbares Feld, das in der zuvor erstellten pdm.xml Datei aufgeführt ist: idMatch matches = "SSN".
  - **Klassifizierung**: Der Klassifizierungswert verweist auf einen vorhandenen oder benutzerdefinierten vertraulichen Informationstyp: Klassifizierung = "U.S. Social Security Number (SSN)". (In diesem Fall wird der vorhandene vertrauliche Informationstyp "US-Sozialversicherungsnummer" verwendet.)

Erstellen Sie ein Regelpaket im XML-Format (mit Unicode-Codierung), wie im folgenden Beispielcode dargestellt. Sie können dieses Beispiel kopieren, ändern und verwenden.

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
Nachdem Sie das Schema für personenbezogene Daten definiert haben, können Sie den **Upload personenbezogener Daten** auf der zweiten Registerkarte der Seite mit den Einstellungen für den Datenabgleich durchführen. Wenn Sie **"Hinzufügen"** auswählen, wählen Sie das persönliche Schema aus, das Sie im ersten Schritt definiert haben, und laden Sie dann die Datei hoch, die die personenbezogenen Daten enthält.

Sie können diese personenbezogenen Daten hochladen, indem Sie eine lokale Datei auswählen oder eine SAS-URL für einen vorhandenen Microsoft Azure Storage Speicherort angeben, der Ihre persönliche Datendatei enthält.
Wenn Sie eine Datei als ersten Schritt in diesem Prozess vorbereitet haben, die dem erstellten Schema entspricht, können Sie diese Datei für den Upload verwenden.

## <a name="legal-disclaimer"></a>Rechtlicher Haftungsausschluss

[Microsoft Priva Rechtlicher Haftungsausschluss](priva-disclaimer.md)
