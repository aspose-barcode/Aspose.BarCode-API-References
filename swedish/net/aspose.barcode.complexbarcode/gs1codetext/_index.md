---
title: "Klass GS1Codetext"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext-klass. Representerar GS1-kodtext för kodning och avkodning som en ordnad sekvens av Application Identifier‑element. Källordning och upprepade Application Identifiers bevaras. Den hakparentes‑representationen har formatet AIvalueAIvalue. Ett bokstavligt öppningsparentes '(' i ett värde måste skrivas som '\\\\(' ; detta är den enda stödda escape‑sekvensen. Ett avslutningsparentes ')' i ett värde kräver ingen escape."
type: docs
weight: 530
url: /sv/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Representerar GS1-kodtext för kodning och avkodning som en ordnad sekvens av Application Identifier‑element. Källordning och upprepade Application Identifiers bevaras. Den hakparentes‑representationen har formatet (AI)value(AI)value. Ett bokstavligt öppningsparentes '(' i ett värde måste skrivas som '\\(' ; detta är den enda stödda escape‑sekvensen. Ett avslutningsparentes ')' i ett värde kräver ingen escape.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Hämtar eller anger streckkodstypen som används för att koda denna GS1-kodtext. Stödda typer är GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR och GS1 DataBar-typer. Standardvärdet är GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Hämtar antalet Application Identifier-element. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Hämtar en kopia av alla element i källordning. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Hämtar ett element efter dess position i den ordnade sekvensen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Tolkar en hakparentes‑GS1‑elementsträng i formatet (AI)value(AI)value. Ett bokstavligt '(' i ett värde måste skrivas som '\\(' ; ingen annan escape‑sekvens stöds, och ')' kräver ingen escape. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Lägger till ett validerat Application Identifier-element. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Hämtar alla värden för ett Application Identifier i källordning. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Hämtar streckkodstypen som används för att koda denna GS1-kodtext. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Skapar den hakparentes‑GS1‑kodtexten i formatet (AI)value(AI)value. Bokstavliga öppningsparenteser i värden escapas som '\\('. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Hämtar det första värdet för ett Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Initierar detta objekt från hakparentes‑GS1‑kodtext i formatet (AI)value(AI)value. Befintliga element ersätts först efter att den angivna kodtexten har tolkats framgångsrikt. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Returnerar den hakparentes‑GS1‑representationen i formatet (AI)value(AI)value. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Försöker tolka en hakparentes‑GS1‑elementsträng i formatet (AI)value(AI)value och returnerar strukturerade valideringsfel. Ett bokstavligt '(' i ett värde måste skrivas som '\\(' ; ingen annan escape‑sekvens stöds, och ')' kräver ingen escape. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Validerar en hakparentes‑GS1‑elementsträng i formatet (AI)value(AI)value utan att skapa ett objekt. Ett bokstavligt '(' i ett värde måste skrivas som '\\(' ; ingen annan escape‑sekvens stöds, och ')' kräver ingen escape. |

### Se även

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


