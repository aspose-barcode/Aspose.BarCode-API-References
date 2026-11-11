---
title: "Klass GS1DigitalLink"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink klass. Representerar GS1 Digital Link codetext för kodning och avkodning som en ordnad sekvens av Application Identifier-element. Källordning och upprepade Application Identifier-element bevaras. Den konstruerade kodtexten är en okomprimerad GS1 Digital Link-URI. Icke-GS1-frågeparametrar och URI-fragment ignoreras vid parsning."
type: docs
weight: 540
url: /sv/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Representerar GS1 Digital Link codetext för kodning och avkodning som en ordnad sekvens av Application Identifier-element. Källordning och upprepade Application Identifier-element bevaras. Den konstruerade kodtexten är en okomprimerad GS1 Digital Link-URI. Icke-GS1-frågeparametrar och URI-fragment ignoreras vid parsning.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Initierar en tom GS1 Digital Link med den angivna URI-stammen. Den primära nyckeln väljs automatiskt när exakt en primär-nyckelkandidat finns. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Initierar en tom GS1 Digital Link med den angivna URI-stammen och primärnyckeln. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Hämtar eller anger streckkodstypen som används för att koda denna GS1 Digital Link. Stödda typer är QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF och Code128. Standardvärdet är QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Hämtar antalet Application Identifier-element. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Hämtar en kopia av alla element i källordning. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Hämtar ett element efter dess position i den ordnade sekvensen. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Hämtar Application Identifier som används som Digital Link-primärnyckel. Null betyder att primärnyckeln väljs automatiskt när URI:n konstrueras. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Hämtar det absoluta URI-prefixet före GS1-primärnyckelns sökvägssegment. Stammen innehåller ingen frågesträng eller fragment. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Skapar en GS1 Digital Link genom att kopiera alla element från GS1 kodtext och välja den enda tillgängliga primärnyckeln. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Skapar en GS1 Digital Link genom att kopiera alla element från GS1 kodtext och använda den angivna primärnyckeln. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Analyserar en okomprimerad GS1 Digital Link-URI. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Lägger till ett validerat Application Identifier-element. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Hämtar alla värden för ett Application Identifier i källordning. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Hämtar streckkodstypen som används för att koda denna GS1 Digital Link. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Konstruerar den okomprimerade GS1 Digital Link-URI:n. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Hämtar det första värdet för ett Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Initierar detta objekt från en okomprimerad GS1 Digital Link-URI. Befintligt tillstånd ersätts först efter att den angivna URI:n har analyserats framgångsrikt. Den valda streckkodstypen bevaras. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Skapar en oberoende GS1-kodtext som innehåller de aktuella GS1-elementen. Information som endast är URI inkluderas inte. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Returnerar den okomprimerade GS1 Digital Link-URI:n. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Formaterar det aktuella objektets tillstånd som en okomprimerad GS1 Digital Link-URI. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Försöker att tolka en okomprimerad GS1 Digital Link-URI och returnerar strukturerade valideringsfel. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Validerar en okomprimerad GS1 Digital Link-URI utan att skapa ett objekt. |

### Se även

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


