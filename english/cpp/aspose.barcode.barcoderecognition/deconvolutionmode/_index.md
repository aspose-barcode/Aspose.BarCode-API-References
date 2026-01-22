---
title:  enum
linktitle: DeconvolutionMode
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use  enum in C++.'
type: docs
weight: 3500
url: /cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Fast | 0 | Enables fast deconvolution methods for high quality images. |
| Normal | 1 | Enables normal deconvolution methods for common images. |
| Slow | 2 | Enables slow deconvolution methods for low quality images. |

## Remarks


Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function which can restore image degraded (convoluted) by any natural function like blur, during obtaining image by camera. Because we cannot detect image function which corrupt the image, we have to check most well know functions like sharp or mathematical morphology. 

This sample shows how to use Deconvolution mode 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
