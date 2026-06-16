---
title: Pdf417Parameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Parameter PDF417.
type: docs
weight: 60
url: /id/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

Parameter PDF417. Berisi parameter PDF417, MacroPDF417, MicroPDF417, dan GS1MicroPdf417. MacroPDF417 memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lainnya bersifat opsional. MicroPDF417 dalam mode Structured Append (sama seperti mode MacroPDF417) memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lainnya bersifat opsional.

Contoh-contoh ini menunjukkan cara mengkodekan mode non Linked UCC/EAN-128 dalam GS1MicroPdf417.

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Jumlah kolom. |
| [getECIEncoding()](#getECIEncoding--) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [getEncodeMode()](#getEncodeMode--) | Mengidentifikasi mode enkode Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | Mendapatkan tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [getMacroCharacters()](#getMacroCharacters--) | Nilai Karakter Makro 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nama penerima barcode MacroPdf417 (bidang opsional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Checksum barcode MacroPdf417 (bidang opsional). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | ID file barcode MacroPdf417 (bidang wajib). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nama file barcode MacroPdf417 (field opsional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Ukuran file MacroPdf417 (field opsional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0, hingga MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Jumlah segmen barcode MacroPdf417 (field opsional). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nama pengirim barcode MacroPdf417 (field opsional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Digunakan untuk memberi tahu encoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Stempel waktu barcode MacroPdf417 (field opsional). |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Tipe simbolologi Pdf417 untuk mode kompaksi BarCode. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Mengidentifikasi mode enkode Pdf417. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | Mendapatkan tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | Nama penerima barcode MacroPdf417 (bidang opsional). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | Checksum barcode MacroPdf417 (bidang opsional). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | ID file barcode MacroPdf417 (bidang wajib). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | Nama file barcode MacroPdf417 (field opsional). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | Ukuran file MacroPdf417 (field opsional). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0, hingga MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | Jumlah segmen barcode MacroPdf417 (field opsional). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | Nama pengirim barcode MacroPdf417 (field opsional). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | Digunakan untuk memberi tahu encoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | Stempel waktu barcode MacroPdf417 (field opsional). |
| [getPdf417Truncate()](#getPdf417Truncate--) | Apakah tipe simbolologi Pdf417 untuk BarCode dipotong (untuk mengurangi ruang). |
| [getRows()](#getRows--) | Jumlah baris. |
| [getTruncate()](#getTruncate--) | Apakah tipe simbolologi Pdf417 untuk BarCode dipotong (untuk mengurangi ruang). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. |
| [isLinked()](#isLinked--) | Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linier terkait selain EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. |
| [setColumns(int value)](#setColumns-int-) | Jumlah kolom. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Mengidentifikasi mode enkode Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Mengatur tipe simbolologi Pdf417 untuk tingkat koreksi kesalahan BarCode mulai dari level0 hingga level8, level0 berarti tidak ada informasi koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [setLinked(boolean value)](#setLinked-boolean-) | Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linier terkait selain EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Nilai Karakter Makro 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Nama penerima barcode MacroPdf417 (bidang opsional). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Checksum barcode MacroPdf417 (bidang opsional). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | ID file barcode MacroPdf417 (bidang wajib). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Nama file barcode MacroPdf417 (field opsional). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Ukuran file MacroPdf417 (field opsional). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0, hingga MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Jumlah segmen barcode MacroPdf417 (field opsional). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Nama pengirim barcode MacroPdf417 (field opsional). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Digunakan untuk memberi tahu encoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Stempel waktu barcode MacroPdf417 (field opsional). |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Tipe simbolologi Pdf417 untuk mode kompaksi BarCode. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Mengidentifikasi mode enkode Pdf417. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Mengatur tipe simbolologi Pdf417 untuk tingkat koreksi kesalahan BarCode mulai dari level0 hingga level8, level0 berarti tidak ada informasi koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | Nama penerima barcode MacroPdf417 (bidang opsional). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | Checksum barcode MacroPdf417 (bidang opsional). |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | ID file barcode MacroPdf417 (bidang wajib). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | Nama file barcode MacroPdf417 (field opsional). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | Ukuran file MacroPdf417 (field opsional). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0, hingga MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | Jumlah segmen barcode MacroPdf417 (field opsional). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | Nama pengirim barcode MacroPdf417 (field opsional). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Digunakan untuk memberi tahu encoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | Stempel waktu barcode MacroPdf417 (field opsional). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Apakah tipe simbolologi Pdf417 untuk BarCode dipotong (untuk mengurangi ruang). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setRows(int value)](#setRows-int-) | Jumlah baris. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Apakah tipe simbolologi Pdf417 untuk BarCode dipotong (untuk mengurangi ruang). |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Rasio Tinggi/ Lebar modul BarCode 2D.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Jumlah kolom.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifier Interpretasi Saluran Ekstended. Digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan pada field teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean charset yang dikenal.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Mendapatkan tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkode yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode 916 dan 917 MicroPdf417. Nilai default: MacroCharacters.None.

Contoh-contoh ini menunjukkan cara mengkodekan Macro Characters dalam MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Nama penerima barcode MacroPdf417 (field opsional). Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Checksum barcode MacroPdf417 (field opsional). Checksum barcode MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Identifier Interpretasi Saluran Ekstended. Berlaku untuk field teks Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append).

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Nama file barcode MacroPdf417 (field opsional). Nama file barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append).

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Jumlah segmen barcode MacroPdf417 (field opsional). Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Nama pengirim barcode MacroPdf417 (field opsional). Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Digunakan untuk memberi tahu encoder apakah akan menambahkan Terminator Macro PDF417 (kode kata 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Stempel waktu barcode MacroPdf417 (field opsional). Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Tipe simbolik Pdf417 untuk mode kompaksi BarCode. Nilai default: Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


Identifier Interpretasi Saluran Ekstended. Digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan pada field teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean charset yang dikenal.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


Mendapatkan tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


Nama penerima barcode MacroPdf417 (field opsional). Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


Checksum barcode MacroPdf417 (field opsional). Checksum barcode MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


Identifier Interpretasi Saluran Ekstended. Berlaku untuk field teks Macro PDF417.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append).

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


Nama file barcode MacroPdf417 (field opsional). Nama file barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append).

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


Jumlah segmen barcode MacroPdf417 (field opsional). Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


Nama pengirim barcode MacroPdf417 (field opsional). Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


Digunakan untuk memberi tahu encoder apakah akan menambahkan Terminator Macro PDF417 (kode kata 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


Stempel waktu barcode MacroPdf417 (field opsional). Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Apakah tipe simbolik Pdf417 untuk BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini.

**Returns:**
boolean
### getRows() {#getRows--}
```
public final int getRows()
```


Jumlah baris.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Apakah tipe simbolik Pdf417 untuk BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128.

Contoh-contoh ini menunjukkan cara mengenkode mode emulasi Code 128 dengan FNC1 pada posisi kedua dan tanpa. Dengan cara ini MicroPdf417 dapat didekode sebagai barcode Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linier terkait selain EAN.UCC.

Contoh-contoh ini menunjukkan cara mengenkode mode \"Linked\" UCC/EAN-128 dalam barcode GS1MicroPdf417 serta Flag Linkage (918) dalam barcode MicroPdf417 dan Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Rasio Tinggi/ Lebar modul BarCode 2D.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128.

Contoh-contoh ini menunjukkan cara mengenkode mode emulasi Code 128 dengan FNC1 pada posisi kedua dan tanpa. Dengan cara ini MicroPdf417 dapat didekode sebagai barcode Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Jumlah kolom.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifier Interpretasi Saluran Ekstended. Digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan pada field teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean charset yang dikenal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Mengatur tipe simbolologi Pdf417 untuk tingkat koreksi kesalahan BarCode mulai dari level0 hingga level8, level0 berarti tidak ada informasi koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Tipe simbolik Pdf417 untuk level koreksi error BarCode berkisar dari level0 hingga level8, level0 berarti tidak ada informasi koreksi error, level8 berarti koreksi error terbaik yang menghasilkan gambar lebih besar. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linier terkait selain EAN.UCC.

Contoh-contoh ini menunjukkan cara mengenkode mode \"Linked\" UCC/EAN-128 dalam barcode GS1MicroPdf417 serta Flag Linkage (918) dalam barcode MicroPdf417 dan Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkode yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode 916 dan 917 MicroPdf417. Nilai default: MacroCharacters.None.

Contoh-contoh ini menunjukkan cara mengkodekan Macro Characters dalam MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Nama penerima barcode MacroPdf417 (field opsional). Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Checksum barcode MacroPdf417 (field opsional). Checksum barcode MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Identifier Interpretasi Saluran Ekstended. Berlaku untuk field teks Macro PDF417.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Nama file barcode MacroPdf417 (field opsional). Nama file barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Jumlah segmen barcode MacroPdf417 (field opsional). Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Nama pengirim barcode MacroPdf417 (field opsional). Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Digunakan untuk memberi tahu encoder apakah akan menambahkan Terminator Macro PDF417 (kode kata 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Stempel waktu barcode MacroPdf417 (field opsional). Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Tipe simbolik Pdf417 untuk mode kompaksi BarCode. Nilai default: Pdf417CompactionMode.Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


Identifier Interpretasi Saluran Ekstended. Digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan pada field teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean charset yang dikenal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Mengatur tipe simbolologi Pdf417 untuk tingkat koreksi kesalahan BarCode mulai dari level0 hingga level8, level0 berarti tidak ada informasi koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Tipe simbolik Pdf417 untuk level koreksi error BarCode berkisar dari level0 hingga level8, level0 berarti tidak ada informasi koreksi error, level8 berarti koreksi error terbaik yang menghasilkan gambar lebih besar. |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


Nama penerima barcode MacroPdf417 (field opsional). Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


Checksum barcode MacroPdf417 (field opsional). Checksum barcode MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


Identifier Interpretasi Saluran Ekstended. Berlaku untuk field teks Macro PDF417.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


Nama file barcode MacroPdf417 (field opsional). Nama file barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


Jumlah segmen barcode MacroPdf417 (field opsional). Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


Nama pengirim barcode MacroPdf417 (field opsional). Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


Digunakan untuk memberi tahu encoder apakah akan menambahkan Terminator Macro PDF417 (kode kata 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


Stempel waktu barcode MacroPdf417 (field opsional). Stempel waktu barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Apakah tipe simbolik Pdf417 untuk BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Jumlah baris.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Apakah tipe simbolik Pdf417 untuk BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) ini.

**Returns:**
java.lang.String - Sebuah string yang merepresentasikan [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) ini.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

