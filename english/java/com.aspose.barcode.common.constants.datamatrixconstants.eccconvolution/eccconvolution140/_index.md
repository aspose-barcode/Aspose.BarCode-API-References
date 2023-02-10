---
title: EccConvolution140
second_title: Aspose.BarCode for Java API Reference
description: Class for the convolution algorithm ECC 140
type: docs
weight: 14
url: /java/com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution/eccconvolution140/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution.EccMathStrategy](../../com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution/eccmathstrategy)

**All Implemented Interfaces:**
[com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution.IConvolutionStrategy](../../com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution/iconvolutionstrategy), [com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution.IConvolutionFano](../../com.aspose.barcode.common.constants.datamatrixconstants.eccconvolution/iconvolutionfano)
```
public class EccConvolution140 extends EccMathStrategy implements IConvolutionStrategy, IConvolutionFano
```

Class for the convolution algorithm ECC 140
## Constructors

| Constructor | Description |
| --- | --- |
| [EccConvolution140()](#EccConvolution140--) | Initializes a new instance of the  EccConvolution140  class. |
## Methods

| Method | Description |
| --- | --- |
| [addPostfix(List<Byte> bytes)](#addPostfix-java.util.List-java.lang.Byte--) | Adds 0 in the end of bytes to make length of List = x^2, where x is the odd from 7 to 47 |
| [addPrefix(List<Byte> bytes)](#addPrefix-java.util.List-java.lang.Byte--) | Adds \\u0430 prefix corresponding CreatePrefix |
| [algorithm(List<Byte> inBytes)](#algorithm-java.util.List-java.lang.Byte--) | Implements convolutional code 4-1-13 and adds prefix and postfix |
| [blockLength()](#blockLength--) | The length of convoluted block for ECC 140, is equal number o summators |
| [continueConvolution(List<Byte> inBytes)](#continueConvolution-java.util.List-java.lang.Byte--) |  |
| [createPrefix()](#createPrefix--) | Create 19 bits corresponding ECC 150 |
| [deltaFactor()](#deltaFactor--) | Returns constant for the Fano algorithm of ECC 140 |
| [doConvolution(List<Byte> inBytes)](#doConvolution-java.util.List-java.lang.Byte--) | The convolution algorithm |
| [doConvolutionEcc(List<Byte> inBytes)](#doConvolutionEcc-java.util.List-java.lang.Byte--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getListGen()](#getListGen--) | Gets a list of lists of generation sequences for different summators |
| [getMemLength()](#getMemLength--) | Gets a number of memory bytes in 1(largest) memory sequence +1 |
| [getMemNum()](#getMemNum--) | Gets the count of memory sequences(number of input bytes in 1 step) |
| [getSumNum()](#getSumNum--) | Gets a number of summators (output bytes in 1 step) |
| [hashCode()](#hashCode--) |  |
| [inBlockLength()](#inBlockLength--) | The length of input block for ECC 140 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [penaltyFactor()](#penaltyFactor--) | Returns constant for the Fano algorithm of ECC 140 |
| [possibleBlocks()](#possibleBlocks--) | Blocks for building decoded sequence by the algorithm Fano of ECC 140 |
| [setMemLength(int value)](#setMemLength-int-) | Sets a number of memory bytes in 1(largest) memory sequence +1 |
| [setMemNum(int value)](#setMemNum-int-) | Sets the count of memory sequences(number of input bytes in 1 step) |
| [setSumNum(int value)](#setSumNum-int-) | Sets a number of summators (output bytes in 1 step) |
| [stoppageConvolution(List<Byte> inBytes, List<Byte> outBytes)](#stoppageConvolution-java.util.List-java.lang.Byte--java.util.List-java.lang.Byte--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EccConvolution140() {#EccConvolution140--}
```
public EccConvolution140()
```


Initializes a new instance of the  EccConvolution140  class.

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

### algorithm(List<Byte> inBytes) {#algorithm-java.util.List-java.lang.Byte--}
```
public List<Byte> algorithm(List<Byte> inBytes)
```


Implements convolutional code 4-1-13 and adds prefix and postfix

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inBytes | java.util.List<java.lang.Byte> | input bytes |

**Returns:**
[List](../../java.util/list) - Encoded bytes
### blockLength() {#blockLength--}
```
public int blockLength()
```


The length of convoluted block for ECC 140, is equal number o summators

**Returns:**
int - The length of convoluted bytes for ECC 140
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
[List](../../java.util/list)
### createPrefix() {#createPrefix--}
```
public List<Byte> createPrefix()
```


Create 19 bits corresponding ECC 150

**Returns:**
[List](../../java.util/list) - a prefix
### deltaFactor() {#deltaFactor--}
```
public int deltaFactor()
```


Returns constant for the Fano algorithm of ECC 140

**Returns:**
int - Constant Delta for the Fano algorithm of ECC 050
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
### doConvolutionEcc(List<Byte> inBytes) {#doConvolutionEcc-java.util.List-java.lang.Byte--}
```
public List<Byte> doConvolutionEcc(List<Byte> inBytes)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inBytes | java.util.List<java.lang.Byte> |  |

**Returns:**
[List](../../java.util/list)
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
### inBlockLength() {#inBlockLength--}
```
public int inBlockLength()
```


The length of input block for ECC 140

**Returns:**
int - The length of input block
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### penaltyFactor() {#penaltyFactor--}
```
public int penaltyFactor()
```


Returns constant for the Fano algorithm of ECC 140

**Returns:**
int - constant for the Fano algorithm of ECC 140
### possibleBlocks() {#possibleBlocks--}
```
public List<List<Byte>> possibleBlocks()
```


Blocks for building decoded sequence by the algorithm Fano of ECC 140

**Returns:**
[List](../../java.util/list) - The list of possible blocks
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
| inBytes | java.util.List<java.lang.Byte> |  |
| outBytes | java.util.List<java.lang.Byte> |  |

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

