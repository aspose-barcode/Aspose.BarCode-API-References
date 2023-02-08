---
title: BitmapServer
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 18
url: /java/com.aspose.barcode.barcoderecognition.internal/bitmapserver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.bitmapserver.IBitmapServer](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/ibitmapserver)
```
public class BitmapServer implements IBitmapServer
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BitmapServer(BitmapImageSource aBitmapSource, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck)](#BitmapServer-com.aspose.barcode.barcoderecognition.recognition.bitmapserver.BitmapImageSource-com.aspose.barcode.barcoderecognition.internal.RecognitionOptions-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getARGBBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy)](#getARGBBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-) |  |
| [getByteBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy)](#getByteBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-) |  |
| [getClass()](#getClass--) |  |
| [getHistogram(int Region, BitmapFilterType aFilterType, boolean isCopy)](#getHistogram-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-) |  |
| [getImageEntity(int Region, BitmapFilterType aFilterType, int aImageType, boolean isCopy)](#getImageEntity-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-int-boolean-) |  |
| [getOriginalBitmapSize()](#getOriginalBitmapSize--) |  |
| [getRegionCount()](#getRegionCount--) |  |
| [getRegionInfo(int RegionId)](#getRegionInfo-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BitmapServer(BitmapImageSource aBitmapSource, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck) {#BitmapServer-com.aspose.barcode.barcoderecognition.recognition.bitmapserver.BitmapImageSource-com.aspose.barcode.barcoderecognition.internal.RecognitionOptions-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public BitmapServer(BitmapImageSource aBitmapSource, RecognitionOptions aRecognitionOptions, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmapSource | [BitmapImageSource](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/bitmapimagesource) |  |
| aRecognitionOptions | [RecognitionOptions](../../com.aspose.barcode.barcoderecognition.internal/recognitionoptions) |  |
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
### getARGBBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy) {#getARGBBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-}
```
public final ARGBBitmap getARGBBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Region | int |  |
| aFilterType | [BitmapFilterType](../../com.aspose.barcode.barcoderecognition.internal/bitmapfiltertype) |  |
| isCopy | boolean |  |

**Returns:**
[ARGBBitmap](../../com.aspose.barcode.common.bitmaps/argbbitmap)
### getByteBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy) {#getByteBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-}
```
public final ByteBitmap getByteBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Region | int |  |
| aFilterType | [BitmapFilterType](../../com.aspose.barcode.barcoderecognition.internal/bitmapfiltertype) |  |
| isCopy | boolean |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHistogram(int Region, BitmapFilterType aFilterType, boolean isCopy) {#getHistogram-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-}
```
public final int[] getHistogram(int Region, BitmapFilterType aFilterType, boolean isCopy)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Region | int |  |
| aFilterType | [BitmapFilterType](../../com.aspose.barcode.barcoderecognition.internal/bitmapfiltertype) |  |
| isCopy | boolean |  |

**Returns:**
int[]
### getImageEntity(int Region, BitmapFilterType aFilterType, int aImageType, boolean isCopy) {#getImageEntity-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-int-boolean-}
```
public final ImageEntity getImageEntity(int Region, BitmapFilterType aFilterType, int aImageType, boolean isCopy)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Region | int |  |
| aFilterType | [BitmapFilterType](../../com.aspose.barcode.barcoderecognition.internal/bitmapfiltertype) |  |
| aImageType | int |  |
| isCopy | boolean |  |

**Returns:**
[ImageEntity](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver.imageentities/imageentity)
### getOriginalBitmapSize() {#getOriginalBitmapSize--}
```
public final System.Drawing.Size getOriginalBitmapSize()
```




**Returns:**
com.aspose.ms.System.Drawing.Size
### getRegionCount() {#getRegionCount--}
```
public final int getRegionCount()
```




**Returns:**
int
### getRegionInfo(int RegionId) {#getRegionInfo-int-}
```
public final BitmapRegionInfo getRegionInfo(int RegionId)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| RegionId | int |  |

**Returns:**
[BitmapRegionInfo](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/bitmapregioninfo)
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

