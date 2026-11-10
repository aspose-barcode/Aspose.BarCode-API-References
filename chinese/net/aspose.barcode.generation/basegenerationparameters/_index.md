---
title: "类 BaseGenerationParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.BaseGenerationParameters 类。条形码图像生成参数"
type: docs
weight: 1030
url: /zh/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

条形码图像生成参数。

```csharp
public class BaseGenerationParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | 指定不同类型的自动尺寸模式。默认值：AutoSizeMode.None。 |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | 条形码图像的背景颜色。默认值：Color.White。参见 Color。 |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | 获取包含所有条形码属性的 [`BarcodeParameters`](../barcodeparameters/)。 |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | 获取包含条形码边框所有配置属性的 [`BorderParameters`](../borderparameters/)。 |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | 条形码图像上方的标题。参见 [`CaptionParameters`](../captionparameters/)。 |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | 条形码图像下方的标题。参见 [`CaptionParameters`](../captionparameters/)。 |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | 图像参数。参见 [`ImageParameters`](../imageparameters/)。 |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | 条形码图像高度，当[`AutoSizeMode`](./autosizemode/)属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 时。 |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | 条形码图像宽度，当[`AutoSizeMode`](./autosizemode/)属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 时。 |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | 获取或设置条码图像的分辨率。两个维度使用同一数值。默认值：96 dpi。 |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | 条形码图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。默认值：0。 |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | 获取或设置一个值，指示是否使用抗锯齿模式来渲染图像 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


