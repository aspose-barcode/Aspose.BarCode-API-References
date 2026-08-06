---
title: GraphicsUnit
second_title: Aspose.BarCode for Android via Java API Reference
description: 주어진 데이터의 측정 단위를 지정합니다.
type: docs
weight: 88
url: /ko/androidjava/com.aspose.barcode.generation/graphicsunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum GraphicsUnit extends Enum<GraphicsUnit>
```

주어진 데이터의 측정 단위를 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [DISPLAY](#DISPLAY) | 디스플레이 장치의 측정 단위를 지정합니다. |
| [DOCUMENT](#DOCUMENT) | 문서 단위(1/300 인치)를 측정 단위로 지정합니다. |
| [INCH](#INCH) | 인치를 측정 단위로 지정합니다. |
| [MILLIMETER](#MILLIMETER) | 밀리미터를 측정 단위로 지정합니다. |
| [PIXEL](#PIXEL) | 디바이스 픽셀을 측정 단위로 지정합니다. |
| [POINT](#POINT) | 프린터 포인트(1/72 인치)를 측정 단위로 지정합니다. |
| [WORLD](#WORLD) | 월드 좌표계 단위를 측정 단위로 지정합니다. |
## Methods

| Method | 설명 |
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


디스플레이 장치의 측정 단위를 지정합니다. 일반적으로 비디오 디스플레이는 픽셀이며, 프린터는 1/100 인치를 사용합니다.

### DOCUMENT {#DOCUMENT}
```
public static final GraphicsUnit DOCUMENT
```


문서 단위(1/300 인치)를 측정 단위로 지정합니다.

### INCH {#INCH}
```
public static final GraphicsUnit INCH
```


인치를 측정 단위로 지정합니다.

### MILLIMETER {#MILLIMETER}
```
public static final GraphicsUnit MILLIMETER
```


밀리미터를 측정 단위로 지정합니다.

### PIXEL {#PIXEL}
```
public static final GraphicsUnit PIXEL
```


디바이스 픽셀을 측정 단위로 지정합니다.

### POINT {#POINT}
```
public static final GraphicsUnit POINT
```


프린터 포인트(1/72 인치)를 측정 단위로 지정합니다.

### WORLD {#WORLD}
```
public static final GraphicsUnit WORLD
```


월드 좌표계 단위를 측정 단위로 지정합니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

