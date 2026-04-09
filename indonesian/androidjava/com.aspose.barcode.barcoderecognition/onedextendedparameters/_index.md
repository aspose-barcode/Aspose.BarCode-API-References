---
title: OneDExtendedParameters
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Menyimpan data khusus dari kode batang 1D yang dikenali seperti teks kode terpisah dan checksum
type: docs
weight: 39
url: /id/androidjava/com.aspose.barcode.barcoderecognition/onedextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class OneDExtendedParameters extends BaseExtendedParameters
```

Menyimpan data khusus dari kode batang 1D yang dikenali seperti teks kode terpisah dan checksum

--------------------

> ```
> This sample shows how to get 1D barcode value and checksum
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.EAN_13);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>     System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>  }
> ```
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai OneDExtendedParameters yang ditentukan. |
| [getCheckSum()](#getCheckSum--) | Mendapatkan checksum untuk kode batang 1D. |
| [getClass()](#getClass--) |  |
| [getValue()](#getValue--) | Mendapatkan teks kode dari kode batang 1D tanpa checksum. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua parameter hanya memiliki nilai default |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari OneDExtendedParameters ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai OneDExtendedParameters yang ditentukan.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Nilai System.Object untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  **true**  jika obj memiliki nilai yang sama dengan instance ini; jika tidak,  **false** .
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


Mendapatkan checksum untuk kode batang 1D.

Nilai: Checksum untuk kode batang 1D.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getValue() {#getValue--}
```
public String getValue()
```


Mendapatkan teks kode dari kode batang 1D tanpa checksum.

Nilai: Teks kode dari kode batang 1D tanpa checksum.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
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


Mengembalikan representasi string yang dapat dibaca manusia dari OneDExtendedParameters ini.

**Returns:**
java.lang.String - String yang merepresentasikan OneDExtendedParameters ini.
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

