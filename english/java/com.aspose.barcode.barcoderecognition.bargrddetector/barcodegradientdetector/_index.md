---
title: BarcodeGradientDetector
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.bargrddetector/barcodegradientdetector/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.bargrddetector.IBarcodeDetector](../../com.aspose.barcode.barcoderecognition.bargrddetector/ibarcodedetector)
```
public class BarcodeGradientDetector implements IBarcodeDetector
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeGradientDetector(ByteBitmap aBmp, int reducingFactor, ITerminationCheck aTerminationCheck)](#BarcodeGradientDetector-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [BarcodeGradientDetector(ByteBitmap aBmp, int reducingFactor, boolean debugMode, ITerminationCheck aTerminationCheck)](#BarcodeGradientDetector-com.aspose.barcode.common.bitmaps.ByteBitmap-int-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
## Fields

| Field | Description |
| --- | --- |
| [_debugObject](#-debugObject) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeAreas()](#getBarcodeAreas--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeGradientDetector(ByteBitmap aBmp, int reducingFactor, ITerminationCheck aTerminationCheck) {#BarcodeGradientDetector-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public BarcodeGradientDetector(ByteBitmap aBmp, int reducingFactor, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| reducingFactor | int |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### BarcodeGradientDetector(ByteBitmap aBmp, int reducingFactor, boolean debugMode, ITerminationCheck aTerminationCheck) {#BarcodeGradientDetector-com.aspose.barcode.common.bitmaps.ByteBitmap-int-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public BarcodeGradientDetector(ByteBitmap aBmp, int reducingFactor, boolean debugMode, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| reducingFactor | int |  |
| debugMode | boolean |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### _debugObject {#-debugObject}
```
public GradientDetectorDebugObject _debugObject
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
### getBarcodeAreas() {#getBarcodeAreas--}
```
public List<ResultedGradientUnion> getBarcodeAreas()
```




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

