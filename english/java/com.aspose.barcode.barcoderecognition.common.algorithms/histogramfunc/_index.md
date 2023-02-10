---
title: HistogramFunc
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 25
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/histogramfunc/
---
**Inheritance:**
java.lang.Object
```
public class HistogramFunc
```
## Constructors

| Constructor | Description |
| --- | --- |
| [HistogramFunc()](#HistogramFunc--) |  |
## Methods

| Method | Description |
| --- | --- |
| [binarizeHistogrammWithThreshold(int[] hist, int Threshold, int MaxValue)](#binarizeHistogrammWithThreshold-int---int-int-) |  |
| [binarizePowerHistogrammOtsu(int[] hist)](#binarizePowerHistogrammOtsu-int---) |  |
| [binarizePowerHistogrammOtsu(int[] hist, int MaxLevels, int MaxValue)](#binarizePowerHistogrammOtsu-int---int-int-) |  |
| [blurHistogrammAverage(int[] hist, int aWindow)](#blurHistogrammAverage-int---int-) |  |
| [boundaryPointType(HistogramItem boundaryItem, ExtremumItem extremum)](#boundaryPointType-com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem-com.aspose.barcode.barcoderecognition.common.algorithms.ExtremumItem-) | A type of boundary point |
| [buildHistogramItems(int[] histogram, HistogramItem[][] histogramExt, System.Collections.Generic.List<ExtremumItem>[] extremums)](#buildHistogramItems-int---com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem-----com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.barcoderecognition.common.algorithms.ExtremumItem----) | Builds histogram items and Extremums. |
| [calculateHistogramStatistic(HistogramItem[] histogram)](#calculateHistogramStatistic-com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem---) | Calculate histogram statistics |
| [calculateHistogrammBars(int[] hist, int MaxValue)](#calculateHistogrammBars-int---int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColumnDifferenceHistogramm(ByteBitmap aBmp)](#getColumnDifferenceHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getColumnsHistogram(ByteBitmap aBmp)](#getColumnsHistogram-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getEnergyOfPartHistogrammRadiant(int[] aHist, int aLevels, double aPart)](#getEnergyOfPartHistogrammRadiant-int---int-double-) |  |
| [getHistogramFromByteBitmap(ByteBitmap aBmp)](#getHistogramFromByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getHistogramThresholdOtsu(int[] histogramData)](#getHistogramThresholdOtsu-int---) |  |
| [getRowDifferenceHistogramm(ByteBitmap aBmp)](#getRowDifferenceHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getRowsHistogram(ByteBitmap aBmp)](#getRowsHistogram-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [hashCode()](#hashCode--) |  |
| [invertHistogramm(int[] hist)](#invertHistogramm-int---) |  |
| [makeBlackColumnsHistogram(ByteBitmap bitmap)](#makeBlackColumnsHistogram-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Make black columns histogram (histogram by 255 - color) |
| [makeIntensityHistogramm(int[] hist, int MaxLevels)](#makeIntensityHistogramm-int---int-) |  |
| [normalizeHistogrammWithMaxValue(int[] hist, int MaxLevels)](#normalizeHistogrammWithMaxValue-int---int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HistogramFunc() {#HistogramFunc--}
```
public HistogramFunc()
```


### binarizeHistogrammWithThreshold(int[] hist, int Threshold, int MaxValue) {#binarizeHistogrammWithThreshold-int---int-int-}
```
public static int[] binarizeHistogrammWithThreshold(int[] hist, int Threshold, int MaxValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hist | int[] |  |
| Threshold | int |  |
| MaxValue | int |  |

**Returns:**
int[]
### binarizePowerHistogrammOtsu(int[] hist) {#binarizePowerHistogrammOtsu-int---}
```
public static int[] binarizePowerHistogrammOtsu(int[] hist)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hist | int[] |  |

**Returns:**
int[]
### binarizePowerHistogrammOtsu(int[] hist, int MaxLevels, int MaxValue) {#binarizePowerHistogrammOtsu-int---int-int-}
```
public static int[] binarizePowerHistogrammOtsu(int[] hist, int MaxLevels, int MaxValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hist | int[] |  |
| MaxLevels | int |  |
| MaxValue | int |  |

**Returns:**
int[]
### blurHistogrammAverage(int[] hist, int aWindow) {#blurHistogrammAverage-int---int-}
```
public static int[] blurHistogrammAverage(int[] hist, int aWindow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hist | int[] |  |
| aWindow | int |  |

**Returns:**
int[]
### boundaryPointType(HistogramItem boundaryItem, ExtremumItem extremum) {#boundaryPointType-com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem-com.aspose.barcode.barcoderecognition.common.algorithms.ExtremumItem-}
```
public static int boundaryPointType(HistogramItem boundaryItem, ExtremumItem extremum)
```


A type of boundary point

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| boundaryItem | [HistogramItem](../../com.aspose.barcode.barcoderecognition.common.algorithms/histogramitem) | Boundary item (column) |
| extremum | [ExtremumItem](../../com.aspose.barcode.barcoderecognition.common.algorithms/extremumitem) | An extremum |

**Returns:**
int - A type of boundary item
### buildHistogramItems(int[] histogram, HistogramItem[][] histogramExt, System.Collections.Generic.List<ExtremumItem>[] extremums) {#buildHistogramItems-int---com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem-----com.aspose.ms.System.Collections.Generic.List-com.aspose.barcode.barcoderecognition.common.algorithms.ExtremumItem----}
```
public static void buildHistogramItems(int[] histogram, HistogramItem[][] histogramExt, System.Collections.Generic.List<ExtremumItem>[] extremums)
```


Builds histogram items and Extremums. This items contain an extended information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| histogram | int[] | simple histogram. It is counted black pioints |
| histogramExt | [HistogramItem\[\]](../../com.aspose.barcode.barcoderecognition.common.algorithms/histogramitem) | extended histogram |
| extremums | com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.common.algorithms.ExtremumItem>[] | Extremums |

### calculateHistogramStatistic(HistogramItem[] histogram) {#calculateHistogramStatistic-com.aspose.barcode.barcoderecognition.common.algorithms.HistogramItem---}
```
public static HistogramStatistic calculateHistogramStatistic(HistogramItem[] histogram)
```


Calculate histogram statistics

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| histogram | [HistogramItem\[\]](../../com.aspose.barcode.barcoderecognition.common.algorithms/histogramitem) | A histogram |

**Returns:**
[HistogramStatistic](../../com.aspose.barcode.barcoderecognition.common.algorithms/histogramstatistic) - Statistics
### calculateHistogrammBars(int[] hist, int MaxValue) {#calculateHistogrammBars-int---int-}
```
public static System.Collections.Generic.List<HistogramFunc.HistWithLength> calculateHistogrammBars(int[] hist, int MaxValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hist | int[] |  |
| MaxValue | int |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
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
### getColumnDifferenceHistogramm(ByteBitmap aBmp) {#getColumnDifferenceHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int[] getColumnDifferenceHistogramm(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
int[]
### getColumnsHistogram(ByteBitmap aBmp) {#getColumnsHistogram-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int[] getColumnsHistogram(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
int[]
### getEnergyOfPartHistogrammRadiant(int[] aHist, int aLevels, double aPart) {#getEnergyOfPartHistogrammRadiant-int---int-double-}
```
public static int getEnergyOfPartHistogrammRadiant(int[] aHist, int aLevels, double aPart)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aHist | int[] |  |
| aLevels | int |  |
| aPart | double |  |

**Returns:**
int
### getHistogramFromByteBitmap(ByteBitmap aBmp) {#getHistogramFromByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int[] getHistogramFromByteBitmap(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
int[]
### getHistogramThresholdOtsu(int[] histogramData) {#getHistogramThresholdOtsu-int---}
```
public static int getHistogramThresholdOtsu(int[] histogramData)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| histogramData | int[] |  |

**Returns:**
int
### getRowDifferenceHistogramm(ByteBitmap aBmp) {#getRowDifferenceHistogramm-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int[] getRowDifferenceHistogramm(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
int[]
### getRowsHistogram(ByteBitmap aBmp) {#getRowsHistogram-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int[] getRowsHistogram(ByteBitmap aBmp)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
int[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### invertHistogramm(int[] hist) {#invertHistogramm-int---}
```
public static int[] invertHistogramm(int[] hist)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hist | int[] |  |

**Returns:**
int[]
### makeBlackColumnsHistogram(ByteBitmap bitmap) {#makeBlackColumnsHistogram-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static int[] makeBlackColumnsHistogram(ByteBitmap bitmap)
```


Make black columns histogram (histogram by 255 - color)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |

**Returns:**
int[] - A histogram
### makeIntensityHistogramm(int[] hist, int MaxLevels) {#makeIntensityHistogramm-int---int-}
```
public static int[] makeIntensityHistogramm(int[] hist, int MaxLevels)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hist | int[] |  |
| MaxLevels | int |  |

**Returns:**
int[]
### normalizeHistogrammWithMaxValue(int[] hist, int MaxLevels) {#normalizeHistogrammWithMaxValue-int---int-}
```
public static int[] normalizeHistogrammWithMaxValue(int[] hist, int MaxLevels)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hist | int[] |  |
| MaxLevels | int |  |

**Returns:**
int[]
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

