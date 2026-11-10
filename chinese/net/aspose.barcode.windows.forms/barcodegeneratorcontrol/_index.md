---
title: "类 BarCodeGeneratorControl"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl 类。BarCode Windows 控件，前往工具箱面板并添加 Aspose.BarCode.dll，即可看到 BarcodeGeneratorControl 出现。只需将其拖放到 Windows 窗体中。see  see"
type: docs
weight: 1800
url: /zh/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control，转到工具箱面板并添加 Aspose.BarCode.dll，您将看到 BarcodeGeneratorControl 出现。只需将其拖放到您的 Windows 窗体中。see  see

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | 获取或设置条码自动调整大小的模式。默认值为 AutoSizeMode.None。 |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | 条码图像的背景颜色。 |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | 当 [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 时的条码图像高度。 |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | 获取或设置条码填充参数 [`Padding`](../../aspose.barcode.generation/padding/)。 |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | 条码的编码类型（符号系统）。使用 [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) 获取当前符号系统。 |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | 当 [`AutoSizeMode`](../../aspose.barcode/generation/autosizemode/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation 时的条码图像宽度。 |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | 条形颜色。 |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | 1D 条码条的高度。如果 [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则忽略。 |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | 获取或设置边框参数 [`BorderParameters`](../../aspose.barcode/generation/borderparameters/)。 |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | 条码图像上方的标题。参见 [`CaptionUI`](../captionui/)。 |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | 条码图像下方的标题。参见 [`CaptionUI`](../captionui/)。 |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | 始终在 Code128 和 GS1Code128 条码的人类可读文本中显示校验位数字。 |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | 待编码的数据，不同类型的条码可能对 CodeText 长度有不同限制。 |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | 获取或设置 CodeText 参数 [`CodetextParametersUI`](../codetextparametersui/)。 |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | 条码的编码类型（符号系统）。使用 [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) 获取当前符号系统。 |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | 获取或设置一个值，指示条是否已填充。仅适用于 1D 条码。 |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | 在生成 1D 条码时启用校验和。 |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | 获取或设置条码图像的分辨率。两个维度使用同一数值。默认值：96 dpi。 |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | BarCode 图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。 |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | 特定参数 |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | 仅适用于 1D 条码。如果 codetext 不正确且值设为 true——将抛出异常。否则 codetext 将被纠正以符合条码规范。以下情况始终会抛出异常：Databar 符号如果 codetext 不正确。以下情况始终不会抛出异常：AustraliaPost、SingapurePost、Code39Extended、Code93Extended、Code16K、Code128 符号如果 codetext 不正确。 |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | 获取或设置一个值，指示是否使用抗锯齿模式渲染图像。 |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | 宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII。 |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X 维度是条码条或空格单元的最小宽度。增大此值会增加整个条码图像的宽度。如果 [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则此设置被忽略。 |

### 另见

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


