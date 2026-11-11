---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "QualitySettings properti. Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua kode batang yang mungkin bahkan kode batang yang tidak tepat"
type: docs
weight: 30
url: /id/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

Preset kualitas pengenalan MaxQuality. Preset ini dikembangkan untuk mengenali semua barcode yang mungkin, bahkan barcode yang tidak tepat.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

Preset kualitas pengenalan MaxQuality.

## Contoh

Contoh ini menunjukkan cara menggunakan mode MaxQuality

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Lihat Juga

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


