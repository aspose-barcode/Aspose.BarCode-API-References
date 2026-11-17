---
title: "枚举"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用枚举。"
type: docs
weight: 3800
url: /zh/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 快速 | 0 | 为高质量图像启用快速去卷积方法。 |
| Normal | 1 | 为常规图像启用普通去卷积方法。 |
| 慢速 | 2 | 为低质量图像启用慢速去卷积方法。 |

## 备注


去卷积（图像恢复）模式，用于定义图像退化程度。去卷积本质上是一种能够恢复因自然函数（如模糊）在相机拍摄时导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。

此示例展示如何使用 Deconvolution 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
