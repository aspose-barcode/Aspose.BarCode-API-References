---
title: "QualitySettings.NormalQuality"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "QualitySettings özelliği. NormalQuality tanıma kalitesi ön ayarı. Çoğu barkod için uygundur"
type: docs
weight: 40
url: /tr/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

NormalQuality tanıma kalite ön ayarı. Çoğu barkod için uygundur

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

NormalQuality tanıma kalitesi ön ayarı.

## Örnekler

Bu örnek, NormalQuality modunun nasıl kullanılacağını gösterir

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


