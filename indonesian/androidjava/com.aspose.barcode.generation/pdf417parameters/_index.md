---
title: "Pdf417Parameters"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: "Parameter PDF417."
type: docs
weight: 58
url: /id/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

Parameter PDF417. Berisi parameter PDF417, MacroPDF417, MicroPDF417, dan GS1MicroPdf417. MacroPDF417 memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lainnya bersifat opsional. MicroPDF417 dalam mode Structured Append (sama dengan mode MacroPDF417) memerlukan dua bidang: Pdf417MacroFileID dan Pdf417MacroSegmentID. Semua bidang lainnya bersifat opsional.

Contoh-contoh ini menunjukkan cara mengkodekan mode non Linked UCC/EAN-128 dalam GS1MicroPdf417

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/Lebar modul 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Jumlah kolom. |
| [getECIEncoding()](#getECIEncoding--) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [getEncodeMode()](#getEncodeMode--) | Mengidentifikasi mode enkode Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | Mendapatkan tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [getMacroCharacters()](#getMacroCharacters--) | Nilai Karakter Makro 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nama penerima barcode MacroPdf417 (bidang opsional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Checksum barcode MacroPdf417 (bidang opsional). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | ID file barcode MacroPdf417 (bidang wajib). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nama file barcode MacroPdf417 (bidang opsional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Ukuran file MacroPdf417 (bidang opsional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | ID segmen barcode MacroPdf417 (bidang wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Jumlah segmen barcode MacroPdf417 (bidang opsional). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nama pengirim barcode MacroPdf417 (bidang opsional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Digunakan untuk memberi tahu pengkode apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Stempel waktu barcode MacroPdf417 (bidang opsional). |
| [getRows()](#getRows--) | Jumlah baris. |
| [getTruncate()](#getTruncate--) | Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. |
| [isLinked()](#isLinked--) | Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode UCC/EAN-128 \u201cLinked\u201d 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC |
| [isReaderInitialization()](#isReaderInitialization--) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/Lebar modul 2D BarCode. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. |
| [setColumns(int value)](#setColumns-int-) | Jumlah kolom. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Mengidentifikasi mode enkode Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Mengatur tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [setLinked(boolean value)](#setLinked-boolean-) | Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode UCC/EAN-128 \u201cLinked\u201d 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Nilai Karakter Makro 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Nama penerima barcode MacroPdf417 (bidang opsional). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Checksum barcode MacroPdf417 (bidang opsional). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | ID file barcode MacroPdf417 (bidang wajib). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Nama file barcode MacroPdf417 (bidang opsional). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Ukuran file MacroPdf417 (bidang opsional). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | ID segmen barcode MacroPdf417 (bidang wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Jumlah segmen barcode MacroPdf417 (bidang opsional). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Nama pengirim barcode MacroPdf417 (bidang opsional). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Digunakan untuk memberi tahu pengkode apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Stempel waktu barcode MacroPdf417 (bidang opsional). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setRows(int value)](#setRows-int-) | Jumlah baris. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Rasio Tinggi/Lebar modul 2D BarCode.

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


Identifier Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan untuk bidang teks Macro PDF417. Implementasi saat ini terdiri dari semua pengkodean set karakter yang dikenal.

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


Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengenkode mode MicroPdf417 916 dan 917. Nilai default: MacroCharacters.None.

Contoh-contoh ini menunjukkan cara mengenkode Macro Characters dalam MicroPdf417

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Nama penerima barcode MacroPdf417 (field opsional). Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append)

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


Identifier Interpretasi Saluran Ekstended. Berlaku untuk bidang teks Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append)

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Nama file barcode MacroPdf417 (field opsional). Nama file barcode MicroPDF417 (field opsional untuk mode Structured Append)

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


ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append)

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Jumlah segmen barcode MacroPdf417 (field opsional). Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Nama pengirim barcode MacroPdf417 (field opsional). Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Digunakan untuk memberi tahu encoder apakah harus menambahkan Terminator Macro PDF417 (kode kata 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Timestamp barcode MacroPdf417 (field opsional). Timestamp barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Returns:**
java.time.LocalDateTime
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


Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128.

Contoh-contoh ini menunjukkan cara mengenkode mode emulasi Code 128 dengan FNC1 pada posisi kedua dan tanpa. Dengan cara ini MicroPdf417 dapat didekode sebagai barcode Code 128

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode UCC/EAN-128 \u201cLinked\u201d 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC

Contoh-contoh ini menunjukkan cara mengenkode mode "Linked" UCC/EAN-128 dalam GS1MicroPdf417 dan Linkage Flag (918) dalam barcode MicroPdf417 dan Pdf417

```

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


Rasio Tinggi/Lebar modul 2D BarCode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128.

Contoh-contoh ini menunjukkan cara mengenkode mode emulasi Code 128 dengan FNC1 pada posisi kedua dan tanpa. Dengan cara ini MicroPdf417 dapat didekode sebagai barcode Code 128

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Jumlah kolom.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifier Interpretasi Saluran Ekstended. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan untuk bidang teks Macro PDF417. Implementasi saat ini terdiri dari semua pengkodean set karakter yang dikenal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Mengidentifikasi mode enkode Pdf417. Nilai default: Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Mengatur tipe simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Tipe simbolologi Pdf417 dari level koreksi kesalahan BarCode berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode UCC/EAN-128 \u201cLinked\u201d 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC

Contoh-contoh ini menunjukkan cara mengenkode mode "Linked" UCC/EAN-128 dalam GS1MicroPdf417 dan Linkage Flag (918) dalam barcode MicroPdf417 dan Pdf417

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengenkode mode MicroPdf417 916 dan 917. Nilai default: MacroCharacters.None.

Contoh-contoh ini menunjukkan cara mengenkode Macro Characters dalam MicroPdf417

```

```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Nama penerima barcode MacroPdf417 (field opsional). Nama penerima barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Checksum barcode MacroPdf417 (field opsional). Checksum barcode MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Identifier Interpretasi Saluran Ekstended. Berlaku untuk bidang teks Macro PDF417.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


ID file barcode MacroPdf417 (field wajib). ID file barcode MicroPDF417 (field wajib untuk mode Structured Append)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Nama file barcode MacroPdf417 (field opsional). Nama file barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


ID segmen barcode MacroPdf417 (field wajib), yang dimulai dari 0 hingga MacroSegmentsCount - 1. ID segmen barcode MicroPDF417 (field wajib untuk mode Structured Append)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Jumlah segmen barcode MacroPdf417 (field opsional). Jumlah segmen barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Nama pengirim barcode MacroPdf417 (field opsional). Nama pengirim barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Digunakan untuk memberi tahu encoder apakah harus menambahkan Terminator Macro PDF417 (kode kata 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Timestamp barcode MacroPdf417 (field opsional). Timestamp barcode MicroPDF417 (field opsional untuk mode Structured Append)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Jumlah baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Apakah tipe simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). Juga dikenal sebagai CompactPDF417. Indikator baris kanan dan pola berhenti kanan dihapus dalam mode ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - Sebuah string yang mewakili [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) ini.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

