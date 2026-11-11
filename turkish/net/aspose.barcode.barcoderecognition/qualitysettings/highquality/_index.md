---
title: "QualitySettings.HighQuality"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "QualitySettings özelliği. HighQuality tanıma kalitesi ön ayarı. Bu ön ayar düşük kaliteli barkodlar için geliştirilmiştir. Çok hasar görmüş barkodların tespit edilmesini sağlar."
type: docs
weight: 20
url: /tr/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

HighQuality tanıma kalite ön ayarı. Bu ön ayar düşük kaliteli barkodlar için geliştirilmiştir. Aşırı hasar görmüş barkodların tespit edilmesini sağlar.

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

HighQuality tanıma kalitesi ön ayarı.

## Örnekler

Bu örnek, HighQuality modunun nasıl kullanılacağını gösterir

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


