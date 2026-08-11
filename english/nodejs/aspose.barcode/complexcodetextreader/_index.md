---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "ComplexCodetextReader decodes codetext to specified complex barcode type."
type: docs
weight: 290
url: /nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader decodes codetext to specified complex barcode type.

```js
new ComplexCodetextReader()
```

**Example:**

```js
This sample shows how to recognize and decode SwissQR image.

 let cr = new BarCodeReader("SwissQRCodetext.png", null, DecodeType.QR);
 cr.read();
 let result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText(false));
```

## Methods

| Name | Description |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Decodes HIBC LIC codetext. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Decodes HIBC PAS codetext. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Decodes Mailmark Barcode C and L codetext. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Decodes Royal Mail Mailmark 2D codetext. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Decodes MaxiCode codetext. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Decodes SwissQR codetext. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Decodes USADriveId codetext. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Decodes HIBC LIC codetext.

| Parameter | Description |
| --- | --- |
| encodedCodetext | encoded codetext |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Decodes HIBC PAS codetext.

| Parameter | Description |
| --- | --- |
| encodedCodetext | encoded codetext |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Decodes Mailmark Barcode C and L codetext.

| Parameter | Description |
| --- | --- |
| encodedCodetext | encoded codetext |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Decodes Royal Mail Mailmark 2D codetext.

| Parameter | Description |
| --- | --- |
| encodedCodetext | encoded codetext |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Decodes MaxiCode codetext.

| Parameter | Description |
| --- | --- |
| maxiCodeMode | MaxiCode mode |
| encodedCodetext | encoded codetext |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Decodes SwissQR codetext.

| Parameter | Description |
| --- | --- |
| encodedCodetext | encoded codetext |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Decodes USADriveId codetext.

| Parameter | Description |
| --- | --- |
| encodedCodetext | Encoded codetext |

**Returns:** Decoded USADriveId or null.
