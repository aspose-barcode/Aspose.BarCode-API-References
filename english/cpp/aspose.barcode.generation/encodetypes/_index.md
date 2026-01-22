---
title: Aspose::BarCode::Generation::EncodeTypes class
linktitle: EncodeTypes
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::EncodeTypes class. Specifies the type of barcode to encode in C++.'
type: docs
weight: 2200
url: /cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


Specifies the type of barcode to encode.

```cpp
class EncodeTypes
```

## Methods

| Method | Description |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | Specifies that data will be checked with all available symbologies. |
| static [GetNames](./getnames/)() | Retrieves an array of the names of the encode types. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converts the string representation of a [BaseEncodeType](../baseencodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converts the string representation of a [BaseEncodeType](../baseencodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
## Fields

| Field | Description |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | Specifies that the data should be encoded with **Australian Post Domestic eParcel Barcode** barcode specification |
| static [AustraliaPost](./australiapost/) | Represents Australia Post Customer [BarCode](../../aspose.barcode/) |
| static [Aztec](./aztec/) | Specifies that the data should be encoded with **Aztec** barcode specification |
| static [Codabar](./codabar/) | Specifies that the data should be encoded with **CODABAR** barcode specification |
| static [CodablockF](./codablockf/) | Specifies that the data should be encoded with **Codablock-F** barcode specification. |
| static [Code11](./code11/) | Specifies that the data should be encoded with **CODE 11** barcode specification |
| static [Code128](./code128/) | Specifies that the data should be encoded with **CODE 128** barcode specification |
| static [Code16K](./code16k/) | Represents Code 16K barcode. |
| static [Code32](./code32/) | Specifies that the data should be encoded with **Code32** barcode specification |
| static [Code39](./code39/) | Specifies that the data should be encoded with **Code 39** basic charset barcode specification: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Specifies that the data should be encoded with **Code 39** full ASCII charset barcode specification: ISO/IEC 16388 |
| static [Code93](./code93/) | Specifies that the data should be encoded with **CODE 93** barcode specification |
| static [DatabarExpanded](./databarexpanded/) | Represents GS1 Databar expanded barcode. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Represents GS1 Databar expanded stacked barcode. |
| static [DatabarLimited](./databarlimited/) | Represents GS1 Databar limited barcode. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Specifies that the data should be encoded with **GS1 Databar omni-directional** barcode specification. |
| static [DatabarStacked](./databarstacked/) | Represents GS1 Databar stacked barcode. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Represents GS1 Databar stacked omni-directional barcode. |
| static [DatabarTruncated](./databartruncated/) | Specifies that the data should be encoded with **GS1 Databar truncated** barcode specification. |
| static [DataLogic2of5](./datalogic2of5/) | Specifies that the data should be encoded with **DataLogic 2 of 5** barcode specification |
| static [DataMatrix](./datamatrix/) | 2D barcode symbology DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Represents Deutsch Post barcode, This Symbology is also known as Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Represents Deutsch Post Leitcode Barcode,also known as German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static [DotCode](./dotcode/) | Specifies that the data should be encoded with **DotCode** barcode specification |
| static [DutchKIX](./dutchkix/) | Specifies that the data should be encoded with **Dutch KIX** barcode specification |
| static [EAN13](./ean13/) | Specifies that the data should be encoded with **EAN-13** barcode specification |
| static [EAN14](./ean14/) | Specifies that the data should be encoded with **EAN14** barcode specification |
| static [EAN8](./ean8/) | Specifies that the data should be encoded with **EAN-8** barcode specification |
| static [GS1Aztec](./gs1aztec/) | Specifies that the data should be encoded with **GS1 Aztec** barcode specification. The codetext must contains parentheses for AI. |
| static [GS1CodablockF](./gs1codablockf/) | Specifies that the data should be encoded with **GS1 Codablock-F** barcode specification. The codetext must contains parentheses for AI. |
| static [GS1Code128](./gs1code128/) | Specifies that the data should be encoded with **GS1 Code 128** barcode specification. The codetext must contains parentheses for AI. |
| static [GS1CompositeBar](./gs1compositebar/) | Specifies that the data should be encoded with **GS1 Composite Bar** barcode specification. The codetext must contains parentheses for AI. 1D codetext and 2D codetext must be separated with symbol '/' |
| static [GS1DataMatrix](./gs1datamatrix/) | 2D barcode symbology DataMatrix with GS1 string format |
| static [GS1DotCode](./gs1dotcode/) | Specifies that the data should be encoded with **GS1 DotCode** barcode specification. The codetext must contains parentheses for AI. |
| static [GS1HanXin](./gs1hanxin/) | 2D barcode symbology HanXin with GS1 string format |
| static [GS1MicroPdf417](./gs1micropdf417/) | Specifies that the data should be encoded with **GS1MicroPdf417** barcode specification |
| static [GS1QR](./gs1qr/) | 2D barcode symbology QR with GS1 string format |
| static [HanXin](./hanxin/) | Specifies that the data should be encoded with **Han Xin** barcode specification |
| static [HIBCAztecLIC](./hibcazteclic/) | Specifies that the data should be encoded with **HIBC LIC Aztec** barcode specification. |
| static [HIBCAztecPAS](./hibcaztecpas/) | Specifies that the data should be encoded with **HIBC PAS Aztec** barcode specification. |
| static [HIBCCode128LIC](./hibccode128lic/) | Specifies that the data should be encoded with **HIBC LIC Code128** barcode specification. |
| static [HIBCCode128PAS](./hibccode128pas/) | Specifies that the data should be encoded with **HIBC PAS Code128** barcode specification. |
| static [HIBCCode39LIC](./hibccode39lic/) | Specifies that the data should be encoded with **HIBC LIC Code39** barcode specification. |
| static [HIBCCode39PAS](./hibccode39pas/) | Specifies that the data should be encoded with **HIBC PAS Code39** barcode specification. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Specifies that the data should be encoded with **HIBC LIC DataMatrix** barcode specification. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Specifies that the data should be encoded with **HIBC PAS DataMatrix** barcode specification. |
| static [HIBCQRLIC](./hibcqrlic/) | Specifies that the data should be encoded with **HIBC LIC QR** barcode specification. |
| static [HIBCQRPAS](./hibcqrpas/) | Specifies that the data should be encoded with **HIBC PAS QR** barcode specification. |
| static [IATA2of5](./iata2of5/) | Represents IATA 2 of 5 barcode.IATA (International Air Transport Assosiation) uses this barcode for the management of air cargo. |
| static [Interleaved2of5](./interleaved2of5/) | Specifies that the data should be encoded with **INTERLEAVED 2 of 5** barcode specification |
| static [ISBN](./isbn/) | Specifies that the data should be encoded with **ISBN** barcode specification |
| static [ISMN](./ismn/) | Specifies that the data should be encoded with **ISMN** barcode specification |
| static [ISSN](./issn/) | Specifies that the data should be encoded with **ISSN** barcode specification |
| static [ItalianPost25](./italianpost25/) | Represents Italian Post 25 barcode. |
| static [ITF14](./itf14/) | Specifies that the data should be encoded with **ITF14** barcode specification |
| static [ITF6](./itf6/) | Represents ITF-6 Barcode. |
| static [MacroPdf417](./macropdf417/) | Specifies that the data should be encoded with **MacroPdf417** barcode specification |
| static [Mailmark](./mailmark/) | Represents Royal Mail Mailmark barcode. |
| static [Matrix2of5](./matrix2of5/) | Represents Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | Specifies that the data should be encoded with **MaxiCode** barcode specification |
| static [MicroPdf417](./micropdf417/) | Specifies that the data should be encoded with **MicroPdf417** barcode specification |
| static [MicroQR](./microqr/) | Specifies that the data should be encoded with **MicroQR Code** barcode specification |
| static [MSI](./msi/) | Specifies that the data should be encoded with **MSI Plessey** barcode specification |
| static [None](./none/) | Unspecified encode type. |
| static [OneCode](./onecode/) | Specifies that the data should be encoded with USPS **OneCode** barcode specification |
| static [OPC](./opc/) | Represents OPC(Optical Product Code) Barcode,also known as , VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| static [PatchCode](./patchcode/) | Represents Patch code barcode |
| static [Pdf417](./pdf417/) | Specifies that the data should be encoded with **Pdf417** barcode specification |
| static [Pharmacode](./pharmacode/) | Represents Pharmacode barcode. |
| static [Planet](./planet/) | Specifies that the data should be encoded with **Planet** barcode specification |
| static [Postnet](./postnet/) | Specifies that the data should be encoded with **Postnet** barcode specification |
| static [PZN](./pzn/) | Represents PZN barcode.This Symbology is also known as Pharmacy central number, Pharmazentralnummer. PZN7 and PZN8 are supported. PZN7 is generated from 6 or less digits, like "123456". PZN8 is generated from 7 or more digits, like "1234567". Provided last checksum digit is ignored and generated by the barcode engine. |
| static [QR](./qr/) | Specifies that the data should be encoded with **QR Code** barcode specification |
| static [RectMicroQR](./rectmicroqr/) | Specifies that the data should be encoded with **RectMicroQR (rMQR) Code** barcode specification |
| static [RM4SCC](./rm4scc/) | Represents RM4SCC barcode. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| static [SCC14](./scc14/) | Specifies that the data should be encoded with **SCC14** barcode specification |
| static [SingaporePost](./singaporepost/) | Specifies that the data should be encoded with **Singapore Post Barcode** barcode specification |
| static [SSCC18](./sscc18/) | Specifies that the data should be encoded with **SSCC18** barcode specification |
| static [Standard2of5](./standard2of5/) | Specifies that the data should be encoded with **Standard 2 of 5** barcode specification |
| static [SwissPostParcel](./swisspostparcel/) | Specifies that the data should be encoded with **Swiss Post Parcel Barcode** barcode specification. Supported types: Domestic Mail, International Mail, Additional Services (new) |
| static [UPCA](./upca/) | Specifies that the data should be encoded with **UPC-A** barcode specification |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | Specifies that the data should be encoded with **UPC coupon with GS1-128 Extended Code** barcode specification. An example of the input string: BarcodeGenerator.Codetext = "514141100906(8102)03", where UPCA part is "514141100906", GS1Code128 part is (8102)03. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | Specifies that the data should be encoded with **UPC coupon with GS1 DataBar addition** barcode specification. An example of the input string: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", where UPCA part is "514141100906", Databar part is "(8110)106141416543213500110000310123196000". To change the caption, use Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | Specifies that the data should be encoded with **UPC-E** barcode specification |
| static [VIN](./vin/) | Represents VIN (Vehicle Identification Number) Barcode. |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
