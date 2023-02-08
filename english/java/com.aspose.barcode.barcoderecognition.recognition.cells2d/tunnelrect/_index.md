---
title: TunnelRect
second_title: Aspose.BarCode for Java API Reference
description: Rectangle of the tunnels.
type: docs
weight: 17
url: /java/com.aspose.barcode.barcoderecognition.recognition.cells2d/tunnelrect/
---
**Inheritance:**
java.lang.Object
```
public class TunnelRect
```

Rectangle of the tunnels.
## Constructors

| Constructor | Description |
| --- | --- |
| [TunnelRect(int wayStart, int wayEnd, int cutFrom, int cutTo, boolean isCol)](#TunnelRect-int-int-int-int-boolean-) | Initializes a new instance of the TunnelRect class by start and end coordinates |
| [TunnelRect()](#TunnelRect--) |  |
## Fields

| Field | Description |
| --- | --- |
| [CutFrom](#CutFrom) | Coordinate to cut from |
| [CutTo](#CutTo) | Coordinate to end cut |
| [IsCol](#IsCol) | If true - research column, if false - research rows |
| [WayEnd](#WayEnd) | Way end |
| [WayStart](#WayStart) | Way start |
## Methods

| Method | Description |
| --- | --- |
| [columnTunnel(RectangleVertexes vertexes)](#columnTunnel-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-) | Creates a new instance of the TunnelRect class by region vertexes for columns researching |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rowTunnel(RectangleVertexes vertexes)](#rowTunnel-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-) | Creates a new instance of the TunnelRect class by region vertexes for rows researching |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TunnelRect(int wayStart, int wayEnd, int cutFrom, int cutTo, boolean isCol) {#TunnelRect-int-int-int-int-boolean-}
```
public TunnelRect(int wayStart, int wayEnd, int cutFrom, int cutTo, boolean isCol)
```


Initializes a new instance of the TunnelRect class by start and end coordinates

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wayStart | int | Way start |
| wayEnd | int | Way end |
| cutFrom | int | Coordinate to cut from |
| cutTo | int | Coordinate to end cut |
| isCol | boolean | If true - research column, if false - research rows |

### TunnelRect() {#TunnelRect--}
```
public TunnelRect()
```


### CutFrom {#CutFrom}
```
public int CutFrom
```


Coordinate to cut from

### CutTo {#CutTo}
```
public int CutTo
```


Coordinate to end cut

### IsCol {#IsCol}
```
public boolean IsCol
```


If true - research column, if false - research rows

### WayEnd {#WayEnd}
```
public int WayEnd
```


Way end

### WayStart {#WayStart}
```
public int WayStart
```


Way start

### columnTunnel(RectangleVertexes vertexes) {#columnTunnel-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-}
```
public static TunnelRect columnTunnel(RectangleVertexes vertexes)
```


Creates a new instance of the TunnelRect class by region vertexes for columns researching

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Region vertexes |

**Returns:**
[TunnelRect](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/tunnelrect) - Created TunnelRect
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




### rowTunnel(RectangleVertexes vertexes) {#rowTunnel-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-}
```
public static TunnelRect rowTunnel(RectangleVertexes vertexes)
```


Creates a new instance of the TunnelRect class by region vertexes for rows researching

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) | Region vertexes |

**Returns:**
[TunnelRect](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/tunnelrect) - Created TunnelRect
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

