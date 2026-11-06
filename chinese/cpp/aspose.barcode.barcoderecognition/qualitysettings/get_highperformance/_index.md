---
title: "method"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。HighPerformance 识别质量预设。在此模式下，高质量条码在 C++ 中能够得到良好识别。"
type: docs
weight: 100
url: /zh/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


HighPerformance 识别质量预设。在此模式下，高质量条码能够得到良好识别。

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## 备注


此示例展示了如何使用 HighPerformance 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


HighPerformance 识别质量预设。
## 另见

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
