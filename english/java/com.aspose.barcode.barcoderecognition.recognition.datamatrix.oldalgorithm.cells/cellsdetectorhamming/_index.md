---
title: CellsDetectorHamming
second_title: Aspose.BarCode for Java API Reference
description: This class detects cells of a datamatrix using hamming differences between rows and columns
type: docs
weight: 15
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/cellsdetectorhamming/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm)
```
public class CellsDetectorHamming implements IAlgorithm
```

This class detects cells of a datamatrix, using hamming differences between rows and columns
## Constructors

| Constructor | Description |
| --- | --- |
| [CellsDetectorHamming()](#CellsDetectorHamming--) |  |
## Methods

| Method | Description |
| --- | --- |
| [alignedSpikes(ByteBitmap byteBitmap, int fromCoordinate, int toCoordinate, int start, int length, int halfModule, int module, boolean isHorisontal, int expectedCount, float blur)](#alignedSpikes-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-int-int-boolean-int-float-) | The positioning of cells in a line from start to end coordinate |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(ModelHolder modelHolder)](#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Executes cells detecting by hamming algorithm |
| [getClass()](#getClass--) |  |
| [hammingAlignedBits(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, float blur)](#hammingAlignedBits-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-int-float-) | Initialize bits for barcode with hamming posicioning algorthm (from 2px module) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CellsDetectorHamming() {#CellsDetectorHamming--}
```
public CellsDetectorHamming()
```


### alignedSpikes(ByteBitmap byteBitmap, int fromCoordinate, int toCoordinate, int start, int length, int halfModule, int module, boolean isHorisontal, int expectedCount, float blur) {#alignedSpikes-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-int-int-boolean-int-float-}
```
public static Int32List alignedSpikes(ByteBitmap byteBitmap, int fromCoordinate, int toCoordinate, int start, int length, int halfModule, int module, boolean isHorisontal, int expectedCount, float blur)
```


The positioning of cells in a line from start to end coordinate

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| fromCoordinate | int | Start coordinate |
| toCoordinate | int | End coordinate |
| start | int | Row or column number |
| length | int |  |
| halfModule | int | half module |
| module | int | A module. Better to take module rounded to the lower side |
| isHorisontal | boolean | Is line horizontal |
| expectedCount | int | an expected count of spikes |
| blur | float |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list) - Centres of cells
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


Executes cells detecting by hamming algorithm

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
### hammingAlignedBits(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, float blur) {#hammingAlignedBits-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-int-float-}
```
public static BitArrayArray hammingAlignedBits(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, float blur)
```


Initialize bits for barcode with hamming posicioning algorthm (from 2px module)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Vertexts of a barcode rectangle |
| dimensionX | int | Dimension X |
| dimensionY | int | Dimension Y |
| separatrix | int | Separatrix |
| blur | float | Blur |

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

