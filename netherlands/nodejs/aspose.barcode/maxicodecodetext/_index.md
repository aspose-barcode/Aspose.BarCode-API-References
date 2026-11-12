---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Basisklasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode‑code."
type: docs
weight: 600
url: /nl/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Basisklasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode‑code. Deze voorbeeld toont hoe ruwe MaxiCode‑codetext te decoderen naar een MaxiCodeCodetext‑instantie.

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Haalt barcode type op. |
| [getECIEncoding()](#geteciencoding) | Haalt de ECI‑codering op. Wordt gebruikt wanneer MaxiCodeEncodeMode AUTO is. |
| [getEncodeMode()](#getencodemode) | Haalt een MaxiCode-coderingsmodus op. Standaardwaarde: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Haalt een MaxiCode-coderingsmodus op. |
| [getMode()](#getmode) | Haalt de MaxiCode-modus op. |
| [setECIEncoding()](#seteciencoding) | Stelt de ECI‑codering in. Wordt gebruikt wanneer MaxiCodeEncodeMode AUTO is. |
| [setEncodeMode(value)](#setencodemode) | Stelt een MaxiCode‑coderingsmodus in. Standaardwaarde: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Stelt een MaxiCode‑coderingsmodus in. |

### getBarcodeType() {#getbarcodetype}

Haalt barcode type op.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Haalt de ECI‑codering op. Wordt gebruikt wanneer MaxiCodeEncodeMode AUTO is.

### getEncodeMode() {#getencodemode}

Haalt een MaxiCode-coderingsmodus op. Standaardwaarde: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Haalt een MaxiCode-coderingsmodus op.

### getMode() {#getmode}

Haalt de MaxiCode-modus op.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Stelt de ECI‑codering in. Wordt gebruikt wanneer MaxiCodeEncodeMode AUTO is.

### setEncodeMode(value) {#setencodemode}

Stelt een MaxiCode‑coderingsmodus in. Standaardwaarde: Auto.

| Parameter | Beschrijving |
| --- | --- |
| waarde | een MaxiCode coderingsmodus. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Stelt een MaxiCode‑coderingsmodus in.
