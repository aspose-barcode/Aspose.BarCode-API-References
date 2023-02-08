---
title: ImageInterpolation
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 30
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/imageinterpolation/
---
**Inheritance:**
java.lang.Object
```
public class ImageInterpolation
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageInterpolation()](#ImageInterpolation--) |  |
## Methods

| Method | Description |
| --- | --- |
| [bilinearInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize)](#bilinearInterpolation-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [nNDecreasedInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize)](#nNDecreasedInterpolation-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-) | Decrease bitmap with average brightness in cell |
| [nNInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize)](#nNInterpolation-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageInterpolation() {#ImageInterpolation--}
```
public ImageInterpolation()
```


### bilinearInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize) {#bilinearInterpolation-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-}
```
public static ByteBitmap bilinearInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| NewSize | com.aspose.ms.System.Drawing.Size |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
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
### nNDecreasedInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize) {#nNDecreasedInterpolation-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-}
```
public static ByteBitmap nNDecreasedInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize)
```


Decrease bitmap with average brightness in cell

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | processing bitmap |
| NewSize | com.aspose.ms.System.Drawing.Size | new bitmap size |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - resized and interpolated bitmap
### nNInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize) {#nNInterpolation-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Size-}
```
public static ByteBitmap nNInterpolation(ByteBitmap aBitmap, System.Drawing.Size NewSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| NewSize | com.aspose.ms.System.Drawing.Size |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
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

