---
title: "Klasse DecodeType"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.DecodeType Klasse. Gibt den Typ des zu lesenden Barcodes an"
type: docs
weight: 230
url: /de/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Geben Sie den zu lesenden Barcode‑Typ an.

```csharp
public static class DecodeType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Gibt ein Array zurück, das AllSupportedTypes darstellt |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Ruft ein Array mit den Namen der Dekodierungstypen ab. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Bestimmt, ob der angegebene [`BaseDecodeType`](../basedecodetype/) irgendeine 1D‑Barcode‑Symbolik enthält |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Bestimmt, ob der angegebene [`BaseDecodeType`](../basedecodetype/) irgendeine 2D‑Barcode‑Symbolik enthält |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Bestimmt, ob der angegebene [`BaseDecodeType`](../basedecodetype/) irgendeine Post‑Barcode‑Symbolik enthält |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Gib Scan‑Sätze nach barcodeTypes an |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Gibt an, dass Daten mit allen verfügbaren Symboliken geprüft werden |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Gibt an, dass die Daten mit der **Australian Post Domestic eParcel Barcode**‑Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Gibt an, dass die Daten mit der **Australia Post**‑Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Gibt an, dass die Daten mit der **Aztec**‑Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Gibt an, dass die Daten mit der **CODABAR**‑Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Gibt an, dass die Daten mit der **CodablockF**‑Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Gibt an, dass die Daten mit der **CODE 11**‑Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Gibt an, dass die Daten mit der **CODE 128**‑Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Gibt an, dass die Daten mit der **SCode16K**‑Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Gibt an, dass die Daten mit **Code32** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | Gibt an, dass die Daten mit **Code 39** Basiszeichensatz-Barcode-Spezifikation dekodiert werden sollen: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | Gibt an, dass die Daten mit **Code 39** vollständiger ASCII-Zeichensatz-Barcode-Spezifikation dekodiert werden sollen: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | Gibt an, dass die Daten mit **CODE 93** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Gibt an, dass die Daten mit **CompactPdf417** (Pdf417Truncated) Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Gibt an, dass die Daten mit **GS1 Databar expanded** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Gibt an, dass die Daten mit **GS1 Databar expanded stacked** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Gibt an, dass die Daten mit **GS1 Databar limited** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Gibt an, dass die Daten mit **GS1 Databar omni-directional** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Gibt an, dass die Daten mit **GS1 Databar stacked** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Gibt an, dass die Daten mit **GS1 Databar stacked omni-directional** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Gibt an, dass die Daten mit **GS1 Databar truncated** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Gibt an, dass die Daten mit **DataLogic 2 of 5** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Gibt an, dass die Daten mit **DataMatrix** Barcode-Symbologie dekodiert werden sollen |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Gibt an, dass die Daten mit **DeutschePost Ident code** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Gibt an, dass die Daten mit **DeutschePost Leit code** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Gibt an, dass die Daten mit **DotCode** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Gibt an, dass die Daten mit **DotCode** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Gibt an, dass die Daten mit **EAN-13** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Gibt an, dass die Daten mit **EAN14** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Gibt an, dass die Daten mit **EAN-8** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | Gibt an, dass die Daten mit **GS1 Aztec** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Gibt an, dass die Daten mit **GS1 CODE 128** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | Gibt an, dass die Daten mit **GS1 Composite Bar** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Gibt an, dass die Daten mit **GS1DataMatrix** Barcode-Symbologie dekodiert werden sollen |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Gibt an, dass die Daten mit **GS1 DotCode** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | Gibt an, dass die Daten mit **GS1 Han Xin Code** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | Gibt an, dass die Daten mit **MicroPdf417** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Gibt an, dass die Daten mit **GS1 QR** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | Gibt an, dass die Daten mit **Han Xin Code** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Gibt an, dass die Daten mit **HIBC LIC Aztec** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Gibt an, dass die Daten mit **HIBC PAS Aztec** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Gibt an, dass die Daten mit **HIBC LIC Code128** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Gibt an, dass die Daten mit **HIBC PAS Code128** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Gibt an, dass die Daten mit **HIBC LIC Code39** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Gibt an, dass die Daten mit **HIBC PAS Code39** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Gibt an, dass die Daten mit **HIBC LIC DataMatrix** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Gibt an, dass die Daten mit **HIBC PAS DataMatrix** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Gibt an, dass die Daten mit **HIBC LIC QR** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Gibt an, dass die Daten mit **HIBC PAS QR** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Gibt an, dass die Daten mit **IATA 2 of 5** Strichcode-Spezifikation dekodiert werden sollen. IATA (International Air Transport Association) verwendet diesen Strichcode für die Verwaltung von Luftfracht. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Gibt an, dass die Daten mit **INTERLEAVED 2 of 5** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Gibt an, dass die Daten mit **ISBN** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Gibt an, dass die Daten mit **ISMN** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Gibt an, dass die Daten mit **ISSN** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Gibt an, dass die Daten mit **Italian Post 25** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Gibt an, dass die Daten mit **ITF14** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Gibt an, dass die Daten mit **ITF6** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | Gibt an, dass die Daten mit **Japan Post** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Gibt an, dass die Daten mit **MacroPdf417** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Gibt an, dass die Daten mit **Royal Mail Mailmark** Strichcode-Spezifikation dekodiert werden sollen. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Gibt an, dass die Daten mit der **Matrix 2 of 5** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Gibt an, dass die Daten mit der **MaxiCode** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Gibt an, dass die Daten mit der **MICR E-13B** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Gibt an, dass die Daten mit **MicroPdf417** Strichcode-Spezifikation dekodiert werden sollen |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Gibt an, dass die Daten mit der **MicroQR Code** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Gibt an, dass Daten mit den am häufigsten verwendeten Symbolen geprüft werden |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Gibt an, dass die Daten mit der **MSI Plessey** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Nicht spezifizierter Dekodierungstyp. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Gibt an, dass die Daten mit der USPS **OneCode** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Gibt an, dass die Daten mit der **OPC** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Gibt an, dass die Daten mit der **Patch code** Barcode-Spezifikation dekodiert werden sollen. Die Barcode-Symbolik wird für automatisches Scannen verwendet |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Gibt an, dass die Daten mit der **Pdf417** Barcode-Symbolik dekodiert werden sollen |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Gibt an, dass die Daten mit dem **Pharmacode** Barcode dekodiert werden sollen. Diese Symbolik ist auch als Pharmaceutical Binary Code bekannt |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Gibt an, dass die Daten mit der **Planet** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Gibt an, dass Daten mit allen **1.5D Postal** Barcode-Symboliken geprüft werden, wie **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Gibt an, dass die Daten mit der **Postnet** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Gibt an, dass die Daten mit der **PZN** Barcode-Spezifikation dekodiert werden sollen. Diese Symbolik ist auch als Pharma Zentral Nummer bekannt. PZN7 und PZN8 werden unterstützt. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Gibt an, dass die Daten mit der **QR Code** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | Gibt an, dass die Daten mit der **RectMicroQR (rMQR) Code** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Gibt an, dass die Daten mit der **RM4SCC** Barcode-Spezifikation dekodiert werden sollen. RM4SCC (Royal Mail 4-state Customer Code) wird für den automatisierten Postsortierprozess im Vereinigten Königreich verwendet. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Gibt an, dass die Daten mit der **SCC14** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Gibt an, dass die Daten mit der **SSCC18** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Gibt an, dass die Daten mit der **Standard 2 of 5** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Gibt an, dass die Daten mit der **Supplement(EAN2, EAN5)** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Gibt an, dass die Daten mit der **Swiss Post Parcel Barcode** Barcode-Spezifikation dekodiert werden sollen |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Gibt an, dass Daten mit allen **1D** Barcode-Symboliken geprüft werden |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Gibt an, dass Daten mit allen **2D**-Barcode‑Symbologien geprüft werden |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Gibt an, dass die Daten mit der **UPC-A**-Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Gibt an, dass die Daten mit der **UPC-E**-Barcode‑Spezifikation dekodiert werden sollen |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Gibt an, dass die Daten mit der **VIN** (Vehicle Identification Number)-Barcode‑Spezifikation dekodiert werden sollen |

## Beispiele

Dieses Beispiel zeigt, wie man Code39- und Code128-Barcodes erkennt.

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

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


