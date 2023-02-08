---
title: TargetsDetector
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.recognition.targets/targetsdetector/
---
**Inheritance:**
java.lang.Object
```
public class TargetsDetector
```
## Constructors

| Constructor | Description |
| --- | --- |
| [TargetsDetector(TargetsDetector.TargetRules aTargetRules, ITerminationCheck aTerminationCheck)](#TargetsDetector-com.aspose.barcode.barcoderecognition.recognition.targets.TargetsDetector.TargetRules-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filterPossibleFakeTargets(List<TargetUnion> Unions)](#filterPossibleFakeTargets-java.util.List-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion--) |  |
| [findTargets(ByteBitmap aBitmap)](#findTargets-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getClass()](#getClass--) |  |
| [getCodeLineByAngle(System.Drawing.PointF aCentralPoint, double aAngle, float aRad, ByteBitmap aBitmap)](#getCodeLineByAngle-com.aspose.ms.System.Drawing.PointF-double-float-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getCodeLineByAngle(System.Drawing.PointF aCentralPoint, double aAngle, float aRad, double aMaxDistFromCentral, ByteBitmap aBitmap)](#getCodeLineByAngle-com.aspose.ms.System.Drawing.PointF-double-float-double-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TargetsDetector(TargetsDetector.TargetRules aTargetRules, ITerminationCheck aTerminationCheck) {#TargetsDetector-com.aspose.barcode.barcoderecognition.recognition.targets.TargetsDetector.TargetRules-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public TargetsDetector(TargetsDetector.TargetRules aTargetRules, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aTargetRules | com.aspose.barcode.barcoderecognition.recognition.targets.TargetsDetector.TargetRules |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

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
### filterPossibleFakeTargets(List<TargetUnion> Unions) {#filterPossibleFakeTargets-java.util.List-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion--}
```
public List<TargetUnion> filterPossibleFakeTargets(List<TargetUnion> Unions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Unions | java.util.List<com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion> |  |

**Returns:**
[List](../../java.util/list)
### findTargets(ByteBitmap aBitmap) {#findTargets-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public List<TargetUnion> findTargets(ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[List](../../java.util/list)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeLineByAngle(System.Drawing.PointF aCentralPoint, double aAngle, float aRad, ByteBitmap aBitmap) {#getCodeLineByAngle-com.aspose.ms.System.Drawing.PointF-double-float-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public CodeLine getCodeLineByAngle(System.Drawing.PointF aCentralPoint, double aAngle, float aRad, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aCentralPoint | com.aspose.ms.System.Drawing.PointF |  |
| aAngle | double |  |
| aRad | float |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[CodeLine](../../com.aspose.barcode.barcoderecognition.recognition.targets/codeline)
### getCodeLineByAngle(System.Drawing.PointF aCentralPoint, double aAngle, float aRad, double aMaxDistFromCentral, ByteBitmap aBitmap) {#getCodeLineByAngle-com.aspose.ms.System.Drawing.PointF-double-float-double-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public CodeLine getCodeLineByAngle(System.Drawing.PointF aCentralPoint, double aAngle, float aRad, double aMaxDistFromCentral, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aCentralPoint | com.aspose.ms.System.Drawing.PointF |  |
| aAngle | double |  |
| aRad | float |  |
| aMaxDistFromCentral | double |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[CodeLine](../../com.aspose.barcode.barcoderecognition.recognition.targets/codeline)
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

