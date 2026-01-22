---
title: Class DecodeType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.DecodeType class. Specify the type of barcode to read
type: docs
weight: 230
url: /net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Specify the type of barcode to read.

```csharp
public static class DecodeType
```

## Properties

| Name | Description |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Gets an array that represents AllSupportedTypes |

## Methods

| Name | Description |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Retrieves an array of the names of the decode types. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Determines if the specified [`BaseDecodeType`](../basedecodetype/) contains any 1D barcode symbology |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Determines if the specified [`BaseDecodeType`](../basedecodetype/) contains any 2D barcode symbology |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Determines if the specified [`BaseDecodeType`](../basedecodetype/) contains any Postal barcode symbology |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Specify scan sets by barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | Converts the string representation of a MultiDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Specifies that data will be checked with all available symbologies |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Specifies that the data should be decoded with **Australian Post Domestic eParcel Barcode** barcode specification |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Specifies that the data should be decoded with **Australia Post** barcode specification |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Specifies that the data should be decoded with **Aztec** barcode specification |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Specifies that the data should be decoded with **CODABAR** barcode specification |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Specifies that the data should be decoded with **CodablockF** barcode specification |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Specifies that the data should be decoded with **CODE 11** barcode specification |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Specifies that the data should be decoded with **CODE 128** barcode specification |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Specifies that the data should be decoded with **SCode16K** barcode specification |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Specifies that the data should be decoded with **Code32** barcode specification |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | Specifies that the data should be decoded with **Code 39** basic charset barcode specification: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | Specifies that the data should be decoded with **Code 39** full ASCII charset barcode specification: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | Specifies that the data should be decoded with **CODE 93** barcode specification |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Specifies that the data should be decoded with **CompactPdf417** (Pdf417Truncated) barcode specification |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Specifies that the data should be decoded with **GS1 Databar expanded** barcode specification |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Specifies that the data should be decoded with **GS1 Databar expanded stacked** barcode specification |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Specifies that the data should be decoded with **GS1 Databar limited** barcode specification |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Specifies that the data should be decoded with **GS1 Databar omni-directional** barcode specification |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Specifies that the data should be decoded with **GS1 Databar stacked** barcode specification |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Specifies that the data should be decoded with **GS1 Databar stacked omni-directional** barcode specification |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Specifies that the data should be decoded with **GS1 Databar truncated** barcode specification |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Specifies that the data should be decoded with **DataLogic 2 of 5** barcode specification |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Specifies that the data should be decoded with **DataMatrix** barcode symbology |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Specifies that the data should be decoded with **DeutschePost Ident code** barcode specification |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Specifies that the data should be decoded with **DeutschePost Leit code** barcode specification |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Specifies that the data should be decoded with **DotCode** barcode specification |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Specifies that the data should be decoded with **DotCode** barcode specification |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Specifies that the data should be decoded with **EAN-13** barcode specification |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Specifies that the data should be decoded with **EAN14** barcode specification |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Specifies that the data should be decoded with **EAN-8** barcode specification |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | Specifies that the data should be decoded with **GS1 Aztec** barcode specification |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Specifies that the data should be decoded with **GS1 CODE 128** barcode specification |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | Specifies that the data should be decoded with **GS1 Composite Bar** barcode specification |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Specifies that the data should be decoded with **GS1DataMatrix** barcode symbology |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Specifies that the data should be decoded with **GS1 DotCode** barcode specification |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | Specifies that the data should be decoded with **GS1 Han Xin Code** barcode specification |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | Specifies that the data should be decoded with **MicroPdf417** barcode specification |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Specifies that the data should be decoded with **GS1 QR** barcode specification |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | Specifies that the data should be decoded with **Han Xin Code** barcode specification |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Specifies that the data should be decoded with **HIBC LIC Aztec** barcode specification |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Specifies that the data should be decoded with **HIBC PAS Aztec** barcode specification |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Specifies that the data should be decoded with **HIBC LIC Code128** barcode specification |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Specifies that the data should be decoded with **HIBC PAS Code128** barcode specification |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Specifies that the data should be decoded with **HIBC LIC Code39** barcode specification |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Specifies that the data should be decoded with **HIBC PAS Code39** barcode specification |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Specifies that the data should be decoded with **HIBC LIC DataMatrix** barcode specification |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Specifies that the data should be decoded with **HIBC PAS DataMatrix** barcode specification |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Specifies that the data should be decoded with **HIBC LIC QR** barcode specification |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Specifies that the data should be decoded with **HIBC PAS QR** barcode specification |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Specifies that the data should be decoded with **IATA 2 of 5** barcode specification. IATA (International Air Transport Association) uses this barcode for the management of air cargo. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Specifies that the data should be decoded with **INTERLEAVED 2 of 5** barcode specification |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Specifies that the data should be decoded with **ISBN** barcode specification |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Specifies that the data should be decoded with **ISMN** barcode specification |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Specifies that the data should be decoded with **ISSN** barcode specification |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Specifies that the data should be decoded with **Italian Post 25** barcode specification |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Specifies that the data should be decoded with **ITF14** barcode specification |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Specifies that the data should be decoded with **ITF6** barcode specification |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Specifies that the data should be decoded with **MacroPdf417** barcode specification |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Specifies that the data should be decoded with **Royal Mail Mailmark** barcode specification. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Specifies that the data should be decoded with **Matrix 2 of 5** barcode specification |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Specifies that the data should be decoded with **MaxiCode** barcode specification |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Specifies that the data should be decoded with **MICR E-13B** barcode specification |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Specifies that the data should be decoded with **MicroPdf417** barcode specification |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Specifies that the data should be decoded with **MicroQR Code** barcode specification |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Specifies that data will be checked with most commonly used symbologies |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Specifies that the data should be decoded with **MSI Plessey** barcode specification |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Unspecified decode type. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Specifies that the data should be decoded with USPS **OneCode** barcode specification |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Specifies that the data should be decoded with **OPC** barcode specification |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Specifies that the data should be decoded with **Patch code** barcode specification. Barcode symbology is used for automated scanning |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Specifies that the data should be decoded with **Pdf417** barcode symbology |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Specifies that the data should be decoded with **Pharmacode** barcode. This symbology is also known as Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Specifies that the data should be decoded with **Planet** barcode specification |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Specifies that data will be checked with all of **1.5D Postal** barcode symbologies, like **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Specifies that the data should be decoded with **Postnet** barcode specification |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Specifies that the data should be decoded with **PZN** barcode specification. This symbology is also known as Pharma Zentral Nummer. PZN7 and PZN8 are supported. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Specifies that the data should be decoded with **QR Code** barcode specification |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | Specifies that the data should be decoded with **RectMicroQR (rMQR) Code** barcode specification |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Specifies that the data should be decoded with **RM4SCC** barcode specification. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Specifies that the data should be decoded with **SCC14** barcode specification |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Specifies that the data should be decoded with **SSCC18** barcode specification |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Specifies that the data should be decoded with **Standard 2 of 5** barcode specification |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Specifies that the data should be decoded with **Supplement(EAN2, EAN5)** barcode specification |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Specifies that the data should be decoded with **Swiss Post Parcel Barcode** barcode specification |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Specifies that data will be checked with all of **1D** barcode symbologies |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Specifies that data will be checked with all of **2D** barcode symbologies |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Specifies that the data should be decoded with **UPC-A** barcode specification |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Specifies that the data should be decoded with **UPC-E** barcode specification |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Specifies that the data should be decoded with **VIN** (Vehicle Identification Number) barcode specification |

## Examples

This sample shows how to detect Code39 and Code128 barcodes.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


