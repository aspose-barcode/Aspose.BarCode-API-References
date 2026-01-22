---
title:  method
linktitle: get_HighPerformance
second_title: Aspose.BarCode for C++ API Reference
description: ' method. HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode in C++.'
type: docs
weight: 100
url: /cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## Remarks


This sample shows how to use HighPerformance mode 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance recognition quality preset. 
## See Also

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
