---
title: "aspose.barcode"
linktitle: "aspose.barcode"
articleTitle: "aspose.barcode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "The aspose.barcode namespace provides classes and enums to configure and generate various barcode types, including postal, Aztec, and extended formats."
type: docs
weight: 10
url: /nodejs/aspose.barcode/
---

This reference page lists all members of the aspose.barcode namespace, such as Address, AlternativeScheme, and the parameter classes for Australian Post, Aztec, and extended barcode configurations. Use these types to fine‑tune barcode generation and integrate postal standards into your Node.js applications.

## Classes

| Class | Description |
| --- | --- |
| [Address](./address/) | Address of creditor or debtor. You can either set street, house number, postal code and town (type structured address) o |
| [AlternativeScheme](./alternativescheme/) | Alternative payment scheme instructions |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbolog |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost barcode parameters. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Extended codetext generator for Aztec barcodes for ExtendedCodetext Mode of AztecEncodeMode Use TwoDDisplayText property |
| [AztecExtendedParameters](./aztecextendedparameters/) | Stores special data of Aztec recognized barcode This sample shows how to get Aztec raw values let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Aztec parameters. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Stores extended parameters of recognized barcode |
| [BarCodeReader](./barcodereader/) | BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operatio |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Represents the recognized barcode's region and barcode angle |
| [BarCodeResult](./barcoderesult/) | Stores recognized barcode data like SingleDecodeType type, `string` codetext, BarCodeRegionParameters region and other p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator for backend barcode images generation. supported symbologies: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Barcode generation parameters. |
| [BarcodeSettings](./barcodesettings/) | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [BaseGenerationParameters](./basegenerationparameters/) | Barcode image generation parameters. |
| [BorderParameters](./borderparameters/) | Barcode image border parameters |
| [CMYKColor](./cmykcolor/) | Class for CMYK color. A null instance means CMYK is not used, and default RGB color is in use. |
| [CaptionParameters](./captionparameters/) | Caption parameters. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Stores a Codabar additional information of recognized barcode |
| [CodabarParameters](./codabarparameters/) | Codabar parameters. |
| [CodablockParameters](./codablockparameters/) | Codablock parameters. |
| [Code128DataPortion](./code128dataportion/) | Contains the data of subtype for Code128 type barcode |
| [Code128ExtendedParameters](./code128extendedparameters/) | Stores special data of Code128 recognized barcode Represents the recognized barcode's region and barcode angle |
| [Code128Parameters](./code128parameters/) | Code128 parameters. |
| [Code16KParameters](./code16kparameters/) | Code16K parameters. |
| [CodetextParameters](./codetextparameters/) | Codetext parameters. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation. |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader decodes codetext to specified complex barcode type. |
| [CouponParameters](./couponparameters/) | Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Stores a DataBar additional information of recognized barcode |
| [DataBarParameters](./databarparameters/) | Databar parameters. |
| [DataElement](./dataelement/) | Represents a jurisdiction-specific data field used in documents, for example ElementID = "ZVA" with Value = "01". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of DataMatrixEncodeMode //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Stores special data of DataMatrix recognized barcode This sample shows how to get DataMatrix raw values let generator =  |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix parameters. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Stores special data of DotCode recognized barcode This sample shows how to get DotCode raw values |
| [DotCodeParameters](./dotcodeparameters/) | DotCode parameters. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Helper class for automatic codetext generation of the Extended Codetext Mode |
| [FontUnit](./fontunit/) | Defines a particular format for text, including font face, size, and style attributes where size in Unit value property. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Stores special data of `GS1 Composite Bar ` recognized barcode |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite bar parameters. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary and secodary data. This samp |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Base class for encoding and decoding the text embedded in the HIBC LIC code. This sample shows how to decode raw HIBC LI |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary data. This sample shows how  |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Class for encoding and decoding the text embedded in the HIBC LIC code which stores seconday data. |
| [HIBCPASCodetext](./hibcpascodetext/) | Class for encoding and decoding the text embedded in the HIBC PAS code. |
| [HIBCPASRecord](./hibcpasrecord/) | Class for storing HIBC PAS record. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Extended codetext generator for Han Xin Code for Extended Mode of HanXinEncodeMode //Extended codetext mode //create cod |
| [HanXinParameters](./hanxinparameters/) | Han Xin parameters. |
| [HslaColor](./hslacolor/) | Class for representing HSLA color (Hue, Saturation, Lightness, Alpha) |
| [IComplexCodetext](./icomplexcodetext/) | Interface for complex codetext used with ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | ITF parameters. |
| [ImageParameters](./imageparameters/) | Image parameters. |
| [License](./license/) | Provides methods to license the component. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code. |
| [MailmarkCodetext](./mailmarkcodetext/) | Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code. |
| [MandatoryFields](./mandatoryfields/) | Mandatory elements (fields) of the card |
| [MaxiCodeCodetext](./maxicodecodetext/) | Base class for encoding and decoding the text embedded in the MaxiCode code. This sample shows how to decode raw MaxiCod |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Class for encoding and decoding the text embedded in the MaxiCode code for modes 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Class for encoding and decoding the text embedded in the MaxiCode code for modes 3. This sample shows how to encode and  |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode Use TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Stores a MaxiCode additional information of recognized barcode |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode parameters. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Class for encoding and decoding standart second message for MaxiCode barcode. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | Class for encoding and decoding standart second message for MaxiCode barcode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Class for encoding and decoding structured second message for MaxiCode barcode. |
| [OneDExtendedParameters](./onedextendedparameters/) | Stores special data of 1D recognized barcode like separate codetext and checksum |
| [OptionalFields](./optionalfields/) | Optional elements (fields) of the card |
| [Padding](./padding/) | Paddings parameters. |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode parameters. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Stores a MacroPdf417 metadata information of recognized barcode |
| [Pdf417Parameters](./pdf417parameters/) | PDF417 parameters. Contains PDF417, MacroPDF417, MicroPDF417 and GS1MicroPdf417 parameters. MacroPDF417 requires two fie |
| [PdfParameters](./pdfparameters/) | PDF parameters wrapper. Expects an underlying `mwObject` instance that provides the corresponding getter/setter methods  |
| [PostalParameters](./postalparameters/) | Postal parameters. Used for Postnet, Planet. |
| [PrimaryData](./primarydata/) | Class for storing HIBC LIC primary data. |
| [QRExtendedParameters](./qrextendedparameters/) | Stores a QR Structured Append information of recognized barcode |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QREncodeMode Use Display2DText property of B |
| [QrParameters](./qrparameters/) | QR parameters. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR structured append parameters. |
| [Quadrangle](./quadrangle/) | Stores a set of four Points that represent a Quadrangle region. |
| [QualitySettings](./qualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [RecognitionAbortedException](./recognitionabortedexception/) | Represents recognition abort exception which is thrown in timeout exceeding during recognition with BarCodeReader. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Class for storing HIBC LIC secondary and additional data. |
| [SubfileProperties](./subfileproperties/) | USA DL subfile properties, offset and length are set automatically. |
| [SupplementParameters](./supplementparameters/) | Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | SVG parameters. |
| [SwissQRBill](./swissqrbill/) | SwissQR bill data |
| [SwissQRCodetext](./swissqrcodetext/) | Class for encoding and decoding the text embedded in the SwissQR code. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Class for encoding and decoding the text embedded in the USA Driving License PDF417 code. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Class for Jurisdiction specific fields for USA DL |
| [Unit](./unit/) | Specifies the size value in different units (Pixel, Inches, etc.). |
