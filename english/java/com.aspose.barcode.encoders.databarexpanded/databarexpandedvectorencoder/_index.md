---
title: DatabarExpandedVectorEncoder
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.aspose.barcode.encoders.databarexpanded/databarexpandedvectorencoder/
---
**Inheritance:**
java.lang.Object
```
public class DatabarExpandedVectorEncoder
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DatabarExpandedVectorEncoder()](#DatabarExpandedVectorEncoder--) |  |
## Fields

| Field | Description |
| --- | --- |
| [STARTSYMBOL](#STARTSYMBOL) |  |
| [STARTSYMBOL_INVERSE](#STARTSYMBOL-INVERSE) |  |
| [STOPSYMBOL](#STOPSYMBOL) |  |
| [STOPSYMBOL_INVERSE](#STOPSYMBOL-INVERSE) |  |
## Methods

| Method | Description |
| --- | --- |
| [addGuardPatterns(String binaryVector)](#addGuardPatterns-java.lang.String-) |  |
| [encodeBinaryStringToVectors(String binaryString)](#encodeBinaryStringToVectors-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [vectors2BinaryString(System.Collections.IEnumerable<Int32List> vectors)](#vectors2BinaryString-com.aspose.ms.System.Collections.IEnumerable-com.aspose.barcode.common.generic.list.Int32List--) |  |
| [vectors2BinaryString(System.Collections.IEnumerable<Int32List> vectors, char startBar)](#vectors2BinaryString-com.aspose.ms.System.Collections.IEnumerable-com.aspose.barcode.common.generic.list.Int32List--char-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DatabarExpandedVectorEncoder() {#DatabarExpandedVectorEncoder--}
```
public DatabarExpandedVectorEncoder()
```


### STARTSYMBOL {#STARTSYMBOL}
```
public static final String STARTSYMBOL
```


### STARTSYMBOL_INVERSE {#STARTSYMBOL-INVERSE}
```
public static final String STARTSYMBOL_INVERSE
```


### STOPSYMBOL {#STOPSYMBOL}
```
public static final String STOPSYMBOL
```


### STOPSYMBOL_INVERSE {#STOPSYMBOL-INVERSE}
```
public static final String STOPSYMBOL_INVERSE
```


### addGuardPatterns(String binaryVector) {#addGuardPatterns-java.lang.String-}
```
public static String addGuardPatterns(String binaryVector)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryVector | java.lang.String |  |

**Returns:**
java.lang.String
### encodeBinaryStringToVectors(String binaryString) {#encodeBinaryStringToVectors-java.lang.String-}
```
public static Int32ListList encodeBinaryStringToVectors(String binaryString)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryString | java.lang.String |  |

**Returns:**
[Int32ListList](../../com.aspose.barcode.common.generic.list/int32listlist)
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
### vectors2BinaryString(System.Collections.IEnumerable<Int32List> vectors) {#vectors2BinaryString-com.aspose.ms.System.Collections.IEnumerable-com.aspose.barcode.common.generic.list.Int32List--}
```
public static String vectors2BinaryString(System.Collections.IEnumerable<Int32List> vectors)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vectors | com.aspose.ms.System.Collections.IEnumerable<com.aspose.barcode.common.generic.list.Int32List> |  |

**Returns:**
java.lang.String
### vectors2BinaryString(System.Collections.IEnumerable<Int32List> vectors, char startBar) {#vectors2BinaryString-com.aspose.ms.System.Collections.IEnumerable-com.aspose.barcode.common.generic.list.Int32List--char-}
```
public static String vectors2BinaryString(System.Collections.IEnumerable<Int32List> vectors, char startBar)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vectors | com.aspose.ms.System.Collections.IEnumerable<com.aspose.barcode.common.generic.list.Int32List> |  |
| startBar | char |  |

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

