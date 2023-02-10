---
title: LineExtender
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 24
url: /java/com.aspose.barcode.barcoderecognition.internal/lineextender/
---
**Inheritance:**
java.lang.Object
```
public class LineExtender
```
## Constructors

| Constructor | Description |
| --- | --- |
| [LineExtender()](#LineExtender--) |  |
## Methods

| Method | Description |
| --- | --- |
| [distance(System.Drawing.Point point1, System.Drawing.Point point2)](#distance-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [distancePow(System.Drawing.Point point1, System.Drawing.Point point2)](#distancePow-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extendX(System.Drawing.Point startPoint, int step, ByteBitmap byteBitmap, int separatrix)](#extendX-com.aspose.ms.System.Drawing.Point-int-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [extendY(System.Drawing.Point startPoint, int step, ByteBitmap byteBitmap, int separatrix)](#extendY-com.aspose.ms.System.Drawing.Point-int-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [extendYWithOneShift(System.Drawing.Point startPoint, int shiftByX, int step, ByteBitmap byteBitmap, int separatrix)](#extendYWithOneShift-com.aspose.ms.System.Drawing.Point-int-int-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isValidExtended(System.Drawing.Point point, boolean value, ByteBitmap byteBitmap, int separatrix)](#isValidExtended-com.aspose.ms.System.Drawing.Point-boolean-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LineExtender() {#LineExtender--}
```
public LineExtender()
```


### distance(System.Drawing.Point point1, System.Drawing.Point point2) {#distance-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static double distance(System.Drawing.Point point1, System.Drawing.Point point2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | com.aspose.ms.System.Drawing.Point |  |
| point2 | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
double
### distancePow(System.Drawing.Point point1, System.Drawing.Point point2) {#distancePow-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static int distancePow(System.Drawing.Point point1, System.Drawing.Point point2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | com.aspose.ms.System.Drawing.Point |  |
| point2 | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
int
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
### extendX(System.Drawing.Point startPoint, int step, ByteBitmap byteBitmap, int separatrix) {#extendX-com.aspose.ms.System.Drawing.Point-int-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static System.Drawing.Point extendX(System.Drawing.Point startPoint, int step, ByteBitmap byteBitmap, int separatrix)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPoint | com.aspose.ms.System.Drawing.Point |  |
| step | int |  |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| separatrix | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### extendY(System.Drawing.Point startPoint, int step, ByteBitmap byteBitmap, int separatrix) {#extendY-com.aspose.ms.System.Drawing.Point-int-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static System.Drawing.Point extendY(System.Drawing.Point startPoint, int step, ByteBitmap byteBitmap, int separatrix)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPoint | com.aspose.ms.System.Drawing.Point |  |
| step | int |  |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| separatrix | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### extendYWithOneShift(System.Drawing.Point startPoint, int shiftByX, int step, ByteBitmap byteBitmap, int separatrix) {#extendYWithOneShift-com.aspose.ms.System.Drawing.Point-int-int-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static System.Drawing.Point extendYWithOneShift(System.Drawing.Point startPoint, int shiftByX, int step, ByteBitmap byteBitmap, int separatrix)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPoint | com.aspose.ms.System.Drawing.Point |  |
| shiftByX | int |  |
| step | int |  |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| separatrix | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
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
### isValidExtended(System.Drawing.Point point, boolean value, ByteBitmap byteBitmap, int separatrix) {#isValidExtended-com.aspose.ms.System.Drawing.Point-boolean-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static boolean isValidExtended(System.Drawing.Point point, boolean value, ByteBitmap byteBitmap, int separatrix)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | com.aspose.ms.System.Drawing.Point |  |
| value | boolean |  |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| separatrix | int |  |

**Returns:**
boolean
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

