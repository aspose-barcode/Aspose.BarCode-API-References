---
title: ImageAlgorithms
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.deconvolution/imagealgorithms/
---
**Inheritance:**
java.lang.Object
```
public class ImageAlgorithms
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageAlgorithms()](#ImageAlgorithms--) |  |
## Methods

| Method | Description |
| --- | --- |
| [autoContrastByEqualization(ByteBitmap aBmp)](#autoContrastByEqualization-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [autoContrastBySides(ByteBitmap aBmp, float Sides)](#autoContrastBySides-com.aspose.barcode.common.bitmaps.ByteBitmap-float-) |  |
| [autoContrastFloat(FloatBitmap aBmp, float threshold)](#autoContrastFloat-com.aspose.barcode.common.bitmaps.FloatBitmap-float-) |  |
| [autoContrastFloatBySides(FloatBitmap aBmp, int PrevHistCnt, float Sides)](#autoContrastFloatBySides-com.aspose.barcode.common.bitmaps.FloatBitmap-int-float-) |  |
| [autoContrastShort(ShortBitmap aBmp)](#autoContrastShort-com.aspose.barcode.common.bitmaps.ShortBitmap-) |  |
| [brightnessGamma(ByteBitmap aBmp)](#brightnessGamma-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [brightnessGamma(ByteBitmap aBmp, double aGamma)](#brightnessGamma-com.aspose.barcode.common.bitmaps.ByteBitmap-double-) |  |
| [brightnessGammaLevels(ByteBitmap aBmp)](#brightnessGammaLevels-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [brightnessGammaLevels(ByteBitmap aBmp, float aC, float aPhi)](#brightnessGammaLevels-com.aspose.barcode.common.bitmaps.ByteBitmap-float-float-) |  |
| [brightnessLogarithmicLevels(ByteBitmap aBmp)](#brightnessLogarithmicLevels-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [brightnessLogarithmicLevels(ByteBitmap aBmp, float aC, float aPhi)](#brightnessLogarithmicLevels-com.aspose.barcode.common.bitmaps.ByteBitmap-float-float-) |  |
| [classicAutoContrast(ByteBitmap aBmp)](#classicAutoContrast-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHistogramFromByteBitmap(ByteBitmap aBmp)](#getHistogramFromByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getHistogramFromRectangle(ByteBitmap byteBitmap, System.Drawing.Rectangle rectangle)](#getHistogramFromRectangle-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-) | Get the histogram for the rectangle on the bytebitmap. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAlgorithms() {#ImageAlgorithms--}
```
public ImageAlgorithms()
```


### autoContrastByEqualization(ByteBitmap aBmp) {#autoContrastByEqualization-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap autoContrastByEqualization(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### autoContrastBySides(ByteBitmap aBmp, float Sides) {#autoContrastBySides-com.aspose.barcode.common.bitmaps.ByteBitmap-float-}
```
public static ByteBitmap autoContrastBySides(ByteBitmap aBmp, float Sides)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| Sides | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### autoContrastFloat(FloatBitmap aBmp, float threshold) {#autoContrastFloat-com.aspose.barcode.common.bitmaps.FloatBitmap-float-}
```
public static FloatBitmap autoContrastFloat(FloatBitmap aBmp, float threshold)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap) |  |
| threshold | float |  |

**Returns:**
[FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap)
### autoContrastFloatBySides(FloatBitmap aBmp, int PrevHistCnt, float Sides) {#autoContrastFloatBySides-com.aspose.barcode.common.bitmaps.FloatBitmap-int-float-}
```
public static ByteBitmap autoContrastFloatBySides(FloatBitmap aBmp, int PrevHistCnt, float Sides)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [FloatBitmap](../../com.aspose.barcode.common.bitmaps/floatbitmap) |  |
| PrevHistCnt | int |  |
| Sides | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### autoContrastShort(ShortBitmap aBmp) {#autoContrastShort-com.aspose.barcode.common.bitmaps.ShortBitmap-}
```
public static ShortBitmap autoContrastShort(ShortBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ShortBitmap](../../com.aspose.barcode.common.bitmaps/shortbitmap) |  |

**Returns:**
[ShortBitmap](../../com.aspose.barcode.common.bitmaps/shortbitmap)
### brightnessGamma(ByteBitmap aBmp) {#brightnessGamma-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap brightnessGamma(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### brightnessGamma(ByteBitmap aBmp, double aGamma) {#brightnessGamma-com.aspose.barcode.common.bitmaps.ByteBitmap-double-}
```
public static ByteBitmap brightnessGamma(ByteBitmap aBmp, double aGamma)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aGamma | double |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### brightnessGammaLevels(ByteBitmap aBmp) {#brightnessGammaLevels-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap brightnessGammaLevels(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### brightnessGammaLevels(ByteBitmap aBmp, float aC, float aPhi) {#brightnessGammaLevels-com.aspose.barcode.common.bitmaps.ByteBitmap-float-float-}
```
public static ByteBitmap brightnessGammaLevels(ByteBitmap aBmp, float aC, float aPhi)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aC | float |  |
| aPhi | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### brightnessLogarithmicLevels(ByteBitmap aBmp) {#brightnessLogarithmicLevels-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap brightnessLogarithmicLevels(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### brightnessLogarithmicLevels(ByteBitmap aBmp, float aC, float aPhi) {#brightnessLogarithmicLevels-com.aspose.barcode.common.bitmaps.ByteBitmap-float-float-}
```
public static ByteBitmap brightnessLogarithmicLevels(ByteBitmap aBmp, float aC, float aPhi)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aC | float |  |
| aPhi | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### classicAutoContrast(ByteBitmap aBmp) {#classicAutoContrast-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap classicAutoContrast(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

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
### getHistogramFromByteBitmap(ByteBitmap aBmp) {#getHistogramFromByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int[] getHistogramFromByteBitmap(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
int[]
### getHistogramFromRectangle(ByteBitmap byteBitmap, System.Drawing.Rectangle rectangle) {#getHistogramFromRectangle-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-}
```
public static int[] getHistogramFromRectangle(ByteBitmap byteBitmap, System.Drawing.Rectangle rectangle)
```


Get the histogram for the rectangle on the bytebitmap. If rectangle is bigger than bytebitmap, get histogram for the interception

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | Input rectangle |

**Returns:**
int[] - A histogram
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

