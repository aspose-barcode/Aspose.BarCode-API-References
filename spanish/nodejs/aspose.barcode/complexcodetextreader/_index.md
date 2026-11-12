---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "ComplexCodetextReader decodifica el codetext al tipo de código de barras complejo especificado."
type: docs
weight: 290
url: /es/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader decodifica el codetext al tipo de código de barras complejo especificado.

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Decodifica el codetext HIBC LIC. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Decodifica el codetext HIBC PAS. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Decodifica el codetext del código de barras Mailmark C y L. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Decodifica el codetext Mailmark 2D de Royal Mail. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Decodifica el codetext MaxiCode. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Decodifica el codetext SwissQR. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Decodifica el codetext USADriveId. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Decodifica el codetext HIBC LIC.

| Parámetro | Descripción |
| --- | --- |
| encodedCodetext | codetext codificado |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Decodifica el codetext HIBC PAS.

| Parámetro | Descripción |
| --- | --- |
| encodedCodetext | codetext codificado |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Decodifica el codetext del código de barras Mailmark C y L.

| Parámetro | Descripción |
| --- | --- |
| encodedCodetext | codetext codificado |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Decodifica el codetext Mailmark 2D de Royal Mail.

| Parámetro | Descripción |
| --- | --- |
| encodedCodetext | codetext codificado |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Decodifica el codetext MaxiCode.

| Parámetro | Descripción |
| --- | --- |
| maxiCodeMode | Modo MaxiCode |
| encodedCodetext | codetext codificado |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Decodifica el codetext SwissQR.

| Parámetro | Descripción |
| --- | --- |
| encodedCodetext | codetext codificado |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Decodifica el codetext USADriveId.

| Parámetro | Descripción |
| --- | --- |
| encodedCodetext | Codetext codificado |

**Returns:** Decoded USADriveId or null.
