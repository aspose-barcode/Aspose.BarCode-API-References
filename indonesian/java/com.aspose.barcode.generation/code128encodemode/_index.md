---
title: "Code128EncodeMode"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Mode enkoding untuk kode batang Code128."
type: docs
weight: 78
url: /id/java/com.aspose.barcode.generation/code128encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128EncodeMode extends Enum<Code128EncodeMode>
```

Mode pengkodean untuk kode batang Code128. Spesifikasi Code 128.

--------------------

> ```
> Thos code demonstrates how to generate code 128 with different encodings
>  
> 
>  //Generate code 128 with ISO 15417 encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO);
>  generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG);
> 
>  //Generate code 128 only with Codeset A encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A);
>  generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);
> ```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [AUTO](#AUTO) | Enkode teks kode dalam mode klasik ISO 15417. |
| [CODE_A](#CODE-A) | Enkode teks kode hanya dalam set kode 128A. |
| [CODE_AB](#CODE-AB) | Enkode teks kode hanya dalam set kode 128A dan 128B. |
| [CODE_AC](#CODE-AC) | Enkode teks kode hanya dalam set kode 128A dan 128C. |
| [CODE_B](#CODE-B) | Enkode teks kode hanya dalam set kode 128B. |
| [CODE_BC](#CODE-BC) | Enkode teks kode hanya dalam set kode 128B dan 128C. |
| [CODE_C](#CODE-C) | Enkode teks kode hanya dalam set kode 128C. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(int value)](#valueOf-int-) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final Code128EncodeMode AUTO
```


Enkode teks kode dalam mode klasik ISO 15417. Mode ini harus digunakan dalam semua kasus biasa.

### CODE_A {#CODE-A}
```
public static final Code128EncodeMode CODE_A
```


Enkode teks kode hanya dalam set kode 128A.

### CODE_AB {#CODE-AB}
```
public static final Code128EncodeMode CODE_AB
```


Enkode teks kode hanya dalam set kode 128A dan 128B.

### CODE_AC {#CODE-AC}
```
public static final Code128EncodeMode CODE_AC
```


Enkode teks kode hanya dalam set kode 128A dan 128C.

### CODE_B {#CODE-B}
```
public static final Code128EncodeMode CODE_B
```


Enkode teks kode hanya dalam set kode 128B.

### CODE_BC {#CODE-BC}
```
public static final Code128EncodeMode CODE_BC
```


Enkode teks kode hanya dalam set kode 128B dan 128C.

### CODE_C {#CODE-C}
```
public static final Code128EncodeMode CODE_C
```


Enkode teks kode hanya dalam set kode 128C.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static Code128EncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(int value) {#valueOf-int-}
```
public static Code128EncodeMode valueOf(int value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Code128EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### values() {#values--}
```
public static Code128EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Code128EncodeMode[]
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

