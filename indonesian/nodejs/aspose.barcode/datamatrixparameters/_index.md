---
title: "DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Parameter DataMatrix."
type: docs
weight: 360
url: /id/nodejs/aspose.barcode/datamatrixparameters/
---

## DataMatrixParameters class

Parameter DataMatrix.

```js
new DataMatrixParameters()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Rasio Tinggi/Lebar modul BarCode 2D. |
| [getColumns()](#getcolumns) | Jumlah kolom. |
| [getDataMatrixEcc()](#getdatamatrixecc) ~~(deprecated)~~ | Mendapatkan tipe ECC Datamatrix. Nilai default: DataMatrixEccType.ECC_200. |
| [getDataMatrixEncodeMode()](#getdatamatrixencodemode) ~~(deprecated)~~ | Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.AUTO. |
| [getDataMatrixVersion()](#getdatamatrixversion) ~~(deprecated)~~ | Mendapatkan ukuran simbol Datamatrix. Nilai default: DataMatrixVersion.Auto. |
| [getEccType()](#getecctype) | Mendapatkan tipe ECC Datamatrix. Nilai default: DataMatrixEccType.Ecc200. |
| [getECIEncoding()](#geteciencoding) | Mendapatkan enkoding ECI. Digunakan ketika DataMatrixEncodeMode dalam mode Auto. Nilai default: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Mode enkode barcode Datamatrix. Nilai default: EncodeMode.Auto. |
| [getMacroCharacters()](#getmacrocharacters) | ISO/IEC 16022 5.2.4.7 Karakter makro 11.3 Protokol untuk karakter makro pada posisi pertama (hanya ECC 200) Macro Cha |
| [getRows()](#getrows) | Jumlah baris. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | ID barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Jumlah barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | ID file untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [getVersion()](#getversion) | Mendapatkan ukuran simbol Datamatrix. Nilai default: Version.Auto. |
| [isReaderProgramming()](#isreaderprogramming) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setAspectRatio()](#setaspectratio) | Rasio Tinggi/Lebar modul BarCode 2D. |
| [setColumns()](#setcolumns) | Jumlah kolom. |
| [setDataMatrixEcc()](#setdatamatrixecc) ~~(deprecated)~~ | Menetapkan tipe ECC Datamatrix. Nilai default: DataMatrixEccType.ECC_200. |
| [setDataMatrixEncodeMode()](#setdatamatrixencodemode) ~~(deprecated)~~ | Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.AUTO. |
| [setDataMatrixVersion()](#setdatamatrixversion) ~~(deprecated)~~ | Menetapkan ukuran simbol Datamatrix. Nilai default: DataMatrixVersion.Auto. |
| [setEccType(value)](#setecctype) | Menetapkan tipe ECC Datamatrix. Nilai default: DataMatrixEccType.Ecc200. |
| [setECIEncoding()](#seteciencoding) | Menetapkan enkoding ECI. Digunakan ketika DataMatrixEncodeMode dalam mode Auto. Nilai default: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | Mode enkode barcode Datamatrix. Nilai default: EncodeMode.Auto. |
| [setMacroCharacters()](#setmacrocharacters) | ISO/IEC 16022 5.2.4.7 Karakter makro 11.3 Protokol untuk karakter makro pada posisi pertama (hanya ECC 200) Macro Cha |
| [setReaderProgramming()](#setreaderprogramming) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setRows()](#setrows) | Jumlah baris. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | ID barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Jumlah barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | ID file untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0 |
| [setVersion(value)](#setversion) | Menetapkan ukuran simbol Datamatrix. Nilai default: Version.Auto. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari DataMatrixParameters. |

### getAspectRatio() {#getaspectratio}

Rasio Tinggi/Lebar modul BarCode 2D.

### getColumns() {#getcolumns}

Jumlah kolom.

### getDataMatrixEcc() {#getdatamatrixecc}

> **Deprecated.** See method description for replacement.

Mendapatkan tipe ECC Datamatrix. Nilai default: DataMatrixEccType.ECC_200.

### getDataMatrixEncodeMode() {#getdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.AUTO.

### getDataMatrixVersion() {#getdatamatrixversion}

> **Deprecated.** See method description for replacement.

Mendapatkan ukuran simbol Datamatrix. Nilai default: DataMatrixVersion.Auto.

### getEccType() {#getecctype}

Mendapatkan tipe ECC Datamatrix. Nilai default: DataMatrixEccType.Ecc200.

**Returns:** a Datamatrix ECC type.

### getECIEncoding() {#geteciencoding}

Mendapatkan enkoding ECI. Digunakan ketika DataMatrixEncodeMode dalam mode Auto. Nilai default: ISO-8859-1

### getEncodeMode() {#getencodemode}

Mode enkode barcode Datamatrix. Nilai default: EncodeMode.Auto.

### getMacroCharacters() {#getmacrocharacters}

ISO/IEC 16022 5.2.4.7 Karakter makro 11.3 Protokol untuk karakter makro pada posisi pertama (hanya ECC 200) Nilai Karakter Makro 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan DataMatrixEccType.ECC_200 atau DataMatrixEccType.ECC_AUTO. Tidak dapat digunakan dengan EncodeTypes.GS_1_DATA_MATRIX Nilai default: MacroCharacter.NONE.

### getRows() {#getrows}

Jumlah baris.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

ID barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Jumlah barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

ID file untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0

### getVersion() {#getversion}

Mendapatkan ukuran simbol Datamatrix. Nilai default: Version.Auto.

**Returns:** a Datamatrix symbol size.

### isReaderProgramming() {#isreaderprogramming}

Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. Nilai default: false

### setAspectRatio() {#setaspectratio}

Rasio Tinggi/Lebar modul BarCode 2D.

### setColumns() {#setcolumns}

Jumlah kolom.

### setDataMatrixEcc() {#setdatamatrixecc}

> **Deprecated.** See method description for replacement.

Menetapkan tipe ECC Datamatrix. Nilai default: DataMatrixEccType.ECC_200.

### setDataMatrixEncodeMode() {#setdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Mode enkode barcode Datamatrix. Nilai default: DataMatrixEncodeMode.AUTO.

### setDataMatrixVersion() {#setdatamatrixversion}

> **Deprecated.** See method description for replacement.

Menetapkan ukuran simbol Datamatrix. Nilai default: DataMatrixVersion.Auto.

### setEccType(value) {#setecctype}

Menetapkan tipe ECC Datamatrix. Nilai default: DataMatrixEccType.Ecc200.

| Parameter | Deskripsi |
| --- | --- |
| nilai | sebuah tipe ECC Datamatrix. |

### setECIEncoding() {#seteciencoding}

Menetapkan enkoding ECI. Digunakan ketika DataMatrixEncodeMode dalam mode Auto. Nilai default: ISO-8859-1

### setEncodeMode() {#setencodemode}

Mode enkode barcode Datamatrix. Nilai default: EncodeMode.Auto.

### setMacroCharacters() {#setmacrocharacters}

ISO/IEC 16022 5.2.4.7 Karakter makro 11.3 Protokol untuk karakter makro pada posisi pertama (hanya ECC 200) Nilai Karakter Makro 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan DataMatrixEccType.ECC_200 atau DataMatrixEccType.ECC_AUTO. Tidak dapat digunakan dengan EncodeTypes.GS_1_DATA_MATRIX Nilai default: MacroCharacter.NONE.

### setReaderProgramming() {#setreaderprogramming}

Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. Nilai default: false

### setRows() {#setrows}

Jumlah baris.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

ID barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Jumlah barcode untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

ID file untuk mode Structured Append pada barcode Datamatrix. Nilai default: 0

### setVersion(value) {#setversion}

Menetapkan ukuran simbol Datamatrix. Nilai default: Version.Auto.

| Parameter | Deskripsi |
| --- | --- |
| nilai | ukuran simbol Datamatrix. |

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari DataMatrixParameters.

**Returns:** presentation of this DataMatrixParameters.
