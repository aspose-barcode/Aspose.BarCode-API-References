---
title: "Aspose::BarCode::Generation::BarcodeGenerator klasse"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::BarcodeGenerator klasse. BarcodeGenerator voor backend barcode‑afbeeldingen generatie in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Maakt een instantie van [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Maakt een instantie van [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Ruim eventuele gebruikte bronnen op. |
| [ExportToXml](./exporttoxml/)(System::String) | Exporteert [BarCode](../../aspose.barcode/) eigenschappen naar het opgegeven xml‑bestand |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exporteert [BarCode](../../aspose.barcode/) eigenschappen naar de opgegeven xml‑stream |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Genereer de barcode‑afbeelding met de huidige instellingen. |
| [get_BarcodeType](./get_barcodetype/)() | Barcode-symbologie type. |
| [get_CodeText](./get_codetext/)() | Te coderen tekst. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) parameters. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importeert [BarCode](../../aspose.barcode/) eigenschappen van het opgegeven xml-bestand en maakt een [BarcodeGenerator](./) instantie aan. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importeert [BarCode](../../aspose.barcode/) eigenschappen van de opgegeven xml-stream en maakt een [BarcodeGenerator](./) instantie aan. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Sla de barcode-afbeelding op naar een stream in een specifiek formaat. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Sla de barcode-afbeelding op naar een specifiek bestand in een specifiek formaat. |
| [Save](./save/)(System::String) | Sla de barcode-afbeelding op naar een specifiek bestand. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Barcode-symbologie type. |
| [set_CodeText](./set_codetext/)(System::String) | Te coderen tekst. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Stel codetext in als een reeks bytes. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Opmerkingen


ondersteunde symbologieën: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

Dit voorbeeld toont hoe een barcode-afbeelding te maken en op te slaan.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
