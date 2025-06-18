---
title: QualitySettings.NormalQuality
second_title: Aspose.BarCode for .NET API Reference
description: QualitySettings property. NormalQuality recognition quality preset. Suitable for the most of barcodes
type: docs
weight: 40
url: /net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

NormalQuality recognition quality preset. Suitable for the most of barcodes

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

NormalQuality recognition quality preset.

## Examples

This sample shows how to use NormalQuality mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


