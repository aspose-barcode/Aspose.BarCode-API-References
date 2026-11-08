---
title: "QrParametersUI"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Pembungkus UI untuk kelas com.aspose.barcode.generation.QrParameters."
type: docs
weight: 17
url: /id/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

Pembungkus UI untuk kelas com.aspose.barcode.generation.QrParameters.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR. |
| [getEncodeMode()](#getEncodeMode--) | Tipe simbolologi QR dari mode enkoding BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. |
| [getMicroQrVersion()](#getMicroQrVersion--) | Versi MicroQR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Versi RectMicroQR Code. |
| [getVersion()](#getVersion--) | Versi QR Code. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Rasio Tinggi/ Lebar modul BarCode 2D. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Pengidentifikasi Interpretasi Saluran Terluas. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Tipe simbolologi QR dari mode enkoding BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | Versi MicroQR Code. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Versi RectMicroQR Code. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Versi QR Code. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [QrParameters](../../com.aspose.barcode.generation/qrparameters) ini. |
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
### getECIEncoding() {#getECIEncoding--}
```
public int getECIEncoding()
```


Identifier Interpretasi Saluran Diperluas. Ini digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR.

Jika false, pemisah GS1 dapat dienkode sebagai '%' dalam mode Alfanumerik sesuai spesifikasi QR.

Jika true, pemisah grup GS1 dienkode dalam mode Byte sebagai karakter 0x1D, dan karakter '%' juga dienkode dalam mode Byte untuk mempertahankannya sebagai data.

Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '%' diinterpretasikan sebagai pemisah GS1.

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Tipe simbolologi QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. lihat QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
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
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versi QR Code. Dari Version1 hingga Version40 untuk QR code dan dari M1 hingga M4 untuk MicroQr. Nilai default adalah QRVersion.Auto.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Identifier Interpretasi Saluran Diperluas. Ini digunakan untuk memberi tahu pembaca barcode detail tentang referensi yang digunakan untuk mengenkode data dalam simbol. Implementasi saat ini mencakup semua pengkodean charset yang dikenal. Tidak didukung oleh MicroQR.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk barcode QR dan RectMicroQR.

Jika false, pemisah GS1 dapat dienkode sebagai '%' dalam mode Alfanumerik sesuai spesifikasi QR.

Jika true, pemisah grup GS1 dienkode dalam mode Byte sebagai karakter 0x1D, dan karakter '%' juga dienkode dalam mode Byte untuk mempertahankannya sebagai data.

Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '%' diinterpretasikan sebagai pemisah GS1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Tipe simbolologi QR dari mode enkoding BarCode. Nilai default: QREncodeMode.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Tingkat koreksi kesalahan Reed-Solomon untuk barcode QR, MicroQR, dan RectMicroQR. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH. lihat QRErrorLevel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
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

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Versi QR Code. Dari Version1 hingga Version40 untuk QR code dan dari M1 hingga M4 untuk MicroQr. Nilai default adalah QRVersion.Auto.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari [QrParameters](../../com.aspose.barcode.generation/qrparameters) ini.

**Returns:**
java.lang.String - String yang mewakili ini [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

