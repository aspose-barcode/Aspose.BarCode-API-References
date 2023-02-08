---
title: WaveAlgorithm
second_title: Aspose.BarCode for Java API Reference
description: Realization of wave algoritm in 2D binarry matrix where -1 untouchable point 0 unamrked point any positive value is marked point
type: docs
weight: 49
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/wavealgorithm/
---
**Inheritance:**
java.lang.Object
```
public class WaveAlgorithm
```

Realization of wave algoritm in 2D binarry matrix, where -1 untouchable point 0 unamrked point any positive value is marked point
## Constructors

| Constructor | Description |
| --- | --- |
| [WaveAlgorithm()](#WaveAlgorithm--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMarkBitmapSByteBitmapWithColor(ByteBitmap aBitmap, byte aColor)](#getMarkBitmapSByteBitmapWithColor-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-) |  |
| [hashCode()](#hashCode--) |  |
| [internalWaveStep(IntBitmap aArr, List<System.Drawing.Point> aOldWave, int aIter, boolean aStraight, List<System.Drawing.Point> aMarkedPts, int aMaxMarkedPoints)](#internalWaveStep-com.aspose.barcode.common.bitmaps.IntBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--int-boolean-java.util.List-com.aspose.ms.System.Drawing.Point--int-) | Wave algoritm function |
| [internalWaveStep(SByteBitmap aArr, List<System.Drawing.Point> aOldWave, byte aIter, boolean aStraight, List<System.Drawing.Point> aMarkedPts, int aMaxMarkedPoints)](#internalWaveStep-com.aspose.barcode.common.bitmaps.SByteBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--byte-boolean-java.util.List-com.aspose.ms.System.Drawing.Point--int-) | Wave algoritm function |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WaveAlgorithm() {#WaveAlgorithm--}
```
public WaveAlgorithm()
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
### getMarkBitmapSByteBitmapWithColor(ByteBitmap aBitmap, byte aColor) {#getMarkBitmapSByteBitmapWithColor-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-}
```
public static SByteBitmap getMarkBitmapSByteBitmapWithColor(ByteBitmap aBitmap, byte aColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aColor | byte |  |

**Returns:**
[SByteBitmap](../../com.aspose.barcode.common.bitmaps/sbytebitmap)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### internalWaveStep(IntBitmap aArr, List<System.Drawing.Point> aOldWave, int aIter, boolean aStraight, List<System.Drawing.Point> aMarkedPts, int aMaxMarkedPoints) {#internalWaveStep-com.aspose.barcode.common.bitmaps.IntBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--int-boolean-java.util.List-com.aspose.ms.System.Drawing.Point--int-}
```
public static int internalWaveStep(IntBitmap aArr, List<System.Drawing.Point> aOldWave, int aIter, boolean aStraight, List<System.Drawing.Point> aMarkedPts, int aMaxMarkedPoints)
```


Wave algoritm function

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aArr | [IntBitmap](../../com.aspose.barcode.common.bitmaps/intbitmap) | marked matrix with 1, 0 and positive values |
| aOldWave | java.util.List<com.aspose.ms.System.Drawing.Point> | Old wave |
| aIter | int | Iteration number |
| aStraight | boolean | use only straight lines, if false we use also diagonal lines |
| aMarkedPts | java.util.List<com.aspose.ms.System.Drawing.Point> | List of all marked points |
| aMaxMarkedPoints | int | Maximum number of marked points |

**Returns:**
int - Count of marked points
### internalWaveStep(SByteBitmap aArr, List<System.Drawing.Point> aOldWave, byte aIter, boolean aStraight, List<System.Drawing.Point> aMarkedPts, int aMaxMarkedPoints) {#internalWaveStep-com.aspose.barcode.common.bitmaps.SByteBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--byte-boolean-java.util.List-com.aspose.ms.System.Drawing.Point--int-}
```
public static int internalWaveStep(SByteBitmap aArr, List<System.Drawing.Point> aOldWave, byte aIter, boolean aStraight, List<System.Drawing.Point> aMarkedPts, int aMaxMarkedPoints)
```


Wave algoritm function

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aArr | [SByteBitmap](../../com.aspose.barcode.common.bitmaps/sbytebitmap) | marked matrix with 1, 0 and positive values |
| aOldWave | java.util.List<com.aspose.ms.System.Drawing.Point> | Old wave |
| aIter | byte | Iteration number |
| aStraight | boolean | use only staight lines, if false we use also diagonal lines |
| aMarkedPts | java.util.List<com.aspose.ms.System.Drawing.Point> | List of all marked points |
| aMaxMarkedPoints | int | Maximum number of marked points |

**Returns:**
int - Count of marked points
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

