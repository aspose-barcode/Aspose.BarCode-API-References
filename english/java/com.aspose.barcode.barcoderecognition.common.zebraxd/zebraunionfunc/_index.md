---
title: ZebraUnionFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 30
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunionfunc/
---
**Inheritance:**
java.lang.Object
```
public class ZebraUnionFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraUnionFunc()](#ZebraUnionFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [calculateExtendedUnionParams(ZebraUnion aUnion, ByteBitmap aBitmap, int aBalance)](#calculateExtendedUnionParams-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) | Calculated extended params for union like bounding quad and gradient angle |
| [calculateExtendedUnionParams(ZebraUnion aUnion, ByteBitmap aBitmap, int MaxGradientLines, int aBalance, int aSelection)](#calculateExtendedUnionParams-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-) | Calculated extended params for union like bounding quad and gradient angle |
| [createZebraUnionBasicWithBasicParams(List<ZebraSegment> aList)](#createZebraUnionBasicWithBasicParams-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--) | Unites ZebraSegment union and calculates basic params: barcode type, value quality, length and zebra pixel size |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGradientAngle(List<ZebraSegment> aList, ByteBitmap aBitmap, int MaxLines)](#getGradientAngle-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-int-) | Detects angle of the lines on the union area bt gradient algorithm |
| [getUnionBalancedQuad(List<ZebraSegment> aSegments, double aDetectedAngle, System.Drawing.Point aCentralPoint, QuadPoints aPreviousQuad, int aBalance, int aSelection)](#getUnionBalancedQuad-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--double-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-int-) | Creates bounding quadrangle for union zebra segments |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraUnionFunc() {#ZebraUnionFunc--}
```
public ZebraUnionFunc()
```


### calculateExtendedUnionParams(ZebraUnion aUnion, ByteBitmap aBitmap, int aBalance) {#calculateExtendedUnionParams-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static void calculateExtendedUnionParams(ZebraUnion aUnion, ByteBitmap aBitmap, int aBalance)
```


Calculated extended params for union like bounding quad and gradient angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) | union with basic params |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap to gradient angle calculation |
| aBalance | int | balance edge types, fast or precise for noised images |

### calculateExtendedUnionParams(ZebraUnion aUnion, ByteBitmap aBitmap, int MaxGradientLines, int aBalance, int aSelection) {#calculateExtendedUnionParams-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-}
```
public static void calculateExtendedUnionParams(ZebraUnion aUnion, ByteBitmap aBitmap, int MaxGradientLines, int aBalance, int aSelection)
```


Calculated extended params for union like bounding quad and gradient angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) | union with basic params |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap to gradient angle calculation |
| MaxGradientLines | int | maximum lines to calculate gradient angle |
| aBalance | int | balance edge types, fast or precise for noised images |
| aSelection | int | detect Start or/and End edges for Quad |

### createZebraUnionBasicWithBasicParams(List<ZebraSegment> aList) {#createZebraUnionBasicWithBasicParams-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--}
```
public static ZebraUnion createZebraUnionBasicWithBasicParams(List<ZebraSegment> aList)
```


Unites ZebraSegment union and calculates basic params: barcode type, value quality, length and zebra pixel size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | clustered segments which should be united to union |

**Returns:**
[ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) - union with basic params
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
### getGradientAngle(List<ZebraSegment> aList, ByteBitmap aBitmap, int MaxLines) {#getGradientAngle-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static double getGradientAngle(List<ZebraSegment> aList, ByteBitmap aBitmap, int MaxLines)
```


Detects angle of the lines on the union area bt gradient algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap |
| MaxLines | int | maximum scans |

**Returns:**
double - detected gradient angle
### getUnionBalancedQuad(List<ZebraSegment> aSegments, double aDetectedAngle, System.Drawing.Point aCentralPoint, QuadPoints aPreviousQuad, int aBalance, int aSelection) {#getUnionBalancedQuad-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--double-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-int-}
```
public static QuadPoints getUnionBalancedQuad(List<ZebraSegment> aSegments, double aDetectedAngle, System.Drawing.Point aCentralPoint, QuadPoints aPreviousQuad, int aBalance, int aSelection)
```


Creates bounding quadrangle for union zebra segments

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegments | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | recognized zebra segments from union |
| aDetectedAngle | double | deetcted by gradient algorithm angle |
| aCentralPoint | com.aspose.ms.System.Drawing.Point |  |
| aPreviousQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | quad from previous union |
| aBalance | int | balance edge types, fast or precise for noised images |
| aSelection | int | detect Start or/and End edges for Quad |

**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) - detected bounding quadrangle
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

