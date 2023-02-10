---
title: ZebraUnionIntersectHelper
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 31
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunionintersecthelper/
---
**Inheritance:**
java.lang.Object
```
public class ZebraUnionIntersectHelper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraUnionIntersectHelper()](#ZebraUnionIntersectHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [excludeIntersectedUnionsFromList(List<ZebraUnion> aResultsList, IIntersectZebraUnionSelector Selector, ITerminationCheck aTerminationCheck)](#excludeIntersectedUnionsFromList-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.barcode.barcoderecognition.common.zebraxd.IIntersectZebraUnionSelector-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Filters by Selector aProceedList intersected ZebraUnions |
| [excludeIntersectedUnionsFromList(List<ZebraUnion> aResultsList, IIntersectZebraUnionSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck)](#excludeIntersectedUnionsFromList-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.barcode.barcoderecognition.common.zebraxd.IIntersectZebraUnionSelector-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Filters by Selector aResultsList intersected ZebraUnions |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraUnionIntersectHelper() {#ZebraUnionIntersectHelper--}
```
public ZebraUnionIntersectHelper()
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
### excludeIntersectedUnionsFromList(List<ZebraUnion> aResultsList, IIntersectZebraUnionSelector Selector, ITerminationCheck aTerminationCheck) {#excludeIntersectedUnionsFromList-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.barcode.barcoderecognition.common.zebraxd.IIntersectZebraUnionSelector-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<ZebraUnion> excludeIntersectedUnionsFromList(List<ZebraUnion> aResultsList, IIntersectZebraUnionSelector Selector, ITerminationCheck aTerminationCheck)
```


Filters by Selector aProceedList intersected ZebraUnions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResultsList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion> | Proceed objects with bounding quads |
| Selector | [IIntersectZebraUnionSelector](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iintersectzebraunionselector) | Selector which can select one or more object from intersected list |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[List](../../java.util/list) - filtered intersected ZebraUnions
### excludeIntersectedUnionsFromList(List<ZebraUnion> aResultsList, IIntersectZebraUnionSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck) {#excludeIntersectedUnionsFromList-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.barcode.barcoderecognition.common.zebraxd.IIntersectZebraUnionSelector-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<ZebraUnion> excludeIntersectedUnionsFromList(List<ZebraUnion> aResultsList, IIntersectZebraUnionSelector Selector, double aMaxDist, ITerminationCheck aTerminationCheck)
```


Filters by Selector aResultsList intersected ZebraUnions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aResultsList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion> | Proceed objects with bounding quads |
| Selector | [IIntersectZebraUnionSelector](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iintersectzebraunionselector) | Selector which can select one or more object from intersected list |
| aMaxDist | double | maximal distance from quad to quad, when distance more then 0, can intersect "nearest" quads |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[List](../../java.util/list) - filtered intersected ZebraUnions
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

