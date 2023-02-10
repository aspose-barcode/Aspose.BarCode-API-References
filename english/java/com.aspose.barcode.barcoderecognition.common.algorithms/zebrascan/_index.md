---
title: ZebraScan
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 51
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/zebrascan/
---
**Inheritance:**
java.lang.Object
```
public class ZebraScan
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraScan()](#ZebraScan--) |  |
## Methods

| Method | Description |
| --- | --- |
| [calculateInt32Zebra(byte[] aZebra)](#calculateInt32Zebra-byte---) |  |
| [calculateZebraBars(byte[] aZebra)](#calculateZebraBars-byte---) |  |
| [copyZebraBarList(List<ZebraScan.ZebraBar> aList)](#copyZebraBarList-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--) |  |
| [createBitmapFromZebraBars(List<ZebraScan.ZebraBar> aBars, byte aDefColor)](#createBitmapFromZebraBars-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--byte-) |  |
| [createBitmapFromZebraBars(List<ZebraScan.ZebraBar> aBars, int ZebraLength, byte aDefColor)](#createBitmapFromZebraBars-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-byte-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDiagonalRow3Pi4(ByteBitmap aBitmap, int aX, int aY, int Borders, byte aDefColor)](#getDiagonalRow3Pi4-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-byte-) |  |
| [getDiagonalRowPi4(ByteBitmap aBitmap, int aX, int aY, int Borders, byte aDefColor)](#getDiagonalRowPi4-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-byte-) |  |
| [getHorisontalRow(ByteBitmap aBitmap, int aY, int Borders, byte aDefColor)](#getHorisontalRow-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-byte-) |  |
| [getHorisontalRow(ByteBitmap aBitmap, int aY, int aStartX, int aEndX, int Borders, byte aDefColor)](#getHorisontalRow-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-byte-) |  |
| [getPointListRow(ByteBitmap aBitmap, List<System.Drawing.Point> aList, byte aDefColor)](#getPointListRow-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--byte-) |  |
| [getVerticalRow(ByteBitmap aBitmap, int aX, int Borders, byte aDefColor)](#getVerticalRow-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-byte-) |  |
| [getVerticalRow(ByteBitmap aBitmap, int aX, int aStartY, int aEndY, int Borders, byte aDefColor)](#getVerticalRow-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-byte-) |  |
| [getZebraFromLine(ByteBitmap aBitmap, int yLine)](#getZebraFromLine-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [hashCode()](#hashCode--) |  |
| [indexOfCurrentLineInList(List<ZebraScan.ZebraPatternLine> aList, ZebraScan.ZebraPatternLine aLine, int MaxDiff)](#indexOfCurrentLineInList-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraPatternLine--com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraPatternLine-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorBarsWithoutEdges(List<ZebraScan.ZebraBar> aList, byte aColor, int aBarSize)](#removeColorBarsWithoutEdges-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--byte-int-) |  |
| [removeSaltAndPaper(List<ZebraScan.ZebraBar> aList, int aSaltPaperSize, boolean isCopy)](#removeSaltAndPaper-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-boolean-) |  |
| [revertZebraBars(List<ZebraScan.ZebraBar> aBars, int ZebraLength)](#revertZebraBars-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-) |  |
| [toString()](#toString--) |  |
| [tryToDetectPattern(List<ZebraScan.ZebraBar> aZebras, int aPos, byte[] aPattern, float WholePatternSize, float Tolerance, float aMinQuality)](#tryToDetectPattern-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-byte---float-float-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraScan() {#ZebraScan--}
```
public ZebraScan()
```


### calculateInt32Zebra(byte[] aZebra) {#calculateInt32Zebra-byte---}
```
public static Int32List calculateInt32Zebra(byte[] aZebra)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebra | byte[] |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
### calculateZebraBars(byte[] aZebra) {#calculateZebraBars-byte---}
```
public static List<ZebraScan.ZebraBar> calculateZebraBars(byte[] aZebra)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebra | byte[] |  |

**Returns:**
[List](../../java.util/list)
### copyZebraBarList(List<ZebraScan.ZebraBar> aList) {#copyZebraBarList-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--}
```
public static List<ZebraScan.ZebraBar> copyZebraBarList(List<ZebraScan.ZebraBar> aList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> |  |

**Returns:**
[List](../../java.util/list)
### createBitmapFromZebraBars(List<ZebraScan.ZebraBar> aBars, byte aDefColor) {#createBitmapFromZebraBars-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--byte-}
```
public static ByteBitmap createBitmapFromZebraBars(List<ZebraScan.ZebraBar> aBars, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBars | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> |  |
| aDefColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### createBitmapFromZebraBars(List<ZebraScan.ZebraBar> aBars, int ZebraLength, byte aDefColor) {#createBitmapFromZebraBars-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-byte-}
```
public static ByteBitmap createBitmapFromZebraBars(List<ZebraScan.ZebraBar> aBars, int ZebraLength, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBars | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> |  |
| ZebraLength | int |  |
| aDefColor | byte |  |

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
### getDiagonalRow3Pi4(ByteBitmap aBitmap, int aX, int aY, int Borders, byte aDefColor) {#getDiagonalRow3Pi4-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-byte-}
```
public static ByteBitmap getDiagonalRow3Pi4(ByteBitmap aBitmap, int aX, int aY, int Borders, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aX | int |  |
| aY | int |  |
| Borders | int |  |
| aDefColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getDiagonalRowPi4(ByteBitmap aBitmap, int aX, int aY, int Borders, byte aDefColor) {#getDiagonalRowPi4-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-byte-}
```
public static ByteBitmap getDiagonalRowPi4(ByteBitmap aBitmap, int aX, int aY, int Borders, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aX | int |  |
| aY | int |  |
| Borders | int |  |
| aDefColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getHorisontalRow(ByteBitmap aBitmap, int aY, int Borders, byte aDefColor) {#getHorisontalRow-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-byte-}
```
public static ByteBitmap getHorisontalRow(ByteBitmap aBitmap, int aY, int Borders, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aY | int |  |
| Borders | int |  |
| aDefColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getHorisontalRow(ByteBitmap aBitmap, int aY, int aStartX, int aEndX, int Borders, byte aDefColor) {#getHorisontalRow-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-byte-}
```
public static ByteBitmap getHorisontalRow(ByteBitmap aBitmap, int aY, int aStartX, int aEndX, int Borders, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aY | int |  |
| aStartX | int |  |
| aEndX | int |  |
| Borders | int |  |
| aDefColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getPointListRow(ByteBitmap aBitmap, List<System.Drawing.Point> aList, byte aDefColor) {#getPointListRow-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.ms.System.Drawing.Point--byte-}
```
public static ByteBitmap getPointListRow(ByteBitmap aBitmap, List<System.Drawing.Point> aList, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aList | java.util.List<com.aspose.ms.System.Drawing.Point> |  |
| aDefColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getVerticalRow(ByteBitmap aBitmap, int aX, int Borders, byte aDefColor) {#getVerticalRow-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-byte-}
```
public static ByteBitmap getVerticalRow(ByteBitmap aBitmap, int aX, int Borders, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aX | int |  |
| Borders | int |  |
| aDefColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getVerticalRow(ByteBitmap aBitmap, int aX, int aStartY, int aEndY, int Borders, byte aDefColor) {#getVerticalRow-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-int-byte-}
```
public static ByteBitmap getVerticalRow(ByteBitmap aBitmap, int aX, int aStartY, int aEndY, int Borders, byte aDefColor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aX | int |  |
| aStartY | int |  |
| aEndY | int |  |
| Borders | int |  |
| aDefColor | byte |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getZebraFromLine(ByteBitmap aBitmap, int yLine) {#getZebraFromLine-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static byte[] getZebraFromLine(ByteBitmap aBitmap, int yLine)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| yLine | int |  |

**Returns:**
byte[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOfCurrentLineInList(List<ZebraScan.ZebraPatternLine> aList, ZebraScan.ZebraPatternLine aLine, int MaxDiff) {#indexOfCurrentLineInList-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraPatternLine--com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraPatternLine-int-}
```
public static int indexOfCurrentLineInList(List<ZebraScan.ZebraPatternLine> aList, ZebraScan.ZebraPatternLine aLine, int MaxDiff)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraPatternLine> |  |
| aLine | [ZebraPatternLine](../../com.aspose.barcode.barcoderecognition.common.algorithms/zebrapatternline) |  |
| MaxDiff | int |  |

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




### removeColorBarsWithoutEdges(List<ZebraScan.ZebraBar> aList, byte aColor, int aBarSize) {#removeColorBarsWithoutEdges-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--byte-int-}
```
public static List<ZebraScan.ZebraBar> removeColorBarsWithoutEdges(List<ZebraScan.ZebraBar> aList, byte aColor, int aBarSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> |  |
| aColor | byte |  |
| aBarSize | int |  |

**Returns:**
[List](../../java.util/list)
### removeSaltAndPaper(List<ZebraScan.ZebraBar> aList, int aSaltPaperSize, boolean isCopy) {#removeSaltAndPaper-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-boolean-}
```
public static List<ZebraScan.ZebraBar> removeSaltAndPaper(List<ZebraScan.ZebraBar> aList, int aSaltPaperSize, boolean isCopy)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> |  |
| aSaltPaperSize | int |  |
| isCopy | boolean |  |

**Returns:**
[List](../../java.util/list)
### revertZebraBars(List<ZebraScan.ZebraBar> aBars, int ZebraLength) {#revertZebraBars-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-}
```
public static List<ZebraScan.ZebraBar> revertZebraBars(List<ZebraScan.ZebraBar> aBars, int ZebraLength)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBars | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> |  |
| ZebraLength | int |  |

**Returns:**
[List](../../java.util/list)
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryToDetectPattern(List<ZebraScan.ZebraBar> aZebras, int aPos, byte[] aPattern, float WholePatternSize, float Tolerance, float aMinQuality) {#tryToDetectPattern-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-byte---float-float-float-}
```
public static ZebraScan.ZebraPatternLine tryToDetectPattern(List<ZebraScan.ZebraBar> aZebras, int aPos, byte[] aPattern, float WholePatternSize, float Tolerance, float aMinQuality)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebras | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> |  |
| aPos | int |  |
| aPattern | byte[] |  |
| WholePatternSize | float |  |
| Tolerance | float |  |
| aMinQuality | float |  |

**Returns:**
[ZebraPatternLine](../../com.aspose.barcode.barcoderecognition.common.algorithms/zebrapatternline)
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

