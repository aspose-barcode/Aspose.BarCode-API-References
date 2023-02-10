---
title: EmfCreateBrushIndirect
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.drawing.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord), [com.aspose.barcode.drawing.emf.records.EmfHandleRecord](../../com.aspose.barcode.drawing.emf.records/emfhandlerecord)
```
public class EmfCreateBrushIndirect extends EmfHandleRecord
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) |  |
| [EmfCreateBrushIndirect(int aHandle, System.Drawing.Color color, boolean Transparent)](#EmfCreateBrushIndirect-int-com.aspose.ms.System.Drawing.Color-boolean-) | Size (4 bytes): An unsigned integer that specifies the size in bytes, of this record. |
## Fields

| Field | Description |
| --- | --- |
| [Handle](#Handle) | Specifies Handle of the object |
| [LogBrush](#LogBrush) | A LogBrushEx object (section 2.2.12) that specifies the style, color, and pattern of the logical brush. |
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
### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


### EmfCreateBrushIndirect(int aHandle, System.Drawing.Color color, boolean Transparent) {#EmfCreateBrushIndirect-int-com.aspose.ms.System.Drawing.Color-boolean-}
```
public EmfCreateBrushIndirect(int aHandle, System.Drawing.Color color, boolean Transparent)
```


Size (4 bytes): An unsigned integer that specifies the size in bytes, of this record. This value is 0x00000018.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aHandle | int |  |
| color | com.aspose.ms.System.Drawing.Color |  |
| Transparent | boolean |  |

### Handle {#Handle}
```
public int Handle
```


Specifies Handle of the object

### LogBrush {#LogBrush}
```
public EmfLogBrushEx LogBrush
```


A LogBrushEx object (section 2.2.12) that specifies the style, color, and pattern of the logical brush. The BrushStyle field in this object MUST be BS\_SOLID, BS\_HATCHED, or BS\_NULL.

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

