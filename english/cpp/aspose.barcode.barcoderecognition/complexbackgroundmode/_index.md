---
title:  enum
linktitle: ComplexBackgroundMode
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use  enum in C++.'
type: docs
weight: 3400
url: /cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | At this time the same as Disabled. Disables additional recognition of color barcodes on color images. |
| Disabled | 1 | Disables additional recognition of color barcodes on color images. |
| Enabled | 2 | Enables additional recognition of color barcodes on color images. |

## Remarks


Mode which enables or disables additional recognition of color barcodes on color images. 

This sample shows how to use ComplexBackground mode 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
