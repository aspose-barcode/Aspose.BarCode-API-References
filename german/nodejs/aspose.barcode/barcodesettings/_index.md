---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Die Haupt-Parameter für die BarCode-Dekodierung."
type: docs
weight: 150
url: /de/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

Die Haupt-Barcode-Dekodierungsparameter. Enthält Parameter, die Einfluss auf erkannte Daten haben.

```js
new BarcodeSettings(settings)
```

BarcodeSettings Kopierkonstruktor

| Parameter | Beschreibung |
| --- | --- |
| Einstellungen | Die Quelle der Daten |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Liefert die Dekodierungsparameter für AustraliaPost |
| [getChecksumValidation()](#getchecksumvalidation) | Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Postal-Barcodes. Standardmäßig wird dies für Symbologien, die eine Prüfsumme erfordern, als Ja behandelt. |
| [getDetectEncoding()](#getdetectencoding) | Das Flag, das die Engine zwingt, die Codetext-Kodierung für Unicode-Zeichensätze zu erkennen. Standardwert ist true. |
| [getStripFNC()](#getstripfnc) | Entfernt FNC1-, FNC2- und FNC3-Zeichen aus dem Codetext. Standardwert ist false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Gibt nur Barcode-Typen zurück, die explizit für die Erkennung angegeben wurden. Wenn aktiviert, werden erkannte Barcodes anderer kompatibler o |
| [setChecksumValidation(value)](#setchecksumvalidation) | Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Postal-Barcodes. Standardmäßig wird dies für Symbologien, die eine Prüfsumme erfordern, als Ja behandelt. |
| [setDetectEncoding()](#setdetectencoding) | Das Flag, das die Engine zwingt, die Codetext-Kodierung für Unicode-Zeichensätze zu erkennen. Standardwert ist true. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Gibt nur Barcode-Typen zurück, die explizit für die Erkennung angegeben wurden. Wenn aktiviert, werden erkannte Barcodes anderer kompatibler o |
| [setStripFNC(value)](#setstripfnc) | Entfernt FNC1-, FNC2- und FNC3-Zeichen aus dem Codetext. Standardwert ist false. |

### getAustraliaPost() {#getaustraliapost}

Liefert die Dekodierungsparameter für AustraliaPost

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Postal-Barcodes. Standardmäßig wird dies für Symbologien, die eine Prüfsumme enthalten müssen, als Ja behandelt, und als Nein, wo eine Prüfsumme nur optional ist. Prüfsumme wird nie verwendet: Codabar, PatchCode, Pharmacode, DataLogic2of5. Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Prüfsumme wird immer verwendet: übrige Symbologien.

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

Das Flag, das die Engine zwingt, die Codetext-Kodierung für Unicode-Zeichensätze zu erkennen. Standardwert ist true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

Entfernt FNC1-, FNC2- und FNC3-Zeichen aus dem Codetext. Standardwert ist false.

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

Gibt nur Barcode-Typen zurück, die explizit für die Erkennung angegeben wurden. Wenn aktiviert, werden erkannte Barcodes anderer kompatibler oder äquivalenter Typen herausgefiltert. Standardwert ist false. Beispiel: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Postal-Barcodes. Standardmäßig wird dies für Symbologien, die eine Prüfsumme enthalten müssen, als Ja behandelt, und als Nein, wo eine Prüfsumme nur optional ist. Prüfsumme wird nie verwendet: Codabar, PatchCode, Pharmacode, DataLogic2of5. Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Prüfsumme wird immer verwendet: übrige Symbologien.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Postal-Barcodes. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

Das Flag, das die Engine zwingt, die Codetext-Kodierung für Unicode-Zeichensätze zu erkennen. Standardwert ist true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

Gibt nur Barcode-Typen zurück, die explizit für die Erkennung angegeben wurden. Wenn aktiviert, werden erkannte Barcodes anderer kompatibler oder äquivalenter Typen herausgefiltert. Standardwert ist false. Beispiel: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Entfernt FNC1-, FNC2- und FNC3-Zeichen aus dem Codetext. Standardwert ist false.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Entfernt FNC1-, FNC2- und FNC3-Zeichen aus dem Codetext. Standardwert ist false. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
