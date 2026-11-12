---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "ComplexCodetextReader يفك تشفير النص المشفر إلى نوع الباركود المعقد المحدد."
type: docs
weight: 290
url: /ar/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader يفك تشفير النص المشفر إلى نوع الباركود المعقد المحدد.

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

## طرق

| اسم | الوصف |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | يفك تشفير نص رمز HIBC LIC. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | يفك تشفير نص رمز HIBC PAS. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | يفك تشفير نص رمز شريط البريد Mailmark C و L. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | يفك تشفير نص رمز Mailmark ثنائي الأبعاد من Royal Mail. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | يفك تشفير نص رمز MaxiCode. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | يفك تشفير نص رمز SwissQR. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | يفك تشفير نص رمز USADriveId. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

يفك تشفير نص رمز HIBC LIC.

| معامل | الوصف |
| --- | --- |
| encodedCodetext | نص رمز مشفر |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

يفك تشفير نص رمز HIBC PAS.

| معامل | الوصف |
| --- | --- |
| encodedCodetext | نص رمز مشفر |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

يفك تشفير نص رمز شريط البريد Mailmark C و L.

| معامل | الوصف |
| --- | --- |
| encodedCodetext | نص رمز مشفر |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

يفك تشفير نص رمز Mailmark ثنائي الأبعاد من Royal Mail.

| معامل | الوصف |
| --- | --- |
| encodedCodetext | نص رمز مشفر |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

يفك تشفير نص رمز MaxiCode.

| معامل | الوصف |
| --- | --- |
| maxiCodeMode | وضع MaxiCode |
| encodedCodetext | نص رمز مشفر |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

يفك تشفير نص رمز SwissQR.

| معامل | الوصف |
| --- | --- |
| encodedCodetext | نص رمز مشفر |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

يفك تشفير نص رمز USADriveId.

| معامل | الوصف |
| --- | --- |
| encodedCodetext | نص رمز مشفر |

**Returns:** Decoded USADriveId or null.
