---
title:  enum
linktitle: XDimensionMode
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use  enum in C++.'
type: docs
weight: 3700
url: /cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Value of XDimension is detected by AI (SVM). At this time the same as Normal |
| Small | 1 | Detects barcodes with small XDimension in 1 pixel or more with quality from BarcodeQuality |
| Normal | 2 | Detects barcodes with classic XDimension in 2 pixels or more with quality from BarcodeQuality or high quality barcodes. |
| Large | 3 | Detects barcodes with large XDimension with quality from BarcodeQuality captured with high-resolution cameras. |
| UseMinimalXDimension | 4 | Detects barcodes from size set in MinimalXDimension with quality from BarcodeQuality |

## Remarks


Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

This sample shows how to use XDimension mode 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
