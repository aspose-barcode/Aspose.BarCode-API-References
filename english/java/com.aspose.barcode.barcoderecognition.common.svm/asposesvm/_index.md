---
title: AsposeSvm
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.common.svm/asposesvm/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.barcoderecognition.common.svm.IAsposeSvm
```
public class AsposeSvm implements IAsposeSvm
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AsposeSvm(MulticlassSvmModel model)](#AsposeSvm-com.aspose.barcode.barcoderecognition.common.svm.MulticlassSvmModel-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [logLikelihood(System.Collections.Generic.List<double[]> features, int classIndex)](#logLikelihood-com.aspose.ms.System.Collections.Generic.List-double----int-) |  |
| [logLikelihood(double[] input, int classIndex)](#logLikelihood-double---int-) |  |
| [logLikelihood(double[][] input, int classIndex, double[] result)](#logLikelihood-double-----int-double---) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scores(double[] input)](#scores-double---) |  |
| [scores(double[] input, double[] result)](#scores-double---double---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AsposeSvm(MulticlassSvmModel model) {#AsposeSvm-com.aspose.barcode.barcoderecognition.common.svm.MulticlassSvmModel-}
```
public AsposeSvm(MulticlassSvmModel model)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | [MulticlassSvmModel](../../com.aspose.barcode.barcoderecognition.common.svm/multiclasssvmmodel) |  |

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
### logLikelihood(System.Collections.Generic.List<double[]> features, int classIndex) {#logLikelihood-com.aspose.ms.System.Collections.Generic.List-double----int-}
```
public double[] logLikelihood(System.Collections.Generic.List<double[]> features, int classIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| features | com.aspose.ms.System.Collections.Generic.List<double[]> |  |
| classIndex | int |  |

**Returns:**
double[]
### logLikelihood(double[] input, int classIndex) {#logLikelihood-double---int-}
```
public double logLikelihood(double[] input, int classIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | double[] |  |
| classIndex | int |  |

**Returns:**
double
### logLikelihood(double[][] input, int classIndex, double[] result) {#logLikelihood-double-----int-double---}
```
public double[] logLikelihood(double[][] input, int classIndex, double[] result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | double[][] |  |
| classIndex | int |  |
| result | double[] |  |

**Returns:**
double[]
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### scores(double[] input) {#scores-double---}
```
public double[] scores(double[] input)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | double[] |  |

**Returns:**
double[]
### scores(double[] input, double[] result) {#scores-double---double---}
```
public double[] scores(double[] input, double[] result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | double[] |  |
| result | double[] |  |

**Returns:**
double[]
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

