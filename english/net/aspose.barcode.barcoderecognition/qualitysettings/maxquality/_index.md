---
title: QualitySettings.MaxQuality
second_title: Aspose.BarCode for .NET API Reference
description: QualitySettings property. MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes even incorrect barcodes
type: docs
weight: 30
url: /net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality recognition quality preset.

## Examples

This sample shows how to use MaxQuality mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


