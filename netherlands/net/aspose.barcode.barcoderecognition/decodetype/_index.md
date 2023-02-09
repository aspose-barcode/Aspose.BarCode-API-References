---
title: DecodeType
second_title: Aspose.BarCode voor .NET API-referentie
description: Geef het type streepjescode op dat moet worden gelezen.
type: docs
weight: 190
url: /nl/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Geef het type streepjescode op dat moet worden gelezen.

```csharp
public static class DecodeType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Haalt een array op die AllSupportedTypes vertegenwoordigt |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Haalt een array op van de namen van de decoderingstypen. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Bepaalt of de opgegeven[`BaseDecodeType`](../basedecodetype/) bevat elke 1D barcode symbologie |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Bepaalt of de opgegeven[`BaseDecodeType`](../basedecodetype/) bevat elke 2D barcode symbologie |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Bepaalt of de opgegeven[`BaseDecodeType`](../basedecodetype/) bevat elke Postal barcode symbology |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een geretourneerde waarde geeft aan of de conversie is geslaagd of mislukt. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Specificeer scansets door barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultyDecodeType) | Converteert de tekenreeksrepresentatie van een MultyDecodeType naar zijn instantie. Een geretourneerde waarde geeft aan of de conversie is geslaagd of mislukt. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een geretourneerde waarde geeft aan of de conversie is geslaagd of mislukt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Geeft aan dat gegevens worden gecontroleerd met alle beschikbare symbologieën |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Australische post binnenlandse eParcel-streepjescode** streepjescodespecificatie |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Australische post** streepjescodespecificatie |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Azteken** streepjescodespecificatie |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **CODABAR** streepjescodespecificatie |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **CodablockF** streepjescodespecificatie |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **CODE 11** streepjescodespecificatie |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **CODE 128** streepjescodespecificatie |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **SCode16K** streepjescodespecificatie |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Code32** lege specificatie |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Verlengde CODE 39** streepjescodespecificatie |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Standaard CODE 39** streepjescodespecificatie |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Uitgebreide CODE 93** streepjescodespecificatie |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Standaard CODE 93** streepjescodespecificatie |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **CompactPdf417** (Pdf417Truncated) streepjescodespecificatie |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1 Databar uitgebreid** streepjescodespecificatie |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1 Databar uitgebreid gestapeld** streepjescodespecificatie |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1 Databar beperkt** streepjescodespecificatie |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1 Databar omnidirectioneel** streepjescodespecificatie |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1 Databar gestapeld** streepjescodespecificatie |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1 Databar gestapeld omnidirectioneel** streepjescodespecificatie |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1-gegevensbalk afgekapt** streepjescodespecificatie |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **DataLogic 2 van 5** lege specificatie |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **DataMatrix** barcode symbologie |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **DeutschePost-identificatiecode** streepjescodespecificatie |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **DeutschePost Leit-code** streepjescodespecificatie |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **DotCode** lege specificatie |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **DotCode** lege specificatie |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **EAN-13** streepjescodespecificatie |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **EAN14** streepjescodespecificatie |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **EAN-8** streepjescodespecificatie |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1-CODE 128** streepjescodespecificatie |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1DataMatrix** barcode symbologie |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1 DotCode** lege specificatie |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **GS1 QR** streepjescodespecificatie |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC LIC Azteken** lege specificatie |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC PAS Azteken** lege specificatie |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC LIC-code128** lege specificatie |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC PAS-code128** lege specificatie |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC LIC-code39** lege specificatie |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC PAS-code39** lege specificatie |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC LIC DataMatrix** lege specificatie |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC PAS DataMatrix** lege specificatie |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC LIC QR** lege specificatie |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **HIBC PAS QR** lege specificatie |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **IATA 2 van 5**streepjescode specificatie. IATA (International Air Transport Association) gebruikt deze barcode voor het beheer van luchtvracht. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **INTERLEAVED 2 van 5** streepjescodespecificatie |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **ISBN-nummer** streepjescodespecificatie |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **ISMN** streepjescodespecificatie |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **ISSN** streepjescodespecificatie |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Italiaanse Post 25** streepjescodespecificatie |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **ITF14** streepjescodespecificatie |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **ITF6** streepjescodespecificatie |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **MacroPdf417** streepjescodespecificatie |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Royal Mail-postzegel** streepjescodespecificatie. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Matrix 2 van 5** streepjescodespecificatie |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **MaxiCode** streepjescodespecificatie |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **MICR E-13B** lege specificatie |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **MicroPdf417** streepjescodespecificatie |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **MicroQR-code** streepjescodespecificatie |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Geeft aan dat gegevens worden gecontroleerd met de meest gebruikte symbologieën |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **MSI Plessey** streepjescodespecificatie |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Ongespecificeerd decoderingstype. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Geeft aan dat de gegevens moeten worden gedecodeerd met USPS **OneCode** streepjescodespecificatie |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **OPC** streepjescodespecificatie |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Patchcode** streepjescode specificatie. Barcodesymboliek wordt gebruikt voor geautomatiseerd scannen |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Pdf417** barcode symbologie |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Farmacode** streepjescode. Deze symboliek is ook bekend als Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Planeet** streepjescodespecificatie |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Geeft aan dat gegevens worden gecontroleerd met alle van **1.5D Post** streepjescodesymbolen, zoals **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Postnet** streepjescodespecificatie |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **PZN** streepjescode specificatie. Deze symboliek is ook bekend als Pharma Zentral Nummer |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **QR code** streepjescodespecificatie |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **RM4SCC** streepjescode specificatie. RM4SCC (Royal Mail 4-state Customer Code) wordt gebruikt voor geautomatiseerd postsorteerproces in het VK. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **VCA14** streepjescodespecificatie |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **SSCC18** streepjescodespecificatie |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Standaard 2 van 5** streepjescodespecificatie |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Toeslag(EAN2, EAN5)** streepjescodespecificatie |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **Zwitserse postpakketstreepjescode** streepjescodespecificatie |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Geeft aan dat gegevens worden gecontroleerd met alle van **1D** streepjescodesymbolen |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Geeft aan dat gegevens worden gecontroleerd met alle van **2D** streepjescodesymbolen |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **UPC-A** streepjescodespecificatie |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **UPC-E** streepjescodespecificatie |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Geeft aan waarmee de gegevens moeten worden gedecodeerd **VIN** (voertuigidentificatienummer) streepjescodespecificatie |

### Voorbeelden

Dit voorbeeld laat zien hoe Code39- en Code128-streepjescodes kunnen worden gedetecteerd.

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

### Zie ook

* naamruimte [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
