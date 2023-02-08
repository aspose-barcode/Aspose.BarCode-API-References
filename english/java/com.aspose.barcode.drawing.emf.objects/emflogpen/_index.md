---
title: EmfLogPen
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 18
url: /java/com.aspose.barcode.drawing.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.objects.XmfObject, com.aspose.barcode.drawing.emf.objects.EmfLogPenBase
```
public class EmfLogPen extends EmfLogPenBase
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
| [EmfLogPen(System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle)](#EmfLogPen-com.aspose.ms.System.Drawing.Color-int-com.aspose.barcode.drawing.PenDashStyle-) |  |
## Fields

| Field | Description |
| --- | --- |
| [ColorRef](#ColorRef) | A WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pen color value. |
| [PenStyle](#PenStyle) | A 32-bit unsigned integer that specifies the PenStyle. |
| [Width](#Width) | A WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the width of the pen by the value of its x field. |
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
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### EmfLogPen(System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle) {#EmfLogPen-com.aspose.ms.System.Drawing.Color-int-com.aspose.barcode.drawing.PenDashStyle-}
```
public EmfLogPen(System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Color | com.aspose.ms.System.Drawing.Color |  |
| Thickness | int |  |
| DashStyle | [PenDashStyle](../../com.aspose.barcode.drawing/pendashstyle) |  |

### ColorRef {#ColorRef}
```
public WmfColorRef ColorRef
```


A WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the pen color value.

### PenStyle {#PenStyle}
```
public long PenStyle
```


A 32-bit unsigned integer that specifies the PenStyle. The value MUST be defined from the PenStyle enumeration table, specified in section 2.1.25.

### Width {#Width}
```
public WmfPointL Width
```


A WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the width of the pen by the value of its x field. The value of its y field MUST be ignored.

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

