---
title: "Klass USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields-klass. Obligatoriska elementfält för kortet"
type: docs
weight: 820
url: /sv/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Obligatoriska element (fält) för kortet

```csharp
public class MandatoryFields
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, Stadsdel av kortägarens adress, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, Postnummerdel av kortägarens adress i USA och Kanada. Om den avslutande delen av postnumret i USA inte är känd, kommer nollor att användas för att fylla den avslutande siffrasekvensen upp till 9 siffror, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, Delstatdel av kortägarens adress, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, Gatuavsnitt av kortägarens adress, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, Land där DL/ID utfärdas. USA = USA, Kanada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Numret som tilldelas eller beräknas av utfärdande myndighet, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Numret måste unikt identifiera ett specifikt dokument som utfärdats till den kunden jämfört med andra som kan ha utfärdats tidigare. Detta nummer kan ha flera syften såsom dokumentdifferentiering, revisionsinformationsnummer och/eller lagerkontroll, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Dokumentets utgångsdatum, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Färg på kortägarens ögon. (ANSI D-20-koder). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Efternamn på kortägaren, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Höjd på kortinnehavaren. Inches (in): antal tum följt av \" in\" t.ex. 6'1'' = \"073 in\" Centimeters (cm): antal centimeter följt av \" cm\" t.ex. 181 centimeter = \"181 cm\", DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Mellannamn på kortinnehavaren. Vid flera mellannamn ska de separeras med ett kommatecken \",\". , DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Kön på kortinnehavaren. 1 = man, 2 = kvinna, 9 = ej specificerat, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS |

### Se även

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


