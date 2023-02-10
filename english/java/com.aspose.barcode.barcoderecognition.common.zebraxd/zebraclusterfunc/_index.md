---
title: ZebraClusterFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 17
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebraclusterfunc/
---
**Inheritance:**
java.lang.Object
```
public class ZebraClusterFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraClusterFunc()](#ZebraClusterFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [clusterSegments(List<ZebraSegment> aSegmentList, ZebraClusterFunc.SegmentClusteringRules aRules, ITerminationCheck aTerminationCheck)](#clusterSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraClusterFunc.SegmentClusteringRules-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Clusters zebra segments into several lists by clustering rules clestered list are converted to the ZebraUnion on the next stage |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [splitSegmentsByReadTypes(List<ZebraSegment> aSegmentList)](#splitSegmentsByReadTypes-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--) | Split ZebraSegment list into multiple by ReadType difference |
| [splitSegmentsByReadTypesAndValues(List<ZebraSegment> aSegmentList)](#splitSegmentsByReadTypesAndValues-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--) | Splits ZebraSegment list into multiple by ReadType and Value difference |
| [splitSegmentsByValues(List<ZebraSegment> aSegmentList)](#splitSegmentsByValues-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--) | Split ZebraSegment list into multiple by Value difference |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraClusterFunc() {#ZebraClusterFunc--}
```
public ZebraClusterFunc()
```


### clusterSegments(List<ZebraSegment> aSegmentList, ZebraClusterFunc.SegmentClusteringRules aRules, ITerminationCheck aTerminationCheck) {#clusterSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraClusterFunc.SegmentClusteringRules-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<List<ZebraSegment>> clusterSegments(List<ZebraSegment> aSegmentList, ZebraClusterFunc.SegmentClusteringRules aRules, ITerminationCheck aTerminationCheck)
```


Clusters zebra segments into several lists by clustering rules clestered list are converted to the ZebraUnion on the next stage

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | processing list |
| aRules | [SegmentClusteringRules](../../com.aspose.barcode.barcoderecognition.common.zebraxd/segmentclusteringrules) | rules for clustering |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[List](../../java.util/list) - clustered lists
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




### splitSegmentsByReadTypes(List<ZebraSegment> aSegmentList) {#splitSegmentsByReadTypes-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--}
```
public static List<List<ZebraSegment>> splitSegmentsByReadTypes(List<ZebraSegment> aSegmentList)
```


Split ZebraSegment list into multiple by ReadType difference

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | processing list |

**Returns:**
[List](../../java.util/list) - split by ReadType lists
### splitSegmentsByReadTypesAndValues(List<ZebraSegment> aSegmentList) {#splitSegmentsByReadTypesAndValues-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--}
```
public static List<List<ZebraSegment>> splitSegmentsByReadTypesAndValues(List<ZebraSegment> aSegmentList)
```


Splits ZebraSegment list into multiple by ReadType and Value difference

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | processing list |

**Returns:**
[List](../../java.util/list) - split by ReadType and Value lists
### splitSegmentsByValues(List<ZebraSegment> aSegmentList) {#splitSegmentsByValues-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--}
```
public static List<List<ZebraSegment>> splitSegmentsByValues(List<ZebraSegment> aSegmentList)
```


Split ZebraSegment list into multiple by Value difference

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | processing list |

**Returns:**
[List](../../java.util/list) - split by Value lists
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

