---
title: PlacementTable
second_title: Aspose.BarCode for Java API Reference
description: The class for placing modules in the matrix
type: docs
weight: 10
url: /java/com.aspose.barcode.common.constants.datamatrixconstants.placementtables/placementtable/
---
**Inheritance:**
java.lang.Object
```
public class PlacementTable
```

The class for placing modules in the matrix
## Constructors

| Constructor | Description |
| --- | --- |
| [PlacementTable()](#PlacementTable--) |  |
## Methods

| Method | Description |
| --- | --- |
| [bytesToMatrix(List<Byte> bytes)](#bytesToMatrix-java.util.List-java.lang.Byte--) | Using the Data Module Placement Grid for this matrix size, the data modules are placed into the binary matrix data area. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [matrixToBytes(byte[][] matrix)](#matrixToBytes-byte-----) | Returns unprotected bit stream with prefix and trailer(postfix) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlacementTable() {#PlacementTable--}
```
public PlacementTable()
```


### bytesToMatrix(List<Byte> bytes) {#bytesToMatrix-java.util.List-java.lang.Byte--}
```
public static byte[][] bytesToMatrix(List<Byte> bytes)
```


Using the Data Module Placement Grid for this matrix size, the data modules are placed into the binary matrix data area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | java.util.List<java.lang.Byte> | input bytes |

**Returns:**
byte[][] - binary matrix
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
### matrixToBytes(byte[][] matrix) {#matrixToBytes-byte-----}
```
public static List<Byte> matrixToBytes(byte[][] matrix)
```


Returns unprotected bit stream with prefix and trailer(postfix)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | byte[][] | input matrix |

**Returns:**
[List](../../java.util/list) - Unprotected bit stream with prefix and trailer(postfix)
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

