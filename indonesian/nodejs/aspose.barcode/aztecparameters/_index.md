---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Parameter Aztec."
type: docs
weight: 70
url: /id/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Parameter Aztec.

```js
new AztecParameters()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Rasio Tinggi/Lebar modul BarCode 2D. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Mendapatkan mode enkode Aztec. Nilai default: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Mendapatkan mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | Mendapatkan enkoding ECI. Digunakan ketika AztecEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Mendapatkan mode enkode Aztec. Nilai default: Auto. |
| [getErrorLevel()](#geterrorlevel) | Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95. |
| [getLayersCount()](#getlayerscount) | Mendapatkan jumlah lapisan simbol Aztec. Jumlah lapisan harus dalam rentang 1 hingga 3 untuk mode Compact dan dalam rentang 1 hingga 3 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | ID barcode untuk mode Structured Append pada barcode Aztec. ID barcode harus dalam rentang 1 hingga jumlah barcode. Default |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Jumlah barcode untuk mode Structured Append pada barcode Aztec. Jumlah barcode harus berada dalam rentang 1 hingga 26. Nilai default |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | ID File untuk mode Structured Append pada barcode Aztec (field opsional). ID File tidak boleh mengandung spasi. Nilai default: |
| [getSymbolMode()](#getsymbolmode) | Mendapatkan mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setAspectRatio()](#setaspectratio) | Rasio Tinggi/Lebar modul BarCode 2D. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Mengatur mode enkode Aztec. Nilai default: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Mengatur mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | Mengatur enkoding ECI. Digunakan ketika AztecEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Mengatur mode enkode Aztec. Nilai default: Auto. |
| [setErrorLevel()](#seterrorlevel) | Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95. |
| [setLayersCount()](#setlayerscount) | Mengatur jumlah lapisan simbol Aztec. Jumlah lapisan harus berada dalam rentang 1 hingga 3 untuk mode Compact dan dalam rentang 1 hingga 3 |
| [setReaderInitialization()](#setreaderinitialization) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | ID barcode untuk mode Structured Append pada barcode Aztec. ID barcode harus dalam rentang 1 hingga jumlah barcode. Default |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Jumlah barcode untuk mode Structured Append pada barcode Aztec. Jumlah barcode harus berada dalam rentang 1 hingga 26. Nilai default |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | ID File untuk mode Structured Append pada barcode Aztec (field opsional). ID File tidak boleh mengandung spasi. Nilai default: |
| [setSymbolMode(value)](#setsymbolmode) | Mengatur mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari `AztecParameters` ini. |

### getAspectRatio() {#getaspectratio}

Rasio Tinggi/Lebar modul BarCode 2D.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Mendapatkan mode enkode Aztec. Nilai default: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Mendapatkan mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

Mendapatkan enkoding ECI. Digunakan ketika AztecEncodeMode adalah Auto. Nilai default: ISO-8859-1

### getEncodeMode() {#getencodemode}

Mendapatkan mode enkode Aztec. Nilai default: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95.

### getLayersCount() {#getlayerscount}

Mendapatkan jumlah lapisan simbol Aztec. Jumlah lapisan harus berada dalam rentang 1 hingga 3 untuk mode Compact dan dalam rentang 1 hingga 32 untuk mode Full Range. Nilai default: 0 (auto).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

ID barcode untuk mode Structured Append pada barcode Aztec. ID barcode harus berada dalam rentang 1 hingga jumlah barcode. Nilai default: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Jumlah barcode untuk mode Structured Append pada barcode Aztec. Jumlah barcode harus berada dalam rentang 1 hingga 26. Nilai default: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

ID File untuk mode Structured Append pada barcode Aztec (field opsional). ID File tidak boleh mengandung spasi. Nilai default: string kosong

### getSymbolMode() {#getsymbolmode}

Mendapatkan mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

### setAspectRatio() {#setaspectratio}

Rasio Tinggi/Lebar modul BarCode 2D.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Mengatur mode enkode Aztec. Nilai default: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Mengatur mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

Mengatur enkoding ECI. Digunakan ketika AztecEncodeMode adalah Auto. Nilai default: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Mengatur mode enkode Aztec. Nilai default: Auto.

| Parameter | Deskripsi |
| --- | --- |
| nilai | sebuah mode enkode Aztec. |

### setErrorLevel() {#seterrorlevel}

Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95.

### setLayersCount() {#setlayerscount}

Mengatur jumlah lapisan simbol Aztec. Jumlah lapisan harus berada dalam rentang 1 hingga 3 untuk mode Compact dan dalam rentang 1 hingga 32 untuk mode Full Range. Nilai default: 0 (auto).

### setReaderInitialization() {#setreaderinitialization}

Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

ID barcode untuk mode Structured Append pada barcode Aztec. ID barcode harus berada dalam rentang 1 hingga jumlah barcode. Nilai default: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Jumlah barcode untuk mode Structured Append pada barcode Aztec. Jumlah barcode harus berada dalam rentang 1 hingga 26. Nilai default: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

ID File untuk mode Structured Append pada barcode Aztec (field opsional). ID File tidak boleh mengandung spasi. Nilai default: string kosong

### setSymbolMode(value) {#setsymbolmode}

Mengatur mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto.

| Parameter | Deskripsi |
| --- | --- |
| nilai | sebuah mode Simbol Aztec. |

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari `AztecParameters` ini.

**Returns:** A string that represents this `AztecParameters`.
