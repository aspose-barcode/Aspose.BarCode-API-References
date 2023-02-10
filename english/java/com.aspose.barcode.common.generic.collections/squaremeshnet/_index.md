---
title: SquareMeshNet
second_title: Aspose.BarCode for Java API Reference
description: Optimizing square mesh net
type: docs
weight: 11
url: /java/com.aspose.barcode.common.generic.collections/squaremeshnet/
---
**Inheritance:**
java.lang.Object
```
public class SquareMeshNet
```

Optimizing square mesh net

 T : Type
## Constructors

| Constructor | Description |
| --- | --- |
| [SquareMeshNet(int netWidth, int netHeight, int cellSize)](#SquareMeshNet-int-int-int-) | Initializes a new instance of SquareMeshNet class. |
## Fields

| Field | Description |
| --- | --- |
| [cells](#cells) | cells |
| [height](#height) | Net height |
| [width](#width) | Net width |
## Methods

| Method | Description |
| --- | --- |
| [buildNet(List<Spot> iPoints)](#buildNet-java.util.List-com.aspose.barcode.common.types.Spot--) | Build the net by list of IPoints |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItem(System.Drawing.Point point)](#getItem-com.aspose.ms.System.Drawing.Point-) | Gets a value of a cell |
| [getItem(int i, int j)](#getItem-int-int-) | Gets a value of a cell |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setItem(System.Drawing.Point point, List<Spot> value)](#setItem-com.aspose.ms.System.Drawing.Point-java.util.List-com.aspose.barcode.common.types.Spot--) | Sets a value of a cell |
| [setItem(int i, int j, List<Spot> value)](#setItem-int-int-java.util.List-com.aspose.barcode.common.types.Spot--) | Sets a value of a cell |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SquareMeshNet(int netWidth, int netHeight, int cellSize) {#SquareMeshNet-int-int-int-}
```
public SquareMeshNet(int netWidth, int netHeight, int cellSize)
```


Initializes a new instance of SquareMeshNet class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| netWidth | int | A width |
| netHeight | int | A height |
| cellSize | int | Cell size |

### cells {#cells}
```
public List<List<Spot>> cells
```


cells

### height {#height}
```
public int height
```


Net height

### width {#width}
```
public int width
```


Net width

### buildNet(List<Spot> iPoints) {#buildNet-java.util.List-com.aspose.barcode.common.types.Spot--}
```
public void buildNet(List<Spot> iPoints)
```


Build the net by list of IPoints

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| iPoints | java.util.List<com.aspose.barcode.common.types.Spot> | A list of IPoints |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getItem(System.Drawing.Point point) {#getItem-com.aspose.ms.System.Drawing.Point-}
```
public List<Spot> getItem(System.Drawing.Point point)
```


Gets a value of a cell

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point | Coordinate of a cell |

**Returns:**
[List](../../java.util/list) - Cell value
### getItem(int i, int j) {#getItem-int-int-}
```
public List<Spot> getItem(int i, int j)
```


Gets a value of a cell

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int | X-coordinate of a cell |
| j | int | Y-coordinate of a cell |

**Returns:**
[List](../../java.util/list) - Cell value
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




### setItem(System.Drawing.Point point, List<Spot> value) {#setItem-com.aspose.ms.System.Drawing.Point-java.util.List-com.aspose.barcode.common.types.Spot--}
```
public void setItem(System.Drawing.Point point, List<Spot> value)
```


Sets a value of a cell

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point | Coordinate of a cell |
| value | java.util.List<com.aspose.barcode.common.types.Spot> |  |

### setItem(int i, int j, List<Spot> value) {#setItem-int-int-java.util.List-com.aspose.barcode.common.types.Spot--}
```
public void setItem(int i, int j, List<Spot> value)
```


Sets a value of a cell

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int | X-coordinate of a cell |
| j | int | Y-coordinate of a cell |
| value | java.util.List<com.aspose.barcode.common.types.Spot> |  |

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

