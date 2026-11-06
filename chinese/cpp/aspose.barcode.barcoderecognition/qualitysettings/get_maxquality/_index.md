---
title: "method"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。MaxQuality 识别质量预设。此预设旨在识别所有可能的条码，甚至是错误的条码，在 C++ 中。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


MaxQuality 识别质量预设。此预设旨在识别所有可能的条形码，即使是错误的条形码。

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## 备注


此示例展示了如何使用 MaxQuality 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


MaxQuality 识别质量预设。
## 另见

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
