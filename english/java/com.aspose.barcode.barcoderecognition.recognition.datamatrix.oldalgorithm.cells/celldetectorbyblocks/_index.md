---
title: CellDetectorByBlocks
second_title: Aspose.BarCode for Java API Reference
description: This class detects cells of a datamatrix with big dimension 32 using all the time patterns of matrix blocks
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/celldetectorbyblocks/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm)
```
public class CellDetectorByBlocks implements IAlgorithm
```

This class detects cells of a datamatrix with big dimension (>=32), using all the time patterns of matrix blocks
## Constructors

| Constructor | Description |
| --- | --- |
| [CellDetectorByBlocks()](#CellDetectorByBlocks--) |  |
## Methods

| Method | Description |
| --- | --- |
| [correctImbalanceDistance(int minThreshold, int maxThreshold, int shift, Int32List[] itemList)](#correctImbalanceDistance-int-int-int-com.aspose.barcode.common.generic.list.Int32List---) | Search items with imbalance distance. |
| [detectSmallWithBlur(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, boolean simpleMethod)](#detectSmallWithBlur-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-int-boolean-) | Detects small matrix with blur, all the time patterns of matrix blocks. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(ModelHolder modelHolder)](#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Executes the algorithm of CellDetectorByBlocks |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CellDetectorByBlocks() {#CellDetectorByBlocks--}
```
public CellDetectorByBlocks()
```


### correctImbalanceDistance(int minThreshold, int maxThreshold, int shift, Int32List[] itemList) {#correctImbalanceDistance-int-int-int-com.aspose.barcode.common.generic.list.Int32List---}
```
public static void correctImbalanceDistance(int minThreshold, int maxThreshold, int shift, Int32List[] itemList)
```


Search items with imbalance distance. This distance is corrected.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| minThreshold | int | an available minimum distance |
| maxThreshold | int | an available maximum distance |
| shift | int | correction value |
| itemList | [Int32List\[\]](../../com.aspose.barcode.common.generic.list/int32list) | list of items |

### detectSmallWithBlur(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, boolean simpleMethod) {#detectSmallWithBlur-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-int-boolean-}
```
public static SpikedBits detectSmallWithBlur(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, int separatrix, boolean simpleMethod)
```


Detects small matrix with blur, all the time patterns of matrix blocks. Only for square matrixes and dimension >=32

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Vertexes of a matrix |
| dimensionX | int | Dimension x |
| dimensionY | int | Dimension y |
| separatrix | int | Separatrix |
| simpleMethod | boolean | True - detect color by 1 point for each cell. False - by 4 points |

**Returns:**
[SpikedBits](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/spikedbits) - Spiked bits
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


Executes the algorithm of CellDetectorByBlocks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modelHolder | [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) | model holder |

**Returns:**
boolean - 
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

