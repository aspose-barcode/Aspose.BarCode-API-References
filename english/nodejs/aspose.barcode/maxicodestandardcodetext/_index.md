---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6."
type: docs
weight: 670
url: /nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6.

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

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](#equals) | Returns a value indicating whether this instance is equal to a specified value. |
| [getConstructedCodetext()](#getconstructedcodetext) | Constructs codetext |
| [getHashCode()](#gethashcode) | Returns the hash code for this instance. |
| [getMessage()](#getmessage) | Gets message. |
| [getMode()](#getmode) | Gets MaxiCode mode. |
| [initFromString(constructedCodetext)](#initfromstring) | Initializes instance from constructed codetext. |
| [setMessage()](#setmessage) | Sets message. |
| [setMode()](#setmode) | Sets MaxiCode mode. Standart codetext can be used only with modes 4, 5 and 6. |

### equals(obj) {#equals}

Returns a value indicating whether this instance is equal to a specified value.

| Parameter | Description |
| --- | --- |
| obj | An value to compare to this instance. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Constructs codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Returns the hash code for this instance.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Gets message.

### getMode() {#getmode}

Gets MaxiCode mode.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Initializes instance from constructed codetext.

| Parameter | Description |
| --- | --- |
| constructedCodetext | Constructed codetext. |

### setMessage() {#setmessage}

Sets message.

### setMode() {#setmode}

Sets MaxiCode mode. Standart codetext can be used only with modes 4, 5 and 6.
