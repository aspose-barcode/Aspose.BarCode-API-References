---
title: DataMatrixEccEncoder
second_title: Aspose.BarCode for Java API Reference
description: The class for encoding
type: docs
weight: 10
url: /java/com.aspose.barcode.encoders.datamatrix.ecc000_140/datamatrixeccencoder/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixEccEncoder
```

The class for encoding
## Constructors

| Constructor | Description |
| --- | --- |
| [DataMatrixEccEncoder()](#DataMatrixEccEncoder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [encode(String codeText, DataMatrixEccType eccType, DataMatrixEncodeMode mode)](#encode-java.lang.String-com.aspose.barcode.generation.DataMatrixEccType-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode the codetext to ECC 000-140 datamatrix |
| [encodeUnprotectedBits(System.Collections.Generic.List<Byte> bits, DataMatrixEccType eccType)](#encodeUnprotectedBits-com.aspose.ms.System.Collections.Generic.List-java.lang.Byte--com.aspose.barcode.generation.DataMatrixEccType-) | Encodes list of unprotected bits to the DataMatrix (corresponding steps 3-6 from par.6.2 of ISO/IEC FCD 16022 ) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCrcForPrefix(String codeText, int formatId)](#getCrcForPrefix-java.lang.String-int-) | Encode ASCII, add prefix, revere by 8, make CRC sequence and reverse |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataMatrixEccEncoder() {#DataMatrixEccEncoder--}
```
public DataMatrixEccEncoder()
```


### encode(String codeText, DataMatrixEccType eccType, DataMatrixEncodeMode mode) {#encode-java.lang.String-com.aspose.barcode.generation.DataMatrixEccType-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public String encode(String codeText, DataMatrixEccType eccType, DataMatrixEncodeMode mode)
```


Encode the codetext to ECC 000-140 datamatrix

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeText | java.lang.String | Input codetext |
| eccType | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | ECC 000, 050, 080, 100 or 140. |
| mode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Datamatrix encodation mode |

**Returns:**
java.lang.String - Datamatrix string
### encodeUnprotectedBits(System.Collections.Generic.List<Byte> bits, DataMatrixEccType eccType) {#encodeUnprotectedBits-com.aspose.ms.System.Collections.Generic.List-java.lang.Byte--com.aspose.barcode.generation.DataMatrixEccType-}
```
public byte[][] encodeUnprotectedBits(System.Collections.Generic.List<Byte> bits, DataMatrixEccType eccType)
```


Encodes list of unprotected bits to the DataMatrix (corresponding steps 3-6 from par.6.2 of ISO/IEC FCD 16022 )

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bits | com.aspose.ms.System.Collections.Generic.List<java.lang.Byte> | Input list of bits |
| eccType | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | The type of ECC from 000 to 140 |

**Returns:**
byte[][] - DataMatrix without bounds
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
### getCrcForPrefix(String codeText, int formatId) {#getCrcForPrefix-java.lang.String-int-}
```
public static System.Collections.Generic.List<Byte> getCrcForPrefix(String codeText, int formatId)
```


Encode ASCII, add prefix, revere by 8, make CRC sequence and reverse

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codeText | java.lang.String | Input codetext |
| formatId | int | format ID |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - CRC part of the prefix
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

