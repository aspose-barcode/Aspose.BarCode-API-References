---
title: "类 BarcodeParameters"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.BarcodeParameters 类。条形码生成参数"
type: docs
weight: 1010
url: /zh/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

条形码生成参数。

```csharp
public class BarcodeParameters
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | AustralianPost 条形码参数。 |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Aztec 参数。 |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | 条形颜色。默认值：Color.Black。 |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | 1D 条码条的高度，以 [`Unit`](../unit/) 为单位。如果 [`AutoSizeMode`](../basegenerationparameters/autosizemode/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则忽略此设置。 |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | 获取或设置用于在打印时补偿墨水扩散的条宽缩减值。默认值：0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | 始终在 Code128 和 GS1Code128 条码的人类可读文本中显示校验位数字。 |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Codabar 参数。 |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Codablock 参数。 |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Code128 参数。 |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Code16K 参数。 |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | 代码文本参数。 |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | 优惠券参数。用于 UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon。 |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Databar 参数。 |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | DataMatrix 参数。 |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | DotCode 参数。 |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | 获取或设置一个值，指示条是否填充。仅适用于 1D 条码。默认值：true。 |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | GS1 参数。 |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | GS1 复合条参数。 |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | HanXin 参数。 |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | 在生成 1D 条码时启用校验和。 |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | ITF 参数。 |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | MaxiCode 参数。 |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | 条码填充。默认值：5pt 5pt 5pt 5pt。 |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | PatchCode 参数。 |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417 参数。 |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | 邮政参数。用于 Postnet、Planet。 |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR、MicroQR 和 RectMicroQR 参数。 |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | 补充参数。用于 Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN。 |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | 仅适用于 1D 条码。如果 codetext 不正确且值设置为 true——将抛出异常。否则 codetext 将被纠正以符合条码规范。以下情况始终会抛出异常：Databar 符号如果 codetext 不正确。以下情况始终不会抛出异常：AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 符号如果 codetext 不正确。 |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | 宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII。 |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-dimension 是条码条或空格单元的最小宽度。增加它将增加整个条码图像的宽度。如果 [`AutoSizeMode`](../basegenerationparameters/autosizemode/) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则忽略此设置。 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


