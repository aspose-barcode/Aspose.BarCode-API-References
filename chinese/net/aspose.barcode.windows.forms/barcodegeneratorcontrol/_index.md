---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode for .NET API 参考
description: BarCode Windows Control转到您的工具箱面板并添加 Aspose.BarCode.dll 您将看到 BarcodeGeneratorControl 出现 只需将其拖放到您的 Windows 窗体中 见 见
type: docs
weight: 1050
url: /zh/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control，转到您的工具箱面板并添加 Aspose.BarCode.dll， ，您将看到 BarcodeGeneratorControl 出现。 只需将其拖放到您的 Windows 窗体中。 见 见

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | 获取或设置条码自动调整大小的模式。 默认值为 AutoSizeMode.None。 |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | 条形码图像的背景颜色。 |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | 条码图像高度时[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode)属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | 获取或设置条形码填充参数[`Padding`](../../aspose.barcode.generation/padding). |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | BarCode 的编码类型（符号）。 使用[`EncodeTypes`](../../aspose.barcode.generation/encodetypes)获取当前符号。 |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | 条码图像宽度时[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode)属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | 条形颜色。 |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | 一维条码条的高度。 忽略如果[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode)属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | 获取或设置边框参数[`BorderParameters`](../../aspose.barcode.generation/borderparameters). |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | 条码图像上方的标题。看[`CaptionParameters`](../../aspose.barcode.generation/captionparameters). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | 条码图像下方的标题。看[`CaptionParameters`](../../aspose.barcode.generation/captionparameters). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | 始终在 Code128 和 GS1Code128 条码的人类可读文本中显示校验和数字。 |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | 要编码的数据，不同类型的BarCode可能有不同的CodeText长度限制。 |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | 获取或设置 CodeText 参数[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters). |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | 指示是否将字符“\”解释为 CodeText 属性中的转义字符。用于Pdf417、DataMatrix、Code128 only 如果EnableEscape为真，“\”将解释为特殊转义字符。否则，“\”作为普通字符。 Aspose.BarCode 支持输入十进制 ascii 码和 ASCII 控制码字符的助记符。例如，\013 和 \\CR 代表 CR。 |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | BarCode 的编码类型（符号）。 使用[`EncodeTypes`](../../aspose.barcode.generation/encodetypes)获取当前符号。 |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | 获取或设置指示条是否填充的值。 仅适用于一维条码。 |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | 在生成一维条码期间启用校验和。 |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | 获取或设置条形码图像的分辨率。 两个维度的一个值。 默认值：96 dpi。 |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | BarCode 图像旋转角度，以度为单位，例如 RotationAngle = 0 或 RotationAngle = 360 表示不旋转。 如果 RotationAngle 不等于 90、180、270 或 0，可能会增加扫描仪读取图像的难度。 |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | 具体参数 |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | 仅适用于一维条码。 如果代码文本不正确且值设置为 true - 将引发异常。否则 codetext 将被更正以匹配条形码的规范。 如果 codetext 不正确，则始终会引发异常。 . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | 宽条与窄条的比例。 默认值：3，即宽条是窄条的 3 倍。 用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | X-dimension 是 BarCode 条或空格单位的最小宽度。 增加这将增加整个条形码图像的宽度。 忽略如果[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode)属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation. |

### 也可以看看

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* 命名空间 [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
