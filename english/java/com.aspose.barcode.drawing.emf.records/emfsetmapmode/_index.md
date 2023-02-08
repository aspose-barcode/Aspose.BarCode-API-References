---
title: EmfSetMapMode
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 29
url: /java/com.aspose.barcode.drawing.emf.records/emfsetmapmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfSetMapMode extends EmfRecord
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetMapMode()](#EmfSetMapMode--) |  |
| [EmfSetMapMode(long aMapMode)](#EmfSetMapMode-long-) |  |
## Fields

| Field | Description |
| --- | --- |
| [MapMode](#MapMode) | A 32-bit unsigned integer whose definition MUST be in the MapMode enumeration (section 2.1.21). |
| [RecordType](#RecordType) | The type of the record |
| [Size](#Size) | The size of the record |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfSetMapMode() {#EmfSetMapMode--}
```
public EmfSetMapMode()
```


### EmfSetMapMode(long aMapMode) {#EmfSetMapMode-long-}
```
public EmfSetMapMode(long aMapMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aMapMode | long |  |

### MapMode {#MapMode}
```
public long MapMode
```


A 32-bit unsigned integer whose definition MUST be in the MapMode enumeration (section 2.1.21).

--------------------

MM\_TEXT mode allows applications to work in device pixels, whose size varies from device to device. The MM\_HIENGLISH, MM\_HIMETRIC, MM\_LOENGLISH, MM\_LOMETRIC, and MM\_TWIPS modes are useful for applications drawing in physically meaningful units such as inches or millimeters. MM\_ISOTROPIC mode ensures a 1:1 aspect ratio.

### RecordType {#RecordType}
```
public long RecordType
```


The type of the record

### Size {#Size}
```
public int Size
```


The size of the record

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

