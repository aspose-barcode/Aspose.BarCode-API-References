---
title: "Aspose::BarCode::Generation::BarcodeGenerator klass"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::BarcodeGenerator klass. BarcodeGenerator för backend-generering av streckkodsbilder i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Skapar en instans av [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Skapar en instans av [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Rensa upp eventuella resurser som används. |
| [ExportToXml](./exporttoxml/)(System::String) | Exporterar [BarCode](../../aspose.barcode/) egenskaper till den angivna xml-filen |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exporterar [BarCode](../../aspose.barcode/) egenskaper till den angivna xml-strömmen |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Generera streckkodsbilden med de aktuella inställningarna. |
| [get_BarcodeType](./get_barcodetype/)() | Streckkodssymboltyp. |
| [get_CodeText](./get_codetext/)() | Text som ska kodas. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) parametrar. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importerar [BarCode](../../aspose.barcode/) egenskaper från den angivna xml-filen och skapar en [BarcodeGenerator](./) instans. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importerar [BarCode](../../aspose.barcode/) egenskaper från den angivna xml-strömmen och skapar en [BarcodeGenerator](./) instans. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Spara streckkodsbild till ström i specifikt format. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Spara streckkodsbild till en specifik fil i specifikt format. |
| [Save](./save/)(System::String) | Spara streckkodsbild till en specifik fil. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Streckkodssymboltyp. |
| [set_CodeText](./set_codetext/)(System::String) | Text som ska kodas. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Ange kodtext som en sekvens av byte. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Anmärkningar


stödda symbologier: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

Detta exempel visar hur man skapar och sparar en streckkodsbild.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
