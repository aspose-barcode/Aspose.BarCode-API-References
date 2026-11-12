---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "ComplexCodetextReader mendekode codetext ke tipe barcode kompleks yang ditentukan."
type: docs
weight: 290
url: /id/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader mendekode codetext ke tipe barcode kompleks yang ditentukan.

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

## Metode

| Nama | Deskripsi |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Mendekode teks kode HIBC LIC. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Mendekode teks kode HIBC PAS. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Mendekode teks kode Barcode Mailmark C dan L. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Mendekode teks kode Royal Mail Mailmark 2D. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Mendekode teks kode MaxiCode. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Mendekode teks kode SwissQR. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Mendekode teks kode USADriveId. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Mendekode teks kode HIBC LIC.

| Parameter | Deskripsi |
| --- | --- |
| encodedCodetext | teks kode terenkode |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Mendekode teks kode HIBC PAS.

| Parameter | Deskripsi |
| --- | --- |
| encodedCodetext | teks kode terenkode |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Mendekode teks kode Barcode Mailmark C dan L.

| Parameter | Deskripsi |
| --- | --- |
| encodedCodetext | teks kode terenkode |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Mendekode teks kode Royal Mail Mailmark 2D.

| Parameter | Deskripsi |
| --- | --- |
| encodedCodetext | teks kode terenkode |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Mendekode teks kode MaxiCode.

| Parameter | Deskripsi |
| --- | --- |
| maxiCodeMode | Mode MaxiCode |
| encodedCodetext | teks kode terenkode |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Mendekode teks kode SwissQR.

| Parameter | Deskripsi |
| --- | --- |
| encodedCodetext | teks kode terenkode |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Mendekode teks kode USADriveId.

| Parameter | Deskripsi |
| --- | --- |
| encodedCodetext | Teks kode terenkode |

**Returns:** Decoded USADriveId or null.
