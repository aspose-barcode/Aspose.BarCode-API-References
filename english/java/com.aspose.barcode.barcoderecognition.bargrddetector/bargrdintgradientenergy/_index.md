---
title: BarGrdIntGradientEnergy
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.bargrddetector/bargrdintgradientenergy/
---
**Inheritance:**
java.lang.Object
```
public class BarGrdIntGradientEnergy
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BarGrdIntGradientEnergy()](#BarGrdIntGradientEnergy--) |  |
## Methods

| Method | Description |
| --- | --- |
| [blurGradientPower(GradientMetrics gradientMetrics, int halfWindow, ITerminationCheck aTerminationCheck)](#blurGradientPower-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [calculateDirectionWindowDiff(IntegralImage[] aIGradients, int x1, int y1, int x2, int y2, int aWindow, int Right, int Bottom, float DiffMainTmp, float[] MainGrdVals, float MainSumm, float[] ResGrdBase, float[] ResGrdMax, float[][] ResGrdVals)](#calculateDirectionWindowDiff-com.aspose.barcode.barcoderecognition.common.algorithms.IntegralImage---int-int-int-int-int-int-int-float-float---float-float---float---float-----) |  |
| [calculateGrdMaxPower(float[][] aGrdVals, float[] aGrdBase, float[] aGrdMax)](#calculateGrdMaxPower-float-----float---float---) |  |
| [clearUnusedEdges(GradientMetrics gradientMetrics, int aHalfWin)](#clearUnusedEdges-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-int-) |  |
| [clearWeakGradients(GradientEnergy gradientEnergy, ITerminationCheck aTerminationCheck)](#clearWeakGradients-com.aspose.barcode.barcoderecognition.bargrddetector.GradientEnergy-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMultiWindowMaxDiffOptimized(GradientMetrics gradientMetrics, IntegralImage[] aIGradients, int aX, int aY, int halfWindow, float[] ResGrdBase, float[] ResGrdMax, float[][] ResGrdVals)](#getMultiWindowMaxDiffOptimized-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-com.aspose.barcode.barcoderecognition.common.algorithms.IntegralImage---int-int-int-float---float---float-----) |  |
| [getMultidirectionalWindowPower(ByteBitmap aSrcPower, int aWindow)](#getMultidirectionalWindowPower-com.aspose.barcode.common.bitmaps.ByteBitmap-int-) |  |
| [getOrtogonalIndex(int aGrdInd)](#getOrtogonalIndex-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [proceedDirectionPower(float[] aGrdVals, int aGrdInd, float[] aGrdPower)](#proceedDirectionPower-float---int-float---) |  |
| [proceedGradientDifferenceFast(ByteBitmap aBmp, int ClSide, float aThresholdEdge, ITerminationCheck aTerminationCheck)](#proceedGradientDifferenceFast-com.aspose.barcode.common.bitmaps.ByteBitmap-int-float-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarGrdIntGradientEnergy() {#BarGrdIntGradientEnergy--}
```
public BarGrdIntGradientEnergy()
```


### blurGradientPower(GradientMetrics gradientMetrics, int halfWindow, ITerminationCheck aTerminationCheck) {#blurGradientPower-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static GradientEnergy blurGradientPower(GradientMetrics gradientMetrics, int halfWindow, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gradientMetrics | [GradientMetrics](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientmetrics) |  |
| halfWindow | int |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
com.aspose.barcode.barcoderecognition.bargrddetector.GradientEnergy
### calculateDirectionWindowDiff(IntegralImage[] aIGradients, int x1, int y1, int x2, int y2, int aWindow, int Right, int Bottom, float DiffMainTmp, float[] MainGrdVals, float MainSumm, float[] ResGrdBase, float[] ResGrdMax, float[][] ResGrdVals) {#calculateDirectionWindowDiff-com.aspose.barcode.barcoderecognition.common.algorithms.IntegralImage---int-int-int-int-int-int-int-float-float---float-float---float---float-----}
```
public static void calculateDirectionWindowDiff(IntegralImage[] aIGradients, int x1, int y1, int x2, int y2, int aWindow, int Right, int Bottom, float DiffMainTmp, float[] MainGrdVals, float MainSumm, float[] ResGrdBase, float[] ResGrdMax, float[][] ResGrdVals)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aIGradients | [IntegralImage\[\]](../../com.aspose.barcode.barcoderecognition.common.algorithms/integralimage) |  |
| x1 | int |  |
| y1 | int |  |
| x2 | int |  |
| y2 | int |  |
| aWindow | int |  |
| Right | int |  |
| Bottom | int |  |
| DiffMainTmp | float |  |
| MainGrdVals | float[] |  |
| MainSumm | float |  |
| ResGrdBase | float[] |  |
| ResGrdMax | float[] |  |
| ResGrdVals | float[][] |  |

### calculateGrdMaxPower(float[][] aGrdVals, float[] aGrdBase, float[] aGrdMax) {#calculateGrdMaxPower-float-----float---float---}
```
public static void calculateGrdMaxPower(float[][] aGrdVals, float[] aGrdBase, float[] aGrdMax)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrdVals | float[][] |  |
| aGrdBase | float[] |  |
| aGrdMax | float[] |  |

### clearUnusedEdges(GradientMetrics gradientMetrics, int aHalfWin) {#clearUnusedEdges-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-int-}
```
public static GradientMetrics clearUnusedEdges(GradientMetrics gradientMetrics, int aHalfWin)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gradientMetrics | [GradientMetrics](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientmetrics) |  |
| aHalfWin | int |  |

**Returns:**
[GradientMetrics](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientmetrics)
### clearWeakGradients(GradientEnergy gradientEnergy, ITerminationCheck aTerminationCheck) {#clearWeakGradients-com.aspose.barcode.barcoderecognition.bargrddetector.GradientEnergy-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static GradientEnergy clearWeakGradients(GradientEnergy gradientEnergy, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gradientEnergy | com.aspose.barcode.barcoderecognition.bargrddetector.GradientEnergy |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
com.aspose.barcode.barcoderecognition.bargrddetector.GradientEnergy
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
### getMultiWindowMaxDiffOptimized(GradientMetrics gradientMetrics, IntegralImage[] aIGradients, int aX, int aY, int halfWindow, float[] ResGrdBase, float[] ResGrdMax, float[][] ResGrdVals) {#getMultiWindowMaxDiffOptimized-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-com.aspose.barcode.barcoderecognition.common.algorithms.IntegralImage---int-int-int-float---float---float-----}
```
public static void getMultiWindowMaxDiffOptimized(GradientMetrics gradientMetrics, IntegralImage[] aIGradients, int aX, int aY, int halfWindow, float[] ResGrdBase, float[] ResGrdMax, float[][] ResGrdVals)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gradientMetrics | [GradientMetrics](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientmetrics) |  |
| aIGradients | [IntegralImage\[\]](../../com.aspose.barcode.barcoderecognition.common.algorithms/integralimage) |  |
| aX | int |  |
| aY | int |  |
| halfWindow | int |  |
| ResGrdBase | float[] |  |
| ResGrdMax | float[] |  |
| ResGrdVals | float[][] |  |

### getMultidirectionalWindowPower(ByteBitmap aSrcPower, int aWindow) {#getMultidirectionalWindowPower-com.aspose.barcode.common.bitmaps.ByteBitmap-int-}
```
public static ByteBitmap getMultidirectionalWindowPower(ByteBitmap aSrcPower, int aWindow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSrcPower | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aWindow | int |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap)
### getOrtogonalIndex(int aGrdInd) {#getOrtogonalIndex-int-}
```
public static int getOrtogonalIndex(int aGrdInd)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrdInd | int |  |

**Returns:**
int
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




### proceedDirectionPower(float[] aGrdVals, int aGrdInd, float[] aGrdPower) {#proceedDirectionPower-float---int-float---}
```
public static void proceedDirectionPower(float[] aGrdVals, int aGrdInd, float[] aGrdPower)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrdVals | float[] |  |
| aGrdInd | int |  |
| aGrdPower | float[] |  |

### proceedGradientDifferenceFast(ByteBitmap aBmp, int ClSide, float aThresholdEdge, ITerminationCheck aTerminationCheck) {#proceedGradientDifferenceFast-com.aspose.barcode.common.bitmaps.ByteBitmap-int-float-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static GradientMetrics proceedGradientDifferenceFast(ByteBitmap aBmp, int ClSide, float aThresholdEdge, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBmp | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| ClSide | int |  |
| aThresholdEdge | float |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[GradientMetrics](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientmetrics)
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

