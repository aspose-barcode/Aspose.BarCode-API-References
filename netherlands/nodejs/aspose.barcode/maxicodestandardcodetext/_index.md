---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van MaxiCode-codetekst voor modus 4, 5 en 6."
type: docs
weight: 670
url: /nl/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Klasse voor het coderen en decoderen van MaxiCode-codetekst voor modus 4, 5 en 6.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven waarde. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construeert codetext |
| [getHashCode()](#gethashcode) | Retourneert de hashcode voor deze instantie. |
| [getMessage()](#getmessage) | Haalt bericht op. |
| [getMode()](#getmode) | Haalt de MaxiCode-modus op. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [setMessage()](#setmessage) | Stelt bericht in. |
| [setMode()](#setmode) | Stelt MaxiCode-modus in. Standaard codetext kan alleen worden gebruikt met modi 4, 5 en 6. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een waarde om te vergelijken met deze instantie. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Construeert codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Haalt bericht op.

### getMode() {#getmode}

Haalt de MaxiCode-modus op.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Initialiseert instantie vanuit geconstrueerde codetext.

| Parameter | Beschrijving |
| --- | --- |
| constructedCodetext | Geconstrueerde codetext. |

### setMessage() {#setmessage}

Stelt bericht in.

### setMode() {#setmode}

Stelt MaxiCode-modus in. Standaard codetext kan alleen worden gebruikt met modi 4, 5 en 6.
