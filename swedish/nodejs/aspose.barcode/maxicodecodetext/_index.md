---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Basklass för kodning och avkodning av texten inbäddad i MaxiCode-koden."
type: docs
weight: 600
url: /sv/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Basisklass för kodning och avkodning av text som är inbäddad i MaxiCode-koden. Detta exempel visar hur man avkodar rå MaxiCode-kodtext till en MaxiCodeCodetext-instans.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Hämtar streckkodstyp. |
| [getECIEncoding()](#geteciencoding) | Hämtar ECI-kodning. Används när MaxiCodeEncodeMode är AUTO. |
| [getEncodeMode()](#getencodemode) | Hämtar ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Hämtar ett MaxiCode-kodningsläge. |
| [getMode()](#getmode) | Hämtar MaxiCode-läge. |
| [setECIEncoding()](#seteciencoding) | Ställer in ECI-kodning. Används när MaxiCodeEncodeMode är AUTO. |
| [setEncodeMode(value)](#setencodemode) | Ställer in ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Ställer in ett MaxiCode-kodningsläge. |

### getBarcodeType() {#getbarcodetype}

Hämtar streckkodstyp.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Hämtar ECI-kodning. Används när MaxiCodeEncodeMode är AUTO.

### getEncodeMode() {#getencodemode}

Hämtar ett MaxiCode-kodningsläge. Standardvärde: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Hämtar ett MaxiCode-kodningsläge.

### getMode() {#getmode}

Hämtar MaxiCode-läge.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Ställer in ECI-kodning. Används när MaxiCodeEncodeMode är AUTO.

### setEncodeMode(value) {#setencodemode}

Ställer in ett MaxiCode-kodningsläge. Standardvärde: Auto.

| Parameter | Beskrivning |
| --- | --- |
| värde | ett MaxiCode-kodningsläge. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Ställer in ett MaxiCode-kodningsläge.
