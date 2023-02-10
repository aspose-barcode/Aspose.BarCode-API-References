---
title: pdf417DataExtractor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417dataextractor/
---
**Inheritance:**
java.lang.Object
```
public class pdf417DataExtractor
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417DataExtractor()](#pdf417DataExtractor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [correctErrors(List<Integer> data, int ecLevel, int CorrType)](#correctErrors-java.util.List-java.lang.Integer--int-int-) | Corrects recognized codewords or return null if correction isn't possible |
| [decodeStream(List<Integer> data, QuadPoints aQuad, boolean FailedCorrection)](#decodeStream-java.util.List-java.lang.Integer--com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-boolean-) | Decode recognized codewords list to recognized result |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417DataExtractor() {#pdf417DataExtractor--}
```
public pdf417DataExtractor()
```


### correctErrors(List<Integer> data, int ecLevel, int CorrType) {#correctErrors-java.util.List-java.lang.Integer--int-int-}
```
public static List<Integer> correctErrors(List<Integer> data, int ecLevel, int CorrType)
```


Corrects recognized codewords or return null if correction isn't possible

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | java.util.List<java.lang.Integer> | list of recognized codewords with replaced wipes |
| ecLevel | int | error correction levels, index of errorCorrectionCapacity |
| CorrType | int | AllowIncorrectBarcodes or normal |

**Returns:**
[List](../../java.util/list) - corrected codewords or null
### decodeStream(List<Integer> data, QuadPoints aQuad, boolean FailedCorrection) {#decodeStream-java.util.List-java.lang.Integer--com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-boolean-}
```
public static pdf417RecognitionResult decodeStream(List<Integer> data, QuadPoints aQuad, boolean FailedCorrection)
```


Decode recognized codewords list to recognized result

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | java.util.List<java.lang.Integer> | corrected or raw recognized codewords |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | external qadrangle of the barcode |
| FailedCorrection | boolean | is data corrected or not |

**Returns:**
[pdf417RecognitionResult](../../com.aspose.barcode.barcoderecognition.pdf417/pdf417recognitionresult) - decoded result with parameters
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

