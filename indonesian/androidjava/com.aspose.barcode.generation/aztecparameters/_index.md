---
title: AztecParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Parameter Aztec.
type: docs
weight: 12
url: /id/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Parameter Aztec.
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Mendapatkan mode encode Aztec. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Tingkat koreksi kesalahan pada tipe barcode Aztec. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Mendapatkan mode Simbol Aztec. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Mendapatkan enkoding ECI. |
| [getEncodeMode()](#getEncodeMode--) | Mendapatkan mode encode Aztec. |
| [getErrorLevel()](#getErrorLevel--) | Tingkat koreksi kesalahan pada tipe barcode Aztec. |
| [getLayersCount()](#getLayersCount--) | Mendapatkan jumlah lapisan simbol Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | ID barcode untuk mode Structured Append pada barcode Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Jumlah barcode untuk mode Structured Append pada barcode Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | ID file untuk mode Structured Append pada barcode Aztec (field opsional). |
| [getSymbolMode()](#getSymbolMode--) | Mendapatkan mode Simbol Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Mengatur mode enkode Aztec. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Tingkat koreksi kesalahan pada tipe barcode Aztec. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Mengatur mode Simbol Aztec. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Mengatur enkoding ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Mengatur mode enkode Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Tingkat koreksi kesalahan pada tipe barcode Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | Mengatur jumlah lapisan simbol Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | ID barcode untuk mode Structured Append pada barcode Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Jumlah barcode untuk mode Structured Append pada barcode Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | ID file untuk mode Structured Append pada barcode Aztec (field opsional). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Mengatur mode Simbol Aztec. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


Mendapatkan mode enkode Aztec. Nilai default: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - sebuah mode enkode Aztec.
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


Mendapatkan mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Mendapatkan enkoding ECI. Digunakan ketika AztecEncodeMode adalah Auto. Nilai default: ISO-8859-1

**Returns:**
int - enkoding ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Mendapatkan mode enkode Aztec. Nilai default: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - sebuah mode enkode Aztec.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Mendapatkan jumlah lapisan simbol Aztec. Jumlah lapisan harus berada dalam rentang 1 hingga 3 untuk mode Compact dan dalam rentang 1 hingga 32 untuk mode Full Range. Nilai default: 0 (otomatis).

**Returns:**
int - jumlah lapisan simbol Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


ID barcode untuk mode Structured Append pada barcode Aztec. ID barcode harus berada dalam rentang 1 hingga jumlah barcode. Nilai default: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Jumlah barcode untuk mode Structured Append pada barcode Aztec. Jumlah barcode harus berada dalam rentang 1 hingga 26. Nilai default: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


ID file untuk mode Structured Append pada barcode Aztec (field opsional). ID file tidak boleh mengandung spasi. Nilai default: string kosong

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Mendapatkan mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


Mengatur mode enkode Aztec. Nilai default: Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.barcode.generation.AztecEncodeMode | sebuah mode enkode Aztec. |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


Mengatur mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | sebuah mode Simbol Aztec. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Mengatur enkoding ECI. Digunakan ketika AztecEncodeMode adalah Auto. Nilai default: ISO-8859-1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | Enkoding ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Mengatur mode enkode Aztec. Nilai default: Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.barcode.generation.AztecEncodeMode | sebuah mode enkode Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Tingkat koreksi kesalahan untuk tipe barcode Aztec. Nilai harus antara 5 hingga 95.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Mengatur jumlah lapisan simbol Aztec. Jumlah lapisan harus berada dalam rentang 1 hingga 3 untuk mode Compact dan dalam rentang 1 hingga 32 untuk mode Full Range. Nilai default: 0 (otomatis).

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | jumlah lapisan simbol Aztec. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Digunakan untuk menginstruksikan pembaca agar menafsirkan data yang terdapat dalam simbol sebagai pemrograman untuk inisialisasi pembaca.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


ID barcode untuk mode Structured Append pada barcode Aztec. ID barcode harus berada dalam rentang 1 hingga jumlah barcode. Nilai default: 0

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Jumlah barcode untuk mode Structured Append pada barcode Aztec. Jumlah barcode harus berada dalam rentang 1 hingga 26. Nilai default: 0

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


ID file untuk mode Structured Append pada barcode Aztec (field opsional). ID file tidak boleh mengandung spasi. Nilai default: string kosong

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Mengatur mode Simbol Aztec. Nilai default: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | sebuah mode Simbol Aztec. |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - Sebuah string yang mewakili [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

