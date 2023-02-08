---
title: MatrixDeformation
second_title: Aspose.BarCode for Java API Reference
description: Functions for the matrix deformations
type: docs
weight: 37
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/matrixdeformation/
---
**Inheritance:**
java.lang.Object
```
public class MatrixDeformation
```

Functions for the matrix deformations
## Constructors

| Constructor | Description |
| --- | --- |
| [MatrixDeformation()](#MatrixDeformation--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fitBitmap(ByteBitmap byteBitmap, RectangleVertexes vertexes, int extend, int orientation, RectangleVertexes[] globalExactVertexes, RectangleVertexes[] localVertexes)](#fitBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes---com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes---) | Fits bitmap and correct vertexes. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MatrixDeformation() {#MatrixDeformation--}
```
public MatrixDeformation()
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
### fitBitmap(ByteBitmap byteBitmap, RectangleVertexes vertexes, int extend, int orientation, RectangleVertexes[] globalExactVertexes, RectangleVertexes[] localVertexes) {#fitBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-int-int-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes---com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes---}
```
public static ByteBitmap fitBitmap(ByteBitmap byteBitmap, RectangleVertexes vertexes, int extend, int orientation, RectangleVertexes[] globalExactVertexes, RectangleVertexes[] localVertexes)
```


Fits bitmap and correct vertexes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte Bitmap |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Global rough vertexes (rectagle) |
| extend | int | extend value |
| orientation | int | An orientation |
| globalExactVertexes | [RectangleVertexes\[\]](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Returns exact global vertexes |
| localVertexes | [RectangleVertexes\[\]](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Returns local vertexes |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - fitted bitmap
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

