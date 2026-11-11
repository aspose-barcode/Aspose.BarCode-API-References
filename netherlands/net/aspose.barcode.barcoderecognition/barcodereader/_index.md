---
title: "Klasse BarCodeReader"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeReader klasse. BarCodeReader omsluit een afbeelding die één of meerdere barcodes kan bevatten en kan vervolgens de ReadBarCodes‑bewerking uitvoeren om barcodes te detecteren"
type: docs
weight: 70
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader omvat een afbeelding die één of meerdere barcodes kan bevatten; deze kan vervolgens de ReadBarCodes‑operatie uitvoeren om barcodes te detecteren.

```csharp
public class BarCodeReader : Component
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse met standaardwaarden. Vereist dat de afbeelding (SetBitmapImage()) wordt ingesteld voordat de ReadBarCodes()‑methode wordt aangeroepen. |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse vanuit een afbeelding. |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse vanuit een luminantie‑frame. |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_18)(string) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse vanuit een bestand. |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | Initialiseert een nieuw exemplaar van de `BarCodeReader`‑klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | Haalt op of stelt het barcode‑decodeertype in dat wordt gebruikt voor herkenning. Moet worden ingesteld vóór het aanroepen van [`ReadBarCodes`](./readbarcodes/). |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | De belangrijkste BarCode-decoderingparameters. Bevat parameters die invloed hebben op de herkende gegevens. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Haalt de array met herkende [`BarCodeResult`](../barcoderesult/) op |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Haalt het aantal herkende barcodes op |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren. Je kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes of je kunt afzonderlijke opties handmatig configureren. De standaardwaarde van QualitySettings is NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Haalt op of stelt de time‑out van het herkenningsproces in milliseconden in. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Haalt een instelling op voor het gebruik van processorkernen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Importeert BarCode‑eigenschappen uit de opgegeven xml‑stream en past ze toe op de huidige BarCodeReader‑instantie. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Importeert BarCode‑eigenschappen uit het opgegeven xml‑bestand en past ze toe op de huidige BarCodeReader‑instantie. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | Functie vraagt beëindiging van de huidige herkenningssessie vanaf een andere thread. Abort is een onblokkeerbare methode en geeft de controle terug direct na het aanroepen. De methode moet worden gebruikt wanneer het herkenningsproces te lang duurt. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Exporteert BarCode‑eigenschappen naar de opgegeven xml‑stream. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Exporteert BarCode‑eigenschappen naar het opgegeven xml‑bestand. |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Leest [`BarCodeResult`](../barcoderesult/)s uit de afbeelding. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | Stelt bitmap‑afbeelding in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()‑methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | Stelt het luminantiekader in voor herkenning. Moet worden aangeroepen vóór de [`ReadBarCodes`](./readbarcodes/) methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | Stelt de afbeeldingsstroom in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | Stelt het afbeeldingsbestand in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | Stelt bitmapafbeelding en gebied in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | Stelt bitmapafbeelding en gebieden in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | Stelt het luminantiekader en gebied in voor herkenning. Moet worden aangeroepen vóór de [`ReadBarCodes`](./readbarcodes/) methode. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | Stelt het luminantiekader en gebieden in voor herkenning. Moet worden aangeroepen vóór de [`ReadBarCodes`](./readbarcodes/) methode. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | Stelt een [`SingleDecodeType`](../singledecodetype/) type-array in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes() methode. |

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


