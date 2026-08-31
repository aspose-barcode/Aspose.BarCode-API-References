---
title: Enum InverseImageMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. Mode which enables or disables additional recognition of barcodes on images with inverted colors luminance
type: docs
weight: 270
url: /net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance).

```csharp
public enum InverseImageMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Disables additional recognition of barcodes on inverse images for all barcode types except QR Code. |
| Disabled | `1` | Disables additional recognition of barcodes on inverse images. |
| Enabled | `2` | Enables additional recognition of barcodes on inverse images |

## Examples

This sample shows how to use InverseImage mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


