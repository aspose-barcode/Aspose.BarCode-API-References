---
title: CellsDetectorByPart
second_title: Aspose.BarCode for Java API Reference
description: This class detects cells of a datamatrix using dividing the big matrix into parts and hamming positioning into that parts.
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/cellsdetectorbypart/
---
**Inheritance:**
java.lang.Object
```
public class CellsDetectorByPart
```

This class detects cells of a datamatrix, using dividing the big matrix into parts, and hamming positioning into that parts.
## Constructors

| Constructor | Description |
| --- | --- |
| [CellsDetectorByPart()](#CellsDetectorByPart--) |  |
## Methods

| Method | Description |
| --- | --- |
| [alignedBitsByParts(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, RegionalTransformation2D transf, float blur)](#alignedBitsByParts-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-int-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-float-) | Initialize bits for 2d barcode with hamming positioning algorithm |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CellsDetectorByPart() {#CellsDetectorByPart--}
```
public CellsDetectorByPart()
```


### alignedBitsByParts(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, RegionalTransformation2D transf, float blur) {#alignedBitsByParts-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-int-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-float-}
```
public static BitArrayArray alignedBitsByParts(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, RegionalTransformation2D transf, float blur)
```


Initialize bits for 2d barcode with hamming positioning algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Vertexts of a barcode rectangle |
| dimensionX | int |  |
| dimensionY | int |  |
| separatrix | int |  |
| transf | [RegionalTransformation2D](../../com.aspose.barcode.barcoderecognition.internal/regionaltransformation2d) | A transformation |
| blur | float |  |

**Returns:**
[BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) - Bits
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

