---
title: DecodeType
second_title: Aspose.BarCode for .NET API Reference
description: 
type: docs
weight: 190
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
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | Gets an array that represents AllSupportedTypes |

## Methods

| Name | Description |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | Retrieves an array of the names of the decode types. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | Determines if the specified [`BaseDecodeType`](../basedecodetype) contains any 1D barcode symbology |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | Determines if the specified [`BaseDecodeType`](../basedecodetype) contains any 2D barcode symbology |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | Determines if the specified [`BaseDecodeType`](../basedecodetype) contains any Postal barcode symbology |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | Specify scan sets by barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse)(string, out MultyDecodeType) | Converts the string representation of a MultyDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse)(string, out SingleDecodeType) | Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |

## Other Members

| Name | Description |
| --- | --- |
| static readonly [AllSupportedTypes](allsupportedtypes) | Specifies that data will be checked with all available symbologies |
| static readonly [AustralianPosteParcel](australianposteparcel) | Specifies that the data should be decoded with **Australian Post Domestic eParcel Barcode** barcode specification |
| static readonly [AustraliaPost](australiapost) | Specifies that the data should be decoded with **Australia Post** barcode specification |
| static readonly [Aztec](aztec) | Specifies that the data should be decoded with **Aztec** barcode specification |
| static readonly [Codabar](codabar) | Specifies that the data should be decoded with **CODABAR** barcode specification |
| static readonly [CodablockF](codablockf) | Specifies that the data should be decoded with **CodablockF** barcode specification |
| static readonly [Code11](code11) | Specifies that the data should be decoded with **CODE 11** barcode specification |
| static readonly [Code128](code128) | Specifies that the data should be decoded with **CODE 128** barcode specification |
| static readonly [Code16K](code16k) | Specifies that the data should be decoded with **SCode16K** barcode specification |
| static readonly [Code32](code32) | Specifies that the data should be decoded with **Code32** blank specification |
| static readonly [Code39Extended](code39extended) | Specifies that the data should be decoded with **Extended CODE 39** barcode specification |
| static readonly [Code39Standard](code39standard) | Specifies that the data should be decoded with **Standard CODE 39** barcode specification |
| static readonly [Code93Extended](code93extended) | Specifies that the data should be decoded with **Extended CODE 93** barcode specification |
| static readonly [Code93Standard](code93standard) | Specifies that the data should be decoded with **Standard CODE 93** barcode specification |
| static readonly [CompactPdf417](compactpdf417) | Specifies that the data should be decoded with **CompactPdf417** (Pdf417Truncated) barcode specification |
| static readonly [DatabarExpanded](databarexpanded) | Specifies that the data should be decoded with **GS1 Databar expanded** barcode specification |
| static readonly [DatabarExpandedStacked](databarexpandedstacked) | Specifies that the data should be decoded with **GS1 Databar expanded stacked** barcode specification |
| static readonly [DatabarLimited](databarlimited) | Specifies that the data should be decoded with **GS1 Databar limited** barcode specification |
| static readonly [DatabarOmniDirectional](databaromnidirectional) | Specifies that the data should be decoded with **GS1 Databar omni-directional** barcode specification |
| static readonly [DatabarStacked](databarstacked) | Specifies that the data should be decoded with **GS1 Databar stacked** barcode specification |
| static readonly [DatabarStackedOmniDirectional](databarstackedomnidirectional) | Specifies that the data should be decoded with **GS1 Databar stacked omni-directional** barcode specification |
| static readonly [DatabarTruncated](databartruncated) | Specifies that the data should be decoded with **GS1 Databar truncated** barcode specification |
| static readonly [DataLogic2of5](datalogic2of5) | Specifies that the data should be decoded with **DataLogic 2 of 5** blank specification |
| static readonly [DataMatrix](datamatrix) | Specifies that the data should be decoded with **DataMatrix** barcode symbology |
| static readonly [DeutschePostIdentcode](deutschepostidentcode) | Specifies that the data should be decoded with **DeutschePost Ident code** barcode specification |
| static readonly [DeutschePostLeitcode](deutschepostleitcode) | Specifies that the data should be decoded with **DeutschePost Leit code** barcode specification |
| static readonly [DotCode](dotcode) | Specifies that the data should be decoded with **DotCode** blank specification |
| static readonly [DutchKIX](dutchkix) | Specifies that the data should be decoded with **DotCode** blank specification |
| static readonly [EAN13](ean13) | Specifies that the data should be decoded with **EAN-13** barcode specification |
| static readonly [EAN14](ean14) | Specifies that the data should be decoded with **EAN14** barcode specification |
| static readonly [EAN8](ean8) | Specifies that the data should be decoded with **EAN-8** barcode specification |
| static readonly [GS1Code128](gs1code128) | Specifies that the data should be decoded with **GS1 CODE 128** barcode specification |
| static readonly [GS1DataMatrix](gs1datamatrix) | Specifies that the data should be decoded with **GS1DataMatrix** barcode symbology |
| static readonly [GS1QR](gs1qr) | Specifies that the data should be decoded with **GS1 QR** barcode specification |
| static readonly [IATA2of5](iata2of5) | Specifies that the data should be decoded with **IATA 2 of 5** barcode specification. IATA (International Air Transport Association) uses this barcode for the management of air cargo. |
| static readonly [Interleaved2of5](interleaved2of5) | Specifies that the data should be decoded with **INTERLEAVED 2 of 5** barcode specification |
| static readonly [ISBN](isbn) | Specifies that the data should be decoded with **ISBN** barcode specification |
| static readonly [ISMN](ismn) | Specifies that the data should be decoded with **ISMN** barcode specification |
| static readonly [ISSN](issn) | Specifies that the data should be decoded with **ISSN** barcode specification |
| static readonly [ItalianPost25](italianpost25) | Specifies that the data should be decoded with **Italian Post 25** barcode specification |
| static readonly [ITF14](itf14) | Specifies that the data should be decoded with **ITF14** barcode specification |
| static readonly [ITF6](itf6) | Specifies that the data should be decoded with **ITF6** barcode specification |
| static readonly [MacroPdf417](macropdf417) | Specifies that the data should be decoded with **MacroPdf417** barcode specification |
| static readonly [Mailmark](mailmark) | Specifies that the data should be decoded with **Royal Mail Mailmark** barcode specification. |
| static readonly [Matrix2of5](matrix2of5) | Specifies that the data should be decoded with **Matrix 2 of 5** barcode specification |
| static readonly [MaxiCode](maxicode) | Specifies that the data should be decoded with **MaxiCode** barcode specification |
| static readonly [MicrE13B](micre13b) | Specifies that the data should be decoded with **MICR E-13B** blank specification |
| static readonly [MicroPdf417](micropdf417) | Specifies that the data should be decoded with **MicroPdf417** barcode specification |
| static readonly [MicroQR](microqr) | Specifies that the data should be decoded with **MicroQR Code** barcode specification |
| static readonly [MostCommonTypes](mostcommontypes) | Specifies that data will be checked with most commonly used symbologies |
| static readonly [MSI](msi) | Specifies that the data should be decoded with **MSI Plessey** barcode specification |
| static readonly [None](none) | Unspecified decode type. |
| static readonly [OneCode](onecode) | Specifies that the data should be decoded with USPS **OneCode** barcode specification |
| static readonly [OPC](opc) | Specifies that the data should be decoded with **OPC** barcode specification |
| static readonly [PatchCode](patchcode) | Specifies that the data should be decoded with **Patch code** barcode specification. Barcode symbology is used for automated scanning |
| static readonly [Pdf417](pdf417) | Specifies that the data should be decoded with **Pdf417** barcode symbology |
| static readonly [Pharmacode](pharmacode) | Specifies that the data should be decoded with **Pharmacode** barcode. This symbology is also known as Pharmaceutical Binary Code |
| static readonly [Planet](planet) | Specifies that the data should be decoded with **Planet** barcode specification |
| static readonly [PostalTypes](postaltypes) | Specifies that data will be checked with all of **1.5D Postal** barcode symbologies, like **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](postnet) | Specifies that the data should be decoded with **Postnet** barcode specification |
| static readonly [PZN](pzn) | Specifies that the data should be decoded with **PZN** barcode specification. This symbology is also known as Pharma Zentral Nummer |
| static readonly [QR](qr) | Specifies that the data should be decoded with **QR Code** barcode specification |
| static readonly [RM4SCC](rm4scc) | Specifies that the data should be decoded with **RM4SCC** barcode specification. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| static readonly [SCC14](scc14) | Specifies that the data should be decoded with **SCC14** barcode specification |
| static readonly [SSCC18](sscc18) | Specifies that the data should be decoded with **SSCC18** barcode specification |
| static readonly [Standard2of5](standard2of5) | Specifies that the data should be decoded with **Standard 2 of 5** barcode specification |
| static readonly [Supplement](supplement) | Specifies that the data should be decoded with **Supplement(EAN2, EAN5)** barcode specification |
| static readonly [SwissPostParcel](swisspostparcel) | Specifies that the data should be decoded with **Swiss Post Parcel Barcode** barcode specification |
| static readonly [Types1D](types1d) | Specifies that data will be checked with all of **1D** barcode symbologies |
| static readonly [Types2D](types2d) | Specifies that data will be checked with all of **2D** barcode symbologies |
| static readonly [UPCA](upca) | Specifies that the data should be decoded with **UPC-A** barcode specification |
| static readonly [UPCE](upce) | Specifies that the data should be decoded with **UPC-E** barcode specification |
| static readonly [VIN](vin) | Specifies that the data should be decoded with **VIN** (Vehicle Identification Number) barcode specification |

### Examples

This sample shows how to detect Code39 and Code128 barcodes.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assembly [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
