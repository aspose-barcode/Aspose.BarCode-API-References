---
title: ZebraUnion
second_title: Aspose.BarCode for Java API Reference
description: union of recognized zebra patternssegments on the image
type: docs
weight: 29
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.common.algorithms.IQuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/iquadpoints), [com.aspose.barcode.barcoderecognition.common.areatrees.ICentralPoint](../../com.aspose.barcode.barcoderecognition.common.areatrees/icentralpoint)
```
public class ZebraUnion implements IQuadPoints, ICentralPoint
```

union of recognized zebra patterns(segments) on the image
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraUnion()](#ZebraUnion--) |  |
| [ZebraUnion(SingleDecodeType aReadType, int aValue)](#ZebraUnion-com.aspose.barcode.barcoderecognition.SingleDecodeType-int-) |  |
| [ZebraUnion(ZebraUnion aUnion)](#ZebraUnion-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-) |  |
## Fields

| Field | Description |
| --- | --- |
| [AvgLength](#AvgLength) |  |
| [CentralPoint](#CentralPoint) |  |
| [DetectedAngle](#DetectedAngle) |  |
| [Quad](#Quad) |  |
| [Quality](#Quality) |  |
| [ReadType](#ReadType) |  |
| [Segments](#Segments) |  |
| [Value](#Value) |  |
| [ZebraPixSize](#ZebraPixSize) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCentralPoint()](#getCentralPoint--) |  |
| [getClass()](#getClass--) |  |
| [getQuadPoints()](#getQuadPoints--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraUnion() {#ZebraUnion--}
```
public ZebraUnion()
```


### ZebraUnion(SingleDecodeType aReadType, int aValue) {#ZebraUnion-com.aspose.barcode.barcoderecognition.SingleDecodeType-int-}
```
public ZebraUnion(SingleDecodeType aReadType, int aValue)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aReadType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |
| aValue | int |  |

### ZebraUnion(ZebraUnion aUnion) {#ZebraUnion-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-}
```
public ZebraUnion(ZebraUnion aUnion)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) |  |

### AvgLength {#AvgLength}
```
public float AvgLength
```


### CentralPoint {#CentralPoint}
```
public System.Drawing.Point CentralPoint
```


### DetectedAngle {#DetectedAngle}
```
public double DetectedAngle
```


### Quad {#Quad}
```
public QuadPoints Quad
```


### Quality {#Quality}
```
public float Quality
```


### ReadType {#ReadType}
```
public SingleDecodeType ReadType
```


### Segments {#Segments}
```
public List<ZebraSegment> Segments
```


### Value {#Value}
```
public int Value
```


### ZebraPixSize {#ZebraPixSize}
```
public float ZebraPixSize
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
### getCentralPoint() {#getCentralPoint--}
```
public System.Drawing.Point getCentralPoint()
```




**Returns:**
com.aspose.ms.System.Drawing.Point
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQuadPoints() {#getQuadPoints--}
```
public QuadPoints getQuadPoints()
```




**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints)
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

