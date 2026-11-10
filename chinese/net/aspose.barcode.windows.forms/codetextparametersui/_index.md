---
title: "类 CodetextParametersUI"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Windows.Forms.CodetextParametersUI 类。Codetext 参数"
type: docs
weight: 1820
url: /zh/net/aspose.barcode.windows.forms/codetextparametersui/
---
## CodetextParametersUI class

代码文本参数。

```csharp
public class CodetextParametersUI
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alignment](../../aspose.barcode.windows.forms/codetextparametersui/alignment/) { get; set; } | 获取或设置代码文本的对齐方式。默认值：StringAlignment.Center。 |
| [Color](../../aspose.barcode.windows.forms/codetextparametersui/color/) { get; set; } | 指定显示的 CodeText 颜色。默认值：Color.Black。 |
| [Font](../../aspose.barcode.windows.forms/codetextparametersui/font/) { get; set; } | 指定显示的 CodeText 字体。默认值：Arial 5pt regular。如果 FontMode 设置为 FontMode.Auto，则此设置被忽略。 |
| [FontMode](../../aspose.barcode.windows.forms/codetextparametersui/fontmode/) { get; set; } | 指定 FontMode。若 FontMode 设置为 Auto，则字体大小将根据 xDimension 值自动计算。建议在 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 中使用 FontMode.Auto。默认值：FontMode.Auto。 |
| [Location](../../aspose.barcode.windows.forms/codetextparametersui/location/) { get; set; } | 指定 CodeText 的显示位置，设置为 CodeLocation.None 可隐藏 CodeText。默认值：1D 条码使用 CodeLocation.Below，2D 条码使用 CodeLocation.None。 |
| [Space](../../aspose.barcode.windows.forms/codetextparametersui/space/) { get; } | CodeText 与条码之间的间距，以 [`Unit`](../../aspose.barcode.generation/unit/) 为单位。默认值：2pt。对 EAN8、EAN13、UPCE、UPCA、ISBN、ISMN、ISSN、UpcaGs1DatabarCoupon 忽略此设置。 |
| [TwoDDisplayText](../../aspose.barcode.windows.forms/codetextparametersui/twoddisplaytext/) { get; set; } | 在 2D 条码中将显示的文本，替代 codetext。用于：Aztec、Pdf417、DataMatrix、QR、MaxiCode、DotCode。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/codetextparametersui/tostring/)() | 返回此 [`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/) 的可读字符串表示。 |

### 另见

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


