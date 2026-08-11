---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Barcode generation parameters."
type: docs
weight: 140
url: /nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Barcode generation parameters.

```js
new BarcodeParameters()
```

## Methods

| Name | Description |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | AustralianPost barcode parameters. |
| [getAztec()](#getaztec) | Aztec parameters. |
| [getBarColor()](#getbarcolor) | Bars color. |
| [getBarHeight()](#getbarheight) | Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | Get bars reduction value that is used to compensate ink spread while printing. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [getCodabar()](#getcodabar) | Codabar parameters. |
| [getCodablock()](#getcodablock) | Codablock parameters. |
| [getCode16K()](#getcode16k) | Code16K parameters. |
| [getCode128()](#getcode128) | Code128 parameters. |
| [getCodeTextParameters()](#getcodetextparameters) | Codetext parameters. |
| [getCoupon()](#getcoupon) | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Databar parameters. |
| [getDataMatrix()](#getdatamatrix) | DataMatrix parameters. |
| [getDotCode()](#getdotcode) | DotCode parameters. |
| [getEnableEscape()](#getenableescape) | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, C |
| [getFilledBars()](#getfilledbars) | Gets a value indicating whether bars filled. Only for 1D barcodes. Default value: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext  |
| [getHanXin()](#gethanxin) | HanXin parameters. |
| [getITF()](#getitf) | ITF parameters. |
| [getMaxiCode()](#getmaxicode) | MaxiCode parameters. |
| [getPadding()](#getpadding) | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | PatchCode parameters. |
| [getPdf417()](#getpdf417) | PDF417 parameters. |
| [getPostal()](#getpostal) | Postal parameters. Used for Postnet, Planet. |
| [getQR()](#getqr) | QR parameters. |
| [getSupplement()](#getsupplement) | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Wide bars to Narrow bars ratio . Default value: 3, that is, wide bars are 3 times as wide as narrow bars . Used for ITF, |
| [getXDimension()](#getxdimension) | x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode i |
| [isChecksumEnabled()](#ischecksumenabled) | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as N |
| [setBarColor(value)](#setbarcolor) | Bars color. |
| [setBarHeight()](#setbarheight) | Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | Sets bars reduction value that is used to compensate ink spread while printing. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [setChecksumEnabled()](#setchecksumenabled) | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as N |
| [setEnableEscape()](#setenableescape) | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, C |
| [setFilledBars()](#setfilledbars) | Sets a value indicating whether bars filled. Only for 1D barcodes. Default value: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext  |
| [setPadding()](#setpadding) | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, P |
| [setXDimension()](#setxdimension) | x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode i |

### getAustralianPost() {#getaustralianpost}

AustralianPost barcode parameters.

### getAztec() {#getaztec}

Aztec parameters.

### getBarColor() {#getbarcolor}

Bars color.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Get bars reduction value that is used to compensate ink spread while printing.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes.

### getCodabar() {#getcodabar}

Codabar parameters.

### getCodablock() {#getcodablock}

Codablock parameters.

### getCode16K() {#getcode16k}

Code16K parameters.

### getCode128() {#getcode128}

Code128 parameters.

### getCodeTextParameters() {#getcodetextparameters}

Codetext parameters.

### getCoupon() {#getcoupon}

Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Databar parameters.

### getDataMatrix() {#getdatamatrix}

DataMatrix parameters.

### getDotCode() {#getdotcode}

DotCode parameters.

### getEnableEscape() {#getenableescape}

Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \013 and \\CR stands for CR.

### getFilledBars() {#getfilledbars}

Gets a value indicating whether bars filled. Only for 1D barcodes. Default value: true.

### getGS1CompositeBar() {#getgs1compositebar}

GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/'

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

HanXin parameters.

### getITF() {#getitf}

ITF parameters.

### getMaxiCode() {#getmaxicode}

MaxiCode parameters.

### getPadding() {#getpadding}

Barcode paddings. Default value: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

PatchCode parameters.

### getPdf417() {#getpdf417}

PDF417 parameters.

### getPostal() {#getpostal}

Postal parameters. Used for Postnet, Planet.

### getQR() {#getqr}

QR parameters.

### getSupplement() {#getsupplement}

Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Wide bars to Narrow bars ratio . Default value: 3, that is, wide bars are 3 times as wide as narrow bars . Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard The WideNarrowRatio parameter value is less than or equal to 0.

### getXDimension() {#getxdimension}

x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology

### setBarColor(value) {#setbarcolor}

Bars color.

| Parameter | Type | Description |
| --- | --- | --- |
| value | String | for Bar color Default value: #000000. |

### setBarHeight() {#setbarheight}

Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Sets bars reduction value that is used to compensate ink spread while printing.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes.

### setChecksumEnabled() {#setchecksumenabled}

Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology

### setEnableEscape() {#setenableescape}

Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports the decimal ascii code and mnemonic for ASCII control-code characters. For example, \013 and \\CR stands for CR.

### setFilledBars() {#setfilledbars}

Sets a value indicating whether bars filled. Only for 1D barcodes. Default value: true.

### setGS1CompositeBar() {#setgs1compositebar}

GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/'

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

Barcode paddings. Default value: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard The WideNarrowRatio parameter value is less than or equal to 0.

### setXDimension() {#setxdimension}

x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
