---
title: "Aspose::BarCode::Generation::BarcodeGenerator sınıfı"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::BarcodeGenerator sınıfı. C++'da arka uç barkod görüntüleri oluşturmak için BarcodeGenerator."
type: docs
weight: 400
url: /tr/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Bir [BarcodeGenerator](./) örneği oluşturur. |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Bir [BarcodeGenerator](./) örneği oluşturur. |
| [Dispose](./dispose/)() override | Kullanılan tüm kaynakları temizle. |
| [ExportToXml](./exporttoxml/)(System::String) | [BarCode](../../aspose.barcode/) özelliklerini belirtilen xml dosyasına dışa aktarır |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | [BarCode](../../aspose.barcode/) özelliklerini belirtilen xml akışına dışa aktarır |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Mevcut ayarlar altında barkod görüntüsünü oluştur. |
| [get_BarcodeType](./get_barcodetype/)() | Barkod semboloji türü. |
| [get_CodeText](./get_codetext/)() | Kodlanacak metin. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) parametreleri. |
| static [ImportFromXml](./importfromxml/)(System::String) | Belirtilen xml dosyasından [BarCode](../../aspose.barcode/) özelliklerini içe aktarır ve bir [BarcodeGenerator](./) örneği oluşturur. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Belirtilen xml akışından [BarCode](../../aspose.barcode/) özelliklerini içe aktarır ve bir [BarcodeGenerator](./) örneği oluşturur. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Barkod görüntüsünü belirli formatta akışa kaydet. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Barkod görüntüsünü belirli formatta belirli bir dosyaya kaydet. |
| [Save](./save/)(System::String) | Barkod görüntüsünü belirli bir dosyaya kaydet. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Barkod semboloji türü. |
| [set_CodeText](./set_codetext/)(System::String) | Kodlanacak metin. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Kod metnini bayt dizisi olarak ayarla. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Açıklamalar


desteklenen sembolojiler: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

Bu örnek, bir barkod görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
