---
title: "Global"
linktitle: "Global"
articleTitle: "Global"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Global enumerations and constants."
type: docs
weight: 20
url: /nodejs/global/
---

## Enumerations

| Enumeration | Description |
| --- | --- |
| [AddressType](./addresstype/) | Address type |
| [AutoSizeMode](./autosizemode/) | Specifies the different types of automatic sizing modes. Default value is AutoSizeMode.NONE. |
| [AztecEncodeMode](./aztecencodemode/) | Encoding mode for Aztec barcodes. |
| [AztecSymbolMode](./aztecsymbolmode/) | Specifies the Aztec symbol mode. |
| [BarCodeConfidence](./barcodeconfidence/) | Contains recognition confidence level |
| [BarCodeImageFormat](./barcodeimageformat/) | Specifies the file format of the image. |
| [BarcodeClassifications](./barcodeclassifications/) | BarcodeClassifications EncodeTypes classification |
| [BarcodeQualityMode](./barcodequalitymode/) | Mode which enables methods to recognize barcode elements with the selected quality. Barcode element with lower quality r |
| [BorderDashStyle](./borderdashstyle/) | Specifies the style of dashed border lines. |
| [ChecksumValidation](./checksumvalidation/) | Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must cont |
| [CodabarChecksumMode](./codabarchecksummode/) | Specifies the checksum algorithm for Codabar |
| [CodabarSymbol](./codabarsymbol/) | Specifies the start or stop symbol of the Codabar barcode specification. |
| [Code128EncodeMode](./code128encodemode/) | Encoding mode for Code128 barcodes. `Code 128` specification. Thos code demonstrates how to generate code 128 with diffe |
| [Code128SubType](./code128subtype/) | Contains types of Code128 subset |
| [CodeLocation](./codelocation/) | Codetext location |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Mode which enables or disables additional recognition of color barcodes on color images. This sample shows how to use Co |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | Defines the interpreting type(C_TABLE or N_TABLE) of customer information for AustralianPost BarCode. |
| [DataMatrixEccType](./datamatrixecctype/) | Specify the type of the ECC to encode. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | DataMatrix encoder's encoding mode, default to Auto This sample shows how to do codetext in Extended Mode. //Auto mode l |
| [DataMatrixVersion](./datamatrixversion/) | Specify the type of the ECC to encode. |
| [DecodeType](./decodetype/) | Specify the type of barcode to read. |
| [DeconvolutionMode](./deconvolutionmode/) | Deconvolution (image restorations) mode which defines level of image degradation. Originally deconvolution is a function |
| [DotCodeEncodeMode](./dotcodeencodemode/) | Encoding mode for DotCode barcodes. |
| [ECIEncodings](./eciencodings/) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [EnableChecksum](./enablechecksum/) | Enable checksum during generation for 1D barcodes. Default is treated as Yes for symbologies which must contain checksum |
| [EncodeTypes](./encodetypes/) | Specifies the type of barcode to encode. |
| [FontMode](./fontmode/) | Font size mode. |
| [FontStyle](./fontstyle/) | FontStyle classification |
| [GraphicsUnit](./graphicsunit/) | Specifies the unit of measure for the given data. |
| [HIBCLICDateFormat](./hibclicdateformat/) | Specifies the different types of date formats for HIBC LIC. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | HIBC PAS data location types. |
| [HIBCPASDataType](./hibcpasdatatype/) | HIBC PAS record's data types. |
| [HanXinEncodeMode](./hanxinencodemode/) | Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode charact |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Level of Reed-Solomon error correction. From low to high: L1, L2, L3, L4. |
| [HanXinVersion](./hanxinversion/) | Version of Han Xin Code. From Version01 - 23 x 23 modules to Version84 - 189 x 189 modules, increasing in steps of 2 mod |
| [ITF14BorderType](./itf14bordertype/) | ITF14 barcode's border type |
| [InverseImageMode](./inverseimagemode/) | Mode which enables or disables additional recognition of barcodes on images with inverted colors (luminance). This sampl |
| [MacroCharacter](./macrocharacter/) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. 05 Macro craracter is trans |
| [Mailmark2DType](./mailmark2dtype/) | 2D Mailmark Type defines size of Data Matrix barcode |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | Encoding mode for MaxiCode barcodes. |
| [MaxiCodeMode](./maxicodemode/) | Encoding mode for MaxiCode barcodes. |
| [MicroQRVersion](./microqrversion/) | Version of MicroQR Code. From M1 to M4. |
| [PatchFormat](./patchformat/) | PatchCode format. Choose PatchOnly to generate single PatchCode. Use page format to generate Patch page with PatchCodes  |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Pdf417 barcode's compation mode |
| [Pdf417EncodeMode](./pdf417encodemode/) | Pdf417 barcode encode mode |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | pdf417 barcode's error correction level, from level 0 to level 9, level 0 means no error correction, level 9 means best  |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Used to tell the encoder whether to add Macro PDF417 Terminator (codeword 922) to the segment. Applied only for Macro PD |
| [QREncodeMode](./qrencodemode/) | Encoding mode for QR barcodes. Example how to use ECI encoding generator = new BarcodeGenerator(EncodeTypes.QR, "12345TE |
| [QREncodeType](./qrencodetype/) | QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strong |
| [QRErrorLevel](./qrerrorlevel/) | Level of Reed-Solomon error correction. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. |
| [QRVersion](./qrversion/) | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR bill standard version |
| [QrExtCompactionMode](./qrextcompactionmode/) | Specifies QR compaction mode for codetext added by QrExtCodetextBuilder. |
| [RectMicroQRVersion](./rectmicroqrversion/) | Version of RectMicroQR Code. From version R7x43 to version R17x139. |
| [SvgColorMode](./svgcolormode/) | Possible modes for filling color in svg file, RGB is default and supported by SVG 1.1. RGBA, HSL, HSLA is allowed in SVG |
| [TextAlignment](./textalignment/) | Text alignment. |
| [TwoDComponentType](./twodcomponenttype/) | Type of 2D component This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D co |
| [USADriveIdCountry](./usadriveidcountry/) | Enum for Country Identification in the US Driver's License |
| [USADriveIdEyeColor](./usadriveideyecolor/) | Enum for Eye Color in the US Driver's License |
| [USADriveIdHairColor](./usadriveidhaircolor/) | Enum for Hair Color in the US Driver's License |
| [USADriveIdSex](./usadriveidsex/) | Enum for Sex field in the US Driver's License |
| [XDimensionMode](./xdimensionmode/) | Recognition mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. This sample shows  |
