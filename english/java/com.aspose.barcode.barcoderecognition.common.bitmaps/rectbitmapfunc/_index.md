---
title: RectBitmapFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.common.bitmaps/rectbitmapfunc/
---
**Inheritance:**
java.lang.Object
```
public class RectBitmapFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RectBitmapFunc()](#RectBitmapFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createRectBitmap(int aRows, int aCols, double aCellWidth, double aCellHeight, System.Drawing.Size ImageSize)](#createRectBitmap-int-int-double-double-com.aspose.ms.System.Drawing.Size-) |  |
| [createRectBitmap(int aRows, int aCols, int CellSize, ByteBitmap aImage)](#createRectBitmap-int-int-int-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [createRectBitmapFromPointFBitmap(PointFBitmap aGrid, double aCellSize, System.Drawing.Size ImageSize)](#createRectBitmapFromPointFBitmap-com.aspose.barcode.common.bitmaps.PointFBitmap-double-com.aspose.ms.System.Drawing.Size-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAverageCellsColorFromBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder)](#extractAverageCellsColorFromBitmap-com.aspose.barcode.common.bitmaps.RectBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [extractBitMatrixFromBinarizedCellBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder)](#extractBitMatrixFromBinarizedCellBitmap-com.aspose.barcode.common.bitmaps.RectBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [extractBitMatrixFromBinarizedCellBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder, double aMinBlackDiffToMark)](#extractBitMatrixFromBinarizedCellBitmap-com.aspose.barcode.common.bitmaps.RectBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-) |  |
| [getAverageValueFromCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap)](#getAverageValueFromCell-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getBWValueFromCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap)](#getBWValueFromCell-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getBorderedAndFitCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap, int BorderSize)](#getBorderedAndFitCell-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectBitmapFunc() {#RectBitmapFunc--}
```
public RectBitmapFunc()
```


### createRectBitmap(int aRows, int aCols, double aCellWidth, double aCellHeight, System.Drawing.Size ImageSize) {#createRectBitmap-int-int-double-double-com.aspose.ms.System.Drawing.Size-}
```
public static RectBitmap createRectBitmap(int aRows, int aCols, double aCellWidth, double aCellHeight, System.Drawing.Size ImageSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRows | int |  |
| aCols | int |  |
| aCellWidth | double |  |
| aCellHeight | double |  |
| ImageSize | com.aspose.ms.System.Drawing.Size |  |

**Returns:**
[RectBitmap](../../com.aspose.barcode.common.bitmaps/rectbitmap)
### createRectBitmap(int aRows, int aCols, int CellSize, ByteBitmap aImage) {#createRectBitmap-int-int-int-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static RectBitmap createRectBitmap(int aRows, int aCols, int CellSize, ByteBitmap aImage)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRows | int |  |
| aCols | int |  |
| CellSize | int |  |
| aImage | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[RectBitmap](../../com.aspose.barcode.common.bitmaps/rectbitmap)
### createRectBitmapFromPointFBitmap(PointFBitmap aGrid, double aCellSize, System.Drawing.Size ImageSize) {#createRectBitmapFromPointFBitmap-com.aspose.barcode.common.bitmaps.PointFBitmap-double-com.aspose.ms.System.Drawing.Size-}
```
public static RectBitmap createRectBitmapFromPointFBitmap(PointFBitmap aGrid, double aCellSize, System.Drawing.Size ImageSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrid | [PointFBitmap](../../com.aspose.barcode.common.bitmaps/pointfbitmap) |  |
| aCellSize | double |  |
| ImageSize | com.aspose.ms.System.Drawing.Size |  |

**Returns:**
[RectBitmap](../../com.aspose.barcode.common.bitmaps/rectbitmap)
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
### extractAverageCellsColorFromBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder) {#extractAverageCellsColorFromBitmap-com.aspose.barcode.common.bitmaps.RectBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap extractAverageCellsColorFromBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRectBitmap | [RectBitmap](../../com.aspose.barcode.common.bitmaps/rectbitmap) |  |
| aDataBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aBorder | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### extractBitMatrixFromBinarizedCellBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder) {#extractBitMatrixFromBinarizedCellBitmap-com.aspose.barcode.common.bitmaps.RectBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap extractBitMatrixFromBinarizedCellBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRectBitmap | [RectBitmap](../../com.aspose.barcode.common.bitmaps/rectbitmap) |  |
| aDataBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aBorder | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### extractBitMatrixFromBinarizedCellBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder, double aMinBlackDiffToMark) {#extractBitMatrixFromBinarizedCellBitmap-com.aspose.barcode.common.bitmaps.RectBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-}
```
public static ByteBitmap extractBitMatrixFromBinarizedCellBitmap(RectBitmap aRectBitmap, ByteBitmap aDataBitmap, int aBorder, double aMinBlackDiffToMark)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRectBitmap | [RectBitmap](../../com.aspose.barcode.common.bitmaps/rectbitmap) |  |
| aDataBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aBorder | int |  |
| aMinBlackDiffToMark | double |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getAverageValueFromCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap) {#getAverageValueFromCell-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static float getAverageValueFromCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aCell | com.aspose.ms.System.Drawing.Rectangle |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
float
### getBWValueFromCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap) {#getBWValueFromCell-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static Tup<Integer,Integer> getBWValueFromCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aCell | com.aspose.ms.System.Drawing.Rectangle |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup)
### getBorderedAndFitCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap, int BorderSize) {#getBorderedAndFitCell-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static System.Drawing.Rectangle getBorderedAndFitCell(System.Drawing.Rectangle aCell, ByteBitmap aBitmap, int BorderSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aCell | com.aspose.ms.System.Drawing.Rectangle |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| BorderSize | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Rectangle
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

