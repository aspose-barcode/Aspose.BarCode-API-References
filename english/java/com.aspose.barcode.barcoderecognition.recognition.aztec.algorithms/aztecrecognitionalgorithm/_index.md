---
title: AztecRecognitionAlgorithm
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.aztec.algorithms/aztecrecognitionalgorithm/
---
**Inheritance:**
java.lang.Object
```
public class AztecRecognitionAlgorithm
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AztecRecognitionAlgorithm(ByteBitmap bitmap, ITerminationCheck aTerminationCheck, BaseDecodeType readType)](#AztecRecognitionAlgorithm-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recognize(ILaserLineVisitor lidar)](#recognize-com.aspose.barcode.barcoderecognition.internal.ILaserLineVisitor-) |  |
| [recognize(List<AztecLocator> locators)](#recognize-java.util.List-com.aspose.barcode.barcoderecognition.recognition.aztec.AztecLocator--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AztecRecognitionAlgorithm(ByteBitmap bitmap, ITerminationCheck aTerminationCheck, BaseDecodeType readType) {#AztecRecognitionAlgorithm-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public AztecRecognitionAlgorithm(ByteBitmap bitmap, ITerminationCheck aTerminationCheck, BaseDecodeType readType)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |
| readType | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

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




### recognize(ILaserLineVisitor lidar) {#recognize-com.aspose.barcode.barcoderecognition.internal.ILaserLineVisitor-}
```
public List<AztecResult> recognize(ILaserLineVisitor lidar)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lidar | [ILaserLineVisitor](../../com.aspose.barcode.barcoderecognition.internal/ilaserlinevisitor) |  |

**Returns:**
[List](../../java.util/list)
### recognize(List<AztecLocator> locators) {#recognize-java.util.List-com.aspose.barcode.barcoderecognition.recognition.aztec.AztecLocator--}
```
public List<AztecResult> recognize(List<AztecLocator> locators)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| locators | java.util.List<com.aspose.barcode.barcoderecognition.recognition.aztec.AztecLocator> |  |

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

