---
title: FanoAlgorithm
second_title: Aspose.BarCode for Java API Reference
description: The class for the Fano algorithm
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.ecc000_140.eccfano/fanoalgorithm/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.datamatrix.ecc000_140.eccfano.IFano](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.ecc000_140.eccfano/ifano)
```
public class FanoAlgorithm implements IFano
```

The class for the Fano algorithm
## Constructors

| Constructor | Description |
| --- | --- |
| [FanoAlgorithm(IConvolutionFano convolution)](#FanoAlgorithm-com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution.IConvolutionFano-) | Initializes a new instance of the  FanoAlgorithm  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [executeFano(List<Byte> inputBytes, int limit)](#executeFano-java.util.List-java.lang.Byte--int-) | Decode byte array |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeSuffix(List<Byte> bytes)](#removeSuffix-com.aspose.barcode.java.List-java.lang.Byte--) | Removes last bytes. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FanoAlgorithm(IConvolutionFano convolution) {#FanoAlgorithm-com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution.IConvolutionFano-}
```
public FanoAlgorithm(IConvolutionFano convolution)
```


Initializes a new instance of the  FanoAlgorithm  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convolution | [IConvolutionFano](../../com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution/iconvolutionfano) | convolution strategy |

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
### executeFano(List<Byte> inputBytes, int limit) {#executeFano-java.util.List-java.lang.Byte--int-}
```
public List<Byte> executeFano(List<Byte> inputBytes, int limit)
```


Decode byte array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputBytes | java.util.List<java.lang.Byte> | input bytes |
| limit | int | a number of convolution iterations after which the forced stop algorithm, is usually several thousand |

**Returns:**
[List](../../com.aspose.barcode.java/list) - Decoded bytes
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




### removeSuffix(List<Byte> bytes) {#removeSuffix-com.aspose.barcode.java.List-java.lang.Byte--}
```
public void removeSuffix(List<Byte> bytes)
```


Removes last bytes. The total length must be divisible by BlockLength. Result may contain additional zeros.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | com.aspose.barcode.java.List<java.lang.Byte> | input bytes |

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

