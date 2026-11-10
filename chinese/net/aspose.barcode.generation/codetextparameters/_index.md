---
title: "类 CodetextParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.CodetextParameters 类。码文本参数"
type: docs
weight: 1160
url: /zh/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

代码文本参数。

```csharp
public class CodetextParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | 获取或设置代码文本的对齐方式。默认值：StringAlignment.Center。 |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | 指定显示的 CodeText 颜色。默认值：Color.Black。 |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | 指定显示的 CodeText 字体。默认值：Arial 5pt regular。如果 FontMode 设置为 FontMode.Auto，则此设置被忽略。 |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | 指定 FontMode。若 FontMode 设置为 Auto，则字体大小将根据 xDimension 值自动计算。建议在 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 中使用 FontMode.Auto。默认值：FontMode.Auto。 |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | 指定 CodeText 的显示位置，设置为 CodeLocation.None 可隐藏 CodeText。默认值：1D 条码使用 CodeLocation.Below，2D 条码使用 CodeLocation.None。 |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | 指定文本内的自动换行（换行符）。默认值：false。 |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | 在 [`Unit`](../unit/) 值中，CodeText 与条码之间的间距。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 忽略此设置。 |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | 在 2D 条码中将显示的文本，替代 codetext。用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | 返回此 `CodetextParameters` 的可读字符串表示。 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


