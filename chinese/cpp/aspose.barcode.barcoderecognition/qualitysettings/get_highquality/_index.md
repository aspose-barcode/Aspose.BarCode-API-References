---
title: "method"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。HighQuality 识别质量预设。此预设针对低质量条码而开发。允许在 C++ 中检测高度损坏的条码。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


HighQuality 识别质量预设。此预设针对低质量条码而开发。允许检测高度损坏的条码。

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## 备注


此示例展示了如何使用 HighQuality 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighQuality 识别质量预设。
## 另见

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
