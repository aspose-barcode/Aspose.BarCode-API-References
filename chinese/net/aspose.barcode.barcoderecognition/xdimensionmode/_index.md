---
title: "枚举 XDimensionMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode 枚举。识别模式，将条码最小元素矩阵单元或条的大小设置为 1 到无限。"
type: docs
weight: 400
url: /zh/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

识别模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限大）。

```csharp
public enum XDimensionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | XDimension 的值由 AI（SVM）检测。目前与 Normal 相同。 |
| Small | `1` | 检测 XDimension 为 1 像素或更大的小尺寸条码，质量来自 BarcodeQuality。 |
| Normal | `2` | 检测 XDimension 为 2 像素或更大的经典尺寸条码，质量来自 BarcodeQuality 或高质量条码。 |
| Large | `3` | 检测 XDimension 为大尺寸的条码，质量来自 BarcodeQuality，使用高分辨率相机捕获。 |
| UseMinimalXDimension | `4` | 检测尺寸设置在 MinimalXDimension 中的条码，质量来自 BarcodeQuality。 |

## 示例

此示例展示如何使用 XDimension 模式

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


