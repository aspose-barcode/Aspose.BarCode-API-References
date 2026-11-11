---
title: "Klass USADriveIdCodetext"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext-klass. Klass för kodning och avkodning av text som är inbäddad i USA Driving License PDF417‑koden"
type: docs
weight: 810
url: /sv/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Klass för kodning och avkodning av text som är inbäddad i USA Driving License PDF417‑koden.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA versionsnummer 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Detta nummer identifierar entydigt den utfärdande jurisdiktionen och kan erhållas genom att kontakta ISO Issuing Authority(AAMVA). Det fullständiga 6-siffriga IIN bör kodas. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Jurisdiktionsspecifika fält |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Jurisdiktionsversionsnummer 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Obligatoriska element (fält) för kortet |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Nummer 00-99 av underfiler |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Valfria element (fält) på kortet |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Innehåller information om följande underfiler, typer, förskjutningar och längder. Viktigt: ange endast typ, förskjutning och längd kommer att sättas automatiskt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Returnerar streckkodstyp för USA DL (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Konstruera kodtext från USA DL-data |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Initiera USA DL-objekt från kodtext |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Sparar till XML |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Obligatoriska element (fält) för kortet |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Valfria element (fält) på kortet |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL-subfilens egenskaper, offset och längd sätts automatiskt. |

### Se även

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


