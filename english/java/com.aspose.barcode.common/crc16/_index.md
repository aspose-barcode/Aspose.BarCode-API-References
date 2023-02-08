---
title: Crc16
second_title: Aspose.BarCode for Java API Reference
description: Functions for generating the CRC16
type: docs
weight: 11
url: /java/com.aspose.barcode.common/crc16/
---
**Inheritance:**
java.lang.Object
```
public class Crc16
```

Functions for generating the CRC16
## Constructors

| Constructor | Description |
| --- | --- |
| [Crc16()](#Crc16--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [genCrc16(Byte[] c, int nByte)](#genCrc16-java.lang.Byte---int-) | Gens the CRC16. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toByteList(System.Collections.Generic.List<Byte> bits)](#toByteList-com.aspose.ms.System.Collections.Generic.List-java.lang.Byte--) | Convert bit list to byte list |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Crc16() {#Crc16--}
```
public Crc16()
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
### genCrc16(Byte[] c, int nByte) {#genCrc16-java.lang.Byte---int-}
```
public static int genCrc16(Byte[] c, int nByte)
```


Gens the CRC16. CRC-1021 = X(16)+x(12)+x(5)+1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | java.lang.Byte[] | The c. |
| nByte | int | The n byte. |

**Returns:**
int - ushort CRC16
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




### toByteList(System.Collections.Generic.List<Byte> bits) {#toByteList-com.aspose.ms.System.Collections.Generic.List-java.lang.Byte--}
```
public static System.Collections.Generic.List<Byte> toByteList(System.Collections.Generic.List<Byte> bits)
```


Convert bit list to byte list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bits | com.aspose.ms.System.Collections.Generic.List<java.lang.Byte> | Input bit list |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - yte list
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

