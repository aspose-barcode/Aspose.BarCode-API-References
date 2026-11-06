---
title: "GraphicsUnit"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "指定されたデータの測定単位を指定します。"
type: docs
weight: 87
url: /ja/androidjava/com.aspose.barcode.generation/graphicsunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum GraphicsUnit extends Enum<GraphicsUnit>
```

指定されたデータの測定単位を指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DISPLAY](#DISPLAY) | 表示デバイスの測定単位を指定します。 |
| [DOCUMENT](#DOCUMENT) | 文書単位 (1/300 インチ) を測定単位として指定します。 |
| [INCH](#INCH) | インチを測定単位として指定します。 |
| [MILLIMETER](#MILLIMETER) | ミリメートルを測定単位として指定します。 |
| [PIXEL](#PIXEL) | デバイスピクセルを測定単位として指定します。 |
| [POINT](#POINT) | プリンターのポイント (1/72 インチ) を測定単位として指定します。 |
| [WORLD](#WORLD) | ワールド座標系の単位を測定単位として指定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
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
### DISPLAY {#DISPLAY}
```
public static final GraphicsUnit DISPLAY
```


表示デバイスの測定単位を指定します。通常、ビデオディスプレイはピクセル、プリンターは 1/100 インチです。

### DOCUMENT {#DOCUMENT}
```
public static final GraphicsUnit DOCUMENT
```


文書単位 (1/300 インチ) を測定単位として指定します。

### INCH {#INCH}
```
public static final GraphicsUnit INCH
```


インチを測定単位として指定します。

### MILLIMETER {#MILLIMETER}
```
public static final GraphicsUnit MILLIMETER
```


ミリメートルを測定単位として指定します。

### PIXEL {#PIXEL}
```
public static final GraphicsUnit PIXEL
```


デバイスピクセルを測定単位として指定します。

### POINT {#POINT}
```
public static final GraphicsUnit POINT
```


プリンターのポイント (1/72 インチ) を測定単位として指定します。

### WORLD {#WORLD}
```
public static final GraphicsUnit WORLD
```


ワールド座標系の単位を測定単位として指定します。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static GraphicsUnit fromValue(int value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

**Returns:**
[GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit)
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
public static GraphicsUnit valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

