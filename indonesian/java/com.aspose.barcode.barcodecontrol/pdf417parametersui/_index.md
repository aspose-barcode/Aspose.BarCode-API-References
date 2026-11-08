---
title: "Pdf417ParametersUI"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Pembungkus UI untuk kelas com.aspose.barcode.generation.Pdf417Parameters."
type: docs
weight: 16
url: /id/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

Pembungkus UI untuk kelas com.aspose.barcode.generation.Pdf417Parameters.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Jumlah kolom. |
| [getECIEncoding()](#getECIEncoding--) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [getEncodeMode()](#getEncodeMode--) | Jenis simbolologi Pdf417 dari mode enkode BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Mendapatkan jenis simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [getMacroCharacters()](#getMacroCharacters--) | Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nama penerima barcode MacroPdf417 (field opsional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Checksum barcode MacroPdf417 (field opsional). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Mendapatkan ID file barcode macro Pdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nama file barcode MacroPdf417 (field opsional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Ukuran file MacroPdf417 (field opsional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Mendapatkan ID segmen barcode macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Mendapatkan jumlah segmen barcode macro Pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nama pengirim barcode MacroPdf417 (field opsional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Digunakan untuk memberi tahu enkoder apakah menambahkan Macro PDF417 Terminator (codeword 922) ke segmen. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Stempel waktu barcode MacroPdf417 (field opsional). |
| [getRows()](#getRows--) | Jumlah baris. |
| [getTruncate()](#getTruncate--) | Apakah jenis simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. |
| [isLinked()](#isLinked--) | Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417 dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan 906, 907, 912, 913, 914, 915 \u201cLinked\u201d mode UCC/EAN-128. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linier terkait selain EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128. |
| [setColumns(int value)](#setColumns-int-) | Jumlah kolom. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Jenis simbolologi Pdf417 dari mode enkode BarCode. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Mengatur jenis simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |
| [setLinked(boolean value)](#setLinked-boolean-) | Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417 dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan 906, 907, 912, 913, 914, 915 \u201cLinked\u201d mode UCC/EAN-128. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linier terkait selain EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Nama penerima barcode MacroPdf417 (field opsional). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Checksum barcode MacroPdf417 (field opsional). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Mengatur ID file barcode macro Pdf417. |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Nama file barcode MacroPdf417 (field opsional). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Ukuran file MacroPdf417 (field opsional). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Mengatur ID segmen barcode macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Mengatur jumlah segmen kode batang macro Pdf417. |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Nama pengirim barcode MacroPdf417 (field opsional). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Digunakan untuk memberi tahu enkoder apakah menambahkan Macro PDF417 Terminator (codeword 922) ke segmen. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Stempel waktu barcode MacroPdf417 (field opsional). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setRows(int value)](#setRows-int-) | Jumlah baris. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Apakah jenis simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang). |
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


Pengidentifikasi Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan untuk bidang teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean charset yang dikenal.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Tipe simbolologi Pdf417 dari mode enkode BarCode. Nilai default: Pdf417EncodeMode.Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Mendapatkan jenis simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode MicroPdf417 916 dan 917. Nilai default: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Nama penerima kode batang MacroPdf417 (field opsional). Nama penerima kode batang MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Checksum kode batang MacroPdf417 (field opsional). Checksum kode batang MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Mendapatkan ID file kode batang macro Pdf417. Digunakan untuk MacroPdf417.

**Returns:**
int - ID file kode batang macro Pdf417.
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Nama file kode batang MacroPdf417 (field opsional). Nama file kode batang MicroPDF417 (field opsional untuk mode Structured Append).

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


Mendapatkan ID segmen barcode macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1.

**Returns:**
int - ID segmen kode batang macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1.
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Mendapatkan jumlah segmen barcode macro Pdf417.

**Returns:**
int - jumlah segmen kode batang macro Pdf417.
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Nama pengirim kode batang MacroPdf417 (field opsional). Nama pengirim kode batang MicroPDF417 (field opsional untuk mode Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Digunakan untuk memberi tahu enkoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Timestamp kode batang MacroPdf417 (field opsional). Timestamp kode batang MicroPDF417 (field opsional untuk mode Structured Append).

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


Apakah jenis simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang).

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

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417 dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan 906, 907, 912, 913, 914, 915 \u201cLinked\u201d mode UCC/EAN-128. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linier terkait selain EAN.UCC.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode emulasi Code 128. Dapat mengkodekan FNC1 pada posisi kedua pada mode 908 dan 909, juga dapat mengkodekan 910 dan 911 yang hanya menunjukkan bahwa MicroPdf417 yang dikenali dapat diinterpretasikan sebagai Code 128.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Jumlah kolom.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Pengidentifikasi Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol. Tidak diterapkan untuk bidang teks Macro PDF417. Implementasi saat ini mencakup semua pengkodean charset yang dikenal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Tipe simbolologi Pdf417 dari mode enkode BarCode. Nilai default: Pdf417EncodeMode.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Mengatur jenis simbolologi Pdf417 dari tingkat koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Tipe simbolologi Pdf417 dari level koreksi kesalahan BarCode yang berkisar dari level0 hingga level8, level0 berarti tidak ada info koreksi kesalahan, level8 berarti koreksi kesalahan terbaik yang menghasilkan gambar lebih besar. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417 dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan 906, 907, 912, 913, 914, 915 \u201cLinked\u201d mode UCC/EAN-128. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linier terkait selain EAN.UCC.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Nilai Macro Characters 05 dan 06 digunakan untuk memperoleh enkoding yang lebih kompak dalam mode khusus. Hanya dapat digunakan dengan MicroPdf417 dan mengkodekan mode MicroPdf417 916 dan 917. Nilai default: MacroCharacters.None.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Nama penerima kode batang MacroPdf417 (field opsional). Nama penerima kode batang MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Checksum kode batang MacroPdf417 (field opsional). Checksum kode batang MicroPDF417 (field opsional untuk mode Structured Append). Field checksum berisi nilai checksum CRC 16-bit (2 byte) menggunakan polinomial CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Pengidentifikasi Interpretasi Saluran yang Diperluas. Berlaku untuk bidang teks Macro PDF417.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Mengatur ID file kode batang macro Pdf417. Digunakan untuk MacroPdf417.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | ID file kode batang macro Pdf417. |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Nama file kode batang MacroPdf417 (field opsional). Nama file kode batang MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Ukuran file MacroPdf417 (field opsional). Ukuran file MicroPDF417 (field opsional untuk mode Structured Append). Field ukuran file berisi ukuran dalam byte dari seluruh file sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Mengatur ID segmen barcode macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | ID segmen kode batang macro Pdf417, yang dimulai dari 0, hingga MacroSegmentsCount - 1. |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Mengatur jumlah segmen kode batang macro Pdf417.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | jumlah segmen kode batang macro Pdf417. |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Nama pengirim kode batang MacroPdf417 (field opsional). Nama pengirim kode batang MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Digunakan untuk memberi tahu enkoder apakah menambahkan Terminator Macro PDF417 (codeword 922) ke segmen. Hanya diterapkan untuk Macro PDF417.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Timestamp kode batang MacroPdf417 (field opsional). Timestamp kode batang MicroPDF417 (field opsional untuk mode Structured Append).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Jumlah baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Apakah jenis simbolologi Pdf417 dari BarCode dipotong (untuk mengurangi ruang).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - String yang mewakili [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) ini.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

