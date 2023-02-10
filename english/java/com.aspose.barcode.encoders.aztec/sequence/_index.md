---
title: Sequence
second_title: Aspose.BarCode for Java API Reference
description: Represents sequence Aztec codes with encoging logic.
type: docs
weight: 13
url: /java/com.aspose.barcode.encoders.aztec/sequence/
---
**Inheritance:**
java.lang.Object
```
public class Sequence
```

Represents sequence Aztec codes with encoging logic.
## Constructors

| Constructor | Description |
| --- | --- |
| [Sequence(int state)](#Sequence-int-) | Initializes a new instance of the Sequence class with specified state id. |
| [Sequence(Sequence sequence)](#Sequence-com.aspose.barcode.encoders.aztec.Sequence-) | Copy constructor. |
## Methods

| Method | Description |
| --- | --- |
| [append(Token token)](#append-com.aspose.barcode.encoders.aztec.Token-) | Adds the token to the end of sequence. |
| [clear()](#clear--) | Removes all elements from the sequence. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBitString()](#generateBitString--) | Generates binary string. |
| [getBackTo()](#getBackTo--) |  |
| [getBytesCountForBinaryState()](#getBytesCountForBinaryState--) | Returns last bytes number in Binary state. |
| [getClass()](#getClass--) |  |
| [getCurLen()](#getCurLen--) | Returns current total length in bits. |
| [getState()](#getState--) |  |
| [hashCode()](#hashCode--) |  |
| [latchToBinary()](#latchToBinary--) | Latch to Binary state. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [returnsFromBinary()](#returnsFromBinary--) |  |
| [setBackTo(int value)](#setBackTo-int-) |  |
| [setState(int value)](#setState-int-) |  |
| [toString()](#toString--) |  |
| [tryAppendToDoubleChars(byte value)](#tryAppendToDoubleChars-byte-) | Tries append new char with previous (special case with double chars in Punctuaction state). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Sequence(int state) {#Sequence-int-}
```
public Sequence(int state)
```


Initializes a new instance of the Sequence class with specified state id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| state | int | State id. |

### Sequence(Sequence sequence) {#Sequence-com.aspose.barcode.encoders.aztec.Sequence-}
```
public Sequence(Sequence sequence)
```


Copy constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sequence | [Sequence](../../com.aspose.barcode.encoders.aztec/sequence) | The source sequence. |

### append(Token token) {#append-com.aspose.barcode.encoders.aztec.Token-}
```
public void append(Token token)
```


Adds the token to the end of sequence.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| token | [Token](../../com.aspose.barcode.encoders.aztec/token) | The token to be added to the end of sequence. |

### clear() {#clear--}
```
public void clear()
```


Removes all elements from the sequence.

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
### generateBitString() {#generateBitString--}
```
public String generateBitString()
```


Generates binary string.

**Returns:**
java.lang.String - The binary string.
### getBackTo() {#getBackTo--}
```
public int getBackTo()
```




**Returns:**
int
### getBytesCountForBinaryState() {#getBytesCountForBinaryState--}
```
public int getBytesCountForBinaryState()
```


Returns last bytes number in Binary state.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurLen() {#getCurLen--}
```
public int getCurLen()
```


Returns current total length in bits.

**Returns:**
int
### getState() {#getState--}
```
public int getState()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### latchToBinary() {#latchToBinary--}
```
public void latchToBinary()
```


Latch to Binary state.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### returnsFromBinary() {#returnsFromBinary--}
```
public void returnsFromBinary()
```




### setBackTo(int value) {#setBackTo-int-}
```
public void setBackTo(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setState(int value) {#setState-int-}
```
public void setState(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryAppendToDoubleChars(byte value) {#tryAppendToDoubleChars-byte-}
```
public boolean tryAppendToDoubleChars(byte value)
```


Tries append new char with previous (special case with double chars in Punctuaction state).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The new chars. |

**Returns:**
boolean - Returns true if success, returns false otherwise.
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

