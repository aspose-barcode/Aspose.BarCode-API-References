---
title: Token
second_title: Aspose.BarCode for Java API Reference
description: Represents one Aztec code.
type: docs
weight: 15
url: /java/com.aspose.barcode.encoders.aztec/token/
---
**Inheritance:**
java.lang.Object
```
public class Token
```

Represents one Aztec code.
## Constructors

| Constructor | Description |
| --- | --- |
| [Token(int value, int numberBits, String info)](#Token-int-int-java.lang.String-) | Initializes a new instance of the Token class with specified value, numder of bits and human text. |
## Fields

| Field | Description |
| --- | --- |
| [Info](#Info) | Human version of this code. |
| [NumberBits](#NumberBits) | Number of bits in this code. |
| [Value](#Value) | Value of this code. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toBitString()](#toBitString--) | Generates binary string. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Token(int value, int numberBits, String info) {#Token-int-int-java.lang.String-}
```
public Token(int value, int numberBits, String info)
```


Initializes a new instance of the Token class with specified value, numder of bits and human text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value Aztec code. |
| numberBits | int | The number bits of code. |
| info | java.lang.String | The human text. |

### Info {#Info}
```
public final String Info
```


Human version of this code.

### NumberBits {#NumberBits}
```
public final int NumberBits
```


Number of bits in this code.

### Value {#Value}
```
public final int Value
```


Value of this code.

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




### toBitString() {#toBitString--}
```
public String toBitString()
```


Generates binary string.

**Returns:**
java.lang.String - The binary string.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - The current human text.
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

