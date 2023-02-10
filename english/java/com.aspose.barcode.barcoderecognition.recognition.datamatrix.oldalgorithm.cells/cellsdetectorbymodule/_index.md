---
title: CellsDetectorByModule
second_title: Aspose.BarCode for Java API Reference
description: This class detects cells of a datamatrix using a module to search and correct the time pattern
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/cellsdetectorbymodule/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm)
```
public class CellsDetectorByModule implements IAlgorithm
```

This class detects cells of a datamatrix, using a module to search and correct the time pattern
## Constructors

| Constructor | Description |
| --- | --- |
| [CellsDetectorByModule()](#CellsDetectorByModule--) | Initializes a new instance of the [CellsDetectorByModule](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/cellsdetectorbymodule) class. |
| [CellsDetectorByModule(boolean isNeedCorrect)](#CellsDetectorByModule-boolean-) | Initializes a new instance of the [CellsDetectorByModule](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/cellsdetectorbymodule) class. |
## Methods

| Method | Description |
| --- | --- |
| [alignedBitsByModule(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, boolean isNeedCorrect)](#alignedBitsByModule-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-boolean-) | Detect datamatrix grid using the time-pattern |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(ModelHolder modelHolder)](#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Detects cells using a module value |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CellsDetectorByModule() {#CellsDetectorByModule--}
```
public CellsDetectorByModule()
```


Initializes a new instance of the [CellsDetectorByModule](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/cellsdetectorbymodule) class.

### CellsDetectorByModule(boolean isNeedCorrect) {#CellsDetectorByModule-boolean-}
```
public CellsDetectorByModule(boolean isNeedCorrect)
```


Initializes a new instance of the [CellsDetectorByModule](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/cellsdetectorbymodule) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isNeedCorrect | boolean | Is needed to use double haming correction |

### alignedBitsByModule(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, boolean isNeedCorrect) {#alignedBitsByModule-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-boolean-}
```
public static SpikedBits alignedBitsByModule(ByteBitmap byteBitmap, RectangleVertexes vertexes, int dimensionX, int dimensionY, boolean isNeedCorrect)
```


Detect datamatrix grid using the time-pattern

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input datamatrix |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Vertexes of a rectangle |
| dimensionX | int |  |
| dimensionY | int |  |
| isNeedCorrect | boolean |  |

**Returns:**
[SpikedBits](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/spikedbits) - Matrix of bits
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


Detects cells using a module value

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

