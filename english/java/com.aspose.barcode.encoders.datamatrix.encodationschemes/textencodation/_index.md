---
title: TextEncodation
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 18
url: /java/com.aspose.barcode.encoders.datamatrix.encodationschemes/textencodation/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.encoders.datamatrix.encodationschemes.EncodationScheme](../../com.aspose.barcode.encoders.datamatrix.encodationschemes/encodationscheme), [com.aspose.barcode.encoders.datamatrix.encodationschemes.C40Encodation](../../com.aspose.barcode.encoders.datamatrix.encodationschemes/c40encodation)
```
public class TextEncodation extends C40Encodation
```
## Constructors

| Constructor | Description |
| --- | --- |
| [TextEncodation()](#TextEncodation--) |  |
## Methods

| Method | Description |
| --- | --- |
| [encodeData(String text)](#encodeData-java.lang.String-) |  |
| [encodeLastData(String text, int targetCapacity)](#encodeLastData-java.lang.String-int-) |  |
| [encodeLastData(String text, int targetCapacity, int usedCapacity)](#encodeLastData-java.lang.String-int-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareToAddPad(System.Collections.Generic.List<Byte> dataCodeWords)](#prepareToAddPad-com.aspose.ms.System.Collections.Generic.List-java.lang.Byte--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextEncodation() {#TextEncodation--}
```
public TextEncodation()
```


### encodeData(String text) {#encodeData-java.lang.String-}
```
public byte[] encodeData(String text)
```




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




### prepareToAddPad(System.Collections.Generic.List<Byte> dataCodeWords) {#prepareToAddPad-com.aspose.ms.System.Collections.Generic.List-java.lang.Byte--}
```
public System.Collections.Generic.List<Byte> prepareToAddPad(System.Collections.Generic.List<Byte> dataCodeWords)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataCodeWords | com.aspose.ms.System.Collections.Generic.List<java.lang.Byte> |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
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

