---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "Barcode generation parameters."
type: docs
weight: 10
url: /php/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

**Namespace:** `Aspose.Barcode.Generation`


Barcode generation parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isChecksumEnabled](#ischecksumenabled) | No | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology |
| [setChecksumEnabled](#setchecksumenabled) | No | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AustralianPost](#australianpost) | Read-only | AustralianPost barcode parameters. |
| [Aztec](#aztec) | Read-only | Aztec parameters. |
| [BarColor](#barcolor) | Read/Write | Bars color. Default value: #000000 |
| [BarHeight](#barheight) | Read/Write | Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION. |
| [BarWidthReduction](#barwidthreduction) | Read/Write | Get bars reduction value that is used to compensate ink spread while printing. |
| [ChecksumAlwaysShow](#checksumalwaysshow) | Read/Write | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [Codabar](#codabar) | Read-only | Codabar parameters. |
| [Codablock](#codablock) | Read-only | Codablock parameters. |
| [Code128](#code128) | Read-only | Code128 parameters. |
| [Code16K](#code16k) | Read-only | Code16K parameters. |
| [CodeTextParameters](#codetextparameters) | Read-only | Codetext parameters. |
| [Coupon](#coupon) | Read-only | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](#databar) | Read-only | Databar parameters. |
| [DataMatrix](#datamatrix) | Read-only | DataMatrix parameters. |
| [DotCode](#dotcode) | Read-only | DotCode parameters. |
| [EnableEscape](#enableescape) | Read/Write | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \013 and \CR stands for CR. |
| [FilledBars](#filledbars) | Read/Write | Only for 1D barcodes. |
| [GS1CompositeBar](#gs1compositebar) | Read/Write | GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' $codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; $generator = new BarcodeGenerator(EncodeTypes::GS_1_COMPOSITE_BAR, $codetext); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setLinearComponentType(EncodeTypes::GS_1_CODE_128); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setTwoDComponentType(TwoDComponentType::CC_A); // Aspect ratio of 2D component $generator->getParameters()->getBarcode()->getPdf417()->setAspectRatio(3); // X-Dimension of 1D and 2D components $generator->getParameters()->getBarcode()->getXDimension()->setPixels(3); /// // Height of 1D component $generator->getParameters()->getBarcode()->getBarHeight()->setPixels(100); /// $generator->save("test.png", BarcodeImageFormat::PNG); |
| [HanXin](#hanxin) | Read-only | HanXin parameters. |
| [ITF](#itf) | Read-only | ITF parameters. |
| [MaxiCode](#maxicode) | Read-only | MaxiCode parameters. |
| [Padding](#padding) | Read/Write | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [PatchCode](#patchcode) | Read-only | PatchCode parameters. |
| [Pdf417](#pdf417) | Read-only | PDF417 parameters. |
| [Postal](#postal) | Read-only | Postal parameters. Used for Postnet, Planet. |
| [QR](#qr) | Read-only | QR parameters. |
| [Supplement](#supplement) | Read-only | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [WideNarrowRatio](#widenarrowratio) | Read/Write | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](#xdimension) | Read/Write | x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION. |

### BarcodeParameters__construct(BarcodeParametersDTO $barcodeParametersDto) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$barcodeParametersDto` | `BarcodeParametersDTO` |  |

### isChecksumEnabledisChecksumEnabled() {#ischecksumenabled}

Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology

### setChecksumEnabledsetChecksumEnabled(int $value) {#setchecksumenabled}

Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### AustralianPost {#australianpost}

**Access:** Read-only

AustralianPost barcode parameters.

### Aztec {#aztec}

**Access:** Read-only

Aztec parameters.

### BarColor {#barcolor}

**Access:** Read/Write

Bars color. Default value: #000000

Bars color. Default value: #000000.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### BarHeight {#barheight}

**Access:** Read/Write

Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION.

Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to utoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Unit` |  |

### BarWidthReduction {#barwidthreduction}

**Access:** Read/Write

**Returns:** Unit value of BarWidthReduction

Get bars reduction value that is used to compensate ink spread while printing.

Sets bars reduction value that is used to compensate ink spread while printing.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `?Unit` |  |

### ChecksumAlwaysShow {#checksumalwaysshow}

**Access:** Read/Write

Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes.

Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes.

| Parameter | Type | Description |
| --- | --- | --- |
| `$checksumAlwaysShow` | `bool` |  |

### Codabar {#codabar}

**Access:** Read-only

Codabar parameters.

### Codablock {#codablock}

**Access:** Read-only

Codablock parameters.

### Code128 {#code128}

**Access:** Read-only

Code128 parameters.

### Code16K {#code16k}

**Access:** Read-only

Code16K parameters.

### CodeTextParameters {#codetextparameters}

**Access:** Read-only

Codetext parameters.

### Coupon {#coupon}

**Access:** Read-only

Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### DataBar {#databar}

**Access:** Read-only

Databar parameters.

### DataMatrix {#datamatrix}

**Access:** Read-only

DataMatrix parameters.

### DotCode {#dotcode}

**Access:** Read-only

DotCode parameters.

### EnableEscape {#enableescape}

**Access:** Read/Write

Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \013 and \CR stands for CR.

Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \013 and \CR stands for CR.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `bool` |  |

### FilledBars {#filledbars}

**Access:** Read/Write

**Returns:** bool Gets a value indicating whether bars filled.

Only for 1D barcodes.

Sets a value indicating whether bars filled. Only for 1D barcodes.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `bool` |  |

### GS1CompositeBar {#gs1compositebar}

**Access:** Read/Write

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' $codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; $generator = new BarcodeGenerator(EncodeTypes::GS_1_COMPOSITE_BAR, $codetext); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setLinearComponentType(EncodeTypes::GS_1_CODE_128); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setTwoDComponentType(TwoDComponentType::CC_A); // Aspect ratio of 2D component $generator->getParameters()->getBarcode()->getPdf417()->setAspectRatio(3); // X-Dimension of 1D and 2D components $generator->getParameters()->getBarcode()->getXDimension()->setPixels(3); /// // Height of 1D component $generator->getParameters()->getBarcode()->getBarHeight()->setPixels(100); /// $generator->save("test.png", BarcodeImageFormat::PNG);

GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' $codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; $generator = new BarcodeGenerator(EncodeTypes::GS_1_COMPOSITE_BAR, $codetext); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setLinearComponentType(EncodeTypes::GS_1_CODE_128); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setTwoDComponentType(TwoDComponentType::CC_A); // Aspect ratio of 2D component $generator->getParameters()->getBarcode()->getPdf417()->setAspectRatio(3); // X-Dimension of 1D and 2D components $generator->getParameters()->getBarcode()->getXDimension()->setPixels(3); /// // Height of 1D component $generator->getParameters()->getBarcode()->getBarHeight()->setPixels(100); /// $generator->save("test.png", BarcodeImageFormat::PNG);

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `GS1CompositeBarParameters` |  |

### HanXin {#hanxin}

**Access:** Read-only

HanXin parameters.

### ITF {#itf}

**Access:** Read-only

ITF parameters.

### MaxiCode {#maxicode}

**Access:** Read-only

MaxiCode parameters.

### Padding {#padding}

**Access:** Read/Write

Barcode paddings. Default value: 5pt 5pt 5pt 5pt.

Barcode paddings. Default value: 5pt 5pt 5pt 5pt.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Padding` |  |

### PatchCode {#patchcode}

**Access:** Read-only

PatchCode parameters.

### Pdf417 {#pdf417}

**Access:** Read-only

PDF417 parameters.

### Postal {#postal}

**Access:** Read-only

Postal parameters. Used for Postnet, Planet.

### QR {#qr}

**Access:** Read-only

QR parameters.

### Supplement {#supplement}

**Access:** Read-only

Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### WideNarrowRatio {#widenarrowratio}

**Access:** Read/Write

Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard

Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `float` |  |

### XDimension {#xdimension}

**Access:** Read/Write

x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION.

x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode::NEAREST or AutoSizeMode::INTERPOLATION.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `Unit` |  |

