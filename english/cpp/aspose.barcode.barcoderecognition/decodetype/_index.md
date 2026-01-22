---
title: Aspose::BarCode::BarCodeRecognition::DecodeType class
linktitle: DecodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::DecodeType class. Specify the type of barcode to read in C++.'
type: docs
weight: 1600
url: /cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Specify the type of barcode to read.

```cpp
class DecodeType
```

## Methods

| Method | Description |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Gets an array that represents AllSupportedTypes |
| static [GetNames](./getnames/)() | Retrieves an array of the names of the decode types. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Determines if the specified [BaseDecodeType](../basedecodetype/) contains any 1D barcode symbology |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Determines if the specified [BaseDecodeType](../basedecodetype/) contains any 2D barcode symbology |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Determines if the specified [BaseDecodeType](../basedecodetype/) contains any Postal barcode symbology |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converts the string representation of a [SingleDecodeType](../singledecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Specify scan sets by barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converts the string representation of a [SingleDecodeType](../singledecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converts the string representation of a [MultiDecodeType](../multidecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
## Fields

| Field | Description |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Specifies that data will be checked with all available symbologies |
| static [AustralianPosteParcel](./australianposteparcel/) | Specifies that the data should be decoded with **Australian Post Domestic eParcel Barcode** barcode specification |
| static [AustraliaPost](./australiapost/) | Specifies that the data should be decoded with **Australia Post** barcode specification |
| static [Aztec](./aztec/) | Specifies that the data should be decoded with **Aztec** barcode specification |
| static [Codabar](./codabar/) | Specifies that the data should be decoded with **CODABAR** barcode specification |
| static [CodablockF](./codablockf/) | Specifies that the data should be decoded with **CodablockF** barcode specification |
| static [Code11](./code11/) | Specifies that the data should be decoded with **CODE 11** barcode specification |
| static [Code128](./code128/) | Specifies that the data should be decoded with **CODE 128** barcode specification |
| static [Code16K](./code16k/) | Specifies that the data should be decoded with **SCode16K** barcode specification |
| static [Code32](./code32/) | Specifies that the data should be decoded with **Code32** barcode specification |
| static [Code39](./code39/) | Specifies that the data should be decoded with **Code 39** basic charset barcode specification: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Specifies that the data should be decoded with **Code 39** full ASCII charset barcode specification: ISO/IEC 16388 |
| static [Code93](./code93/) | Specifies that the data should be decoded with **CODE 93** barcode specification |
| static [CompactPdf417](./compactpdf417/) | Specifies that the data should be decoded with **CompactPdf417** (Pdf417Truncated) barcode specification |
| static [DatabarExpanded](./databarexpanded/) | Specifies that the data should be decoded with **GS1 Databar expanded** barcode specification |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Specifies that the data should be decoded with **GS1 Databar expanded stacked** barcode specification |
| static [DatabarLimited](./databarlimited/) | Specifies that the data should be decoded with **GS1 Databar limited** barcode specification |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Specifies that the data should be decoded with **GS1 Databar omni-directional** barcode specification |
| static [DatabarStacked](./databarstacked/) | Specifies that the data should be decoded with **GS1 Databar stacked** barcode specification |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Specifies that the data should be decoded with **GS1 Databar stacked omni-directional** barcode specification |
| static [DatabarTruncated](./databartruncated/) | Specifies that the data should be decoded with **GS1 Databar truncated** barcode specification |
| static [DataLogic2of5](./datalogic2of5/) | Specifies that the data should be decoded with **DataLogic 2 of 5** barcode specification |
| static [DataMatrix](./datamatrix/) | Specifies that the data should be decoded with **DataMatrix** barcode symbology |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Specifies that the data should be decoded with **DeutschePost Ident code** barcode specification |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Specifies that the data should be decoded with **DeutschePost Leit code** barcode specification |
| static [DotCode](./dotcode/) | Specifies that the data should be decoded with **DotCode** barcode specification |
| static [DutchKIX](./dutchkix/) | Specifies that the data should be decoded with **DotCode** barcode specification |
| static [EAN13](./ean13/) | Specifies that the data should be decoded with **EAN-13** barcode specification |
| static [EAN14](./ean14/) | Specifies that the data should be decoded with **EAN14** barcode specification |
| static [EAN8](./ean8/) | Specifies that the data should be decoded with **EAN-8** barcode specification |
| static [GS1Aztec](./gs1aztec/) | Specifies that the data should be decoded with **GS1 Aztec** barcode specification |
| static [GS1Code128](./gs1code128/) | Specifies that the data should be decoded with **GS1 CODE 128** barcode specification |
| static [GS1CompositeBar](./gs1compositebar/) | Specifies that the data should be decoded with **GS1 Composite Bar** barcode specification |
| static [GS1DataMatrix](./gs1datamatrix/) | Specifies that the data should be decoded with **GS1DataMatrix** barcode symbology |
| static [GS1DotCode](./gs1dotcode/) | Specifies that the data should be decoded with **GS1 DotCode** barcode specification |
| static [GS1HanXin](./gs1hanxin/) | Specifies that the data should be decoded with **GS1 Han Xin Code** barcode specification |
| static [GS1MicroPdf417](./gs1micropdf417/) | Specifies that the data should be decoded with **MicroPdf417** barcode specification |
| static [GS1QR](./gs1qr/) | Specifies that the data should be decoded with **GS1 QR** barcode specification |
| static [HanXin](./hanxin/) | Specifies that the data should be decoded with **Han Xin Code** barcode specification |
| static [HIBCAztecLIC](./hibcazteclic/) | Specifies that the data should be decoded with **HIBC LIC Aztec** barcode specification |
| static [HIBCAztecPAS](./hibcaztecpas/) | Specifies that the data should be decoded with **HIBC PAS Aztec** barcode specification |
| static [HIBCCode128LIC](./hibccode128lic/) | Specifies that the data should be decoded with **HIBC LIC Code128** barcode specification |
| static [HIBCCode128PAS](./hibccode128pas/) | Specifies that the data should be decoded with **HIBC PAS Code128** barcode specification |
| static [HIBCCode39LIC](./hibccode39lic/) | Specifies that the data should be decoded with **HIBC LIC Code39** barcode specification |
| static [HIBCCode39PAS](./hibccode39pas/) | Specifies that the data should be decoded with **HIBC PAS Code39** barcode specification |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Specifies that the data should be decoded with **HIBC LIC DataMatrix** barcode specification |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Specifies that the data should be decoded with **HIBC PAS DataMatrix** barcode specification |
| static [HIBCQRLIC](./hibcqrlic/) | Specifies that the data should be decoded with **HIBC LIC QR** barcode specification |
| static [HIBCQRPAS](./hibcqrpas/) | Specifies that the data should be decoded with **HIBC PAS QR** barcode specification |
| static [IATA2of5](./iata2of5/) | Specifies that the data should be decoded with **IATA 2 of 5** barcode specification. IATA (International Air Transport Association) uses this barcode for the management of air cargo. |
| static [Interleaved2of5](./interleaved2of5/) | Specifies that the data should be decoded with **INTERLEAVED 2 of 5** barcode specification |
| static [ISBN](./isbn/) | Specifies that the data should be decoded with **ISBN** barcode specification |
| static [ISMN](./ismn/) | Specifies that the data should be decoded with **ISMN** barcode specification |
| static [ISSN](./issn/) | Specifies that the data should be decoded with **ISSN** barcode specification |
| static [ItalianPost25](./italianpost25/) | Specifies that the data should be decoded with **Italian Post 25** barcode specification |
| static [ITF14](./itf14/) | Specifies that the data should be decoded with **ITF14** barcode specification |
| static [ITF6](./itf6/) | Specifies that the data should be decoded with **ITF6** barcode specification |
| static [MacroPdf417](./macropdf417/) | Specifies that the data should be decoded with **MacroPdf417** barcode specification |
| static [Mailmark](./mailmark/) | Specifies that the data should be decoded with **Royal Mail Mailmark** barcode specification. |
| static [Matrix2of5](./matrix2of5/) | Specifies that the data should be decoded with **Matrix 2 of 5** barcode specification |
| static [MaxiCode](./maxicode/) | Specifies that the data should be decoded with **MaxiCode** barcode specification |
| static [MicrE13B](./micre13b/) | Specifies that the data should be decoded with **MICR E-13B** barcode specification |
| static [MicroPdf417](./micropdf417/) | Specifies that the data should be decoded with **MicroPdf417** barcode specification |
| static [MicroQR](./microqr/) | Specifies that the data should be decoded with **MicroQR Code** barcode specification |
| static [MostCommonTypes](./mostcommontypes/) | Specifies that data will be checked with most commonly used symbologies |
| static [MSI](./msi/) | Specifies that the data should be decoded with **MSI Plessey** barcode specification |
| static [None](./none/) | Unspecified decode type. |
| static [OneCode](./onecode/) | Specifies that the data should be decoded with USPS **OneCode** barcode specification |
| static [OPC](./opc/) | Specifies that the data should be decoded with **OPC** barcode specification |
| static [PatchCode](./patchcode/) | Specifies that the data should be decoded with **Patch code** barcode specification. Barcode symbology is used for automated scanning |
| static [Pdf417](./pdf417/) | Specifies that the data should be decoded with **Pdf417** barcode symbology |
| static [Pharmacode](./pharmacode/) | Specifies that the data should be decoded with **Pharmacode** barcode. This symbology is also known as Pharmaceutical Binary Code |
| static [Planet](./planet/) | Specifies that the data should be decoded with **Planet** barcode specification |
| static [PostalTypes](./postaltypes/) | Specifies that data will be checked with all of **1.5D Postal** barcode symbologies, like **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | Specifies that the data should be decoded with **Postnet** barcode specification |
| static [PZN](./pzn/) | Specifies that the data should be decoded with **PZN** barcode specification. This symbology is also known as Pharma Zentral Nummer. PZN7 and PZN8 are supported. |
| static [QR](./qr/) | Specifies that the data should be decoded with **QR Code** barcode specification |
| static [RectMicroQR](./rectmicroqr/) | Specifies that the data should be decoded with **RectMicroQR (rMQR) Code** barcode specification |
| static [RM4SCC](./rm4scc/) | Specifies that the data should be decoded with **RM4SCC** barcode specification. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| static [SCC14](./scc14/) | Specifies that the data should be decoded with **SCC14** barcode specification |
| static [SSCC18](./sscc18/) | Specifies that the data should be decoded with **SSCC18** barcode specification |
| static [Standard2of5](./standard2of5/) | Specifies that the data should be decoded with **Standard 2 of 5** barcode specification |
| static [Supplement](./supplement/) | Specifies that the data should be decoded with **Supplement(EAN2, EAN5)** barcode specification |
| static [SwissPostParcel](./swisspostparcel/) | Specifies that the data should be decoded with **Swiss Post Parcel Barcode** barcode specification |
| static [Types1D](./types1d/) | Specifies that data will be checked with all of **1D** barcode symbologies |
| static [Types2D](./types2d/) | Specifies that data will be checked with all of **2D** barcode symbologies |
| static [UPCA](./upca/) | Specifies that the data should be decoded with **UPC-A** barcode specification |
| static [UPCE](./upce/) | Specifies that the data should be decoded with **UPC-E** barcode specification |
| static [VIN](./vin/) | Specifies that the data should be decoded with **VIN** (Vehicle Identification Number) barcode specification |
## Remarks


This sample shows how to detect Code39 and Code128 barcodes. 
```cpp
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

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
