---
title: ExtBitStream
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.common/extbitstream/
---
**Inheritance:**
java.lang.Object
```
public class ExtBitStream
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ExtBitStream(byte[] aBuffer, boolean isBitBuffer)](#ExtBitStream-byte---boolean-) |  |
| [ExtBitStream(byte[] aBuffer, int bitsCount, boolean isBitBuffer)](#ExtBitStream-byte---int-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvailable()](#getAvailable--) |  |
| [getAvailableToLastSignificantByte()](#getAvailableToLastSignificantByte--) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) |  |
| [getPosition()](#getPosition--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBits(int count)](#readBits-int-) | Added for the support |
| [readBitsBuffer(int count)](#readBitsBuffer-int-) |  |
| [readByte()](#readByte--) |  |
| [readByte(int count)](#readByte-int-) |  |
| [readInt32(int count)](#readInt32-int-) |  |
| [seek(int offset, int loc)](#seek-int-int-) |  |
| [spyBitsBuffer(int count)](#spyBitsBuffer-int-) | Read bit data without moving position |
| [spyByte()](#spyByte--) |  |
| [spyByte(int count)](#spyByte-int-) |  |
| [spyInt32(int count)](#spyInt32-int-) | Read bit data without moving position |
| [toString()](#toString--) |  |
| [trimmToLastSignificantByte()](#trimmToLastSignificantByte--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeBitsBuffer(byte[] aBuffer)](#writeBitsBuffer-byte---) |  |
| [writeByte(byte value)](#writeByte-byte-) |  |
| [writeByte(byte value, int count)](#writeByte-byte-int-) |  |
| [writeInt32(int value, int count)](#writeInt32-int-int-) |  |
### ExtBitStream(byte[] aBuffer, boolean isBitBuffer) {#ExtBitStream-byte---boolean-}
```
public ExtBitStream(byte[] aBuffer, boolean isBitBuffer)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBuffer | byte[] |  |
| isBitBuffer | boolean |  |

### ExtBitStream(byte[] aBuffer, int bitsCount, boolean isBitBuffer) {#ExtBitStream-byte---int-boolean-}
```
public ExtBitStream(byte[] aBuffer, int bitsCount, boolean isBitBuffer)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBuffer | byte[] |  |
| bitsCount | int |  |
| isBitBuffer | boolean |  |

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
### getAvailable() {#getAvailable--}
```
public int getAvailable()
```




**Returns:**
int
### getAvailableToLastSignificantByte() {#getAvailableToLastSignificantByte--}
```
public int getAvailableToLastSignificantByte()
```




**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public int getLength()
```




**Returns:**
int
### getPosition() {#getPosition--}
```
public int getPosition()
```




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




### readBits(int count) {#readBits-int-}
```
public int readBits(int count)
```


Added for the support

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int | bits count to read |

**Returns:**
int - packed integer value of read bits
### readBitsBuffer(int count) {#readBitsBuffer-int-}
```
public byte[] readBitsBuffer(int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int |  |

**Returns:**
byte[]
### readByte() {#readByte--}
```
public byte readByte()
```




**Returns:**
byte
### readByte(int count) {#readByte-int-}
```
public byte readByte(int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int |  |

**Returns:**
byte
### readInt32(int count) {#readInt32-int-}
```
public int readInt32(int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int |  |

**Returns:**
int
### seek(int offset, int loc) {#seek-int-int-}
```
public int seek(int offset, int loc)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offset | int |  |
| loc | int |  |

**Returns:**
int
### spyBitsBuffer(int count) {#spyBitsBuffer-int-}
```
public byte[] spyBitsBuffer(int count)
```


Read bit data without moving position

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int | bits count to read |

**Returns:**
byte[] - bits array as bytes array
### spyByte() {#spyByte--}
```
public byte spyByte()
```




**Returns:**
byte
### spyByte(int count) {#spyByte-int-}
```
public byte spyByte(int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int |  |

**Returns:**
byte
### spyInt32(int count) {#spyInt32-int-}
```
public int spyInt32(int count)
```


Read bit data without moving position

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int | bits count to read |

**Returns:**
int - int in which all bits are read
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### trimmToLastSignificantByte() {#trimmToLastSignificantByte--}
```
public void trimmToLastSignificantByte()
```




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

### writeBitsBuffer(byte[] aBuffer) {#writeBitsBuffer-byte---}
```
public void writeBitsBuffer(byte[] aBuffer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBuffer | byte[] |  |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### writeByte(byte value, int count) {#writeByte-byte-int-}
```
public void writeByte(byte value, int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
| count | int |  |

### writeInt32(int value, int count) {#writeInt32-int-int-}
```
public void writeInt32(int value, int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
| count | int |  |

