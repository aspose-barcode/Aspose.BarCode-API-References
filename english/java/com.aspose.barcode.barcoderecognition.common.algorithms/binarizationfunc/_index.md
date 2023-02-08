---
title: BinarizationFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/binarizationfunc/
---
**Inheritance:**
java.lang.Object
```
public class BinarizationFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BinarizationFunc()](#BinarizationFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [adaptiveAverageBinarizeImage(ByteBitmap bitmap, int radius)](#adaptiveAverageBinarizeImage-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [adaptiveBinarizeImage(ByteBitmap bitmap)](#adaptiveBinarizeImage-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [adaptiveBinarizeImage(ByteBitmap bitmap, int radius)](#adaptiveBinarizeImage-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [binarizeIntegralImageByMiddle(ByteBitmap aBitmap, int aWindow)](#binarizeIntegralImageByMiddle-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [binarizeIntegralImageByMiddle(ByteBitmap aBitmap, int aWindow, float aNormalization)](#binarizeIntegralImageByMiddle-com.aspose.barcode.common.bitmaps.ByteBitmap-int-float-) |  |
| [binarizeOtsu(ByteBitmap aBitmap)](#binarizeOtsu-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [binarizeSavola(ByteBitmap aBitmap)](#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [binarizeSavola(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck)](#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [binarizeSavola(ByteBitmap aBitmap, int aWindow)](#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [binarizeSavola(ByteBitmap aBitmap, int aWindow, ITerminationCheck aTerminationCheck)](#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [binarizeSavola(ByteBitmap aBitmap, int aWindow, float aK)](#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-int-float-) |  |
| [binarizeSavola(ByteBitmap aBitmap, int aWindow, float aK, ITerminationCheck aTerminationCheck)](#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-int-float-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [binarizeSavolaOtsu(ByteBitmap aBitmap)](#binarizeSavolaOtsu-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Combined Savola and Otsu binarization |
| [binarizeWithThreshold(ByteBitmap aBitmap, byte Threshold)](#binarizeWithThreshold-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitmapHistogram(ByteBitmap aBitmap)](#getBitmapHistogram-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getClass()](#getClass--) |  |
| [getDarknessThreshold(ByteBitmap aBitmap, double aDarkPixels)](#getDarknessThreshold-com.aspose.barcode.common.bitmaps.ByteBitmap-double-) | Recognizes threshold by bitmap white black pixels filling in most cases we have 50/50 of black and white dosts in barcodes area |
| [getDarknessThreshold(int[] aHistogram, double aDarkness, int aPixelsCnt)](#getDarknessThreshold-int---double-int-) | Recognizes threshold by bitmap white black pixels filling in most cases we have 50/50 of black and white dosts in barcodes area |
| [getThresholdOtsu(int[] histogramData)](#getThresholdOtsu-int---) |  |
| [getThresholdOtsuMethod(ByteBitmap aBitmap)](#getThresholdOtsuMethod-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getThresholdOtsuMethod(int[] histogramData)](#getThresholdOtsuMethod-int---) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [tRSinghBinarization(ByteBitmap aBitmap)](#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [tRSinghBinarization(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck)](#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [tRSinghBinarization(ByteBitmap aBitmap, float K, int HalfWindow)](#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-float-int-) |  |
| [tRSinghBinarization(ByteBitmap aBitmap, float K, int HalfWindow, ITerminationCheck aTerminationCheck)](#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-float-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BinarizationFunc() {#BinarizationFunc--}
```
public BinarizationFunc()
```


### adaptiveAverageBinarizeImage(ByteBitmap bitmap, int radius) {#adaptiveAverageBinarizeImage-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap adaptiveAverageBinarizeImage(ByteBitmap bitmap, int radius)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| radius | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### adaptiveBinarizeImage(ByteBitmap bitmap) {#adaptiveBinarizeImage-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap adaptiveBinarizeImage(ByteBitmap bitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### adaptiveBinarizeImage(ByteBitmap bitmap, int radius) {#adaptiveBinarizeImage-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap adaptiveBinarizeImage(ByteBitmap bitmap, int radius)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| radius | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeIntegralImageByMiddle(ByteBitmap aBitmap, int aWindow) {#binarizeIntegralImageByMiddle-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap binarizeIntegralImageByMiddle(ByteBitmap aBitmap, int aWindow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aWindow | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeIntegralImageByMiddle(ByteBitmap aBitmap, int aWindow, float aNormalization) {#binarizeIntegralImageByMiddle-com.aspose.barcode.common.bitmaps.ByteBitmap-int-float-}
```
public static ByteBitmap binarizeIntegralImageByMiddle(ByteBitmap aBitmap, int aWindow, float aNormalization)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aWindow | int |  |
| aNormalization | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeOtsu(ByteBitmap aBitmap) {#binarizeOtsu-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap binarizeOtsu(ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeSavola(ByteBitmap aBitmap) {#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap binarizeSavola(ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeSavola(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck) {#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static ByteBitmap binarizeSavola(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeSavola(ByteBitmap aBitmap, int aWindow) {#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap binarizeSavola(ByteBitmap aBitmap, int aWindow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aWindow | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeSavola(ByteBitmap aBitmap, int aWindow, ITerminationCheck aTerminationCheck) {#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static ByteBitmap binarizeSavola(ByteBitmap aBitmap, int aWindow, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aWindow | int |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeSavola(ByteBitmap aBitmap, int aWindow, float aK) {#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-int-float-}
```
public static ByteBitmap binarizeSavola(ByteBitmap aBitmap, int aWindow, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aWindow | int |  |
| aK | float |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeSavola(ByteBitmap aBitmap, int aWindow, float aK, ITerminationCheck aTerminationCheck) {#binarizeSavola-com.aspose.barcode.common.bitmaps.ByteBitmap-int-float-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static ByteBitmap binarizeSavola(ByteBitmap aBitmap, int aWindow, float aK, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aWindow | int |  |
| aK | float |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### binarizeSavolaOtsu(ByteBitmap aBitmap) {#binarizeSavolaOtsu-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static ByteBitmap binarizeSavolaOtsu(ByteBitmap aBitmap)
```


Combined Savola and Otsu binarization

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - Binarized bytebitmap
### binarizeWithThreshold(ByteBitmap aBitmap, byte Threshold) {#binarizeWithThreshold-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-}
```
public static ByteBitmap binarizeWithThreshold(ByteBitmap aBitmap, byte Threshold)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| Threshold | byte |  |

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
### getBitmapHistogram(ByteBitmap aBitmap) {#getBitmapHistogram-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int[] getBitmapHistogram(ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
int[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDarknessThreshold(ByteBitmap aBitmap, double aDarkPixels) {#getDarknessThreshold-com.aspose.barcode.common.bitmaps.ByteBitmap-double-}
```
public static byte getDarknessThreshold(ByteBitmap aBitmap, double aDarkPixels)
```


Recognizes threshold by bitmap white black pixels filling in most cases we have 50/50 of black and white dosts in barcodes area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | proceed bitmap |
| aDarkPixels | double | darkness of image, 0.3% image must be bright, 0.7 image must be dark |

**Returns:**
byte - threshold
### getDarknessThreshold(int[] aHistogram, double aDarkness, int aPixelsCnt) {#getDarknessThreshold-int---double-int-}
```
public static byte getDarknessThreshold(int[] aHistogram, double aDarkness, int aPixelsCnt)
```


Recognizes threshold by bitmap white black pixels filling in most cases we have 50/50 of black and white dosts in barcodes area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aHistogram | int[] | gray histogram |
| aDarkness | double | darkness of image, 0.3% image must be bright, 0.7 image must be dark |
| aPixelsCnt | int | cashed value of pizels countm if -1 or 0, it is calculated |

**Returns:**
byte - threshold
### getThresholdOtsu(int[] histogramData) {#getThresholdOtsu-int---}
```
public static int getThresholdOtsu(int[] histogramData)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| histogramData | int[] |  |

**Returns:**
int
### getThresholdOtsuMethod(ByteBitmap aBitmap) {#getThresholdOtsuMethod-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte getThresholdOtsuMethod(ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte
### getThresholdOtsuMethod(int[] histogramData) {#getThresholdOtsuMethod-int---}
```
public static byte getThresholdOtsuMethod(int[] histogramData)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| histogramData | int[] |  |

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
### tRSinghBinarization(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck) {#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static ByteBitmap tRSinghBinarization(ByteBitmap aBitmap, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### tRSinghBinarization(ByteBitmap aBitmap, float K, int HalfWindow) {#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-float-int-}
```
public static ByteBitmap tRSinghBinarization(ByteBitmap aBitmap, float K, int HalfWindow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| K | float |  |
| HalfWindow | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### tRSinghBinarization(ByteBitmap aBitmap, float K, int HalfWindow, ITerminationCheck aTerminationCheck) {#tRSinghBinarization-com.aspose.barcode.common.bitmaps.ByteBitmap-float-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static ByteBitmap tRSinghBinarization(ByteBitmap aBitmap, float K, int HalfWindow, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| K | float |  |
| HalfWindow | int |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

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

