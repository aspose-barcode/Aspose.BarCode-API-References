---
title: LocatorsDetectorWithPattern
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.aztec.locators/locatorsdetectorwithpattern/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.recognition.aztec.locators.LocatorsDetector](../../com.aspose.barcode.barcoderecognition.recognition.aztec.locators/locatorsdetector)
```
public class LocatorsDetectorWithPattern extends LocatorsDetector
```
## Constructors

| Constructor | Description |
| --- | --- |
| [LocatorsDetectorWithPattern(ByteBitmap bitmap, int separatix, ITerminationCheck aTerminationCheck)](#LocatorsDetectorWithPattern-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
## Methods

| Method | Description |
| --- | --- |
| [detect(ILaserLineVisitor lidar)](#detect-com.aspose.barcode.barcoderecognition.internal.ILaserLineVisitor-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LocatorsDetectorWithPattern(ByteBitmap bitmap, int separatix, ITerminationCheck aTerminationCheck) {#LocatorsDetectorWithPattern-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public LocatorsDetectorWithPattern(ByteBitmap bitmap, int separatix, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| separatix | int |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### detect(ILaserLineVisitor lidar) {#detect-com.aspose.barcode.barcoderecognition.internal.ILaserLineVisitor-}
```
public List<AztecLocator> detect(ILaserLineVisitor lidar)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lidar | [ILaserLineVisitor](../../com.aspose.barcode.barcoderecognition.internal/ilaserlinevisitor) |  |

**Returns:**
[List](../../java.util/list)
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

