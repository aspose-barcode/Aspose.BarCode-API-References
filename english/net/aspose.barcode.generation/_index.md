---
title: Aspose.BarCode.Generation
second_title: Aspose.BarCode for .NET API Reference
description: The **Aspose.BarCode.Generation** containing general classes for the implementation of BarCode generation functions.
type: docs
weight: 50
url: /net/aspose.barcode.generation/
---
The **Aspose.BarCode.Generation** containing general classes for the implementation of BarCode generation functions.

## Classes

| Class | Description |
| --- | --- |
| class [AustralianPostParameters](./australianpostparameters) | AustralianPost barcode parameters. |
| class [AztecParameters](./aztecparameters) | Aztec parameters. |
| class [BarcodeGenerator](./barcodegenerator) | BarcodeGenerator for backend barcode images generation. |
| class [BarcodeParameters](./barcodeparameters) | Barcode generation parameters. |
| class [BaseEncodeType](./baseencodetype) | Base class for SymbologyEncodeType. |
| class [BaseGenerationParameters](./basegenerationparameters) | Barcode image generation parameters. |
| class [BorderParameters](./borderparameters) | Barcode image border parameters |
| class [CaptionParameters](./captionparameters) | Caption parameters. |
| class [CodabarParameters](./codabarparameters) | Codabar parameters. |
| class [CodablockParameters](./codablockparameters) | Codablock parameters. |
| class [Code16KParameters](./code16kparameters) | Code16K parameters. |
| class [CodetextParameters](./codetextparameters) | Codetext parameters. |
| class [CouponParameters](./couponparameters) | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| class [DataBarParameters](./databarparameters) | Databar parameters. |
| class [DataMatrixParameters](./datamatrixparameters) | DataMatrix parameters. |
| class [DotCodeParameters](./dotcodeparameters) | DotCode parameters. |
| static class [EncodeTypes](./encodetypes) | Specifies the type of barcode to encode. |
| abstract class [ExtCodetextBuilder](./extcodetextbuilder) | Helper class for automatic codetext generation of the Extended Codetext Mode |
| class [FontUnit](./fontunit) | Defines a particular format for text, including font face, size, and style attributes where size in Unit value property. |
| class [ITFParameters](./itfparameters) | ITF parameters. |
| class [MaxiCodeParameters](./maxicodeparameters) | MaxiCode parameters. |
| class [Padding](./padding) | Paddings parameters. |
| class [PatchCodeParameters](./patchcodeparameters) | PatchCode parameters. |
| class [Pdf417Parameters](./pdf417parameters) | PDF417 parameters. Contains PDF417, MacroPDF417 and MicroPDF417 parameters. MacroPDF417 requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. MicroPDF417 in Structured Append mode (same as MacroPDF417 mode) requires two fields: Pdf417MacroFileID and Pdf417MacroSegmentID. All other fields are optional. |
| class [PostalParameters](./postalparameters) | Postal parameters. Used for Postnet, Planet. |
| class [QrExtCodetextBuilder](./qrextcodetextbuilder) | Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QrEncodeMode |
| class [QrParameters](./qrparameters) | QR parameters. |
| class [QrStructuredAppendParameters](./qrstructuredappendparameters) | QR structured append parameters. |
| class [SupplementParameters](./supplementparameters) | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| class [SymbologyEncodeType](./symbologyencodetype) | Symbology encode type. See EncodeTypes to get instance. |
| class [Unit](./unit) | Specifies the size value in different units (Pixel, Inches, etc.). |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [AutoSizeMode](./autosizemode) | Specifies the different types of automatic sizing modes. |
| enum [AztecSymbolMode](./aztecsymbolmode) | Specifies the Aztec symbol mode. |
| enum [BarcodeClassifications](./barcodeclassifications) | Symbology classification |
| enum [BarCodeImageFormat](./barcodeimageformat) | Specifies the file format of the image. |
| enum [BorderDashStyle](./borderdashstyle) | Specifies the style of dashed border lines. |
| enum [CodabarChecksumMode](./codabarchecksummode) | Specifies the checksum algorithm for Codabar |
| enum [CodabarSymbol](./codabarsymbol) | Specifies the start or stop symbol of the Codabar barcode specification. |
| enum [Code128Emulation](./code128emulation) | Function codewords for Code 128 emulation. Applied for MicroPDF417 only. Ignored for PDF417 and MacroPDF417 barcodes. |
| enum [CodeLocation](./codelocation) | Codetext location |
| enum [DataMatrixEccType](./datamatrixecctype) | Specify the type of the ECC to encode. |
| enum [DataMatrixEncodeMode](./datamatrixencodemode) | DataMatrix encoder's encoding mode, default to Auto |
| enum [ECIEncodings](./eciencodings) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Currently, it is used only for QR 2D barcode. |
| enum [EnableChecksum](./enablechecksum) | Enable checksum during generation for 1D barcodes. |
| enum [FontMode](./fontmode) | Font size mode. |
| enum [ITF14BorderType](./itf14bordertype) | ITF14 border type of barcode |
| enum [MacroCharacter](./macrocharacter) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is translated to "[)&gt;\u001E05\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. 06 Macro craracter is translated to "[)&gt;\u001E06\u001D" as decoded data header and "\u001E\u0004" as decoded data trailer. |
| enum [PatchFormat](./patchformat) | PatchCode format. Choose PatchOnly to generate single PatchCode. Use page format to generate Patch page with PatchCodes as borders |
| enum [Pdf417CompactionMode](./pdf417compactionmode) | Pdf417 barcode compaction mode |
| enum [Pdf417ErrorLevel](./pdf417errorlevel) | pdf417 barcode's error correction level, from level 0 to level 9, level 0 means no error correction, level 9 means best error correction |
| enum [QREncodeMode](./qrencodemode) | Encoding mode for QR barcodes. It is recommended to Use Auto with CodeTextEncoding = Encoding.UTF8 for Latin symbols or digits and Utf8BOM for Unicode symbols. |
| enum [QREncodeType](./qrencodetype) | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. ForceMicroQR is used for strongly MicroQR symbol generation if it is possible. |
| enum [QRErrorLevel](./qrerrorlevel) | Level of Reed-Solomon error correction. From low to high: LevelL, LevelM, LevelQ, LevelH. |
| enum [QRVersion](./qrversion) | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. |
| enum [TextAlignment](./textalignment) | Text alignment. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
