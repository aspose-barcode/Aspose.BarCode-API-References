---
title: OffsetIterator
second_title: Aspose.BarCode for Java API Reference
description: Class for modifying an offset of a context in a cycle
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.timepatterns/offsetiterator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ICorrector](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/icorrector)
```
public class OffsetIterator implements ICorrector
```

Class for modifying an offset of a context in a cycle
## Constructors

| Constructor | Description |
| --- | --- |
| [OffsetIterator(int maxOffset)](#OffsetIterator-int-) | Initializes a new instance of the [OffsetIterator](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.timepatterns/offsetiterator) class with specified maximum offset |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [modifies(ModelHolder modelHolder)](#modifies-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Modifies an offset from a DataMatrix context |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OffsetIterator(int maxOffset) {#OffsetIterator-int-}
```
public OffsetIterator(int maxOffset)
```


Initializes a new instance of the [OffsetIterator](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.timepatterns/offsetiterator) class with specified maximum offset

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxOffset | int | A maximum offset |

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
### modifies(ModelHolder modelHolder) {#modifies-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-}
```
public final boolean modifies(ModelHolder modelHolder)
```


Modifies an offset from a DataMatrix context

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modelHolder | [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) | Model holder |

**Returns:**
boolean - If modified, return true, else false
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

