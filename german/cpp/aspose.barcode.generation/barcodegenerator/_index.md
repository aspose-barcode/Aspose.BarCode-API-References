---
title: "Aspose::BarCode::Generation::BarcodeGenerator Klasse"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::BarcodeGenerator Klasse. BarcodeGenerator für die Backend-Barcode-Bilderzeugung in C++."
type: docs
weight: 400
url: /de/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Erstellt eine Instanz von [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Erstellt eine Instanz von [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Räume alle verwendeten Ressourcen auf. |
| [ExportToXml](./exporttoxml/)(System::String) | Exportiert die Eigenschaften von [BarCode](../../aspose.barcode/) in die angegebene XML-Datei |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exportiert die Eigenschaften von [BarCode](../../aspose.barcode/) in den angegebenen XML-Stream |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Erstelle das Barcode-Bild mit den aktuellen Einstellungen. |
| [get_BarcodeType](./get_barcodetype/)() | Barcode-Symbologie-Typ. |
| [get_CodeText](./get_codetext/)() | Zu codierender Text. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) Parameter. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importiert die Eigenschaften von [BarCode](../../aspose.barcode/) aus der angegebenen XML-Datei und erstellt eine Instanz von [BarcodeGenerator](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importiert die Eigenschaften von [BarCode](../../aspose.barcode/) aus dem angegebenen XML-Stream und erstellt eine Instanz von [BarcodeGenerator](./). |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Speichere das Barcode-Bild in einen Stream in einem bestimmten Format. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Speichere das Barcode-Bild in einer bestimmten Datei in einem bestimmten Format. |
| [Save](./save/)(System::String) | Speichere das Barcode-Bild in einer bestimmten Datei. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Barcode-Symbologie-Typ. |
| [set_CodeText](./set_codetext/)(System::String) | Zu codierender Text. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Setze den Codetext als Bytefolge. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Hinweise


unterstützte Symbologien: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet, EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR-Code ...

Dieses Beispiel zeigt, wie man ein Barcode-Bild erstellt und speichert.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
