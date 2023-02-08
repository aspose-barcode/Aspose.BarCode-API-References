---
title: PolyLine
second_title: Aspose.BarCode for Java API Reference
description: Contour that consists of polylines
type: docs
weight: 18
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells/polyline/
---
**Inheritance:**
java.lang.Object
```
public class PolyLine
```

Contour that consists of polylines
## Constructors

| Constructor | Description |
| --- | --- |
| [PolyLine(List<System.Drawing.Point> lineNodes, Dictionary<Integer,LineSegment> segmentsMap, int number)](#PolyLine-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.java.Dictionary-java.lang.Integer-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.LineSegment--int-) | Initializes a new instance of the PolyLine class. |
## Fields

| Field | Description |
| --- | --- |
| [AllPoints](#AllPoints) | Full line |
| [Nodes](#Nodes) | Nodes (ordered list) |
| [Number](#Number) | Number of this polyline (colum or row number) |
| [SegmentsMap](#SegmentsMap) | Node map. |
## Methods

| Method | Description |
| --- | --- |
| [calculatePolyLine(List<System.Drawing.Point> lineNodes)](#calculatePolyLine-java.util.List-com.aspose.ms.System.Drawing.Point--) | Calculates a polyline from line nodes |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolyLine(List<System.Drawing.Point> lineNodes, Dictionary<Integer,LineSegment> segmentsMap, int number) {#PolyLine-java.util.List-com.aspose.ms.System.Drawing.Point--com.aspose.barcode.java.Dictionary-java.lang.Integer-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.LineSegment--int-}
```
public PolyLine(List<System.Drawing.Point> lineNodes, Dictionary<Integer,LineSegment> segmentsMap, int number)
```


Initializes a new instance of the PolyLine class. Calculates FullLine by the nodes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineNodes | java.util.List<com.aspose.ms.System.Drawing.Point> | Nodes |
| segmentsMap | com.aspose.barcode.java.Dictionary<java.lang.Integer,com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.LineSegment> |  |
| number | int | A number |

### AllPoints {#AllPoints}
```
public PointList AllPoints
```


Full line

### Nodes {#Nodes}
```
public List<System.Drawing.Point> Nodes
```


Nodes (ordered list)

### Number {#Number}
```
public int Number
```


Number of this polyline (colum or row number)

### SegmentsMap {#SegmentsMap}
```
public Dictionary<Integer,LineSegment> SegmentsMap
```


Node map. Key is the node index. Value is the joined segment

### calculatePolyLine(List<System.Drawing.Point> lineNodes) {#calculatePolyLine-java.util.List-com.aspose.ms.System.Drawing.Point--}
```
public static PointList calculatePolyLine(List<System.Drawing.Point> lineNodes)
```


Calculates a polyline from line nodes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineNodes | java.util.List<com.aspose.ms.System.Drawing.Point> | Line nodes |

**Returns:**
[PointList](../../com.aspose.barcode.common.generic.list/pointlist) - All points of the polyline
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

