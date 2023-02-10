---
title: DMHelperFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmhelperfunc/
---
**Inheritance:**
java.lang.Object
```
public class DMHelperFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DMHelperFunc()](#DMHelperFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdaptiveTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap)](#getAdaptiveTresholdByTheBlackChain-java.util.List-com.aspose.barcode.common.types.ShortPoint----com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getAdaptiveTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap, double aDeviantK, int aMaxDeviantVal)](#getAdaptiveTresholdByTheBlackChain-java.util.List-com.aspose.barcode.common.types.ShortPoint----com.aspose.barcode.common.bitmaps.ByteBitmap-double-int-) |  |
| [getAdaptiveTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap)](#getAdaptiveTresholdFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getAdaptiveTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap, double aDeviantK, int aMaxDeviantVal)](#getAdaptiveTresholdFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-double-int-) |  |
| [getAveragePoint(System.Drawing.PointF Pt0, System.Drawing.PointF Pt1)](#getAveragePoint-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) |  |
| [getAveragePoint(System.Drawing.PointF[] Points)](#getAveragePoint-com.aspose.ms.System.Drawing.PointF---) |  |
| [getAverageTresholdFromLPattern(LPatternData aPattern, ByteBitmap aBitmap)](#getAverageTresholdFromLPattern-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getAverageTresholdFromLPattern(LPatternData aPattern, ByteBitmap aBitmap, float aK)](#getAverageTresholdFromLPattern-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-com.aspose.barcode.common.bitmaps.ByteBitmap-float-) |  |
| [getBWValueFromBinarizedBitmap(System.Drawing.Point Pt0, System.Drawing.Point Pt1, ByteBitmap aBitmap)](#getBWValueFromBinarizedBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getBWValueFromPoints(System.Drawing.Point Pt0, System.Drawing.Point Pt1, ByteBitmap aBitmap, byte aDef, byte aThreshold)](#getBWValueFromPoints-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-byte-) |  |
| [getClass()](#getClass--) |  |
| [getLPatternQuad(LPatternData aPattern)](#getLPatternQuad-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-) |  |
| [getMostClosePoint(System.Drawing.Point From, DoublePoints aLine)](#getMostClosePoint-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-) |  |
| [getMostClosePoint(System.Drawing.PointF From, DoublePointFs aLine)](#getMostClosePoint-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-) |  |
| [getMostDistantPoint(System.Drawing.Point From, DoublePoints aLine)](#getMostDistantPoint-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-) |  |
| [getMostDistantPoint(System.Drawing.PointF From, DoublePointFs aLine)](#getMostDistantPoint-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-) |  |
| [getOppositeLPatternPoint(LPatternData aPattern)](#getOppositeLPatternPoint-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-) |  |
| [getPrecisedByLinePointsFormChain(DoublePointFs aLine, List<ShortPoint> aChain)](#getPrecisedByLinePointsFormChain-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-java.util.List-com.aspose.barcode.common.types.ShortPoint--) |  |
| [getPrecisedByLinePointsFormChain(LineCoefs aLine, List<ShortPoint> aChain)](#getPrecisedByLinePointsFormChain-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-java.util.List-com.aspose.barcode.common.types.ShortPoint--) |  |
| [getScanListMaxLines(QuadPoints aQuad, int aMaxScanLines)](#getScanListMaxLines-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-) |  |
| [getTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap)](#getTresholdByTheBlackChain-java.util.List-com.aspose.barcode.common.types.ShortPoint----com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap)](#getTresholdFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [hashCode()](#hashCode--) |  |
| [mergeExtractedLines(ExtractedLineF aMainLine, ExtractedLineF aAddLine, boolean isPrecisePointsByMainLine)](#mergeExtractedLines-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLineF-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLineF-boolean-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DMHelperFunc() {#DMHelperFunc--}
```
public DMHelperFunc()
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
### getAdaptiveTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap) {#getAdaptiveTresholdByTheBlackChain-java.util.List-com.aspose.barcode.common.types.ShortPoint----com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte getAdaptiveTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.common.types.ShortPoint>[] |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte
### getAdaptiveTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap, double aDeviantK, int aMaxDeviantVal) {#getAdaptiveTresholdByTheBlackChain-java.util.List-com.aspose.barcode.common.types.ShortPoint----com.aspose.barcode.common.bitmaps.ByteBitmap-double-int-}
```
public static byte getAdaptiveTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap, double aDeviantK, int aMaxDeviantVal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.common.types.ShortPoint>[] |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aDeviantK | double |  |
| aMaxDeviantVal | int |  |

**Returns:**
byte
### getAdaptiveTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap) {#getAdaptiveTresholdFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte getAdaptiveTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte
### getAdaptiveTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap, double aDeviantK, int aMaxDeviantVal) {#getAdaptiveTresholdFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-double-int-}
```
public static byte getAdaptiveTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap, double aDeviantK, int aMaxDeviantVal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aDeviantK | double |  |
| aMaxDeviantVal | int |  |

**Returns:**
byte
### getAveragePoint(System.Drawing.PointF Pt0, System.Drawing.PointF Pt1) {#getAveragePoint-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static System.Drawing.PointF getAveragePoint(System.Drawing.PointF Pt0, System.Drawing.PointF Pt1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Pt0 | com.aspose.ms.System.Drawing.PointF |  |
| Pt1 | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### getAveragePoint(System.Drawing.PointF[] Points) {#getAveragePoint-com.aspose.ms.System.Drawing.PointF---}
```
public static System.Drawing.PointF getAveragePoint(System.Drawing.PointF[] Points)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Points | com.aspose.ms.System.Drawing.PointF[] |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### getAverageTresholdFromLPattern(LPatternData aPattern, ByteBitmap aBitmap) {#getAverageTresholdFromLPattern-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte getAverageTresholdFromLPattern(LPatternData aPattern, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPattern | [LPatternData](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/lpatterndata) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte
### getAverageTresholdFromLPattern(LPatternData aPattern, ByteBitmap aBitmap, float aK) {#getAverageTresholdFromLPattern-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-com.aspose.barcode.common.bitmaps.ByteBitmap-float-}
```
public static byte getAverageTresholdFromLPattern(LPatternData aPattern, ByteBitmap aBitmap, float aK)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPattern | [LPatternData](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/lpatterndata) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aK | float |  |

**Returns:**
byte
### getBWValueFromBinarizedBitmap(System.Drawing.Point Pt0, System.Drawing.Point Pt1, ByteBitmap aBitmap) {#getBWValueFromBinarizedBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static Tup<Integer,Integer> getBWValueFromBinarizedBitmap(System.Drawing.Point Pt0, System.Drawing.Point Pt1, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Pt0 | com.aspose.ms.System.Drawing.Point |  |
| Pt1 | com.aspose.ms.System.Drawing.Point |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup)
### getBWValueFromPoints(System.Drawing.Point Pt0, System.Drawing.Point Pt1, ByteBitmap aBitmap, byte aDef, byte aThreshold) {#getBWValueFromPoints-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-byte-}
```
public static Tup<Integer,Integer> getBWValueFromPoints(System.Drawing.Point Pt0, System.Drawing.Point Pt1, ByteBitmap aBitmap, byte aDef, byte aThreshold)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Pt0 | com.aspose.ms.System.Drawing.Point |  |
| Pt1 | com.aspose.ms.System.Drawing.Point |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aDef | byte |  |
| aThreshold | byte |  |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLPatternQuad(LPatternData aPattern) {#getLPatternQuad-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-}
```
public static QuadPoints getLPatternQuad(LPatternData aPattern)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPattern | [LPatternData](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/lpatterndata) |  |

**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints)
### getMostClosePoint(System.Drawing.Point From, DoublePoints aLine) {#getMostClosePoint-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-}
```
public static System.Drawing.Point getMostClosePoint(System.Drawing.Point From, DoublePoints aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| From | com.aspose.ms.System.Drawing.Point |  |
| aLine | [DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### getMostClosePoint(System.Drawing.PointF From, DoublePointFs aLine) {#getMostClosePoint-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-}
```
public static System.Drawing.PointF getMostClosePoint(System.Drawing.PointF From, DoublePointFs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| From | com.aspose.ms.System.Drawing.PointF |  |
| aLine | [DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs) |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### getMostDistantPoint(System.Drawing.Point From, DoublePoints aLine) {#getMostDistantPoint-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints-}
```
public static System.Drawing.Point getMostDistantPoint(System.Drawing.Point From, DoublePoints aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| From | com.aspose.ms.System.Drawing.Point |  |
| aLine | [DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints) |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### getMostDistantPoint(System.Drawing.PointF From, DoublePointFs aLine) {#getMostDistantPoint-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-}
```
public static System.Drawing.PointF getMostDistantPoint(System.Drawing.PointF From, DoublePointFs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| From | com.aspose.ms.System.Drawing.PointF |  |
| aLine | [DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs) |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### getOppositeLPatternPoint(LPatternData aPattern) {#getOppositeLPatternPoint-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData-}
```
public static System.Drawing.Point getOppositeLPatternPoint(LPatternData aPattern)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPattern | [LPatternData](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/lpatterndata) |  |

**Returns:**
com.aspose.ms.System.Drawing.Point
### getPrecisedByLinePointsFormChain(DoublePointFs aLine, List<ShortPoint> aChain) {#getPrecisedByLinePointsFormChain-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePointFs-java.util.List-com.aspose.barcode.common.types.ShortPoint--}
```
public static DoublePointFs getPrecisedByLinePointsFormChain(DoublePointFs aLine, List<ShortPoint> aChain)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLine | [DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs) |  |
| aChain | java.util.List<com.aspose.barcode.common.types.ShortPoint> |  |

**Returns:**
[DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs)
### getPrecisedByLinePointsFormChain(LineCoefs aLine, List<ShortPoint> aChain) {#getPrecisedByLinePointsFormChain-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-java.util.List-com.aspose.barcode.common.types.ShortPoint--}
```
public static DoublePointFs getPrecisedByLinePointsFormChain(LineCoefs aLine, List<ShortPoint> aChain)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |
| aChain | java.util.List<com.aspose.barcode.common.types.ShortPoint> |  |

**Returns:**
[DoublePointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepointfs)
### getScanListMaxLines(QuadPoints aQuad, int aMaxScanLines) {#getScanListMaxLines-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-int-}
```
public static List<DoublePoints> getScanListMaxLines(QuadPoints aQuad, int aMaxScanLines)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aQuad | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) |  |
| aMaxScanLines | int |  |

**Returns:**
[List](../../java.util/list)
### getTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap) {#getTresholdByTheBlackChain-java.util.List-com.aspose.barcode.common.types.ShortPoint----com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte getTresholdByTheBlackChain(List<ShortPoint>[] aList, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.common.types.ShortPoint>[] |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte
### getTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap) {#getTresholdFromDMRegion-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.DMRegionExt-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static byte getTresholdFromDMRegion(DMRegionExt aRegion, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegion | [DMRegionExt](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/dmregionext) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
byte
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mergeExtractedLines(ExtractedLineF aMainLine, ExtractedLineF aAddLine, boolean isPrecisePointsByMainLine) {#mergeExtractedLines-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLineF-com.aspose.barcode.barcoderecognition.common.algorithms.ExtractedLineF-boolean-}
```
public static ExtractedLineF mergeExtractedLines(ExtractedLineF aMainLine, ExtractedLineF aAddLine, boolean isPrecisePointsByMainLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aMainLine | [ExtractedLineF](../../com.aspose.barcode.barcoderecognition.common.algorithms/extractedlinef) |  |
| aAddLine | [ExtractedLineF](../../com.aspose.barcode.barcoderecognition.common.algorithms/extractedlinef) |  |
| isPrecisePointsByMainLine | boolean |  |

**Returns:**
[ExtractedLineF](../../com.aspose.barcode.barcoderecognition.common.algorithms/extractedlinef)
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

