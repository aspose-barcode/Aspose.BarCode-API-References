---
title: "Klasse USADriveIdCodetext"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext klasse. Klasse voor het coderen en decoderen van de tekst die is ingebed in de USA Driving License PDF417-code."
type: docs
weight: 810
url: /nl/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Klasse voor het coderen en decoderen van de in de USA Driving License PDF417-code ingebedde tekst.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA-versienummer 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Dit nummer identificeert de uitgevende jurisdictie uniek en kan worden verkregen door contact op te nemen met de ISO-uitgevende autoriteit (AAMVA). Het volledige 6-cijferige IIN moet worden gecodeerd. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Jurisdictiespecifieke velden |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Jurisdictieversienummer 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Verplichte elementen (velden) van de kaart |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Aantal subbestanden 00-99 |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Optionele elementen (velden) van de kaart |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Bevat informatie over de volgende subbestanden, types, offsets en lengtes. Belangrijk: stel alleen type in, offset en lengte worden automatisch ingesteld. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Retourneert barcode-type van USA DL (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Construeer codetekst vanuit USA DL-gegevens |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Initialiseer USA DL-object vanuit codetekst |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Slaat op in XML |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Verplichte elementen (velden) van de kaart |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Optionele elementen (velden) van de kaart |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL subfile-eigenschappen, offset en lengte worden automatisch ingesteld. |

### Zie ook

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


