---
title: "Klasse USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields Klasse. Pflichtfelder des Kartenfeldes"
type: docs
weight: 820
url: /de/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Pflichtfelder (Felder) der Karte

```csharp
public class MandatoryFields
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. Wenn der nachfolgende Teil der Postleitzahl in den USA nicht bekannt ist, werden Nullen verwendet, um den nachfolgenden Zahlenblock bis zu 9 Stellen aufzufüllen, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, Bundeslandanteil der Karteninhaberadresse, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, Land, in dem DL/ID ausgestellt wird. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Die Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die in der Vergangenheit ausgestellt wurden, unterscheiden. Diese Nummer kann mehrere Zwecke erfüllen, z. B. Dokumentenunterscheidung, Prüfungsinformationsnummer und/oder Bestandskontrolle, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Ablaufdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Augenfarbe des Karteninhabers. (ANSI D-20 Codes). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Familienname des Karteninhabers, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Vorname des Karteninhabers, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Größe des Karteninhabers. Zoll (in): Anzahl der Zoll gefolgt von " in", z. B. 6'1'' = "073 in" Zentimeter (cm): Anzahl der Zentimeter gefolgt von " cm", z. B. 181 Zentimeter = "181 cm", DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Zweitname(n) des Karteninhabers. Im Falle mehrerer Zweitnamen sollen sie durch ein Komma "," getrennt werden., DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, jurisdiktion-spezifische Beschränzungscodes, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Geschlecht des Karteninhabers. 1 = männlich, 2 = weiblich, 9 = nicht angegeben, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, jurisdiktion-spezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS |

### Siehe auch

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


