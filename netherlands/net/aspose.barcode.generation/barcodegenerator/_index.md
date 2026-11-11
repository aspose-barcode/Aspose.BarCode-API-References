---
title: "Klasse BarcodeGenerator"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.BarcodeGenerator klasse. BarcodeGenerator voor back‑end barcode‑afbeeldingen generatie"
type: docs
weight: 1000
url: /nl/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator voor het genereren van backend‑barcode‑afbeeldingen.

ondersteunde symbologieën: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | Maakt een instantie van BarcodeGenerator aan. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | Maakt een instantie van BarcodeGenerator aan. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Type barcode‑symbologie. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Te coderen tekst. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Generatieparameters. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Importeert BarCode‑eigenschappen van de opgegeven xml‑stream en maakt een BarcodeGenerator‑instantie. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Importeert BarCode‑eigenschappen van het opgegeven xml‑bestand en maakt een BarcodeGenerator‑instantie. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | Tekent barcode‑afbeelding op een WPF‑canvas. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | Exporteert BarCode‑eigenschappen naar de opgegeven xml‑stream. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | Exporteert BarCode‑eigenschappen naar het opgegeven xml‑bestand. |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Genereer de barcode‑afbeelding met de huidige instellingen. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Sla barcode‑afbeelding op naar een specifiek bestand. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Sla barcode‑afbeelding op naar een stream in een specifiek formaat. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Sla barcode‑afbeelding op naar een specifiek bestand in een specifiek formaat. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | Stel codetext in als een reeks bytes. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | Encodeert de Unicode **codeText** naar een byte‑reeks met behulp van de opgegeven **encoding**. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt, voegt de functie automatisch een [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) toe. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | Encodeert de Unicode **codeText** naar een byte‑reeks met behulp van de opgegeven **encoding**. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt en **insertBOM** is ingesteld op `true`, voegt de functie een [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) toe. |

## Voorbeelden

Dit voorbeeld laat zien hoe je een barcode‑afbeelding maakt en opslaat.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


