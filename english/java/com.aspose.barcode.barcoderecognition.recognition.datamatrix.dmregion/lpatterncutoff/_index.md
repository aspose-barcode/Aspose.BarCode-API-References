---
title: LPatternCutOff
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion/lpatterncutoff/
---
**Inheritance:**
java.lang.Object
```
public class LPatternCutOff
```
## Constructors

| Constructor | Description |
| --- | --- |
| [LPatternCutOff()](#LPatternCutOff--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filterLPatternsByBWFillingAndZebra(List<LPatternData> aList, ByteBitmap aBitmap, double aPreciseAngle, int aMaxLinesToCheck, double aMinBlack, double aMaxBlack, double aMinAvgZebra, LPatternCutOff.TresholdType aTType, ITerminationCheck aTerminationCheck)](#filterLPatternsByBWFillingAndZebra-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--com.aspose.barcode.common.bitmaps.ByteBitmap-double-int-double-double-double-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternCutOff.TresholdType-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [filterLPatternsByGradientAngleDiff(List<LPatternData> aList, ByteBitmap aBitmap, double aPreciseAngle, int aMaxLinesToCheck, double aMaxAvgAngleDiff, ITerminationCheck aTerminationCheck)](#filterLPatternsByGradientAngleDiff-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--com.aspose.barcode.common.bitmaps.ByteBitmap-double-int-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [filterLPatternsByMinMaxSquare(List<LPatternData> aList, int aMinSize, int aMaxSize)](#filterLPatternsByMinMaxSquare-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--int-int-) |  |
| [filterLPatternsByQuietZone(List<LPatternData> aList, ByteBitmap aBitmap, double QuietDistance, double aMinWhiteFilling, ITerminationCheck aTerminationCheck)](#filterLPatternsByQuietZone-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--com.aspose.barcode.common.bitmaps.ByteBitmap-double-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [unifiedCutOff(List<LPatternData> aList, ByteBitmap aBitmap, ITerminationCheck aTerminationCheck)](#unifiedCutOff-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LPatternCutOff() {#LPatternCutOff--}
```
public LPatternCutOff()
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
### filterLPatternsByBWFillingAndZebra(List<LPatternData> aList, ByteBitmap aBitmap, double aPreciseAngle, int aMaxLinesToCheck, double aMinBlack, double aMaxBlack, double aMinAvgZebra, LPatternCutOff.TresholdType aTType, ITerminationCheck aTerminationCheck) {#filterLPatternsByBWFillingAndZebra-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--com.aspose.barcode.common.bitmaps.ByteBitmap-double-int-double-double-double-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternCutOff.TresholdType-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<LPatternData> filterLPatternsByBWFillingAndZebra(List<LPatternData> aList, ByteBitmap aBitmap, double aPreciseAngle, int aMaxLinesToCheck, double aMinBlack, double aMaxBlack, double aMinAvgZebra, LPatternCutOff.TresholdType aTType, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData> |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aPreciseAngle | double |  |
| aMaxLinesToCheck | int |  |
| aMinBlack | double |  |
| aMaxBlack | double |  |
| aMinAvgZebra | double |  |
| aTType | com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternCutOff.TresholdType |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
### filterLPatternsByGradientAngleDiff(List<LPatternData> aList, ByteBitmap aBitmap, double aPreciseAngle, int aMaxLinesToCheck, double aMaxAvgAngleDiff, ITerminationCheck aTerminationCheck) {#filterLPatternsByGradientAngleDiff-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--com.aspose.barcode.common.bitmaps.ByteBitmap-double-int-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<LPatternData> filterLPatternsByGradientAngleDiff(List<LPatternData> aList, ByteBitmap aBitmap, double aPreciseAngle, int aMaxLinesToCheck, double aMaxAvgAngleDiff, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData> |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aPreciseAngle | double |  |
| aMaxLinesToCheck | int |  |
| aMaxAvgAngleDiff | double |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
### filterLPatternsByMinMaxSquare(List<LPatternData> aList, int aMinSize, int aMaxSize) {#filterLPatternsByMinMaxSquare-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--int-int-}
```
public static List<LPatternData> filterLPatternsByMinMaxSquare(List<LPatternData> aList, int aMinSize, int aMaxSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData> |  |
| aMinSize | int |  |
| aMaxSize | int |  |

**Returns:**
[List](../../java.util/list)
### filterLPatternsByQuietZone(List<LPatternData> aList, ByteBitmap aBitmap, double QuietDistance, double aMinWhiteFilling, ITerminationCheck aTerminationCheck) {#filterLPatternsByQuietZone-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--com.aspose.barcode.common.bitmaps.ByteBitmap-double-double-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<LPatternData> filterLPatternsByQuietZone(List<LPatternData> aList, ByteBitmap aBitmap, double QuietDistance, double aMinWhiteFilling, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData> |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| QuietDistance | double |  |
| aMinWhiteFilling | double |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
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
### unifiedCutOff(List<LPatternData> aList, ByteBitmap aBitmap, ITerminationCheck aTerminationCheck) {#unifiedCutOff-java.util.List-com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData--com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<LPatternData> unifiedCutOff(List<LPatternData> aList, ByteBitmap aBitmap, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.recognition.datamatrix.dmregion.LPatternData> |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
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

