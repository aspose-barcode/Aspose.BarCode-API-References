---
title: EncodeTypes
second_title: Aspose.BarCode for .NET API Reference
description: 
type: docs
weight: 720
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
| static [AllEncodeTypes](../../aspose.barcode.generation/encodetypes/allencodetypes) { get; } | Specifies that data will be checked with all available symbologies. |

## Methods

| Name | Description |
| --- | --- |
| static [GetNames](../../aspose.barcode.generation/encodetypes/getnames)() | Retrieves an array of the names of the encode types. |
| static [Parse](../../aspose.barcode.generation/encodetypes/parse)(string, out BaseEncodeType) | Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../../aspose.barcode.generation/encodetypes/tryparse)(string, out BaseEncodeType) | Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed. |

## Other Members

| Name | Description |
| --- | --- |
| static readonly [AustralianPosteParcel](australianposteparcel) | Specifies that the data should be encoded with **Australian Post Domestic eParcel Barcode** barcode specification |
| static readonly [AustraliaPost](australiapost) | Represents Australia Post Customer BarCode |
| static readonly [Aztec](aztec) | Specifies that the data should be encoded with **Aztec** barcode specification |
| static readonly [Codabar](codabar) | Specifies that the data should be encoded with **CODABAR** barcode specification |
| static readonly [CodablockF](codablockf) | Specifies that the data should be encoded with **Codablock-F** barcode specification. |
| static readonly [Code11](code11) | Specifies that the data should be encoded with **CODE 11** barcode specification |
| static readonly [Code128](code128) | Specifies that the data should be encoded with **CODE 128** barcode specification |
| static readonly [Code16K](code16k) | Represents Code 16K barcode. |
| static readonly [Code32](code32) | Specifies that the data should be encoded with **Code32** barcode specification |
| static readonly [Code39Extended](code39extended) | Specifies that the data should be encoded with **Extended CODE 39** barcode specification |
| static readonly [Code39Standard](code39standard) | Specifies that the data should be encoded with **Standard CODE 39** barcode specification |
| static readonly [Code93Extended](code93extended) | Specifies that the data should be encoded with **Extended CODE 93** barcode specification |
| static readonly [Code93Standard](code93standard) | Specifies that the data should be encoded with **Standard CODE 93** barcode specification |
| static readonly [DatabarExpanded](databarexpanded) | Represents GS1 Databar expanded barcode. |
| static readonly [DatabarExpandedStacked](databarexpandedstacked) | Represents GS1 Databar expanded stacked barcode. |
| static readonly [DatabarLimited](databarlimited) | Represents GS1 Databar limited barcode. |
| static readonly [DatabarOmniDirectional](databaromnidirectional) | Specifies that the data should be encoded with **GS1 Databar omni-directional** barcode specification. |
| static readonly [DatabarStacked](databarstacked) | Represents GS1 Databar stacked barcode. |
| static readonly [DatabarStackedOmniDirectional](databarstackedomnidirectional) | Represents GS1 Databar stacked omni-directional barcode. |
| static readonly [DatabarTruncated](databartruncated) | Specifies that the data should be encoded with **GS1 Databar truncated** barcode specification. |
| static readonly [DataLogic2of5](datalogic2of5) | Specifies that the data should be encoded with **DataLogic 2 of 5** barcode specification |
| static readonly [DataMatrix](datamatrix) | 2D barcode symbology DataMatrix |
| static readonly [DeutschePostIdentcode](deutschepostidentcode) | Represents Deutsch Post barcode, This Symbology is also known as Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static readonly [DeutschePostLeitcode](deutschepostleitcode) | Represents Deutsch Post Leitcode Barcode,also known as German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| static readonly [DotCode](dotcode) | Specifies that the data should be encoded with **DotCode** barcode specification |
| static readonly [DutchKIX](dutchkix) | Specifies that the data should be encoded with **Dutch KIX** barcode specification |
| static readonly [EAN13](ean13) | Specifies that the data should be encoded with **EAN-13** barcode specification |
| static readonly [EAN14](ean14) | Specifies that the data should be encoded with **EAN14** barcode specification |
| static readonly [EAN8](ean8) | Specifies that the data should be encoded with **EAN-8** barcode specification |
| static readonly [GS1CodablockF](gs1codablockf) | Specifies that the data should be encoded with **GS1 Codablock-F** barcode specification. The codetext must contains parentheses for AI. |
| static readonly [GS1Code128](gs1code128) | Specifies that the data should be encoded with **GS1 Code 128** barcode specification. The codetext must contains parentheses for AI. |
| static readonly [GS1DataMatrix](gs1datamatrix) | 2D barcode symbology DataMatrix with GS1 string format |
| static readonly [GS1QR](gs1qr) | 2D barcode symbology QR with GS1 string format |
| static readonly [IATA2of5](iata2of5) | Represents IATA 2 of 5 barcode.IATA (International Air Transport Assosiation) uses this barcode for the management of air cargo. |
| static readonly [Interleaved2of5](interleaved2of5) | Specifies that the data should be encoded with **INTERLEAVED 2 of 5** barcode specification |
| static readonly [ISBN](isbn) | Specifies that the data should be encoded with **ISBN** barcode specification |
| static readonly [ISMN](ismn) | Specifies that the data should be encoded with **ISMN** barcode specification |
| static readonly [ISSN](issn) | Specifies that the data should be encoded with **ISSN** barcode specification |
| static readonly [ItalianPost25](italianpost25) | Represents Italian Post 25 barcode. |
| static readonly [ITF14](itf14) | Specifies that the data should be encoded with **ITF14** barcode specification |
| static readonly [ITF6](itf6) | Represents ITF-6 Barcode. |
| static readonly [MacroPdf417](macropdf417) | Specifies that the data should be encoded with **MacroPdf417** barcode specification |
| static readonly [Mailmark](mailmark) | Represents Royal Mail Mailmark barcode. |
| static readonly [Matrix2of5](matrix2of5) | Represents Matrix 2 of 5 BarCode |
| static readonly [MaxiCode](maxicode) | Specifies that the data should be encoded with **MaxiCode** barcode specification |
| static readonly [MicroPdf417](micropdf417) | Specifies that the data should be encoded with **MicroPdf417** barcode specification |
| static readonly [MSI](msi) | Specifies that the data should be encoded with **MSI Plessey** barcode specification |
| static readonly [None](none) | Unspecified encode type. |
| static readonly [OneCode](onecode) | Specifies that the data should be encoded with USPS **OneCode** barcode specification |
| static readonly [OPC](opc) | Represents OPC(Optical Product Code) Barcode,also known as , VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| static readonly [PatchCode](patchcode) | Represents Patch code barcode |
| static readonly [Pdf417](pdf417) | Specifies that the data should be encoded with **Pdf417** barcode specification |
| static readonly [Pharmacode](pharmacode) | Represents Pharmacode barcode. |
| static readonly [Planet](planet) | Specifies that the data should be encoded with **Planet** barcode specification |
| static readonly [Postnet](postnet) | Specifies that the data should be encoded with **Postnet** barcode specification |
| static readonly [PZN](pzn) | Represents PZN barcode.This Symbology is also known as Pharmacy central number, Pharmazentralnummer |
| static readonly [QR](qr) | Specifies that the data should be encoded with **QR Code** barcode specification |
| static readonly [RM4SCC](rm4scc) | Represents RM4SCC barcode. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| static readonly [SCC14](scc14) | Specifies that the data should be encoded with **SCC14** barcode specification |
| static readonly [SingaporePost](singaporepost) | Specifies that the data should be encoded with **Singapore Post Barcode** barcode specification |
| static readonly [SSCC18](sscc18) | Specifies that the data should be encoded with **SSCC18** barcode specification |
| static readonly [Standard2of5](standard2of5) | Specifies that the data should be encoded with **Standard 2 of 5** barcode specification |
| static readonly [SwissPostParcel](swisspostparcel) | Specifies that the data should be encoded with **Swiss Post Parcel Barcode** barcode specification. Supported types: Domestic Mail, International Mail, Additional Services (new) |
| static readonly [UPCA](upca) | Specifies that the data should be encoded with **UPC-A** barcode specification |
| static readonly [UpcaGs1Code128Coupon](upcags1code128coupon) | Specifies that the data should be encoded with **UPC coupon with GS1-128 Extended Code** barcode specification. An example of the input string: BarcodeGenerator.Codetext = "514141100906(8102)03", where UPCA part is "514141100906", GS1Code128 part is (8102)03. |
| static readonly [UpcaGs1DatabarCoupon](upcags1databarcoupon) | Specifies that the data should be encoded with **UPC coupon with GS1 DataBar addition** barcode specification. An example of the input string: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", where UPCA part is "514141100906", Databar part is "(8110)106141416543213500110000310123196000". To change the caption, use Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static readonly [UPCE](upce) | Specifies that the data should be encoded with **UPC-E** barcode specification |
| static readonly [VIN](vin) | Represents VIN (Vehicle Identification Number) Barcode. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* assembly [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
