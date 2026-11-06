---
title: "枚举"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用枚举。"
type: docs
weight: 3600
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| High | 0 | 启用针对高质量条码的识别方法。 |
| Normal | 1 | 启用针对普通（Normal）质量条码的识别方法。 |
| Low | 2 | 启用针对低质量条码的识别方法。 |

## 备注


此模式启用使用所选质量识别条码元素的方法。质量较低的条码元素需要更复杂的方法，从而减慢识别速度。

此示例展示如何使用 BarcodeQuality 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
