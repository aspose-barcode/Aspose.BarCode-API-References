---
title: "method"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。NormalQuality 识别质量预设。适用于大多数条码（C++）。"
type: docs
weight: 200
url: /zh/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


NormalQuality 识别质量预设。适用于大多数条形码。

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## 备注


此示例展示了如何使用 NormalQuality 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


NormalQuality 识别质量预设。
## 另见

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
