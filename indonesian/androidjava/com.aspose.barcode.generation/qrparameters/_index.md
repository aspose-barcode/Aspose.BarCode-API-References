---
title: "QrParameters"
second_title: "Referensi API Aspose.BarCode untuk Android via Java"
description: "Parameter QR."
type: docs
weight: 62
url: /id/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Parameter QR.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/Lebar modul 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | Tipe simbol QR dari mode enkoding BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Level koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versi MicroQR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versi RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Parameter penambahan terstruktur QR. |
| [getVersion()](#getVersion--) | Versi QR Code. Dari Version1 hingga Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/Lebar modul 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Tipe simbol QR dari mode enkoding BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Level koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versi MicroQR Code. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Versi RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | Parameter penambahan terstruktur QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Versi QR Code. Dari Version1 hingga Version40. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifier Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


Mendapatkan atau menetapkan nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR.

Jika false, pemisah GS1 dapat dienkode sebagai '%' dalam mode Alfanumerik menurut spesifikasi QR.

Jika true, pemisah grup GS1 dienkode dalam mode Byte sebagai karakter 0x1D, dan karakter '%' juga dienkode dalam mode Byte untuk mempertahankannya sebagai data.

Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '%' diinterpretasikan sebagai pemisah GS1.

**Returns:**
boolean - nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR.
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


Level koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
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


Parameter penambahan terstruktur QR. Mode penambahan terstruktur tidak didukung oleh barcode MicroQR dan RectMicroQR.

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
public final int hashCode()
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


Rasio Tinggi/Lebar modul 2D BarCode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifier Interpretasi Saluran yang Diperluas. Ini digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


Mendapatkan atau menetapkan nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR.

Jika false, pemisah GS1 dapat dienkode sebagai '%' dalam mode Alfanumerik menurut spesifikasi QR.

Jika true, pemisah grup GS1 dienkode dalam mode Byte sebagai karakter 0x1D, dan karakter '%' juga dienkode dalam mode Byte untuk mempertahankannya sebagai data.

Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '%' diinterpretasikan sebagai pemisah GS1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR. |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Tipe simbol QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Level koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. Lihat QRErrorLevel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Versi MicroQR Code. Dari versi M1 hingga versi M4. Nilai default adalah MicroQRVersion.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Versi RectMicroQR Code. Dari versi R7x59 hingga versi R17x139. Nilai default adalah RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Parameter penambahan terstruktur QR. Mode penambahan terstruktur tidak didukung oleh barcode MicroQR dan RectMicroQR.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Versi QR Code. Dari Version1 hingga Version40. Nilai default adalah QRVersion.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - String yang mewakili [QrParameters](../../com.aspose.barcode.generation/qrparameters) ini.
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

