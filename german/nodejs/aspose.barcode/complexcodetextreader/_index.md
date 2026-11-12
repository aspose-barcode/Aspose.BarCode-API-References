---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "ComplexCodetextReader dekodiert Codetext in den angegebenen komplexen Barcode-Typ."
type: docs
weight: 290
url: /de/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader dekodiert Codetext in den angegebenen komplexen Barcode-Typ.

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

| Name | Beschreibung |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Dekodiert HIBC LIC Codetext. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Dekodiert HIBC PAS Codetext. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Dekodiert Mailmark Barcode C und L Codetext. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Dekodiert Royal Mail Mailmark 2D Codetext. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Dekodiert MaxiCode Codetext. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Dekodiert SwissQR Codetext. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Dekodiert USADriveId Codetext. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Dekodiert HIBC LIC Codetext.

| Parameter | Beschreibung |
| --- | --- |
| encodedCodetext | kodierter Codetext |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Dekodiert HIBC PAS Codetext.

| Parameter | Beschreibung |
| --- | --- |
| encodedCodetext | kodierter Codetext |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Dekodiert Mailmark Barcode C und L Codetext.

| Parameter | Beschreibung |
| --- | --- |
| encodedCodetext | kodierter Codetext |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Dekodiert Royal Mail Mailmark 2D Codetext.

| Parameter | Beschreibung |
| --- | --- |
| encodedCodetext | kodierter Codetext |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Dekodiert MaxiCode Codetext.

| Parameter | Beschreibung |
| --- | --- |
| maxiCodeMode | MaxiCode-Modus |
| encodedCodetext | kodierter Codetext |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Dekodiert SwissQR Codetext.

| Parameter | Beschreibung |
| --- | --- |
| encodedCodetext | kodierter Codetext |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Dekodiert USADriveId Codetext.

| Parameter | Beschreibung |
| --- | --- |
| encodedCodetext | Kodierter Codetext |

**Returns:** Decoded USADriveId or null.
