---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "ComplexCodetextReader decodeert codetekst naar het opgegeven complexe barcodetype."
type: docs
weight: 290
url: /nl/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader decodeert codetekst naar het opgegeven complexe barcodetype.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Decodeert HIBC LIC-codetext. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Decodeert HIBC PAS-codetext. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Decodeert Mailmark Barcode C en L codetext. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Decodeert Royal Mail Mailmark 2D-codetext. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Decodeert MaxiCode-codetext. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Decodeert SwissQR-codetext. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Decodeert USADriveId-codetext. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Decodeert HIBC LIC-codetext.

| Parameter | Beschrijving |
| --- | --- |
| encodedCodetext | gecodeerde codetext |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Decodeert HIBC PAS-codetext.

| Parameter | Beschrijving |
| --- | --- |
| encodedCodetext | gecodeerde codetext |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Decodeert Mailmark Barcode C en L codetext.

| Parameter | Beschrijving |
| --- | --- |
| encodedCodetext | gecodeerde codetext |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Decodeert Royal Mail Mailmark 2D-codetext.

| Parameter | Beschrijving |
| --- | --- |
| encodedCodetext | gecodeerde codetext |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Decodeert MaxiCode-codetext.

| Parameter | Beschrijving |
| --- | --- |
| maxiCodeMode | MaxiCode-modus |
| encodedCodetext | gecodeerde codetext |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Decodeert SwissQR-codetext.

| Parameter | Beschrijving |
| --- | --- |
| encodedCodetext | gecodeerde codetext |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Decodeert USADriveId-codetext.

| Parameter | Beschrijving |
| --- | --- |
| encodedCodetext | Gecodeerde codetext |

**Returns:** Decoded USADriveId or null.
