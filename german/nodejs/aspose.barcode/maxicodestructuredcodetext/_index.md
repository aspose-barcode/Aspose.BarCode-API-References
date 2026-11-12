---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Basisklasse zum Kodieren und Dekodieren des im MaxiCode-Code eingebetteten Textes für die Modi 2 und 3."
type: docs
weight: 700
url: /de/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Basisklasse zum Kodieren und Dekodieren des im MaxiCode-Code eingebetteten Textes für die Modi 2 und 3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Wert entspricht. |
| [getConstructedCodetext()](#getconstructedcodetext) | Erstellt Codetext |
| [getCountryCode()](#getcountrycode) | Identifiziert den 3‑stelligen Ländercode. |
| [getHashCode()](#gethashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [getPostalCode()](#getpostalcode) | Identifiziert die Postleitzahl. Muss im Modus 2 aus 9 Ziffern oder im Modus 3 aus 6 alphanumerischen Zeichen bestehen. |
| [getSecondMessage()](#getsecondmessage) | Identifiziert die zweite Nachricht des Barcodes. |
| [getServiceCategory()](#getservicecategory) | Identifiziert die 3‑stellige Servicekategorie. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [setCountryCode()](#setcountrycode) | Identifiziert den 3‑stelligen Ländercode. |
| [setPostalCode()](#setpostalcode) | Identifiziert die Postleitzahl. Muss im Modus 2 aus 9 Ziffern oder im Modus 3 aus 6 alphanumerischen Zeichen bestehen. |
| [setSecondMessage()](#setsecondmessage) | Identifiziert die zweite Nachricht des Barcodes. |
| [setServiceCategory()](#setservicecategory) | Identifiziert die 3‑stellige Servicekategorie. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein Wert zum Vergleich mit dieser Instanz |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Erstellt Codetext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Identifiziert den 3‑stelligen Ländercode.

### getHashCode() {#gethashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Identifiziert die Postleitzahl. Muss im Modus 2 aus 9 Ziffern oder im Modus 3 aus 6 alphanumerischen Zeichen bestehen.

### getSecondMessage() {#getsecondmessage}

Identifiziert die zweite Nachricht des Barcodes.

### getServiceCategory() {#getservicecategory}

Identifiziert die 3‑stellige Servicekategorie.

### initFromString(constructedCodetext) {#initfromstring}

Initialisiert die Instanz aus dem erstellten Codetext.

| Parameter | Beschreibung |
| --- | --- |
| constructedCodetext | Erstellter Codetext. |

### setCountryCode() {#setcountrycode}

Identifiziert den 3‑stelligen Ländercode.

### setPostalCode() {#setpostalcode}

Identifiziert die Postleitzahl. Muss im Modus 2 aus 9 Ziffern oder im Modus 3 aus 6 alphanumerischen Zeichen bestehen.

### setSecondMessage() {#setsecondmessage}

Identifiziert die zweite Nachricht des Barcodes.

### setServiceCategory() {#setservicecategory}

Identifiziert die 3‑stellige Servicekategorie.
