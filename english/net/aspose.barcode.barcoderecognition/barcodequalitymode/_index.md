---
title: Enum BarcodeQualityMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode enum. Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition
type: docs
weight: 110
url: /net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition.

```csharp
public enum BarcodeQualityMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| High | `0` | Enables recognition methods for High quality barcodes. |
| Normal | `1` | Enables recognition methods for Common(Normal) quality barcodes. |
| Low | `2` | Enables recognition methods for Low quality barcodes. |

## Examples

This sample shows how to use BarcodeQuality mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


