---
title: Enum DeconvolutionMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Deconvolution image restorations mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded convoluted by any natural function like blur during obtaining image by camera. Because we cannot detect image function which corrupt the image we have to check most well know functions like sharp or mathematical morphology
type: docs
weight: 240
url: /net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology.

```csharp
public enum DeconvolutionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Fast | `0` | Enables fast deconvolution methods for high quality images. |
| Normal | `1` | Enables normal deconvolution methods for common images. |
| Slow | `2` | Enables slow deconvolution methods for low quality images. |

## Examples

This sample shows how to use Deconvolution mode

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


