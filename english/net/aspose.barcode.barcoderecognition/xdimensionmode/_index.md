---
title: Enum XDimensionMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.XDimensionMode enum. Recognition mode which sets size from 1 to infinity of barcode minimal element matrix cell or bar
type: docs
weight: 370
url: /net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

```csharp
public enum XDimensionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Value of XDimension is detected by AI (SVM). At this time the same as Normal |
| Small | `1` | Detects barcodes with small XDimension in 1 pixel or more with quality from BarcodeQuality |
| Normal | `2` | Detects barcodes with classic XDimension in 2 pixels or more with quality from BarcodeQuality or high quality barcodes. |
| Large | `3` | Detects barcodes with large XDimension with quality from BarcodeQuality captured with high-resolution cameras. |
| UseMinimalXDimension | `4` | Detects barcodes from size set in MinimalXDimension with quality from BarcodeQuality |

## Examples

This sample shows how to use XDimension mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


