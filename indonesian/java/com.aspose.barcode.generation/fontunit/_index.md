---
title: "FontUnit"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Mendefinisikan format khusus untuk teks termasuk ukuran font, gaya, dan atribut lainnya dimana ukuran berada dalam properti nilai Unit."
type: docs
weight: 42
url: /id/java/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

Mendefinisikan format tertentu untuk teks, termasuk jenis huruf, ukuran, dan atribut gaya dimana ukuran berada dalam properti nilai Unit.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | Mendapatkan nama font dari Font ini. |
| [getSize()](#getSize--) | Mendapatkan ukuran FontUnit ini dalam nilai Unit. |
| [getStyle()](#getStyle--) | Mendapatkan informasi gaya untuk FontUnit ini. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Mengatur nama font dari Font ini. |
| [setStyle(int value)](#setStyle-int-) | Mengatur informasi gaya untuk FontUnit ini. |
| [toString()](#toString--) |  |
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
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Mendapatkan nama font dari Font ini.

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public Unit getSize()
```


Mendapatkan ukuran FontUnit ini dalam nilai Unit.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStyle() {#getStyle--}
```
public int getStyle()
```


Mendapatkan informasi gaya untuk FontUnit ini.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Mengatur nama font dari Font ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Mengatur informasi gaya untuk FontUnit ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

