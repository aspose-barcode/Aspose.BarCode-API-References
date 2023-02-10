---
title: LsdCornerHelper
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/lsdcornerhelper/
---
**Inheritance:**
java.lang.Object
```
public class LsdCornerHelper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [LsdCornerHelper()](#LsdCornerHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createExpectedQuad(RectangleForLsd lineA, RectangleForLsd lineB)](#createExpectedQuad-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-) |  |
| [createQuad(RectangleForLsd lineA, RectangleForLsd lineB)](#createQuad-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [normilizeCornerPoint(RectangleForLsd[] lineA, RectangleForLsd[] lineB)](#normilizeCornerPoint-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd---com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd---) | Normilize corner point. |
| [normilizeOrderOfLines(RectangleForLsd[] lineA, RectangleForLsd[] lineB)](#normilizeOrderOfLines-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd---com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd---) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [shiftLine(RectangleForLsd lineA, RectangleForLsd lineB, double factor)](#shiftLine-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-double-) |  |
| [stretchLine(RectangleForLsd line, double factor)](#stretchLine-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-double-) | Stretch line by factor. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LsdCornerHelper() {#LsdCornerHelper--}
```
public LsdCornerHelper()
```


### createExpectedQuad(RectangleForLsd lineA, RectangleForLsd lineB) {#createExpectedQuad-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-}
```
public static QuadPointFs createExpectedQuad(RectangleForLsd lineA, RectangleForLsd lineB)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineA | [RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) |  |
| lineB | [RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) |  |

**Returns:**
[QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs)
### createQuad(RectangleForLsd lineA, RectangleForLsd lineB) {#createQuad-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-}
```
public static QuadPointFs createQuad(RectangleForLsd lineA, RectangleForLsd lineB)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineA | [RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) |  |
| lineB | [RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) |  |

**Returns:**
[QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs)
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
### normilizeCornerPoint(RectangleForLsd[] lineA, RectangleForLsd[] lineB) {#normilizeCornerPoint-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd---com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd---}
```
public static void normilizeCornerPoint(RectangleForLsd[] lineA, RectangleForLsd[] lineB)
```


Normilize corner point. Set corner point of second point in lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineA | [RectangleForLsd\[\]](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) | First line. |
| lineB | [RectangleForLsd\[\]](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) | Second line. |

### normilizeOrderOfLines(RectangleForLsd[] lineA, RectangleForLsd[] lineB) {#normilizeOrderOfLines-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd---com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd---}
```
public static void normilizeOrderOfLines(RectangleForLsd[] lineA, RectangleForLsd[] lineB)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineA | [RectangleForLsd\[\]](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) |  |
| lineB | [RectangleForLsd\[\]](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### shiftLine(RectangleForLsd lineA, RectangleForLsd lineB, double factor) {#shiftLine-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-double-}
```
public static RectangleForLsd shiftLine(RectangleForLsd lineA, RectangleForLsd lineB, double factor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineA | [RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) |  |
| lineB | [RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) |  |
| factor | double |  |

**Returns:**
[RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd)
### stretchLine(RectangleForLsd line, double factor) {#stretchLine-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd.RectangleForLsd-double-}
```
public static RectangleForLsd stretchLine(RectangleForLsd line, double factor)
```


Stretch line by factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | [RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) | Original line. |
| factor | double | Scale factor. |

**Returns:**
[RectangleForLsd](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.lsd/rectangleforlsd) - The stretched line.
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

