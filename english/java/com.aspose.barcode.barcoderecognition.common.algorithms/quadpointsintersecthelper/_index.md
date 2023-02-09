---
title: QuadPointsIntersectHelper
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 45
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/quadpointsintersecthelper/
---
**Inheritance:**
java.lang.Object
```
public class QuadPointsIntersectHelper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [QuadPointsIntersectHelper()](#QuadPointsIntersectHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [excludeIntersectedUnionsFromList(System.Collections.Generic.List<IQuadPoints> aResultsList, IIntersectQuadPointsSelector Selector, ITerminationCheck aTerminationCheck)](#excludeIntersectedUnionsFromList-com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.barcoderecognition.common.algorithms.IQuadPoints--com.aspose.barcode.barcoderecognition.common.algorithms.IIntersectQuadPointsSelector-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [excludeIntersectedUnionsFromList(List<IQuadPoints> aProceedList, IIntersectQuadPointsSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck)](#excludeIntersectedUnionsFromList-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.IQuadPoints--com.aspose.barcode.barcoderecognition.common.algorithms.IIntersectQuadPointsSelector-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Filters by Selector aProceedList objects with bounding quads from intersected quads |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QuadPointsIntersectHelper() {#QuadPointsIntersectHelper--}
```
public QuadPointsIntersectHelper()
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
### excludeIntersectedUnionsFromList(System.Collections.Generic.List<IQuadPoints> aResultsList, IIntersectQuadPointsSelector Selector, ITerminationCheck aTerminationCheck) {#excludeIntersectedUnionsFromList-com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.barcoderecognition.common.algorithms.IQuadPoints--com.aspose.barcode.barcoderecognition.common.algorithms.IIntersectQuadPointsSelector-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static System.Collections.Generic.List<IQuadPoints> excludeIntersectedUnionsFromList(System.Collections.Generic.List<IQuadPoints> aResultsList, IIntersectQuadPointsSelector Selector, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResultsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.common.algorithms.IQuadPoints> |  |
| Selector | [IIntersectQuadPointsSelector](../../com.aspose.barcode.barcoderecognition.common.algorithms/iintersectquadpointsselector) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
### excludeIntersectedUnionsFromList(List<IQuadPoints> aProceedList, IIntersectQuadPointsSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck) {#excludeIntersectedUnionsFromList-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.IQuadPoints--com.aspose.barcode.barcoderecognition.common.algorithms.IIntersectQuadPointsSelector-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static System.Collections.Generic.List<IQuadPoints> excludeIntersectedUnionsFromList(List<IQuadPoints> aProceedList, IIntersectQuadPointsSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck)
```


Filters by Selector aProceedList objects with bounding quads from intersected quads

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aProceedList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.IQuadPoints> | Proceed objects with bounding quads |
| Selector | [IIntersectQuadPointsSelector](../../com.aspose.barcode.barcoderecognition.common.algorithms/iintersectquadpointsselector) | Selector which can select one or more object from intersected list |
| aMaxDist | double | maximal distance from quad to quad, when distance more then 0, can intersect "nearest" quads |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - filtered by Selector quads from intersected quads
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
