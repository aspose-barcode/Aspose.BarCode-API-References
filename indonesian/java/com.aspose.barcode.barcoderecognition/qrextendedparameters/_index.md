---
title: "QRExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Menyimpan informasi QR Structured Append dari barcode yang dikenali"
type: docs
weight: 38
url: /id/java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Menyimpan informasi QR Structured Append dari barcode yang dikenali

Contoh ini menunjukkan cara mendapatkan data QR Structured Append

```
{
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Level koreksi kesalahan Reed-Solomon dari barcode yang dikenali. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Versi MicroQR Code yang dikenali. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Versi RectMicroQR Code yang dikenali. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Mendapatkan indeks barcode mode penambahan terstruktur QR. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Mendapatkan jumlah barcode mode penambahan terstruktur QR. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Mendapatkan data parity mode penambahan terstruktur QR. |
| [getVersion()](#getVersion--) | Versi QR Code yang dikenali. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua parameter hanya memiliki nilai default |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
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
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Level koreksi kesalahan Reed-Solomon dari barcode yang dikenali. Dari rendah ke tinggi: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Versi MicroQR Code yang dikenali. Dari M1 hingga M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Versi RectMicroQR Code yang dikenali. Dari R7x43 hingga R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Mendapatkan indeks barcode mode penambahan terstruktur QR. Indeks dimulai dari 0. Nilai default adalah -1.

Nilai: Jumlah barcode mode penambahan terstruktur QR.

**Returns:**
int - indeks barcode mode penambahan terstruktur QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Mendapatkan jumlah barcode mode penambahan terstruktur QR. Nilai default adalah -1.

Nilai: Jumlah barcode mode penambahan terstruktur QR.

**Returns:**
int - jumlah barcode mode penambahan terstruktur QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Mendapatkan data parity mode penambahan terstruktur QR. Nilai default adalah -1.

Nilai: Indeks barcode mode penambahan terstruktur QR.

**Returns:**
int - data parity mode penambahan terstruktur QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Versi QR Code yang dikenali. Dari Versi1 hingga Versi40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash bilangan bulat bertanda 32-bit.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Menguji apakah semua parameter hanya memiliki nilai default

Value: Mengembalikan **true** jika semua parameter hanya memiliki nilai default; jika tidak, **false**.

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


Mengembalikan representasi string yang dapat dibaca manusia dari [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - String yang mewakili [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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

