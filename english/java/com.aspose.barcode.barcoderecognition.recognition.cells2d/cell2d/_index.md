---
title: Cell2D
second_title: Aspose.BarCode for Java API Reference
description: 2D cell
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.cells2d/cell2d/
---
**Inheritance:**
java.lang.Object
```
public class Cell2D
```

2D cell
## Constructors

| Constructor | Description |
| --- | --- |
| [Cell2D()](#Cell2D--) |  |
## Fields

| Field | Description |
| --- | --- |
| [BlackCount](#BlackCount) | Count of black in the cell |
| [SumX](#SumX) | Sum of x coordinate to compute a center mass |
| [SumY](#SumY) | Sum of y coordinate to compute a center mass |
| [WhiteCount](#WhiteCount) | Count of white in the cell |
## Methods

| Method | Description |
| --- | --- |
| [accumulate(byte pixel, int x, int y)](#accumulate-byte-int-int-) | Adds the pixel to WhiteCount or BlackCount |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getX()](#getX--) | X-coordinate of the center |
| [getY()](#getY--) | Y-coordinate of the center |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setX(int value)](#setX-int-) | X-coordinate of the center |
| [setY(int value)](#setY-int-) | Y-coordinate of the center |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cell2D() {#Cell2D--}
```
public Cell2D()
```


### BlackCount {#BlackCount}
```
public int BlackCount
```


Count of black in the cell

### SumX {#SumX}
```
public int SumX
```


Sum of x coordinate to compute a center mass

### SumY {#SumY}
```
public int SumY
```


Sum of y coordinate to compute a center mass

### WhiteCount {#WhiteCount}
```
public int WhiteCount
```


Count of white in the cell

### accumulate(byte pixel, int x, int y) {#accumulate-byte-int-int-}
```
public void accumulate(byte pixel, int x, int y)
```


Adds the pixel to WhiteCount or BlackCount

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixel | byte | Color of a pixel |
| x | int | X-coordinate of pixel |
| y | int | Y-coordinate of pixel |

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
### getX() {#getX--}
```
public int getX()
```


X-coordinate of the center

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Y-coordinate of the center

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




### setX(int value) {#setX-int-}
```
public void setX(int value)
```


X-coordinate of the center

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Y-coordinate of the center

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

