---
title: "BarCodeReader"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die Operation ReadBarCodes ausführen, um Barcodes zu erkennen.

Der BarCodeReader-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| BarCodeReader() | Initialisiert eine neue Instanz der [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) Klasse mit Standardwerten.<br/>            Erfordert, dass ein Bild (SetBitmapImage()) gesetzt wird, bevor die Methode ReadBarCodes() aufgerufen wird. |
| BarCodeReader(image) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(image, decode_types) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(image, type) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(image, area, decode_types) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(image, area, type) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(image, areas, decode_types) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(image, areas, type) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(filename) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(filename, decode_types) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(filename, type) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(stream) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(stream, type) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(stream, decode_types) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(frame, areas, type) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(frame, areas, decode_types) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(frame, area, type) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(frame, area, decode_types) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(frame, type) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(frame, decode_types) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
| BarCodeReader(frame) | Initialisiert eine neue Instanz der BarCodeReader-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| processor_settings | Ruft eine Einstellung zur Verwendung von Prozessorkernen ab. |
| timeout | Ruft den Timeout des Erkennungsprozesses in Millisekunden ab oder legt ihn fest. |
| found_bar_codes | Ruft das Array erkannter [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s ab |
| found_count | Ruft die Anzahl erkannter Barcodes ab |
| quality_settings | QualitySettings ermöglicht es, die Erkennungsqualität und -geschwindigkeit manuell zu konfigurieren.<br/>            Sie können QualitySettings schnell über eingebettete Vorgaben einrichten: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes oder Sie können einzelne Optionen manuell konfigurieren.<br/>            Der Standardwert von QualitySettings ist NormalQuality. |
| barcode_settings | Die Hauptparameter für die Barcode‑Dekodierung. Enthält Parameter, die Einfluss auf die erkannten Daten haben. |
| bar_code_read_type | Liest oder setzt den Barcode-Dekodierungstyp, der für die Erkennung verwendet wird.<br/>            Muss gesetzt werden, bevor [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) aufgerufen wird. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| set_bar_code_image(value) | Legt das Bitmap-Bild für die Erkennung fest. <br/>            Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| set_bar_code_image(value, areas) | Legt das Bitmap-Bild und die Bereiche für die Erkennung fest. <br/>            Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| set_bar_code_image(value, area) | Legt das Bitmap-Bild und die Bereiche für die Erkennung fest. <br/>            Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| set_bar_code_image(filename) | Legt die Bilddatei für die Erkennung fest. <br/>            Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| set_bar_code_image(stream) | Legt den Bild-Stream für die Erkennung fest. <br/>            Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| set_bar_code_image(frame, area) | Legt den Luminanzrahmen und den Bereich für die Erkennung fest. Muss vor der Methode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) aufgerufen werden. |
| set_bar_code_image(frame, areas) | Legt den Luminanzrahmen und die Bereiche für die Erkennung fest. Muss vor der Methode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) aufgerufen werden. |
| set_bar_code_image(frame) | Legt den Luminanzrahmen und den Bereich für die Erkennung fest. Muss vor der Methode [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) aufgerufen werden. |
| export_to_xml(xml_file) | Exportiert BarCode-Eigenschaften in die angegebene XML-Datei |
| export_to_xml(xml_stream) | Exportiert BarCode-Eigenschaften in den angegebenen XML-Stream |
| import_from_xml(xml_file) | Importiert BarCode-Eigenschaften aus der angegebenen XML-Datei und wendet sie auf die aktuelle BarCodeReader-Instanz an. |
| import_from_xml(xml_stream) | Importiert BarCode-Eigenschaften aus dem angegebenen XML-Stream und wendet sie auf die aktuelle BarCodeReader-Instanz an. |
| abort() | Die Funktion fordert die Beendigung der aktuellen Erkennungssitzung von einem anderen Thread an. Abort ist eine nicht blockierbare Methode und gibt die Kontrolle sofort nach dem Aufruf zurück. <br/>            Die Methode sollte verwendet werden, wenn der Erkennungsprozess zu lange dauert. |
| read_bar_codes() | Liest [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s aus dem Bild. |
| set_bar_code_read_type(barcode_types) | Setzt das [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) Typ-Array für die Erkennung. <br/>            Muss vor der ReadBarCodes()-Methode aufgerufen werden. |

### Siehe auch

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

