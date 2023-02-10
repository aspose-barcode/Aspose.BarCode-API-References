---
title: ZebraScanUtilBase
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 27
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebrascanutilbase/
---
**Inheritance:**
java.lang.Object
```
public class ZebraScanUtilBase
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraScanUtilBase()](#ZebraScanUtilBase--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fixCoordBrezenheimScan(List<ZebraSegment> aBarList, System.Drawing.Point aFirst, System.Drawing.Point aSecond)](#fixCoordBrezenheimScan-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Add real coordinates to ZebraSegment on the image, which are recognized on extracted by Bresenham algorithm bitmap line http://en.wikipedia.org/wiki/Bresenham%27s\_line\_algorithm |
| [fixCoordDDAScan(List<ZebraSegment> aBarList, System.Drawing.Point aFirst, System.Drawing.Point aSecond, int aPointsCount)](#fixCoordDDAScan-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-int-) | Add real coordinates to ZebraSegment on the image, which are recognized on extracted by Digital differential analyzer algorithm bitmap line https://en.wikipedia.org/wiki/Digital\_differential\_analyzer\_(graphics\_algorithm) |
| [getClass()](#getClass--) |  |
| [getGammaSharpAverageBinarized(ByteBitmap aBmp, BBMap aGammaFunction, int HalfWindow, float aK)](#getGammaSharpAverageBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.deconvolution.BBMap-int-float-) |  |
| [getNNIncWithColorErosionAverage(ByteBitmap aBmp, int Multiplier, boolean isEraseBlack, int HalfWindow, float K)](#getNNIncWithColorErosionAverage-com.aspose.barcode.common.bitmaps.ByteBitmap-int-boolean-int-float-) |  |
| [getOtsuBinarized(ByteBitmap aBmp)](#getOtsuBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getSharpWithAverageBinarized(ByteBitmap aBmp)](#getSharpWithAverageBinarized-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraScanUtilBase() {#ZebraScanUtilBase--}
```
public ZebraScanUtilBase()
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

