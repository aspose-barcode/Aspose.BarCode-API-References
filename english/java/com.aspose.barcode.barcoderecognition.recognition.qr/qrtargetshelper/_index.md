---
title: QRTargetsHelper
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.qr/qrtargetshelper/
---
**Inheritance:**
java.lang.Object
```
public class QRTargetsHelper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [QRTargetsHelper()](#QRTargetsHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [averageCellCount(TargetUnion aFirst, TargetUnion aSecond)](#averageCellCount-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-) |  |
| [averageQrImageCellParams(TargetUnion LinkTarget, TargetUnion RightTarget, TargetUnion BottomTarget)](#averageQrImageCellParams-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAPCrossLineSize(System.Drawing.PointF CentralPoint, LineCoefs Line, float aRad, List<System.Drawing.Point> aShapePoints)](#getAPCrossLineSize-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-float-java.util.List-com.aspose.ms.System.Drawing.Point--) |  |
| [getAlignmentPatterns(System.Drawing.Point ShiftPoint, ByteBitmap aBitmap, float WidthCellSize, float HeightCellSize)](#getAlignmentPatterns-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-float-float-) |  |
| [getAugmentedPoint(LineCoefs aLine, double aRad, System.Drawing.PointF CentralPoint, System.Drawing.PointF TestingPoint, boolean isCloserToTesting)](#getAugmentedPoint-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-) |  |
| [getAverageCellsSizeOfQrImageUnion(QrImageUnion aUnion)](#getAverageCellsSizeOfQrImageUnion-com.aspose.barcode.barcoderecognition.recognition.qr.QrImageUnion-) |  |
| [getClass()](#getClass--) |  |
| [getDirectingLines(TargetUnion aUnion, LineCoefs aLine)](#getDirectingLines-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-) |  |
| [getDirectingLines(TargetUnion aUnion, System.Drawing.PointF aFirst, System.Drawing.PointF aSecond)](#getDirectingLines-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) |  |
| [getExtractingQuadByTheWholeBarcode(System.Drawing.PointF CornerPoint, System.Drawing.PointF OppositeFirst, System.Drawing.PointF OppositeSecond, System.Drawing.PointF OppositeDiagonal, float BarcodeCells, float CellForSquare)](#getExtractingQuadByTheWholeBarcode-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-float-float-) |  |
| [getExtractionQuad(TargetUnion aUnion, System.Drawing.PointF CornerPoint, System.Drawing.PointF OppositeFirst, System.Drawing.PointF OppositeSecond, System.Drawing.PointF OppositeDiagonal, float CellFirst, float CellSecond)](#getExtractionQuad-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-float-float-) |  |
| [getLinksWithQrLines(TargetUnion aUnion, LineCoefs LinkMain, LineCoefs LinkOrtogonal, boolean IsQrRight)](#getLinksWithQrLines-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-boolean-) |  |
| [getPointPlacesFromMarksBitmap(SByteBitmap aBitmap)](#getPointPlacesFromMarksBitmap-com.aspose.barcode.common.bitmaps.SByteBitmap-) |  |
| [getTargetAverageCellSize(TargetUnion aUnion)](#getTargetAverageCellSize-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-) |  |
| [getTimingPatterns(System.Drawing.PointF aFirst, System.Drawing.PointF aSecond, double aOrtCellSize, ByteBitmap aBitmap)](#getTimingPatterns-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getZebrasFromPoints(System.Drawing.Point aFirst, System.Drawing.Point aSecond, ByteBitmap aBitmap)](#getZebrasFromPoints-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [hashCode()](#hashCode--) |  |
| [isMicroQrImageUnionBilinearExtraction(MicroQRImageUnion aUnion)](#isMicroQrImageUnionBilinearExtraction-com.aspose.barcode.barcoderecognition.recognition.qr.MicroQRImageUnion-) |  |
| [isQrImageFullyRight(QrImageUnion aUnion)](#isQrImageFullyRight-com.aspose.barcode.barcoderecognition.recognition.qr.QrImageUnion-) |  |
| [isQrImageUnionBilinearExtraction(QrImageUnion aUnion)](#isQrImageUnionBilinearExtraction-com.aspose.barcode.barcoderecognition.recognition.qr.QrImageUnion-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [preciseCellSize(float CellCount, System.Drawing.PointF aFirst, System.Drawing.PointF aSecond)](#preciseCellSize-float-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) |  |
| [shiftPoints(QuadPointFs aPoints, int ShiftCnt, boolean isClockWise)](#shiftPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-int-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QRTargetsHelper() {#QRTargetsHelper--}
```
public QRTargetsHelper()
```


### averageCellCount(TargetUnion aFirst, TargetUnion aSecond) {#averageCellCount-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-}
```
public static QRTargetsHelper.CellCountWithCellSize averageCellCount(TargetUnion aFirst, TargetUnion aSecond)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirst | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |
| aSecond | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |

**Returns:**
com.aspose.barcode.barcoderecognition.recognition.qr.QRTargetsHelper.CellCountWithCellSize
### averageQrImageCellParams(TargetUnion LinkTarget, TargetUnion RightTarget, TargetUnion BottomTarget) {#averageQrImageCellParams-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-}
```
public static QRTargetsHelper.CellCountWithRBCellSize averageQrImageCellParams(TargetUnion LinkTarget, TargetUnion RightTarget, TargetUnion BottomTarget)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| LinkTarget | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |
| RightTarget | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |
| BottomTarget | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |

**Returns:**
com.aspose.barcode.barcoderecognition.recognition.qr.QRTargetsHelper.CellCountWithRBCellSize
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
### getAPCrossLineSize(System.Drawing.PointF CentralPoint, LineCoefs Line, float aRad, List<System.Drawing.Point> aShapePoints) {#getAPCrossLineSize-com.aspose.ms.System.Drawing.PointF-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-float-java.util.List-com.aspose.ms.System.Drawing.Point--}
```
public static DoublePoints getAPCrossLineSize(System.Drawing.PointF CentralPoint, LineCoefs Line, float aRad, List<System.Drawing.Point> aShapePoints)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| CentralPoint | com.aspose.ms.System.Drawing.PointF |  |
| Line | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |
| aRad | float |  |
| aShapePoints | java.util.List<com.aspose.ms.System.Drawing.Point> |  |

**Returns:**
[DoublePoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/doublepoints)
### getAlignmentPatterns(System.Drawing.Point ShiftPoint, ByteBitmap aBitmap, float WidthCellSize, float HeightCellSize) {#getAlignmentPatterns-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-float-float-}
```
public static List<QRTargetsHelper.AlignmentPattern> getAlignmentPatterns(System.Drawing.Point ShiftPoint, ByteBitmap aBitmap, float WidthCellSize, float HeightCellSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ShiftPoint | com.aspose.ms.System.Drawing.Point |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| WidthCellSize | float |  |
| HeightCellSize | float |  |

**Returns:**
[List](../../java.util/list)
### getAugmentedPoint(LineCoefs aLine, double aRad, System.Drawing.PointF CentralPoint, System.Drawing.PointF TestingPoint, boolean isCloserToTesting) {#getAugmentedPoint-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-double-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-boolean-}
```
public static System.Drawing.PointF getAugmentedPoint(LineCoefs aLine, double aRad, System.Drawing.PointF CentralPoint, System.Drawing.PointF TestingPoint, boolean isCloserToTesting)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |
| aRad | double |  |
| CentralPoint | com.aspose.ms.System.Drawing.PointF |  |
| TestingPoint | com.aspose.ms.System.Drawing.PointF |  |
| isCloserToTesting | boolean |  |

**Returns:**
com.aspose.ms.System.Drawing.PointF
### getAverageCellsSizeOfQrImageUnion(QrImageUnion aUnion) {#getAverageCellsSizeOfQrImageUnion-com.aspose.barcode.barcoderecognition.recognition.qr.QrImageUnion-}
```
public static double getAverageCellsSizeOfQrImageUnion(QrImageUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [QrImageUnion](../../com.aspose.barcode.barcoderecognition.recognition.qr/qrimageunion) |  |

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirectingLines(TargetUnion aUnion, LineCoefs aLine) {#getDirectingLines-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-}
```
public static QRTargetsHelper.DirectingLines getDirectingLines(TargetUnion aUnion, LineCoefs aLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |
| aLine | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |

**Returns:**
[DirectingLines](../../com.aspose.barcode.barcoderecognition.recognition.qr/directinglines)
### getDirectingLines(TargetUnion aUnion, System.Drawing.PointF aFirst, System.Drawing.PointF aSecond) {#getDirectingLines-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static QRTargetsHelper.DirectingLines getDirectingLines(TargetUnion aUnion, System.Drawing.PointF aFirst, System.Drawing.PointF aSecond)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |
| aFirst | com.aspose.ms.System.Drawing.PointF |  |
| aSecond | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
[DirectingLines](../../com.aspose.barcode.barcoderecognition.recognition.qr/directinglines)
### getExtractingQuadByTheWholeBarcode(System.Drawing.PointF CornerPoint, System.Drawing.PointF OppositeFirst, System.Drawing.PointF OppositeSecond, System.Drawing.PointF OppositeDiagonal, float BarcodeCells, float CellForSquare) {#getExtractingQuadByTheWholeBarcode-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-float-float-}
```
public static QuadPointFs getExtractingQuadByTheWholeBarcode(System.Drawing.PointF CornerPoint, System.Drawing.PointF OppositeFirst, System.Drawing.PointF OppositeSecond, System.Drawing.PointF OppositeDiagonal, float BarcodeCells, float CellForSquare)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| CornerPoint | com.aspose.ms.System.Drawing.PointF |  |
| OppositeFirst | com.aspose.ms.System.Drawing.PointF |  |
| OppositeSecond | com.aspose.ms.System.Drawing.PointF |  |
| OppositeDiagonal | com.aspose.ms.System.Drawing.PointF |  |
| BarcodeCells | float |  |
| CellForSquare | float |  |

**Returns:**
[QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs)
### getExtractionQuad(TargetUnion aUnion, System.Drawing.PointF CornerPoint, System.Drawing.PointF OppositeFirst, System.Drawing.PointF OppositeSecond, System.Drawing.PointF OppositeDiagonal, float CellFirst, float CellSecond) {#getExtractionQuad-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-float-float-}
```
public static QuadPointFs getExtractionQuad(TargetUnion aUnion, System.Drawing.PointF CornerPoint, System.Drawing.PointF OppositeFirst, System.Drawing.PointF OppositeSecond, System.Drawing.PointF OppositeDiagonal, float CellFirst, float CellSecond)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |
| CornerPoint | com.aspose.ms.System.Drawing.PointF |  |
| OppositeFirst | com.aspose.ms.System.Drawing.PointF |  |
| OppositeSecond | com.aspose.ms.System.Drawing.PointF |  |
| OppositeDiagonal | com.aspose.ms.System.Drawing.PointF |  |
| CellFirst | float |  |
| CellSecond | float |  |

**Returns:**
[QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs)
### getLinksWithQrLines(TargetUnion aUnion, LineCoefs LinkMain, LineCoefs LinkOrtogonal, boolean IsQrRight) {#getLinksWithQrLines-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-com.aspose.barcode.barcoderecognition.common.algorithms.LineCoefs-boolean-}
```
public static QRTargetsHelper.LinksWithQrLines getLinksWithQrLines(TargetUnion aUnion, LineCoefs LinkMain, LineCoefs LinkOrtogonal, boolean IsQrRight)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |
| LinkMain | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |
| LinkOrtogonal | [LineCoefs](../../com.aspose.barcode.barcoderecognition.common.algorithms/linecoefs) |  |
| IsQrRight | boolean |  |

**Returns:**
com.aspose.barcode.barcoderecognition.recognition.qr.QRTargetsHelper.LinksWithQrLines
### getPointPlacesFromMarksBitmap(SByteBitmap aBitmap) {#getPointPlacesFromMarksBitmap-com.aspose.barcode.common.bitmaps.SByteBitmap-}
```
public static List<QRTargetsHelper.PointsPlace> getPointPlacesFromMarksBitmap(SByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [SByteBitmap](../../com.aspose.barcode.common.bitmaps/sbytebitmap) |  |

**Returns:**
[List](../../java.util/list)
### getTargetAverageCellSize(TargetUnion aUnion) {#getTargetAverageCellSize-com.aspose.barcode.barcoderecognition.recognition.targets.TargetUnion-}
```
public static double getTargetAverageCellSize(TargetUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [TargetUnion](../../com.aspose.barcode.barcoderecognition.recognition.targets/targetunion) |  |

**Returns:**
double
### getTimingPatterns(System.Drawing.PointF aFirst, System.Drawing.PointF aSecond, double aOrtCellSize, ByteBitmap aBitmap) {#getTimingPatterns-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-double-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static List<List<ZebraScan.ZebraBar>> getTimingPatterns(System.Drawing.PointF aFirst, System.Drawing.PointF aSecond, double aOrtCellSize, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirst | com.aspose.ms.System.Drawing.PointF |  |
| aSecond | com.aspose.ms.System.Drawing.PointF |  |
| aOrtCellSize | double |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[List](../../java.util/list)
### getZebrasFromPoints(System.Drawing.Point aFirst, System.Drawing.Point aSecond, ByteBitmap aBitmap) {#getZebrasFromPoints-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static List<List<ZebraScan.ZebraBar>> getZebrasFromPoints(System.Drawing.Point aFirst, System.Drawing.Point aSecond, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aFirst | com.aspose.ms.System.Drawing.Point |  |
| aSecond | com.aspose.ms.System.Drawing.Point |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[List](../../java.util/list)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isMicroQrImageUnionBilinearExtraction(MicroQRImageUnion aUnion) {#isMicroQrImageUnionBilinearExtraction-com.aspose.barcode.barcoderecognition.recognition.qr.MicroQRImageUnion-}
```
public static boolean isMicroQrImageUnionBilinearExtraction(MicroQRImageUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | com.aspose.barcode.barcoderecognition.recognition.qr.MicroQRImageUnion |  |

**Returns:**
boolean
### isQrImageFullyRight(QrImageUnion aUnion) {#isQrImageFullyRight-com.aspose.barcode.barcoderecognition.recognition.qr.QrImageUnion-}
```
public static boolean isQrImageFullyRight(QrImageUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [QrImageUnion](../../com.aspose.barcode.barcoderecognition.recognition.qr/qrimageunion) |  |

**Returns:**
boolean
### isQrImageUnionBilinearExtraction(QrImageUnion aUnion) {#isQrImageUnionBilinearExtraction-com.aspose.barcode.barcoderecognition.recognition.qr.QrImageUnion-}
```
public static boolean isQrImageUnionBilinearExtraction(QrImageUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [QrImageUnion](../../com.aspose.barcode.barcoderecognition.recognition.qr/qrimageunion) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### preciseCellSize(float CellCount, System.Drawing.PointF aFirst, System.Drawing.PointF aSecond) {#preciseCellSize-float-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public static QRTargetsHelper.CellCountWithCellSize preciseCellSize(float CellCount, System.Drawing.PointF aFirst, System.Drawing.PointF aSecond)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| CellCount | float |  |
| aFirst | com.aspose.ms.System.Drawing.PointF |  |
| aSecond | com.aspose.ms.System.Drawing.PointF |  |

**Returns:**
com.aspose.barcode.barcoderecognition.recognition.qr.QRTargetsHelper.CellCountWithCellSize
### shiftPoints(QuadPointFs aPoints, int ShiftCnt, boolean isClockWise) {#shiftPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-int-boolean-}
```
public static QuadPointFs shiftPoints(QuadPointFs aPoints, int ShiftCnt, boolean isClockWise)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoints | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) |  |
| ShiftCnt | int |  |
| isClockWise | boolean |  |

**Returns:**
[QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs)
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

