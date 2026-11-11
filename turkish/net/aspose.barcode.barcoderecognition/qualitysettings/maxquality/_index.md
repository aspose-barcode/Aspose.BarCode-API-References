---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "QualitySettings özelliği. MaxQuality tanıma kalitesi ön ayarı. Bu ön ayar, hatalı barkodlar dahil tüm olası barkodları tanımak için geliştirilmiştir"
type: docs
weight: 30
url: /tr/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality tanıma kalite ön ayarı. Bu ön ayar, hatalı barkodlar dahil olmak üzere tüm olası barkodları tanımak için geliştirilmiştir.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality tanıma kalitesi ön ayarı.

## Örnekler

Bu örnek, MaxQuality modunun nasıl kullanılacağını gösterir

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


