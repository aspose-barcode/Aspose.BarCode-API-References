---
title: MaxiCodeParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Parameter MaxiCode.
type: docs
weight: 57
url: /id/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

Parameter MaxiCode.
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Mendapatkan enkoding ECI. |
| [getEncodeMode()](#getEncodeMode--) | Mendapatkan mode enkode MaxiCode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Mendapatkan mode enkode MaxiCode. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | Mendapatkan mode enkode MaxiCode. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | Mendapatkan ID barcode MaxiCode dalam mode penambahan terstruktur. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | Mendapatkan jumlah barcode MaxiCode dalam mode penambahan terstruktur. |
| [getMode()](#getMode--) | Mendapatkan mode enkode MaxiCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Mendapatkan ID barcode MaxiCode dalam mode penambahan terstruktur. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Mendapatkan jumlah barcode MaxiCode dalam mode penambahan terstruktur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Mengatur enkoding ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Mengatur mode enkode MaxiCode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Mengatur mode enkode MaxiCode. |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | Mengatur mode enkode MaxiCode. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | Mengatur ID kode batang MaxiCode dalam mode penambahan terstruktur. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | Mengatur jumlah kode batang MaxiCode dalam mode penambahan terstruktur. |
| [setMode(int value)](#setMode-int-) | Mengatur mode enkode MaxiCode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Mengatur ID kode batang MaxiCode dalam mode penambahan terstruktur. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Mengatur jumlah kode batang MaxiCode dalam mode penambahan terstruktur. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Mendapatkan enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1

**Returns:**
int - enkoding ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Mendapatkan mode enkode MaxiCode. Nilai default: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Mendapatkan mode enkode MaxiCode. Nilai default: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


Mendapatkan mode enkode MaxiCode.

**Returns:**
int - sebuah mode enkode MaxiCode.
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


Mendapatkan ID kode batang MaxiCode dalam mode penambahan terstruktur. ID harus berupa nilai antara 1 dan 8. Nilai default: 0

**Returns:**
int - sebuah ID barcode MaxiCode dalam mode penambahan terstruktur.
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


Mendapatkan jumlah kode batang MaxiCode dalam mode penambahan terstruktur. Jumlah harus berupa nilai antara 2 dan 8 (jumlah kode batang maksimum). Nilai default: -1

**Returns:**
int - sebuah jumlah barcode MaxiCode dalam mode penambahan terstruktur.
### getMode() {#getMode--}
```
public final int getMode()
```


Mendapatkan mode enkode MaxiCode.

**Returns:**
int - sebuah mode enkode MaxiCode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Mendapatkan ID kode batang MaxiCode dalam mode penambahan terstruktur. ID harus berupa nilai antara 1 dan 8. Nilai default: 0

**Returns:**
int - sebuah ID barcode MaxiCode dalam mode penambahan terstruktur.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Mendapatkan jumlah kode batang MaxiCode dalam mode penambahan terstruktur. Jumlah harus berupa nilai antara 2 dan 8 (jumlah kode batang maksimum). Nilai default: -1

**Returns:**
int - sebuah jumlah barcode MaxiCode dalam mode penambahan terstruktur.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Mengatur enkoding ECI. Digunakan ketika MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | Enkoding ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Mengatur mode enkode MaxiCode. Nilai default: Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | sebuah mode enkode MaxiCode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Mengatur mode enkode MaxiCode. Nilai default: Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | sebuah mode enkode MaxiCode. |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


Mengatur mode enkode MaxiCode.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | sebuah mode enkode MaxiCode. |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


Mengatur ID kode batang MaxiCode dalam mode penambahan terstruktur. ID harus berupa nilai antara 1 dan 8. Nilai default: 0

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | sebuah ID kode batang MaxiCode dalam mode penambahan terstruktur. |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


Mengatur jumlah kode batang MaxiCode dalam mode penambahan terstruktur. Jumlah harus berupa nilai antara 2 dan 8 (jumlah kode batang maksimum). Nilai default: -1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | jumlah barcode MaxiCode dalam mode penambahan terstruktur. |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Mengatur mode enkode MaxiCode.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | sebuah mode enkode MaxiCode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Mengatur ID kode batang MaxiCode dalam mode penambahan terstruktur. ID harus berupa nilai antara 1 dan 8. Nilai default: 0

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | sebuah ID kode batang MaxiCode dalam mode penambahan terstruktur. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Mengatur jumlah kode batang MaxiCode dalam mode penambahan terstruktur. Jumlah harus berupa nilai antara 2 dan 8 (jumlah kode batang maksimum). Nilai default: -1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int | jumlah barcode MaxiCode dalam mode penambahan terstruktur. |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - Sebuah string yang mewakili [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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

