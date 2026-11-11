---
title: "Enum DeconvolutionMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Görüntü bozulma seviyesini tanımlayan dekonvolüsyon görüntü restorasyon modudur. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş görüntüyü geri yükleyebilen bir işlevdir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir."
type: docs
weight: 240
url: /tr/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Dekonvolüsyon (görüntü restorasyonu) modu, görüntü bozulma seviyesini tanımlar. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş (konvolüsyonlu) görüntüyü geri yükleyebilen bir işlevtir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir.

```csharp
public enum DeconvolutionMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Fast | `0` | Yüksek kaliteli görüntüler için hızlı dekonvolüsyon yöntemlerini etkinleştirir. |
| Normal | `1` | Ortak görüntüler için normal dekonvolüsyon yöntemlerini etkinleştirir. |
| Slow | `2` | Düşük kaliteli görüntüler için yavaş dekonvolüsyon yöntemlerini etkinleştirir. |

## Örnekler

Bu örnek, Deconvolution modunun nasıl kullanılacağını gösterir

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


