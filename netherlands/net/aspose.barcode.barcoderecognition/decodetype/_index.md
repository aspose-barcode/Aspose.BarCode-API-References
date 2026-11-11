---
title: "Klasse DecodeType"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.DecodeType class. Specificeer het type barcode om te lezen"
type: docs
weight: 230
url: /nl/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Specificeer het type barcode om te lezen.

```csharp
public static class DecodeType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Haalt een array op die AllSupportedTypes vertegenwoordigt |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Haalt een array op met de namen van de decodeertypen. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Bepaalt of de opgegeven [`BaseDecodeType`](../basedecodetype/) enige 1D-barcode-symbologie bevat |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Bepaalt of de opgegeven [`BaseDecodeType`](../basedecodetype/) enige 2D-barcode-symbologie bevat |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Bepaalt of de opgegeven [`BaseDecodeType`](../basedecodetype/) enige postbarcode-symbologie bevat |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Specificeer scansets op basis van barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | Converteert de tekenreeksrepresentatie van een MultiDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Specificeert dat gegevens worden gecontroleerd met alle beschikbare symbologieën |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Australian Post Domestic eParcel Barcode** barcode-specificatie |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Australia Post** barcode-specificatie |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Aztec** barcode-specificatie |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CODABAR** barcode-specificatie |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CodablockF** barcode-specificatie |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CODE 11** barcode-specificatie |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **CODE 128** barcode-specificatie |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **SCode16K** barcode-specificatie |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Code32** barcode-specificatie |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Code 39** basistekenset barcode-specificatie: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Code 39** volledige ASCII-tekenset barcode-specificatie: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | Specificeert dat de gegevens moeten worden gedecodeerd met **CODE 93** barcode-specificatie |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Specificeert dat de gegevens moeten worden gedecodeerd met **CompactPdf417** (Pdf417Truncated) barcode-specificatie |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Databar expanded** barcode-specificatie |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Databar expanded stacked** barcode-specificatie |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Databar limited** barcode-specificatie |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Databar omni-directional** barcode-specificatie |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Databar stacked** barcode-specificatie |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Databar stacked omni-directional** barcode-specificatie |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Databar truncated** barcode-specificatie |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met **DataLogic 2 of 5** barcode-specificatie |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Specificeert dat de gegevens moeten worden gedecodeerd met **DataMatrix** barcode-symbool |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Specificeert dat de gegevens moeten worden gedecodeerd met **DeutschePost Ident code** barcode-specificatie |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Specificeert dat de gegevens moeten worden gedecodeerd met **DeutschePost Leit code** barcode-specificatie |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Specificeert dat de gegevens moeten worden gedecodeerd met **DotCode** barcode-specificatie |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Specificeert dat de gegevens moeten worden gedecodeerd met **DotCode** barcode-specificatie |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Specificeert dat de gegevens moeten worden gedecodeerd met **EAN-13** barcode-specificatie |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Specificeert dat de gegevens moeten worden gedecodeerd met **EAN14** barcode-specificatie |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Specificeert dat de gegevens moeten worden gedecodeerd met **EAN-8** barcode-specificatie |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Aztec** barcode-specificatie |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 CODE 128** barcode-specificatie |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Composite Bar** barcode-specificatie |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1DataMatrix** barcode-symbool |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 DotCode** barcode-specificatie |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 Han Xin Code** barcode-specificatie |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | Specificeert dat de gegevens moeten worden gedecodeerd met **MicroPdf417** barcode-specificatie |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Specificeert dat de gegevens moeten worden gedecodeerd met **GS1 QR** barcode-specificatie |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Han Xin Code** barcode-specificatie |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC LIC Aztec** barcode-specificatie |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC PAS Aztec** barcode-specificatie |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC LIC Code128** barcode-specificatie |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC PAS Code128** barcode-specificatie |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC LIC Code39** barcode-specificatie |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC PAS Code39** barcode-specificatie |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC LIC DataMatrix** barcode-specificatie |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC PAS DataMatrix** barcode-specificatie |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC LIC QR** barcode-specificatie |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **HIBC PAS QR** barcode-specificatie |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **IATA 2 of 5** barcode-specificatie. IATA (International Air Transport Association) gebruikt deze barcode voor het beheer van luchtvracht. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **INTERLEAVED 2 of 5** barcode-specificatie |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ISBN** barcode-specificatie |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ISMN** barcode-specificatie |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ISSN** barcode-specificatie |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Italian Post 25** barcode-specificatie |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ITF14** barcode-specificatie |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **ITF6** barcode-specificatie |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Japan Post** barcode-specificatie |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MacroPdf417** barcode-specificatie |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Royal Mail Mailmark** barcode-specificatie. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Matrix 2 of 5** barcode-specificatie |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MaxiCode** barcode-specificatie |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MICR E-13B** barcode-specificatie |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Specificeert dat de gegevens moeten worden gedecodeerd met **MicroPdf417** barcode-specificatie |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MicroQR Code** barcode-specificatie |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Specificeert dat gegevens worden gecontroleerd met de meest gebruikte symbologieën |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **MSI Plessey** barcode-specificatie |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Niet-gespecificeerd decodeertype. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Specificeert dat de gegevens moeten worden gedecodeerd met de USPS **OneCode** barcode-specificatie |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **OPC** barcode-specificatie |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Patch code** barcode-specificatie. Barcode-symbologie wordt gebruikt voor geautomatiseerd scannen |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Pdf417** barcode-symbologie |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Pharmacode** barcode. Deze symbologie staat ook bekend als Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Planet** barcode-specificatie |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Specificeert dat gegevens worden gecontroleerd met alle **1.5D Postal** barcode-symbologieën, zoals **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Postnet** barcode-specificatie |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **PZN** barcode-specificatie. Deze symbologie staat ook bekend als Pharma Zentral Nummer. PZN7 en PZN8 worden ondersteund. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **QR Code** barcode-specificatie |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **RectMicroQR (rMQR) Code** barcode-specificatie |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **RM4SCC** barcode-specificatie. RM4SCC (Royal Mail 4-state Customer Code) wordt gebruikt voor geautomatiseerde postsortering in het VK. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **SCC14** barcode-specificatie |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **SSCC18** barcode-specificatie |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Standard 2 of 5** barcode-specificatie |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Supplement(EAN2, EAN5)** barcode-specificatie |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Swiss Post Parcel Barcode** barcode-specificatie |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Specificeert dat gegevens worden gecontroleerd met alle **1D** barcode-symbologieën |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Specificeert dat gegevens worden gecontroleerd met alle **2D** barcode-symbologieën |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **UPC-A** barcode-specificatie |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **UPC-E** barcode-specificatie |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Specificeert dat de gegevens moeten worden gedecodeerd met de **VIN** (Voertuigidentificatienummer) barcode-specificatie |

## Voorbeelden

Dit voorbeeld toont hoe Code39- en Code128-barcodes te detecteren.

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

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


