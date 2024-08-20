---
title: Enum ComplexBackgroundMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode enum. Mode which enables or disables additional recognition of color barcodes on color images
type: docs
weight: 200
url: /net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

Mode which enables or disables additional recognition of color barcodes on color images.

```csharp
public enum ComplexBackgroundMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | At this time the same as Disabled. Disables additional recognition of color barcodes on color images. |
| Disabled | `1` | Disables additional recognition of color barcodes on color images. |
| Enabled | `2` | Enables additional recognition of color barcodes on color images. |

## Examples

This sample shows how to use ComplexBackground mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


