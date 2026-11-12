---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Parameter PDF417."
type: docs
weight: 770
url: /id/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

Parameter PDF417. Berisi parameter PDF417, MacroPDF417, MicroPDF417, dan GS1MicroPdf417. MacroPDF417 memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lain bersifat opsional. MicroPDF417 dalam mode Structured Append (sama seperti mode MacroPDF417) memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lain bersifat opsional. Contoh-contoh ini menunjukkan cara mengkodekan mode non‑Linked UCC/EAN-128 dalam GS1MicroPdf417

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Rasio Tinggi/Lebar modul BarCode 2D. |
| [getColumns()](#getcolumns) | Jumlah kolom. |
| [getECIEncoding()](#geteciencoding) | Pengidentifikasi Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk |
| [getEncodeMode()](#getencodemode) | Mengidentifikasi mode enkode Pdf417. Nilai default: Auto. |
| [getErrorLevel()](#geterrorlevel) | Mendapatkan tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada koreksi kesalahan |
| [getMacroCharacters()](#getmacrocharacters) | Nilai Karakter Makro 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan Micro |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | nama penerima barcode MacroPdf417 (field opsional). nama penerima barcode MicroPDF417 (field opsional untuk Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | checksum barcode MacroPdf417 (field opsional). checksum barcode MicroPDF417 (field opsional untuk mode Structured Append) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append) |
| [getMacroPdf417FileName()](#getmacropdf417filename) | nama file barcode MacroPdf417 (field opsional). nama file barcode MicroPDF417 (field opsional untuk mode Structured Append) |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | ukuran file MacroPdf417 (field opsional). ukuran file MicroPDF417 (field opsional untuk mode Structured Append) Ukuran file |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0, hingga MacroSegmentsCount - 1. barcode MicroPDF417 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | jumlah segmen barcode MacroPdf417 (field opsional). jumlah segmen barcode MicroPDF417 (field opsional untuk Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | nama pengirim barcode MacroPdf417 (field opsional). nama pengirim barcode MicroPDF417 (field opsional untuk Structured Append) |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Digunakan untuk memberi tahu encoder apakah menambahkan Macro PDF417 Terminator (codeword 922) ke segmen. Diterapkan hanya untuk Macro PD |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | stempel waktu barcode MacroPdf417 (field opsional). stempel waktu barcode MicroPDF417 (field opsional untuk Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | tipe simbolologi Pdf417 dari mode kompaksi BarCode. Nilai default: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Pengidentifikasi Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Mengidentifikasi mode enkode Pdf417. Nilai default: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Mendapatkan tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada koreksi kesalahan |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Mendapatkan nama penerima barcode macro Pdf417. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Mendapatkan checksum barcode macro Pdf417. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Mendapatkan ID file barcode Pdf417 macro. Digunakan untuk MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Mendapatkan nama file barcode macro Pdf417. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Mendapatkan ukuran file macro Pdf417. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Mendapatkan ID segmen barcode macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Mendapatkan jumlah segmen barcode macro Pdf417. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Mendapatkan nama pengirim barcode macro Pdf417. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Digunakan untuk memberi tahu encoder apakah menambahkan Macro PDF417 Terminator (codeword 922) ke segmen. Diterapkan hanya untuk Macro PD |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Mendapatkan stempel waktu barcode macro Pdf417. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). |
| [getRows()](#getrows) | Jumlah baris. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Mengidentifikasi ID barcode mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan barcode |
| [getTruncate()](#gettruncate) | Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan |
| [isCode128Emulation()](#iscode128emulation) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua mode 908 dan |
| [isLinked()](#islinked) | Mendefinisikan mode terhubung dengan kode batang GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbol GS1MicroPdf417 mengkodekan 906, 907. |
| [isReaderInitialization()](#isreaderinitialization) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setAspectRatio()](#setaspectratio) | Rasio Tinggi/Lebar modul BarCode 2D. |
| [setCode128Emulation()](#setcode128emulation) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua mode 908 dan |
| [setColumns()](#setcolumns) | Jumlah kolom. |
| [setECIEncoding()](#seteciencoding) | Pengidentifikasi Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk |
| [setEncodeMode()](#setencodemode) | Mengidentifikasi mode enkode Pdf417. Nilai default: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Mengatur tipe simbol Pdf417 pada tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada koreksi kesalahan. |
| [setLinked()](#setlinked) | Mendefinisikan mode terhubung dengan kode batang GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbol GS1MicroPdf417 mengkodekan 906, 907. |
| [setMacroCharacters()](#setmacrocharacters) | Nilai Karakter Makro 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan Micro |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | nama penerima barcode MacroPdf417 (field opsional). nama penerima barcode MicroPDF417 (field opsional untuk Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | checksum barcode MacroPdf417 (field opsional). checksum barcode MicroPDF417 (field opsional untuk mode Structured Append) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append) |
| [setMacroPdf417FileName()](#setmacropdf417filename) | nama file barcode MacroPdf417 (field opsional). nama file barcode MicroPDF417 (field opsional untuk mode Structured Append) |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | ukuran file MacroPdf417 (field opsional). ukuran file MicroPDF417 (field opsional untuk mode Structured Append) Ukuran file |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0, hingga MacroSegmentsCount - 1. barcode MicroPDF417 |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | jumlah segmen barcode MacroPdf417 (field opsional). jumlah segmen barcode MicroPDF417 (field opsional untuk Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | nama pengirim barcode MacroPdf417 (field opsional). nama pengirim barcode MicroPDF417 (field opsional untuk Structured Append) |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Digunakan untuk memberi tahu encoder apakah menambahkan Macro PDF417 Terminator (codeword 922) ke segmen. Diterapkan hanya untuk Macro PD |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | stempel waktu barcode MacroPdf417 (field opsional). stempel waktu barcode MicroPDF417 (field opsional untuk Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | tipe simbolologi Pdf417 dari mode kompaksi BarCode. Nilai default: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Pengidentifikasi Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Mengidentifikasi mode enkode Pdf417. Nilai default: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Mengatur tipe simbol Pdf417 pada tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada koreksi kesalahan. |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Mengatur nama penerima kode batang macro Pdf417. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Mengatur checksum kode batang macro Pdf417. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Mengatur ID file kode batang macro Pdf417. Digunakan untuk MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Mengatur nama file macro Pdf417. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Mengatur ukuran file macro Pdf417. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Mengatur ID segmen kode batang macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Mengatur jumlah segmen kode batang macro Pdf417. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Mengatur nama pengirim kode batang macro Pdf417. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Digunakan untuk memberi tahu encoder apakah menambahkan Macro PDF417 Terminator (codeword 922) ke segmen. Diterapkan hanya untuk Macro PD |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Mengatur cap waktu kode batang macro Pdf417. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). |
| [setReaderInitialization(value)](#setreaderinitialization) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setRows()](#setrows) | Jumlah baris. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Mengidentifikasi ID barcode mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan barcode |
| [setTruncate()](#settruncate) | Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan |
| [toString()](#tostring) | Mengembalikan representasi string yang dapat dibaca manusia dari Pdf417Parameters ini. |

### getAspectRatio() {#getaspectratio}

Rasio Tinggi/Lebar modul BarCode 2D.

### getColumns() {#getcolumns}

Jumlah kolom.

### getECIEncoding() {#geteciencoding}

Identifier Interpretasi Saluran Terluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan pada bidang teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean charset yang dikenal.

### getEncodeMode() {#getencodemode}

Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

### getErrorLevel() {#geterrorlevel}

Mendapatkan tipe simbol Pdf417 pada tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada informasi koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh pengkodean yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode MicroPdf417 916 serta 917. Nilai default: MacroCharacters.None. Contoh-contoh ini menunjukkan cara mengkodekan Macro Characters dalam MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Nama penerima kode batang MacroPdf417 (field opsional). Nama penerima kode batang MicroPDF417 (field opsional untuk mode Structured Append).

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Checksum kode batang MacroPdf417 (field opsional). Checksum kode batang MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1.

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417.

### getMacroPdf417FileID() {#getmacropdf417fileid}

ID file kode batang MacroPdf417 (field wajib). ID file kode batang MicroPDF417 (field wajib untuk mode Structured Append).

### getMacroPdf417FileName() {#getmacropdf417filename}

Nama file kode batang MacroPdf417 (field opsional). Nama file kode batang MicroPDF417 (field opsional untuk mode Structured Append).

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

ID segmen kode batang MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen kode batang MicroPDF417 (field wajib untuk mode Structured Append).

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Jumlah segmen kode batang MacroPdf417 (field opsional). Jumlah segmen kode batang MicroPDF417 (field opsional untuk mode Structured Append).

### getMacroPdf417Sender() {#getmacropdf417sender}

Nama pengirim kode batang MacroPdf417 (field opsional). Nama pengirim kode batang MicroPDF417 (field opsional untuk mode Structured Append).

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Digunakan untuk memberi tahu encoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Stempel waktu barcode MacroPdf417 (field opsional). Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append)

### getPdf417CompactionMode() {#getpdf417compactionmode}

tipe simbolologi Pdf417 dari mode kompaksi BarCode. Nilai default: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Pengidentifikasi Interpretasi Saluran Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini terdiri dari semua pengkodean charset yang dikenal luas.

### getPdf417EncodeMode() {#getpdf417encodemode}

Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Mendapatkan tipe simbol Pdf417 pada tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada informasi koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Mendapatkan nama penerima barcode macro Pdf417.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Mendapatkan checksum barcode macro Pdf417.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Mendapatkan ID file barcode Pdf417 macro. Digunakan untuk MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Mendapatkan nama file barcode macro Pdf417.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Mendapatkan ukuran file macro Pdf417.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Mendapatkan ID segmen barcode macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Mendapatkan jumlah segmen barcode macro Pdf417.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Mendapatkan nama pengirim barcode macro Pdf417.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Digunakan untuk memberi tahu encoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Mendapatkan stempel waktu barcode macro Pdf417.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang).

### getRows() {#getrows}

Jumlah baris.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Mengidentifikasi ID dari barcode mode structured append DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1.

### getTruncate() {#gettruncate}

Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini.

### isCode128Emulation() {#iscode128emulation}

Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. Contoh ini menunjukkan cara mengkodekan mode emulasi Code 128 dengan FNC1 pada posisi kedua dan tanpa. Dengan cara ini MicroPdf417 dapat didekode sebagai barcode Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC. Contoh ini menunjukkan cara mengkodekan mode “Linked” UCC/EAN-128 dalam GS1MicroPdf417 dan Flag Tautan (918) dalam barcode MicroPdf417 dan Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Rasio Tinggi/Lebar modul BarCode 2D.

### setCode128Emulation() {#setcode128emulation}

Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. Contoh ini menunjukkan cara mengkodekan mode emulasi Code 128 dengan FNC1 pada posisi kedua dan tanpa. Dengan cara ini MicroPdf417 dapat didekode sebagai barcode Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Jumlah kolom.

### setECIEncoding() {#seteciencoding}

Identifier Interpretasi Saluran Terluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan pada bidang teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean charset yang dikenal.

### setEncodeMode() {#setencodemode}

Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

### setErrorLevel(value) {#seterrorlevel}

Mengatur tingkat koreksi kesalahan tipe simbolologi Pdf417 pada BarCode mulai dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Tipe simbolologi Pdf417 pada tingkat koreksi kesalahan BarCode mulai dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |

### setLinked() {#setlinked}

Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC. Contoh ini menunjukkan cara mengkodekan mode “Linked” UCC/EAN-128 dalam GS1MicroPdf417 dan Flag Tautan (918) dalam barcode MicroPdf417 dan Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh pengkodean yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode MicroPdf417 916 serta 917. Nilai default: MacroCharacters.None. Contoh-contoh ini menunjukkan cara mengkodekan Macro Characters dalam MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

Nama penerima kode batang MacroPdf417 (field opsional). Nama penerima kode batang MicroPDF417 (field opsional untuk mode Structured Append).

### setMacroPdf417Checksum() {#setmacropdf417checksum}

Checksum kode batang MacroPdf417 (field opsional). Checksum kode batang MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1.

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417.

### setMacroPdf417FileID() {#setmacropdf417fileid}

ID file kode batang MacroPdf417 (field wajib). ID file kode batang MicroPDF417 (field wajib untuk mode Structured Append).

### setMacroPdf417FileName() {#setmacropdf417filename}

Nama file kode batang MacroPdf417 (field opsional). Nama file kode batang MicroPDF417 (field opsional untuk mode Structured Append).

### setMacroPdf417FileSize() {#setmacropdf417filesize}

Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

ID segmen kode batang MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen kode batang MicroPDF417 (field wajib untuk mode Structured Append).

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

Jumlah segmen kode batang MacroPdf417 (field opsional). Jumlah segmen kode batang MicroPDF417 (field opsional untuk mode Structured Append).

### setMacroPdf417Sender() {#setmacropdf417sender}

Nama pengirim kode batang MacroPdf417 (field opsional). Nama pengirim kode batang MicroPDF417 (field opsional untuk mode Structured Append).

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Digunakan untuk memberi tahu encoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

Stempel waktu barcode MacroPdf417 (field opsional). Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append)

### setPdf417CompactionMode() {#setpdf417compactionmode}

tipe simbolologi Pdf417 dari mode kompaksi BarCode. Nilai default: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Pengidentifikasi Interpretasi Saluran Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini terdiri dari semua pengkodean charset yang dikenal luas.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Mengatur tingkat koreksi kesalahan tipe simbolologi Pdf417 pada BarCode mulai dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Mengatur nama penerima kode batang macro Pdf417.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Mengatur checksum kode batang macro Pdf417.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Mengatur ID file kode batang macro Pdf417. Digunakan untuk MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Mengatur nama file macro Pdf417.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Mengatur ukuran file macro Pdf417.

| Parameter | Deskripsi |
| --- | --- |
| nilai | Field ukuran file berisi ukuran dalam byte dari seluruh file sumber. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Mengatur ID segmen kode batang macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Mengatur jumlah segmen kode batang macro Pdf417.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Mengatur nama pengirim kode batang macro Pdf417.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Digunakan untuk memberi tahu encoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Mengatur cap waktu kode batang macro Pdf417.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang).

### setReaderInitialization(value) {#setreaderinitialization}

Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

| Parameter | Deskripsi |
| --- | --- |
| nilai |  |

### setRows() {#setrows}

Jumlah baris.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Mengidentifikasi ID dari barcode mode structured append DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1.

### setTruncate() {#settruncate}

Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini.

### toString() {#tostring}

Mengembalikan representasi string yang dapat dibaca manusia dari Pdf417Parameters ini.

**Returns:** A string that represents this Pdf417Parameters.
