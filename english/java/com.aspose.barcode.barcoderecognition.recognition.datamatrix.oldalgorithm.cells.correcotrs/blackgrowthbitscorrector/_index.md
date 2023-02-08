---
title: BlackGrowthBitsCorrector
second_title: Aspose.BarCode for Java API Reference
description: This class contains algorithms for the black growth effect correction
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.correcotrs/blackgrowthbitscorrector/
---
**Inheritance:**
java.lang.Object
```
public class BlackGrowthBitsCorrector
```

This class contains algorithms for the black growth effect correction
## Constructors

| Constructor | Description |
| --- | --- |
| [BlackGrowthBitsCorrector()](#BlackGrowthBitsCorrector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [correctForSmallModule(ByteBitmap byteBitmap, int separatrix, BitArrayArray bitMatrix, RegionalTransformation2D transf)](#correctForSmallModule-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-) | Correct bits matrix to recognize datamatrix with growth effects(work for ~3px module only) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [estimateGrowthByTransformation(ByteBitmap byteBitmap, int separatrix, BitArrayArray bitMatrix, RegionalTransformation2D transf, float module)](#estimateGrowthByTransformation-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-float-) | Estimate growth print effect in percents. |
| [estimateModuleByTransformation(int dimensionX, int dimensionY, RegionalTransformation2D transf)](#estimateModuleByTransformation-int-int-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-) | Estimate module |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlackGrowthBitsCorrector() {#BlackGrowthBitsCorrector--}
```
public BlackGrowthBitsCorrector()
```


### correctForSmallModule(ByteBitmap byteBitmap, int separatrix, BitArrayArray bitMatrix, RegionalTransformation2D transf) {#correctForSmallModule-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-}
```
public static BitArrayArray correctForSmallModule(ByteBitmap byteBitmap, int separatrix, BitArrayArray bitMatrix, RegionalTransformation2D transf)
```


Correct bits matrix to recognize datamatrix with growth effects(work for ~3px module only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte bitmap |
| separatrix | int | separatrix |
| bitMatrix | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) | bit matrix |
| transf | [RegionalTransformation2D](../../com.aspose.barcode.barcoderecognition.internal/regionaltransformation2d) | a transformation |

**Returns:**
[BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) - Return corrected bits or null
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
### estimateGrowthByTransformation(ByteBitmap byteBitmap, int separatrix, BitArrayArray bitMatrix, RegionalTransformation2D transf, float module) {#estimateGrowthByTransformation-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-float-}
```
public static float estimateGrowthByTransformation(ByteBitmap byteBitmap, int separatrix, BitArrayArray bitMatrix, RegionalTransformation2D transf, float module)
```


Estimate growth print effect in percents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte bitmap |
| separatrix | int | separatrix |
| bitMatrix | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) | bit matrix |
| transf | [RegionalTransformation2D](../../com.aspose.barcode.barcoderecognition.internal/regionaltransformation2d) | transformation |
| module | float | module |

**Returns:**
float - Value "100" is no growth. Value "110" and more is growth.
### estimateModuleByTransformation(int dimensionX, int dimensionY, RegionalTransformation2D transf) {#estimateModuleByTransformation-int-int-com.aspose.barcode.barcoderecognition.internal.RegionalTransformation2D-}
```
public static float estimateModuleByTransformation(int dimensionX, int dimensionY, RegionalTransformation2D transf)
```


Estimate module

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dimensionX | int | dimension x |
| dimensionY | int | dimension y |
| transf | [RegionalTransformation2D](../../com.aspose.barcode.barcoderecognition.internal/regionaltransformation2d) | transformation |

**Returns:**
float - 
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

