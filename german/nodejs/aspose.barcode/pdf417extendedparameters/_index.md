---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert Metadateninformationen von MacroPdf417 für einen erkannten Barcode."
type: docs
weight: 760
url: /de/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Speichert Metadateninformationen von MacroPdf417 für einen erkannten Barcode.

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Pdf417ExtendedParameters-Wert entspricht. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Macro PDF417 Empfängername (optional). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Macro PDF417 Prüfsumme (optional). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Liest die Datei-ID des Barcodes, nur verfügbar mit MacroPdf417. Wert: Die Datei-ID für MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Macro PDF417 Dateiname (optional). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Macro PDF417 Dateigröße (optional). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Liest die Segment-ID des Barcodes, nur verfügbar mit MacroPdf417. Wert: Die Segment-ID des Barcodes. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Liest die Anzahl der Macro PDF417 Barcode-Segmente. Standardwert ist -1. Wert: Segmentanzahl. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Macro PDF417 Absendername (optional). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Macro PDF417 Zeitstempel (optional). |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [isCode128Emulation()](#iscode128emulation) | Flag, das anzeigt, dass der MicroPdf417-Barcode mit den Emulationscodewörtern 908, 909, 910 oder 911 von Code 128 codiert wurde. |
| [isLinked()](#islinked) | Flag, das anzeigt, dass der Barcode mit einem 1D-Barcode verknüpft sein muss. Wert: Verknüpfungs-Flag |
| [isReaderInitialization()](#isreaderinitialization) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Pdf417ExtendedParameters zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Pdf417ExtendedParameters-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Macro PDF417 Empfängername (optional).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Macro PDF417 Prüfsumme (optional).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Liest die Datei-ID des Barcodes, nur verfügbar mit MacroPdf417. Wert: Die Datei-ID für MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Macro PDF417 Dateiname (optional).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Macro PDF417 Dateigröße (optional).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Liest die Segment-ID des Barcodes, nur verfügbar mit MacroPdf417. Wert: Die Segment-ID des Barcodes.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Liest die Anzahl der Macro PDF417 Barcode-Segmente. Standardwert ist -1. Wert: Segmentanzahl.

### getMacroPdf417Sender() {#getmacropdf417sender}

Macro PDF417 Absendername (optional).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Macro PDF417 Zeitstempel (optional).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Flag, das anzeigt, dass der MicroPdf417-Barcode mit den Emulationscodewörtern 908, 909, 910 oder 911 von Code 128 codiert wurde.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Flag, das anzeigt, dass der Barcode mit einem 1D-Barcode verknüpft sein muss. Wert: Verknüpfungs-Flag

### isReaderInitialization() {#isreaderinitialization}

Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

**Returns:** Reader initialization flag

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Pdf417ExtendedParameters zurück.

**Returns:** A string that represents this Pdf417ExtendedParameters.
