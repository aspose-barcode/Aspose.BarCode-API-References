---
title: DataBarExtendedParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Menyimpan informasi tambahan DataBar dari barcode yang dikenali BarCodeReader reader  new BarCodeReadertest.png DecodeType.DATABAR_OMNI_DIRECTIONAL forBarCodeResult result  reader.readBarCodes    System.out.printlnBarCode Type   result.getCodeTypeName    System.out.printlnBarCode CodeText   result.getCodeText    System.out.printlnQR Structured Append Quantity   result.getExtended.getQR.getQRStructuredAppendModeBarCodesQuantity
type: docs
weight: 30
url: /id/androidjava/com.aspose.barcode.barcoderecognition/databarextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public class DataBarExtendedParameters extends BaseExtendedParameters
```

Menyimpan informasi tambahan DataBar dari kode batang yang dikenali BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai yang ditentukan. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [is2DCompositeComponent()](#is2DCompositeComponent--) | Mendapatkan flag komponen komposit DataBar 2D. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua parameter hanya memiliki nilai default |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari ini . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:**
boolean - **true** jika obj memiliki nilai yang sama dengan instance ini; jika tidak, **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### is2DCompositeComponent() {#is2DCompositeComponent--}
```
public boolean is2DCompositeComponent()
```


Mendapatkan flag komponen komposit DataBar 2D. Nilai default adalah false.

**Returns:**
boolean - Flag komponen komposit DataBar 2D.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Menguji apakah semua parameter hanya memiliki nilai default

Nilai: Mengembalikan  **true**  jika semua parameter hanya memiliki nilai default; jika tidak,  **false** .

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


Mengembalikan representasi string yang dapat dibaca manusia dari ini .

**Returns:**
java.lang.String - Sebuah string yang merepresentasikan ini.
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

