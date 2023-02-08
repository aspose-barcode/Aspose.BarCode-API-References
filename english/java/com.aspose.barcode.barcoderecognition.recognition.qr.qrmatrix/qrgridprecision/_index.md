---
title: QRGridPrecision
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.qr.qrmatrix/qrgridprecision/
---
**Inheritance:**
java.lang.Object
```
public class QRGridPrecision
```
## Constructors

| Constructor | Description |
| --- | --- |
| [QRGridPrecision()](#QRGridPrecision--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createAlignmentGridFromVersion(int aVersion, double aCellSize)](#createAlignmentGridFromVersion-int-double-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPrecisedAlignmentGrid(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision)](#getPrecisedAlignmentGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-) |  |
| [getPrecisedBitMatrix(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision, int aBorder)](#getPrecisedBitMatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-int-) |  |
| [getPrecisedBitMatrix(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision, int aBorder, double aMinBlackDiffToMark)](#getPrecisedBitMatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-int-double-) |  |
| [getPrecisedPointGrid(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision)](#getPrecisedPointGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [preciseAlignmentsInGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, double aCellSize)](#preciseAlignmentsInGrid-com.aspose.barcode.common.bitmaps.AlignmentPatternsGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-double-) |  |
| [preciseAlignmentsInGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, double aCellSize, double aMaxDistFromUndetectedAlignment)](#preciseAlignmentsInGrid-com.aspose.barcode.common.bitmaps.AlignmentPatternsGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-double-double-) |  |
| [preciseAugmentedPatternsWithTimingPatterns(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, int aVersion, double aCellSize, boolean ForcePrecision)](#preciseAugmentedPatternsWithTimingPatterns-com.aspose.barcode.common.bitmaps.AlignmentPatternsGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-boolean-) |  |
| [preciseGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision)](#preciseGrid-com.aspose.barcode.common.bitmaps.AlignmentPatternsGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QRGridPrecision() {#QRGridPrecision--}
```
public QRGridPrecision()
```


### createAlignmentGridFromVersion(int aVersion, double aCellSize) {#createAlignmentGridFromVersion-int-double-}
```
public static AlignmentPatternsGrid createAlignmentGridFromVersion(int aVersion, double aCellSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aVersion | int |  |
| aCellSize | double |  |

**Returns:**
[AlignmentPatternsGrid](../../com.aspose.barcode.common.bitmaps/alignmentpatternsgrid)
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
### getPrecisedAlignmentGrid(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision) {#getPrecisedAlignmentGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-}
```
public static AlignmentPatternsGrid getPrecisedAlignmentGrid(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aVersion | int |  |
| aCellSize | double |  |
| aTimingForce | int |  |
| aAugmentedPrecision | int |  |

**Returns:**
[AlignmentPatternsGrid](../../com.aspose.barcode.common.bitmaps/alignmentpatternsgrid)
### getPrecisedBitMatrix(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision, int aBorder) {#getPrecisedBitMatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-int-}
```
public static ByteBitmap getPrecisedBitMatrix(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision, int aBorder)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aVersion | int |  |
| aCellSize | double |  |
| aTimingForce | int |  |
| aAugmentedPrecision | int |  |
| aBorder | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getPrecisedBitMatrix(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision, int aBorder, double aMinBlackDiffToMark) {#getPrecisedBitMatrix-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-int-double-}
```
public static ByteBitmap getPrecisedBitMatrix(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision, int aBorder, double aMinBlackDiffToMark)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aVersion | int |  |
| aCellSize | double |  |
| aTimingForce | int |  |
| aAugmentedPrecision | int |  |
| aBorder | int |  |
| aMinBlackDiffToMark | double |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getPrecisedPointGrid(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision) {#getPrecisedPointGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-}
```
public static PointFBitmap getPrecisedPointGrid(ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aVersion | int |  |
| aCellSize | double |  |
| aTimingForce | int |  |
| aAugmentedPrecision | int |  |

**Returns:**
[PointFBitmap](../../com.aspose.barcode.common.bitmaps/pointfbitmap)
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




### preciseAlignmentsInGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, double aCellSize) {#preciseAlignmentsInGrid-com.aspose.barcode.common.bitmaps.AlignmentPatternsGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-double-}
```
public static void preciseAlignmentsInGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, double aCellSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrid | [AlignmentPatternsGrid](../../com.aspose.barcode.common.bitmaps/alignmentpatternsgrid) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aCellSize | double |  |

### preciseAlignmentsInGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, double aCellSize, double aMaxDistFromUndetectedAlignment) {#preciseAlignmentsInGrid-com.aspose.barcode.common.bitmaps.AlignmentPatternsGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-double-double-}
```
public static void preciseAlignmentsInGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, double aCellSize, double aMaxDistFromUndetectedAlignment)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrid | [AlignmentPatternsGrid](../../com.aspose.barcode.common.bitmaps/alignmentpatternsgrid) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aCellSize | double |  |
| aMaxDistFromUndetectedAlignment | double |  |

### preciseAugmentedPatternsWithTimingPatterns(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, int aVersion, double aCellSize, boolean ForcePrecision) {#preciseAugmentedPatternsWithTimingPatterns-com.aspose.barcode.common.bitmaps.AlignmentPatternsGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-boolean-}
```
public static void preciseAugmentedPatternsWithTimingPatterns(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, int aVersion, double aCellSize, boolean ForcePrecision)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrid | [AlignmentPatternsGrid](../../com.aspose.barcode.common.bitmaps/alignmentpatternsgrid) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aVersion | int |  |
| aCellSize | double |  |
| ForcePrecision | boolean |  |

### preciseGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision) {#preciseGrid-com.aspose.barcode.common.bitmaps.AlignmentPatternsGrid-com.aspose.barcode.common.bitmaps.ByteBitmap-int-double-int-int-}
```
public static void preciseGrid(AlignmentPatternsGrid aGrid, ByteBitmap aBitmap, int aVersion, double aCellSize, int aTimingForce, int aAugmentedPrecision)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrid | [AlignmentPatternsGrid](../../com.aspose.barcode.common.bitmaps/alignmentpatternsgrid) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aVersion | int |  |
| aCellSize | double |  |
| aTimingForce | int |  |
| aAugmentedPrecision | int |  |

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

