---
title: EccMathContext
second_title: Aspose.BarCode for Java API Reference
description: Math for ECC 000-140 algorithm
type: docs
weight: 11
url: /java/com.aspose.barcode.encoders/eccmathcontext/
---
**Inheritance:**
java.lang.Object
```
public class EccMathContext
```

Math for ECC 000-140 algorithm
## Constructors

| Constructor | Description |
| --- | --- |
| [EccMathContext(IConvolutionStrategy convolutionStrategy)](#EccMathContext-com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution.IConvolutionStrategy-) | Initializes a new instance of the  EccMathContext  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [executeConvolution()](#executeConvolution--) | Executes convolution algorithm |
| [getClass()](#getClass--) |  |
| [getOutBytes()](#getOutBytes--) | Get result algorithm bytes |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBytes(List<Byte> bytes)](#setBytes-java.util.List-java.lang.Byte--) | Initializes field \_bytes by input bytes |
| [toBitStream(byte[] args)](#toBitStream-byte---) | Initializes \_bytes by args |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EccMathContext(IConvolutionStrategy convolutionStrategy) {#EccMathContext-com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution.IConvolutionStrategy-}
```
public EccMathContext(IConvolutionStrategy convolutionStrategy)
```


Initializes a new instance of the  EccMathContext  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convolutionStrategy | [IConvolutionStrategy](../../com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution/iconvolutionstrategy) | 000, 050, 080, 100 or 140 ECC strategy |

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
### executeConvolution() {#executeConvolution--}
```
public void executeConvolution()
```


Executes convolution algorithm

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOutBytes() {#getOutBytes--}
```
public List<Byte> getOutBytes()
```


Get result algorithm bytes

**Returns:**
[List](../../java.util/list) - \_outBytes field of the EccMathContext class
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




### setBytes(List<Byte> bytes) {#setBytes-java.util.List-java.lang.Byte--}
```
public void setBytes(List<Byte> bytes)
```


Initializes field \_bytes by input bytes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | java.util.List<java.lang.Byte> | input bytes |

### toBitStream(byte[] args) {#toBitStream-byte---}
```
public void toBitStream(byte[] args)
```


Initializes \_bytes by args

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | byte[] | input arguments |

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

