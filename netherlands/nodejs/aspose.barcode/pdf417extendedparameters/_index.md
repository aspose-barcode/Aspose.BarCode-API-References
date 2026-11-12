---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat metadata-informatie van een herkende MacroPdf417 barcode op"
type: docs
weight: 760
url: /nl/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Slaat metadata-informatie van een herkende MacroPdf417 barcode op

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

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven Pdf417ExtendedParameters-waarde. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Macro PDF417-ontvangernaam (optioneel). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Macro PDF417-controlecode (optioneel). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Haalt de bestands-ID van de barcode op, alleen beschikbaar met MacroPdf417. Waarde: De bestands-ID voor MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Macro PDF417 bestandsnaam (optioneel). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Macro PDF417 bestandsgrootte (optioneel). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Haalt de segment-ID van de barcode,alleen beschikbaar met MacroPdf417.Waarde: De segment-ID van de barcode. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Haalt het aantal segmenten van de macro pdf417 barcode op. Standaardwaarde is -1.Waarde: Aantal segmenten. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Macro PDF417 afzendernaam (optioneel). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Macro PDF417 tijdstempel (optioneel). |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [isCode128Emulation()](#iscode128emulation) | Vlag die aangeeft dat de MicroPdf417 barcode is gecodeerd met 908, 909, 910 of 911 Code 128-emulatiecodewoorden. |
| [isLinked()](#islinked) | Vlag die aangeeft dat de barcode moet worden gekoppeld aan een 1D-barcode. Waarde: Koppelingvlag |
| [isReaderInitialization()](#isreaderinitialization) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Pdf417ExtendedParameters. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven Pdf417ExtendedParameters-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Macro PDF417-ontvangernaam (optioneel).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Macro PDF417-controlecode (optioneel).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Haalt de bestands-ID van de barcode op, alleen beschikbaar met MacroPdf417. Waarde: De bestands-ID voor MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Macro PDF417 bestandsnaam (optioneel).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Macro PDF417 bestandsgrootte (optioneel).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Haalt de segment-ID van de barcode,alleen beschikbaar met MacroPdf417.Waarde: De segment-ID van de barcode.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Haalt het aantal segmenten van de macro pdf417 barcode op. Standaardwaarde is -1.Waarde: Aantal segmenten.

### getMacroPdf417Sender() {#getmacropdf417sender}

Macro PDF417 afzendernaam (optioneel).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Macro PDF417 tijdstempel (optioneel).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Vlag die aangeeft dat de MicroPdf417 barcode is gecodeerd met 908, 909, 910 of 911 Code 128-emulatiecodewoorden.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Vlag die aangeeft dat de barcode moet worden gekoppeld aan een 1D-barcode. Waarde: Koppelingvlag

### isReaderInitialization() {#isreaderinitialization}

Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie.

**Returns:** Reader initialization flag

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Pdf417ExtendedParameters.

**Returns:** A string that represents this Pdf417ExtendedParameters.
