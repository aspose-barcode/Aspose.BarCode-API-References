---
title: BitStream
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition/bitstream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream
```
public class BitStream extends System.IO.Stream
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BitStream()](#BitStream--) |  |
| [BitStream(int capacity)](#BitStream-int-) |  |
| [BitStream(byte[] buffer, boolean writable)](#BitStream-byte---boolean-) |  |
| [BitStream(byte[] buffer)](#BitStream-byte---) |  |
## Fields

| Field | Description |
| --- | --- |
| [Null](#Null) |  |
## Methods

| Method | Description |
| --- | --- |
| [available()](#available--) |  |
| [beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)](#beginRead-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)](#beginWrite-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [canRead()](#canRead--) |  |
| [canSeek()](#canSeek--) |  |
| [canWrite()](#canWrite--) |  |
| [close()](#close--) |  |
| [dispose()](#dispose--) |  |
| [endRead(System.IAsyncResult arg0)](#endRead-com.aspose.ms.System.IAsyncResult-) |  |
| [endWrite(System.IAsyncResult arg0)](#endWrite-com.aspose.ms.System.IAsyncResult-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) |  |
| [fromJava(InputStream arg0)](#fromJava-java.io.InputStream-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) |  |
| [getPosition()](#getPosition--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) |  |
| [readBits(int count)](#readBits-int-) |  |
| [readByte()](#readByte--) |  |
| [seek(long offset, int loc)](#seek-long-int-) |  |
| [setCapacity(int value)](#setCapacity-int-) |  |
| [setLength(long value)](#setLength-long-) |  |
| [setPosition(long value)](#setPosition-long-) |  |
| [toInputStream()](#toInputStream--) |  |
| [toJava(System.IO.Stream arg0)](#toJava-com.aspose.ms.System.IO.Stream-) |  |
| [toOutputStream()](#toOutputStream--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) |  |
| [writeByte(byte value)](#writeByte-byte-) |  |
### BitStream() {#BitStream--}
```
public BitStream()
```


### BitStream(int capacity) {#BitStream-int-}
```
public BitStream(int capacity)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int |  |

### BitStream(byte[] buffer, boolean writable) {#BitStream-byte---boolean-}
```
public BitStream(byte[] buffer, boolean writable)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] |  |
| writable | boolean |  |

### BitStream(byte[] buffer) {#BitStream-byte---}
```
public BitStream(byte[] buffer)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] |  |

### Null {#Null}
```
public static System.IO.Stream Null
```


### available() {#available--}
```
public long available()
```




**Returns:**
long
### beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4) {#beginRead-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public System.IAsyncResult beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | byte[] |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | com.aspose.ms.System.AsyncCallback |  |
| arg4 | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4) {#beginWrite-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public System.IAsyncResult beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | byte[] |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | com.aspose.ms.System.AsyncCallback |  |
| arg4 | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### canRead() {#canRead--}
```
public boolean canRead()
```




**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```




**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```




**Returns:**
boolean
### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public void dispose()
```




### endRead(System.IAsyncResult arg0) {#endRead-com.aspose.ms.System.IAsyncResult-}
```
public int endRead(System.IAsyncResult arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
int
### endWrite(System.IAsyncResult arg0) {#endWrite-com.aspose.ms.System.IAsyncResult-}
```
public void endWrite(System.IAsyncResult arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IAsyncResult |  |

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
### flush() {#flush--}
```
public void flush()
```




### fromJava(InputStream arg0) {#fromJava-java.io.InputStream-}
```
public static System.IO.Stream fromJava(InputStream arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.io.InputStream |  |

**Returns:**
com.aspose.ms.System.IO.Stream
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public long getLength()
```




**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```




**Returns:**
long
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




### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] |  |
| offset | int |  |
| count | int |  |

**Returns:**
int
### readBits(int count) {#readBits-int-}
```
public int readBits(int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int |  |

**Returns:**
int
### readByte() {#readByte--}
```
public int readByte()
```




**Returns:**
int
### seek(long offset, int loc) {#seek-long-int-}
```
public long seek(long offset, int loc)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offset | long |  |
| loc | int |  |

**Returns:**
long
### setCapacity(int value) {#setCapacity-int-}
```
public void setCapacity(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### toInputStream() {#toInputStream--}
```
public InputStream toInputStream()
```




**Returns:**
java.io.InputStream
### toJava(System.IO.Stream arg0) {#toJava-com.aspose.ms.System.IO.Stream-}
```
public static InputStream toJava(System.IO.Stream arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

**Returns:**
java.io.InputStream
### toOutputStream() {#toOutputStream--}
```
public OutputStream toOutputStream()
```




**Returns:**
java.io.OutputStream
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

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] |  |
| offset | int |  |
| count | int |  |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

