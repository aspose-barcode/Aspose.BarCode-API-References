---
title: Unit
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Menentukan nilai ukuran dalam unit yang berbeda seperti Piksel, Inci, dll..
type: docs
weight: 69
url: /id/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Menentukan nilai ukuran dalam unit yang berbeda (Pixel, Inci, dll.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah instance ini dan objek yang ditentukan, yang juga harus berupa objek Unit, memiliki nilai yang sama. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Mendapatkan nilai ukuran dalam unit dokumen. |
| [getInches()](#getInches--) | Mendapatkan nilai ukuran dalam inci. |
| [getMillimeters()](#getMillimeters--) | Mendapatkan nilai ukuran dalam milimeter. |
| [getPixels()](#getPixels--) | Mendapatkan nilai ukuran dalam piksel. |
| [getPoint()](#getPoint--) | Mendapatkan nilai ukuran dalam poin. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk objek ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Mengatur nilai ukuran dalam unit dokumen. |
| [setInches(float value)](#setInches-float-) | Mengatur nilai ukuran dalam inci. |
| [setMillimeters(float value)](#setMillimeters-float-) | Mengatur nilai ukuran dalam milimeter. |
| [setPixels(float value)](#setPixels-float-) | Mengatur nilai ukuran dalam piksel. |
| [setPoint(float value)](#setPoint-float-) | Mengatur nilai ukuran dalam poin. |
| [toString()](#toString--) | Mengembalikan representasi string yang dapat dibaca manusia dari Unit ini. |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah instance ini dan objek yang ditentukan, yang juga harus berupa objek Unit, memiliki nilai yang sama.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Unit untuk dibandingkan dengan instance ini. |

**Returns:**
boolean - true jika obj adalah Unit dan nilainya sama dengan instance ini; jika tidak, false. Jika obj bernilai null, metode mengembalikan false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


Mendapatkan nilai ukuran dalam unit dokumen.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Mendapatkan nilai ukuran dalam inci.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Mendapatkan nilai ukuran dalam milimeter.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Mendapatkan nilai ukuran dalam piksel.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Mendapatkan nilai ukuran dalam poin.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk objek ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


Mengatur nilai ukuran dalam unit dokumen.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Mengatur nilai ukuran dalam inci.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Mengatur nilai ukuran dalam milimeter.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Mengatur nilai ukuran dalam piksel.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Mengatur nilai ukuran dalam poin.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string yang dapat dibaca manusia dari Unit ini.

**Returns:**
java.lang.String - String yang mewakili Unit ini.
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dpi | float |  |

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

