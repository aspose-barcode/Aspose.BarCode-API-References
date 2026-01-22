---
title:  enum
linktitle: InverseImageMode
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use  enum in C++.'
type: docs
weight: 3600
url: /cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Disables additional recognition of barcodes on inverse images for all barcode types except QR Code. |
| Disabled | 1 | Disables additional recognition of barcodes on inverse images. |
| Enabled | 2 | Enables additional recognition of barcodes on inverse images |

## Remarks


Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). 

This sample shows how to use InverseImage mode 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
