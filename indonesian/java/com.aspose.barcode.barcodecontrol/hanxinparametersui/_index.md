---
title: "HanXinParametersUI"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: 
type: docs
weight: 15
url: /id/java/com.aspose.barcode.barcodecontrol/hanxinparametersui/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParametersUI
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [getEncodeMode()](#getEncodeMode--) | Tipe simbolologi HanXin dari mode enkoding BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Level koreksi kesalahan Reed-Solomon untuk barcode HanXin. |
| [getVersion()](#getVersion--) | Versi Kode HanXin. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | Tipe simbolologi HanXin dari mode enkoding BarCode. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Level koreksi kesalahan Reed-Solomon untuk barcode HanXin. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | Versi Kode HanXin. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) ini. |
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


Pengidentifikasi Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini terdiri dari semua pengkodean charset yang dikenal.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


Tipe simbolologi HanXin dari mode enkoding BarCode. Nilai default: EncodeMode.Auto.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Level koreksi kesalahan Reed-Solomon untuk barcode HanXin. Dari rendah ke tinggi: L1 - L4. lihat ErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


Versi kode HanXin. Dari Version01 hingga Version84 untuk kode HanXin. Nilai default adalah Version.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Pengidentifikasi Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini terdiri dari semua pengkodean charset yang dikenal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


Tipe simbolologi HanXin dari mode enkoding BarCode. Nilai default: EncodeMode.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Level koreksi kesalahan Reed-Solomon untuk barcode HanXin. Dari rendah ke tinggi: L1 - L4. lihat ErrorLevel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


Versi kode HanXin. Dari Version01 hingga Version84 untuk kode HanXin. Nilai default adalah Version.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) ini.

**Returns:**
java.lang.String - String yang mewakili ini [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters).
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

