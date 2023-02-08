---
title: EccMathStrategy
second_title: Aspose.BarCode for Java API Reference
description: Base class for convolution strategies
type: docs
weight: 15
url: /java/com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution/eccmathstrategy/
---
**Inheritance:**
java.lang.Object
```
public class EccMathStrategy
```

Base class for convolution strategies
## Constructors

| Constructor | Description |
| --- | --- |
| [EccMathStrategy()](#EccMathStrategy--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addPostfix(List<Byte> bytes)](#addPostfix-java.util.List-java.lang.Byte--) | Adds 0 in the end of bytes to make length of List = x^2, where x is the odd from 7 to 47 |
| [addPrefix(List<Byte> bytes)](#addPrefix-java.util.List-java.lang.Byte--) | Adds \\u0430 prefix corresponding CreatePrefix |
| [continueConvolution(List<Byte> inBytes)](#continueConvolution-java.util.List-java.lang.Byte--) | This methos continue convolution algorithm from the last stoppage |
| [createPrefix()](#createPrefix--) | Create the Ecc algorithm prefix. |
| [doConvolution(List<Byte> inBytes)](#doConvolution-java.util.List-java.lang.Byte--) | The convolution algorithm |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getListGen()](#getListGen--) | Gets a list of lists of generation sequences for different summators |
| [getMemLength()](#getMemLength--) | Gets a number of memory bytes in 1(largest) memory sequence +1 |
| [getMemNum()](#getMemNum--) | Gets the count of memory sequences(number of input bytes in 1 step) |
| [getSumNum()](#getSumNum--) | Gets a number of summators (output bytes in 1 step) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMemLength(int value)](#setMemLength-int-) | Sets a number of memory bytes in 1(largest) memory sequence +1 |
| [setMemNum(int value)](#setMemNum-int-) | Sets the count of memory sequences(number of input bytes in 1 step) |
| [setSumNum(int value)](#setSumNum-int-) | Sets a number of summators (output bytes in 1 step) |
| [stoppageConvolution(List<Byte> inBytes, List<Byte> outBytes)](#stoppageConvolution-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--) | Marks a stoppage point |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EccMathStrategy() {#EccMathStrategy--}
```
public EccMathStrategy()
```


### addPostfix(List<Byte> bytes) {#addPostfix-java.util.List-java.lang.Byte--}
```
public void addPostfix(List<Byte> bytes)
```


Adds 0 in the end of bytes to make length of List = x^2, where x is the odd from 7 to 47

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | java.util.List<java.lang.Byte> | input bytes |

### addPrefix(List<Byte> bytes) {#addPrefix-java.util.List-java.lang.Byte--}
```
public void addPrefix(List<Byte> bytes)
```


Adds \\u0430 prefix corresponding CreatePrefix

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | java.util.List<java.lang.Byte> | input list of binary data |

### continueConvolution(List<Byte> inBytes) {#continueConvolution-java.util.List-java.lang.Byte--}
```
public List<Byte> continueConvolution(List<Byte> inBytes)
```


This methos continue convolution algorithm from the last stoppage

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inBytes | java.util.List<java.lang.Byte> |  |

**Returns:**
[List](../../java.util/list) - 
### createPrefix() {#createPrefix--}
```
public List<Byte> createPrefix()
```


Create the Ecc algorithm prefix.

**Returns:**
[List](../../java.util/list) - a prefix
### doConvolution(List<Byte> inBytes) {#doConvolution-java.util.List-java.lang.Byte--}
```
public List<Byte> doConvolution(List<Byte> inBytes)
```


The convolution algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inBytes | java.util.List<java.lang.Byte> | input unprotected bytes |

**Returns:**
[List](../../java.util/list) - convoluted bytes
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
### getListGen() {#getListGen--}
```
public List<List<List<Byte>>> getListGen()
```


Gets a list of lists of generation sequences for different summators

**Returns:**
[List](../../java.util/list)
### getMemLength() {#getMemLength--}
```
public int getMemLength()
```


Gets a number of memory bytes in 1(largest) memory sequence +1

**Returns:**
int
### getMemNum() {#getMemNum--}
```
public int getMemNum()
```


Gets the count of memory sequences(number of input bytes in 1 step)

**Returns:**
int
### getSumNum() {#getSumNum--}
```
public int getSumNum()
```


Gets a number of summators (output bytes in 1 step)

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




### setMemLength(int value) {#setMemLength-int-}
```
public void setMemLength(int value)
```


Sets a number of memory bytes in 1(largest) memory sequence +1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMemNum(int value) {#setMemNum-int-}
```
public void setMemNum(int value)
```


Sets the count of memory sequences(number of input bytes in 1 step)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSumNum(int value) {#setSumNum-int-}
```
public void setSumNum(int value)
```


Sets a number of summators (output bytes in 1 step)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### stoppageConvolution(List<Byte> inBytes, List<Byte> outBytes) {#stoppageConvolution-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--}
```
public void stoppageConvolution(List<Byte> inBytes, List<Byte> outBytes)
```


Marks a stoppage point

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inBytes | java.util.List<java.lang.Byte> | input bytes |
| outBytes | java.util.List<java.lang.Byte> | already received output bytes |

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

