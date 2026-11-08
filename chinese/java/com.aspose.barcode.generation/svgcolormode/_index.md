---
title: "SvgColorMode"
second_title: "Aspose.BarCode for Java API Reference"
description: "svg 文件中填充颜色的可能模式，默认是 RGB，且受 SVG 1.1 支持。"
type: docs
weight: 106
url: /zh/java/com.aspose.barcode.generation/svgcolormode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SvgColorMode extends Enum<SvgColorMode>
```

svg 文件中填充颜色的可能模式，RGB 为默认并受 SVG 1.1 支持。RGBA、HSL、HSLA 在 SVG 2.0 标准中被允许。即使是 RGB，透明度也将通过 "fill-opacity" 参数设置。
## 字段

| 字段 | 描述 |
| --- | --- |
| [HSL](#HSL) | HSL 模式，例如：fill="hsl(17, 100%, 53%)" fill-opacity="0.73" |
| [HSLA](#HSLA) | HSLA 模式，例如：fill="hsla(30, 50%, 70%, 0.8)" |
| [RGB](#RGB) | RGB 模式，例如：fill="\#ff5511" fill-opacity="0.73"。 |
| [RGBA](#RGBA) | RGBA 模式，例如：fill="rgba(255, 85, 17, 0.73)" |
## 方法

| 方法 | 描述 |
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


HSL 模式，例如：fill="hsl(17, 100%, 53%)" fill-opacity="0.73"

### HSLA {#HSLA}
```
public static final SvgColorMode HSLA
```


HSLA 模式，例如：fill="hsla(30, 50%, 70%, 0.8)"

### RGB {#RGB}
```
public static final SvgColorMode RGB
```


RGB 模式，例如：fill="\#ff5511" fill-opacity="0.73"。默认模式。

### RGBA {#RGBA}
```
public static final SvgColorMode RGBA
```


RGBA 模式，例如：fill="rgba(255, 85, 17, 0.73)"

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static SvgColorMode fromValue(int value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

