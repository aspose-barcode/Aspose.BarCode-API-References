---
title: MaxiCodeTargetDetector
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.maxicode._target/maxicodetargetdetector/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraScanUtilBase](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebrascanutilbase)
```
public class MaxiCodeTargetDetector extends ZebraScanUtilBase
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MaxiCodeTargetDetector()](#MaxiCodeTargetDetector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [cutOfByCenterAndSize(List<ZebraUnion> unions, System.Drawing.Point horizontalUnionCenter, float zebraPixSize, float size)](#cutOfByCenterAndSize-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.ms.System.Drawing.Point-float-float-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findTargets(ByteBitmap byteBitmap, boolean readTinyBarcodes, ITerminationCheck aTerminationCheck)](#findTargets-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [fixCoordBrezenheimScan(List<ZebraSegment> aBarList, System.Drawing.Point aFirst, System.Drawing.Point aSecond)](#fixCoordBrezenheimScan-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Add real coordinates to ZebraSegment on the image, which are recognized on extracted by Bresenham algorithm bitmap line http://en.wikipedia.org/wiki/Bresenham%27s\_line\_algorithm |
| [fixCoordDDAScan(List<ZebraSegment> aBarList, System.Drawing.Point aFirst, System.Drawing.Point aSecond, int aPointsCount)](#fixCoordDDAScan-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-int-) | Add real coordinates to ZebraSegment on the image, which are recognized on extracted by Digital differential analyzer algorithm bitmap line https://en.wikipedia.org/wiki/Digital\_differential\_analyzer\_(graphics\_algorithm) |
| [getClass()](#getClass--) |  |
| [getGammaSharpAverageBinarized(ByteBitmap aBmp, BBMap aGammaFunction, int HalfWindow, float aK)](#getGammaSharpAverageBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.deconvolution.BBMap-int-float-) |  |
| [getNNIncWithColorErosionAverage(ByteBitmap aBmp, int Multiplier, boolean isEraseBlack, int HalfWindow, float K)](#getNNIncWithColorErosionAverage-com.aspose.barcode.common.bitmaps.ByteBitmap-int-boolean-int-float-) |  |
| [getOtsuBinarized(ByteBitmap aBmp)](#getOtsuBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getSearchRectangle(System.Drawing.Point unionCenter, float unionLength)](#getSearchRectangle-com.aspose.ms.System.Drawing.Point-float-) |  |
| [getSearchRectangle2(System.Drawing.Point unionCenter, float unionLength)](#getSearchRectangle2-com.aspose.ms.System.Drawing.Point-float-) |  |
| [getSharpWithAverageBinarized(ByteBitmap aBmp)](#getSharpWithAverageBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getUnions(ByteBitmap byteBitmap, System.Drawing.Rectangle rect, MaxiCodeTargetDetector.Direction direction, boolean readTinyBarcodes, ITerminationCheck terminationCheck)](#getUnions-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.barcoderecognition.recognition.maxicode.-target.MaxiCodeTargetDetector.Direction-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [preciseCentralPoint(ZebraUnion target, ByteBitmap byteBitmap, ITerminationCheck terminationCheck)](#preciseCentralPoint-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeTargetDetector() {#MaxiCodeTargetDetector--}
```
public MaxiCodeTargetDetector()
```


### cutOfByCenterAndSize(List<ZebraUnion> unions, System.Drawing.Point horizontalUnionCenter, float zebraPixSize, float size) {#cutOfByCenterAndSize-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.ms.System.Drawing.Point-float-float-}
```
public static List<ZebraSegment> cutOfByCenterAndSize(List<ZebraUnion> unions, System.Drawing.Point horizontalUnionCenter, float zebraPixSize, float size)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unions | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion> |  |
| horizontalUnionCenter | com.aspose.ms.System.Drawing.Point |  |
| zebraPixSize | float |  |
| size | float |  |

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
### findTargets(ByteBitmap byteBitmap, boolean readTinyBarcodes, ITerminationCheck aTerminationCheck) {#findTargets-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<ZebraUnion> findTargets(ByteBitmap byteBitmap, boolean readTinyBarcodes, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| readTinyBarcodes | boolean |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
### fixCoordBrezenheimScan(List<ZebraSegment> aBarList, System.Drawing.Point aFirst, System.Drawing.Point aSecond) {#fixCoordBrezenheimScan-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public static void fixCoordBrezenheimScan(List<ZebraSegment> aBarList, System.Drawing.Point aFirst, System.Drawing.Point aSecond)
```


Add real coordinates to ZebraSegment on the image, which are recognized on extracted by Bresenham algorithm bitmap line http://en.wikipedia.org/wiki/Bresenham%27s\_line\_algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBarList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | recognized segment on 1D line with X coordinates |
| aFirst | com.aspose.ms.System.Drawing.Point | first point of scanline |
| aSecond | com.aspose.ms.System.Drawing.Point | second point of scanline |

### fixCoordDDAScan(List<ZebraSegment> aBarList, System.Drawing.Point aFirst, System.Drawing.Point aSecond, int aPointsCount) {#fixCoordDDAScan-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-int-}
```
public static void fixCoordDDAScan(List<ZebraSegment> aBarList, System.Drawing.Point aFirst, System.Drawing.Point aSecond, int aPointsCount)
```


Add real coordinates to ZebraSegment on the image, which are recognized on extracted by Digital differential analyzer algorithm bitmap line https://en.wikipedia.org/wiki/Digital\_differential\_analyzer\_(graphics\_algorithm)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBarList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | recognized segment on 1D line with X coordinates |
| aFirst | com.aspose.ms.System.Drawing.Point | first point of scanline |
| aSecond | com.aspose.ms.System.Drawing.Point | second point of scanline |
| aPointsCount | int |  |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGammaSharpAverageBinarized(ByteBitmap aBmp, BBMap aGammaFunction, int HalfWindow, float aK) {#getGammaSharpAverageBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.deconvolution.BBMap-int-float-}
```
public static byte[] getGammaSharpAverageBinarized(ByteBitmap aBmp, BBMap aGammaFunction, int HalfWindow, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aGammaFunction | [BBMap](../../com.aspose.barcode.barcoderecognition.deconvolution/bbmap) |  |
| HalfWindow | int |  |
| aK | float |  |

**Returns:**
byte[]
### getNNIncWithColorErosionAverage(ByteBitmap aBmp, int Multiplier, boolean isEraseBlack, int HalfWindow, float K) {#getNNIncWithColorErosionAverage-com.aspose.barcode.common.bitmaps.ByteBitmap-int-boolean-int-float-}
```
public static byte[] getNNIncWithColorErosionAverage(ByteBitmap aBmp, int Multiplier, boolean isEraseBlack, int HalfWindow, float K)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| Multiplier | int |  |
| isEraseBlack | boolean |  |
| HalfWindow | int |  |
| K | float |  |

**Returns:**
byte[]
### getOtsuBinarized(ByteBitmap aBmp) {#getOtsuBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte[] getOtsuBinarized(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte[]
### getSearchRectangle(System.Drawing.Point unionCenter, float unionLength) {#getSearchRectangle-com.aspose.ms.System.Drawing.Point-float-}
```
public static System.Drawing.Rectangle getSearchRectangle(System.Drawing.Point unionCenter, float unionLength)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unionCenter | com.aspose.ms.System.Drawing.Point |  |
| unionLength | float |  |

**Returns:**
com.aspose.ms.System.Drawing.Rectangle
### getSearchRectangle2(System.Drawing.Point unionCenter, float unionLength) {#getSearchRectangle2-com.aspose.ms.System.Drawing.Point-float-}
```
public static System.Drawing.Rectangle getSearchRectangle2(System.Drawing.Point unionCenter, float unionLength)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unionCenter | com.aspose.ms.System.Drawing.Point |  |
| unionLength | float |  |

**Returns:**
com.aspose.ms.System.Drawing.Rectangle
### getSharpWithAverageBinarized(ByteBitmap aBmp) {#getSharpWithAverageBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte[] getSharpWithAverageBinarized(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte[]
### getUnions(ByteBitmap byteBitmap, System.Drawing.Rectangle rect, MaxiCodeTargetDetector.Direction direction, boolean readTinyBarcodes, ITerminationCheck terminationCheck) {#getUnions-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.barcoderecognition.recognition.maxicode.-target.MaxiCodeTargetDetector.Direction-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<ZebraUnion> getUnions(ByteBitmap byteBitmap, System.Drawing.Rectangle rect, MaxiCodeTargetDetector.Direction direction, boolean readTinyBarcodes, ITerminationCheck terminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| rect | com.aspose.ms.System.Drawing.Rectangle |  |
| direction | com.aspose.barcode.barcoderecognition.recognition.maxicode._target.MaxiCodeTargetDetector.Direction |  |
| readTinyBarcodes | boolean |  |
| terminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
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




### preciseCentralPoint(ZebraUnion target, ByteBitmap byteBitmap, ITerminationCheck terminationCheck) {#preciseCentralPoint-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static void preciseCentralPoint(ZebraUnion target, ByteBitmap byteBitmap, ITerminationCheck terminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| target | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) |  |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| terminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

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

