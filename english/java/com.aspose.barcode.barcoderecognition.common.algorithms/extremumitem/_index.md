---
title: ExtremumItem
second_title: Aspose.BarCode for Java API Reference
description: Extremum item extends the histogram info to work with a columns range
type: docs
weight: 22
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/extremumitem/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class ExtremumItem extends Struct<ExtremumItem>
```

Extremum item extends the histogram info to work with a columns range
## Constructors

| Constructor | Description |
| --- | --- |
| [ExtremumItem()](#ExtremumItem--) |  |
| [ExtremumItem(HistogramItem histogramItem, int histogramItemType)](#ExtremumItem-com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem-int-) | Initialize a new instance of the  ExtremumItem  class. |
## Fields

| Field | Description |
| --- | --- |
| [IsComplex](#IsComplex) | Is complex extremum |
| [Module](#Module) | A module |
| [ModuleBySkew](#ModuleBySkew) | Module calculated using skew |
| [NumberFrom](#NumberFrom) | A start of extremum column |
| [NumberTo](#NumberTo) | An end of of extremum column |
| [PointType](#PointType) | A type of a point (extremum, regular, complex) |
| [Value](#Value) | Value of darkness. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(ExtremumItem that)](#CloneTo-com.aspose.barcode.barcoderecognition.common.algorithms.ExtremumItem-) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [flipExtremum()](#flipExtremum--) | Flip min to max or max to min |
| [getClass()](#getClass--) |  |
| [getHashCode()](#getHashCode--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtremumItem() {#ExtremumItem--}
```
public ExtremumItem()
```


### ExtremumItem(HistogramItem histogramItem, int histogramItemType) {#ExtremumItem-com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem-int-}
```
public ExtremumItem(HistogramItem histogramItem, int histogramItemType)
```


Initialize a new instance of the  ExtremumItem  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| histogramItem | [HistogramItem](../../com.aspose.barcode.barcoderecognition.common.algorithms/histogramitem) | histogram item |
| histogramItemType | int | type of item |

### IsComplex {#IsComplex}
```
public boolean IsComplex
```


Is complex extremum

### Module {#Module}
```
public int Module
```


A module

### ModuleBySkew {#ModuleBySkew}
```
public float ModuleBySkew
```


Module calculated using skew

### NumberFrom {#NumberFrom}
```
public int NumberFrom
```


A start of extremum column

### NumberTo {#NumberTo}
```
public int NumberTo
```


An end of of extremum column

### PointType {#PointType}
```
public int PointType
```


A type of a point (extremum, regular, complex)

### Value {#Value}
```
public int Value
```


Value of darkness.

### Clone() {#Clone--}
```
public ExtremumItem Clone()
```




**Returns:**
[ExtremumItem](../../com.aspose.barcode.barcoderecognition.common.algorithms/extremumitem)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(ExtremumItem that) {#CloneTo-com.aspose.barcode.barcoderecognition.common.algorithms.ExtremumItem-}
```
public void CloneTo(ExtremumItem that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [ExtremumItem](../../com.aspose.barcode.barcoderecognition.common.algorithms/extremumitem) |  |

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
### flipExtremum() {#flipExtremum--}
```
public void flipExtremum()
```


Flip min to max or max to min

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHashCode() {#getHashCode--}
```
public int getHashCode()
```




**Returns:**
int
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

