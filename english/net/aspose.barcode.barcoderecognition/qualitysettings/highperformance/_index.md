---
title: QualitySettings.HighPerformance
second_title: Aspose.BarCode for .NET API Reference
description: QualitySettings property. HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode
type: docs
weight: 10
url: /net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode.

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

HighPerformance recognition quality preset.

## Examples

This sample shows how to use HighPerformance mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


