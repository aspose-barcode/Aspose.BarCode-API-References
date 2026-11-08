---
title: "SvgColorMode"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Mode yang mungkin untuk mengisi warna dalam file svg. RGB adalah default dan didukung oleh SVG 1.1."
type: docs
weight: 106
url: /id/java/com.aspose.barcode.generation/svgcolormode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SvgColorMode extends Enum<SvgColorMode>
```

Mode yang mungkin untuk mengisi warna dalam file svg, RGB adalah default dan didukung oleh SVG 1.1. RGBA, HSL, HSLA diizinkan dalam standar SVG 2.0. Bahkan pada RGB opasitas akan diatur melalui parameter "fill-opacity"
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [HSL](#HSL) | Mode HSL, contoh: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| [HSLA](#HSLA) | Mode HSLA, contoh: fill="hsla(30, 50%, 70%, 0.8)" |
| [RGB](#RGB) | Mode RGB, contoh: fill="\#ff5511" fill-opacity="0.73". |
| [RGBA](#RGBA) | Mode RGBA, contoh: fill="rgba(255, 85, 17, 0.73)" |
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
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HSL {#HSL}
```
public static final SvgColorMode HSL
```


Mode HSL, contoh: fill="hsl(17, 100%, 53%)" fill-opacity="0.73"

### HSLA {#HSLA}
```
public static final SvgColorMode HSLA
```


Mode HSLA, contoh: fill="hsla(30, 50%, 70%, 0.8)"

### RGB {#RGB}
```
public static final SvgColorMode RGB
```


Mode RGB, contoh: fill="\#ff5511" fill-opacity="0.73". Mode default.

### RGBA {#RGBA}
```
public static final SvgColorMode RGBA
```


Mode RGBA, contoh: fill="rgba(255, 85, 17, 0.73)"

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
public static SvgColorMode fromValue(int value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

**Returns:**
[SvgColorMode](../../com.aspose.barcode.generation/svgcolormode)
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
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SvgColorMode valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[SvgColorMode](../../com.aspose.barcode.generation/svgcolormode)
### values() {#values--}
```
public static SvgColorMode[] values()
```




**Returns:**
com.aspose.barcode.generation.SvgColorMode[]
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

