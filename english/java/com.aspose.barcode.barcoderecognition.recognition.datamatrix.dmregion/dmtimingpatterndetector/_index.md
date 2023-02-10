---
title: DMTimingPatternDetector
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmtimingpatterndetector/
---
**Inheritance:**
java.lang.Object
```
public class DMTimingPatternDetector
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DMTimingPatternDetector()](#DMTimingPatternDetector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [detectDimensionByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap)](#detectDimensionByTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [detectDimensionByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper, int aRegionType)](#detectDimensionByTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-int-) |  |
| [detectRegionTypeByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap)](#detectRegionTypeByTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEcc200Ecc0140Probabilities(DMRegionExt aRegion, ByteBitmap aBitmap)](#getEcc200Ecc0140Probabilities-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getPrecisedCellSizesFromTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper)](#getPrecisedCellSizesFromTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [precisCellSizesFromTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper)](#precisCellSizesFromTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-) |  |
| [preciseDMRegionFourthPoint(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper)](#preciseDMRegionFourthPoint-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DMTimingPatternDetector() {#DMTimingPatternDetector--}
```
public DMTimingPatternDetector()
```


### detectDimensionByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap) {#detectDimensionByTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static DMDimension detectDimensionByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[DMDimension](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix/dmdimension)
### detectDimensionByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper, int aRegionType) {#detectDimensionByTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-int-}
```
public static DMDimension detectDimensionByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper, int aRegionType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| FilterSaltAndPaper | boolean |  |
| aRegionType | int |  |

**Returns:**
[DMDimension](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix/dmdimension)
### detectRegionTypeByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap) {#detectRegionTypeByTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int detectRegionTypeByTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
int
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
### getEcc200Ecc0140Probabilities(DMRegionExt aRegion, ByteBitmap aBitmap) {#getEcc200Ecc0140Probabilities-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static Tup<Double,Double> getEcc200Ecc0140Probabilities(DMRegionExt aRegion, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup)
### getPrecisedCellSizesFromTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper) {#getPrecisedCellSizesFromTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-}
```
public static Tup<Double,Double> getPrecisedCellSizesFromTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| FilterSaltAndPaper | boolean |  |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup)
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




### precisCellSizesFromTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper) {#precisCellSizesFromTimingPatterns-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-}
```
public static void precisCellSizesFromTimingPatterns(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| FilterSaltAndPaper | boolean |  |

### preciseDMRegionFourthPoint(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper) {#preciseDMRegionFourthPoint-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-}
```
public static void preciseDMRegionFourthPoint(DMRegionExt aRegion, ByteBitmap aBitmap, boolean FilterSaltAndPaper)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| FilterSaltAndPaper | boolean |  |

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

