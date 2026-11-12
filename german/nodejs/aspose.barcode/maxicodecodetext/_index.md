---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Basisklasse für das Codieren und Dekodieren des im MaxiCode-Code eingebetteten Textes."
type: docs
weight: 600
url: /de/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Basisklasse für das Codieren und Dekodieren des im MaxiCode-Code eingebetteten Textes. Dieses Beispiel zeigt, wie man rohen MaxiCode-Codetext in eine MaxiCodeCodetext-Instanz dekodiert.

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

| Name | Beschreibung |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Ermittelt den Barcode-Typ. |
| [getECIEncoding()](#geteciencoding) | Liest die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf AUTO steht. |
| [getEncodeMode()](#getencodemode) | Ermittelt einen MaxiCode-Kodierungsmodus. Standardwert: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Ermittelt einen MaxiCode-Kodierungsmodus. |
| [getMode()](#getmode) | Liefert den MaxiCode-Modus. |
| [setECIEncoding()](#seteciencoding) | Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf AUTO steht. |
| [setEncodeMode(value)](#setencodemode) | Legt einen MaxiCode-Codierungsmodus fest. Standardwert: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Legt einen MaxiCode-Codierungsmodus fest. |

### getBarcodeType() {#getbarcodetype}

Ermittelt den Barcode-Typ.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Liest die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf AUTO steht.

### getEncodeMode() {#getencodemode}

Ermittelt einen MaxiCode-Kodierungsmodus. Standardwert: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Ermittelt einen MaxiCode-Kodierungsmodus.

### getMode() {#getmode}

Liefert den MaxiCode-Modus.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf AUTO steht.

### setEncodeMode(value) {#setencodemode}

Legt einen MaxiCode-Codierungsmodus fest. Standardwert: Auto.

| Parameter | Beschreibung |
| --- | --- |
| Wert | ein MaxiCode-Codierungsmodus. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Legt einen MaxiCode-Codierungsmodus fest.
