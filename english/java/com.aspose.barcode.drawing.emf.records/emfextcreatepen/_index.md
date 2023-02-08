---
title: EmfExtCreatePen
second_title: Aspose.BarCode for Java API Reference
description: EMR_EXTCREATEPEN Record
type: docs
weight: 15
url: /java/com.aspose.barcode.drawing.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord), [com.aspose.barcode.drawing.emf.records.EmfHandleRecord](../../com.aspose.barcode.drawing.emf.records/emfhandlerecord)
```
public class EmfExtCreatePen extends EmfHandleRecord
```

EMR\_EXTCREATEPEN Record
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfExtCreatePen()](#EmfExtCreatePen--) |  |
| [EmfExtCreatePen(int aHandle, System.Drawing.Color Color)](#EmfExtCreatePen-int-com.aspose.ms.System.Drawing.Color-) |  |
| [EmfExtCreatePen(int aHandle, System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle)](#EmfExtCreatePen-int-com.aspose.ms.System.Drawing.Color-int-com.aspose.barcode.drawing.PenDashStyle-) |  |
## Fields

| Field | Description |
| --- | --- |
| [BitmapBuffer](#BitmapBuffer) | An optional buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). |
| [CbBits](#CbBits) | 32-bit unsigned integer that specifies the size of the DIB bits, if the record contains a DIB. |
| [CbBmi](#CbBmi) | A 32-bit unsigned integer that specifies the size of the DIB header, if the record contains a DIB. |
| [Elp](#Elp) | A LogPenEx object (section 2.2.20) that specifies an extended logical pen with attributes including an optional line style array. |
| [Handle](#Handle) | Specifies Handle of the object |
| [OffBits](#OffBits) | A 32-bit unsigned integer that specifies the offset from the start of this record to the DIB bits, if the record contains a DIB. |
| [OffBmi](#OffBmi) | 32-bit unsigned integer that specifies the offset from the start of this record to the DIB header, if the record contains a DIB. |
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
### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


### EmfExtCreatePen(int aHandle, System.Drawing.Color Color) {#EmfExtCreatePen-int-com.aspose.ms.System.Drawing.Color-}
```
public EmfExtCreatePen(int aHandle, System.Drawing.Color Color)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aHandle | int |  |
| Color | com.aspose.ms.System.Drawing.Color |  |

### EmfExtCreatePen(int aHandle, System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle) {#EmfExtCreatePen-int-com.aspose.ms.System.Drawing.Color-int-com.aspose.barcode.drawing.PenDashStyle-}
```
public EmfExtCreatePen(int aHandle, System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aHandle | int |  |
| Color | com.aspose.ms.System.Drawing.Color |  |
| Thickness | int |  |
| DashStyle | [PenDashStyle](../../com.aspose.barcode.drawing/pendashstyle) |  |

### BitmapBuffer {#BitmapBuffer}
```
public byte[] BitmapBuffer
```


An optional buffer containing a packed DIB in the form of a WMF DeviceIndependentBitmap object ([MS-WMF] section 2.2.2.9). It is not required to be contiguous with the fixed portion of the EMR\_EXTCREATEPEN record public WmfDeviceIndependentBitmap BitmapBuffer;

### CbBits {#CbBits}
```
public long CbBits
```


32-bit unsigned integer that specifies the size of the DIB bits, if the record contains a DIB.

### CbBmi {#CbBmi}
```
public long CbBmi
```


A 32-bit unsigned integer that specifies the size of the DIB header, if the record contains a DIB.

### Elp {#Elp}
```
public EmfLogPenEx Elp
```


A LogPenEx object (section 2.2.20) that specifies an extended logical pen with attributes including an optional line style array.

### Handle {#Handle}
```
public int Handle
```


Specifies Handle of the object

### OffBits {#OffBits}
```
public long OffBits
```


A 32-bit unsigned integer that specifies the offset from the start of this record to the DIB bits, if the record contains a DIB.

### OffBmi {#OffBmi}
```
public long OffBmi
```


32-bit unsigned integer that specifies the offset from the start of this record to the DIB header, if the record contains a DIB.

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

