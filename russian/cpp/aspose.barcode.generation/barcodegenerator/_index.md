---
title: "Aspose::BarCode::Generation::BarcodeGenerator класс"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::BarcodeGenerator класс. BarcodeGenerator для генерации изображений штрихкодов на стороне сервера в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Methods

| Method | Описание |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Создаёт экземпляр [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Создаёт экземпляр [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Освободить любые используемые ресурсы. |
| [ExportToXml](./exporttoxml/)(System::String) | Экспортирует свойства [BarCode](../../aspose.barcode/) в указанный XML‑файл |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Экспортирует свойства [BarCode](../../aspose.barcode/) в указанный XML‑поток |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Сгенерировать изображение штрихкода с текущими настройками. |
| [get_BarcodeType](./get_barcodetype/)() | Тип символьной системы штрих‑кода. |
| [get_CodeText](./get_codetext/)() | Текст для кодирования. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) параметры. |
| static [ImportFromXml](./importfromxml/)(System::String) | Импортирует свойства [BarCode](../../aspose.barcode/) из указанного XML‑файла и создает экземпляр [BarcodeGenerator](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Импортирует свойства [BarCode](../../aspose.barcode/) из указанного XML‑потока и создает экземпляр [BarcodeGenerator](./). |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Сохранить изображение штрих‑кода в поток в указанном формате. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Сохранить изображение штрих‑кода в указанный файл в указанном формате. |
| [Save](./save/)(System::String) | Сохранить изображение штрих‑кода в указанный файл. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Тип символьной системы штрих‑кода. |
| [set_CodeText](./set_codetext/)(System::String) | Текст для кодирования. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Установить codetext как последовательность байтов. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Примечания


поддерживаемые символьные системы: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

Этот пример показывает, как создать и сохранить изображение штрих‑кода.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
