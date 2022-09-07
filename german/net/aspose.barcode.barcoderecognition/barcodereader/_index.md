---
title: BarCodeReader
second_title: Aspose.BarCode für .NET-API-Referenz
description: BarCodeReader kapselt ein Bild ein das einen oder mehrere Barcodes enthalten kann und kann dann die ReadBarCodes-Operation ausführen um Barcodes zu erkennen.
type: docs
weight: 60
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader kapselt ein Bild ein, das einen oder mehrere Barcodes enthalten kann, und kann dann die ReadBarCodes-Operation ausführen, um Barcodes zu erkennen.

```csharp
public class BarCodeReader : Component
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BarCodeReader](barcodereader#constructor)() | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse mit Standardwerten. Erfordert das Setzen eines Bildes (SetBitmapImage()) vor dem Aufruf der Methode ReadBarCodes(). |
| [BarCodeReader](barcodereader#constructor_1)(Bitmap) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse aus einem Bild. |
| [BarCodeReader](barcodereader#constructor_8)(Stream) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_11)(string) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse aus Datei. |
| [BarCodeReader](barcodereader#constructor_2)(Bitmap, BaseDecodeType) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_3)(Bitmap, params BaseDecodeType[]) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_9)(Stream, BaseDecodeType) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_10)(Stream, params BaseDecodeType[]) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_12)(string, BaseDecodeType) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_13)(string, params BaseDecodeType[]) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |
| [BarCodeReader](barcodereader#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Initialisiert eine neue Instanz von[`BarCodeReader`](../barcodereader) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings) { get; } | Die wichtigsten BarCode-Decodierungsparameter. Enthält Parameter, die Einfluss auf erkannte Daten nehmen. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes) { get; } | Wird erkannt[`BarCodeResult`](../barcoderesult)s-Array |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount) { get; } | Ruft die Anzahl der erkannten Barcodes ab |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings) { get; set; } | QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell durch eingebettete Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oder Sie können separate Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout) { get; set; } | Ruft das Timeout des Erkennungsprozesses in Millisekunden ab oder setzt es. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings) { get; } | Ruft Einstellungen zur Verwendung von Prozessorkernen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml)(Stream) | Importiert BarCode-Eigenschaften aus dem angegebenen XML-Stream und wendet sie auf die aktuelle BarCodeReader-Instanz an. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml#importfromxml_1)(string) | Importiert BarCode-Eigenschaften aus der angegebenen XML-Datei und wendet sie auf die aktuelle BarCodeReader-Instanz an. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort)() | Die Funktion fordert die Beendigung der aktuellen Erkennungssitzung von einem anderen Thread an. Abort ist eine nicht blockierbare Methode und gibt die Kontrolle unmittelbar nach dem Aufruf zurück. Die Methode sollte angewendet werden, wenn der Erkennungsprozess zu lang ist. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml)(Stream) | Exportiert BarCode-Eigenschaften in den angegebenen XML-Stream |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml#exporttoxml_1)(string) | Exportiert BarCode-Eigenschaften in die XML-Datei spezifiziert |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes)() | liest[`BarCodeResult`](../barcoderesult) s aus dem Bild. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage)(Bitmap) | Legt ein Bitmap-Bild für die Erkennung fest. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_3)(Stream) | Legt den Bildstrom für die Erkennung fest. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_4)(string) | Legt die Bilddatei für die Erkennung fest. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_1)(Bitmap, Rectangle) | Legt Bitmap-Bild und Erkennungsbereich fest. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage#setbarcodeimage_2)(Bitmap, Rectangle[]) | Legt Bitmap-Bild und Erkennungsbereiche fest. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype)(BaseDecodeType) | Legt den Dekodierungstyp für die Erkennung fest. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype#setbarcodereadtype_1)(params SingleDecodeType[]) | Sätze[`SingleDecodeType`](../singledecodetype) Typ-Array zur Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden. |

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
