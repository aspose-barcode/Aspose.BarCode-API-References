---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da enum nasıl kullanılır?"
type: docs
weight: 3800
url: /tr/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Hızlı | 0 | Yüksek kaliteli görüntüler için hızlı dekonvolüsyon yöntemlerini etkinleştirir. |
| Normal | 1 | Ortak görüntüler için normal dekonvolüsyon yöntemlerini etkinleştirir. |
| Yavaş | 2 | Düşük kaliteli görüntüler için yavaş dekonvolüsyon yöntemlerini etkinleştirir. |

## Açıklamalar


Görüntü bozulma seviyesini tanımlayan dekonvolüsyon (görüntü restorasyonu) modu. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş (konvolüsyonlu) görüntüyü geri getirebilen bir işlevdir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir.

Bu örnek, Deconvolution modunun nasıl kullanılacağını gösterir
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
