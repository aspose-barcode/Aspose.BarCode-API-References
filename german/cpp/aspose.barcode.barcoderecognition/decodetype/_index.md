---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType Klasse"
linktitle: "DecodeType"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType Klasse. Gibt den Typ des zu lesenden Barcodes in C++ an."
type: docs
weight: 1600
url: /de/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


Geben Sie den zu lesenden Barcode-Typ an.

```cpp
class DecodeType
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | Ermittelt ein Array, das AllSupportedTypes darstellt |
| static [GetNames](./getnames/)() | Ruft ein Array der Namen der Decodierungstypen ab. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | Bestimmt, ob der angegebene [BaseDecodeType](../basedecodetype/) irgendeine 1D-Barcode-Symbologie enthält |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | Bestimmt, ob der angegebene [BaseDecodeType](../basedecodetype/) irgendeine 2D-Barcode-Symbologie enthält |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | Bestimmt, ob der angegebene [BaseDecodeType](../basedecodetype/) irgendeine Post-Barcode-Symbologie enthält |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [SingleDecodeType](../singledecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Geben Sie Scan-Sets anhand von barcodeTypes an |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [SingleDecodeType](../singledecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [MultiDecodeType](../multidecodetype/) in seine Instanz. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | Gibt an, dass Daten mit allen verfügbaren Symbologien überprüft werden |
| static [AustralianPosteParcel](./australianposteparcel/) | Gibt an, dass die Daten mit der **Australian Post Domestic eParcel Barcode** Barcode-Spezifikation decodiert werden sollen |
| static [AustraliaPost](./australiapost/) | Gibt an, dass die Daten mit der **Australia Post** Barcode-Spezifikation decodiert werden sollen |
| static [Aztec](./aztec/) | Gibt an, dass die Daten mit der **Aztec** Barcode-Spezifikation decodiert werden sollen |
| static [Codabar](./codabar/) | Gibt an, dass die Daten mit der **CODABAR** Barcode-Spezifikation decodiert werden sollen |
| static [CodablockF](./codablockf/) | Gibt an, dass die Daten mit der **CodablockF** Barcode-Spezifikation decodiert werden sollen |
| static [Code11](./code11/) | Gibt an, dass die Daten mit der **CODE 11** Barcode-Spezifikation decodiert werden sollen |
| static [Code128](./code128/) | Gibt an, dass die Daten mit der **CODE 128** Barcode-Spezifikation decodiert werden sollen |
| static [Code16K](./code16k/) | Gibt an, dass die Daten mit der **SCode16K** Barcode-Spezifikation decodiert werden sollen |
| static [Code32](./code32/) | Gibt an, dass die Daten mit der **Code32** Barcode-Spezifikation decodiert werden sollen |
| static [Code39](./code39/) | Gibt an, dass die Daten mit der **Code 39** Basiszeichensatz-Barcode-Spezifikation decodiert werden sollen: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | Gibt an, dass die Daten mit der **Code 39** vollständiger ASCII-Zeichensatz-Barcode-Spezifikation decodiert werden sollen: ISO/IEC 16388 |
| static [Code93](./code93/) | Gibt an, dass die Daten mit der **CODE 93** Barcode-Spezifikation decodiert werden sollen |
| static [CompactPdf417](./compactpdf417/) | Gibt an, dass die Daten mit der **CompactPdf417** (Pdf417Truncated) Barcode-Spezifikation decodiert werden sollen |
| static [DatabarExpanded](./databarexpanded/) | Gibt an, dass die Daten mit der **GS1 Databar expanded** Barcode-Spezifikation decodiert werden sollen |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | Gibt an, dass die Daten mit der **GS1 Databar expanded stacked** Barcode-Spezifikation decodiert werden sollen |
| static [DatabarLimited](./databarlimited/) | Gibt an, dass die Daten mit der **GS1 Databar limited** Barcode-Spezifikation decodiert werden sollen |
| static [DatabarOmniDirectional](./databaromnidirectional/) | Gibt an, dass die Daten mit der **GS1 Databar omni-directional** Barcode-Spezifikation decodiert werden sollen |
| static [DatabarStacked](./databarstacked/) | Gibt an, dass die Daten mit der **GS1 Databar stacked** Barcode-Spezifikation decodiert werden sollen |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | Gibt an, dass die Daten mit der **GS1 Databar stacked omni-directional** Barcode-Spezifikation decodiert werden sollen |
| static [DatabarTruncated](./databartruncated/) | Gibt an, dass die Daten mit **GS1 Databar truncated** Barcode-Spezifikation dekodiert werden sollen |
| static [DataLogic2of5](./datalogic2of5/) | Gibt an, dass die Daten mit **DataLogic 2 of 5** Barcode-Spezifikation dekodiert werden sollen |
| static [DataMatrix](./datamatrix/) | Gibt an, dass die Daten mit **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** Barcode-Symbologie dekodiert werden sollen |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Gibt an, dass die Daten mit **DeutschePost Ident code** Barcode-Spezifikation dekodiert werden sollen |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Gibt an, dass die Daten mit **DeutschePost Leit code** Barcode-Spezifikation dekodiert werden sollen |
| static [DotCode](./dotcode/) | Gibt an, dass die Daten mit **DotCode** Barcode-Spezifikation dekodiert werden sollen |
| static [DutchKIX](./dutchkix/) | Gibt an, dass die Daten mit **DotCode** Barcode-Spezifikation dekodiert werden sollen |
| static [EAN13](./ean13/) | Gibt an, dass die Daten mit **EAN-13** Barcode-Spezifikation dekodiert werden sollen |
| static [EAN14](./ean14/) | Gibt an, dass die Daten mit **EAN14** Barcode-Spezifikation dekodiert werden sollen |
| static [EAN8](./ean8/) | Gibt an, dass die Daten mit **EAN-8** Barcode-Spezifikation dekodiert werden sollen |
| static [GS1Aztec](./gs1aztec/) | Gibt an, dass die Daten mit **GS1 Aztec** Barcode-Spezifikation dekodiert werden sollen |
| static [GS1Code128](./gs1code128/) | Gibt an, dass die Daten mit **GS1 CODE 128** Barcode-Spezifikation dekodiert werden sollen |
| static [GS1CompositeBar](./gs1compositebar/) | Gibt an, dass die Daten mit **GS1 Composite Bar** Barcode-Spezifikation dekodiert werden sollen |
| static [GS1DataMatrix](./gs1datamatrix/) | Gibt an, dass die Daten mit **GS1DataMatrix** Barcode-Symbologie dekodiert werden sollen |
| static [GS1DotCode](./gs1dotcode/) | Gibt an, dass die Daten mit **GS1 DotCode** Barcode-Spezifikation dekodiert werden sollen |
| static [GS1HanXin](./gs1hanxin/) | Gibt an, dass die Daten mit **GS1 Han Xin Code** Barcode-Spezifikation dekodiert werden sollen |
| static [GS1MicroPdf417](./gs1micropdf417/) | Gibt an, dass die Daten mit **MicroPdf417** Barcode-Spezifikation dekodiert werden sollen |
| static [GS1QR](./gs1qr/) | Gibt an, dass die Daten mit **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** Barcode-Spezifikation dekodiert werden sollen |
| static [HanXin](./hanxin/) | Gibt an, dass die Daten mit **Han Xin Code** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCAztecLIC](./hibcazteclic/) | Gibt an, dass die Daten mit **HIBC LIC Aztec** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCAztecPAS](./hibcaztecpas/) | Gibt an, dass die Daten mit **HIBC PAS Aztec** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCCode128LIC](./hibccode128lic/) | Gibt an, dass die Daten mit **HIBC LIC Code128** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCCode128PAS](./hibccode128pas/) | Gibt an, dass die Daten mit **HIBC PAS Code128** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCCode39LIC](./hibccode39lic/) | Gibt an, dass die Daten mit **HIBC LIC Code39** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCCode39PAS](./hibccode39pas/) | Gibt an, dass die Daten mit **HIBC PAS Code39** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | Gibt an, dass die Daten mit **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | Gibt an, dass die Daten mit der **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCQRLIC](./hibcqrlic/) | Gibt an, dass die Daten mit der **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** Barcode-Spezifikation dekodiert werden sollen |
| static [HIBCQRPAS](./hibcqrpas/) | Gibt an, dass die Daten mit der **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** Barcode-Spezifikation dekodiert werden sollen |
| static [IATA2of5](./iata2of5/) | Gibt an, dass die Daten mit der **IATA 2 of 5** Barcode-Spezifikation dekodiert werden sollen. IATA (International Air Transport Association) verwendet diesen Barcode für die Verwaltung von Luftfracht. |
| static [Interleaved2of5](./interleaved2of5/) | Gibt an, dass die Daten mit der **INTERLEAVED 2 of 5** Barcode-Spezifikation dekodiert werden sollen |
| static [ISBN](./isbn/) | Gibt an, dass die Daten mit der **ISBN** Barcode-Spezifikation dekodiert werden sollen |
| static [ISMN](./ismn/) | Gibt an, dass die Daten mit der **ISMN** Barcode-Spezifikation dekodiert werden sollen |
| static [ISSN](./issn/) | Gibt an, dass die Daten mit der **ISSN** Barcode-Spezifikation dekodiert werden sollen |
| static [ItalianPost25](./italianpost25/) | Gibt an, dass die Daten mit der **Italian Post 25** Barcode-Spezifikation dekodiert werden sollen |
| static [ITF14](./itf14/) | Gibt an, dass die Daten mit der **ITF14** Barcode-Spezifikation dekodiert werden sollen |
| static [ITF6](./itf6/) | Gibt an, dass die Daten mit der **ITF6** Barcode-Spezifikation dekodiert werden sollen |
| static [JapanPost](./japanpost/) | Gibt an, dass die Daten mit der **Japan Post** Barcode-Spezifikation dekodiert werden sollen |
| static [MacroPdf417](./macropdf417/) | Gibt an, dass die Daten mit der **MacroPdf417** Barcode-Spezifikation dekodiert werden sollen |
| static [Mailmark](./mailmark/) | Gibt an, dass die Daten mit der **Royal Mail Mailmark** Barcode-Spezifikation dekodiert werden sollen. |
| static [Matrix2of5](./matrix2of5/) | Gibt an, dass die Daten mit der **Matrix 2 of 5** Barcode-Spezifikation dekodiert werden sollen |
| static [MaxiCode](./maxicode/) | Gibt an, dass die Daten mit der **MaxiCode** Barcode-Spezifikation dekodiert werden sollen |
| static [MicrE13B](./micre13b/) | Gibt an, dass die Daten mit der **MICR E-13B** Barcode-Spezifikation dekodiert werden sollen |
| static [MicroPdf417](./micropdf417/) | Gibt an, dass die Daten mit **MicroPdf417** Barcode-Spezifikation dekodiert werden sollen |
| static [MicroQR](./microqr/) | Gibt an, dass die Daten mit der **MicroQR Code** Barcode-Spezifikation dekodiert werden sollen |
| static [MostCommonTypes](./mostcommontypes/) | Gibt an, dass die Daten mit den am häufigsten verwendeten Symbolen überprüft werden |
| static [MSI](./msi/) | Gibt an, dass die Daten mit der **MSI Plessey** Barcode-Spezifikation dekodiert werden sollen |
| static [None](./none/) | Unbestimmter Dekodierungstyp. |
| static [OneCode](./onecode/) | Gibt an, dass die Daten mit der USPS **OneCode** Barcode-Spezifikation dekodiert werden sollen |
| static [OPC](./opc/) | Gibt an, dass die Daten mit der **OPC** Barcode-Spezifikation dekodiert werden sollen |
| static [PatchCode](./patchcode/) | Gibt an, dass die Daten mit der **Patch code** Barcode-Spezifikation dekodiert werden sollen. Die Barcode-Symbologie wird für automatisiertes Scannen verwendet |
| static [Pdf417](./pdf417/) | Gibt an, dass die Daten mit der **Pdf417** Barcode-Symbologie dekodiert werden sollen |
| static [Pharmacode](./pharmacode/) | Gibt an, dass die Daten mit dem **Pharmacode**-Barcode dekodiert werden sollen. Diese Symbologie ist auch als Pharmaceutical Binary Code bekannt. |
| static [Planet](./planet/) | Gibt an, dass die Daten mit der **Planet**-Barcode-Spezifikation dekodiert werden sollen. |
| static [PostalTypes](./postaltypes/) | Gibt an, dass die Daten mit allen **1.5D Postal**-Barcode-Symbologien geprüft werden, wie **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX**. |
| static [Postnet](./postnet/) | Gibt an, dass die Daten mit der **Postnet**-Barcode-Spezifikation dekodiert werden sollen. |
| static [PZN](./pzn/) | Gibt an, dass die Daten mit der **PZN**-Barcode-Spezifikation dekodiert werden sollen. Diese Symbologie ist auch als Pharma Zentral Nummer bekannt. PZN7 und PZN8 werden unterstützt. |
| static [QR](./qr/) | Gibt an, dass die Daten mit dem **[QR](../../aspose.barcode.barcoderecognition.qr/) Code**-Barcode dekodiert werden sollen. |
| static [RectMicroQR](./rectmicroqr/) | Gibt an, dass die Daten mit dem **RectMicroQR (rMQR) Code**-Barcode dekodiert werden sollen. |
| static [RM4SCC](./rm4scc/) | Gibt an, dass die Daten mit der **RM4SCC**-Barcode-Spezifikation dekodiert werden sollen. RM4SCC (Royal Mail 4-state Customer Code) wird für den automatisierten Postsortierprozess im Vereinigten Königreich verwendet. |
| static [SCC14](./scc14/) | Gibt an, dass die Daten mit der **SCC14**-Barcode-Spezifikation dekodiert werden sollen. |
| static [SSCC18](./sscc18/) | Gibt an, dass die Daten mit der **SSCC18**-Barcode-Spezifikation dekodiert werden sollen. |
| static [Standard2of5](./standard2of5/) | Gibt an, dass die Daten mit der **Standard 2 of 5**-Barcode-Spezifikation dekodiert werden sollen. |
| static [Supplement](./supplement/) | Gibt an, dass die Daten mit der **Supplement(EAN2, EAN5)**-Barcode-Spezifikation dekodiert werden sollen. |
| static [SwissPostParcel](./swisspostparcel/) | Gibt an, dass die Daten mit dem **Swiss Post Parcel Barcode**-Barcode dekodiert werden sollen. |
| static [Types1D](./types1d/) | Gibt an, dass die Daten mit allen **1D**-Barcode-Symbologien geprüft werden. |
| static [Types2D](./types2d/) | Gibt an, dass die Daten mit allen **2D**-Barcode-Symbologien geprüft werden. |
| static [UPCA](./upca/) | Gibt an, dass die Daten mit der **UPC-A**-Barcode-Spezifikation dekodiert werden sollen. |
| static [UPCE](./upce/) | Gibt an, dass die Daten mit der **UPC-E**-Barcode-Spezifikation dekodiert werden sollen. |
| static [VIN](./vin/) | Gibt an, dass die Daten mit der **VIN** (Vehicle Identification Number)-Barcode-Spezifikation dekodiert werden sollen. |
## Hinweise


Dieses Beispiel zeigt, wie Code39- und Code128-Barcodes erkannt werden.
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

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
