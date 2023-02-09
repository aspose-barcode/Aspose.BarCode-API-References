---
title: BarCodeReader
second_title: Aspose.BarCode voor .NET API-referentie
description: BarCodeReader kapselt een afbeelding in die een of meerdere streepjescodes kan bevatten en kan vervolgens de ReadBarCodesbewerking uitvoeren om streepjescodes te detecteren.
type: docs
weight: 60
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader kapselt een afbeelding in die een of meerdere streepjescodes kan bevatten, en kan vervolgens de ReadBarCodes-bewerking uitvoeren om streepjescodes te detecteren.

```csharp
public class BarCodeReader : Component
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse met standaardwaarden. Vereist het instellen van de afbeelding (SetBitmapImage()) voordat de methode ReadBarCodes() wordt aangeroepen. |
| [BarCodeReader](barcodereader/#constructor_1)(Bitmap) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse van een afbeelding. |
| [BarCodeReader](barcodereader/#constructor_8)(Stream) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_11)(string) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse uit bestand. |
| [BarCodeReader](barcodereader/#constructor_2)(Bitmap, BaseDecodeType) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_3)(Bitmap, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_9)(Stream, BaseDecodeType) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_10)(Stream, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_12)(string, BaseDecodeType) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_13)(string, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |
| [BarCodeReader](barcodereader/#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van het`BarCodeReader` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | De belangrijkste BarCode-decoderingsparameters. Bevat parameters die invloed hebben op herkende gegevens. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Wordt herkend[`BarCodeResult`](../barcoderesult/)s reeks |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Krijgt herkende barcodes tellen |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | Met QualitySettings kunt u de herkenningskwaliteit en -snelheid handmatig configureren. U kunt QualitySettings snel instellen met ingesloten presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes of u kunt handmatig afzonderlijke opties configureren. De standaardwaarde van QualitySettings is NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Haalt of stelt de time-out van het herkenningsproces in milliseconden in. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Krijgt instellingen voor het gebruik van processorcores. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Importeert BarCode-eigenschappen uit de opgegeven xml-stream en past deze toe op de huidige BarCodeReader-instantie. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Importeert BarCode-eigenschappen uit het opgegeven xml-bestand en past deze toe op de huidige BarCodeReader-instantie. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | Functie verzoekt om beëindiging van de huidige herkenningssessie vanuit een andere thread. Afbreken is een niet-blokkeerbare methode en geeft de controle direct na het aanroepen terug. De methode moet worden gebruikt als het herkenningsproces te lang duurt. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Exporteert streepjescode-eigenschappen naar de gespecificeerde xml-stream |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Exporteert streepjescode-eigenschappen naar het opgegeven xml-bestand |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | leest[`BarCodeResult`](../barcoderesult/) s van de afbeelding. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(Bitmap) | Stelt bitmapafbeelding in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Stream) | Stelt beeldstroom in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(string) | Stelt afbeeldingsbestand in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(Bitmap, Rectangle) | Stelt bitmapafbeelding en gebied in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(Bitmap, Rectangle[]) | Stelt bitmapafbeelding en gebieden voor herkenning in. Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype)(BaseDecodeType) | Stelt het decodeertype in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype_1)(params SingleDecodeType[]) | sets[`SingleDecodeType`](../singledecodetype/) typ array voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode. |

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
