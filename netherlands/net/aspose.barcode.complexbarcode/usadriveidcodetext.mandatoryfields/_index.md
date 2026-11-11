---
title: "Klasse USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields klasse. Verplichte elementen en velden van de kaart"
type: docs
weight: 820
url: /nl/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Verplichte elementen (velden) van de kaart

```csharp
public class MandatoryFields
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, Stedelijk gedeelte van het adres van de kaarthouder, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, Postcodegedeelte van het adres van de kaarthouder in de VS en Canada. Als het achterste gedeelte van de postcode in de VS niet bekend is, worden nullen gebruikt om het achterste cijferreeks tot 9 cijfers aan te vullen, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, Staatgedeelte van het adres van de kaarthouder, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, Straatgedeelte van het adres van de kaarthouder, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, Land waarin DL/ID wordt uitgegeven. VS = USA, Canada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Het nummer dat is toegewezen of berekend door de uitgevende autoriteit, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Datum waarop het document is uitgegeven, MMDDCCYY voor VS, CCYYMMDD voor Canada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Nummer moet een specifiek document dat aan die klant is uitgegeven uniek identificeren ten opzichte van andere die in het verleden zijn uitgegeven. Dit nummer kan meerdere doeleinden dienen, zoals documentdiscriminatie, auditinformatie‑nummer en/of voorraadbeheer, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Jurisdictiespecifieke goedkeuringcodes, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Documentvervaldatum, MMDDCCYY voor VS, CCYYMMDD voor Canada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Kleur van de ogen van de kaarthouder. (ANSI D-20 codes). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Achternaam van de kaarthouder, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of afgekapt (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Voornaam van de kaarthouder, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of afgekapt (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Lengte van de kaarthouder. Inches (in): aantal inches gevolgd door " in", bijv. 6'1'' = "073 in" Centimeters (cm): aantal centimeters gevolgd door " cm", bijv. 181 centimeters = "181 cm", DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Datum waarop het document is uitgegeven, MMDDCCYY voor VS, CCYYMMDD voor Canada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Middelste naam (namen) van de kaarthouder. In het geval van meerdere middelste namen moeten ze gescheiden worden door een komma ","., DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of afgekapt (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Jurisdictiespecifieke restrictiecodes, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Geslacht van de kaarthouder. 1 = man, 2 = vrouw, 9 = niet gespecificeerd, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Jurisdictiespecifieke voertuigklasse / groepscode, DL, V6ANS |

### Zie ook

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


