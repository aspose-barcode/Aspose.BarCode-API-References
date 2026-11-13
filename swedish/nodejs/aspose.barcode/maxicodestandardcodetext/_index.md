---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6."
type: docs
weight: 670
url: /sv/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om den här instansen är lika med ett angivet värde. |
| [getConstructedCodetext()](#getconstructedcodetext) | Skapar kodtext |
| [getHashCode()](#gethashcode) | Returnerar hashkoden för detta objekt. |
| [getMessage()](#getmessage) | Hämtar meddelande. |
| [getMode()](#getmode) | Hämtar MaxiCode-läge. |
| [initFromString(constructedCodetext)](#initfromstring) | Initierar objektet från konstruerad kodtext. |
| [setMessage()](#setmessage) | Ställer in meddelande. |
| [setMode()](#setmode) | Ställer in MaxiCode‑läge. Standard‑codetext kan endast användas med lägena 4, 5 och 6. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om den här instansen är lika med ett angivet värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett värde att jämföra med detta objekt. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Skapar kodtext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Hämtar meddelande.

### getMode() {#getmode}

Hämtar MaxiCode-läge.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Initierar objektet från konstruerad kodtext.

| Parameter | Beskrivning |
| --- | --- |
| constructedCodetext | Konstruerad kodtext. |

### setMessage() {#setmessage}

Ställer in meddelande.

### setMode() {#setmode}

Ställer in MaxiCode‑läge. Standard‑codetext kan endast användas med lägena 4, 5 och 6.
