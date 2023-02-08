---
title: pdf417DataImageHelper
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataimagehelper/
---
**Inheritance:**
java.lang.Object
```
public class pdf417DataImageHelper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417DataImageHelper()](#pdf417DataImageHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [checkIsPossibleToExtractQuadAsRect(QuadPoints aQuad, double aMaxDistance)](#checkIsPossibleToExtractQuadAsRect-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-double-) | Checks possiblity to extract bitmap as quad |
| [checkQuadToRectanglePointsMaxDistance(QuadPoints aQuad, System.Drawing.Rectangle aRect)](#checkQuadToRectanglePointsMaxDistance-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.ms.System.Drawing.Rectangle-) | Detects max distance from quadrangle point to matching rectangle point |
| [clearWhiteRows(ByteBitmap aBitmap, float aCell17Width)](#clearWhiteRows-com.aspose.barcode.common.bitmaps.ByteBitmap-float-) | Extracts dataregion bitmap with wiped upper and lower white rows |
| [clearWhiteRows(ByteBitmap aBitmap, float aCell17Width, int aMinIgnoredBlackPix, float aMinIgnoredBlackFilling)](#clearWhiteRows-com.aspose.barcode.common.bitmaps.ByteBitmap-float-int-float-) | Extracts dataregion bitmap with wiped upper and lower white rows |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractBitmapFromQuadAsRect(ByteBitmap aBitmap, QuadPoints aQuad)](#extractBitmapFromQuadAsRect-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-) | Extracts dataregion bitmap as rectangle with size close to aQuad |
| [fitCell17MinimalWidth(pdf417DataRegion aRegion, boolean isBilinear)](#fitCell17MinimalWidth-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-) | Increases dataregion bitmap with resized params |
| [fitCell17MinimalWidth(pdf417DataRegion aRegion, boolean isBilinear, double aMinCellSize)](#fitCell17MinimalWidth-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-double-) | Increases dataregion bitmap with resized params |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resizeDataRegion(pdf417DataRegion aRegion, boolean isBilinear, double aWidthIncrease, double aHeightIncrease)](#resizeDataRegion-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-double-double-) | Increases dataregion bitmap with resized params |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417DataImageHelper() {#pdf417DataImageHelper--}
```
public pdf417DataImageHelper()
```


### checkIsPossibleToExtractQuadAsRect(QuadPoints aQuad, double aMaxDistance) {#checkIsPossibleToExtractQuadAsRect-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-double-}
```
public static boolean checkIsPossibleToExtractQuadAsRect(QuadPoints aQuad, double aMaxDistance)
```


Checks possiblity to extract bitmap as quad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | bounding quadrangle |
| aMaxDistance | double | max distance from rectangle points to aQuad points |

**Returns:**
boolean - possiblity to extract bitmap as quad
### checkQuadToRectanglePointsMaxDistance(QuadPoints aQuad, System.Drawing.Rectangle aRect) {#checkQuadToRectanglePointsMaxDistance-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.ms.System.Drawing.Rectangle-}
```
public static double checkQuadToRectanglePointsMaxDistance(QuadPoints aQuad, System.Drawing.Rectangle aRect)
```


Detects max distance from quadrangle point to matching rectangle point

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | bounding quadrangle |
| aRect | com.aspose.ms.System.Drawing.Rectangle | checking rectangle |

**Returns:**
double - max distance from quadrangle point to matching rectangle point
### clearWhiteRows(ByteBitmap aBitmap, float aCell17Width) {#clearWhiteRows-com.aspose.barcode.common.bitmaps.ByteBitmap-float-}
```
public static ByteBitmap clearWhiteRows(ByteBitmap aBitmap, float aCell17Width)
```


Extracts dataregion bitmap with wiped upper and lower white rows

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | dataregion bitmap |
| aCell17Width | float | possible width of column (17 cells size) |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - dataregion bitmap with wiped upper and lower white rows
### clearWhiteRows(ByteBitmap aBitmap, float aCell17Width, int aMinIgnoredBlackPix, float aMinIgnoredBlackFilling) {#clearWhiteRows-com.aspose.barcode.common.bitmaps.ByteBitmap-float-int-float-}
```
public static ByteBitmap clearWhiteRows(ByteBitmap aBitmap, float aCell17Width, int aMinIgnoredBlackPix, float aMinIgnoredBlackFilling)
```


Extracts dataregion bitmap with wiped upper and lower white rows

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | dataregion bitmap |
| aCell17Width | float | possible width of column (17 cells size) |
| aMinIgnoredBlackPix | int | ignored black pixels in row, means fully white row |
| aMinIgnoredBlackFilling | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - dataregion bitmap with wiped upper and lower white rows
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
### extractBitmapFromQuadAsRect(ByteBitmap aBitmap, QuadPoints aQuad) {#extractBitmapFromQuadAsRect-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-}
```
public static ByteBitmap extractBitmapFromQuadAsRect(ByteBitmap aBitmap, QuadPoints aQuad)
```


Extracts dataregion bitmap as rectangle with size close to aQuad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | dataregion |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | bounding quadrangle |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - dataregion bitmap
### fitCell17MinimalWidth(pdf417DataRegion aRegion, boolean isBilinear) {#fitCell17MinimalWidth-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-}
```
public static pdf417DataRegion fitCell17MinimalWidth(pdf417DataRegion aRegion, boolean isBilinear)
```


Increases dataregion bitmap with resized params

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) |  |
| isBilinear | boolean | bilenear or nearest neighbour interpolation |

**Returns:**
[pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) - increased dataregion bitmap with resized params
### fitCell17MinimalWidth(pdf417DataRegion aRegion, boolean isBilinear, double aMinCellSize) {#fitCell17MinimalWidth-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-double-}
```
public static pdf417DataRegion fitCell17MinimalWidth(pdf417DataRegion aRegion, boolean isBilinear, double aMinCellSize)
```


Increases dataregion bitmap with resized params

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) |  |
| isBilinear | boolean | bilenear or nearest neighbour interpolation |
| aMinCellSize | double | minimal cell size which doesnt need icreasing |

**Returns:**
[pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) - increased dataregion bitmap with resized params
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




### resizeDataRegion(pdf417DataRegion aRegion, boolean isBilinear, double aWidthIncrease, double aHeightIncrease) {#resizeDataRegion-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-double-double-}
```
public static pdf417DataRegion resizeDataRegion(pdf417DataRegion aRegion, boolean isBilinear, double aWidthIncrease, double aHeightIncrease)
```


Increases dataregion bitmap with resized params

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) |  |
| isBilinear | boolean | bilenear or nearest neighbour interpolation |
| aWidthIncrease | double | increase multiplier by width |
| aHeightIncrease | double | increase multiplier by height |

**Returns:**
[pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) - increased dataregion bitmap with resized params
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

