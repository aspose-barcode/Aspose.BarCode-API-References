---
title: "Klasse BarCodeReader"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeReader Klasse. BarCodeReader kapselt ein Bild, das ein oder mehrere Barcodes enthalten kann, und kann dann die ReadBarCodes‑Operation ausführen, um Barcodes zu erkennen."
type: docs
weight: 70
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die ReadBarCodes‑Operation ausführen, um Barcodes zu erkennen.

```csharp
public class BarCodeReader : Component
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse mit Standardwerten. Erfordert, dass das Bild (SetBitmapImage()) gesetzt wird, bevor die Methode ReadBarCodes() aufgerufen wird. |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse aus einem Bild. |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse aus einem Luminanz‑Frame. |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_18)(string) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse aus einer Datei. |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | Initialisiert eine neue Instanz der `BarCodeReader`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | Liest oder setzt den Barcode‑Dekodierungstyp, der für die Erkennung verwendet wird. Muss gesetzt werden, bevor [`ReadBarCodes`](./readbarcodes/) aufgerufen wird. |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | Die Haupt‑BarCode‑Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten haben. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Liefert das erkannte [`BarCodeResult`](../barcoderesult/)-Array |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Liefert die Anzahl erkannter Barcodes |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren. Sie können QualitySettings schnell über integrierte Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, oder Sie können einzelne Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Liest oder setzt den Timeout des Erkennungsprozesses in Millisekunden. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Liest die Einstellung zur Nutzung von Prozessorkernen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Importiert BarCode‑Eigenschaften aus dem angegebenen XML‑Stream und wendet sie auf die aktuelle BarCodeReader‑Instanz an. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Importiert BarCode‑Eigenschaften aus der angegebenen XML‑Datei und wendet sie auf die aktuelle BarCodeReader‑Instanz an. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | Funktion fordert die Beendigung der aktuellen Erkennungssitzung von einem anderen Thread an. Abort ist eine nicht blockierbare Methode und gibt die Kontrolle unmittelbar nach dem Aufruf zurück. Die Methode sollte verwendet werden, wenn der Erkennungsprozess zu lange dauert. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Exportiert BarCode‑Eigenschaften in den angegebenen XML‑Stream |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Exportiert BarCode-Eigenschaften in die angegebene XML-Datei. |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Liest [`BarCodeResult`](../barcoderesult/)s aus dem Bild. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | Setzt das Bitmap-Bild für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | Setzt den Luminanzrahmen für die Erkennung. Muss vor der [`ReadBarCodes`](./readbarcodes/) Methode aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | Setzt den Bild-Stream für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | Setzt die Bilddatei für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | Setzt das Bitmap-Bild und den Bereich für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | Setzt das Bitmap-Bild und die Bereiche für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | Setzt den Luminanzrahmen und den Bereich für die Erkennung. Muss vor der [`ReadBarCodes`](./readbarcodes/) Methode aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | Setzt den Luminanzrahmen und die Bereiche für die Erkennung. Muss vor der [`ReadBarCodes`](./readbarcodes/) Methode aufgerufen werden. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | Setzt das [`SingleDecodeType`](../singledecodetype/) Typ-Array für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden. |

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


