---
title: HistogramItem
second_title: Aspose.BarCode for Java API Reference
description: A histogram item column
type: docs
weight: 26
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/histogramitem/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class HistogramItem extends Struct<HistogramItem>
```

A histogram item (column)
## Constructors

| Constructor | Description |
| --- | --- |
| [HistogramItem()](#HistogramItem--) |  |
## Fields

| Field | Description |
| --- | --- |
| [IsDoubtfulSkew](#IsDoubtfulSkew) | Is doubtful skew |
| [Number](#Number) | A histogram column number |
| [Skew](#Skew) | Backward skew: the difference between the previous and the current value. |
| [Value](#Value) | Value of darkness. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(HistogramItem that)](#CloneTo-com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem-) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HistogramItem() {#HistogramItem--}
```
public HistogramItem()
```


### IsDoubtfulSkew {#IsDoubtfulSkew}
```
public boolean IsDoubtfulSkew
```


Is doubtful skew

### Number {#Number}
```
public int Number
```


A histogram column number

### Skew {#Skew}
```
public int Skew
```


Backward skew: the difference between the previous and the current value.

### Value {#Value}
```
public int Value
```


Value of darkness. Sum of (255-color)

### Clone() {#Clone--}
```
public HistogramItem Clone()
```




**Returns:**
[HistogramItem](../../com.aspose.barcode.barcoderecognition.common.algorithms/histogramitem)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(HistogramItem that) {#CloneTo-com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem-}
```
public void CloneTo(HistogramItem that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [HistogramItem](../../com.aspose.barcode.barcoderecognition.common.algorithms/histogramitem) |  |

### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

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

