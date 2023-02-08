---
title: EmfPolygon
second_title: Aspose.BarCode for Java API Reference
description: The EMR_POLYGON record specifies a polygon consisting of two or more vertexes connected by  straight lines.
type: docs
weight: 22
url: /java/com.aspose.barcode.drawing.emf.records/emfpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfPolygon extends EmfRecord
```

The EMR\_POLYGON record specifies a polygon consisting of two or more vertexes connected by straight lines.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPolygon()](#EmfPolygon--) |  |
| [EmfPolygon(System.Drawing.Point[] points)](#EmfPolygon-com.aspose.ms.System.Drawing.Point---) |  |
| [EmfPolygon(System.Drawing.PointF[] points)](#EmfPolygon-com.aspose.ms.System.Drawing.PointF---) |  |
## Fields

| Field | Description |
| --- | --- |
| [APoints](#APoints) | A Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the vertexes of the polygon in logical units. |
| [Bounds](#Bounds) | A 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [Count](#Count) | A 32-bit unsigned integer that specifies the number of points in the aPoints array. |
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
### EmfPolygon() {#EmfPolygon--}
```
public EmfPolygon()
```


### EmfPolygon(System.Drawing.Point[] points) {#EmfPolygon-com.aspose.ms.System.Drawing.Point---}
```
public EmfPolygon(System.Drawing.Point[] points)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | com.aspose.ms.System.Drawing.Point[] |  |

### EmfPolygon(System.Drawing.PointF[] points) {#EmfPolygon-com.aspose.ms.System.Drawing.PointF---}
```
public EmfPolygon(System.Drawing.PointF[] points)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | com.aspose.ms.System.Drawing.PointF[] |  |

### APoints {#APoints}
```
public WmfPointL[] APoints
```


A Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the vertexes of the polygon in logical units.

### Bounds {#Bounds}
```
public WmfRectL Bounds
```


A 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units.

### Count {#Count}
```
public long Count
```


A 32-bit unsigned integer that specifies the number of points in the aPoints array.

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

