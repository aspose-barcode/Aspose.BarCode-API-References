---
title: Class BarcodeParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.BarcodeParameters class. Barcode generation parameters
type: docs
weight: 930
url: /net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Barcode generation parameters.

```csharp
public class BarcodeParameters
```

## Properties

| Name | Description |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | AustralianPost barcode parameters. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Aztec parameters. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Bars color. Default value: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | Height of 1D barcodes' bars in [`Unit`](../unit/) value. Ignored if [`AutoSizeMode`](../basegenerationparameters/autosizemode/) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Get or sets bars reduction value that is used to compensate ink spread while printing. Default value: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Codabar parameters. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Codablock parameters. |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Code128 parameters. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Code16K parameters. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | Codetext parameters. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Databar parameters. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | DataMatrix parameters. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | DotCode parameters. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape/) { get; set; } | EnableEscape is deprecated and ignored. Process escape sequences explicitly (e.g., Regex.Unescape). This property will be removed in future releases. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Gets or sets a value indicating whether bars filled. Only for 1D barcodes. Default value: true. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | GS1 Composite Bar parameters. |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | HanXin parameters. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | Enable checksum during generation 1D barcodes. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | ITF parameters. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | MaxiCode parameters. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | PatchCode parameters. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417 parameters. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Postal parameters. Used for Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR, MicroQR and RectMicroQR parameters. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology if codetext is incorrect. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if [`AutoSizeMode`](../basegenerationparameters/autosizemode/) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


