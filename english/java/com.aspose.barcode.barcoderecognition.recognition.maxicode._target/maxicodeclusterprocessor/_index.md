---
title: MaxiCodeClusterProcessor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.maxicode._target/maxicodeclusterprocessor/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.common.zebraxd.ClusterZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/clusterzebraprocessor)
```
public class MaxiCodeClusterProcessor extends ClusterZebraProcessor
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MaxiCodeClusterProcessor(ITerminationCheck aTerminationCheck, ZebraClusterFunc.SegmentClusteringRules aRules)](#MaxiCodeClusterProcessor-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraClusterFunc.SegmentClusteringRules-) |  |
| [MaxiCodeClusterProcessor(MaxiCodeClusterProcessor aProcessor)](#MaxiCodeClusterProcessor-com.aspose.barcode.barcoderecognition.recognition.maxicode.-target.MaxiCodeClusterProcessor-) |  |
## Methods

| Method | Description |
| --- | --- |
| [clusterZebraSegments(List<ZebraSegment> aSegmentsList)](#clusterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--) |  |
| [createZebraUnionIfCorrect(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap)](#createZebraUnionIfCorrect-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getProcessorCopy()](#getProcessorCopy--) |  |
| [getTerminatioCheck()](#getTerminatioCheck--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [splitZebraSegmentsByBasicParams(List<ZebraSegment> aSegmentsList)](#splitZebraSegmentsByBasicParams-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeClusterProcessor(ITerminationCheck aTerminationCheck, ZebraClusterFunc.SegmentClusteringRules aRules) {#MaxiCodeClusterProcessor-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraClusterFunc.SegmentClusteringRules-}
```
public MaxiCodeClusterProcessor(ITerminationCheck aTerminationCheck, ZebraClusterFunc.SegmentClusteringRules aRules)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |
| aRules | [SegmentClusteringRules](../../com.aspose.barcode.barcoderecognition.common.zebraxd/segmentclusteringrules) |  |

### MaxiCodeClusterProcessor(MaxiCodeClusterProcessor aProcessor) {#MaxiCodeClusterProcessor-com.aspose.barcode.barcoderecognition.recognition.maxicode.-target.MaxiCodeClusterProcessor-}
```
public MaxiCodeClusterProcessor(MaxiCodeClusterProcessor aProcessor)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aProcessor | [MaxiCodeClusterProcessor](../../com.aspose.barcode.barcoderecognition.recognition.maxicode._target/maxicodeclusterprocessor) |  |

### clusterZebraSegments(List<ZebraSegment> aSegmentsList) {#clusterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--}
```
public List<List<ZebraSegment>> clusterZebraSegments(List<ZebraSegment> aSegmentsList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentsList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |

**Returns:**
[List](../../java.util/list)
### createZebraUnionIfCorrect(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap) {#createZebraUnionIfCorrect-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public ZebraUnion createZebraUnionIfCorrect(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnionSegments | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion)
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
### getProcessorCopy() {#getProcessorCopy--}
```
public IClusterZebraProcessor getProcessorCopy()
```




**Returns:**
[IClusterZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iclusterzebraprocessor)
### getTerminatioCheck() {#getTerminatioCheck--}
```
public ITerminationCheck getTerminatioCheck()
```




**Returns:**
[ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck)
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




### splitZebraSegmentsByBasicParams(List<ZebraSegment> aSegmentsList) {#splitZebraSegmentsByBasicParams-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--}
```
public List<List<ZebraSegment>> splitZebraSegmentsByBasicParams(List<ZebraSegment> aSegmentsList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentsList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |

**Returns:**
[List](../../java.util/list)
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

