---
title: BitmapImageSource
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.bitmapserver/bitmapimagesource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class BitmapImageSource implements System.IDisposable
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BitmapImageSource(System.Drawing.Bitmap aBitmap)](#BitmapImageSource-com.aspose.ms.System.Drawing.Bitmap-) |  |
| [BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Drawing.Rectangle aArea)](#BitmapImageSource-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Collections.Generic.List<System.Drawing.Rectangle> aRegionsList)](#BitmapImageSource-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Drawing.Rectangle--) |  |
| [BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Drawing.Rectangle[] aRegionsList)](#BitmapImageSource-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle---) |  |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fitRectangleToBitmap(System.Drawing.Rectangle aRect)](#fitRectangleToBitmap-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [getClass()](#getClass--) |  |
| [getOriginalSize()](#getOriginalSize--) |  |
| [getRegionData(int Index)](#getRegionData-int-) |  |
| [getRegionInfo(int Index)](#getRegionInfo-int-) |  |
| [getRegionRectangle(int Index)](#getRegionRectangle-int-) |  |
| [getRegionsCount()](#getRegionsCount--) |  |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BitmapImageSource(System.Drawing.Bitmap aBitmap) {#BitmapImageSource-com.aspose.ms.System.Drawing.Bitmap-}
```
public BitmapImageSource(System.Drawing.Bitmap aBitmap)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | com.aspose.ms.System.Drawing.Bitmap |  |

### BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Drawing.Rectangle aArea) {#BitmapImageSource-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle-}
```
public BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Drawing.Rectangle aArea)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | com.aspose.ms.System.Drawing.Bitmap |  |
| aArea | com.aspose.ms.System.Drawing.Rectangle |  |

### BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Collections.Generic.List<System.Drawing.Rectangle> aRegionsList) {#BitmapImageSource-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Drawing.Rectangle--}
```
public BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Collections.Generic.List<System.Drawing.Rectangle> aRegionsList)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | com.aspose.ms.System.Drawing.Bitmap |  |
| aRegionsList | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Drawing.Rectangle> |  |

### BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Drawing.Rectangle[] aRegionsList) {#BitmapImageSource-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle---}
```
public BitmapImageSource(System.Drawing.Bitmap aBitmap, System.Drawing.Rectangle[] aRegionsList)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | com.aspose.ms.System.Drawing.Bitmap |  |
| aRegionsList | com.aspose.ms.System.Drawing.Rectangle[] |  |

### dispose() {#dispose--}
```
public final void dispose()
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
### fitRectangleToBitmap(System.Drawing.Rectangle aRect) {#fitRectangleToBitmap-com.aspose.ms.System.Drawing.Rectangle-}
```
public final System.Drawing.Rectangle fitRectangleToBitmap(System.Drawing.Rectangle aRect)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRect | com.aspose.ms.System.Drawing.Rectangle |  |

**Returns:**
com.aspose.ms.System.Drawing.Rectangle
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOriginalSize() {#getOriginalSize--}
```
public final System.Drawing.Size getOriginalSize()
```




**Returns:**
com.aspose.ms.System.Drawing.Size
### getRegionData(int Index) {#getRegionData-int-}
```
public BitmapRegionData getRegionData(int Index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Index | int |  |

**Returns:**
[BitmapRegionData](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/bitmapregiondata)
### getRegionInfo(int Index) {#getRegionInfo-int-}
```
public final BitmapRegionInfo getRegionInfo(int Index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Index | int |  |

**Returns:**
[BitmapRegionInfo](../../com.aspose.barcode.barcoderecognition.recognition.bitmapserver/bitmapregioninfo)
### getRegionRectangle(int Index) {#getRegionRectangle-int-}
```
public final System.Drawing.Rectangle getRegionRectangle(int Index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Index | int |  |

**Returns:**
com.aspose.ms.System.Drawing.Rectangle
### getRegionsCount() {#getRegionsCount--}
```
public final int getRegionsCount()
```




**Returns:**
int
### getResolution() {#getResolution--}
```
public final System.Drawing.SizeF getResolution()
```




**Returns:**
com.aspose.ms.System.Drawing.SizeF
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

