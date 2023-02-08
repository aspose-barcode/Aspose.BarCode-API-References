---
title: pdf417DataRegionExtractor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregionextractor/
---
**Inheritance:**
java.lang.Object
```
public class pdf417DataRegionExtractor
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417DataRegionExtractor()](#pdf417DataRegionExtractor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get2dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, pdf417DataRegionExtractor.RulesFor2dRestoration aRules, ITerminationCheck aTerminationCheck)](#get2dExtracting-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.pdf417.targets.pdf417CodeRegion-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegionExtractor.RulesFor2dRestoration-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Extract dataregion from corrupted targets with 2D target restorations |
| [get2dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, ITerminationCheck aTerminationCheck)](#get2dExtracting-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.pdf417.targets.pdf417CodeRegion-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Extract dataregion with corrupted targets with 2D target restorations |
| [get3dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, ITerminationCheck aTerminationCheck)](#get3dExtracting-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.pdf417.targets.pdf417CodeRegion-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Extract dataregion with classic 3D restoration with full targets |
| [getClass()](#getClass--) |  |
| [getQuadExtracting(ByteBitmap aBitmap, QuadPoints aQuad, QuadPoints ExternalQuad, float Cell17Length, ITerminationCheck aTerminationCheck)](#getQuadExtracting-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-float-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Extract dataregion |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417DataRegionExtractor() {#pdf417DataRegionExtractor--}
```
public pdf417DataRegionExtractor()
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
### get2dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, pdf417DataRegionExtractor.RulesFor2dRestoration aRules, ITerminationCheck aTerminationCheck) {#get2dExtracting-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.pdf417.targets.pdf417CodeRegion-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegionExtractor.RulesFor2dRestoration-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417DataRegion get2dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, pdf417DataRegionExtractor.RulesFor2dRestoration aRules, ITerminationCheck aTerminationCheck)
```


Extract dataregion from corrupted targets with 2D target restorations

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | recognized bitmap |
| aRegion | [pdf417CodeRegion](../../com.aspose.barcode.barcoderecognition.pdf417.targets/pdf417coderegion) | connected start + stop targets into single region |
| aRules | com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegionExtractor.RulesFor2dRestoration | extracting 2D rules |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) - dataregion with extracted bitmap and params
### get2dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, ITerminationCheck aTerminationCheck) {#get2dExtracting-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.pdf417.targets.pdf417CodeRegion-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417DataRegion get2dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, ITerminationCheck aTerminationCheck)
```


Extract dataregion with corrupted targets with 2D target restorations

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | recognized bitmap |
| aRegion | [pdf417CodeRegion](../../com.aspose.barcode.barcoderecognition.pdf417.targets/pdf417coderegion) | connected start + stop targets into single region |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) - dataregion with extracted bitmap and params
### get3dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, ITerminationCheck aTerminationCheck) {#get3dExtracting-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.pdf417.targets.pdf417CodeRegion-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417DataRegion get3dExtracting(ByteBitmap aBitmap, pdf417CodeRegion aRegion, ITerminationCheck aTerminationCheck)
```


Extract dataregion with classic 3D restoration with full targets

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | recognized bitmap |
| aRegion | [pdf417CodeRegion](../../com.aspose.barcode.barcoderecognition.pdf417.targets/pdf417coderegion) | connected start + stop targets into single region |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) - dataregion with extracted bitmap and params
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQuadExtracting(ByteBitmap aBitmap, QuadPoints aQuad, QuadPoints ExternalQuad, float Cell17Length, ITerminationCheck aTerminationCheck) {#getQuadExtracting-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-float-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417DataRegion getQuadExtracting(ByteBitmap aBitmap, QuadPoints aQuad, QuadPoints ExternalQuad, float Cell17Length, ITerminationCheck aTerminationCheck)
```


Extract dataregion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | recognized bitmap |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | internal dataregion quadrangle |
| ExternalQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | Bounding barcode quadrangle |
| Cell17Length | float | possible column width(17 cells) |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) - dataregion with extracted bitmap and params
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

