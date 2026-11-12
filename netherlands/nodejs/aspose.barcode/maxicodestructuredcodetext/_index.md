---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Basisklasse voor het coderen en decoderen van de in de MaxiCode-code ingebedde tekst voor modus 2 en 3."
type: docs
weight: 700
url: /nl/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Basisklasse voor het coderen en decoderen van de in de MaxiCode-code ingebedde tekst voor modus 2 en 3.

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

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven waarde. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construeert codetext |
| [getCountryCode()](#getcountrycode) | Identificeert de 3‑cijferige landcode. |
| [getHashCode()](#gethashcode) | Retourneert de hashcode voor deze instantie. |
| [getPostalCode()](#getpostalcode) | Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3. |
| [getSecondMessage()](#getsecondmessage) | Identificeert het tweede bericht van de barcode. |
| [getServiceCategory()](#getservicecategory) | Identificeert de 3‑cijferige servicecategorie. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [setCountryCode()](#setcountrycode) | Identificeert de 3‑cijferige landcode. |
| [setPostalCode()](#setpostalcode) | Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3. |
| [setSecondMessage()](#setsecondmessage) | Identificeert het tweede bericht van de barcode. |
| [setServiceCategory()](#setservicecategory) | Identificeert de 3‑cijferige servicecategorie. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een waarde om te vergelijken met deze instantie |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Construeert codetext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Identificeert de 3‑cijferige landcode.

### getHashCode() {#gethashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3.

### getSecondMessage() {#getsecondmessage}

Identificeert het tweede bericht van de barcode.

### getServiceCategory() {#getservicecategory}

Identificeert de 3‑cijferige servicecategorie.

### initFromString(constructedCodetext) {#initfromstring}

Initialiseert instantie vanuit geconstrueerde codetext.

| Parameter | Beschrijving |
| --- | --- |
| constructedCodetext | Geconstrueerde codetext. |

### setCountryCode() {#setcountrycode}

Identificeert de 3‑cijferige landcode.

### setPostalCode() {#setpostalcode}

Identificeert de postcode. Moet 9 cijfers zijn in modus 2 of 6 alfanumerieke tekens in modus 3.

### setSecondMessage() {#setsecondmessage}

Identificeert het tweede bericht van de barcode.

### setServiceCategory() {#setservicecategory}

Identificeert de 3‑cijferige servicecategorie.
