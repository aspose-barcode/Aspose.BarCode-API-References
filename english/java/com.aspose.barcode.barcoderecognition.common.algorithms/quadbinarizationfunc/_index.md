---
title: QuadBinarizationFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 42
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/quadbinarizationfunc/
---
**Inheritance:**
java.lang.Object
```
public class QuadBinarizationFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [QuadBinarizationFunc()](#QuadBinarizationFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [averageBinarization(ByteBitmap aBitmap, int[] aHistogramm)](#averageBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---) |  |
| [averageBinarization(ByteBitmap aBitmap, int[] aHistogramm, float aK)](#averageBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---float-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHistogrammAverage(int[] aHistogramm)](#getHistogrammAverage-int---) |  |
| [getHistogrammDeviance(int[] aHistogramm, double Average)](#getHistogrammDeviance-int---double-) |  |
| [getQuadHistogramm(ByteBitmap aBitmap, QuadPoints aQuad)](#getQuadHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-) |  |
| [getQuadHistogramm(ByteBitmap aBitmap, QuadPoints aQuad, int aMaxScanLines)](#getQuadHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-) |  |
| [getQuadThresholdOtsuMethod(ByteBitmap aBitmap, QuadPoints aQuad, int aMaxScanLines)](#getQuadThresholdOtsuMethod-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sauvolaBinarization(ByteBitmap aBitmap)](#sauvolaBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [sauvolaBinarization(ByteBitmap aBitmap, float aK)](#sauvolaBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-float-) |  |
| [sauvolaBinarization(ByteBitmap aBitmap, int[] aHistogramm)](#sauvolaBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---) |  |
| [sauvolaBinarization(ByteBitmap aBitmap, int[] aHistogramm, float aK)](#sauvolaBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---float-) |  |
| [tRSinghBinarization(ByteBitmap aBitmap)](#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [tRSinghBinarization(ByteBitmap aBitmap, float aK)](#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-float-) |  |
| [tRSinghBinarization(ByteBitmap aBitmap, int[] aHistogramm)](#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---) |  |
| [tRSinghBinarization(ByteBitmap aBitmap, int[] aHistogramm, float K)](#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---float-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QuadBinarizationFunc() {#QuadBinarizationFunc--}
```
public QuadBinarizationFunc()
```


### averageBinarization(ByteBitmap aBitmap, int[] aHistogramm) {#averageBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---}
```
public static ByteBitmap averageBinarization(ByteBitmap aBitmap, int[] aHistogramm)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aHistogramm | int[] |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### averageBinarization(ByteBitmap aBitmap, int[] aHistogramm, float aK) {#averageBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---float-}
```
public static ByteBitmap averageBinarization(ByteBitmap aBitmap, int[] aHistogramm, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aHistogramm | int[] |  |
| aK | float |  |

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
### getHistogrammAverage(int[] aHistogramm) {#getHistogrammAverage-int---}
```
public static double getHistogrammAverage(int[] aHistogramm)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aHistogramm | int[] |  |

**Returns:**
double
### getHistogrammDeviance(int[] aHistogramm, double Average) {#getHistogrammDeviance-int---double-}
```
public static double getHistogrammDeviance(int[] aHistogramm, double Average)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aHistogramm | int[] |  |
| Average | double |  |

**Returns:**
double
### getQuadHistogramm(ByteBitmap aBitmap, QuadPoints aQuad) {#getQuadHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-}
```
public static int[] getQuadHistogramm(ByteBitmap aBitmap, QuadPoints aQuad)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |

**Returns:**
int[]
### getQuadHistogramm(ByteBitmap aBitmap, QuadPoints aQuad, int aMaxScanLines) {#getQuadHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-}
```
public static int[] getQuadHistogramm(ByteBitmap aBitmap, QuadPoints aQuad, int aMaxScanLines)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |
| aMaxScanLines | int |  |

**Returns:**
int[]
### getQuadThresholdOtsuMethod(ByteBitmap aBitmap, QuadPoints aQuad, int aMaxScanLines) {#getQuadThresholdOtsuMethod-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-}
```
public static byte getQuadThresholdOtsuMethod(ByteBitmap aBitmap, QuadPoints aQuad, int aMaxScanLines)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |
| aMaxScanLines | int |  |

**Returns:**
byte
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




### sauvolaBinarization(ByteBitmap aBitmap) {#sauvolaBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap sauvolaBinarization(ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### sauvolaBinarization(ByteBitmap aBitmap, float aK) {#sauvolaBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-float-}
```
public static ByteBitmap sauvolaBinarization(ByteBitmap aBitmap, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aK | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### sauvolaBinarization(ByteBitmap aBitmap, int[] aHistogramm) {#sauvolaBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---}
```
public static ByteBitmap sauvolaBinarization(ByteBitmap aBitmap, int[] aHistogramm)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aHistogramm | int[] |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### sauvolaBinarization(ByteBitmap aBitmap, int[] aHistogramm, float aK) {#sauvolaBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---float-}
```
public static ByteBitmap sauvolaBinarization(ByteBitmap aBitmap, int[] aHistogramm, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aHistogramm | int[] |  |
| aK | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### tRSinghBinarization(ByteBitmap aBitmap) {#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap tRSinghBinarization(ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### tRSinghBinarization(ByteBitmap aBitmap, float aK) {#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-float-}
```
public static ByteBitmap tRSinghBinarization(ByteBitmap aBitmap, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aK | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### tRSinghBinarization(ByteBitmap aBitmap, int[] aHistogramm) {#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---}
```
public static ByteBitmap tRSinghBinarization(ByteBitmap aBitmap, int[] aHistogramm)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aHistogramm | int[] |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### tRSinghBinarization(ByteBitmap aBitmap, int[] aHistogramm, float K) {#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-int---float-}
```
public static ByteBitmap tRSinghBinarization(ByteBitmap aBitmap, int[] aHistogramm, float K)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aHistogramm | int[] |  |
| K | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
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

