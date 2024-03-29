---
title: BarcodeGenerator
second_title: Aspose.BarCode voor .NET API-referentie
description: BarcodeGenerator voor het genereren van backendbarcodeafbeeldingen.
type: docs
weight: 700
url: /nl/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator voor het genereren van backend-barcodeafbeeldingen.

supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14 , SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR-code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | Maakt een instantie van BarcodeGenerator. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | Maakt een instantie van BarcodeGenerator. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Type streepjescodesymboliek. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Te coderen tekst. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Generatieparameters. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Importeert BarCode-eigenschappen uit de opgegeven xml-stream en maakt BarcodeGenerator-instantie. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Importeert BarCode-eigenschappen uit het opgegeven xml-bestand en maakt BarcodeGenerator-instantie. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | Tekent streepjescodeafbeelding op WPF-canvas. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | Exporteert streepjescode-eigenschappen naar de gespecificeerde xml-stream |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | Exporteert streepjescode-eigenschappen naar het opgegeven xml-bestand |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Genereer de barcode-afbeelding onder de huidige instellingen. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Bewaar streepjescode-afbeelding in een specifiek bestand. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Bewaar streepjescodeafbeelding om te streamen in specifiek formaat. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Bewaar streepjescode-afbeelding in een specifiek bestand in een specifiek formaat. |

### Voorbeelden

Dit voorbeeld laat zien hoe u een streepjescodeafbeelding maakt en opslaat.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### Zie ook

* naamruimte [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
