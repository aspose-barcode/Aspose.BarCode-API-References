---
title: DataMatrixLocator
second_title: Aspose.BarCode for Java API Reference
description: Functions for bits locating.
type: docs
weight: 17
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/datamatrixlocator/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixLocator
```

Functions for bits locating. Functions are consist of different combinations of dimension, time pattern, spikes algorithms.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataMatrixLocator()](#DataMatrixLocator--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [locateByAll(ByteBitmap byteBitmap, LocatorParams rules)](#locateByAll-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-) |  |
| [locateByContours(ByteBitmap byteBitmap, LocatorParams rules)](#locateByContours-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-) | Locates the bits by irregular cells. |
| [locateByHammingOrEqual(ByteBitmap byteBitmap, LocatorParams rules)](#locateByHammingOrEqual-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-) |  |
| [locateByModule(ByteBitmap byteBitmap, LocatorParams rules)](#locateByModule-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-) |  |
| [locateSmallMatrix(ByteBitmap cuttedBitmap, LocatorParams rules)](#locateSmallMatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-) | Locates small matrix (a bit array, vertexes and angle) |
| [locateSmallMatrixCorrect(ByteBitmap cuttedBitmap, LocatorParams rules)](#locateSmallMatrixCorrect-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-) | Locates small matrix (a bit array, vertexes and angle) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataMatrixLocator() {#DataMatrixLocator--}
```
public DataMatrixLocator()
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### locateByAll(ByteBitmap byteBitmap, LocatorParams rules) {#locateByAll-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-}
```
public static BitsLocation locateByAll(ByteBitmap byteBitmap, LocatorParams rules)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| rules | [LocatorParams](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params/locatorparams) |  |

**Returns:**
[BitsLocation](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/bitslocation)
### locateByContours(ByteBitmap byteBitmap, LocatorParams rules) {#locateByContours-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-}
```
public static BitsLocation locateByContours(ByteBitmap byteBitmap, LocatorParams rules)
```


Locates the bits by irregular cells. Uses the distance to black-white contours

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| rules | [LocatorParams](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params/locatorparams) | Rules |

**Returns:**
[BitsLocation](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/bitslocation) - Bits location
### locateByHammingOrEqual(ByteBitmap byteBitmap, LocatorParams rules) {#locateByHammingOrEqual-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-}
```
public static BitsLocation locateByHammingOrEqual(ByteBitmap byteBitmap, LocatorParams rules)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| rules | [LocatorParams](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params/locatorparams) |  |

**Returns:**
[BitsLocation](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/bitslocation)
### locateByModule(ByteBitmap byteBitmap, LocatorParams rules) {#locateByModule-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-}
```
public static BitsLocation locateByModule(ByteBitmap byteBitmap, LocatorParams rules)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| rules | [LocatorParams](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params/locatorparams) |  |

**Returns:**
[BitsLocation](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/bitslocation)
### locateSmallMatrix(ByteBitmap cuttedBitmap, LocatorParams rules) {#locateSmallMatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-}
```
public static BitsLocation locateSmallMatrix(ByteBitmap cuttedBitmap, LocatorParams rules)
```


Locates small matrix (a bit array, vertexes and angle)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cuttedBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | a cutted bitmap |
| rules | [LocatorParams](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params/locatorparams) | a rules |

**Returns:**
[BitsLocation](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/bitslocation) - 
### locateSmallMatrixCorrect(ByteBitmap cuttedBitmap, LocatorParams rules) {#locateSmallMatrixCorrect-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params.LocatorParams-}
```
public static BitsLocation locateSmallMatrixCorrect(ByteBitmap cuttedBitmap, LocatorParams rules)
```


Locates small matrix (a bit array, vertexes and angle)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cuttedBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | a cutted bitmap |
| rules | [LocatorParams](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.params/locatorparams) |  |

**Returns:**
[BitsLocation](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/bitslocation) - Bit location
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

