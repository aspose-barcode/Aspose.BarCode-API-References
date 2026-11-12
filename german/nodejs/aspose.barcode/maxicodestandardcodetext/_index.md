---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren von MaxiCode-Codetext für die Modi 4, 5 und 6."
type: docs
weight: 670
url: /de/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Klasse zum Kodieren und Dekodieren von MaxiCode-Codetext für die Modi 4, 5 und 6.

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

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Wert entspricht. |
| [getConstructedCodetext()](#getconstructedcodetext) | Erstellt Codetext |
| [getHashCode()](#gethashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [getMessage()](#getmessage) | Liest Nachricht. |
| [getMode()](#getmode) | Liefert den MaxiCode-Modus. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [setMessage()](#setmessage) | Setzt Nachricht. |
| [setMode()](#setmode) | Setzt den MaxiCode-Modus. Standard‑Codetext kann nur mit den Modi 4, 5 und 6 verwendet werden. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein Wert zum Vergleich mit dieser Instanz. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Erstellt Codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Liest Nachricht.

### getMode() {#getmode}

Liefert den MaxiCode-Modus.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Initialisiert die Instanz aus dem erstellten Codetext.

| Parameter | Beschreibung |
| --- | --- |
| constructedCodetext | Erstellter Codetext. |

### setMessage() {#setmessage}

Setzt Nachricht.

### setMode() {#setmode}

Setzt den MaxiCode-Modus. Standard‑Codetext kann nur mit den Modi 4, 5 und 6 verwendet werden.
