---
title: CellDetectorSmallDoubleHamming
second_title: Aspose.BarCode for Java API Reference
description: This class detects cells of a datamatrix using the double hamming algorithm
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/celldetectorsmalldoublehamming/
---
**Inheritance:**
java.lang.Object
```
public class CellDetectorSmallDoubleHamming
```

This class detects cells of a datamatrix, using the double hamming algorithm
## Constructors

| Constructor | Description |
| --- | --- |
| [CellDetectorSmallDoubleHamming()](#CellDetectorSmallDoubleHamming--) |  |
## Methods

| Method | Description |
| --- | --- |
| [colsByDoubleHamming(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RegionalTransformation2D transf)](#colsByDoubleHamming-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-) | Calculates columns coordinates by hamming left and right |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hammingAlignedBitsSmallModule(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix)](#hammingAlignedBitsSmallModule-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-int-) | Creates bits matrix by hamming distances and clarifies. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rowsByDoubleHamming(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RegionalTransformation2D transf)](#rowsByDoubleHamming-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-) | Calculates rows coordinates by hamming above and below |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CellDetectorSmallDoubleHamming() {#CellDetectorSmallDoubleHamming--}
```
public CellDetectorSmallDoubleHamming()
```


### colsByDoubleHamming(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RegionalTransformation2D transf) {#colsByDoubleHamming-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-}
```
public static Int32List colsByDoubleHamming(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RegionalTransformation2D transf)
```


Calculates columns coordinates by hamming left and right

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| dimensionX | int | Dimension X |
| dimensionY | int | Dimension Y |
| transf | [RegionalTransformation2D](../../com.aspose.barcode.barcoderecognition.internal/regionaltransformation2d) | A transformation |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list) - Columns coordinates
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
### hammingAlignedBitsSmallModule(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix) {#hammingAlignedBitsSmallModule-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-int-}
```
public static BitArrayArray hammingAlignedBitsSmallModule(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix)
```


Creates bits matrix by hamming distances and clarifies. Works only for small module datamatrixes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Vertexes |
| dimensionX | int | Dimension X |
| dimensionY | int | Dimension Y |
| separatrix | int | A separatrix |

**Returns:**
[BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) - Bits
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




### rowsByDoubleHamming(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RegionalTransformation2D transf) {#rowsByDoubleHamming-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-}
```
public static Int32List rowsByDoubleHamming(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RegionalTransformation2D transf)
```


Calculates rows coordinates by hamming above and below

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| dimensionX | int | Dimension X |
| dimensionY | int | Dimension Y |
| transf | [RegionalTransformation2D](../../com.aspose.barcode.barcoderecognition.internal/regionaltransformation2d) | A transformation |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list) - Rows coordinates
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

