---
title: PointBitmapFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.common.bitmaps/pointbitmapfunc/
---
**Inheritance:**
java.lang.Object
```
public class PointBitmapFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PointBitmapFunc()](#PointBitmapFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createCentralPointFsGrid(int aRows, int aCols, double aCellSize, double aCellShiftX, double aCellShiftY)](#createCentralPointFsGrid-int-int-double-double-double-) |  |
| [createCentralPointFsGrid(int aRows, int aCols, int aCellSize, int aCellShiftX, int aCellShiftY)](#createCentralPointFsGrid-int-int-int-int-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractBitmapFromPointBitmap(ByteBitmap aBitmap, PointFBitmap aPointBitmap, byte aDef)](#extractBitmapFromPointBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.PointFBitmap-byte-) |  |
| [extractBitmapFromPointBitmapBilinear(ByteBitmap aBitmap, PointFBitmap aPointBitmap, byte aDef)](#extractBitmapFromPointBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.PointFBitmap-byte-) |  |
| [getCentralPointFBitmapFromCellRegion(QuadPointFs aRegionQuad, int aRows, int aCols, double aCellSize, double aCellShiftX, double aCellShiftY)](#getCentralPointFBitmapFromCellRegion-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-int-int-double-double-double-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointBitmapFunc() {#PointBitmapFunc--}
```
public PointBitmapFunc()
```


### createCentralPointFsGrid(int aRows, int aCols, double aCellSize, double aCellShiftX, double aCellShiftY) {#createCentralPointFsGrid-int-int-double-double-double-}
```
public static PointFBitmap createCentralPointFsGrid(int aRows, int aCols, double aCellSize, double aCellShiftX, double aCellShiftY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRows | int |  |
| aCols | int |  |
| aCellSize | double |  |
| aCellShiftX | double |  |
| aCellShiftY | double |  |

**Returns:**
[PointFBitmap](../../com.aspose.barcode.common.bitmaps/pointfbitmap)
### createCentralPointFsGrid(int aRows, int aCols, int aCellSize, int aCellShiftX, int aCellShiftY) {#createCentralPointFsGrid-int-int-int-int-int-}
```
public static PointFBitmap createCentralPointFsGrid(int aRows, int aCols, int aCellSize, int aCellShiftX, int aCellShiftY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRows | int |  |
| aCols | int |  |
| aCellSize | int |  |
| aCellShiftX | int |  |
| aCellShiftY | int |  |

**Returns:**
[PointFBitmap](../../com.aspose.barcode.common.bitmaps/pointfbitmap)
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
### extractBitmapFromPointBitmap(ByteBitmap aBitmap, PointFBitmap aPointBitmap, byte aDef) {#extractBitmapFromPointBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.PointFBitmap-byte-}
```
public static ByteBitmap extractBitmapFromPointBitmap(ByteBitmap aBitmap, PointFBitmap aPointBitmap, byte aDef)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aPointBitmap | [PointFBitmap](../../com.aspose.barcode.common.bitmaps/pointfbitmap) |  |
| aDef | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### extractBitmapFromPointBitmapBilinear(ByteBitmap aBitmap, PointFBitmap aPointBitmap, byte aDef) {#extractBitmapFromPointBitmapBilinear-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.PointFBitmap-byte-}
```
public static ByteBitmap extractBitmapFromPointBitmapBilinear(ByteBitmap aBitmap, PointFBitmap aPointBitmap, byte aDef)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aPointBitmap | [PointFBitmap](../../com.aspose.barcode.common.bitmaps/pointfbitmap) |  |
| aDef | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getCentralPointFBitmapFromCellRegion(QuadPointFs aRegionQuad, int aRows, int aCols, double aCellSize, double aCellShiftX, double aCellShiftY) {#getCentralPointFBitmapFromCellRegion-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-int-int-double-double-double-}
```
public static PointFBitmap getCentralPointFBitmapFromCellRegion(QuadPointFs aRegionQuad, int aRows, int aCols, double aCellSize, double aCellShiftX, double aCellShiftY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegionQuad | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) |  |
| aRows | int |  |
| aCols | int |  |
| aCellSize | double |  |
| aCellShiftX | double |  |
| aCellShiftY | double |  |

**Returns:**
[PointFBitmap](../../com.aspose.barcode.common.bitmaps/pointfbitmap)
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

