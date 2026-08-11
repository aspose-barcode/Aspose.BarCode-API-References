---
title: "aspose_barcode.generation"
linktitle: "aspose_barcode.generation"
second_title: "Aspose.BarCode for Python via Java"
description: "The aspose_barcode.generation namespace offers classes and enums for configuring and creating a wide variety of barcode images."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/
---

## aspose_barcode.generation module

Use these types to define generation parameters such as symbology settings, visual styling, and output options, enabling precise control over barcode rendering in Python via Java. The namespace includes specialized parameter objects for specific standards like Australian Post, Aztec, and caption handling, as well as the core BarcodeGenerator class.

## Classes

| Class | Description |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost barcode parameters. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Extended codetext generator for Aztec barcodes for ExtendedCodetext Mode of AztecEncodeMode Use TwoDDisplayText property |
| [AztecParameters](./aztecparameters/) | Aztec parameters. |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator for backend barcode images generation. Supported symbologies: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Barcode generation parameters. |
| [BaseGenerationParameters](./basegenerationparameters/) | Barcode image generation parameters. |
| [BorderParameters](./borderparameters/) | Barcode image border parameters. |
| [CaptionParameters](./captionparameters/) | Caption parameters. |
| [CMYKColor](./cmykcolor/) |  |
| [CodabarParameters](./codabarparameters/) | Codabar parameters. |
| [CodablockParameters](./codablockparameters/) | Codablock parameters. |
| [Code128Parameters](./code128parameters/) | Code128 parameters. |
| [Code16KParameters](./code16kparameters/) | Code16K parameters. |
| [CodetextParameters](./codetextparameters/) | Codetext parameters. |
| [CouponParameters](./couponparameters/) | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters/) | Databar parameters. |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of DataMatrixEncodeMode. |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix parameters. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode. |
| [DotCodeParameters](./dotcodeparameters/) | DotCode parameters. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Helper class for automatic codetext generation of the Extended Codetext Mode. |
| [FontUnit](./fontunit/) | Defines a particular format for text, including font face, size, and style attributes where size in Unit value property. |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite bar parameters. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Extended codetext generator for Han Xin Code for Extended Mode of HanXinEncodeMode. |
| [HanXinParameters](./hanxinparameters/) | Han Xin parameters. |
| [HslaColor](./hslacolor/) | Class for representing HSLA color (Hue, Saturation, Lightness, Alpha) |
| [ImageParameters](./imageparameters/) | Image parameters. |
| [ITFParameters](./itfparameters/) | ITF parameters. |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode Use TwoDDisplayText pr |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode parameters. |
| [Padding](./padding/) | Paddings parameters. |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode parameters. |
| [Pdf417Parameters](./pdf417parameters/) | PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fie |
| [PdfParameters](./pdfparameters/) |  |
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
| [AutoSizeMode](./autosizemode/) | Specifies the different types of automatic sizing modes. Default value is AutoSizeMode.NONE. This sample shows how to cr |
| [AztecEncodeMode](./aztecencodemode/) |  |
| [AztecSymbolMode](./aztecsymbolmode/) | Specifies the Aztec symbol mode. |
| [BarcodeClassifications](./barcodeclassifications/) | BarcodeClassifications EncodeTypes classification. |
| [BarCodeImageFormat](./barcodeimageformat/) | Specifies the file format of the image. |
| [BorderDashStyle](./borderdashstyle/) | Specifies the style of dashed border lines. |
| [CodabarChecksumMode](./codabarchecksummode/) | Specifies the checksum algorithm for Codabar. |
| [CodabarSymbol](./codabarsymbol/) | Specifies the start or stop symbol of the Codabar barcode specification. |
| [Code128EncodeMode](./code128encodemode/) | Encoding mode for Code128 barcodes. specification. This code demonstrates how to generate code 128 with different encodi |
| [CodeLocation](./codelocation/) | Codetext location. |
| [DataMatrixEccType](./datamatrixecctype/) | Specify the type of the ECC to encode. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | DataMatrix encoder's encoding mode, default to Auto. This sample shows how to do codetext in Extended Mode. |
| [DataMatrixVersion](./datamatrixversion/) | Specify the type of the ECC to encode. |
| [DotCodeEncodeMode](./dotcodeencodemode/) | Encoding mode for DotCode barcodes. |
| [ECIEncodings](./eciencodings/) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [EnableChecksum](./enablechecksum/) | DEFAULT = 0 - If checksum is required by the specification - it will be attached. YES = 1 - Always use checksum if possi |
| [EncodeTypes](./encodetypes/) | Specifies the type of barcode to encode. |
| [FontMode](./fontmode/) | Font size mode. |
| [FontStyle](./fontstyle/) | Specifies style information applied to text. |
| [GraphicsUnit](./graphicsunit/) | Specifies the unit of measure for the given data. WORLD = 0 - Specifies the world coordinate system unit as the unit of  |
| [HanXinEncodeMode](./hanxinencodemode/) | Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode charact |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Level of Reed-Solomon error correction. From low to high = L1, L2, L3, L4. |
| [HanXinVersion](./hanxinversion/) | Version of Han Xin Code. From Version01 - 23 x 23 modules to Version84 - 189 x 189 modules, increasing in steps of 2 mod |
| [ITF14BorderType](./itf14bordertype/) | ITF14 barcode's border type. |
| [MacroCharacter](./macrocharacter/) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is trans |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | Encoding mode for MaxiCode barcodes. codetext = "犬Right狗" generator = BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext)  |
| [MaxiCodeMode](./maxicodemode/) | Encoding mode for MaxiCode barcodes. This sample shows how to genereate MaxiCode barcodes using ComplexBarcodeGenerator |
| [MicroQRVersion](./microqrversion/) | Version of MicroQR Code. From M1 to M4. |
| [PatchFormat](./patchformat/) | PatchCode format. Choose PatchOnly to generate single PatchCode. Use page format to generate Patch page with PatchCodes  |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Pdf417 barcode's compation mode. |
| [Pdf417EncodeMode](./pdf417encodemode/) | Pdf417 barcode encode mode. |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | pdf417 barcode's error correction level, from level 0 to level 9, level 0 means no error correction, level 9 means best  |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [QREncodeMode](./qrencodemode/) | Encoding mode for QR barcodes. |
| [QREncodeType](./qrencodetype/) | QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strong |
| [QRErrorLevel](./qrerrorlevel/) | Level of Reed-Solomon error correction. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. |
| [QrExtCompactionMode](./qrextcompactionmode/) | Specifies QR compaction mode for codetext added by QrExtCodetextBuilder. |
| [QRVersion](./qrversion/) | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. |
| [RectMicroQRVersion](./rectmicroqrversion/) |  |
| [SvgColorMode](./svgcolormode/) | Possible modes for filling color in svg file, RGB is default and supported by SVG 1.1. RGBA, HSL, HSLA is allowed in SVG |
| [TextAlignment](./textalignment/) | Text alignment. |
| [TwoDComponentType](./twodcomponenttype/) | Type of 2D component This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D co |

