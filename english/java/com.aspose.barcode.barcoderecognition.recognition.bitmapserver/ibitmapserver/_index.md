---
title: IBitmapServer
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 15
url: /java/com.aspose.barcode.barcoderecognition.recognition.bitmapserver/ibitmapserver/
---```
public interface IBitmapServer
```
## Methods

| Method | Description |
| --- | --- |
| [getARGBBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy)](#getARGBBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-) |  |
| [getByteBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy)](#getByteBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-) |  |
| [getHistogram(int Region, BitmapFilterType aFilterType, boolean isCopy)](#getHistogram-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-) |  |
| [getImageEntity(int Region, BitmapFilterType aFilterType, int aImageType, boolean isCopy)](#getImageEntity-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-int-boolean-) |  |
| [getOriginalBitmapSize()](#getOriginalBitmapSize--) |  |
| [getRegionCount()](#getRegionCount--) |  |
| [getRegionInfo(int RegionId)](#getRegionInfo-int-) |  |
### getARGBBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy) {#getARGBBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-}
```
public abstract ARGBBitmap getARGBBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy)
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
public abstract ByteBitmap getByteBitmap(int Region, BitmapFilterType aFilterType, boolean isCopy)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Region | int |  |
| aFilterType | [BitmapFilterType](../../com.aspose.barcode.barcoderecognition.internal/bitmapfiltertype) |  |
| isCopy | boolean |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getHistogram(int Region, BitmapFilterType aFilterType, boolean isCopy) {#getHistogram-int-com.aspose.barcode.barcoderecognition.internal.BitmapFilterType-boolean-}
```
public abstract int[] getHistogram(int Region, BitmapFilterType aFilterType, boolean isCopy)
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
public abstract ImageEntity getImageEntity(int Region, BitmapFilterType aFilterType, int aImageType, boolean isCopy)
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
public abstract System.Drawing.Size getOriginalBitmapSize()
```




**Returns:**
com.aspose.ms.System.Drawing.Size
### getRegionCount() {#getRegionCount--}
```
public abstract int getRegionCount()
```




**Returns:**
int
### getRegionInfo(int RegionId) {#getRegionInfo-int-}
```
public abstract BitmapRegionInfo getRegionInfo(int RegionId)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| RegionId | int |  |

**Returns:**
[BitmapRegionInfo](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/bitmapregioninfo)
