---
title: ZebraScanUtilBase.ZebraScanMTBaseSingleProcessor
second_title: Aspose.BarCode for Java API Reference
description: Multithreaded zebra segment recognizer single processor version
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebrascanutilbase.zebrascanmtbasesingleprocessor/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraScanUtilBase.ZebraScanMTBaseFunc

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.common.threads.IKernelAction](../../com.aspose.barcode.barcoderecognition.common.threads/ikernelaction)
```
public abstract static class ZebraScanUtilBase.ZebraScanMTBaseSingleProcessor extends ZebraScanUtilBase.ZebraScanMTBaseFunc implements IKernelAction
```

Multithreaded zebra segment recognizer, single processor version
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraScanMTBaseSingleProcessor(ByteBitmap aBitmap, List<DoublePoints> aLinesList, IZebraProcessor aProcessor, int aDirection, int[] aFilterSaltAndPaperSizes, ITerminationCheck aTerminationCheck)](#ZebraScanMTBaseSingleProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--com.aspose.barcode.barcoderecognition.common.zebraxd.IZebraProcessor-int-int---com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
## Fields

| Field | Description |
| --- | --- |
| [ResultList](#ResultList) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [kernelAction(KernelInstanceData data)](#kernelAction-com.aspose.barcode.barcoderecognition.common.threads.KernelInstanceData-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scanZebraSegments()](#scanZebraSegments--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraScanMTBaseSingleProcessor(ByteBitmap aBitmap, List<DoublePoints> aLinesList, IZebraProcessor aProcessor, int aDirection, int[] aFilterSaltAndPaperSizes, ITerminationCheck aTerminationCheck) {#ZebraScanMTBaseSingleProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--com.aspose.barcode.barcoderecognition.common.zebraxd.IZebraProcessor-int-int---com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public ZebraScanMTBaseSingleProcessor(ByteBitmap aBitmap, List<DoublePoints> aLinesList, IZebraProcessor aProcessor, int aDirection, int[] aFilterSaltAndPaperSizes, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aLinesList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints> |  |
| aProcessor | [IZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/izebraprocessor) |  |
| aDirection | int |  |
| aFilterSaltAndPaperSizes | int[] |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### ResultList {#ResultList}
```
public List<ZebraSegment> ResultList
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
### kernelAction(KernelInstanceData data) {#kernelAction-com.aspose.barcode.barcoderecognition.common.threads.KernelInstanceData-}
```
public void kernelAction(KernelInstanceData data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | [KernelInstanceData](../../com.aspose.barcode.barcoderecognition.common.threads/kernelinstancedata) |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### scanZebraSegments() {#scanZebraSegments--}
```
public List<ZebraSegment> scanZebraSegments()
```




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

