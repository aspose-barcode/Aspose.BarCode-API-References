---
title: BarcodeParameters Class
linktitle: BarcodeParameters
articleTitle: BarcodeParameters
second_title: Aspose.BarCode for Node.js via Java
description: "Barcode generation parameters."
type: docs
weight: 450
url: /nodejs/barcodeparameters/
---
## BarcodeParameters class

Barcode generation parameters.

```javascript
public class BarcodeParameters : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [BarcodeParameters](./barcodeparameters/#constructor)(*object*) | Initializes a new instance of the BarcodeParameters class. |

## Methods

| Name | Description |
| --- | --- |
| [getAustralianPost](./getaustralianpost/) | AustralianPost barcode parameters. |
| [getAztec](./getaztec/) | Aztec parameters. |
| [getBarColor](./getbarcolor/) | Bars color. |
| [getBarHeight](./getbarheight/) | Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [getBarWidthReduction](./getbarwidthreduction/) | Get bars reduction value that is used to compensate ink spread while printing. |
| [getChecksumAlwaysShow](./getchecksumalwaysshow/) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [getCodabar](./getcodabar/) | Codabar parameters. |
| [getCodablock](./getcodablock/) | Codablock parameters. |
| [getCode128](./getcode128/) | Code128 parameters. |
| [getCode16K](./getcode16k/) | Code16K parameters. |
| [getCodeTextParameters](./getcodetextparameters/) | Codetext parameters. |
| [getCoupon](./getcoupon/) | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar](./getdatabar/) | Databar parameters. |
| [getDataMatrix](./getdatamatrix/) | DataMatrix parameters. |
| [getDotCode](./getdotcode/) | DotCode parameters. |
| [getEnableEscape](./getenableescape/) | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports inputing decimal... |
| [getFilledBars](./getfilledbars/) | Gets a value indicating whether bars filled. Only for 1D barcodes. Default value: true. |
| [getGS1CompositeBar](./getgs1compositebar/) | GS1 Composite Bar parameters. |
| [getHanXin](./gethanxin/) | HanXin parameters. |
| [getITF](./getitf/) | ITF parameters. |
| [getMaxiCode](./getmaxicode/) | MaxiCode parameters. |
| [getPadding](./getpadding/) | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [getPatchCode](./getpatchcode/) | PatchCode parameters. |
| [getPdf417](./getpdf417/) | PDF417 parameters. |
| [getPostal](./getpostal/) | Postal parameters. Used for Postnet, Planet. |
| [getQR](./getqr/) | QR parameters. |
| [getSupplement](./getsupplement/) | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio](./getwidenarrowratio/) | Wide bars to Narrow bars ratio . Default value: 3, that is, wide bars are 3 times as wide as narrow bars . Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard The... |
| [getXDimension](./getxdimension/) | x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [init](./init/) |  |
| [isChecksumEnabled](./ischecksumenabled/) | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode... |
| [setBarColor](./setbarcolor/)(*object*) | Bars color. |
| [setBarHeight](./setbarheight/)(*object*) | Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [setBarWidthReduction](./setbarwidthreduction/)(*object*) | Sets bars reduction value that is used to compensate ink spread while printing. |
| [setChecksumAlwaysShow](./setchecksumalwaysshow/)(*object*) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [setChecksumEnabled](./setchecksumenabled/)(*object*) | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode... |
| [setEnableEscape](./setenableescape/)(*object*) | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. |
| [setFilledBars](./setfilledbars/)(*object*) | Sets a value indicating whether bars filled. Only for 1D barcodes. Default value: true. |
| [setGS1CompositeBar](./setgs1compositebar/)(*object*) | GS1 Composite Bar parameters. |
| [setPadding](./setpadding/)(*object*) | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio](./setwidenarrowratio/)(*object*) | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. |
| [setXDimension](./setxdimension/)(*object*) | x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |

## Fields

| Name | Description |
| --- | --- |
| [australianPost](./australianpost/) |  |
| [aztec](./aztec/) |  |
| [barHeight](./barheight/) |  |
| [barWidthReduction](./barwidthreduction/) |  |
| [codabar](./codabar/) |  |
| [codablock](./codablock/) |  |
| [code128](./code128/) |  |
| [code16K](./code16k/) |  |
| [codeTextParameters](./codetextparameters/) |  |
| [coupon](./coupon/) |  |
| [dataBar](./databar/) |  |
| [dataMatrix](./datamatrix/) |  |
| [dotCode](./dotcode/) |  |
| [gs1CompositeBar](./gs1compositebar/) |  |
| [hanXin](./hanxin/) |  |
| [itf](./itf/) |  |
| [maxiCode](./maxicode/) |  |
| [padding](./padding/) |  |
| [patchCode](./patchcode/) |  |
| [pdf417](./pdf417/) |  |
| [postal](./postal/) |  |
| [qr](./qr/) |  |
| [supplement](./supplement/) |  |
| [xDimension](./xdimension/) |  |

### See Also

* assembly [Aspose.BarCode](../)

