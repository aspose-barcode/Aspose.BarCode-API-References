---
title: ZebraScanGeometry
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 26
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebrascangeometry/
---
**Inheritance:**
java.lang.Object
```
public class ZebraScanGeometry
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraScanGeometry()](#ZebraScanGeometry--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDiagonal3Pi4Lines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize)](#getDiagonal3Pi4Lines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-) | create 3Pi4 scan lines list from aRect and fit them to aBitmap size |
| [getDiagonalPi4Lines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize)](#getDiagonalPi4Lines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-) | create Pi4 scan lines list from aRect and fit them to aBitmap size |
| [getHorizontalLines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize)](#getHorizontalLines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-) | create horizontal scan lines list from aRect and fit them to aBitmap size |
| [getQuadLines(QuadPoints aQuad, int GapSize)](#getQuadLines-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-) | create quadrangle scan lines list from start to stop edge |
| [getReverseLines(List<DoublePoints> aList)](#getReverseLines-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--) | Mirrors scan lines and replaces start and end points |
| [getReverseQuad(QuadPoints aQuad)](#getReverseQuad-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-) | create quadrangle with mirrored direction, where start edge begen end edge |
| [getScanRectangleLines(ByteBitmap aBitmap, ScanRectangle aRect)](#getScanRectangleLines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.scanrect.ScanRectangle-) | Create scan lines list from ScanRectangle and fit them to aBitmap size |
| [getVerticalLines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize)](#getVerticalLines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-) | create vertical scan lines list from aRect and fit them to aBitmap size |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraScanGeometry() {#ZebraScanGeometry--}
```
public ZebraScanGeometry()
```


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
### getDiagonal3Pi4Lines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize) {#getDiagonal3Pi4Lines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-}
```
public static List<DoublePoints> getDiagonal3Pi4Lines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize)
```


create 3Pi4 scan lines list from aRect and fit them to aBitmap size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | processing bitmap |
| aRect | com.aspose.ms.System.Drawing.Rectangle | rectangle |
| GapSize | int | gap between scans, 1 no gap |

**Returns:**
[List](../../java.util/list) - scan lines list
### getDiagonalPi4Lines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize) {#getDiagonalPi4Lines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-}
```
public static List<DoublePoints> getDiagonalPi4Lines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize)
```


create Pi4 scan lines list from aRect and fit them to aBitmap size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | processing bitmap |
| aRect | com.aspose.ms.System.Drawing.Rectangle | rectangle |
| GapSize | int | gap between scans, 1 no gap |

**Returns:**
[List](../../java.util/list) - scan lines list
### getHorizontalLines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize) {#getHorizontalLines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-}
```
public static List<DoublePoints> getHorizontalLines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize)
```


create horizontal scan lines list from aRect and fit them to aBitmap size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | processing bitmap |
| aRect | com.aspose.ms.System.Drawing.Rectangle | rectangle |
| GapSize | int | gap between scans, 1 no gap |

**Returns:**
[List](../../java.util/list) - scan lines list
### getQuadLines(QuadPoints aQuad, int GapSize) {#getQuadLines-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-}
```
public static List<DoublePoints> getQuadLines(QuadPoints aQuad, int GapSize)
```


create quadrangle scan lines list from start to stop edge

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | quadrangle |
| GapSize | int | gap between scans, 1 no gap |

**Returns:**
[List](../../java.util/list) - scan lines list
### getReverseLines(List<DoublePoints> aList) {#getReverseLines-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--}
```
public static List<DoublePoints> getReverseLines(List<DoublePoints> aList)
```


Mirrors scan lines and replaces start and end points

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints> | original list |

**Returns:**
[List](../../java.util/list) - mirrored list
### getReverseQuad(QuadPoints aQuad) {#getReverseQuad-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-}
```
public static QuadPoints getReverseQuad(QuadPoints aQuad)
```


create quadrangle with mirrored direction, where start edge begen end edge

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | original quadrangle |

**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) - mirrored qaudrangle
### getScanRectangleLines(ByteBitmap aBitmap, ScanRectangle aRect) {#getScanRectangleLines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.scanrect.ScanRectangle-}
```
public static List<DoublePoints> getScanRectangleLines(ByteBitmap aBitmap, ScanRectangle aRect)
```


Create scan lines list from ScanRectangle and fit them to aBitmap size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | processing bitmap |
| aRect | [ScanRectangle](../../com.aspose.barcode.barcoderecognition.common.algorithms.scanrect/scanrectangle) | rectangle with scan direction |

**Returns:**
[List](../../java.util/list) - scan lines list
### getVerticalLines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize) {#getVerticalLines-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-}
```
public static List<DoublePoints> getVerticalLines(ByteBitmap aBitmap, System.Drawing.Rectangle aRect, int GapSize)
```


create vertical scan lines list from aRect and fit them to aBitmap size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | processing bitmap |
| aRect | com.aspose.ms.System.Drawing.Rectangle | rectangle |
| GapSize | int | gap between scans, 1 no gap |

**Returns:**
[List](../../java.util/list) - scan lines list
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

