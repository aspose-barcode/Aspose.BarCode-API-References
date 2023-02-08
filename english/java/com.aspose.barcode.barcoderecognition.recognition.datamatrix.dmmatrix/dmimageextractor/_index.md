---
title: DMImageExtractor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 15
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix/dmimageextractor/
---
**Inheritance:**
java.lang.Object
```
public class DMImageExtractor
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DMImageExtractor()](#DMImageExtractor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [checkECC000_140Dimension(DMDimension aDimension)](#checkECC000-140Dimension-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix.DMDimension-) |  |
| [checkECC200Dimension(DMDimension aDimension)](#checkECC200Dimension-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix.DMDimension-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractResizedDMImageFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap, DMDimension aNewDimension, boolean isBilinear, boolean isBinarize)](#extractResizedDMImageFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix.DMDimension-boolean-boolean-) |  |
| [getClass()](#getClass--) |  |
| [getECC000_140DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive)](#getECC000-140DimensionListFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-boolean-) |  |
| [getECC000_140DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive, double aMaxDimensionDistToFail)](#getECC000-140DimensionListFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-boolean-double-) |  |
| [getECC200DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive)](#getECC200DimensionListFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-boolean-) |  |
| [getECC200DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive, double aMaxDimensionDistToFail)](#getECC200DimensionListFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-boolean-double-) |  |
| [getMaxDimensionError(DMRegionExt aRegion)](#getMaxDimensionError-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-) |  |
| [getMaxDimensionError(double aRows, double aCols)](#getMaxDimensionError-double-double-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DMImageExtractor() {#DMImageExtractor--}
```
public DMImageExtractor()
```


### checkECC000_140Dimension(DMDimension aDimension) {#checkECC000-140Dimension-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix.DMDimension-}
```
public static boolean checkECC000_140Dimension(DMDimension aDimension)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aDimension | [DMDimension](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix/dmdimension) |  |

**Returns:**
boolean
### checkECC200Dimension(DMDimension aDimension) {#checkECC200Dimension-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix.DMDimension-}
```
public static boolean checkECC200Dimension(DMDimension aDimension)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aDimension | [DMDimension](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix/dmdimension) |  |

**Returns:**
boolean
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
### extractResizedDMImageFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap, DMDimension aNewDimension, boolean isBilinear, boolean isBinarize) {#extractResizedDMImageFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix.DMDimension-boolean-boolean-}
```
public static DMImage extractResizedDMImageFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap, DMDimension aNewDimension, boolean isBilinear, boolean isBinarize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aNewDimension | [DMDimension](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix/dmdimension) |  |
| isBilinear | boolean |  |
| isBinarize | boolean |  |

**Returns:**
[DMImage](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmmatrix/dmimage)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECC000_140DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive) {#getECC000-140DimensionListFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-boolean-}
```
public static System.Collections.Generic.List<DMDimension> getECC000_140DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| isAdaptive | boolean |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
### getECC000_140DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive, double aMaxDimensionDistToFail) {#getECC000-140DimensionListFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-boolean-double-}
```
public static System.Collections.Generic.List<DMDimension> getECC000_140DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive, double aMaxDimensionDistToFail)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| isAdaptive | boolean |  |
| aMaxDimensionDistToFail | double |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
### getECC200DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive) {#getECC200DimensionListFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-boolean-}
```
public static System.Collections.Generic.List<DMDimension> getECC200DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| isAdaptive | boolean |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
### getECC200DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive, double aMaxDimensionDistToFail) {#getECC200DimensionListFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-boolean-double-}
```
public static System.Collections.Generic.List<DMDimension> getECC200DimensionListFromDMRegion(DMRegionExt aRegion, boolean isAdaptive, double aMaxDimensionDistToFail)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| isAdaptive | boolean |  |
| aMaxDimensionDistToFail | double |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
### getMaxDimensionError(DMRegionExt aRegion) {#getMaxDimensionError-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-}
```
public static double getMaxDimensionError(DMRegionExt aRegion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |

**Returns:**
double
### getMaxDimensionError(double aRows, double aCols) {#getMaxDimensionError-double-double-}
```
public static double getMaxDimensionError(double aRows, double aCols)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRows | double |  |
| aCols | double |  |

**Returns:**
double
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

