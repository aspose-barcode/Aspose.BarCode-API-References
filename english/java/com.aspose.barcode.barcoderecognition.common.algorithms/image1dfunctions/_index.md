---
title: Image1DFunctions
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 29
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/image1dfunctions/
---
**Inheritance:**
java.lang.Object
```
public class Image1DFunctions
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Image1DFunctions()](#Image1DFunctions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [binarizeAverage(byte[] bitmap1D, int HalfWindow, float aK)](#binarizeAverage-byte---int-float-) |  |
| [binarizeSavolaWithDynamicVariance(byte[] bitmap1D, int HalfWindow, float aK)](#binarizeSavolaWithDynamicVariance-byte---int-float-) |  |
| [binarizeWithThreshold(byte[] bitmap1D, byte Threshold)](#binarizeWithThreshold-byte---byte-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [eraseColor(byte[] bitmap1D, boolean isEraseBlack)](#eraseColor-byte---boolean-) |  |
| [getClass()](#getClass--) |  |
| [getOtsuThreshold(byte[] bitmap1D)](#getOtsuThreshold-byte---) |  |
| [hashCode()](#hashCode--) |  |
| [linearInterpolation(byte[] bitmap1D, int NewSize)](#linearInterpolation-byte---int-) |  |
| [nNInterpolation(byte[] bitmap1D, int NewSize)](#nNInterpolation-byte---int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [otsuBinarization(byte[] bitmap1D)](#otsuBinarization-byte---) |  |
| [tRSinghBinarization(byte[] Bitmap1D, int HalfWindow, float aK)](#tRSinghBinarization-byte---int-float-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Image1DFunctions() {#Image1DFunctions--}
```
public Image1DFunctions()
```


### binarizeAverage(byte[] bitmap1D, int HalfWindow, float aK) {#binarizeAverage-byte---int-float-}
```
public static byte[] binarizeAverage(byte[] bitmap1D, int HalfWindow, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap1D | byte[] |  |
| HalfWindow | int |  |
| aK | float |  |

**Returns:**
byte[]
### binarizeSavolaWithDynamicVariance(byte[] bitmap1D, int HalfWindow, float aK) {#binarizeSavolaWithDynamicVariance-byte---int-float-}
```
public static byte[] binarizeSavolaWithDynamicVariance(byte[] bitmap1D, int HalfWindow, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap1D | byte[] |  |
| HalfWindow | int |  |
| aK | float |  |

**Returns:**
byte[]
### binarizeWithThreshold(byte[] bitmap1D, byte Threshold) {#binarizeWithThreshold-byte---byte-}
```
public static byte[] binarizeWithThreshold(byte[] bitmap1D, byte Threshold)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap1D | byte[] |  |
| Threshold | byte |  |

**Returns:**
byte[]
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
### eraseColor(byte[] bitmap1D, boolean isEraseBlack) {#eraseColor-byte---boolean-}
```
public static byte[] eraseColor(byte[] bitmap1D, boolean isEraseBlack)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap1D | byte[] |  |
| isEraseBlack | boolean |  |

**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOtsuThreshold(byte[] bitmap1D) {#getOtsuThreshold-byte---}
```
public static byte getOtsuThreshold(byte[] bitmap1D)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap1D | byte[] |  |

**Returns:**
byte
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### linearInterpolation(byte[] bitmap1D, int NewSize) {#linearInterpolation-byte---int-}
```
public static byte[] linearInterpolation(byte[] bitmap1D, int NewSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap1D | byte[] |  |
| NewSize | int |  |

**Returns:**
byte[]
### nNInterpolation(byte[] bitmap1D, int NewSize) {#nNInterpolation-byte---int-}
```
public static byte[] nNInterpolation(byte[] bitmap1D, int NewSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap1D | byte[] |  |
| NewSize | int |  |

**Returns:**
byte[]
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### otsuBinarization(byte[] bitmap1D) {#otsuBinarization-byte---}
```
public static byte[] otsuBinarization(byte[] bitmap1D)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap1D | byte[] |  |

**Returns:**
byte[]
### tRSinghBinarization(byte[] Bitmap1D, int HalfWindow, float aK) {#tRSinghBinarization-byte---int-float-}
```
public static byte[] tRSinghBinarization(byte[] Bitmap1D, int HalfWindow, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Bitmap1D | byte[] |  |
| HalfWindow | int |  |
| aK | float |  |

**Returns:**
byte[]
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

