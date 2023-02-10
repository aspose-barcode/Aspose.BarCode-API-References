---
title: ExtLineClusteringData
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 15
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/extlineclusteringdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.common.areatrees.ICentralPoint](../../com.aspose.barcode.barcoderecognition.common.areatrees/icentralpoint)
```
public class ExtLineClusteringData implements ICentralPoint
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ExtLineClusteringData(ExtractedLine aLine, boolean aIsFirstPoint)](#ExtLineClusteringData-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLine-boolean-) |  |
## Fields

| Field | Description |
| --- | --- |
| [IsFirstPoint](#IsFirstPoint) |  |
| [Line](#Line) |  |
## Methods

| Method | Description |
| --- | --- |
| [createClusteringFromLines(List<ExtractedLine> aLines)](#createClusteringFromLines-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLine--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractUniqueLinesFromData(List<ExtLineClusteringData> aList)](#extractUniqueLinesFromData-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.ExtLineClusteringData--) |  |
| [getCentralPoint()](#getCentralPoint--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtLineClusteringData(ExtractedLine aLine, boolean aIsFirstPoint) {#ExtLineClusteringData-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLine-boolean-}
```
public ExtLineClusteringData(ExtractedLine aLine, boolean aIsFirstPoint)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLine | [ExtractedLine](../../com.aspose.barcode.barcoderecognition.common.algorithms/extractedline) |  |
| aIsFirstPoint | boolean |  |

### IsFirstPoint {#IsFirstPoint}
```
public boolean IsFirstPoint
```


### Line {#Line}
```
public ExtractedLine Line
```


### createClusteringFromLines(List<ExtractedLine> aLines) {#createClusteringFromLines-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLine--}
```
public static List<ExtLineClusteringData> createClusteringFromLines(List<ExtractedLine> aLines)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLines | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLine> |  |

**Returns:**
[List](../../java.util/list)
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
### extractUniqueLinesFromData(List<ExtLineClusteringData> aList) {#extractUniqueLinesFromData-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.ExtLineClusteringData--}
```
public static List<ExtractedLine> extractUniqueLinesFromData(List<ExtLineClusteringData> aList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.ExtLineClusteringData> |  |

**Returns:**
[List](../../java.util/list)
### getCentralPoint() {#getCentralPoint--}
```
public final System.Drawing.Point getCentralPoint()
```




**Returns:**
com.aspose.ms.System.Drawing.Point
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

