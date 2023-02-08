---
title: LineExtractor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 36
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/lineextractor/
---
**Inheritance:**
java.lang.Object
```
public class LineExtractor
```
## Constructors

| Constructor | Description |
| --- | --- |
| [LineExtractor()](#LineExtractor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractLinesFromChain(List<ShortPoint> aChain, int MinDistFromDominantRearrange, int MinDistFromDominantCollapsed, double aMaxTriangleHeigthToCollapse)](#extractLinesFromChain-java.util.List-com.aspose.barcode.common.types.ShortPoint--int-int-double-) |  |
| [extractLinesFromChains(List<List<ShortPoint>> aChainList, ITerminationCheck aTerminationCheck)](#extractLinesFromChains-java.util.List-java.util.List-com.aspose.barcode.common.types.ShortPoint---com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [extractLinesFromChains(List<List<ShortPoint>> aChainList, int MinDistFromDominantRearrange, int MinDistFromDominantCollapsed, double aMaxTriangleHeigthToCollapse, ITerminationCheck aTerminationCheck)](#extractLinesFromChains-java.util.List-java.util.List-com.aspose.barcode.common.types.ShortPoint---int-int-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [filterLines(List<ExtractedLine> aLineList, int aMinChain, double aMinSize)](#filterLines-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLine--int-double-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LineExtractor() {#LineExtractor--}
```
public LineExtractor()
```


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
### extractLinesFromChain(List<ShortPoint> aChain, int MinDistFromDominantRearrange, int MinDistFromDominantCollapsed, double aMaxTriangleHeigthToCollapse) {#extractLinesFromChain-java.util.List-com.aspose.barcode.common.types.ShortPoint--int-int-double-}
```
public static List<ExtractedLine> extractLinesFromChain(List<ShortPoint> aChain, int MinDistFromDominantRearrange, int MinDistFromDominantCollapsed, double aMaxTriangleHeigthToCollapse)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aChain | java.util.List<com.aspose.barcode.common.types.ShortPoint> |  |
| MinDistFromDominantRearrange | int |  |
| MinDistFromDominantCollapsed | int |  |
| aMaxTriangleHeigthToCollapse | double |  |

**Returns:**
[List](../../java.util/list)
### extractLinesFromChains(List<List<ShortPoint>> aChainList, ITerminationCheck aTerminationCheck) {#extractLinesFromChains-java.util.List-java.util.List-com.aspose.barcode.common.types.ShortPoint---com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<ExtractedLine> extractLinesFromChains(List<List<ShortPoint>> aChainList, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aChainList | java.util.List<java.util.List<com.aspose.barcode.common.types.ShortPoint>> |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
### extractLinesFromChains(List<List<ShortPoint>> aChainList, int MinDistFromDominantRearrange, int MinDistFromDominantCollapsed, double aMaxTriangleHeigthToCollapse, ITerminationCheck aTerminationCheck) {#extractLinesFromChains-java.util.List-java.util.List-com.aspose.barcode.common.types.ShortPoint---int-int-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<ExtractedLine> extractLinesFromChains(List<List<ShortPoint>> aChainList, int MinDistFromDominantRearrange, int MinDistFromDominantCollapsed, double aMaxTriangleHeigthToCollapse, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aChainList | java.util.List<java.util.List<com.aspose.barcode.common.types.ShortPoint>> |  |
| MinDistFromDominantRearrange | int |  |
| MinDistFromDominantCollapsed | int |  |
| aMaxTriangleHeigthToCollapse | double |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
### filterLines(List<ExtractedLine> aLineList, int aMinChain, double aMinSize) {#filterLines-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLine--int-double-}
```
public static List<ExtractedLine> filterLines(List<ExtractedLine> aLineList, int aMinChain, double aMinSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLineList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLine> |  |
| aMinChain | int |  |
| aMinSize | double |  |

**Returns:**
[List](../../java.util/list)
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

