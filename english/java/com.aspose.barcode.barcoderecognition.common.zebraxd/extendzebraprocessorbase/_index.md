---
title: ExtendZebraProcessorBase
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/extendzebraprocessorbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.common.zebraxd.IExtendZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextendzebraprocessor)
```
public abstract class ExtendZebraProcessorBase implements IExtendZebraProcessor
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ExtendZebraProcessorBase(ITerminationCheck aTerminationCheck)](#ExtendZebraProcessorBase-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [ExtendZebraProcessorBase(ExtendZebraProcessorBase aProcessor)](#ExtendZebraProcessorBase-com.aspose.barcode.barcoderecognition.common.zebraxd.ExtendZebraProcessorBase-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filterZebraSegments(List<ZebraSegment> aSegments, ZebraUnion aUnion)](#filterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedQuad(ZebraUnion aUnion)](#getExtendedQuad-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-) |  |
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
### ExtendZebraProcessorBase(ITerminationCheck aTerminationCheck) {#ExtendZebraProcessorBase-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public ExtendZebraProcessorBase(ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### ExtendZebraProcessorBase(ExtendZebraProcessorBase aProcessor) {#ExtendZebraProcessorBase-com.aspose.barcode.barcoderecognition.common.zebraxd.ExtendZebraProcessorBase-}
```
public ExtendZebraProcessorBase(ExtendZebraProcessorBase aProcessor)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aProcessor | [ExtendZebraProcessorBase](../../com.aspose.barcode.barcoderecognition.common.zebraxd/extendzebraprocessorbase) |  |

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
### getExtendedQuad(ZebraUnion aUnion) {#getExtendedQuad-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-}
```
public QuadPoints getExtendedQuad(ZebraUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) |  |

**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints)
### getProcessorCopy() {#getProcessorCopy--}
```
public abstract IExtendZebraProcessor getProcessorCopy()
```




**Returns:**
[IExtendZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextendzebraprocessor)
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

