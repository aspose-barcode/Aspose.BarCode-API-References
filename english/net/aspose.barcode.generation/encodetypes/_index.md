---
title: Class EncodeTypes
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.EncodeTypes class. Specifies the type of barcode to encode
type: docs
weight: 1210
url: /net/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class

Specifies the type of barcode to encode.

```csharp
public static class EncodeTypes
```

## Properties

| Name | Description |
| --- | --- |
| static [AllEncodeTypes](../../aspose.barcode.generation/encodetypes/allencodetypes/) { get; } | Specifies that data will be checked with all available symbologies. |

## Methods

| Name | Description |
| --- | --- |
| static [GetNames](../../aspose.barcode.generation/encodetypes/getnames/)() | Retrieves an array of the names of the encode types. |
| static [Parse](../../aspose.barcode.generation/encodetypes/parse/)(string, out BaseEncodeType) | Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../../aspose.barcode.generation/encodetypes/tryparse/)(string, out BaseEncodeType) | Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [AustralianPosteParcel](../../aspose.barcode.generation/encodetypes/australianposteparcel/) | Specifies that the data should be encoded with **Australian Post Domestic eParcel Barcode** barcode specification |
| static readonly [AustraliaPost](../../aspose.barcode.generation/encodetypes/australiapost/) | Represents Australia Post Customer BarCode |
| static readonly [Aztec](../../aspose.barcode.generation/encodetypes/aztec/) | Specifies that the data should be encoded with **Aztec** barcode specification |
| static readonly [Codabar](../../aspose.barcode.generation/encodetypes/codabar/) | Specifies that the data should be encoded with **CODABAR** barcode specification |
| static readonly [CodablockF](../../aspose.barcode.generation/encodetypes/codablockf/) | Specifies that the data should be encoded with **Codablock-F** barcode specification. |
| static readonly [Code11](../../aspose.barcode.generation/encodetypes/code11/) | Specifies that the data should be encoded with **CODE 11** barcode specification |
| static readonly [Code128](../../aspose.barcode.generation/encodetypes/code128/) | Specifies that the data should be encoded with **CODE 128** barcode specification |
| static readonly [Code16K](../../aspose.barcode.generation/encodetypes/code16k/) | Represents Code 16K barcode. |
| static readonly [Code32](../../aspose.barcode.generation/encodetypes/code32/) | Specifies that the data should be encoded with **Code32** barcode specification |
| static readonly [Code39](../../aspose.barcode.generation/encodetypes/code39/) | Specifies that the data should be encoded with **Code 39** basic charset barcode specification: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.generation/encodetypes/code39fullascii/) | Specifies that the data should be encoded with **Code 39** full ASCII charset barcode specification: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.generation/encodetypes/code93/) | Specifies that the data should be encoded with **CODE 93** barcode specification |
| static readonly [DatabarExpanded](../../aspose.barcode.generation/encodetypes/databarexpanded/) | Represents GS1 Databar expanded barcode. |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.generation/encodetypes/databarexpandedstacked/) | Represents GS1 Databar expanded stacked barcode. |
| static readonly [DatabarLimited](../../aspose.barcode.generation/encodetypes/databarlimited/) | Represents GS1 Databar limited barcode. |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.generation/encodetypes/databaromnidirectional/) | Specifies that the data should be encoded with **GS1 Databar omni-directional** barcode specification. |
| static readonly [DatabarStacked](../../aspose.barcode.generation/encodetypes/databarstacked/) | Represents GS1 Databar stacked barcode. |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.generation/encodetypes/databarstackedomnidirectional/) | Represents GS1 Databar stacked omni-directional barcode. |
| static readonly [DatabarTruncated](../../aspose.barcode.generation/encodetypes/databartruncated/) | Specifies that the data should be encoded with **GS1 Databar truncated** barcode specification. |
| static readonly [DataLogic2of5](../../aspose.barcode.generation/encodetypes/datalogic2of5/) | Specifies that the data should be encoded with **DataLogic 2 of 5** barcode specification |
| static readonly [DataMatrix](../../aspose.barcode.generation/encodetypes/datamatrix/) | 2D barcode symbology DataMatrix |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.generation/encodetypes/deutschepostidentcode/) | Represents Deutsch Post barcode, This Symbology is also known as Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.generation/encodetypes/deutschepostleitcode/) | Represents Deutsch Post Leitcode Barcode,also known as German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static readonly [DotCode](../../aspose.barcode.generation/encodetypes/dotcode/) | Specifies that the data should be encoded with **DotCode** barcode specification |
| static readonly [DutchKIX](../../aspose.barcode.generation/encodetypes/dutchkix/) | Specifies that the data should be encoded with **Dutch KIX** barcode specification |
| static readonly [EAN13](../../aspose.barcode.generation/encodetypes/ean13/) | Specifies that the data should be encoded with **EAN-13** barcode specification |
| static readonly [EAN14](../../aspose.barcode.generation/encodetypes/ean14/) | Specifies that the data should be encoded with **EAN14** barcode specification |
| static readonly [EAN8](../../aspose.barcode.generation/encodetypes/ean8/) | Specifies that the data should be encoded with **EAN-8** barcode specification |
| static readonly [GS1Aztec](../../aspose.barcode.generation/encodetypes/gs1aztec/) | Specifies that the data should be encoded with **GS1 Aztec** barcode specification. The codetext must contains parentheses for AI. |
| static readonly [GS1CodablockF](../../aspose.barcode.generation/encodetypes/gs1codablockf/) | Specifies that the data should be encoded with **GS1 Codablock-F** barcode specification. The codetext must contains parentheses for AI. |
| static readonly [GS1Code128](../../aspose.barcode.generation/encodetypes/gs1code128/) | Specifies that the data should be encoded with **GS1 Code 128** barcode specification. The codetext must contains parentheses for AI. |
| static readonly [GS1CompositeBar](../../aspose.barcode.generation/encodetypes/gs1compositebar/) | Specifies that the data should be encoded with **GS1 Composite Bar** barcode specification. The codetext must contains parentheses for AI. 1D codetext and 2D codetext must be separated with symbol '/' |
| static readonly [GS1DataMatrix](../../aspose.barcode.generation/encodetypes/gs1datamatrix/) | 2D barcode symbology DataMatrix with GS1 string format |
| static readonly [GS1DotCode](../../aspose.barcode.generation/encodetypes/gs1dotcode/) | Specifies that the data should be encoded with **GS1 DotCode** barcode specification. The codetext must contains parentheses for AI. |
| static readonly [GS1HanXin](../../aspose.barcode.generation/encodetypes/gs1hanxin/) | 2D barcode symbology HanXin with GS1 string format |
| static readonly [GS1MicroPdf417](../../aspose.barcode.generation/encodetypes/gs1micropdf417/) | Specifies that the data should be encoded with **GS1MicroPdf417** barcode specification |
| static readonly [GS1QR](../../aspose.barcode.generation/encodetypes/gs1qr/) | 2D barcode symbology QR with GS1 string format |
| static readonly [HanXin](../../aspose.barcode.generation/encodetypes/hanxin/) | Specifies that the data should be encoded with **Han Xin** barcode specification |
| static readonly [HIBCAztecLIC](../../aspose.barcode.generation/encodetypes/hibcazteclic/) | Specifies that the data should be encoded with **HIBC LIC Aztec** barcode specification. |
| static readonly [HIBCAztecPAS](../../aspose.barcode.generation/encodetypes/hibcaztecpas/) | Specifies that the data should be encoded with **HIBC PAS Aztec** barcode specification. |
| static readonly [HIBCCode128LIC](../../aspose.barcode.generation/encodetypes/hibccode128lic/) | Specifies that the data should be encoded with **HIBC LIC Code128** barcode specification. |
| static readonly [HIBCCode128PAS](../../aspose.barcode.generation/encodetypes/hibccode128pas/) | Specifies that the data should be encoded with **HIBC PAS Code128** barcode specification. |
| static readonly [HIBCCode39LIC](../../aspose.barcode.generation/encodetypes/hibccode39lic/) | Specifies that the data should be encoded with **HIBC LIC Code39** barcode specification. |
| static readonly [HIBCCode39PAS](../../aspose.barcode.generation/encodetypes/hibccode39pas/) | Specifies that the data should be encoded with **HIBC PAS Code39** barcode specification. |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.generation/encodetypes/hibcdatamatrixlic/) | Specifies that the data should be encoded with **HIBC LIC DataMatrix** barcode specification. |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.generation/encodetypes/hibcdatamatrixpas/) | Specifies that the data should be encoded with **HIBC PAS DataMatrix** barcode specification. |
| static readonly [HIBCQRLIC](../../aspose.barcode.generation/encodetypes/hibcqrlic/) | Specifies that the data should be encoded with **HIBC LIC QR** barcode specification. |
| static readonly [HIBCQRPAS](../../aspose.barcode.generation/encodetypes/hibcqrpas/) | Specifies that the data should be encoded with **HIBC PAS QR** barcode specification. |
| static readonly [IATA2of5](../../aspose.barcode.generation/encodetypes/iata2of5/) | Represents IATA 2 of 5 barcode.IATA (International Air Transport Assosiation) uses this barcode for the management of air cargo. |
| static readonly [Interleaved2of5](../../aspose.barcode.generation/encodetypes/interleaved2of5/) | Specifies that the data should be encoded with **INTERLEAVED 2 of 5** barcode specification |
| static readonly [ISBN](../../aspose.barcode.generation/encodetypes/isbn/) | Specifies that the data should be encoded with **ISBN** barcode specification |
| static readonly [ISMN](../../aspose.barcode.generation/encodetypes/ismn/) | Specifies that the data should be encoded with **ISMN** barcode specification |
| static readonly [ISSN](../../aspose.barcode.generation/encodetypes/issn/) | Specifies that the data should be encoded with **ISSN** barcode specification |
| static readonly [ItalianPost25](../../aspose.barcode.generation/encodetypes/italianpost25/) | Represents Italian Post 25 barcode. |
| static readonly [ITF14](../../aspose.barcode.generation/encodetypes/itf14/) | Specifies that the data should be encoded with **ITF14** barcode specification |
| static readonly [ITF6](../../aspose.barcode.generation/encodetypes/itf6/) | Represents ITF-6 Barcode. |
| static readonly [MacroPdf417](../../aspose.barcode.generation/encodetypes/macropdf417/) | Specifies that the data should be encoded with **MacroPdf417** barcode specification |
| static readonly [Mailmark](../../aspose.barcode.generation/encodetypes/mailmark/) | Represents Royal Mail Mailmark barcode. |
| static readonly [Matrix2of5](../../aspose.barcode.generation/encodetypes/matrix2of5/) | Represents Matrix 2 of 5 BarCode |
| static readonly [MaxiCode](../../aspose.barcode.generation/encodetypes/maxicode/) | Specifies that the data should be encoded with **MaxiCode** barcode specification |
| static readonly [MicroPdf417](../../aspose.barcode.generation/encodetypes/micropdf417/) | Specifies that the data should be encoded with **MicroPdf417** barcode specification |
| static readonly [MicroQR](../../aspose.barcode.generation/encodetypes/microqr/) | Specifies that the data should be encoded with **MicroQR Code** barcode specification |
| static readonly [MSI](../../aspose.barcode.generation/encodetypes/msi/) | Specifies that the data should be encoded with **MSI Plessey** barcode specification |
| static readonly [None](../../aspose.barcode.generation/encodetypes/none/) | Unspecified encode type. |
| static readonly [OneCode](../../aspose.barcode.generation/encodetypes/onecode/) | Specifies that the data should be encoded with USPS **OneCode** barcode specification |
| static readonly [OPC](../../aspose.barcode.generation/encodetypes/opc/) | Represents OPC(Optical Product Code) Barcode,also known as , VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| static readonly [PatchCode](../../aspose.barcode.generation/encodetypes/patchcode/) | Represents Patch code barcode |
| static readonly [Pdf417](../../aspose.barcode.generation/encodetypes/pdf417/) | Specifies that the data should be encoded with **Pdf417** barcode specification |
| static readonly [Pharmacode](../../aspose.barcode.generation/encodetypes/pharmacode/) | Represents Pharmacode barcode. |
| static readonly [Planet](../../aspose.barcode.generation/encodetypes/planet/) | Specifies that the data should be encoded with **Planet** barcode specification |
| static readonly [Postnet](../../aspose.barcode.generation/encodetypes/postnet/) | Specifies that the data should be encoded with **Postnet** barcode specification |
| static readonly [PZN](../../aspose.barcode.generation/encodetypes/pzn/) | Represents PZN barcode.This Symbology is also known as Pharmacy central number, Pharmazentralnummer. PZN7 and PZN8 are supported. PZN7 is generated from 6 or less digits, like "123456". PZN8 is generated from 7 or more digits, like "1234567". Provided last checksum digit is ignored and generated by the barcode engine. |
| static readonly [QR](../../aspose.barcode.generation/encodetypes/qr/) | Specifies that the data should be encoded with **QR Code** barcode specification |
| static readonly [RectMicroQR](../../aspose.barcode.generation/encodetypes/rectmicroqr/) | Specifies that the data should be encoded with **RectMicroQR (rMQR) Code** barcode specification |
| static readonly [RM4SCC](../../aspose.barcode.generation/encodetypes/rm4scc/) | Represents RM4SCC barcode. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| static readonly [SCC14](../../aspose.barcode.generation/encodetypes/scc14/) | Specifies that the data should be encoded with **SCC14** barcode specification |
| static readonly [SingaporePost](../../aspose.barcode.generation/encodetypes/singaporepost/) | Specifies that the data should be encoded with **Singapore Post Barcode** barcode specification |
| static readonly [SSCC18](../../aspose.barcode.generation/encodetypes/sscc18/) | Specifies that the data should be encoded with **SSCC18** barcode specification |
| static readonly [Standard2of5](../../aspose.barcode.generation/encodetypes/standard2of5/) | Specifies that the data should be encoded with **Standard 2 of 5** barcode specification |
| static readonly [SwissPostParcel](../../aspose.barcode.generation/encodetypes/swisspostparcel/) | Specifies that the data should be encoded with **Swiss Post Parcel Barcode** barcode specification. Supported types: Domestic Mail, International Mail, Additional Services (new) |
| static readonly [UPCA](../../aspose.barcode.generation/encodetypes/upca/) | Specifies that the data should be encoded with **UPC-A** barcode specification |
| static readonly [UpcaGs1Code128Coupon](../../aspose.barcode.generation/encodetypes/upcags1code128coupon/) | Specifies that the data should be encoded with **UPC coupon with GS1-128 Extended Code** barcode specification. An example of the input string: BarcodeGenerator.Codetext = "514141100906(8102)03", where UPCA part is "514141100906", GS1Code128 part is (8102)03. |
| static readonly [UpcaGs1DatabarCoupon](../../aspose.barcode.generation/encodetypes/upcags1databarcoupon/) | Specifies that the data should be encoded with **UPC coupon with GS1 DataBar addition** barcode specification. An example of the input string: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", where UPCA part is "514141100906", Databar part is "(8110)106141416543213500110000310123196000". To change the caption, use Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static readonly [UPCE](../../aspose.barcode.generation/encodetypes/upce/) | Specifies that the data should be encoded with **UPC-E** barcode specification |
| static readonly [VIN](../../aspose.barcode.generation/encodetypes/vin/) | Represents VIN (Vehicle Identification Number) Barcode. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


