---
title: DecodeType
second_title: Aspose.BarCode für .NET-API-Referenz
description: Geben Sie den Typ des zu lesenden Barcodes an.
type: docs
weight: 190
url: /de/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Geben Sie den Typ des zu lesenden Barcodes an.

```csharp
public static class DecodeType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | Ruft ein Array ab, das AllSupportedTypes darstellt |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | Ruft ein Array der Namen der Dekodierungstypen ab. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | Bestimmt, ob die angegebene[`BaseDecodeType`](../basedecodetype) enthält eine beliebige 1D-Barcode-Symbologie |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | Bestimmt, ob die angegebene[`BaseDecodeType`](../basedecodetype) enthält eine beliebige 2D-Barcode-Symbologie |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | Bestimmt, ob die angegebene[`BaseDecodeType`](../basedecodetype) enthält einen postalischen Barcode symbology |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | Konvertiert die Zeichenfolgendarstellung eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | Scansätze nach BarcodeTypes angeben |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | Konvertiert die Zeichenfolgendarstellung eines MultyDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | Konvertiert die Zeichenfolgendarstellung eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | Gibt an, dass Daten mit allen verfügbaren Symbologien geprüft werden |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | Gibt an, dass die Daten mit dekodiert werden sollen **Inlands-eParcel-Barcode der australischen Post** Barcodespezifikation |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | Gibt an, dass die Daten mit dekodiert werden sollen **Australische Post** Barcode-Spezifikation |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | Gibt an, dass die Daten mit dekodiert werden sollen **aztekisch** Barcode-Spezifikation |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | Gibt an, dass die Daten mit dekodiert werden sollen **CODABAR** Barcodespezifikation |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | Gibt an, dass die Daten mit dekodiert werden sollen **CodablockF** Barcode-Spezifikation |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | Gibt an, dass die Daten mit dekodiert werden sollen **KODEX 11** Barcodespezifikation |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | Gibt an, dass die Daten mit dekodiert werden sollen **CODE 128** Barcodespezifikation |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | Gibt an, dass die Daten mit dekodiert werden sollen **SCode16K** Barcode-Spezifikation |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | Gibt an, dass die Daten mit dekodiert werden sollen **Code32** leere Spezifikation |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | Gibt an, dass die Daten mit dekodiert werden sollen **Erweiterter CODE 39** Barcodespezifikation |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | Gibt an, dass die Daten mit dekodiert werden sollen **Standard-CODE 39** Barcodespezifikation |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | Gibt an, dass die Daten mit dekodiert werden sollen **Erweiterter CODE 93** Barcodespezifikation |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | Gibt an, dass die Daten mit dekodiert werden sollen **Standard-CODE 93** Barcodespezifikation |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | Gibt an, dass die Daten mit dekodiert werden sollen **KompaktPdf417** (Pdf417Truncated) Barcode-Spezifikation |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1 Databar erweitert** Barcode-Spezifikation |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1 Databar erweitert gestapelt** Barcode-Spezifikation |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1 Databar begrenzt** Barcode-Spezifikation |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1 Databar omnidirektional** Barcode-Spezifikation |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1 Databar gestapelt** Barcode-Spezifikation |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1 Databar gestapelt omnidirektional** Barcode-Spezifikation |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1 Databar abgeschnitten** Barcode-Spezifikation |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | Gibt an, dass die Daten mit dekodiert werden sollen **DataLogic 2 von 5** leere Spezifikation |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | Gibt an, dass die Daten mit dekodiert werden sollen **Datenmatrix** Strichcode-Symbologie |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | Gibt an, dass die Daten mit dekodiert werden sollen **DeutschePost Ident-Code** Barcodespezifikation |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | Gibt an, dass die Daten mit dekodiert werden sollen **DeutschePost Leitcode** Barcodespezifikation |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | Gibt an, dass die Daten mit dekodiert werden sollen **DotCode** leere Spezifikation |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | Gibt an, dass die Daten mit dekodiert werden sollen **DotCode** leere Spezifikation |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | Gibt an, dass die Daten mit dekodiert werden sollen **EAN-13** Barcodespezifikation |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | Gibt an, dass die Daten mit dekodiert werden sollen **EAN14** Barcode-Spezifikation |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | Gibt an, dass die Daten mit dekodiert werden sollen **EAN-8** Barcodespezifikation |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1-CODE 128** Barcodespezifikation |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1DataMatrix** Strichcode-Symbologie |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | Gibt an, dass die Daten mit dekodiert werden sollen **GS1-QR** Barcode-Spezifikation |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | Gibt an, dass die Daten mit dekodiert werden sollen **IATA 2 von 5** Barcode-Spezifikation. IATA (International Air Transport Association) verwendet diesen Barcode für die Verwaltung von Luftfracht. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | Gibt an, dass die Daten mit dekodiert werden sollen **INTERLEAVED 2 von 5** Barcodespezifikation |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | Gibt an, dass die Daten mit dekodiert werden sollen **ISBN** Barcodespezifikation |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | Gibt an, dass die Daten mit dekodiert werden sollen **ISMN** Barcodespezifikation |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | Gibt an, dass die Daten mit dekodiert werden sollen **ISSN** Barcodespezifikation |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | Gibt an, dass die Daten mit dekodiert werden sollen **Italienische Post 25** Barcodespezifikation |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | Gibt an, dass die Daten mit dekodiert werden sollen **ITF14** Barcode-Spezifikation |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | Gibt an, dass die Daten mit dekodiert werden sollen **ITF6** Barcodespezifikation |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | Gibt an, dass die Daten mit dekodiert werden sollen **MacroPdf417** Barcode-Spezifikation |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | Gibt an, dass die Daten mit dekodiert werden sollen **Royal Mail Poststempel** Barcode-Spezifikation. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | Gibt an, dass die Daten mit dekodiert werden sollen **Matrix 2 von 5** Barcodespezifikation |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | Gibt an, dass die Daten mit dekodiert werden sollen **MaxiCode** Barcode-Spezifikation |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | Gibt an, dass die Daten mit dekodiert werden sollen **MICR E-13B** leere Spezifikation |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | Gibt an, dass die Daten mit dekodiert werden sollen **MicroPdf417** Barcode-Spezifikation |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | Gibt an, dass die Daten mit dekodiert werden sollen **MicroQR-Code** Barcode-Spezifikation |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | Gibt an, dass Daten mit den am häufigsten verwendeten Symbologien überprüft werden |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | Gibt an, dass die Daten mit dekodiert werden sollen **MSI Plessey** Barcodespezifikation |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | Nicht spezifizierter Dekodierungstyp. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | Gibt an, dass die Daten mit USPS dekodiert werden sollen **OneCode** Barcode-Spezifikation |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | Gibt an, dass die Daten mit dekodiert werden sollen **OPC** Barcodespezifikation |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | Gibt an, dass die Daten mit dekodiert werden sollen **Patchcode** Barcode-Spezifikation. Barcode-Symbologie wird für automatisiertes Scannen verwendet |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | Gibt an, dass die Daten mit dekodiert werden sollen **Pdf417** Strichcode-Symbologie |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | Gibt an, dass die Daten mit dekodiert werden sollen **Pharmacode** Barcode. Diese Symbologie ist auch als Pharmaceutical Binary Code bekannt. |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | Gibt an, dass die Daten mit dekodiert werden sollen **Planet** Barcode-Spezifikation |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | Gibt an, dass Daten mit allen überprüft werden **1.5D Post** Barcode-Symbologien, wie **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | Gibt an, dass die Daten mit dekodiert werden sollen **Postnet** Barcodespezifikation |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | Gibt an, dass die Daten mit dekodiert werden sollen **PZN**Barcode-Spezifikation. Diese Symbologie ist auch als Pharma Zentral Nummer bekannt. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | Gibt an, dass die Daten mit dekodiert werden sollen **QR-Code** Barcode-Spezifikation |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | Gibt an, dass die Daten mit dekodiert werden sollen **RM4SCC** Barcode-Spezifikation. RM4SCC (Royal Mail 4-state Customer Code) wird für den automatisierten Postsortierprozess in Großbritannien verwendet. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | Gibt an, dass die Daten mit dekodiert werden sollen **SCC14** Barcode-Spezifikation |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | Gibt an, dass die Daten mit dekodiert werden sollen **SSCC18** Barcode-Spezifikation |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | Gibt an, dass die Daten mit dekodiert werden sollen **Standard 2 von 5** Barcodespezifikation |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | Gibt an, dass die Daten mit dekodiert werden sollen **Nachtrag (EAN2, EAN5)** Barcodespezifikation |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | Gibt an, dass die Daten mit dekodiert werden sollen **Paket-Barcode der Schweizerischen Post** Barcode-Spezifikation |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | Gibt an, dass Daten mit allen überprüft werden **1D** Barcode-Symbologien |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | Gibt an, dass Daten mit allen überprüft werden **2D** Barcode-Symbologien |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | Gibt an, dass die Daten mit dekodiert werden sollen **UPC-A** Barcodespezifikation |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | Gibt an, dass die Daten mit dekodiert werden sollen **UPC-E** Barcodespezifikation |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | Gibt an, dass die Daten mit dekodiert werden sollen **Fahrgestellnummer** (Fahrzeug-Identifizierungsnummer) Barcode-Spezifikation |

### Beispiele

Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.

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

### Siehe auch

* namensraum [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
