---
title: "枚举"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用枚举。"
type: docs
weight: 3700
url: /zh/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | 此时与 Disabled 相同。禁用对彩色图像中彩色条形码的额外识别。 |
| 已禁用 | 1 | 禁用对彩色图像中彩色条形码的额外识别。 |
| 已启用 | 2 | 启用对彩色图像中彩色条形码的额外识别。 |

## 备注


此模式启用或禁用对彩色图像中彩色条码的额外识别。

此示例展示了如何使用 ComplexBackground 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
