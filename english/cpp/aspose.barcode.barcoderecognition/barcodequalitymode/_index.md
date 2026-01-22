---
title:  enum
linktitle: BarcodeQualityMode
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use  enum in C++.'
type: docs
weight: 3300
url: /cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| High | 0 | Enables recognition methods for High quality barcodes. |
| Normal | 1 | Enables recognition methods for Common(Normal) quality barcodes. |
| Low | 2 | Enables recognition methods for Low quality barcodes. |

## Remarks


Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality requires more hard methods which slows the recognition. 

This sample shows how to use BarcodeQuality mode 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
