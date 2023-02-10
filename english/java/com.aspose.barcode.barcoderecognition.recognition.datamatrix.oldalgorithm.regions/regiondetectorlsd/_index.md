---
title: RegionDetectorLsd
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions/regiondetectorlsd/
---
**Inheritance:**
java.lang.Object
```
public class RegionDetectorLsd
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RegionDetectorLsd(ByteBitmap image)](#RegionDetectorLsd-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
## Fields

| Field | Description |
| --- | --- |
| [currentCornerIndex](#currentCornerIndex) |  |
| [originalQuad](#originalQuad) |  |
## Methods

| Method | Description |
| --- | --- |
| [calculateMinimumOfBlackPointsVertical(int fromX, int toX, int fromY, int toY, ByteBitmap byteBitmap)](#calculateMinimumOfBlackPointsVertical-int-int-int-int-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Calculates minimum of black points by vertical |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLargestCorner(ByteBitmap originalBitmap)](#getLargestCorner-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getNextCorner(ByteBitmap originalBitmap)](#getNextCorner-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [hasNextCorner()](#hasNextCorner--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RegionDetectorLsd(ByteBitmap image) {#RegionDetectorLsd-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public RegionDetectorLsd(ByteBitmap image)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

### currentCornerIndex {#currentCornerIndex}
```
public int currentCornerIndex
```


### originalQuad {#originalQuad}
```
public List<QuadPointFs> originalQuad
```


### calculateMinimumOfBlackPointsVertical(int fromX, int toX, int fromY, int toY, ByteBitmap byteBitmap) {#calculateMinimumOfBlackPointsVertical-int-int-int-int-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int calculateMinimumOfBlackPointsVertical(int fromX, int toX, int fromY, int toY, ByteBitmap byteBitmap)
```


Calculates minimum of black points by vertical

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fromX | int | from X bound |
| toX | int | to X bound |
| fromY | int | from Y bound |
| toY | int | to Y bound |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte bitmap |

**Returns:**
int - count of black point
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
### getLargestCorner(ByteBitmap originalBitmap) {#getLargestCorner-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public final DetectedCorner getLargestCorner(ByteBitmap originalBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[DetectedCorner](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions.corners/detectedcorner)
### getNextCorner(ByteBitmap originalBitmap) {#getNextCorner-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public final DetectedCorner getNextCorner(ByteBitmap originalBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[DetectedCorner](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions.corners/detectedcorner)
### hasNextCorner() {#hasNextCorner--}
```
public final boolean hasNextCorner()
```




**Returns:**
boolean
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

