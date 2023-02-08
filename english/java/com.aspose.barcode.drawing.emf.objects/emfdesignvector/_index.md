---
title: EmfDesignVector
second_title: Aspose.BarCode for Java API Reference
description: EmfDesignVector class
type: docs
weight: 10
url: /java/com.aspose.barcode.drawing.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.objects.XmfObject
```
public class EmfDesignVector extends XmfObject
```

EmfDesignVector class
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Fields

| Field | Description |
| --- | --- |
| [NumAxes](#NumAxes) | A 32-bit unsigned integer that specifies the number of elements in the Values array. |
| [Signature](#Signature) | A 32-bit unsigned integer that MUST be set to the value 0x08007664. |
| [Values](#Values) | An optional array of 32-bit signed integers that specify the values of the font axes of a multiple master, OpenType font. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSize()](#getSize--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### NumAxes {#NumAxes}
```
public long NumAxes
```


A 32-bit unsigned integer that specifies the number of elements in the Values array. It MUST be in the range 0 to 16, inclusive

### Signature {#Signature}
```
public long Signature
```


A 32-bit unsigned integer that MUST be set to the value 0x08007664.

### Values {#Values}
```
public int[] Values
```


An optional array of 32-bit signed integers that specify the values of the font axes of a multiple master, OpenType font. The maximum number of values in the array is 16.

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
### getSize() {#getSize--}
```
public int getSize()
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

