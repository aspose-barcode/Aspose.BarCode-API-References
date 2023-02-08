---
title: BitsLocation
second_title: Aspose.BarCode for Java API Reference
description: Data of bits matrix location for barcode region
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.cells2d/bitslocation/
---
**Inheritance:**
java.lang.Object
```
public class BitsLocation
```

Data of bit's matrix location for barcode region
## Constructors

| Constructor | Description |
| --- | --- |
| [BitsLocation()](#BitsLocation--) | Initializes a new instance of the  BitsLocation  class. |
| [BitsLocation(BitArrayArray bits, System.Drawing.Point[] endpoints, float angle)](#BitsLocation-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.ms.System.Drawing.Point---float-) | Initializes a new instance of the  BitsLocation  class. |
| [BitsLocation(BitArrayArray bits, RectangleVertexes vertexes, float angle)](#BitsLocation-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-float-) | Initializes a new instance of the  BitsLocation  class. |
## Fields

| Field | Description |
| --- | --- |
| [Angle](#Angle) | Angel of barcode region. |
| [Bits](#Bits) | Bits matrix for barcode region. |
| [EndPoints](#EndPoints) | Lacation of barcode region. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BitsLocation() {#BitsLocation--}
```
public BitsLocation()
```


Initializes a new instance of the  BitsLocation  class.

### BitsLocation(BitArrayArray bits, System.Drawing.Point[] endpoints, float angle) {#BitsLocation-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.ms.System.Drawing.Point---float-}
```
public BitsLocation(BitArrayArray bits, System.Drawing.Point[] endpoints, float angle)
```


Initializes a new instance of the  BitsLocation  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bits | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) | Bits matrix. |
| endpoints | com.aspose.ms.System.Drawing.Point[] | Lacation of barcode region. |
| angle | float | Angel of barcode region. |

### BitsLocation(BitArrayArray bits, RectangleVertexes vertexes, float angle) {#BitsLocation-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-float-}
```
public BitsLocation(BitArrayArray bits, RectangleVertexes vertexes, float angle)
```


Initializes a new instance of the  BitsLocation  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bits | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) | Bit matrix |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | vertexes in the whole bitmap |
| angle | float | angle |

### Angle {#Angle}
```
public float Angle
```


Angel of barcode region.

### Bits {#Bits}
```
public BitArrayArray Bits
```


Bits matrix for barcode region. It is transposed.

### EndPoints {#EndPoints}
```
public System.Drawing.Point[] EndPoints
```


Lacation of barcode region.

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

