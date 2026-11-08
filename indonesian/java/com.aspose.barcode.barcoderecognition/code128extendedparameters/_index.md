---
title: "Code128ExtendedParameters"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Menyimpan data khusus dari barcode Code128 yang dikenali"
type: docs
weight: 27
url: /id/java/com.aspose.barcode.barcoderecognition/code128extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Code128ExtendedParameters extends BaseExtendedParameters
```

Menyimpan data khusus dari barcode Code128 yang dikenali

Mewakili wilayah barcode yang dikenali dan sudut barcode

--------------------

> ```
> This sample shows how to get code128 raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("Code128 Data Portions: " + result.getExtended().getCode128());
>  }
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  Code128ExtendedParameters  yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getCode128DataPortions()](#getCode128DataPortions--) | Mendapatkan array  Code128DataPortion  dari barcode Code128 yang dikenali |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEmpty()](#isEmpty--) | Menguji apakah semua parameter hanya memiliki nilai default |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari  Code128ExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai  Code128ExtendedParameters  yang ditentukan.

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
### getCode128DataPortions() {#getCode128DataPortions--}
```
public Code128DataPortion[] getCode128DataPortions()
```


Mendapatkan array  Code128DataPortion  dari barcode Code128 yang dikenali

Nilai: Array dari  Code128DataPortion .

**Returns:**
com.aspose.barcode.barcoderecognition.Code128DataPortion[]
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


Mengembalikan representasi string yang dapat dibaca manusia dari  Code128ExtendedParameters .

**Returns:**
java.lang.String - String yang mewakili  Code128ExtendedParameters .
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

