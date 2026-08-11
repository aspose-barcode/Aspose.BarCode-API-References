---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Base class for encoding and decoding the text embedded in the MaxiCode code."
type: docs
weight: 600
url: /nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Base class for encoding and decoding the text embedded in the MaxiCode code. This sample shows how to decode raw MaxiCode codetext to MaxiCodeCodetext instance.

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

## Methods

| Name | Description |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Gets barcode type. |
| [getECIEncoding()](#geteciencoding) | Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. |
| [getEncodeMode()](#getencodemode) | Gets a MaxiCode encode mode. Default value: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Gets a MaxiCode encode mode. |
| [getMode()](#getmode) | Gets MaxiCode mode. |
| [setECIEncoding()](#seteciencoding) | Sets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. |
| [setEncodeMode(value)](#setencodemode) | Sets a MaxiCode encode mode. Default value: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Sets a MaxiCode encode mode. |

### getBarcodeType() {#getbarcodetype}

Gets barcode type.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO.

### getEncodeMode() {#getencodemode}

Gets a MaxiCode encode mode. Default value: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Gets a MaxiCode encode mode.

### getMode() {#getmode}

Gets MaxiCode mode.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Sets ECI encoding. Used when MaxiCodeEncodeMode is AUTO.

### setEncodeMode(value) {#setencodemode}

Sets a MaxiCode encode mode. Default value: Auto.

| Parameter | Description |
| --- | --- |
| value | a MaxiCode encode mode. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Sets a MaxiCode encode mode.
