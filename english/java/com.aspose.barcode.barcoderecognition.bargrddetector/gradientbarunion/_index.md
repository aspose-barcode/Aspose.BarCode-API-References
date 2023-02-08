---
title: GradientBarUnion
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.bargrddetector/gradientbarunion/
---
**Inheritance:**
java.lang.Object
```
public class GradientBarUnion
```
## Constructors

| Constructor | Description |
| --- | --- |
| [GradientBarUnion(int minUnionArea)](#GradientBarUnion-int-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Doubtful](#Doubtful) |  |
| [Features](#Features) |  |
| [GrdAvg](#GrdAvg) |  |
| [GrdBaseDirSumm](#GrdBaseDirSumm) |  |
| [GrdMainDirAvg](#GrdMainDirAvg) |  |
| [GrdMainDirIdx](#GrdMainDirIdx) |  |
| [GrdMainDirSum](#GrdMainDirSum) |  |
| [GrdSumm](#GrdSumm) |  |
| [ImageReducing](#ImageReducing) |  |
| [Marked](#Marked) |  |
| [Points](#Points) |  |
| [Rect](#Rect) |  |
| [SizeMultiplier](#SizeMultiplier) |  |
## Methods

| Method | Description |
| --- | --- |
| [addPoint(GradientEnergy gradientEnergy, int x, int y)](#addPoint-com.aspose.barcode.barcoderecognition.bargrddetector.GradientEnergy-int-int-) |  |
| [calculateUnionFutures(ByteBitmap DecreasedBitmap)](#calculateUnionFutures-com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [canSplit()](#canSplit--) |  |
| [checkUnionIfItIsCorrect(ByteBitmap DecreasedBitmap, int aMaxWidth, int aMaxHeight)](#checkUnionIfItIsCorrect-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientBarUnion(int minUnionArea) {#GradientBarUnion-int-}
```
public GradientBarUnion(int minUnionArea)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| minUnionArea | int |  |

### Doubtful {#Doubtful}
```
public boolean Doubtful
```


### Features {#Features}
```
public GradientUnionGeometricalFeatures Features
```


### GrdAvg {#GrdAvg}
```
public float[] GrdAvg
```


### GrdBaseDirSumm {#GrdBaseDirSumm}
```
public float GrdBaseDirSumm
```


### GrdMainDirAvg {#GrdMainDirAvg}
```
public float GrdMainDirAvg
```


### GrdMainDirIdx {#GrdMainDirIdx}
```
public int GrdMainDirIdx
```


### GrdMainDirSum {#GrdMainDirSum}
```
public float GrdMainDirSum
```


### GrdSumm {#GrdSumm}
```
public float[] GrdSumm
```


### ImageReducing {#ImageReducing}
```
public int ImageReducing
```


### Marked {#Marked}
```
public boolean Marked
```


### Points {#Points}
```
public System.Collections.Generic.List<System.Drawing.Point> Points
```


### Rect {#Rect}
```
public System.Drawing.Rectangle Rect
```


### SizeMultiplier {#SizeMultiplier}
```
public int SizeMultiplier
```


### addPoint(GradientEnergy gradientEnergy, int x, int y) {#addPoint-com.aspose.barcode.barcoderecognition.bargrddetector.GradientEnergy-int-int-}
```
public void addPoint(GradientEnergy gradientEnergy, int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gradientEnergy | com.aspose.barcode.barcoderecognition.bargrddetector.GradientEnergy |  |
| x | int |  |
| y | int |  |

### calculateUnionFutures(ByteBitmap DecreasedBitmap) {#calculateUnionFutures-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public void calculateUnionFutures(ByteBitmap DecreasedBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| DecreasedBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

### canSplit() {#canSplit--}
```
public boolean canSplit()
```




**Returns:**
boolean
### checkUnionIfItIsCorrect(ByteBitmap DecreasedBitmap, int aMaxWidth, int aMaxHeight) {#checkUnionIfItIsCorrect-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-}
```
public boolean checkUnionIfItIsCorrect(ByteBitmap DecreasedBitmap, int aMaxWidth, int aMaxHeight)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| DecreasedBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aMaxWidth | int |  |
| aMaxHeight | int |  |

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

