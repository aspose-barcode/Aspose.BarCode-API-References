---
title: CellDetectorEqualNet
second_title: Aspose.BarCode for Java API Reference
description: This class detects cells of a datamatrix using the dividng to equal parts.
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/celldetectorequalnet/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm)
```
public class CellDetectorEqualNet implements IAlgorithm
```

This class detects cells of a datamatrix, using the dividng to equal parts.
## Constructors

| Constructor | Description |
| --- | --- |
| [CellDetectorEqualNet()](#CellDetectorEqualNet--) |  |
## Methods

| Method | Description |
| --- | --- |
| [detectEqualRowsAndColumns(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RectangleVertexes vertexes, Int32List[] rows, Int32List[] col)](#detectEqualRowsAndColumns-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-com.aspose.barcode.common.generic.list.Int32List---com.aspose.barcode.common.generic.list.Int32List---) | Executes cells detecting by dividng a region to equal parts. |
| [detectEqualSpikes(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RectangleVertexes vertexes)](#detectEqualSpikes-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-) | Executes cells detecting by dividng a region to equal parts. |
| [equalDistributionBits(ByteBitmap byteBitmap, int dimensionX, int dimensionY, int separatrix, RectangleVertexes vertexes)](#equalDistributionBits-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-) | Creates bits matrix by dividing bytebitmap to equal parts and getting cells. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(ModelHolder modelHolder)](#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Executes cells detecting by dividng a region to equal parts. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CellDetectorEqualNet() {#CellDetectorEqualNet--}
```
public CellDetectorEqualNet()
```


### detectEqualRowsAndColumns(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RectangleVertexes vertexes, Int32List[] rows, Int32List[] col) {#detectEqualRowsAndColumns-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-com.aspose.barcode.common.generic.list.Int32List---com.aspose.barcode.common.generic.list.Int32List---}
```
public static void detectEqualRowsAndColumns(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RectangleVertexes vertexes, Int32List[] rows, Int32List[] col)
```


Executes cells detecting by dividng a region to equal parts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| dimensionX | int | Dimension X |
| dimensionY | int | Dimension Y |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Vertexes |
| rows | [Int32List\[\]](../../com.aspose.barcode.common.generic.list/int32list) | result rows |
| col | [Int32List\[\]](../../com.aspose.barcode.common.generic.list/int32list) | result columns |

### detectEqualSpikes(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RectangleVertexes vertexes) {#detectEqualSpikes-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-}
```
public static SpikedBits detectEqualSpikes(ByteBitmap byteBitmap, int dimensionX, int dimensionY, RectangleVertexes vertexes)
```


Executes cells detecting by dividng a region to equal parts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| dimensionX | int | Dimension X |
| dimensionY | int | Dimension Y |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | vertexes |

**Returns:**
[SpikedBits](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/spikedbits) - spiked bits
### equalDistributionBits(ByteBitmap byteBitmap, int dimensionX, int dimensionY, int separatrix, RectangleVertexes vertexes) {#equalDistributionBits-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-}
```
public static BitArrayArray equalDistributionBits(ByteBitmap byteBitmap, int dimensionX, int dimensionY, int separatrix, RectangleVertexes vertexes)
```


Creates bits matrix by dividing bytebitmap to equal parts and getting cells.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| dimensionX | int | Dimension X |
| dimensionY | int | Dimension Y |
| separatrix | int | A separatrix |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Vertexes |

**Returns:**
[BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) - Bits.
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
### execute(ModelHolder modelHolder) {#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-}
```
public final boolean execute(ModelHolder modelHolder)
```


Executes cells detecting by dividng a region to equal parts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modelHolder | [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) | Model holder |

**Returns:**
boolean - True if found cells, else false
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

