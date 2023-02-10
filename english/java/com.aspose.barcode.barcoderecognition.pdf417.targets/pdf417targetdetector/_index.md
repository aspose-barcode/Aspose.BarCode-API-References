---
title: pdf417TargetDetector
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.pdf417.targets/pdf417targetdetector/
---
**Inheritance:**
java.lang.Object
```
public class pdf417TargetDetector
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417TargetDetector()](#pdf417TargetDetector--) |  |
## Fields

| Field | Description |
| --- | --- |
| [c_StopId](#c-StopId) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractStartUnions(List<ZebraUnion> aUnions)](#extractStartUnions-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--) | Extracts start targets from list |
| [extractStopUnions(List<ZebraUnion> aUnions)](#extractStopUnions-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--) | Extracts stop targets from list |
| [getClass()](#getClass--) |  |
| [getExtended3DUnions(ByteBitmap aBitmap, List<ZebraSegment> aSegments, ITerminationCheck aTerminationCheck)](#getExtended3DUnions-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Clusters and extends in 3D targets |
| [getExtendedSyntheticUnionsFromHorizontalScan(ByteBitmap aBitmap, List<ZebraSegment> aSegments, ITerminationCheck aTerminationCheck)](#getExtendedSyntheticUnionsFromHorizontalScan-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Clusters and extends rectangular targets |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pdf417ScanZebraSegments(ByteBitmap aBitmap, boolean isFullScanHorizontal, boolean isDetectAndScanGradient, boolean isDetectGap, ITerminationCheck aTerminationCheck)](#pdf417ScanZebraSegments-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-boolean-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Detects barcode target segments |
| [pdf417ScanZebraSegments(ByteBitmap aBitmap, boolean isDetectGap, ITerminationCheck aTerminationCheck)](#pdf417ScanZebraSegments-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Detects barcode target segments |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417TargetDetector() {#pdf417TargetDetector--}
```
public pdf417TargetDetector()
```


### c_StopId {#c-StopId}
```
public static final int c_StopId
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
### extractStartUnions(List<ZebraUnion> aUnions) {#extractStartUnions-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--}
```
public static System.Collections.Generic.List<ZebraUnion> extractStartUnions(List<ZebraUnion> aUnions)
```


Extracts start targets from list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnions | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion> | detected targets |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - start targets
### extractStopUnions(List<ZebraUnion> aUnions) {#extractStopUnions-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--}
```
public static System.Collections.Generic.List<ZebraUnion> extractStopUnions(List<ZebraUnion> aUnions)
```


Extracts stop targets from list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnions | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion> | detected targets |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - stop targets
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtended3DUnions(ByteBitmap aBitmap, List<ZebraSegment> aSegments, ITerminationCheck aTerminationCheck) {#getExtended3DUnions-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<ZebraUnion> getExtended3DUnions(ByteBitmap aBitmap, List<ZebraSegment> aSegments, ITerminationCheck aTerminationCheck)
```


Clusters and extends in 3D targets

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | recognized bitmap |
| aSegments | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | recognized target segments |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[List](../../java.util/list) - clustered and extended in 3D targets
### getExtendedSyntheticUnionsFromHorizontalScan(ByteBitmap aBitmap, List<ZebraSegment> aSegments, ITerminationCheck aTerminationCheck) {#getExtendedSyntheticUnionsFromHorizontalScan-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<ZebraUnion> getExtendedSyntheticUnionsFromHorizontalScan(ByteBitmap aBitmap, List<ZebraSegment> aSegments, ITerminationCheck aTerminationCheck)
```


Clusters and extends rectangular targets

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | recognized bitmap |
| aSegments | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | recognized horizontally target segments |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[List](../../java.util/list) - clustered and extended rectangular targets
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




### pdf417ScanZebraSegments(ByteBitmap aBitmap, boolean isFullScanHorizontal, boolean isDetectAndScanGradient, boolean isDetectGap, ITerminationCheck aTerminationCheck) {#pdf417ScanZebraSegments-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-boolean-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static Tup<List<ZebraSegment>,List<ZebraSegment>> pdf417ScanZebraSegments(ByteBitmap aBitmap, boolean isFullScanHorizontal, boolean isDetectAndScanGradient, boolean isDetectGap, ITerminationCheck aTerminationCheck)
```


Detects barcode target segments

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | recognized bitmap |
| isFullScanHorizontal | boolean | always scan horizontal with otsu thresholding |
| isDetectAndScanGradient | boolean | detect and scan regions with gardient locator |
| isDetectGap | boolean | detect scanning gaps |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup) - first value is horizontally scanned barcodes with otsu thresholding, second detected by gradient locator
### pdf417ScanZebraSegments(ByteBitmap aBitmap, boolean isDetectGap, ITerminationCheck aTerminationCheck) {#pdf417ScanZebraSegments-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static Tup<List<ZebraSegment>,List<ZebraSegment>> pdf417ScanZebraSegments(ByteBitmap aBitmap, boolean isDetectGap, ITerminationCheck aTerminationCheck)
```


Detects barcode target segments

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | recognized bitmap |
| isDetectGap | boolean | detect scanning gaps |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup) - first value is horizontally scanned barcodes with otsu thresholding, second detected by gradient locator
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

