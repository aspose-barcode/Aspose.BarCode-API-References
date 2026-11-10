---
title: "枚举 DeconvolutionMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode 枚举。去卷积图像恢复模式，用于定义图像退化的程度。最初，去卷积是一种函数，可恢复因任何自然函数（如相机拍摄时的模糊）导致的卷积退化图像。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。"
type: docs
weight: 240
url: /zh/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

去卷积（图像恢复）模式，用于定义图像退化的程度。去卷积最初是一种能够恢复因自然函数（如模糊）在相机拍摄时导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。

```csharp
public enum DeconvolutionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Fast | `0` | 为高质量图像启用快速去卷积方法。 |
| Normal | `1` | 启用常规图像的普通去卷积方法。 |
| Slow | `2` | 启用低质量图像的慢速去卷积方法。 |

## 示例

此示例展示如何使用去卷积模式

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


