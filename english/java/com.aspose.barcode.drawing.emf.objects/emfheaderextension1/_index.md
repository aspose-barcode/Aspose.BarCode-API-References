---
title: EmfHeaderExtension1
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.drawing.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.objects.XmfObject
```
public class EmfHeaderExtension1 extends XmfObject
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Fields

| Field | Description |
| --- | --- |
| [BOpenGL](#BOpenGL) | A 32-bit unsigned integer that indicates whether OpenGL commands are present in the metafile. |
| [CbPixelFormat](#CbPixelFormat) | A 32-bit unsigned integer that specifies the size of the PixelFormatDescriptor object. |
| [OffPixelFormat](#OffPixelFormat) | A 32-bit unsigned integer that specifies the offset to the PixelFormatDescriptor object. |
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
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### BOpenGL {#BOpenGL}
```
public long BOpenGL
```


A 32-bit unsigned integer that indicates whether OpenGL commands are present in the metafile. 0x00000000 OpenGL records are not present in the metafile. 0x00000001 OpenGL records are present in the metafile.

### CbPixelFormat {#CbPixelFormat}
```
public long CbPixelFormat
```


A 32-bit unsigned integer that specifies the size of the PixelFormatDescriptor object. This MUST be 0x00000000 if no pixel format is set

### OffPixelFormat {#OffPixelFormat}
```
public long OffPixelFormat
```


A 32-bit unsigned integer that specifies the offset to the PixelFormatDescriptor object. This MUST be 0x00000000 if no pixel format is set.

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

