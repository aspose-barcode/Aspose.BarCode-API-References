---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "ComplexCodetextReader decodifica il codetext al tipo di barcode complesso specificato."
type: docs
weight: 290
url: /it/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader decodifica il codetext al tipo di barcode complesso specificato.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Decodifica il codetext HIBC LIC. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Decodifica il codetext HIBC PAS. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Decodifica il codetext del codice a barre Mailmark C e L. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Decodifica il codetext Mailmark 2D di Royal Mail. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Decodifica il codetext MaxiCode. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Decodifica il codetext SwissQR. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Decodifica il codetext USADriveId. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Decodifica il codetext HIBC LIC.

| Parametro | Descrizione |
| --- | --- |
| encodedCodetext | codetext codificato |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Decodifica il codetext HIBC PAS.

| Parametro | Descrizione |
| --- | --- |
| encodedCodetext | codetext codificato |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Decodifica il codetext del codice a barre Mailmark C e L.

| Parametro | Descrizione |
| --- | --- |
| encodedCodetext | codetext codificato |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Decodifica il codetext Mailmark 2D di Royal Mail.

| Parametro | Descrizione |
| --- | --- |
| encodedCodetext | codetext codificato |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Decodifica il codetext MaxiCode.

| Parametro | Descrizione |
| --- | --- |
| maxiCodeMode | Modalità MaxiCode |
| encodedCodetext | codetext codificato |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Decodifica il codetext SwissQR.

| Parametro | Descrizione |
| --- | --- |
| encodedCodetext | codetext codificato |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Decodifica il codetext USADriveId.

| Parametro | Descrizione |
| --- | --- |
| encodedCodetext | Codetext codificato |

**Returns:** Decoded USADriveId or null.
