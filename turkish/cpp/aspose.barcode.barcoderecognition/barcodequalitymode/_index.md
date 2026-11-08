---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da enum nasıl kullanılır?"
type: docs
weight: 3600
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Yüksek | 0 | Yüksek kalite barkodlar için tanıma yöntemlerini etkinleştirir. |
| Normal | 1 | Ortak (Normal) kalite barkodlar için tanıma yöntemlerini etkinleştirir. |
| Düşük | 2 | Düşük kalite barkodlar için tanıma yöntemlerini etkinleştirir. |

## Açıklamalar


Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir.

Bu örnek, BarcodeQuality modunun nasıl kullanılacağını gösterir
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
