---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Menyimpan informasi metadata MacroPdf417 dari barcode yang dikenali."
type: docs
weight: 760
url: /id/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Menyimpan informasi metadata MacroPdf417 dari barcode yang dikenali.

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [equals(obj)](#equals) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai Pdf417ExtendedParameters yang ditentukan. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Nama penerima Macro PDF417 (opsional). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Checksum Macro PDF417 (opsional). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Mendapatkan ID file barcode, hanya tersedia dengan MacroPdf417. Nilai: ID file untuk MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Nama file Macro PDF417 (opsional). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Ukuran file Macro PDF417 (opsional). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Mendapatkan ID segmen barcode, hanya tersedia dengan MacroPdf417. Nilai: ID segmen barcode. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Mendapatkan jumlah segmen barcode macro pdf417. Nilai default adalah -1. Nilai: Jumlah segmen. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Nama pengirim Macro PDF417 (opsional). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Stempel waktu Macro PDF417 (opsional). |
| [hashCode()](#hashcode) | Mengembalikan kode hash untuk instance ini. |
| [isCode128Emulation()](#iscode128emulation) | Bendera yang menunjukkan bahwa barcode MicroPdf417 dienkode dengan kode kata emulasi Code 128 908, 909, 910, atau 911. |
| [isLinked()](#islinked) | Bendera yang menunjukkan bahwa barcode harus terhubung ke barcode 1D. Nilai: Bendera tautan. |
| [isReaderInitialization()](#isreaderinitialization) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari Pdf417ExtendedParameters ini. |

### equals(obj) {#equals}

Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai Pdf417ExtendedParameters yang ditentukan.

| Parameter | Deskripsi |
| --- | --- |
| obj | Sebuah nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Nama penerima Macro PDF417 (opsional).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Checksum Macro PDF417 (opsional).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Mendapatkan ID file barcode, hanya tersedia dengan MacroPdf417. Nilai: ID file untuk MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Nama file Macro PDF417 (opsional).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Ukuran file Macro PDF417 (opsional).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Mendapatkan ID segmen barcode, hanya tersedia dengan MacroPdf417. Nilai: ID segmen barcode.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Mendapatkan jumlah segmen barcode macro pdf417. Nilai default adalah -1. Nilai: Jumlah segmen.

### getMacroPdf417Sender() {#getmacropdf417sender}

Nama pengirim Macro PDF417 (opsional).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Stempel waktu Macro PDF417 (opsional).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Mengembalikan kode hash untuk instance ini.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Bendera yang menunjukkan bahwa barcode MicroPdf417 dienkode dengan kode kata emulasi Code 128 908, 909, 910, atau 911.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Bendera yang menunjukkan bahwa barcode harus terhubung ke barcode 1D. Nilai: Bendera tautan.

### isReaderInitialization() {#isreaderinitialization}

Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

**Returns:** Reader initialization flag

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari Pdf417ExtendedParameters ini.

**Returns:** A string that represents this Pdf417ExtendedParameters.
