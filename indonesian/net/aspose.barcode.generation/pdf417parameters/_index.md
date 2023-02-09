---
title: Pdf417Parameters
second_title: Aspose.BarCode untuk .NET API Referensi
description: parameter PDF417. Berisi parameter PDF417 MacroPDF417 dan MicroPDF417. MacroPDF417 membutuhkan dua bidang Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua kolom lainnya bersifat opsional. MicroPDF417 dalam mode Structured Append sama seperti mode MacroPDF417 membutuhkan dua kolom Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua kolom lainnya bersifat opsional.
type: docs
weight: 1130
url: /id/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

parameter PDF417. Berisi parameter PDF417, MacroPDF417 dan MicroPDF417. MacroPDF417 membutuhkan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua kolom lainnya bersifat opsional. MicroPDF417 dalam mode Structured Append (sama seperti mode MacroPDF417) membutuhkan dua kolom: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua kolom lainnya bersifat opsional.

```csharp
public class Pdf417Parameters
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | Rasio Tinggi/Lebar modul 2D BarCode. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation/) { get; set; } | Kata kode fungsi untuk emulasi Kode 128. Diterapkan hanya untuk MicroPDF417. Diabaikan untuk barcode PDF417 dan MacroPDF417. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding/) { get; set; } | Mendapat atau menyetel penyandian teks kode. Nilai default: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Jumlah kolom. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Digunakan untuk menginstruksikan pembaca untuk menginterpretasikan data yang terkandung dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode/) { get; set; } | Jenis simbologi Pdf417 dari mode pemadatan BarCode. Nilai default: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding/) { get; set; } | Pengidentifikasi Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu detail pembaca barcode tentang referensi yang digunakan untuk menyandikan data dalam simbol. Tidak diterapkan untuk bidang teks Macro PDF417. Implementasi saat ini terdiri dari semua pengkodean charset yang terkenal. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel/) { get; set; } | Mendapat atau menetapkan jenis simbologi Pdf417 dari level koreksi kesalahan BarCode mulai dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang berarti gambar lebih besar. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee/) { get; set; } | Nama penerima kode batang MacroPdf417 (bidang opsional). Nama alamat kode batang MicroPDF417 (bidang opsional untuk mode Penambahan Terstruktur) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum/) { get; set; } | Checksum barcode MacroPdf417 (bidang opsional). Checksum barcode MicroPDF417 (bidang opsional untuk mode Penambahan Terstruktur) Bidang checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding/) { get; set; } | Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid/) { get; set; } | ID file barcode MacroPdf417 (Kolom wajib diisi). ID file barcode MicroPDF417 (Kolom wajib diisi untuk mode Penambahan Terstruktur) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename/) { get; set; } | Nama file barcode MacroPdf417 (bidang opsional). Nama file barcode MicroPDF417 (bidang opsional untuk mode Penambahan Terstruktur) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize/) { get; set; } | Ukuran file MacroPdf417 (bidang opsional). Ukuran file MicroPDF417 (bidang opsional untuk mode Penambahan Terstruktur) Bidang ukuran file berisi ukuran dalam byte dari seluruh file sumber. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid/) { get; set; } | ID segmen barcode MacroPdf417 (Kolom wajib diisi), yang dimulai dari 0, hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (Kolom wajib diisi untuk mode Penambahan Terstruktur) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount/) { get; set; } | Jumlah segmen barcode MacroPdf417 (bidang opsional). Jumlah segmen barcode MicroPDF417 (bidang opsional untuk mode Penambahan Terstruktur) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender/) { get; set; } | Nama pengirim barcode MacroPdf417 (bidang opsional). Nama pengirim barcode MicroPDF417 (bidang opsional untuk mode Penambahan Terstruktur) |
| [Pdf417MacroTerminator](../../aspose.barcode.generation/pdf417parameters/pdf417macroterminator/) { get; set; } | Digunakan untuk memberi tahu encoder apakah akan menambahkan Macro PDF417 Terminator (codeword 922) ke segmen. Hanya berlaku untuk Makro PDF417. |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp/) { get; set; } | stempel waktu kode batang MacroPdf417 (bidang opsional). Stempel waktu kode batang MicroPDF417 (bidang opsional untuk mode Penambahan Terstruktur) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate/) { get; set; } | Apakah BarCode jenis simbologi Pdf417 dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola stop kanan dihilangkan dalam mode ini. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Jumlah baris. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Mengembalikan representasi string yang dapat dibaca manusia dari ini`Pdf417Parameters` . |

### Lihat juga

* ruang nama [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
