---
title: Pdf417ExtendedParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Menyimpan informasi metadata MacroPdf417 dari kode batang yang dikenali
type: docs
weight: 40
url: /id/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Menyimpan informasi metadata MacroPdf417 dari kode batang yang dikenali

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai Pdf417ExtendedParameters yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Nama penerima Macro PDF417 (opsional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Checksum Macro PDF417 (opsional). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Mendapatkan ID file barcode, hanya tersedia dengan MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Nama file Macro PDF417 (opsional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Ukuran file Macro PDF417 (opsional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Mendapatkan ID segmen barcode, hanya tersedia dengan MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Mendapatkan jumlah segmen barcode macro pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Nama pengirim Macro PDF417 (opsional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Menunjukkan apakah segmen tersebut adalah segmen terakhir dari file Macro PDF417. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Stempel waktu Macro PDF417 (opsional). |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isCode128Emulation()](#isCode128Emulation--) | Bendera yang menunjukkan bahwa barcode MicroPdf417 dienkode dengan kata kode emulasi Code 128 908, 909, 910, atau 911. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua parameter hanya memiliki nilai default |
| [isLinked()](#isLinked--) | Bendera yang menunjukkan bahwa barcode harus dihubungkan ke barcode 1D. |
| [isReaderInitialization()](#isReaderInitialization--) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari Pdf417ExtendedParameters ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai Pdf417ExtendedParameters yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Nama penerima Macro PDF417 (opsional).

**Returns:**
java.lang.String - Nama penerima.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Checksum Macro PDF417 (opsional).

**Returns:**
int - Checksum.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Mendapatkan ID file barcode, hanya tersedia dengan MacroPdf417.

Nilai: ID file untuk MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Nama file Macro PDF417 (opsional).

**Returns:**
java.lang.String - Nama file.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Ukuran file Macro PDF417 (opsional).

**Returns:**
int - Ukuran file.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Mendapatkan ID segmen barcode, hanya tersedia dengan MacroPdf417.

Nilai: ID segmen barcode.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Mendapatkan jumlah segmen barcode macro pdf417. Nilai default adalah -1.

Nilai: Jumlah segmen.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Nama pengirim Macro PDF417 (opsional).

**Returns:**
java.lang.String - Nama pengirim
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Menunjukkan apakah segmen tersebut adalah segmen terakhir dari file Macro PDF417.

**Returns:**
boolean - Terminator.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Stempel waktu Macro PDF417 (opsional).

**Returns:**
java.time.LocalDateTime - Tanda waktu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Bendera yang menunjukkan bahwa barcode MicroPdf417 dienkode dengan kata kode emulasi Code 128 908, 909, 910, atau 911.

**Returns:**
boolean - Bendera emulasi Code 128
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Menguji apakah semua parameter hanya memiliki nilai default

Nilai: Mengembalikan  **true**  jika semua parameter hanya memiliki nilai default; jika tidak,  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Bendera yang menunjukkan bahwa barcode harus dihubungkan ke barcode 1D.

Nilai: Bendera tautan

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

Nilai: Bendera inisialisasi pembaca

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




### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari Pdf417ExtendedParameters ini.

**Returns:**
java.lang.String - Sebuah string yang mewakili Pdf417ExtendedParameters ini.
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

