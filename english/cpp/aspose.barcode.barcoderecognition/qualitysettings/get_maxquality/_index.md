---
title:  method
linktitle: get_MaxQuality
second_title: Aspose.BarCode for C++ API Reference
description: ' method. MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes in C++.'
type: docs
weight: 400
url: /cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


MaxQuality recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## Remarks


This sample shows how to use MaxQuality mode 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


MaxQuality recognition quality preset. 
## See Also

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
