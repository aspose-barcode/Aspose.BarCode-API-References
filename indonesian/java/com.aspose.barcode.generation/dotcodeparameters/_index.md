---
title: "DotCodeParameters"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Parameter DotCode."
type: docs
weight: 34
url: /id/java/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

Parameter DotCode.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Mengidentifikasi jumlah kolom. |
| [getECIEncoding()](#getECIEncoding--) | Mengidentifikasi pengkodean ECI. |
| [getEncodeMode()](#getEncodeMode--) | Mengidentifikasi mode pengkodean DotCode. |
| [getRows()](#getRows--) | Mengidentifikasi jumlah baris. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Mengidentifikasi ID barcode mode penambahan terstruktur DotCode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Mengidentifikasi jumlah barcode mode penambahan terstruktur DotCode. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [setColumns(int value)](#setColumns-int-) | Mengidentifikasi jumlah kolom. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Mengidentifikasi pengkodean ECI. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Mengidentifikasi mode pengkodean DotCode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. |
| [setRows(int value)](#setRows-int-) | Mengidentifikasi jumlah baris. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Mengidentifikasi ID barcode mode penambahan terstruktur DotCode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Mengidentifikasi jumlah barcode mode penambahan terstruktur DotCode. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) ini. |
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


Mengidentifikasi jumlah kolom. Jumlah baris ditambah jumlah kolom dari simbol DotCode harus ganjil. Jumlah kolom harus minimal 5. Nilai default: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Mengidentifikasi pengkodean ECI. Digunakan ketika DotCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Mengidentifikasi mode pengkodean DotCode. Nilai default: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Mengidentifikasi jumlah baris. Jumlah baris ditambah jumlah kolom dari simbol DotCode harus ganjil. Jumlah baris harus minimal 5. Nilai default: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Mengidentifikasi ID barcode mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Mengidentifikasi jumlah barcode mode penambahan terstruktur DotCode. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35.

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false.

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Mengidentifikasi jumlah kolom. Jumlah baris ditambah jumlah kolom dari simbol DotCode harus ganjil. Jumlah kolom harus minimal 5. Nilai default: -1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Mengidentifikasi pengkodean ECI. Digunakan ketika DotCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Mengidentifikasi mode pengkodean DotCode. Nilai default: Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Menunjukkan apakah kode digunakan untuk menginstruksikan pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca kode batang. Nilai default adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Mengidentifikasi jumlah baris. Jumlah baris ditambah jumlah kolom dari simbol DotCode harus ganjil. Jumlah baris harus minimal 5. Nilai default: -1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Mengidentifikasi ID barcode mode penambahan terstruktur DotCode. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah -1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Mengidentifikasi jumlah barcode mode penambahan terstruktur DotCode. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) ini.

**Returns:**
java.lang.String - Sebuah string yang merepresentasikan [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) ini.
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

