---
title: Class BarcodeGenerator
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.BarcodeGenerator class. BarcodeGenerator for backend barcode images generation
type: docs
weight: 920
url: /net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator for backend barcode images generation.

supported symbologies: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Constructors

| Name | Description |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | Creates an instance of BarcodeGenerator. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | Creates an instance of BarcodeGenerator. |

## Properties

| Name | Description |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Barcode symbology type. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Text to be encoded. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Generation parameters. |

## Methods

| Name | Description |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Imports BarCode properties from the xml-stream specified and creates BarcodeGenerator instance. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | Draws barcode image on WPF canvas. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | Exports BarCode properties to the xml-stream specified |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | Exports BarCode properties to the xml-file specified |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Generate the barcode image under current settings. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Save barcode image to specific file. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Save barcode image to stream in specific format. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Save barcode image to specific file in specific format. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | Set codetext as sequence of bytes. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | Encodes the Unicode **codeText** into a byte sequence using the specified **encoding**. UTF-8 is the most commonly used encoding. If the encoding supports it, the function automatically inserts a [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding). |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | Encodes the Unicode **codeText** into a byte sequence using the specified **encoding**. UTF-8 is the most commonly used encoding. If the encoding supports it and **insertBOM** is set to `true`, the function includes a [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding). |

## Examples

This sample shows how to create and save a barcode image.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


