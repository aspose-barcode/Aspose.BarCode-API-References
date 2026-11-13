---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Bas‑klass för kodning och avkodning av texten som är inbäddad i MaxiCode‑koden för lägena 2 och 3."
type: docs
weight: 700
url: /sv/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Bas‑klass för kodning och avkodning av texten som är inbäddad i MaxiCode‑koden för lägena 2 och 3.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om den här instansen är lika med ett angivet värde. |
| [getConstructedCodetext()](#getconstructedcodetext) | Skapar kodtext |
| [getCountryCode()](#getcountrycode) | Identifierar en 3-siffrig landskod. |
| [getHashCode()](#gethashcode) | Returnerar hashkoden för detta objekt. |
| [getPostalCode()](#getpostalcode) | Identifierar postnumret. Måste vara 9 siffror i läge 2 eller 6 alfanumeriska tecken i läge 3. |
| [getSecondMessage()](#getsecondmessage) | Identifierar det andra meddelandet i streckkoden. |
| [getServiceCategory()](#getservicecategory) | Identifierar en 3-siffrig tjänstekategori. |
| [initFromString(constructedCodetext)](#initfromstring) | Initierar objektet från konstruerad kodtext. |
| [setCountryCode()](#setcountrycode) | Identifierar en 3-siffrig landskod. |
| [setPostalCode()](#setpostalcode) | Identifierar postnumret. Måste vara 9 siffror i läge 2 eller 6 alfanumeriska tecken i läge 3. |
| [setSecondMessage()](#setsecondmessage) | Identifierar det andra meddelandet i streckkoden. |
| [setServiceCategory()](#setservicecategory) | Identifierar en 3-siffrig tjänstekategori. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om den här instansen är lika med ett angivet värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett värde att jämföra med den här instansen |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Skapar kodtext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Identifierar en 3-siffrig landskod.

### getHashCode() {#gethashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Identifierar postnumret. Måste vara 9 siffror i läge 2 eller 6 alfanumeriska tecken i läge 3.

### getSecondMessage() {#getsecondmessage}

Identifierar det andra meddelandet i streckkoden.

### getServiceCategory() {#getservicecategory}

Identifierar en 3-siffrig tjänstekategori.

### initFromString(constructedCodetext) {#initfromstring}

Initierar objektet från konstruerad kodtext.

| Parameter | Beskrivning |
| --- | --- |
| constructedCodetext | Konstruerad kodtext. |

### setCountryCode() {#setcountrycode}

Identifierar en 3-siffrig landskod.

### setPostalCode() {#setpostalcode}

Identifierar postnumret. Måste vara 9 siffror i läge 2 eller 6 alfanumeriska tecken i läge 3.

### setSecondMessage() {#setsecondmessage}

Identifierar det andra meddelandet i streckkoden.

### setServiceCategory() {#setservicecategory}

Identifierar en 3-siffrig tjänstekategori.
