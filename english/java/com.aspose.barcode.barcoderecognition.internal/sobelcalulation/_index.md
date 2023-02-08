---
title: SobelCalulation
second_title: Aspose.BarCode for Java API Reference
description: This class contains convolution of Sobel.
type: docs
weight: 44
url: /java/com.aspose.barcode.barcoderecognition.internal/sobelcalulation/
---
**Inheritance:**
java.lang.Object
```
public class SobelCalulation
```

This class contains convolution of Sobel.
## Constructors

| Constructor | Description |
| --- | --- |
| [SobelCalulation()](#SobelCalulation--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeText(ByteBitmap bitmap)](#removeText-com.aspose.barcode.common.bitmaps.ByteBitmap-) | try remove text in the bitmap (use sobel convolutions) |
| [sobelConvolution(ByteBitmap bitmap, boolean drawAngle)](#sobelConvolution-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-) | Calculate a sobel convolution |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SobelCalulation() {#SobelCalulation--}
```
public SobelCalulation()
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeText(ByteBitmap bitmap) {#removeText-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap removeText(ByteBitmap bitmap)
```


try remove text in the bitmap (use sobel convolutions)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - 
### sobelConvolution(ByteBitmap bitmap, boolean drawAngle) {#sobelConvolution-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-}
```
public static ByteBitmap sobelConvolution(ByteBitmap bitmap, boolean drawAngle)
```


Calculate a sobel convolution

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | input bitmap |
| drawAngle | boolean | Outputs a steering angle (0-180 degrees) if value "true" of drawAngle, else draw gradient |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - 
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

