---
title:  method
linktitle: get_HighQuality
second_title: Aspose.BarCode for C++ API Reference
description: ' method. HighQuality recognition quality preset. This preset is developed for low quality barcodes. Allows to detect highly damaged barcodes in C++.'
type: docs
weight: 300
url: /cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality recognition quality preset. This preset is developed for low quality barcodes. Allows to detect highly damaged barcodes.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## Remarks


This sample shows how to use HighQuality mode 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality recognition quality preset. 
## See Also

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
