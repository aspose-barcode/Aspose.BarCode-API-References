---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType class"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType class. Specificera typen av streckkod att läsa i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Ange typen av streckkod att läsa.

```cpp
class DecodeType
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Hämtar en array som representerar AllSupportedTypes |
| static [GetNames](./getnames/)() | Hämtar en array med namnen på avkodningstyperna. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Bestämmer om den angivna [BaseDecodeType](../basedecodetype/) innehåller någon 1D-streckkodssymbologi |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Bestämmer om den angivna [BaseDecodeType](../basedecodetype/) innehåller någon 2D-streckkodssymbologi |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Bestämmer om den angivna [BaseDecodeType](../basedecodetype/) innehåller någon poststreckkodssymbologi |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konverterar strängrepresentationen av en [SingleDecodeType](../singledecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Ange skanningsuppsättningar efter barcodeTypes |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konverterar strängrepresentationen av en [SingleDecodeType](../singledecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Konverterar strängrepresentationen av en [MultiDecodeType](../multidecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Anger att data kommer att kontrolleras med alla tillgängliga symbologier |
| static [AustralianPosteParcel](./australianposteparcel/) | Anger att data ska avkodas med **Australian Post Domestic eParcel Barcode** streckkodsspecifikation |
| static [AustraliaPost](./australiapost/) | Anger att data ska avkodas med **Australia Post** streckkodsspecifikation |
| static [Aztec](./aztec/) | Anger att data ska avkodas med **Aztec** streckkodsspecifikation |
| static [Codabar](./codabar/) | Anger att data ska avkodas med **CODABAR** streckkodsspecifikation |
| static [CodablockF](./codablockf/) | Anger att data ska avkodas med **CodablockF** streckkodsspecifikation |
| static [Code11](./code11/) | Anger att data ska avkodas med **CODE 11** streckkodsspecifikation |
| static [Code128](./code128/) | Anger att data ska avkodas med **CODE 128** streckkodsspecifikation |
| static [Code16K](./code16k/) | Anger att data ska avkodas med **SCode16K** streckkodsspecifikation |
| static [Code32](./code32/) | Anger att data ska avkodas med **Code32** streckkodsspecifikation |
| static [Code39](./code39/) | Anger att data ska avkodas med **Code 39** grundläggande teckenuppsättning streckkodsspecifikation: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Anger att data ska avkodas med **Code 39** full ASCII-teckenuppsättning streckkodsspecifikation: ISO/IEC 16388 |
| static [Code93](./code93/) | Anger att data ska avkodas med **CODE 93** streckkodsspecifikation |
| static [CompactPdf417](./compactpdf417/) | Anger att data ska avkodas med **CompactPdf417** (Pdf417Truncated) streckkodsspecifikation |
| static [DatabarExpanded](./databarexpanded/) | Anger att data ska avkodas med **GS1 Databar expanded** streckkodsspecifikation |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Anger att data ska avkodas med **GS1 Databar expanded stacked** streckkodsspecifikation |
| static [DatabarLimited](./databarlimited/) | Anger att data ska avkodas med **GS1 Databar limited** streckkodsspecifikation |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Anger att data ska avkodas med **GS1 Databar omni-directional** streckkodsspecifikation |
| static [DatabarStacked](./databarstacked/) | Anger att data ska avkodas med **GS1 Databar stacked** streckkodsspecifikation |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Anger att data ska avkodas med **GS1 Databar stacked omni-directional** streckkodsspecifikation |
| static [DatabarTruncated](./databartruncated/) | Anger att data ska avkodas med **GS1 Databar truncated** streckkodsspecifikation |
| static [DataLogic2of5](./datalogic2of5/) | Anger att data ska avkodas med **DataLogic 2 of 5** streckkodsspecifikation |
| static [DataMatrix](./datamatrix/) | Anger att data ska avkodas med **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** streckkodssymbol |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Anger att data ska avkodas med **DeutschePost Ident code** streckkodsspecifikation |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Anger att data ska avkodas med **DeutschePost Leit code** streckkodsspecifikation |
| static [DotCode](./dotcode/) | Anger att data ska avkodas med **DotCode** streckkodsspecifikation |
| static [DutchKIX](./dutchkix/) | Anger att data ska avkodas med **DotCode** streckkodsspecifikation |
| static [EAN13](./ean13/) | Anger att data ska avkodas med **EAN-13** streckkodsspecifikation |
| static [EAN14](./ean14/) | Anger att data ska avkodas med **EAN14** streckkodsspecifikation |
| static [EAN8](./ean8/) | Anger att data ska avkodas med **EAN-8** streckkodsspecifikation |
| static [GS1Aztec](./gs1aztec/) | Anger att data ska avkodas med **GS1 Aztec** streckkodsspecifikation |
| static [GS1Code128](./gs1code128/) | Anger att data ska avkodas med **GS1 CODE 128** streckkodsspecifikation |
| static [GS1CompositeBar](./gs1compositebar/) | Anger att data ska avkodas med **GS1 Composite Bar** streckkodsspecifikation |
| static [GS1DataMatrix](./gs1datamatrix/) | Anger att data ska avkodas med **GS1DataMatrix** streckkodssymbol |
| static [GS1DotCode](./gs1dotcode/) | Anger att data ska avkodas med **GS1 DotCode** streckkodsspecifikation |
| static [GS1HanXin](./gs1hanxin/) | Anger att data ska avkodas med **GS1 Han Xin Code** streckkodsspecifikation |
| static [GS1MicroPdf417](./gs1micropdf417/) | Anger att data ska avkodas med **MicroPdf417** streckkodsspecifikation |
| static [GS1QR](./gs1qr/) | Anger att data ska avkodas med **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** streckkodsspecifikation |
| static [HanXin](./hanxin/) | Anger att data ska avkodas med **Han Xin Code** streckkodsspecifikation |
| static [HIBCAztecLIC](./hibcazteclic/) | Anger att data ska avkodas med **HIBC LIC Aztec** streckkodsspecifikation |
| static [HIBCAztecPAS](./hibcaztecpas/) | Anger att data ska avkodas med **HIBC PAS Aztec** streckkodsspecifikation |
| static [HIBCCode128LIC](./hibccode128lic/) | Anger att data ska avkodas med **HIBC LIC Code128** streckkodsspecifikation |
| static [HIBCCode128PAS](./hibccode128pas/) | Anger att data ska avkodas med **HIBC PAS Code128** streckkodsspecifikation |
| static [HIBCCode39LIC](./hibccode39lic/) | Anger att data ska avkodas med **HIBC LIC Code39** streckkodsspecifikation |
| static [HIBCCode39PAS](./hibccode39pas/) | Anger att data ska avkodas med **HIBC PAS Code39** streckkodsspecifikation |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Anger att data ska avkodas med **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** streckkodsspecifikation |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Anger att data ska avkodas med **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** streckkodsspecifikation |
| static [HIBCQRLIC](./hibcqrlic/) | Anger att data ska avkodas med **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** streckkodsspecifikation |
| static [HIBCQRPAS](./hibcqrpas/) | Anger att data ska avkodas med **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** streckkodsspecifikation |
| static [IATA2of5](./iata2of5/) | Anger att data ska avkodas med **IATA 2 of 5** streckkodsspecifikation. IATA (International Air Transport Association) använder denna streckkod för hantering av luftfrakt. |
| static [Interleaved2of5](./interleaved2of5/) | Anger att data ska avkodas med **INTERLEAVED 2 of 5** streckkodsspecifikation |
| static [ISBN](./isbn/) | Anger att data ska avkodas med **ISBN** streckkodsspecifikation |
| static [ISMN](./ismn/) | Anger att data ska avkodas med **ISMN** streckkodsspecifikation |
| static [ISSN](./issn/) | Anger att data ska avkodas med **ISSN** streckkodsspecifikation |
| static [ItalianPost25](./italianpost25/) | Anger att data ska avkodas med **Italian Post 25** streckkodsspecifikation |
| static [ITF14](./itf14/) | Anger att data ska avkodas med **ITF14** streckkodsspecifikation |
| static [ITF6](./itf6/) | Anger att data ska avkodas med **ITF6** streckkodsspecifikation |
| static [JapanPost](./japanpost/) | Anger att data ska avkodas med **Japan Post** streckkodsspecifikation |
| static [MacroPdf417](./macropdf417/) | Anger att data ska avkodas med **MacroPdf417** streckkodsspecifikation |
| static [Mailmark](./mailmark/) | Anger att data ska avkodas med **Royal Mail Mailmark** streckkodsspecifikation. |
| static [Matrix2of5](./matrix2of5/) | Anger att data ska avkodas med **Matrix 2 of 5** streckkodsspecifikation |
| static [MaxiCode](./maxicode/) | Anger att data ska avkodas med **MaxiCode** streckkodsspecifikation |
| static [MicrE13B](./micre13b/) | Anger att data ska avkodas med **MICR E-13B** streckkodsspecifikation |
| static [MicroPdf417](./micropdf417/) | Anger att data ska avkodas med **MicroPdf417** streckkodsspecifikation |
| static [MicroQR](./microqr/) | Anger att data ska avkodas med **MicroQR Code** streckkodsspecifikation |
| static [MostCommonTypes](./mostcommontypes/) | Anger att data kommer att kontrolleras med de mest använda symbologierna |
| static [MSI](./msi/) | Anger att data ska avkodas med **MSI Plessey** streckkodsspecifikation |
| static [None](./none/) | Ospecificerad avkodningstyp. |
| static [OneCode](./onecode/) | Anger att data ska avkodas med USPS **OneCode** streckkodsspecifikation |
| static [OPC](./opc/) | Anger att data ska avkodas med **OPC** streckkodsspecifikation |
| static [PatchCode](./patchcode/) | Anger att data ska avkodas med **Patch code** streckkodsspecifikation. Streckkodssymbologi används för automatisk skanning |
| static [Pdf417](./pdf417/) | Anger att data ska avkodas med **Pdf417** streckkodssymbologi |
| static [Pharmacode](./pharmacode/) | Anger att data ska avkodas med **Pharmacode** streckkod. Denna symbologi är också känd som Pharmaceutical Binary Code |
| static [Planet](./planet/) | Anger att data ska avkodas med **Planet** streckkodsspecifikation |
| static [PostalTypes](./postaltypes/) | Anger att data kommer att kontrolleras med alla **1.5D Postal** streckkodssymbologier, såsom **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | Anger att data ska avkodas med **Postnet** streckkodsspecifikation |
| static [PZN](./pzn/) | Anger att data ska avkodas med **PZN** streckkodsspecifikation. Denna symbologi är också känd som Pharma Zentral Nummer. PZN7 och PZN8 stöds. |
| static [QR](./qr/) | Anger att data ska avkodas med **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** streckkodsspecifikation |
| static [RectMicroQR](./rectmicroqr/) | Anger att data ska avkodas med **RectMicroQR (rMQR) Code** streckkodsspecifikation |
| static [RM4SCC](./rm4scc/) | Anger att data ska avkodas med **RM4SCC** streckkodsspecifikation. RM4SCC (Royal Mail 4-state Customer Code) används för automatiserad postsortering i Storbritannien. |
| static [SCC14](./scc14/) | Anger att data ska avkodas med **SCC14** streckkodsspecifikation |
| static [SSCC18](./sscc18/) | Anger att data ska avkodas med **SSCC18** streckkodsspecifikation |
| static [Standard2of5](./standard2of5/) | Anger att data ska avkodas med **Standard 2 of 5** streckkodsspecifikation |
| static [Supplement](./supplement/) | Anger att data ska avkodas med **Supplement(EAN2, EAN5)** streckkodsspecifikation |
| static [SwissPostParcel](./swisspostparcel/) | Anger att data ska avkodas med **Swiss Post Parcel Barcode** streckkodsspecifikation |
| static [Types1D](./types1d/) | Anger att data kommer att kontrolleras med alla **1D** streckkodssymbologier |
| static [Types2D](./types2d/) | Anger att data kommer att kontrolleras med alla **2D** streckkodssymbologier |
| static [UPCA](./upca/) | Anger att data ska avkodas med **UPC-A** streckkodsspecifikation |
| static [UPCE](./upce/) | Anger att data ska avkodas med **UPC-E** streckkodsspecifikation |
| static [VIN](./vin/) | Anger att data ska avkodas med **VIN** (Vehicle Identification Number) streckkodsspecifikation |
## Anmärkningar


Detta exempel visar hur man upptäcker Code39- och Code128-streckkoder.
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

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
