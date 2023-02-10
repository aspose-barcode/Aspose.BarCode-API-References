---
title: ZebraDimensionDetector
second_title: Aspose.BarCode for Java API Reference
description: Detector of the dimensions
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.timepatterns/zebradimensiondetector/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm)
```
public class ZebraDimensionDetector implements IAlgorithm
```

Detector of the dimensions
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraDimensionDetector()](#ZebraDimensionDetector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(ModelHolder modelHolder)](#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Searches dimensions |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [locateDimensions(ByteBitmap byteBitmap, RectangleVertexes vertexes, int pixelOffset2Try, float angle, int rectSeparatrix, int[] dimensionX, int[] dimensionY)](#locateDimensions-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-float-int-int---int---) | Calculate x- and y-dimensions |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraDimensionDetector() {#ZebraDimensionDetector--}
```
public ZebraDimensionDetector()
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
### execute(ModelHolder modelHolder) {#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-}
```
public final boolean execute(ModelHolder modelHolder)
```


Searches dimensions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modelHolder | [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) | Model holder |

**Returns:**
boolean - Is succesfully found dimensions
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
### locateDimensions(ByteBitmap byteBitmap, RectangleVertexes vertexes, int pixelOffset2Try, float angle, int rectSeparatrix, int[] dimensionX, int[] dimensionY) {#locateDimensions-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-float-int-int---int---}
```
public static void locateDimensions(ByteBitmap byteBitmap, RectangleVertexes vertexes, int pixelOffset2Try, float angle, int rectSeparatrix, int[] dimensionX, int[] dimensionY)
```


Calculate x- and y-dimensions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Vertexes of a rectangle |
| pixelOffset2Try | int | An offset |
| angle | float | Input angle |
| rectSeparatrix | int | A rectangle separatrix |
| dimensionX | int[] | X-dimension |
| dimensionY | int[] | Y-dimension |

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

