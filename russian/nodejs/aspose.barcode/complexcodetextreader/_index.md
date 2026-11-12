---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "ComplexCodetextReader декодирует codetext в указанный тип сложного штрих‑кода."
type: docs
weight: 290
url: /ru/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader декодирует codetext в указанный тип сложного штрих‑кода.

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

## Методы

| Имя | Описание |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Декодирует HIBC LIC codetext. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Декодирует HIBC PAS codetext. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Декодирует Mailmark Barcode C и L codetext. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Декодирует Royal Mail Mailmark 2D codetext. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Декодирует MaxiCode codetext. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Декодирует SwissQR codetext. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Декодирует USADriveId codetext. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Декодирует HIBC LIC codetext.

| Параметр | Описание |
| --- | --- |
| encodedCodetext | закодированный codetext |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Декодирует HIBC PAS codetext.

| Параметр | Описание |
| --- | --- |
| encodedCodetext | закодированный codetext |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Декодирует Mailmark Barcode C и L codetext.

| Параметр | Описание |
| --- | --- |
| encodedCodetext | закодированный codetext |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Декодирует Royal Mail Mailmark 2D codetext.

| Параметр | Описание |
| --- | --- |
| encodedCodetext | закодированный codetext |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Декодирует MaxiCode codetext.

| Параметр | Описание |
| --- | --- |
| maxiCodeMode | Режим MaxiCode |
| encodedCodetext | закодированный codetext |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Декодирует SwissQR codetext.

| Параметр | Описание |
| --- | --- |
| encodedCodetext | закодированный codetext |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Декодирует USADriveId codetext.

| Параметр | Описание |
| --- | --- |
| encodedCodetext | Закодированный codetext |

**Returns:** Decoded USADriveId or null.
