---
title: BBFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.common.bitmaps/bbfunc/
---
**Inheritance:**
java.lang.Object
```
public class BBFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BBFunc()](#BBFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [calcSeparatrix(ByteBitmap bitmap)](#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [calcSeparatrix(ByteBitmap bitmap, RectangleVertexes vertexes)](#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-) |  |
| [calcSeparatrix(ByteBitmap bitmap, System.Drawing.Point pointStart, System.Drawing.Point pointEnd)](#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [calcSeparatrix(ByteBitmap bitmap, System.Drawing.Point startPoint, int endX, int endY)](#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-int-int-) |  |
| [calcSeparatrix(ByteBitmap bitmap, System.Drawing.Rectangle rectangle)](#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [calcSeparatrix(ByteBitmap bitmap, int startX, int startY, System.Drawing.Point endPoint)](#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.ms.System.Drawing.Point-) |  |
| [calcSeparatrix(ByteBitmap bitmap, int startX, int startY, int endX, int endY)](#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-) |  |
| [calculateBlackPercent(ByteBitmap bitmap, List<System.Drawing.Point> line, byte separatrix)](#calculateBlackPercent-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--byte-) | Claculates a black percent in the line(list of points). |
| [calculateBlackPercent(ByteBitmap bitmap, List<System.Drawing.Point> line, int offsetCount, boolean flip, int sign, int separatrix)](#calculateBlackPercent-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--int-boolean-int-int-) | Calculate black percent at the expected offset zone. |
| [contains(ByteBitmap bitmap, System.Drawing.Point p)](#contains-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-) |  |
| [contains(ByteBitmap bitmap, int x, int y)](#contains-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllPoints(ByteBitmap bitmap, System.Drawing.Point start, System.Drawing.Point end)](#getAllPoints-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [getClass()](#getClass--) |  |
| [getContrast(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint)](#getContrast-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [getPixelFlip(ByteBitmap bitmap, int x, int y, boolean flip)](#getPixelFlip-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-boolean-) |  |
| [getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint)](#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint, int separatrix)](#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-int-) | Get zebra between start and end points using Bresenham line algorithm |
| [getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, int endX, int endY)](#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-int-int-) |  |
| [getZebra(ByteBitmap bitmap, int startX, int startY, System.Drawing.Point endPoint)](#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.ms.System.Drawing.Point-) |  |
| [getZebra(ByteBitmap bitmap, int startX, int startY, int endX, int endY)](#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-) |  |
| [getZebraWithRemove1pxNoise(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint)](#getZebraWithRemove1pxNoise-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Get Zebra from bitmap between startPoint and endPoint with removing little noise. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointValidation(ByteBitmap bitmap, System.Drawing.Point a)](#pointValidation-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [widthOrHeight(ByteBitmap bitmap, boolean flip)](#widthOrHeight-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-) | Size of bitmap (Width or Height) |
### BBFunc() {#BBFunc--}
```
public BBFunc()
```


### calcSeparatrix(ByteBitmap bitmap) {#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte calcSeparatrix(ByteBitmap bitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte
### calcSeparatrix(ByteBitmap bitmap, RectangleVertexes vertexes) {#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-}
```
public static byte calcSeparatrix(ByteBitmap bitmap, RectangleVertexes vertexes)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) |  |

**Returns:**
byte
### calcSeparatrix(ByteBitmap bitmap, System.Drawing.Point pointStart, System.Drawing.Point pointEnd) {#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static byte calcSeparatrix(ByteBitmap bitmap, System.Drawing.Point pointStart, System.Drawing.Point pointEnd)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| pointStart | com.aspose.ms.System.Drawing.Point |  |
| pointEnd | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
byte
### calcSeparatrix(ByteBitmap bitmap, System.Drawing.Point startPoint, int endX, int endY) {#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-int-int-}
```
public static byte calcSeparatrix(ByteBitmap bitmap, System.Drawing.Point startPoint, int endX, int endY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startPoint | com.aspose.ms.System.Drawing.Point |  |
| endX | int |  |
| endY | int |  |

**Returns:**
byte
### calcSeparatrix(ByteBitmap bitmap, System.Drawing.Rectangle rectangle) {#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-}
```
public static byte calcSeparatrix(ByteBitmap bitmap, System.Drawing.Rectangle rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

**Returns:**
byte
### calcSeparatrix(ByteBitmap bitmap, int startX, int startY, System.Drawing.Point endPoint) {#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.ms.System.Drawing.Point-}
```
public static byte calcSeparatrix(ByteBitmap bitmap, int startX, int startY, System.Drawing.Point endPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startX | int |  |
| startY | int |  |
| endPoint | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
byte
### calcSeparatrix(ByteBitmap bitmap, int startX, int startY, int endX, int endY) {#calcSeparatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-}
```
public static byte calcSeparatrix(ByteBitmap bitmap, int startX, int startY, int endX, int endY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startX | int |  |
| startY | int |  |
| endX | int |  |
| endY | int |  |

**Returns:**
byte
### calculateBlackPercent(ByteBitmap bitmap, List<System.Drawing.Point> line, byte separatrix) {#calculateBlackPercent-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--byte-}
```
public static float calculateBlackPercent(ByteBitmap bitmap, List<System.Drawing.Point> line, byte separatrix)
```


Claculates a black percent in the line(list of points).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| line | java.util.List<com.aspose.ms.System.Drawing.Point> | A list of points |
| separatrix | byte | A separatrix |

**Returns:**
float - Percent of black points. Float from 0 to 1
### calculateBlackPercent(ByteBitmap bitmap, List<System.Drawing.Point> line, int offsetCount, boolean flip, int sign, int separatrix) {#calculateBlackPercent-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--int-boolean-int-int-}
```
public static float calculateBlackPercent(ByteBitmap bitmap, List<System.Drawing.Point> line, int offsetCount, boolean flip, int sign, int separatrix)
```


Calculate black percent at the expected offset zone. If flip is true, consider line vertical (and add offset horizontal)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| line | java.util.List<com.aspose.ms.System.Drawing.Point> | A line |
| offsetCount | int | Offset count |
| flip | boolean | true - vertical line, false - horizontal line |
| sign | int | Direction to offset |
| separatrix | int | A separatrix |

**Returns:**
float - Black percent
### contains(ByteBitmap bitmap, System.Drawing.Point p) {#contains-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-}
```
public static boolean contains(ByteBitmap bitmap, System.Drawing.Point p)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| p | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
boolean
### contains(ByteBitmap bitmap, int x, int y) {#contains-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-}
```
public static boolean contains(ByteBitmap bitmap, int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| x | int |  |
| y | int |  |

**Returns:**
boolean
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
### getAllPoints(ByteBitmap bitmap, System.Drawing.Point start, System.Drawing.Point end) {#getAllPoints-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static List<System.Drawing.Point> getAllPoints(ByteBitmap bitmap, System.Drawing.Point start, System.Drawing.Point end)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| start | com.aspose.ms.System.Drawing.Point |  |
| end | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
[List](../../java.util/list)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint) {#getContrast-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static byte[] getContrast(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startPoint | com.aspose.ms.System.Drawing.Point |  |
| endPoint | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
byte[]
### getPixelFlip(ByteBitmap bitmap, int x, int y, boolean flip) {#getPixelFlip-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-boolean-}
```
public static byte getPixelFlip(ByteBitmap bitmap, int x, int y, boolean flip)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| x | int |  |
| y | int |  |
| flip | boolean |  |

**Returns:**
byte
### getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint) {#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static Int32List getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startPoint | com.aspose.ms.System.Drawing.Point |  |
| endPoint | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
### getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint, int separatrix) {#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-int-}
```
public static Int32List getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint, int separatrix)
```


Get zebra between start and end points using Bresenham line algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startPoint | com.aspose.ms.System.Drawing.Point | Start point |
| endPoint | com.aspose.ms.System.Drawing.Point | End point |
| separatrix | int | A separatrix |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list) - A zebra
### getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, int endX, int endY) {#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-int-int-}
```
public static Int32List getZebra(ByteBitmap bitmap, System.Drawing.Point startPoint, int endX, int endY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startPoint | com.aspose.ms.System.Drawing.Point |  |
| endX | int |  |
| endY | int |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
### getZebra(ByteBitmap bitmap, int startX, int startY, System.Drawing.Point endPoint) {#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.ms.System.Drawing.Point-}
```
public static Int32List getZebra(ByteBitmap bitmap, int startX, int startY, System.Drawing.Point endPoint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startX | int |  |
| startY | int |  |
| endPoint | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
### getZebra(ByteBitmap bitmap, int startX, int startY, int endX, int endY) {#getZebra-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-}
```
public static Int32List getZebra(ByteBitmap bitmap, int startX, int startY, int endX, int endY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startX | int |  |
| startY | int |  |
| endX | int |  |
| endY | int |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
### getZebraWithRemove1pxNoise(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint) {#getZebraWithRemove1pxNoise-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static Int32List getZebraWithRemove1pxNoise(ByteBitmap bitmap, System.Drawing.Point startPoint, System.Drawing.Point endPoint)
```


Get Zebra from bitmap between startPoint and endPoint with removing little noise.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| startPoint | com.aspose.ms.System.Drawing.Point | The start point for zebra. |
| endPoint | com.aspose.ms.System.Drawing.Point | The end point for zebra. |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list) - The zebra.
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




### pointValidation(ByteBitmap bitmap, System.Drawing.Point a) {#pointValidation-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-}
```
public static System.Drawing.Point pointValidation(ByteBitmap bitmap, System.Drawing.Point a)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| a | com.aspose.ms.System.Drawing.Point |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
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

### widthOrHeight(ByteBitmap bitmap, boolean flip) {#widthOrHeight-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-}
```
public static int widthOrHeight(ByteBitmap bitmap, boolean flip)
```


Size of bitmap (Width or Height)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| flip | boolean | false is width; true is height |

**Returns:**
int - 
