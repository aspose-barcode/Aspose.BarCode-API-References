---
title: BarCodeReader
second_title: Aspose.BarCode för .NET API-referens
description: BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder den kan sedan utföra ReadBarCodes operation för att upptäcka streckkoder.
type: docs
weight: 60
url: /sv/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, den kan sedan utföra ReadBarCodes operation för att upptäcka streckkoder.

```csharp
public class BarCodeReader : Component
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | Initierar en ny instans av[`BarCodeReader`](../barcodereader) klass med standardvärden. Kräver att ställa in bild (SetBitmapImage()) innan metoden ReadBarCodes() anropas. |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) klass från en bild. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_11)(string) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) klass från fil. |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initierar en ny instans av[`BarCodeReader`](../barcodereader) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | De viktigaste streckkodsavkodningsparametrarna. Innehåller parametrar som påverkar igenkända data. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | Blir igenkänd[`BarCodeResult`](../barcoderesult)s array |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | Får igenkända streckkoder |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings gör det möjligt att konfigurera igenkänningskvalitet och -hastighet manuellt. Du kan snabbt ställa in QualitySettings genom inbäddade förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Settings. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | Hämtar eller ställer in timeout för igenkänningsprocessen i millisekunder. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | Får inställningar för användning av processorkärnor. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | Importerar BarCode-egenskaper från den angivna xml-strömmen och tillämpar dem på den aktuella BarCodeReader-instansen. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | Importerar BarCode-egenskaper från den angivna xml-filen och tillämpar dem på den aktuella BarCodeReader-instansen. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | Funktion begär avslutning av aktuell igenkänningssession från annan tråd. Avbryt är en avblockerbar metod och returnerar kontrollen direkt efter anropet. Metoden bör användas när igenkänningsprocessen är för lång. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | Exporterar streckkodsegenskaper till xml-strömmen specificerad |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | Exporterar streckkodsegenskaper till xml-filen specificerad |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | Läser[`BarCodeResult`](../barcoderesult) s från bilden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | Ställer in bitmappsbild för igenkänning. Måste anropas före metoden ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | Ställer in bildström för igenkänning. Måste anropas före metoden ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | Ställer in bildfil för igenkänning. Måste anropas före metoden ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | Ställer in bitmappsbild och område för igenkänning. Måste anropas före metoden ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | Ställer in bitmappsbild och områden för igenkänning. Måste anropas före metoden ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | Ställer in avkodningstyp för igenkänning. Måste anropas före metoden ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | Sets[`SingleDecodeType`](../singledecodetype) typ array för igenkänning. Måste anropas före metoden ReadBarCodes(). |

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
