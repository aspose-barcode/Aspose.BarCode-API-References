---
title: SvgColorMode
second_title: Aspose.BarCode for Java API Reference
description: Possible modes for filling color in svg file RGB is default and supported by SVG 1.1.
type: docs
weight: 102
url: /java/com.aspose.barcode.generation/svgcolormode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SvgColorMode extends Enum<SvgColorMode>
```

Possible modes for filling color in svg file, RGB is default and supported by SVG 1.1. RGBA, HSL, HSLA is allowed in SVG 2.0 standard. Even in RGB opacity will be set through "fill-opacity" parameter
## Fields

| Field | Description |
| --- | --- |
| [HSL](#HSL) | HSL mode, example: fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| [HSLA](#HSLA) | HSLA mode, example: fill="hsla(30, 50%, 70%, 0.8)" |
| [RGB](#RGB) | RGB mode, example: fill="\#ff5511" fill-opacity="0.73". |
| [RGBA](#RGBA) | RGBA mode, example: fill="rgba(255, 85, 17, 0.73)" |
## Methods

| Method | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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


HSL mode, example: fill="hsl(17, 100%, 53%)" fill-opacity="0.73"

### HSLA {#HSLA}
```
public static final SvgColorMode HSLA
```


HSLA mode, example: fill="hsla(30, 50%, 70%, 0.8)"

### RGB {#RGB}
```
public static final SvgColorMode RGB
```


RGB mode, example: fill="\#ff5511" fill-opacity="0.73". Default mode.

### RGBA {#RGBA}
```
public static final SvgColorMode RGBA
```


RGBA mode, example: fill="rgba(255, 85, 17, 0.73)"

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.SvgColorMode
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

