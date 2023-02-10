---
title: DataMatrixStateBasedDecodingStream
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.statehandler/datamatrixstatebaseddecodingstream/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.internal.AStateBasedDecodingStream](../../com.aspose.barcode.barcoderecognition.internal/astatebaseddecodingstream)
```
public class DataMatrixStateBasedDecodingStream extends AStateBasedDecodingStream
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DataMatrixStateBasedDecodingStream()](#DataMatrixStateBasedDecodingStream--) |  |
## Methods

| Method | Description |
| --- | --- |
| [decode(BitStream stream)](#decode-com.aspose.barcode.barcoderecognition.recognition.BitStream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reassemblyBytes(int firstByte, int secondByte, int[] result)](#reassemblyBytes-int-int-int---) |  |
| [toString()](#toString--) |  |
| [unrandomize255State(int randomizedBase256Codeword, int base256CodewordPosition)](#unrandomize255State-int-int-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataMatrixStateBasedDecodingStream() {#DataMatrixStateBasedDecodingStream--}
```
public DataMatrixStateBasedDecodingStream()
```


### decode(BitStream stream) {#decode-com.aspose.barcode.barcoderecognition.recognition.BitStream-}
```
public System.Text.msStringBuilder decode(BitStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [BitStream](../../com.aspose.barcode.barcoderecognition.recognition/bitstream) |  |

**Returns:**
com.aspose.ms.System.Text.msStringBuilder
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




### reassemblyBytes(int firstByte, int secondByte, int[] result) {#reassemblyBytes-int-int-int---}
```
public static void reassemblyBytes(int firstByte, int secondByte, int[] result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstByte | int |  |
| secondByte | int |  |
| result | int[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unrandomize255State(int randomizedBase256Codeword, int base256CodewordPosition) {#unrandomize255State-int-int-}
```
public static byte unrandomize255State(int randomizedBase256Codeword, int base256CodewordPosition)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| randomizedBase256Codeword | int |  |
| base256CodewordPosition | int |  |

**Returns:**
byte
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

