---
title: "BarcodeParameters Class"
linktitle: "BarcodeParameters"
articleTitle: "BarcodeParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "Barcode generation parameters."
type: docs
weight: 10
url: /php/aspose/barcode/generation/barcodeparameters/
---

## BarcodeParameters class

**Namespace:** `Aspose.Barcode.Generation`


Barcode generation parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](/php/aspose/barcode/generation/barcodeparameters/barcodeparameters/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isChecksumEnabled](/php/aspose/barcode/generation/barcodeparameters/ischecksumenabled/) | No | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology |
| [setChecksumEnabled](/php/aspose/barcode/generation/barcodeparameters/setchecksumenabled/) | No | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AustralianPost](/php/aspose/barcode/generation/barcodeparameters/australianpost/) | Read-only | AustralianPost barcode parameters. |
| [Aztec](/php/aspose/barcode/generation/barcodeparameters/aztec/) | Read-only | Aztec parameters. |
| [BarColor](/php/aspose/barcode/generation/barcodeparameters/barcolor/) | Read/Write | Bars color. Default value: #000000 |
| [BarHeight](/php/aspose/barcode/generation/barcodeparameters/barheight/) | Read/Write | Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION. |
| [BarWidthReduction](/php/aspose/barcode/generation/barcodeparameters/barwidthreduction/) | Read/Write | Get bars reduction value that is used to compensate ink spread while printing. |
| [ChecksumAlwaysShow](/php/aspose/barcode/generation/barcodeparameters/checksumalwaysshow/) | Read/Write | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [Codabar](/php/aspose/barcode/generation/barcodeparameters/codabar/) | Read-only | Codabar parameters. |
| [Codablock](/php/aspose/barcode/generation/barcodeparameters/codablock/) | Read-only | Codablock parameters. |
| [Code128](/php/aspose/barcode/generation/barcodeparameters/code128/) | Read-only | Code128 parameters. |
| [Code16K](/php/aspose/barcode/generation/barcodeparameters/code16k/) | Read-only | Code16K parameters. |
| [CodeTextParameters](/php/aspose/barcode/generation/barcodeparameters/codetextparameters/) | Read-only | Codetext parameters. |
| [Coupon](/php/aspose/barcode/generation/barcodeparameters/coupon/) | Read-only | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](/php/aspose/barcode/generation/barcodeparameters/databar/) | Read-only | Databar parameters. |
| [DataMatrix](/php/aspose/barcode/generation/barcodeparameters/datamatrix/) | Read-only | DataMatrix parameters. |
| [DotCode](/php/aspose/barcode/generation/barcodeparameters/dotcode/) | Read-only | DotCode parameters. |
| [EnableEscape](/php/aspose/barcode/generation/barcodeparameters/enableescape/) | Read/Write | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \013 and \CR stands for CR. |
| [FilledBars](/php/aspose/barcode/generation/barcodeparameters/filledbars/) | Read/Write | Only for 1D barcodes. |
| [GS1CompositeBar](/php/aspose/barcode/generation/barcodeparameters/gs1compositebar/) | Read/Write | GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' $codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; $generator = new BarcodeGenerator(EncodeTypes::GS_1_COMPOSITE_BAR, $codetext); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setLinearComponentType(EncodeTypes::GS_1_CODE_128); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setTwoDComponentType(TwoDComponentType::CC_A); // Aspect ratio of 2D component $generator->getParameters()->getBarcode()->getPdf417()->setAspectRatio(3); // X-Dimension of 1D and 2D components $generator->getParameters()->getBarcode()->getXDimension()->setPixels(3); /// // Height of 1D component $generator->getParameters()->getBarcode()->getBarHeight()->setPixels(100); /// $generator->save("test.png", BarcodeImageFormat::PNG); |
| [HanXin](/php/aspose/barcode/generation/barcodeparameters/hanxin/) | Read-only | HanXin parameters. |
| [ITF](/php/aspose/barcode/generation/barcodeparameters/itf/) | Read-only | ITF parameters. |
| [MaxiCode](/php/aspose/barcode/generation/barcodeparameters/maxicode/) | Read-only | MaxiCode parameters. |
| [Padding](/php/aspose/barcode/generation/barcodeparameters/padding/) | Read/Write | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [PatchCode](/php/aspose/barcode/generation/barcodeparameters/patchcode/) | Read-only | PatchCode parameters. |
| [Pdf417](/php/aspose/barcode/generation/barcodeparameters/pdf417/) | Read-only | PDF417 parameters. |
| [Postal](/php/aspose/barcode/generation/barcodeparameters/postal/) | Read-only | Postal parameters. Used for Postnet, Planet. |
| [QR](/php/aspose/barcode/generation/barcodeparameters/qr/) | Read-only | QR parameters. |
| [Supplement](/php/aspose/barcode/generation/barcodeparameters/supplement/) | Read-only | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [WideNarrowRatio](/php/aspose/barcode/generation/barcodeparameters/widenarrowratio/) | Read/Write | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](/php/aspose/barcode/generation/barcodeparameters/xdimension/) | Read/Write | x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION. |
