---
title: "Aspose.Barcode.Generation"
linktitle: "Aspose.Barcode.Generation"
second_title: "Aspose.BarCode for PHP via Java"
description: "The Aspose.Barcode.Generation namespace supplies classes and enums for configuring and creating barcodes in PHP via Java."
type: docs
weight: 10
url: /php/aspose.barcode.generation/
---

## Aspose.Barcode.Generation namespace

Use the types in this namespace to define barcode symbology, visual appearance, and output options. The reference lists each class and enumeration, their properties, methods, and usage examples.

## Classes

| Class | Description |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost barcode parameters. |
| [AztecParameters](./aztecparameters/) | Aztec parameters. |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator for backend barcode images generation. supported symbologies: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Barcode generation parameters. |
| [BaseGenerationParameters](./basegenerationparameters/) | Barcode image generation parameters. |
| [BorderParameters](./borderparameters/) | Barcode image border parameters |
| [CaptionParameters](./captionparameters/) | Caption parameters. |
| [CMYKColor](./cmykcolor/) | Class for CMYK color. A null instance means CMYK is not used, and default RGB color is in use. |
| [CodabarParameters](./codabarparameters/) | Codabar parameters. |
| [CodablockParameters](./codablockparameters/) | Codablock parameters. |
| [Code128Parameters](./code128parameters/) | Code128 parameters. |
| [Code16KParameters](./code16kparameters/) | Code16K parameters. |
| [CodetextParameters](./codetextparameters/) | Codetext parameters. |
| [CouponParameters](./couponparameters/) | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters/) | Databar parameters. |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of DataMatrixEncodeMode |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix parameters. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode |
| [DotCodeParameters](./dotcodeparameters/) | DotCode parameters. |
| [EncodeTypes](./encodetypes/) | Specifies the type of barcode to encode. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Helper class for automatic codetext generation of the Extended Codetext Mode |
| [FontUnit](./fontunit/) | Defines a particular format for text, including font face, size, and style attributes where size in Unit value property. |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite bar parameters. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Extended codetext generator for Han Xin Code for Extended Mode of HanXinEncodeMode |
| [HanXinParameters](./hanxinparameters/) | Han Xin parameters. |
| [HslaColor](./hslacolor/) | Class for representing HSLA color (Hue, Saturation, Lightness, Alpha) |
| [ImageParameters](./imageparameters/) | Image parameters. |
| [ITFParameters](./itfparameters/) | ITF parameters. |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode Use TwoDDisplayText pr |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode parameters. |
| [Padding](./padding/) | Paddings parameters. |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode parameters. |
| [Pdf417Parameters](./pdf417parameters/) | PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fie |
| [PdfParameters](./pdfparameters/) | PDF parameters wrapper. Expects an underlying javaClass instance that provides the corresponding getter/setter methods r |
| [PostalParameters](./postalparameters/) | Postal parameters. Used for Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QREncodeMode Use Display2DText property of B |
| [QrParameters](./qrparameters/) | QR parameters. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR structured append parameters. |
| [SupplementParameters](./supplementparameters/) | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | SVG parameters. |
| [Unit](./unit/) | Specifies the size value in different units (Pixel, Inches, etc.). This sample shows how to create and save a BarCode im |

## Enums

| Enum | Description |
| --- | --- |
| [AutoSizeMode](./autosizemode/) | Specifies the different types of automatic sizing modes. Default value is AutoSizeMode::NONE. This sample shows how to c |
| [AztecEncodeMode](./aztecencodemode/) | Encoding mode for Aztec barcodes. |
| [AztecSymbolMode](./aztecsymbolmode/) | Specifies the Aztec symbol mode. |
| [BarCodeImageFormat](./barcodeimageformat/) | Specifies the file format of the image. |
| [Base64CodeTextType](./base64codetexttype/) |  |
| [BorderDashStyle](./borderdashstyle/) | Specifies the style of dashed border lines. |
| [CodabarChecksumMode](./codabarchecksummode/) | Specifies the checksum algorithm for Codabar |
| [CodabarSymbol](./codabarsymbol/) | Specifies the start or stop symbol of the Codabar barcode specification. |
| [Code128EncodeMode](./code128encodemode/) | Encoding mode for Code128 barcodes. specification. |
| [CodeLocation](./codelocation/) | Codetext location |
| [DataMatrixEccType](./datamatrixecctype/) | Specify the type of the ECC to encode. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | DataMatrix encoder's encoding mode, default to Auto |
| [DataMatrixVersion](./datamatrixversion/) | Specify the type of the ECC to encode. |
| [DotCodeEncodeMode](./dotcodeencodemode/) | Encoding mode for DotCode barcodes. |
| [ECIEncodings](./eciencodings/) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [EnableChecksum](./enablechecksum/) | Enable checksum during generation for 1D barcodes. Default is treated as Yes for symbologies which must contain checksum |
| [ExtCodeItemType](./extcodeitemtype/) |  |
| [ExtCodetextBuilderType](./extcodetextbuildertype/) |  |
| [FontMode](./fontmode/) | Font size mode. |
| [FontStyle](./fontstyle/) | Specifies style information applied to text. |
| [GraphicsUnit](./graphicsunit/) | Specifies the unit of measure for the given data. |
| [HanXinEncodeMode](./hanxinencodemode/) | Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode charact |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Level of Reed-Solomon error correction. From low to high: L1, L2, L3, L4. |
| [HanXinExtCodetextBuilderType](./hanxinextcodetextbuildertype/) |  |
| [HanXinVersion](./hanxinversion/) | Version of Han Xin Code. From Version01 - 23 x 23 modules to Version84 - 189 x 189 modules, increasing in steps of 2 mod |
| [ITF14BorderType](./itf14bordertype/) | ITF14 barcode's border type |
| [MacroCharacter](./macrocharacter/) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is trans |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | Encoding mode for MaxiCode barcodes. |
| [MaxiCodeMode](./maxicodemode/) | Encoding mode for MaxiCode barcodes. This sample shows how to genereate MaxiCode barcodes using ComplexBarcodeGenerator |
| [MicroQRVersion](./microqrversion/) | Version of MicroQR Code. From M1 to M4. |
| [PatchFormat](./patchformat/) | PatchCode format. Choose PatchOnly to generate single PatchCode. Use page format to generate Patch page with PatchCodes  |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Pdf417 barcode's compation mode |
| [Pdf417EncodeMode](./pdf417encodemode/) | Pdf417 barcode encode mode |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | pdf417 barcode's error correction level, from level 0 to level 9, level 0 means no error correction, level 9 means best  |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [QREncodeMode](./qrencodemode/) | Encoding mode for QR barcodes. This sample shows how to use FNC1 second position in Extended Mode. This sample shows how |
| [QREncodeType](./qrencodetype/) | QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strong |
| [QRErrorLevel](./qrerrorlevel/) | Level of Reed-Solomon error correction. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. |
| [QRVersion](./qrversion/) | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. |
| [RectMicroQRVersion](./rectmicroqrversion/) | Version of RectMicroQR Code. From version R7x43 to version R17x139. |
| [SvgColorMode](./svgcolormode/) | Possible modes for filling color in svg file, RGB is default and supported by SVG 1.1. RGBA, HSL, HSLA is allowed in SVG |
| [TextAlignment](./textalignment/) | Text alignment. |
| [TwoDComponentType](./twodcomponenttype/) | Type of 2D component This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D co |

