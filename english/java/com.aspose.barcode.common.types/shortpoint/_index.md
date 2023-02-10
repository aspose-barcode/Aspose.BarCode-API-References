---
title: ShortPoint
second_title: Aspose.BarCode for Java API Reference
description: Represents an ordered pair of shor x- and y-coordinates that defines a point in a two-dimensional plane.
type: docs
weight: 11
url: /java/com.aspose.barcode.common.types/shortpoint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class ShortPoint extends Struct<ShortPoint>
```

Represents an ordered pair of shor x- and y-coordinates that defines a point in a two-dimensional plane.
## Constructors

| Constructor | Description |
| --- | --- |
| [ShortPoint()](#ShortPoint--) |  |
| [ShortPoint(short x, short y)](#ShortPoint-short-short-) | Initializes a new instance of the  ShortPoint  struct with the specified coordinates. |
## Fields

| Field | Description |
| --- | --- |
| [X](#X) |  |
| [Y](#Y) |  |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(ShortPoint that)](#CloneTo-com.aspose.barcode.common.types.ShortPoint-) |  |
| [cast(System.Drawing.Point point)](#cast-com.aspose.ms.System.Drawing.Point-) | Initializes a new instance of the  ShortPoint  struct with the specified coordinates. |
| [cast(int x, int y)](#cast-int-int-) | Initializes a new instance of the  ShortPoint  struct with the specified coordinates. |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHashCode()](#getHashCode--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toFloatPoint()](#toFloatPoint--) |  |
| [toIntPoint()](#toIntPoint--) | Converts this ShortPoint to System.Drawing.Point. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShortPoint() {#ShortPoint--}
```
public ShortPoint()
```


### ShortPoint(short x, short y) {#ShortPoint-short-short-}
```
public ShortPoint(short x, short y)
```


Initializes a new instance of the  ShortPoint  struct with the specified coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | short | x: The horizontal position of the point. |
| y | short | y: The vertical position of the point. |

### X {#X}
```
public short X
```


### Y {#Y}
```
public short Y
```


### Clone() {#Clone--}
```
public ShortPoint Clone()
```




**Returns:**
[ShortPoint](../../com.aspose.barcode.common.types/shortpoint)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(ShortPoint that) {#CloneTo-com.aspose.barcode.common.types.ShortPoint-}
```
public void CloneTo(ShortPoint that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [ShortPoint](../../com.aspose.barcode.common.types/shortpoint) |  |

### cast(System.Drawing.Point point) {#cast-com.aspose.ms.System.Drawing.Point-}
```
public static ShortPoint cast(System.Drawing.Point point)
```


Initializes a new instance of the  ShortPoint  struct with the specified coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point | The System.Drawing.Point to cast. |

**Returns:**
[ShortPoint](../../com.aspose.barcode.common.types/shortpoint) - a cast point
### cast(int x, int y) {#cast-int-int-}
```
public static ShortPoint cast(int x, int y)
```


Initializes a new instance of the  ShortPoint  struct with the specified coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | x: The horizontal position of the point. |
| y | int | y: The vertical position of the point. |

**Returns:**
[ShortPoint](../../com.aspose.barcode.common.types/shortpoint)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHashCode() {#getHashCode--}
```
public int getHashCode()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
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




### toFloatPoint() {#toFloatPoint--}
```
public System.Drawing.PointF toFloatPoint()
```




**Returns:**
com.aspose.ms.System.Drawing.PointF
### toIntPoint() {#toIntPoint--}
```
public System.Drawing.Point toIntPoint()
```


Converts this ShortPoint to System.Drawing.Point.

**Returns:**
com.aspose.ms.System.Drawing.Point - A System.Drawing.Point that represents this ShortPoint
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

