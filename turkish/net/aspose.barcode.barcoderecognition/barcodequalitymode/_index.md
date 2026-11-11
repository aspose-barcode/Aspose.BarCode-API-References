---
title: "Enum BarcodeQualityMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode enum. Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir."
type: docs
weight: 110
url: /tr/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir.

```csharp
public enum BarcodeQualityMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| High | `0` | Yüksek kalite barkodlar için tanıma yöntemlerini etkinleştirir. |
| Normal | `1` | Orta (Normal) kalite barkodlar için tanıma yöntemlerini etkinleştirir. |
| Low | `2` | Düşük kalite barkodlar için tanıma yöntemlerini etkinleştirir. |

## Örnekler

Bu örnek, BarcodeQuality modunun nasıl kullanılacağını gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


