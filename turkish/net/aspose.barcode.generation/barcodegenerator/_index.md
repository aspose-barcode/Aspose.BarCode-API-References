---
title: "Sınıf BarcodeGenerator"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.BarcodeGenerator sınıfı. Arka uç barkod görüntülerinin oluşturulması için BarcodeGenerator"
type: docs
weight: 1000
url: /tr/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

Arka uç barkod görüntüleri üretimi için BarcodeGenerator.

desteklenen sembolojiler: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | BarcodeGenerator sınıfının bir örneğini oluşturur. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | BarcodeGenerator sınıfının bir örneğini oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Barkod semboloji türü. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Kodlanacak metin. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Oluşturma parametreleri. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Belirtilen xml-akışından BarCode özelliklerini içe aktarır ve BarcodeGenerator örneği oluşturur. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Belirtilen xml-dosyasından BarCode özelliklerini içe aktarır ve BarcodeGenerator örneği oluşturur. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | WPF tuvalinde barkod görüntüsü çizer. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | BarCode özelliklerini belirtilen xml akışına dışa aktarır |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | BarCode özelliklerini belirtilen xml dosyasına dışa aktarır |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Mevcut ayarlar altında barkod görüntüsünü oluştur. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Barkod görüntüsünü belirli bir dosyaya kaydet. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Barkod görüntüsünü belirli bir formatta akışa kaydet. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Barkod görüntüsünü belirli bir formatta belirli bir dosyaya kaydet. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | codetext'i bayt dizisi olarak ayarla. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | Belirtilen **encoding** kullanılarak Unicode **codeText**'i bir bayt dizisine kodlar. UTF-8 en yaygın kullanılan kodlamadır. Kodlama bunu destekliyorsa, işlev otomatik olarak bir [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ekler. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | Belirtilen **encoding** kullanılarak Unicode **codeText**'i bir bayt dizisine kodlar. UTF-8 en yaygın kullanılan kodlamadır. Kodlama bunu destekliyor ve **insertBOM** `true` olarak ayarlanmışsa, işlev bir [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ekler. |

## Örnekler

Bu örnek, bir barkod görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


