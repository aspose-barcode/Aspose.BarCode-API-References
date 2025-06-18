---
title: QualitySettings.HighQuality
second_title: Aspose.BarCode for .NET API Reference
description: QualitySettings property. HighQuality recognition quality preset. This preset is developed for low quality barcodes. Allows to detect highly damaged barcodes
type: docs
weight: 20
url: /net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

HighQuality recognition quality preset. This preset is developed for low quality barcodes. Allows to detect highly damaged barcodes.

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

HighQuality recognition quality preset.

## Examples

This sample shows how to use HighQuality mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


