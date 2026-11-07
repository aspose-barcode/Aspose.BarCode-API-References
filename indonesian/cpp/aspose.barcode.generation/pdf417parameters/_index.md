---
title: "kelas Aspose::BarCode::Generation::Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "kelas Aspose::BarCode::Generation::Pdf417Parameters. Parameter PDF417. Berisi parameter PDF417, MacroPDF417, MicroPDF417, dan GS1MicroPdf417. MacroPDF417 memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lainnya bersifat opsional. MicroPDF417 dalam mode Structured Append (sama dengan mode MacroPDF417) memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lainnya bersifat opsional dalam C++."
type: docs
weight: 4000
url: /id/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


Parameter PDF417. Berisi parameter PDF417, MacroPDF417, MicroPDF417, dan GS1MicroPdf417. MacroPDF417 memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lain bersifat opsional. MicroPDF417 dalam mode Structured Append (sama dengan mode MacroPDF417) memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lain bersifat opsional.

```cpp
class Pdf417Parameters : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [get_Columns](./get_columns/)() const | Jumlah kolom. |
| [get_ECIEncoding](./get_eciencoding/)() const | Pengidentifikasi Interpretasi Saluran Terluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan untuk bidang teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean set karakter yang dikenal. |
| [get_EncodeMode](./get_encodemode/)() const | Mengidentifikasi mode enkode Pdf417. Nilai default: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Mendapatkan tipe simbolologi Pdf417 dari tingkat koreksi kesalahan [BarCode](../../aspose.barcode/) yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. |
| [get_IsLinked](./get_islinked/)() const | Mendefinisikan mode terhubung dengan kode batang GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode 916 dan 917 MicroPdf417. Nilai default: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Nama penerima barcode MacroPdf417 (field opsional). Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Checksum barcode MacroPdf417 (field opsional). Checksum barcode MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Pengidentifikasi Interpretasi Saluran Terluas. Diterapkan untuk bidang teks Macro PDF417. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Nama file barcode MacroPdf417 (field opsional). Nama file barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Jumlah segmen barcode MacroPdf417 (field opsional). Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Nama pengirim barcode MacroPdf417 (field opsional). Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Digunakan untuk memberi tahu encoder apakah harus menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. Hanya diterapkan untuk Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Stempel waktu barcode MacroPdf417 (field opsional). Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [get_Rows](./get_rows/)() const | Jumlah baris. |
| [get_Truncate](./get_truncate/)() const | Apakah tipe simbolologi Pdf417 dari [BarCode](../../aspose.barcode/) dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini. |
| [set_AspectRatio](./set_aspectratio/)(float) | Rasio tinggi/lebar modul [BarCode](../../aspose.barcode/) 2D. |
| [set_Columns](./set_columns/)(int32_t) | Jumlah kolom. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Pengidentifikasi Interpretasi Saluran Terluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan untuk bidang teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean set karakter yang dikenal. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Mengidentifikasi mode enkode Pdf417. Nilai default: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Mengatur tipe simbolografi Pdf417 dari tingkat koreksi kesalahan [BarCode](../../aspose.barcode/)'s mulai dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang berarti gambar lebih besar. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. |
| [set_IsLinked](./set_islinked/)(bool) | Mendefinisikan mode terhubung dengan kode batang GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode 916 dan 917 MicroPdf417. Nilai default: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | Nama penerima barcode MacroPdf417 (field opsional). Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | Checksum barcode MacroPdf417 (field opsional). Checksum barcode MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Pengidentifikasi Interpretasi Saluran Terluas. Diterapkan untuk bidang teks Macro PDF417. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | Nama file barcode MacroPdf417 (field opsional). Nama file barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | Jumlah segmen barcode MacroPdf417 (field opsional). Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | Nama pengirim barcode MacroPdf417 (field opsional). Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Digunakan untuk memberi tahu encoder apakah harus menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. Hanya diterapkan untuk Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | Stempel waktu barcode MacroPdf417 (field opsional). Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append). |
| [set_Rows](./set_rows/)(int32_t) | Jumlah baris. |
| [set_Truncate](./set_truncate/)(bool) | Apakah tipe simbolologi Pdf417 dari [BarCode](../../aspose.barcode/) dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini. |
| [ToString](./tostring/)() const override | Mengembalikan representasi string yang dapat dibaca manusia dari [Pdf417Parameters](./). |
## Catatan


Contoh-contoh ini menunjukkan cara mengode mode non Linked UCC/EAN-128 dalam GS1MicroPdf417
```cpp
[C#]
//Menyandikan mode non Linked GS1 UCC/EAN-128 905 dengan AI 01 (GTIN)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Menyandikan mode non Linked GS1 UCC/EAN-128 903, 904 dengan AI apa pun
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
