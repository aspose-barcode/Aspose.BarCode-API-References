---
title: QrParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Parameter QR.
type: docs
weight: 64
url: /id/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Parameter QR.
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [getEncodeMode()](#getEncodeMode--) | Tipe simbol QR dari mode enkoding BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Level koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versi MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [getQrEncodeMode()](#getQrEncodeMode--) | Tipe simbol QR dari mode enkoding BarCode. |
| [getQrEncodeType()](#getQrEncodeType--) | Mode pemilih QR / MicroQR. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Level koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. |
| [getQrVersion()](#getQrVersion--) | Versi QR Code. Dari Versi1 hingga Versi40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versi RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Parameter penambahan terstruktur QR. |
| [getVersion()](#getVersion--) | Versi QR Code. Dari Versi1 hingga Versi40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Diperluas. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Tipe simbol QR dari mode enkoding BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Level koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versi MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | Mode pemilih QR / MicroQR. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Versi RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | Parameter penambahan terstruktur QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Versi QR Code. Dari Versi1 hingga Versi40. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [QrParameters](../../com.aspose.barcode.generation/qrparameters) ini. |
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


Identifier Interpretasi Saluran Diperluas. Digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Tingkat koreksi kesalahan Reed-Solomon untuk kode batang QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QERrrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Identifier Interpretasi Saluran Diperluas. Digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


Mode pemilih QR / MicroQR. Pilih ForceQR untuk simbol QR standar, Auto untuk MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Tingkat koreksi kesalahan Reed-Solomon untuk kode batang QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QERrrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Versi QR Code. Dari Version1 hingga Version40. Nilai default adalah QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


Parameter penambahan terstruktur QR. Mode penambahan terstruktur tidak didukung oleh kode batang MicroQR dan RectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versi QR Code. Dari Version1 hingga Version40. Nilai default adalah QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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


Identifier Interpretasi Saluran Diperluas. Digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Tingkat koreksi kesalahan Reed-Solomon untuk kode batang QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QERrrorLevel.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


Mode pemilih QR / MicroQR. Pilih ForceQR untuk simbol QR standar, Auto untuk MicroQR.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Parameter penambahan terstruktur QR. Mode penambahan terstruktur tidak didukung oleh kode batang MicroQR dan RectMicroQR.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Versi QR Code. Dari Version1 hingga Version40. Nilai default adalah QRVersion.Auto.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [QrParameters](../../com.aspose.barcode.generation/qrparameters) ini.

**Returns:**
java.lang.String - Sebuah string yang mewakili ini [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

