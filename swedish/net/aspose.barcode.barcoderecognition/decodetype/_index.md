---
title: DecodeType
second_title: Aspose.BarCode för .NET API-referens
description: Ange vilken typ av streckkod som ska läsas.
type: docs
weight: 190
url: /sv/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Ange vilken typ av streckkod som ska läsas.

```csharp
public static class DecodeType
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | Får en array som representerar AllSupportedTypes |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | Hämtar en uppsättning av namnen på avkodningstyperna. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | Bestämmer om den angivna[`BaseDecodeType`](../basedecodetype) innehåller valfri 1D streckkod symbology |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | Bestämmer om den angivna[`BaseDecodeType`](../basedecodetype) innehåller valfri 2D streckkod symbology |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | Bestämmer om den angivna[`BaseDecodeType`](../basedecodetype) innehåller alla streckkoder symbology |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde anger om konverteringen lyckades eller misslyckades. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | Ange skanningsuppsättningar med streckkodstyp |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | Konverterar strängrepresentationen av en MultyDecodeType till dess instans. Ett returvärde anger om konverteringen lyckades eller misslyckades. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde anger om konverteringen lyckades eller misslyckades. |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | Anger att data kommer att kontrolleras med alla tillgängliga symbologies |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | Anger att data ska avkodas med **Australian Post Domestic eParcel streckkod** streckkodsspecifikation |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | Anger att data ska avkodas med **Australia Post** streckkodsspecifikation |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | Anger att data ska avkodas med **Aztec** streckkodsspecifikation |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | Anger att data ska avkodas med **CODABAR** streckkodsspecifikation |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | Anger att data ska avkodas med **CodablockF** streckkodsspecifikation |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | Anger att data ska avkodas med **KOD 11** streckkodsspecifikation |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | Anger att data ska avkodas med **KOD 128** streckkodsspecifikation |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | Anger att data ska avkodas med **SCode16K** streckkodsspecifikation |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | Anger att data ska avkodas med **Kod32** blank specification |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | Anger att data ska avkodas med **Utökad KOD 39** streckkodsspecifikation |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | Anger att data ska avkodas med **Standard KOD 39** streckkodsspecifikation |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | Anger att data ska avkodas med **Utökad KOD 93** streckkodsspecifikation |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | Anger att data ska avkodas med **Standard KOD 93** streckkodsspecifikation |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | Anger att data ska avkodas med **Kompakt pdf417** (Pdf417Truncated) streckkodsspecifikation |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | Anger att data ska avkodas med **GS1 Databar utökad** streckkodsspecifikation |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | Anger att data ska avkodas med **GS1 Databar expanderad staplad** streckkodsspecifikation |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | Anger att data ska avkodas med **GS1 Databar begränsad** streckkodsspecifikation |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | Anger att data ska avkodas med **GS1 Databar rundstrålande** streckkodsspecifikation |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | Anger att data ska avkodas med **GS1-datafältet är staplat** streckkodsspecifikation |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | Anger att data ska avkodas med **GS1 Databar staplad rundstrålande** streckkodsspecifikation |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | Anger att data ska avkodas med **GS1 Databar trunkerad** streckkodsspecifikation |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | Anger att data ska avkodas med **DataLogic 2 av 5** blank specification |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | Anger att data ska avkodas med **DataMatrix** streckkod symbology |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | Anger att data ska avkodas med **DeutschePost ID-kod** streckkodsspecifikation |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | Anger att data ska avkodas med **DeutschePost Leit-kod** streckkodsspecifikation |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | Anger att data ska avkodas med **DotCode** blank specification |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | Anger att data ska avkodas med **DotCode** blank specification |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | Anger att data ska avkodas med **EAN-13** streckkodsspecifikation |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | Anger att data ska avkodas med **EAN14** streckkodsspecifikation |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | Anger att data ska avkodas med **EAN-8** streckkodsspecifikation |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | Anger att data ska avkodas med **GS1 KOD 128** streckkodsspecifikation |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | Anger att data ska avkodas med **GS1DataMatrix** streckkod symbology |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | Anger att data ska avkodas med **GS1 QR** streckkodsspecifikation |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | Anger att data ska avkodas med **IATA 2 av 5** streckkodsspecifikation. IATA (International Air Transport Association) använder denna streckkod för hantering av flygfrakt. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | Anger att data ska avkodas med **INTERLEAVERADE 2 av 5** streckkodsspecifikation |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | Anger att data ska avkodas med **ISBN** streckkodsspecifikation |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | Anger att data ska avkodas med **ISMN** streckkodsspecifikation |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | Anger att data ska avkodas med **ISSN** streckkodsspecifikation |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | Anger att data ska avkodas med **Italienska posten 25** streckkodsspecifikation |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | Anger att data ska avkodas med **ITF14** streckkodsspecifikation |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | Anger att data ska avkodas med **ITF6** streckkodsspecifikation |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | Anger att data ska avkodas med **MacroPdf417** streckkodsspecifikation |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | Anger att data ska avkodas med **Royal Mail Mailmark** streckkodsspecifikation. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | Anger att data ska avkodas med **Matris 2 av 5** streckkodsspecifikation |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | Anger att data ska avkodas med **MaxiCode** streckkodsspecifikation |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | Anger att data ska avkodas med **MICR E-13B** blank specification |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | Anger att data ska avkodas med **MicroPdf417** streckkodsspecifikation |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | Anger att data ska avkodas med **MicroQR-kod** streckkodsspecifikation |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | Anger att data kommer att kontrolleras med de vanligaste symbologies |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | Anger att data ska avkodas med **MSI Plessey** streckkodsspecifikation |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | Ospecificerad avkodningstyp. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | Anger att data ska avkodas med USPS **OneCode** streckkodsspecifikation |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | Anger att data ska avkodas med **OPC** streckkodsspecifikation |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | Anger att data ska avkodas med **Patchkod** streckkodsspecifikation. Streckkodssymbologi används för automatisk skanning |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | Anger att data ska avkodas med **Pdf417** streckkod symbology |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | Anger att data ska avkodas med **Farmakod** streckkod. Denna symbologi är också känd som Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | Anger att data ska avkodas med **Planet** streckkodsspecifikation |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | Anger att data ska kontrolleras med alla **1.5D Postal** streckkodssymboler, som **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | Anger att data ska avkodas med **Postnet** streckkodsspecifikation |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | Anger att data ska avkodas med **PZN**streckkodsspecifikation. Denna symbologi är också känd som Pharma Zentral Nummer |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | Anger att data ska avkodas med **QR-kod** streckkodsspecifikation |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | Anger att data ska avkodas med **RM4SCC** streckkodsspecifikation. RM4SCC (Royal Mail 4-stats kundkod) används för automatiserad postsorteringsprocess i Storbritannien. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | Anger att data ska avkodas med **SCC14** streckkodsspecifikation |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | Anger att data ska avkodas med **SSCC18** streckkodsspecifikation |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | Anger att data ska avkodas med **Standard 2 av 5** streckkodsspecifikation |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | Anger att data ska avkodas med **Tillägg(EAN2, EAN5)** streckkodsspecifikation |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | Anger att data ska avkodas med **Streckkod för schweizisk postpaket** streckkodsspecifikation |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | Anger att data ska kontrolleras med alla **1D** streckkod symbologies |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | Anger att data ska kontrolleras med alla **2D** streckkod symbologies |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | Anger att data ska avkodas med **UPC-A** streckkodsspecifikation |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | Anger att data ska avkodas med **UPC-E** streckkodsspecifikation |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | Anger att data ska avkodas med **VIN** (Fordonets identifieringsnummer) streckkodsspecifikation |

### Exempel

Detta exempel visar hur man upptäcker Code39 och Code128 streckkoder.

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

### Se även

* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
