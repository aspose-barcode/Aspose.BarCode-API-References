---
title: Aspose::BarCode::Generation::BarcodeGenerator class
linktitle: BarcodeGenerator
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::BarcodeGenerator class. BarcodeGenerator for backend barcode images generation in C++.'
type: docs
weight: 400
url: /cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Creates an instance of [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Creates an instance of [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Clean up any resources being used. |
| [ExportToXml](./exporttoxml/)(System::String) | Exports [BarCode](../../aspose.barcode/) properties to the xml-file specified |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exports [BarCode](../../aspose.barcode/) properties to the xml-stream specified |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Generate the barcode image under current settings. |
| [get_BarcodeType](./get_barcodetype/)() | Barcode symbology type. |
| [get_CodeText](./get_codetext/)() | Text to be encoded. |
| [get_Parameters](./get_parameters/)() | [Generation](../) parameters. |
| static [ImportFromXml](./importfromxml/)(System::String) | Imports [BarCode](../../aspose.barcode/) properties from the xml-file specified and creates [BarcodeGenerator](./) instance. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Imports [BarCode](../../aspose.barcode/) properties from the xml-stream specified and creates [BarcodeGenerator](./) instance. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Save barcode image to stream in specific format. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Save barcode image to specific file in specific format. |
| [Save](./save/)(System::String) | Save barcode image to specific file. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Barcode symbology type. |
| [set_CodeText](./set_codetext/)(System::String) | Text to be encoded. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Set codetext as sequence of bytes. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Remarks


supported symbologies: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ... 

This sample shows how to create and save a barcode image. 
```cpp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
