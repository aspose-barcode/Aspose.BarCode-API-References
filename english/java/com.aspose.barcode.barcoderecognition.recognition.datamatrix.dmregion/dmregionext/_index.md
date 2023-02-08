---
title: DMRegionExt
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext/
---
**Inheritance:**
java.lang.Object
```
public class DMRegionExt
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DMRegionExt(LPatternData aLPattern)](#DMRegionExt-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-) |  |
| [DMRegionExt(DMRegionExt aRegion)](#DMRegionExt-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-) |  |
## Fields

| Field | Description |
| --- | --- |
| [BottomLine](#BottomLine) |  |
| [BottomPoint](#BottomPoint) |  |
| [CellHeight](#CellHeight) |  |
| [CellWidth](#CellWidth) |  |
| [CornerPoint](#CornerPoint) |  |
| [Histogramm](#Histogramm) |  |
| [LeftLine](#LeftLine) |  |
| [LeftPoint](#LeftPoint) |  |
| [OppositeCornerPoint](#OppositeCornerPoint) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getRegionHistogramm(ByteBitmap aBitmap, boolean Refresh)](#getRegionHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-) |  |
| [getRegionQuad()](#getRegionQuad--) |  |
| [getRegionQuadF()](#getRegionQuadF--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DMRegionExt(LPatternData aLPattern) {#DMRegionExt-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-}
```
public DMRegionExt(LPatternData aLPattern)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLPattern | [LPatternData](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/lpatterndata) |  |

### DMRegionExt(DMRegionExt aRegion) {#DMRegionExt-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-}
```
public DMRegionExt(DMRegionExt aRegion)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |

### BottomLine {#BottomLine}
```
public ExtractedLineF BottomLine
```


### BottomPoint {#BottomPoint}
```
public System.Drawing.PointF BottomPoint
```


### CellHeight {#CellHeight}
```
public double CellHeight
```


### CellWidth {#CellWidth}
```
public double CellWidth
```


### CornerPoint {#CornerPoint}
```
public System.Drawing.PointF CornerPoint
```


### Histogramm {#Histogramm}
```
public int[] Histogramm
```


### LeftLine {#LeftLine}
```
public ExtractedLineF LeftLine
```


### LeftPoint {#LeftPoint}
```
public System.Drawing.PointF LeftPoint
```


### OppositeCornerPoint {#OppositeCornerPoint}
```
public System.Drawing.PointF OppositeCornerPoint
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
### getRegionHistogramm(ByteBitmap aBitmap, boolean Refresh) {#getRegionHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-}
```
public final int[] getRegionHistogramm(ByteBitmap aBitmap, boolean Refresh)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| Refresh | boolean |  |

**Returns:**
int[]
### getRegionQuad() {#getRegionQuad--}
```
public final QuadPoints getRegionQuad()
```




**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints)
### getRegionQuadF() {#getRegionQuadF--}
```
public final QuadPointFs getRegionQuadF()
```




**Returns:**
[QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs)
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

