---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar metadata‑information för MacroPdf417 för igenkänd streckkod"
type: docs
weight: 760
url: /sv/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Lagrar metadata‑information för MacroPdf417 för igenkänd streckkod

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat Pdf417ExtendedParameters‑värde. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Macro PDF417 mottagarnamn (valfritt). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Macro PDF417 kontrollsumma (valfritt). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Hämtar fil‑ID för streckkoden, endast tillgängligt med MacroPdf417.Värde: Fil‑ID för MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Macro PDF417 filnamn (valfritt). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Macro PDF417 filstorlek (valfritt). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Hämtar segment‑ID för streckkoden, endast tillgängligt med MacroPdf417.Värde: Segment‑ID för streckkoden. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Hämtar antalet segment för macro pdf417‑streckkod. Standardvärdet är -1.Värde: Segmentantal. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Macro PDF417 avsändarnamn (valfritt). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Macro PDF417 tidsstämpel (valfritt). |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [isCode128Emulation()](#iscode128emulation) | Flagga som indikerar att MicroPdf417‑streckkoden är kodad med 908, 909, 910 eller 911 Code 128‑emuleringskodord. |
| [isLinked()](#islinked) | Flagga som indikerar att streckkoden måste länkas till en 1D‑streckkod. Värde: Länkningsflagga. |
| [isReaderInitialization()](#isreaderinitialization) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta Pdf417ExtendedParameters. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat Pdf417ExtendedParameters‑värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett System.Object-värde att jämföra med detta objekt. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Macro PDF417 mottagarnamn (valfritt).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Macro PDF417 kontrollsumma (valfritt).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Hämtar fil‑ID för streckkoden, endast tillgängligt med MacroPdf417.Värde: Fil‑ID för MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Macro PDF417 filnamn (valfritt).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Macro PDF417 filstorlek (valfritt).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Hämtar segment‑ID för streckkoden, endast tillgängligt med MacroPdf417.Värde: Segment‑ID för streckkoden.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Hämtar antalet segment för macro pdf417‑streckkod. Standardvärdet är -1.Värde: Segmentantal.

### getMacroPdf417Sender() {#getmacropdf417sender}

Macro PDF417 avsändarnamn (valfritt).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Macro PDF417 tidsstämpel (valfritt).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Flagga som indikerar att MicroPdf417‑streckkoden är kodad med 908, 909, 910 eller 911 Code 128‑emuleringskodord.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Flagga som indikerar att streckkoden måste länkas till en 1D‑streckkod. Värde: Länkningsflagga.

### isReaderInitialization() {#isreaderinitialization}

Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering.

**Returns:** Reader initialization flag

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta Pdf417ExtendedParameters.

**Returns:** A string that represents this Pdf417ExtendedParameters.
