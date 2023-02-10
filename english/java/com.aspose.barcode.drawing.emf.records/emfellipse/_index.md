---
title: EmfEllipse
second_title: Aspose.BarCode for Java API Reference
description: The EMR_ELLIPSE record specifies an ellipse.
type: docs
weight: 12
url: /java/com.aspose.barcode.drawing.emf.records/emfellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfEllipse extends EmfRecord
```

The EMR\_ELLIPSE record specifies an ellipse. The center of the ellipse is the center of the specified bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfEllipse()](#EmfEllipse--) |  |
| [EmfEllipse(System.Drawing.RectangleF rect)](#EmfEllipse-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [EmfEllipse(System.Drawing.Rectangle rect)](#EmfEllipse-com.aspose.ms.System.Drawing.Rectangle-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Box](#Box) | A 128-bit (WMF) RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
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
### EmfEllipse() {#EmfEllipse--}
```
public EmfEllipse()
```


### EmfEllipse(System.Drawing.RectangleF rect) {#EmfEllipse-com.aspose.ms.System.Drawing.RectangleF-}
```
public EmfEllipse(System.Drawing.RectangleF rect)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | com.aspose.ms.System.Drawing.RectangleF |  |

### EmfEllipse(System.Drawing.Rectangle rect) {#EmfEllipse-com.aspose.ms.System.Drawing.Rectangle-}
```
public EmfEllipse(System.Drawing.Rectangle rect)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | com.aspose.ms.System.Drawing.Rectangle |  |

### Box {#Box}
```
public WmfRectL Box
```


A 128-bit (WMF) RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle.

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

