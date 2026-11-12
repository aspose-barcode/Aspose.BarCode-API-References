---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode."
type: docs
weight: 600
url: /id/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode. Contoh ini menunjukkan cara mendekode codetext MaxiCode mentah menjadi instance MaxiCodeCodetext.

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Mendapatkan tipe barcode. |
| [getECIEncoding()](#geteciencoding) | Mendapatkan enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah AUTO. |
| [getEncodeMode()](#getencodemode) | Mendapatkan mode enkode MaxiCode. Nilai default: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Mendapatkan mode enkode MaxiCode. |
| [getMode()](#getmode) | Mendapatkan mode MaxiCode. |
| [setECIEncoding()](#seteciencoding) | Mengatur enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah AUTO. |
| [setEncodeMode(value)](#setencodemode) | Mengatur mode enkode MaxiCode. Nilai default: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Mengatur mode enkode MaxiCode. |

### getBarcodeType() {#getbarcodetype}

Mendapatkan tipe barcode.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Mendapatkan enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah AUTO.

### getEncodeMode() {#getencodemode}

Mendapatkan mode enkode MaxiCode. Nilai default: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Mendapatkan mode enkode MaxiCode.

### getMode() {#getmode}

Mendapatkan mode MaxiCode.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Mengatur enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah AUTO.

### setEncodeMode(value) {#setencodemode}

Mengatur mode enkode MaxiCode. Nilai default: Auto.

| Parameter | Deskripsi |
| --- | --- |
| nilai | sebuah mode enkode MaxiCode. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Mengatur mode enkode MaxiCode.
