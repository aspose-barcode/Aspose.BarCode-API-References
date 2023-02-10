---
title: Extend3DZebraProcessorBase
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/extend3dzebraprocessorbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.common.zebraxd.IExtend3DZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextend3dzebraprocessor)
```
public abstract class Extend3DZebraProcessorBase implements IExtend3DZebraProcessor
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Extend3DZebraProcessorBase(ITerminationCheck aTerminationCheck)](#Extend3DZebraProcessorBase-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [Extend3DZebraProcessorBase(Extend3DZebraProcessorBase aProcessor)](#Extend3DZebraProcessorBase-com.aspose.barcode.barcoderecognition.common.zebraxd.Extend3DZebraProcessorBase-) |  |
## Methods

| Method | Description |
| --- | --- |
| [createZebraUnion(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap)](#createZebraUnion-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filterZebraSegments(List<ZebraSegment> aSegments, ZebraUnion aUnion)](#filterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-) |  |
| [getClass()](#getClass--) |  |
| [getExtendingParam()](#getExtendingParam--) |  |
| [getProcessorCopy()](#getProcessorCopy--) |  |
| [getTerminatioCheck()](#getTerminatioCheck--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scan(ByteBitmap aBitmap, List<DoublePoints> aLinesList)](#scan-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Extend3DZebraProcessorBase(ITerminationCheck aTerminationCheck) {#Extend3DZebraProcessorBase-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public Extend3DZebraProcessorBase(ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### Extend3DZebraProcessorBase(Extend3DZebraProcessorBase aProcessor) {#Extend3DZebraProcessorBase-com.aspose.barcode.barcoderecognition.common.zebraxd.Extend3DZebraProcessorBase-}
```
public Extend3DZebraProcessorBase(Extend3DZebraProcessorBase aProcessor)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aProcessor | [Extend3DZebraProcessorBase](../../com.aspose.barcode.barcoderecognition.common.zebraxd/extend3dzebraprocessorbase) |  |

### createZebraUnion(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap) {#createZebraUnion-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public ZebraUnion createZebraUnion(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap)
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
### filterZebraSegments(List<ZebraSegment> aSegments, ZebraUnion aUnion) {#filterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-}
```
public List<ZebraSegment> filterZebraSegments(List<ZebraSegment> aSegments, ZebraUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegments | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) |  |

**Returns:**
[List](../../java.util/list)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendingParam() {#getExtendingParam--}
```
public ZebraExtend3DParam getExtendingParam()
```




**Returns:**
[ZebraExtend3DParam](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraextend3dparam)
### getProcessorCopy() {#getProcessorCopy--}
```
public abstract IExtend3DZebraProcessor getProcessorCopy()
```




**Returns:**
[IExtend3DZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextend3dzebraprocessor)
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




### scan(ByteBitmap aBitmap, List<DoublePoints> aLinesList) {#scan-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--}
```
public abstract List<ZebraSegment> scan(ByteBitmap aBitmap, List<DoublePoints> aLinesList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aLinesList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints> |  |

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

