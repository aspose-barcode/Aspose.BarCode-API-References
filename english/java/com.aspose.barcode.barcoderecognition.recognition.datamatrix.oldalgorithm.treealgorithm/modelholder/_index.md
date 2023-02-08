---
title: ModelHolder
second_title: Aspose.BarCode for Java API Reference
description: Class for holding and extracting different models
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder/
---
**Inheritance:**
java.lang.Object
```
public class ModelHolder
```

Class for holding and extracting different models
## Constructors

| Constructor | Description |
| --- | --- |
| [ModelHolder()](#ModelHolder--) | Initializes a new instance of the [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) class. |
## Methods

| Method | Description |
| --- | --- |
| [<T>extract(Class clazz)](#-T-extract-java.lang.Class-) | Extracts a model with specified type |
| [addOrRewrite(Object contextModel)](#addOrRewrite-java.lang.Object-) | Adds or rewrites specified model |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getRewritedTypes()](#getRewritedTypes--) | List of the rewrited types |
| [hashCode()](#hashCode--) |  |
| [isAllExtracted()](#isAllExtracted--) | Checks if all types that were extracted after StartExtraction(), are not null |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [startExtraction(Object algorithm)](#startExtraction-java.lang.Object-) | Starts an extraction. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ModelHolder() {#ModelHolder--}
```
public ModelHolder()
```


Initializes a new instance of the [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) class.

### <T>extract(Class clazz) {#-T-extract-java.lang.Class-}
```
public T <T>extract(Class clazz)
```


Extracts a model with specified type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class |  |

**Returns:**
T - Extracted model or null, if can' extract

 T : Type of a model
### addOrRewrite(Object contextModel) {#addOrRewrite-java.lang.Object-}
```
public final void addOrRewrite(Object contextModel)
```


Adds or rewrites specified model

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contextModel | java.lang.Object | A model |

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
### getRewritedTypes() {#getRewritedTypes--}
```
public final System.Collections.Generic.List<System.Type> getRewritedTypes()
```


List of the rewrited types

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAllExtracted() {#isAllExtracted--}
```
public final boolean isAllExtracted()
```


Checks if all types that were extracted after StartExtraction(), are not null

**Returns:**
boolean - True if all types that were extracted after StartExtraction(), are not null
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### startExtraction(Object algorithm) {#startExtraction-java.lang.Object-}
```
public final void startExtraction(Object algorithm)
```


Starts an extraction. Need to call before Extract

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| algorithm | java.lang.Object |  |

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

