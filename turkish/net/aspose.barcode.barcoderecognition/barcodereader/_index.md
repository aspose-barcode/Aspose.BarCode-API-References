---
title: BarCodeReader
second_title: Aspose.BarCode for .NET API Referansı
description: BarCodeReader bir veya birkaç barkod içerebilen bir görüntüyü kapsüller ardından barkodları algılamak için ReadBarCodes işlemini gerçekleştirebilir.
type: docs
weight: 60
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader, bir veya birkaç barkod içerebilen bir görüntüyü kapsüller, ardından barkodları algılamak için ReadBarCodes işlemini gerçekleştirebilir.

```csharp
public class BarCodeReader : Component
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) varsayılan değerlere sahip sınıf. ReadBarCodes() yöntemini çağırmadan önce görüntünün (SetBitmapImage()) ayarlanmasını gerektirir. |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) bir görüntüden sınıf. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_11)(string) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) dosyadan sınıf. |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Yeni bir örneğini başlatır[`BarCodeReader`](../barcodereader) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | Ana Barkod kod çözme parametreleri. Tanınan veriler üzerinde etkili olan parametreleri içerir. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | Tanınır[`BarCodeResult`](../barcoderesult)s dizisi |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | Tanınan barkod sayısını alır |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i yerleşik ön ayarlarla hızlı bir şekilde ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxBarCodes veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | Tanıma işleminin zaman aşımını milisaniye cinsinden alır veya ayarlar. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | İşlemci çekirdeklerini kullanma ayarlarını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | Belirtilen xml akışından BarCode özelliklerini içe aktarır ve bunları geçerli BarCodeReader örneğine uygular. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | Belirtilen xml dosyasından BarCode özelliklerini içe aktarır ve bunları geçerli BarCodeReader örneğine uygular. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | İşlev, diğer iş parçacığından geçerli tanıma oturumunun sonlandırılmasını istiyor. Abort, engellenemez bir yöntemdir ve çağrıdan hemen sonra kontrolü döndürür. Tanıma işlemi çok uzun olduğunda yöntem kullanılmalıdır. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | BarCode özelliklerini belirtilen xml akışına aktarır |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | BarCode özelliklerini belirtilen xml dosyasına verir |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | Okuma sayısı[`BarCodeResult`](../barcoderesult) görüntüden s. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | Tanıma için bitmap görüntüsünü ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | Tanıma için görüntü akışını ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | Görüntü dosyasını tanıma için ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | Tanıma için bitmap görüntüsünü ve alanını ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | Tanıma için bitmap görüntüsünü ve alanları ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | Tanıma için kod çözme türünü ayarlar. ReadBarCodes() yönteminden önce çağrılmalıdır. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | Kümeler[`SingleDecodeType`](../singledecodetype) tanıma için dizi yazın. ReadBarCodes() yönteminden önce çağrılmalıdır. |

### Örnekler

Bu örnek, Code39 ve Code128 barkodlarının nasıl algılanacağını gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Ayrıca bakınız

* ad alanı [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
