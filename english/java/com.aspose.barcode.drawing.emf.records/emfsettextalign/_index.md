---
title: EmfSetTextAlign
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 32
url: /java/com.aspose.barcode.drawing.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfSetTextAlign extends EmfRecord
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetTextAlign()](#EmfSetTextAlign--) |  |
| [EmfSetTextAlign(long aTextAlignmentMode)](#EmfSetTextAlign-long-) |  |
## Fields

| Field | Description |
| --- | --- |
| [RecordType](#RecordType) | The type of the record |
| [Size](#Size) | The size of the record |
| [TextAlignmentMode](#TextAlignmentMode) | TextAlignmentMode Flags specify the relationship between a reference point and a bounding rectangle, for text alignment. |
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
### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


### EmfSetTextAlign(long aTextAlignmentMode) {#EmfSetTextAlign-long-}
```
public EmfSetTextAlign(long aTextAlignmentMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aTextAlignmentMode | long |  |

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

### TextAlignmentMode {#TextAlignmentMode}
```
public long TextAlignmentMode
```


TextAlignmentMode Flags specify the relationship between a reference point and a bounding rectangle, for text alignment. These flags can be combined to specify multiple options, with the restriction that only one flag can be chosen that alters the drawing position in the playback device context. Horizontal text alignment is performed when the font has a horizontal default baseline.

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

