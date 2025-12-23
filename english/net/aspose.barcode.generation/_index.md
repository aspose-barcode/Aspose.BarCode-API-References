---
title: Aspose.BarCode.Generation
second_title: Aspose.BarCode for .NET API Reference
description: The Aspose.BarCode.Generation containing general classes for the implementation of BarCode generation functions
type: docs
weight: 50
url: /net/aspose.barcode.generation/
---
The **Aspose.BarCode.Generation** containing general classes for the implementation of BarCode generation functions.

## Classes

| Class | Description |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost barcode parameters. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Extended codetext generator for Aztec barcodes for ExtendedCodetext Mode of AztecEncodeMode |
| [AztecParameters](./aztecparameters/) | Aztec parameters. |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator for backend barcode images generation. |
| [BarcodeParameters](./barcodeparameters/) | Barcode generation parameters. |
| [BaseEncodeType](./baseencodetype/) | Base class for SymbologyEncodeType. |
| [BaseGenerationParameters](./basegenerationparameters/) | Barcode image generation parameters. |
| [BorderParameters](./borderparameters/) | Barcode image border parameters |
| [CaptionParameters](./captionparameters/) | Caption parameters. |
| [CMYKColor](./cmykcolor/) | Class for CMYK color. Null means CMYK is not used, default RGB color is in use. |
| [CodabarParameters](./codabarparameters/) | Codabar parameters. |
| [CodablockParameters](./codablockparameters/) | Codablock parameters. |
| [Code128Parameters](./code128parameters/) | Code128 parameters. |
| [Code16KParameters](./code16kparameters/) | Code16K parameters. |
| [CodetextParameters](./codetextparameters/) | Codetext parameters. |
| [CouponParameters](./couponparameters/) | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters/) | Databar parameters. |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of EncodeMode |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix parameters. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode |
| [DotCodeParameters](./dotcodeparameters/) | DotCode parameters. |
| [EncodeTypes](./encodetypes/) | Specifies the type of barcode to encode. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Helper class for automatic codetext generation of the Extended Codetext Mode |
| [FontUnit](./fontunit/) | Defines a particular format for text, including font face, size, and style attributes where size in Unit value property. |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite bar parameters. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Extended codetext generator for Han Xin Code for Extended Mode of EncodeMode |
| [HanXinParameters](./hanxinparameters/) | Han Xin parameters. |
| [HslaColor](./hslacolor/) | Class for representing HSLA color (Hue, Saturation, Lightness, Alpha) |
| [ImageParameters](./imageparameters/) | Image parameters. |
| [ITFParameters](./itfparameters/) | ITF parameters. |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode parameters. |
| [Padding](./padding/) | Paddings parameters. |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode parameters. |
| [Pdf417Parameters](./pdf417parameters/) | PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. |
| [PdfParameters](./pdfparameters/) | PDF parameters. |
| [PostalParameters](./postalparameters/) | Postal parameters. Used for Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of EncodeMode |
| [QrParameters](./qrparameters/) | QR parameters. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR structured append parameters. |
| [SupplementParameters](./supplementparameters/) | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | SVG parameters. |
| [SymbologyEncodeType](./symbologyencodetype/) | Symbology encode type. See EncodeTypes to get instance. |
| [Unit](./unit/) | Specifies the size value in different units (Pixel, Inches, etc.). |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [AutoSizeMode](./autosizemode/) | Specifies the different types of automatic sizing modes. |
| [AztecEncodeMode](./aztecencodemode/) | Encoding mode for Aztec barcodes. |
| [AztecSymbolMode](./aztecsymbolmode/) | Specifies the Aztec symbol mode. |
| [BarcodeClassifications](./barcodeclassifications/) | Symbology classification |
| [BarCodeImageFormat](./barcodeimageformat/) | Specifies the file format of the image. |
| [BorderDashStyle](./borderdashstyle/) | Specifies the style of dashed border lines. |
| [CodabarChecksumMode](./codabarchecksummode/) | Specifies the checksum algorithm for Codabar |
| [CodabarSymbol](./codabarsymbol/) | Specifies the start or stop symbol of the Codabar barcode specification. |
| [Code128EncodeMode](./code128encodemode/) | Encoding mode for Code128 barcodes. [Code 128](https://en.wikipedia.org/wiki/Code_128) specification. |
| [CodeLocation](./codelocation/) | Codetext location |
| [DataMatrixEccType](./datamatrixecctype/) | Specify the type of the ECC to encode. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | DataMatrix encoder's encoding mode, default to Auto |
| [DataMatrixVersion](./datamatrixversion/) | Specify the type of the ECC to encode. |
| [DotCodeEncodeMode](./dotcodeencodemode/) | Encoding mode for DotCode barcodes. |
| [ECIEncodings](./eciencodings/) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. |
| [EnableChecksum](./enablechecksum/) | Enable checksum during generation for 1D barcodes. |
| [FontMode](./fontmode/) | Font size mode. |
| [HanXinEncodeMode](./hanxinencodemode/) | Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters. |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Level of Reed-Solomon error correction. From low to high: L1, L2, L3, L4. |
| [HanXinVersion](./hanxinversion/) | Version of Han Xin Code. From Version01 - 23 x 23 modules to Version84 - 189 x 189 modules, increasing in steps of 2 modules per side. |
| [ITF14BorderType](./itf14bordertype/) | ITF14 border type of barcode |
| [MacroCharacter](./macrocharacter/) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to "[)&gt;\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. 06 Macro craracter is translated to "[)&gt;\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | Encoding mode for MaxiCode barcodes. |
| [MaxiCodeMode](./maxicodemode/) | Encoding mode for MaxiCode barcodes. |
| [MicroQRVersion](./microqrversion/) | Version of MicroQR Code. From M1 to M4. |
| [PatchFormat](./patchformat/) | PatchCode format. Choose PatchOnly to generate single PatchCode. Use page format to generate Patch page with PatchCodes as borders |
| [Pdf417EncodeMode](./pdf417encodemode/) | Pdf417 barcode encode mode |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | pdf417 barcode's error correction level, from level 0 to level 9, level 0 means no error correction, level 8 means best error correction |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PDF417. |
| [QREncodeMode](./qrencodemode/) | Encoding mode for QR barcodes. |
| [QREncodeType](./qrencodetype/) | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. ForceMicroQR is used for strongly MicroQR symbol generation if it is possible. |
| [QRErrorLevel](./qrerrorlevel/) | Level of Reed-Solomon error correction. From low to high: LevelL, LevelM, LevelQ, LevelH. |
| [QRVersion](./qrversion/) | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. |
| [RectMicroQRVersion](./rectmicroqrversion/) | Version of RectMicroQR Code. From version R7x43 to version R17x139. |
| [SvgColorMode](./svgcolormode/) | Possible modes for filling color in svg file, RGB is default and supported by SVG 1.1. RGBA, HSL, HSLA is allowed in SVG 2.0 standard. Even in RGB opacity will be set through "fill-opacity" parameter |
| [TextAlignment](./textalignment/) | Text alignment. |
| [TwoDComponentType](./twodcomponenttype/) | Type of 2D component |


