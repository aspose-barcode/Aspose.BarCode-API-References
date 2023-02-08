---
title: FakeFullEncodation
second_title: Aspose.BarCode for Java API Reference
description: Fake encoder for calculating expected capacity.
type: docs
weight: 17
url: /java/com.aspose.barcode.encoders.datamatrix.encodationschemes/fakefullencodation/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.encoders.datamatrix.encodationschemes.EncodationScheme](../../com.aspose.barcode.encoders.datamatrix.encodationschemes/encodationscheme)
```
public class FakeFullEncodation extends EncodationScheme
```

Fake encoder for calculating expected capacity.
## Constructors

| Constructor | Description |
| --- | --- |
| [FakeFullEncodation(DataMatrixEncodeMode mode)](#FakeFullEncodation-com.aspose.barcode.generation.DataMatrixEncodeMode-) |  |
## Methods

| Method | Description |
| --- | --- |
| [encodeData(String text)](#encodeData-java.lang.String-) | Calcultes expected capacity. |
| [encodeLastData(String text, int targetCapacity)](#encodeLastData-java.lang.String-int-) |  |
| [encodeLastData(String text, int targetCapacity, int usedCapacity)](#encodeLastData-java.lang.String-int-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FakeFullEncodation(DataMatrixEncodeMode mode) {#FakeFullEncodation-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public FakeFullEncodation(DataMatrixEncodeMode mode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### encodeData(String text) {#encodeData-java.lang.String-}
```
public byte[] encodeData(String text)
```


Calcultes expected capacity. Doesn't encode data code words.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |

**Returns:**
byte[]
### encodeLastData(String text, int targetCapacity) {#encodeLastData-java.lang.String-int-}
```
public byte[] encodeLastData(String text, int targetCapacity)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| targetCapacity | int |  |

**Returns:**
byte[]
### encodeLastData(String text, int targetCapacity, int usedCapacity) {#encodeLastData-java.lang.String-int-int-}
```
public byte[] encodeLastData(String text, int targetCapacity, int usedCapacity)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| targetCapacity | int |  |
| usedCapacity | int |  |

**Returns:**
byte[]
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

