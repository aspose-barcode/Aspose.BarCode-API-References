---
title: "BarCodeReader sınıfı"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeReader sınıfı. BarCodeReader, bir veya birkaç barkod içerebilecek bir görüntüyü kapsüller ve ardından barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir."
type: docs
weight: 70
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader, bir veya birkaç barkod içerebilecek bir görüntüyü kapsar ve ardından barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir.

```csharp
public class BarCodeReader : Component
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | `BarCodeReader` sınıfının yeni bir örneğini varsayılan değerlerle başlatır. ReadBarCodes() metodunu çağırmadan önce görüntüyü (SetBitmapImage()) ayarlamanız gerekir. |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | `BarCodeReader` sınıfının yeni bir örneğini bir görüntüden başlatır. |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | `BarCodeReader` sınıfının yeni bir örneğini bir parlaklık çerçevesinden başlatır. |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_18)(string) | `BarCodeReader` sınıfının yeni bir örneğini dosyadan başlatır. |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | `BarCodeReader` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | Tanıma için kullanılan barkod çözümleme türünü alır veya ayarlar. [`ReadBarCodes`](./readbarcodes/) çağrılmadan önce ayarlanmalıdır. |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | Ana BarCode kod çözme parametreleri. Tanınan veriler üzerinde etkisi olan parametreler içerir. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Tanımlanan [`BarCodeResult`](../barcoderesult/) dizisini alır |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Tanımlanan barkodların sayısını alır |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i gömülü ön ayarlar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ile hızlıca ayarlayabilir veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Tanıma işleminin zaman aşımını milisaniye cinsinden alır veya ayarlar. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | İşlemci çekirdeklerinin kullanım ayarlarını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Belirtilen xml akışından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Belirtilen xml dosyasından BarCode özelliklerini içe aktarır ve mevcut BarCodeReader örneğine uygular. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | Fonksiyon, başka bir iş parçacığından mevcut tanıma oturumunun sonlandırılmasını talep eder. Abort, engellenemeyen bir yöntemdir ve çağrıldıktan hemen sonra kontrolü geri verir. Bu yöntem, tanıma işlemi çok uzun sürdüğünde kullanılmalıdır. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | BarCode özelliklerini belirtilen xml akışına dışa aktarır |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | BarCode özelliklerini belirtilen xml dosyasına dışa aktarır |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Görüntüden [`BarCodeResult`](../barcoderesult/) öğelerini okur. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | Tanıma için bitmap görüntüsünü ayarlar. ReadBarCodes() metodundan önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | Tanıma için parlaklık çerçevesini ayarlar. [`ReadBarCodes`](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | Tanıma için görüntü akışını ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | Tanıma için görüntü dosyasını ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | Tanıma için bitmap görüntüsü ve alanı ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | Tanıma için bitmap görüntüsü ve alanları ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | Tanıma için parlaklık çerçevesi ve alanı ayarlar. [`ReadBarCodes`](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | Tanıma için parlaklık çerçevesi ve alanları ayarlar. [`ReadBarCodes`](./readbarcodes/) yönteminden önce çağrılmalıdır. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | Tanıma için [`SingleDecodeType`](../singledecodetype/) tip dizisini ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |

## Örnekler

Bu örnek, Code39 ve Code128 barkodlarını nasıl algılayacağınızı gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


