---
title: "BarcodeParameters Class"
linktitle: "BarcodeParameters"
articleTitle: "BarcodeParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "Barcode generation parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/barcodeparameters/
---

## BarcodeParameters class

**Module:** `aspose_barcode.generation.barcode_parameters`


Barcode generation parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./barcodeparameters/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [australian_post](./australian_post/) | `AustralianPostParameters` | No | AustralianPost barcode parameters. |
| [aztec](./aztec/) | `AztecParameters` | No | Aztec parameters. |
| [codabar](./codabar/) | `CodabarParameters` | No | Codabar parameters. |
| [codablock](./codablock/) | `CodablockParameters` | No | Codablock parameters. |
| [code_128](./code_128/) | `Code128Parameters` | No | Code128 parameters. |
| [code_16k](./code_16k/) | `Code16KParameters` | No | Code16K parameters. |
| [codetext_parameters](./codetext_parameters/) | `CodetextParameters` | No | Codetext parameters. |
| [coupon](./coupon/) | `CouponParameters` | No | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [data_bar](./data_bar/) | `DataBarParameters` | No | Databar parameters. |
| [data_matrix](./data_matrix/) | `DataMatrixParameters` | No | DataMatrix parameters. |
| [dot_code](./dot_code/) | `DotCodeParameters` | No | DotCode parameters. |
| [han_xin](./han_xin/) | `HanXinParameters` | No | HanXin parameters. |
| [itf](./itf/) | `ITFParameters` | No | ITF parameters. |
| [maxi_code](./maxi_code/) | `MaxiCodeParameters` | No | MaxiCode parameters. |
| [padding](./padding/) | `Padding` | No | Barcode paddings. Default value: 5pt 5pt 5pt 5pt. |
| [patch_code](./patch_code/) | `PatchCodeParameters` | No | PatchCode parameters. |
| [pdf_417](./pdf_417/) | `Pdf417Parameters` | No | PDF417 parameters. |
| [postal](./postal/) | `PostalParameters` | No | Postal parameters. Used for Postnet, Planet. |
| [qr](./qr/) | `QrParameters` | No | QR parameters. |
| [supplement](./supplement/) | `SupplementParameters` | No | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [bar_color](./bar_color/) | `Tuple[int, int, int]` | Bars color, representation of an RGB tuple. Default value: 0 |
| [bar_height](./bar_height/) | `Unit` | Height of 1D barcodes' bars in Unit value. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
| [bar_width_reduction](./bar_width_reduction/) | `Unit` | Get bars reduction value that is used to compensate ink spread while printing. |
| [checksum_always_show](./checksum_always_show/) | `bool` | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [checksum_enabled](./checksum_enabled/) | `EnableChecksum` | Enable checksum during generation 1D barcodes. Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible. Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar Checksum always used: Rest symbology |
| [enable_escape](./enable_escape/) | `bool` | Indicates whether explains the character "\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is True, "\" will be explained as a special escape character. Otherwise, "\" acts as normal characters. Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \013 and \CR stands for CR. |
| [filled_bars](./filled_bars/) | `bool` | Gets a value indicating whether bars filled. Only for 1D barcodes. Default value: True. |
| [gs1_composite_bar](./gs1_composite_bar/) | `GS1CompositeBarParameters` | GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' |
| [wide_narrow_ratio](./wide_narrow_ratio/) | `float` | Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard The WideNarrowRatio parameter value is less than or equal to 0. |
| [x_dimension](./x_dimension/) | `Unit` | x-dimension is the smallest width of the unit of BarCode bars or spaces. Increasing this will increase the whole barcode image width. Ignored if AutoSizeMode property is set to AutoSizeMode.NEAREST or AutoSizeMode.INTERPOLATION. |
