---
title: BrightnessGamma
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.deconvolution/brightnessgamma/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.deconvolution.BBMap](../../com.aspose.barcode.barcoderecognition.deconvolution/bbmap)
```
public class BrightnessGamma extends BBMap
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BrightnessGamma()](#BrightnessGamma--) |  |
| [BrightnessGamma(double aGamma)](#BrightnessGamma-double-) |  |
## Fields

| Field | Description |
| --- | --- |
| [_mapArray](#-mapArray) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mapBitmap(ByteBitmap aBitmap, boolean isCopy)](#mapBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-) | Replaces pixels values by \_mapArray precalculated values |
| [mapBitmap1D(byte[] aBitmap, boolean isCopy)](#mapBitmap1D-byte---boolean-) | Replaces pixels values by \_mapArray precalculated values |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BrightnessGamma() {#BrightnessGamma--}
```
public BrightnessGamma()
```


### BrightnessGamma(double aGamma) {#BrightnessGamma-double-}
```
public BrightnessGamma(double aGamma)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGamma | double |  |

### _mapArray {#-mapArray}
```
public byte[] _mapArray
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
### mapBitmap(ByteBitmap aBitmap, boolean isCopy) {#mapBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-}
```
public ByteBitmap mapBitmap(ByteBitmap aBitmap, boolean isCopy)
```


Replaces pixels values by \_mapArray precalculated values

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | preprocessing bitmap |
| isCopy | boolean | copy the result or replace onsite |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - bitmap with replacing pixel brigtness
### mapBitmap1D(byte[] aBitmap, boolean isCopy) {#mapBitmap1D-byte---boolean-}
```
public byte[] mapBitmap1D(byte[] aBitmap, boolean isCopy)
```


Replaces pixels values by \_mapArray precalculated values

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | byte[] | preprocessing 1D bitmap |
| isCopy | boolean | copy the result or replace onsite |

**Returns:**
byte[] - 1D bitmap with replacing pixel brigtness
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

