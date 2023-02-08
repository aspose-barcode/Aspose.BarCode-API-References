---
title: IntegralImage
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 32
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/integralimage/
---
**Inheritance:**
java.lang.Object
```
public class IntegralImage
```
## Constructors

| Constructor | Description |
| --- | --- |
| [IntegralImage(FloatBitmap aBitmap)](#IntegralImage-com.aspose.barcode.common.bitmaps.FloatBitmap-) |  |
| [IntegralImage(ByteBitmap aBitmap)](#IntegralImage-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [IntegralImage(IntegralImage aImage)](#IntegralImage-com.aspose.barcode.barcoderecognition.common.algorithms.IntegralImage-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAverageFromArea(int aLeft, int aTop, int aRight, int aBottom)](#getAverageFromArea-int-int-int-int-) |  |
| [getAverageFromWindow(int aX, int aY, int aWindow)](#getAverageFromWindow-int-int-int-) |  |
| [getClass()](#getClass--) |  |
| [getHeight()](#getHeight--) |  |
| [getSummAndAreaFromWindow(int aX, int aY, int aWindow)](#getSummAndAreaFromWindow-int-int-int-) |  |
| [getWidth()](#getWidth--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IntegralImage(FloatBitmap aBitmap) {#IntegralImage-com.aspose.barcode.common.bitmaps.FloatBitmap-}
```
public IntegralImage(FloatBitmap aBitmap)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap) |  |

### IntegralImage(ByteBitmap aBitmap) {#IntegralImage-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public IntegralImage(ByteBitmap aBitmap)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

### IntegralImage(IntegralImage aImage) {#IntegralImage-com.aspose.barcode.barcoderecognition.common.algorithms.IntegralImage-}
```
public IntegralImage(IntegralImage aImage)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aImage | [IntegralImage](../../com.aspose.barcode.barcoderecognition.common.algorithms/integralimage) |  |

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
### getAverageFromArea(int aLeft, int aTop, int aRight, int aBottom) {#getAverageFromArea-int-int-int-int-}
```
public float getAverageFromArea(int aLeft, int aTop, int aRight, int aBottom)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLeft | int |  |
| aTop | int |  |
| aRight | int |  |
| aBottom | int |  |

**Returns:**
float
### getAverageFromWindow(int aX, int aY, int aWindow) {#getAverageFromWindow-int-int-int-}
```
public float getAverageFromWindow(int aX, int aY, int aWindow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aX | int |  |
| aY | int |  |
| aWindow | int |  |

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeight() {#getHeight--}
```
public int getHeight()
```




**Returns:**
int
### getSummAndAreaFromWindow(int aX, int aY, int aWindow) {#getSummAndAreaFromWindow-int-int-int-}
```
public IntegralImage.SummAndArea getSummAndAreaFromWindow(int aX, int aY, int aWindow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aX | int |  |
| aY | int |  |
| aWindow | int |  |

**Returns:**
[SummAndArea](../../com.aspose.barcode.barcoderecognition.common.algorithms/summandarea)
### getWidth() {#getWidth--}
```
public int getWidth()
```




**Returns:**
int
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

