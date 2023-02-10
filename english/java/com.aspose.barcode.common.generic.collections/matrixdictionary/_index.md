---
title: MatrixDictionary
second_title: Aspose.BarCode for Java API Reference
description: Dictionary with 2 keys
type: docs
weight: 10
url: /java/com.aspose.barcode.common.generic.collections/matrixdictionary/
---
**Inheritance:**
java.lang.Object
```
public class MatrixDictionary<TData>
```

Dictionary with 2 keys

 TData : Type of a value
## Constructors

| Constructor | Description |
| --- | --- |
| [MatrixDictionary()](#MatrixDictionary--) |  |
## Methods

| Method | Description |
| --- | --- |
| [containsKey(int keyA, int keyB)](#containsKey-int-int-) | Determines whether the MatrixDictionary contains the specified complex key. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(int keyA, int keyB, TData value)](#setValue-int-int-TData-) | Set value. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MatrixDictionary() {#MatrixDictionary--}
```
public MatrixDictionary()
```


### containsKey(int keyA, int keyB) {#containsKey-int-int-}
```
public boolean containsKey(int keyA, int keyB)
```


Determines whether the MatrixDictionary contains the specified complex key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyA | int | The KeyA to locate in MatrixDictionary |
| keyB | int | The KeyB to locate in MatrixDictionary |

**Returns:**
boolean - true if the MatrixDictionary contains an element with the specified key; otherwise, false.
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




### setValue(int keyA, int keyB, TData value) {#setValue-int-int-TData-}
```
public void setValue(int keyA, int keyB, TData value)
```


Set value. The exception is not thrown if value is exist.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyA | int |  |
| keyB | int |  |
| value | TData |  |

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

