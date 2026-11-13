---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "ComplexCodetextReader avkodar kodtext till angiven komplex streckkodstyp."
type: docs
weight: 290
url: /sv/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader avkodar kodtext till angiven komplex streckkodstyp.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Avkodar HIBC LIC kodtext. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Avkodar HIBC PAS kodtext. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Avkodar Mailmark-streckkod C och L kodtext. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Avkodar Royal Mail Mailmark 2D kodtext. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Avkodar MaxiCode kodtext. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Avkodar SwissQR kodtext. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Avkodar USADriveId kodtext. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Avkodar HIBC LIC kodtext.

| Parameter | Beskrivning |
| --- | --- |
| encodedCodetext | kodad kodtext |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Avkodar HIBC PAS kodtext.

| Parameter | Beskrivning |
| --- | --- |
| encodedCodetext | kodad kodtext |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Avkodar Mailmark-streckkod C och L kodtext.

| Parameter | Beskrivning |
| --- | --- |
| encodedCodetext | kodad kodtext |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Avkodar Royal Mail Mailmark 2D kodtext.

| Parameter | Beskrivning |
| --- | --- |
| encodedCodetext | kodad kodtext |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Avkodar MaxiCode kodtext.

| Parameter | Beskrivning |
| --- | --- |
| maxiCodeMode | MaxiCode läge |
| encodedCodetext | kodad kodtext |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Avkodar SwissQR kodtext.

| Parameter | Beskrivning |
| --- | --- |
| encodedCodetext | kodad kodtext |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Avkodar USADriveId kodtext.

| Parameter | Beskrivning |
| --- | --- |
| encodedCodetext | Kodad kodtext |

**Returns:** Decoded USADriveId or null.
