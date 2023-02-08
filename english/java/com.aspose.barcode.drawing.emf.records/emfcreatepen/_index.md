---
title: EmfCreatePen
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.drawing.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord), [com.aspose.barcode.drawing.emf.records.EmfHandleRecord](../../com.aspose.barcode.drawing.emf.records/emfhandlerecord)
```
public class EmfCreatePen extends EmfHandleRecord
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCreatePen()](#EmfCreatePen--) |  |
| [EmfCreatePen(int aHandle, System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle)](#EmfCreatePen-int-com.aspose.ms.System.Drawing.Color-int-com.aspose.barcode.drawing.PenDashStyle-) | Size (4 bytes): An unsigned integer that specifies the size in bytes, of this record. |
## Fields

| Field | Description |
| --- | --- |
| [Handle](#Handle) | Specifies Handle of the object |
| [LogPen](#LogPen) | A LogPen object (section 2.2.19) that specifies the style, width, and color of the logical pen. |
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
### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


### EmfCreatePen(int aHandle, System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle) {#EmfCreatePen-int-com.aspose.ms.System.Drawing.Color-int-com.aspose.barcode.drawing.PenDashStyle-}
```
public EmfCreatePen(int aHandle, System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle)
```


Size (4 bytes): An unsigned integer that specifies the size in bytes, of this record. This value is 0x0000001C.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aHandle | int |  |
| Color | com.aspose.ms.System.Drawing.Color |  |
| Thickness | int |  |
| DashStyle | [PenDashStyle](../../com.aspose.barcode.drawing/pendashstyle) |  |

### Handle {#Handle}
```
public int Handle
```


Specifies Handle of the object

### LogPen {#LogPen}
```
public EmfLogPen LogPen
```


A LogPen object (section 2.2.19) that specifies the style, width, and color of the logical pen.

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

