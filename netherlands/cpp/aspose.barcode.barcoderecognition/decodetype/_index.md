---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType klasse"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType klasse. Specificeer het type barcode om te lezen in C++."
type: docs
weight: 1600
url: /nl/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Specificeer het type barcode om te lezen.

```cpp
class DecodeType
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Haalt een array op die AllSupportedTypes vertegenwoordigt |
| static [GetNames](./getnames/)() | Haalt een array op van de namen van de decodeertypen. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Bepaalt of het opgegeven [BaseDecodeType](../basedecodetype/) enige 1D-barcode-symbologie bevat |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Bepaalt of het opgegeven [BaseDecodeType](../basedecodetype/) enige 2D-barcode-symbologie bevat |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Bepaalt of het opgegeven [BaseDecodeType](../basedecodetype/) enige postbarcode-symbologie bevat |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [SingleDecodeType](../singledecodetype/) naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Specificeer scansets op basis van barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [SingleDecodeType](../singledecodetype/) naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [MultiDecodeType](../multidecodetype/) naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Specificeert dat gegevens worden gecontroleerd met alle beschikbare symbologieën |
| static [AustralianPosteParcel](./australianposteparcel/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Australian Post Domestic eParcel Barcode** barcode-specificatie |
| static [AustraliaPost](./australiapost/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Australia Post** barcode-specificatie |
| static [Aztec](./aztec/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Aztec** barcode-specificatie |
| static [Codabar](./codabar/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CODABAR** barcode-specificatie |
| static [CodablockF](./codablockf/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CodablockF** barcode-specificatie |
| static [Code11](./code11/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CODE 11** barcode-specificatie |
| static [Code128](./code128/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CODE 128** barcode-specificatie |
| static [Code16K](./code16k/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **SCode16K** barcode-specificatie |
| static [Code32](./code32/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Code32** barcode-specificatie |
| static [Code39](./code39/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Code 39** basis‑tekenset barcode-specificatie: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Code 39** volledige ASCII-tekenset barcode-specificatie: ISO/IEC 16388 |
| static [Code93](./code93/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CODE 93** barcode-specificatie |
| static [CompactPdf417](./compactpdf417/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CompactPdf417** (Pdf417Truncated) barcode-specificatie |
| static [DatabarExpanded](./databarexpanded/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **GS1 Databar expanded** barcode-specificatie |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **GS1 Databar expanded stacked** barcode-specificatie |
| static [DatabarLimited](./databarlimited/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **GS1 Databar limited** barcode-specificatie |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **GS1 Databar omni-directional** barcode-specificatie |
| static [DatabarStacked](./databarstacked/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **GS1 Databar stacked** barcode-specificatie |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **GS1 Databar stacked omni-directional** barcode-specificatie |
| static [DatabarTruncated](./databartruncated/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **GS1 Databar truncated** barcode-specificatie |
| static [DataLogic2of5](./datalogic2of5/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **DataLogic 2 of 5** barcode-specificatie |
| static [DataMatrix](./datamatrix/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** barcode-symbool |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **DeutschePost Ident code** barcode-specificatie |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **DeutschePost Leit code** barcode-specificatie |
| static [DotCode](./dotcode/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **DotCode** barcode-specificatie |
| static [DutchKIX](./dutchkix/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **DotCode** barcode-specificatie |
| static [EAN13](./ean13/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **EAN-13** barcode-specificatie |
| static [EAN14](./ean14/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **EAN14** barcode-specificatie |
| static [EAN8](./ean8/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **EAN-8** barcode-specificatie |
| static [GS1Aztec](./gs1aztec/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1 Aztec** barcode-specificatie |
| static [GS1Code128](./gs1code128/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1 CODE 128** barcode-specificatie |
| static [GS1CompositeBar](./gs1compositebar/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1 Composite Bar** barcode-specificatie |
| static [GS1DataMatrix](./gs1datamatrix/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1DataMatrix** barcode-symbool |
| static [GS1DotCode](./gs1dotcode/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1 DotCode** barcode-specificatie |
| static [GS1HanXin](./gs1hanxin/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1 Han Xin Code** barcode-specificatie |
| static [GS1MicroPdf417](./gs1micropdf417/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **MicroPdf417** barcode-specificatie |
| static [GS1QR](./gs1qr/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** barcode-specificatie |
| static [HanXin](./hanxin/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **Han Xin Code** barcode-specificatie |
| static [HIBCAztecLIC](./hibcazteclic/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **HIBC LIC Aztec** barcode-specificatie |
| static [HIBCAztecPAS](./hibcaztecpas/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **HIBC PAS Aztec** barcode-specificatie |
| static [HIBCCode128LIC](./hibccode128lic/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **HIBC LIC Code128** barcode-specificatie |
| static [HIBCCode128PAS](./hibccode128pas/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **HIBC PAS Code128** barcode-specificatie |
| static [HIBCCode39LIC](./hibccode39lic/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **HIBC LIC Code39** barcode-specificatie |
| static [HIBCCode39PAS](./hibccode39pas/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **HIBC PAS Code39** barcode-specificatie |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** barcode-specificatie |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** barcode-specificatie |
| static [HIBCQRLIC](./hibcqrlic/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** barcode-specificatie |
| static [HIBCQRPAS](./hibcqrpas/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** barcode-specificatie |
| static [IATA2of5](./iata2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **IATA 2 of 5** barcode-specificatie. IATA (International Air Transport Association) gebruikt deze barcode voor het beheer van luchtvracht. |
| static [Interleaved2of5](./interleaved2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **INTERLEAVED 2 of 5** barcode-specificatie |
| static [ISBN](./isbn/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ISBN** barcode-specificatie |
| static [ISMN](./ismn/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ISMN** barcode-specificatie |
| static [ISSN](./issn/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ISSN** barcode-specificatie |
| static [ItalianPost25](./italianpost25/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Italian Post 25** barcode-specificatie |
| static [ITF14](./itf14/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ITF14** barcode-specificatie |
| static [ITF6](./itf6/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ITF6** barcode-specificatie |
| static [JapanPost](./japanpost/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Japan Post** barcode-specificatie |
| static [MacroPdf417](./macropdf417/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MacroPdf417** barcode-specificatie |
| static [Mailmark](./mailmark/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Royal Mail Mailmark** barcode-specificatie. |
| static [Matrix2of5](./matrix2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Matrix 2 of 5** barcode-specificatie |
| static [MaxiCode](./maxicode/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MaxiCode** barcode-specificatie |
| static [MicrE13B](./micre13b/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MICR E-13B** barcode-specificatie |
| static [MicroPdf417](./micropdf417/) | Geeft aan dat de gegevens moeten worden gedecodeerd met **MicroPdf417** barcode-specificatie |
| static [MicroQR](./microqr/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MicroQR Code** barcode-specificatie |
| static [MostCommonTypes](./mostcommontypes/) | Specificeert dat gegevens worden gecontroleerd met de meest gebruikte symbologieën |
| static [MSI](./msi/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MSI Plessey** barcode-specificatie |
| static [None](./none/) | Niet-gespecificeerd decodeertype. |
| static [OneCode](./onecode/) | Specificeert dat de gegevens moeten worden gedecodeerd met de USPS **OneCode** barcode-specificatie |
| static [OPC](./opc/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **OPC** barcode-specificatie |
| static [PatchCode](./patchcode/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Patch code** barcode-specificatie. Barcode-symbologie wordt gebruikt voor geautomatiseerd scannen |
| static [Pdf417](./pdf417/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Pdf417** barcode-symbologie |
| static [Pharmacode](./pharmacode/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Pharmacode** barcode. Deze symbologie staat ook bekend als Pharmaceutical Binary Code |
| static [Planet](./planet/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Planet** barcode-specificatie |
| static [PostalTypes](./postaltypes/) | Specificeert dat gegevens worden gecontroleerd met alle **1.5D Postal** barcode-symbologieën, zoals **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Postnet** barcode-specificatie |
| static [PZN](./pzn/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **PZN** barcode-specificatie. Deze symbologie staat ook bekend als Pharma Zentral Nummer. PZN7 en PZN8 worden ondersteund. |
| static [QR](./qr/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** barcode-specificatie |
| static [RectMicroQR](./rectmicroqr/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **RectMicroQR (rMQR) Code** barcode-specificatie |
| static [RM4SCC](./rm4scc/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **RM4SCC** barcode-specificatie. RM4SCC (Royal Mail 4-state Customer Code) wordt gebruikt voor geautomatiseerde postsortering in het VK. |
| static [SCC14](./scc14/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **SCC14** barcode-specificatie |
| static [SSCC18](./sscc18/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **SSCC18** barcode-specificatie |
| static [Standard2of5](./standard2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Standard 2 of 5** barcode-specificatie |
| static [Supplement](./supplement/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Supplement(EAN2, EAN5)** barcode-specificatie |
| static [SwissPostParcel](./swisspostparcel/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Swiss Post Parcel Barcode** barcode-specificatie |
| static [Types1D](./types1d/) | Specificeert dat gegevens worden gecontroleerd met alle **1D** barcode-symbologieën |
| static [Types2D](./types2d/) | Specificeert dat gegevens worden gecontroleerd met alle **2D** barcode-symbologieën |
| static [UPCA](./upca/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **UPC-A** barcode-specificatie |
| static [UPCE](./upce/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **UPC-E** barcode-specificatie |
| static [VIN](./vin/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **VIN** (Vehicle Identification Number) barcode-specificatie |
## Opmerkingen


Dit voorbeeld laat zien hoe Code39- en Code128-barcodes te detecteren.
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

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
