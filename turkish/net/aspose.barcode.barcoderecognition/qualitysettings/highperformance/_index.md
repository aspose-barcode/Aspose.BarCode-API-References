---
title: "QualitySettings.HighPerformance"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "QualitySettings özelliği. HighPerformance tanıma kalite ön ayarı. Yüksek kaliteli barkodlar bu modda iyi tanınır."
type: docs
weight: 10
url: /tr/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

HighPerformance tanıma kalite ön ayarı. Bu modda yüksek kaliteli barkodlar iyi tanınır.

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

HighPerformance tanıma kalite ön ayarı.

## Örnekler

Bu örnek, HighPerformance modunun nasıl kullanılacağını gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


