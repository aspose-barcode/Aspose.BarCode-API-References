---
title: GraphicsUnit
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Menentukan satuan ukuran untuk data yang diberikan.
type: docs
weight: 88
url: /id/androidjava/com.aspose.barcode.generation/graphicsunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum GraphicsUnit extends Enum<GraphicsUnit>
```

Menentukan satuan ukuran untuk data yang diberikan.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DISPLAY](#DISPLAY) | Menentukan satuan ukuran perangkat tampilan. |
| [DOCUMENT](#DOCUMENT) | Menentukan satuan dokumen (1/300 inci) sebagai satuan ukuran. |
| [INCH](#INCH) | Menentukan inci sebagai satuan ukuran. |
| [MILLIMETER](#MILLIMETER) | Menentukan milimeter sebagai satuan ukuran. |
| [PIXEL](#PIXEL) | Menentukan piksel perangkat sebagai satuan ukuran. |
| [POINT](#POINT) | Menentukan titik printer (1/72 inci) sebagai satuan ukuran. |
| [WORLD](#WORLD) | Menentukan satuan sistem koordinat dunia sebagai satuan ukuran. |
## Methods

| Method | Deskripsi |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getGraphicsUnitName(int graphicsUnit)](#getGraphicsUnitName-int-) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DISPLAY {#DISPLAY}
```
public static final GraphicsUnit DISPLAY
```


Menentukan satuan ukuran perangkat tampilan. Biasanya piksel untuk tampilan video, dan 1/100 inci untuk printer.

### DOCUMENT {#DOCUMENT}
```
public static final GraphicsUnit DOCUMENT
```


Menentukan satuan dokumen (1/300 inci) sebagai satuan ukuran.

### INCH {#INCH}
```
public static final GraphicsUnit INCH
```


Menentukan inci sebagai satuan ukuran.

### MILLIMETER {#MILLIMETER}
```
public static final GraphicsUnit MILLIMETER
```


Menentukan milimeter sebagai satuan ukuran.

### PIXEL {#PIXEL}
```
public static final GraphicsUnit PIXEL
```


Menentukan piksel perangkat sebagai satuan ukuran.

### POINT {#POINT}
```
public static final GraphicsUnit POINT
```


Menentukan titik printer (1/72 inci) sebagai satuan ukuran.

### WORLD {#WORLD}
```
public static final GraphicsUnit WORLD
```


Menentukan satuan sistem koordinat dunia sebagai satuan ukuran.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getGraphicsUnitName(int graphicsUnit) {#getGraphicsUnitName-int-}
```
public static String getGraphicsUnitName(int graphicsUnit)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| graphicsUnit | int |  |

**Returns:**
java.lang.String
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
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static GraphicsUnit valueOf(String name)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit)
### values() {#values--}
```
public static GraphicsUnit[] values()
```




**Returns:**
com.aspose.barcode.generation.GraphicsUnit[]
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

