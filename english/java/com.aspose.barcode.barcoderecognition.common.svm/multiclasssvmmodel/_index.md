---
title: MulticlassSvmModel
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.common.svm/multiclasssvmmodel/
---
**Inheritance:**
java.lang.Object
```
public class MulticlassSvmModel
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MulticlassSvmModel(int numberOfInputs, int numberOfClasses, Dictionary<String,BinarySvmModel> binaryModels)](#MulticlassSvmModel-int-int-com.aspose.barcode.java.Dictionary-java.lang.String-com.aspose.barcode.barcoderecognition.common.svm.BinarySvmModel--) |  |
## Fields

| Field | Description |
| --- | --- |
| [BinaryModels](#BinaryModels) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getByClassPair(ClassPair classPair)](#getByClassPair-com.aspose.barcode.barcoderecognition.common.svm.ClassPair-) |  |
| [getByClassPair(int class1, int class2)](#getByClassPair-int-int-) |  |
| [getClass()](#getClass--) |  |
| [getNumberOfClasses()](#getNumberOfClasses--) |  |
| [getNumberOfInputs()](#getNumberOfInputs--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MulticlassSvmModel(int numberOfInputs, int numberOfClasses, Dictionary<String,BinarySvmModel> binaryModels) {#MulticlassSvmModel-int-int-com.aspose.barcode.java.Dictionary-java.lang.String-com.aspose.barcode.barcoderecognition.common.svm.BinarySvmModel--}
```
public MulticlassSvmModel(int numberOfInputs, int numberOfClasses, Dictionary<String,BinarySvmModel> binaryModels)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numberOfInputs | int |  |
| numberOfClasses | int |  |
| binaryModels | com.aspose.barcode.java.Dictionary<java.lang.String,com.aspose.barcode.barcoderecognition.common.svm.BinarySvmModel> |  |

### BinaryModels {#BinaryModels}
```
public Dictionary<String,BinarySvmModel> BinaryModels
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
### getByClassPair(ClassPair classPair) {#getByClassPair-com.aspose.barcode.barcoderecognition.common.svm.ClassPair-}
```
public BinarySvmModel getByClassPair(ClassPair classPair)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| classPair | com.aspose.barcode.barcoderecognition.common.svm.ClassPair |  |

**Returns:**
[BinarySvmModel](../../com.aspose.barcode.barcoderecognition.common.svm/binarysvmmodel)
### getByClassPair(int class1, int class2) {#getByClassPair-int-int-}
```
public BinarySvmModel getByClassPair(int class1, int class2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| class1 | int |  |
| class2 | int |  |

**Returns:**
[BinarySvmModel](../../com.aspose.barcode.barcoderecognition.common.svm/binarysvmmodel)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getNumberOfClasses() {#getNumberOfClasses--}
```
public int getNumberOfClasses()
```




**Returns:**
int
### getNumberOfInputs() {#getNumberOfInputs--}
```
public int getNumberOfInputs()
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

