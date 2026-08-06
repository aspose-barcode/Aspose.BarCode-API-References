---
title: GraphicsUnit
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 指定给定数据的计量单位。
type: docs
weight: 88
url: /zh/androidjava/com.aspose.barcode.generation/graphicsunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum GraphicsUnit extends Enum<GraphicsUnit>
```

指定给定数据的计量单位。
## 字段

| 字段 | 描述 |
| --- | --- |
| [DISPLAY](#DISPLAY) | 指定显示设备的计量单位。 |
| [DOCUMENT](#DOCUMENT) | 指定文档单位（1/300 英寸）为计量单位。 |
| [INCH](#INCH) | 指定英寸为计量单位。 |
| [MILLIMETER](#MILLIMETER) | 指定毫米为计量单位。 |
| [PIXEL](#PIXEL) | 指定设备像素为计量单位。 |
| [POINT](#POINT) | 指定打印机点（1/72 英寸）为计量单位。 |
| [WORLD](#WORLD) | 指定世界坐标系单位为计量单位。 |
## Methods

| Method | 描述 |
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


指定显示设备的计量单位。通常视频显示为像素，打印机为 1/100 英寸。

### DOCUMENT {#DOCUMENT}
```
public static final GraphicsUnit DOCUMENT
```


指定文档单位（1/300 英寸）为计量单位。

### INCH {#INCH}
```
public static final GraphicsUnit INCH
```


指定英寸为计量单位。

### MILLIMETER {#MILLIMETER}
```
public static final GraphicsUnit MILLIMETER
```


指定毫米为计量单位。

### PIXEL {#PIXEL}
```
public static final GraphicsUnit PIXEL
```


指定设备像素为计量单位。

### POINT {#POINT}
```
public static final GraphicsUnit POINT
```


指定打印机点（1/72 英寸）为计量单位。

### WORLD {#WORLD}
```
public static final GraphicsUnit WORLD
```


指定世界坐标系单位为计量单位。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

