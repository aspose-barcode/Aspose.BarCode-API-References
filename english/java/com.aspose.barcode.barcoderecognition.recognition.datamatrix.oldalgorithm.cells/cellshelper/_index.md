---
title: CellsHelper
second_title: Aspose.BarCode for Java API Reference
description: Functions for cells posicioning and restoring small damage.
type: docs
weight: 16
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/cellshelper/
---
**Inheritance:**
java.lang.Object
```
public class CellsHelper
```

Functions for cells posicioning and restoring small damage.
## Constructors

| Constructor | Description |
| --- | --- |
| [CellsHelper()](#CellsHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [bitToBitmapPosition(RegionalTransformation2D transf, float x, float y, int[] x1, int[] y1)](#bitToBitmapPosition-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-float-float-int---int---) | Calculates a real position by use trensformation object (add "smart" round) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flipByOrder(int[] valueFrom, int[] valueTo)](#flipByOrder-int---int---) | Orders two values |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CellsHelper() {#CellsHelper--}
```
public CellsHelper()
```


### bitToBitmapPosition(RegionalTransformation2D transf, float x, float y, int[] x1, int[] y1) {#bitToBitmapPosition-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-float-float-int---int---}
```
public static void bitToBitmapPosition(RegionalTransformation2D transf, float x, float y, int[] x1, int[] y1)
```


Calculates a real position by use trensformation object (add "smart" round)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transf | [RegionalTransformation2D](../../com.aspose.barcode.barcoderecognition.internal/regionaltransformation2d) | trensformation object |
| x | float | input X-coordinate |
| y | float | input Y-coordinate |
| x1 | int[] | calculated X-coordinate |
| y1 | int[] | calculated Y-coordinate |

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
### flipByOrder(int[] valueFrom, int[] valueTo) {#flipByOrder-int---int---}
```
public static void flipByOrder(int[] valueFrom, int[] valueTo)
```


Orders two values

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| valueFrom | int[] | first value |
| valueTo | int[] | second value |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

