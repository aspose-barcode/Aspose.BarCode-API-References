---
title: MatrixFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 38
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/matrixfunc/
---
**Inheritance:**
java.lang.Object
```
public class MatrixFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MatrixFunc()](#MatrixFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [convertByteBitmapToFloatBitmap(ByteBitmap aBmp)](#convertByteBitmapToFloatBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [convertByteBitmapToShortBitmap(ByteBitmap aBmp)](#convertByteBitmapToShortBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [convertFloatBitmapToByteBitmap(FloatBitmap aBmp)](#convertFloatBitmapToByteBitmap-com.aspose.barcode.common.bitmaps.FloatBitmap-) |  |
| [convertShortBitmapToByteBitmap(ShortBitmap aBmp)](#convertShortBitmapToByteBitmap-com.aspose.barcode.common.bitmaps.ShortBitmap-) |  |
| [cut(ByteBitmap bitmap, System.Drawing.Rectangle aRect)](#cut-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [cut(ByteBitmap bitmap, System.Drawing.Rectangle rectangle, int orientation)](#cut-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-) | Fast cuts and rotate the bitmap by a rectangle and the orientation |
| [cut(FloatBitmap bitmap, System.Drawing.Rectangle aRect)](#cut-com.aspose.barcode.common.bitmaps.FloatBitmap-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [decreaseBitmapOriginal(ByteBitmap aBmp, int aZoom)](#decreaseBitmapOriginal-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [decreaseBitmapSelection(ByteBitmap aBmp, int aZoom)](#decreaseBitmapSelection-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) | Decreases bitmap. |
| [decreaseBitmapSelectionCross(ByteBitmap aBmp, int aZoom)](#decreaseBitmapSelectionCross-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) | Decreases bitmap. |
| [decreaseBitmapSelectionMedian(ByteBitmap aBmp, int aZoom)](#decreaseBitmapSelectionMedian-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) | Decreases bitmap. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extendBitmap(ByteBitmap aBmp, int aSide)](#extendBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [extendBitmap(ByteBitmap aBmp, int aSide, byte DefaultColor)](#extendBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-byte-) |  |
| [fitRectangleSizeToArea(System.Drawing.Rectangle aRect, int aMaxWidth, int aMaxHeight)](#fitRectangleSizeToArea-com.aspose.ms.System.Drawing.Rectangle-int-int-) |  |
| [fitRectangleSizeToBitmap(ByteBitmap aBitmap, System.Drawing.Rectangle aRect)](#fitRectangleSizeToBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [fitReducedSize(int aSize, int ClSide)](#fitReducedSize-int-int-) |  |
| [fitToHeight(ByteBitmap byteBitmap, int aVal)](#fitToHeight-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [fitToWidth(ByteBitmap byteBitmap, int aVal)](#fitToWidth-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [increaseByNearestNeighbour(ByteBitmap byteBitmap, int zoom)](#increaseByNearestNeighbour-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) | Increases the bytebitmap by nearest neighbour algorithm |
| [inverseByteBitmapColors(ByteBitmap aBitmap)](#inverseByteBitmapColors-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [locateWhiteZone(ByteBitmap byteBitmap, int fromI, int toI, int start, int stop, int sign, boolean flip, int whiteThreshold)](#locateWhiteZone-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-int-boolean-int-) | Locate white zone |
| [makeBitmapBlur(ByteBitmap aBmp, int HalfWindow)](#makeBitmapBlur-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [makeBitmapBlurLight(ByteBitmap bitmap)](#makeBitmapBlurLight-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Make lighting blur bitmap. |
| [mirrorBitmapHoriz(ByteBitmap aBmp)](#mirrorBitmapHoriz-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Mirror Bitmap horizontally |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [putBitmap(ByteBitmap SrcBitmap, ByteBitmap DstBitmap, int XShift, int YShift)](#putBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-) |  |
| [putBitmap(FloatBitmap SrcBitmap, FloatBitmap DstBitmap, int XShift, int YShift)](#putBitmap-com.aspose.barcode.common.bitmaps.FloatBitmap-com.aspose.barcode.common.bitmaps.FloatBitmap-int-int-) |  |
| [reduceBitmap(ByteBitmap aBmp, int aSide)](#reduceBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [regrowsBinarized(ByteBitmap aBmp, int aBlackCnt)](#regrowsBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [rotate180(ByteBitmap aBmp)](#rotate180-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [rotate90ClockWise(ByteBitmap aBmp)](#rotate90ClockWise-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [rotate90CounterClockWise(ByteBitmap aBmp)](#rotate90CounterClockWise-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [rotateImage(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise)](#rotateImage-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.ms.System.Drawing.PointF-double-byte-boolean-) |  |
| [rotateImage(ByteBitmap aBitmap, double aAngle, byte aBackground, boolean aClockwise)](#rotateImage-com.aspose.barcode.common.bitmaps.ByteBitmap-double-byte-boolean-) |  |
| [rotateImageBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aResultPoint, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise)](#rotateImageBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double-byte-boolean-) |  |
| [rotateImageBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise)](#rotateImageBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.ms.System.Drawing.PointF-double-byte-boolean-) |  |
| [selectAverageBy5Pts(ByteBitmap byteBitmap, int x1, int y1)](#selectAverageBy5Pts-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-) | Get a average from 5 points: (x1,y1) and 4 pts around |
| [selectBlackBitmapFromBinarized(ByteBitmap aBmp)](#selectBlackBitmapFromBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [selectMedianAround(ByteBitmap byteBitmap, int x1, int y1)](#selectMedianAround-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-) | Get a median from 5 points: (x1,y1) and 4 pts around |
| [sumLine(ByteBitmap byteBitmap, int start, int stop, int i, boolean flip)](#sumLine-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-boolean-) | Sum line. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MatrixFunc() {#MatrixFunc--}
```
public MatrixFunc()
```


### convertByteBitmapToFloatBitmap(ByteBitmap aBmp) {#convertByteBitmapToFloatBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static FloatBitmap convertByteBitmapToFloatBitmap(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap)
### convertByteBitmapToShortBitmap(ByteBitmap aBmp) {#convertByteBitmapToShortBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ShortBitmap convertByteBitmapToShortBitmap(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ShortBitmap](../../com.aspose.barcode.common.bitmaps/shortbitmap)
### convertFloatBitmapToByteBitmap(FloatBitmap aBmp) {#convertFloatBitmapToByteBitmap-com.aspose.barcode.common.bitmaps.FloatBitmap-}
```
public static ByteBitmap convertFloatBitmapToByteBitmap(FloatBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### convertShortBitmapToByteBitmap(ShortBitmap aBmp) {#convertShortBitmapToByteBitmap-com.aspose.barcode.common.bitmaps.ShortBitmap-}
```
public static ByteBitmap convertShortBitmapToByteBitmap(ShortBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ShortBitmap](../../com.aspose.barcode.common.bitmaps/shortbitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### cut(ByteBitmap bitmap, System.Drawing.Rectangle aRect) {#cut-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-}
```
public static ByteBitmap cut(ByteBitmap bitmap, System.Drawing.Rectangle aRect)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aRect | com.aspose.ms.System.Drawing.Rectangle |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### cut(ByteBitmap bitmap, System.Drawing.Rectangle rectangle, int orientation) {#cut-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-int-}
```
public static ByteBitmap cut(ByteBitmap bitmap, System.Drawing.Rectangle rectangle, int orientation)
```


Fast cuts and rotate the bitmap by a rectangle and the orientation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bitmap |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | A rectangle |
| orientation | int | An orientation |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - The cutted and rotated bytebitmap
### cut(FloatBitmap bitmap, System.Drawing.Rectangle aRect) {#cut-com.aspose.barcode.common.bitmaps.FloatBitmap-com.aspose.ms.System.Drawing.Rectangle-}
```
public static FloatBitmap cut(FloatBitmap bitmap, System.Drawing.Rectangle aRect)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap) |  |
| aRect | com.aspose.ms.System.Drawing.Rectangle |  |

**Returns:**
[FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap)
### decreaseBitmapOriginal(ByteBitmap aBmp, int aZoom) {#decreaseBitmapOriginal-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap decreaseBitmapOriginal(ByteBitmap aBmp, int aZoom)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aZoom | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### decreaseBitmapSelection(ByteBitmap aBmp, int aZoom) {#decreaseBitmapSelection-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap decreaseBitmapSelection(ByteBitmap aBmp, int aZoom)
```


Decreases bitmap. This algorithm select an one point (very fast) o x x x x x x x x x x x x x x x x x x x x x x x x

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | input bitmap |
| aZoom | int | zoom |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - decreased bitmap
### decreaseBitmapSelectionCross(ByteBitmap aBmp, int aZoom) {#decreaseBitmapSelectionCross-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap decreaseBitmapSelectionCross(ByteBitmap aBmp, int aZoom)
```


Decreases bitmap. This algorithm calculate average color by the cross(not tested, archived) o o o o o o x x x x o x x x x o x x x x o x x x x

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | input bitmap |
| aZoom | int | zoom |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - decreased bitmap
### decreaseBitmapSelectionMedian(ByteBitmap aBmp, int aZoom) {#decreaseBitmapSelectionMedian-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap decreaseBitmapSelectionMedian(ByteBitmap aBmp, int aZoom)
```


Decreases bitmap. This algorithm calculate average color by median(archived)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | input bitmap |
| aZoom | int | zoom |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - decreased bitmap
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
### extendBitmap(ByteBitmap aBmp, int aSide) {#extendBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap extendBitmap(ByteBitmap aBmp, int aSide)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aSide | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### extendBitmap(ByteBitmap aBmp, int aSide, byte DefaultColor) {#extendBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-byte-}
```
public static ByteBitmap extendBitmap(ByteBitmap aBmp, int aSide, byte DefaultColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aSide | int |  |
| DefaultColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### fitRectangleSizeToArea(System.Drawing.Rectangle aRect, int aMaxWidth, int aMaxHeight) {#fitRectangleSizeToArea-com.aspose.ms.System.Drawing.Rectangle-int-int-}
```
public static System.Drawing.Rectangle fitRectangleSizeToArea(System.Drawing.Rectangle aRect, int aMaxWidth, int aMaxHeight)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRect | com.aspose.ms.System.Drawing.Rectangle |  |
| aMaxWidth | int |  |
| aMaxHeight | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Rectangle
### fitRectangleSizeToBitmap(ByteBitmap aBitmap, System.Drawing.Rectangle aRect) {#fitRectangleSizeToBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-}
```
public static System.Drawing.Rectangle fitRectangleSizeToBitmap(ByteBitmap aBitmap, System.Drawing.Rectangle aRect)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aRect | com.aspose.ms.System.Drawing.Rectangle |  |

**Returns:**
com.aspose.ms.System.Drawing.Rectangle
### fitReducedSize(int aSize, int ClSide) {#fitReducedSize-int-int-}
```
public static int fitReducedSize(int aSize, int ClSide)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSize | int |  |
| ClSide | int |  |

**Returns:**
int
### fitToHeight(ByteBitmap byteBitmap, int aVal) {#fitToHeight-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static int fitToHeight(ByteBitmap byteBitmap, int aVal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aVal | int |  |

**Returns:**
int
### fitToWidth(ByteBitmap byteBitmap, int aVal) {#fitToWidth-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static int fitToWidth(ByteBitmap byteBitmap, int aVal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aVal | int |  |

**Returns:**
int
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
### increaseByNearestNeighbour(ByteBitmap byteBitmap, int zoom) {#increaseByNearestNeighbour-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap increaseByNearestNeighbour(ByteBitmap byteBitmap, int zoom)
```


Increases the bytebitmap by nearest neighbour algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| zoom | int | A zoom |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - Increased bytebitmap
### inverseByteBitmapColors(ByteBitmap aBitmap) {#inverseByteBitmapColors-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap inverseByteBitmapColors(ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### locateWhiteZone(ByteBitmap byteBitmap, int fromI, int toI, int start, int stop, int sign, boolean flip, int whiteThreshold) {#locateWhiteZone-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-int-boolean-int-}
```
public static List<Integer> locateWhiteZone(ByteBitmap byteBitmap, int fromI, int toI, int start, int stop, int sign, boolean flip, int whiteThreshold)
```


Locate white zone

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| fromI | int | first coordinate start |
| toI | int | first coordinate end |
| start | int | second coordinate start |
| stop | int | second coordinate stop |
| sign | int | direction of first coordinate |
| flip | boolean | True - research vertical lines (1st coordinate y, 2nd - x). False - research horizontal lines (1st coordinate x, 2nd - y) |
| whiteThreshold | int |  |

**Returns:**
[List](../../java.util/list) - Quiet zones possible starts
### makeBitmapBlur(ByteBitmap aBmp, int HalfWindow) {#makeBitmapBlur-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap makeBitmapBlur(ByteBitmap aBmp, int HalfWindow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| HalfWindow | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### makeBitmapBlurLight(ByteBitmap bitmap) {#makeBitmapBlurLight-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap makeBitmapBlurLight(ByteBitmap bitmap)
```


Make lighting blur bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - 
### mirrorBitmapHoriz(ByteBitmap aBmp) {#mirrorBitmapHoriz-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap mirrorBitmapHoriz(ByteBitmap aBmp)
```


Mirror Bitmap horizontally

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - Mirrored bitmap horizontally
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### putBitmap(ByteBitmap SrcBitmap, ByteBitmap DstBitmap, int XShift, int YShift) {#putBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-}
```
public static void putBitmap(ByteBitmap SrcBitmap, ByteBitmap DstBitmap, int XShift, int YShift)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SrcBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| DstBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| XShift | int |  |
| YShift | int |  |

### putBitmap(FloatBitmap SrcBitmap, FloatBitmap DstBitmap, int XShift, int YShift) {#putBitmap-com.aspose.barcode.common.bitmaps.FloatBitmap-com.aspose.barcode.common.bitmaps.FloatBitmap-int-int-}
```
public static void putBitmap(FloatBitmap SrcBitmap, FloatBitmap DstBitmap, int XShift, int YShift)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SrcBitmap | [FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap) |  |
| DstBitmap | [FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap) |  |
| XShift | int |  |
| YShift | int |  |

### reduceBitmap(ByteBitmap aBmp, int aSide) {#reduceBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap reduceBitmap(ByteBitmap aBmp, int aSide)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aSide | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### regrowsBinarized(ByteBitmap aBmp, int aBlackCnt) {#regrowsBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap regrowsBinarized(ByteBitmap aBmp, int aBlackCnt)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aBlackCnt | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### rotate180(ByteBitmap aBmp) {#rotate180-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap rotate180(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### rotate90ClockWise(ByteBitmap aBmp) {#rotate90ClockWise-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap rotate90ClockWise(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### rotate90CounterClockWise(ByteBitmap aBmp) {#rotate90CounterClockWise-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap rotate90CounterClockWise(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### rotateImage(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise) {#rotateImage-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.ms.System.Drawing.PointF-double-byte-boolean-}
```
public static ByteBitmap rotateImage(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size |  |
| aStartPoint | com.aspose.ms.System.Drawing.PointF |  |
| aAngle | double |  |
| aBackground | byte |  |
| aClockwise | boolean |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### rotateImage(ByteBitmap aBitmap, double aAngle, byte aBackground, boolean aClockwise) {#rotateImage-com.aspose.barcode.common.bitmaps.ByteBitmap-double-byte-boolean-}
```
public static ByteBitmap rotateImage(ByteBitmap aBitmap, double aAngle, byte aBackground, boolean aClockwise)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aAngle | double |  |
| aBackground | byte |  |
| aClockwise | boolean |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### rotateImageBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aResultPoint, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise) {#rotateImageBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double-byte-boolean-}
```
public static ByteBitmap rotateImageBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aResultPoint, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size |  |
| aResultPoint | com.aspose.ms.System.Drawing.PointF |  |
| aStartPoint | com.aspose.ms.System.Drawing.PointF |  |
| aAngle | double |  |
| aBackground | byte |  |
| aClockwise | boolean |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### rotateImageBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise) {#rotateImageBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-com.aspose.ms.System.Drawing.PointF-double-byte-boolean-}
```
public static ByteBitmap rotateImageBilinear(ByteBitmap aBitmap, System.Drawing.Size aResultBmpSize, System.Drawing.PointF aStartPoint, double aAngle, byte aBackground, boolean aClockwise)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aResultBmpSize | com.aspose.ms.System.Drawing.Size |  |
| aStartPoint | com.aspose.ms.System.Drawing.PointF |  |
| aAngle | double |  |
| aBackground | byte |  |
| aClockwise | boolean |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### selectAverageBy5Pts(ByteBitmap byteBitmap, int x1, int y1) {#selectAverageBy5Pts-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-}
```
public static byte selectAverageBy5Pts(ByteBitmap byteBitmap, int x1, int y1)
```


Get a average from 5 points: (x1,y1) and 4 pts around

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| x1 | int | X-coordinate of central point |
| y1 | int | y-coordinate of central point |

**Returns:**
byte - A median
### selectBlackBitmapFromBinarized(ByteBitmap aBmp) {#selectBlackBitmapFromBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap selectBlackBitmapFromBinarized(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### selectMedianAround(ByteBitmap byteBitmap, int x1, int y1) {#selectMedianAround-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-}
```
public static byte selectMedianAround(ByteBitmap byteBitmap, int x1, int y1)
```


Get a median from 5 points: (x1,y1) and 4 pts around

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| x1 | int | X-coordinate of central point |
| y1 | int | y-coordinate of central point |

**Returns:**
byte - A median
### sumLine(ByteBitmap byteBitmap, int start, int stop, int i, boolean flip) {#sumLine-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-boolean-}
```
public static float sumLine(ByteBitmap byteBitmap, int start, int stop, int i, boolean flip)
```


Sum line. Only horizontal or vertical

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| start | int | Start second coordinate |
| stop | int | Stop second coordinate |
| i | int | First coordinate |
| flip | boolean | True - vertical line, false - horizontal line |

**Returns:**
float - Sum of line pixels
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

