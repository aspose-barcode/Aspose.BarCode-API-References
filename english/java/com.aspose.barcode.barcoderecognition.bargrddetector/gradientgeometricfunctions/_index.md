---
title: GradientGeometricFunctions
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.bargrddetector/gradientgeometricfunctions/
---
**Inheritance:**
java.lang.Object
```
public class GradientGeometricFunctions
```
## Constructors

| Constructor | Description |
| --- | --- |
| [GradientGeometricFunctions()](#GradientGeometricFunctions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [calculateGradientAngle(GradientDirection mainDirection, float mainPower, GradientDirection secondaryDirection, float secondaryPower)](#calculateGradientAngle-com.aspose.barcode.barcoderecognition.bargrddetector.GradientDirection-float-com.aspose.barcode.barcoderecognition.bargrddetector.GradientDirection-float-) |  |
| [doDirectionalBlur(GradientMetrics gradientMetrics)](#doDirectionalBlur-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointDirectionalBlur(GradientMetrics gradientMetrics, int x, int y)](#pointDirectionalBlur-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-int-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientGeometricFunctions() {#GradientGeometricFunctions--}
```
public GradientGeometricFunctions()
```


### calculateGradientAngle(GradientDirection mainDirection, float mainPower, GradientDirection secondaryDirection, float secondaryPower) {#calculateGradientAngle-com.aspose.barcode.barcoderecognition.bargrddetector.GradientDirection-float-com.aspose.barcode.barcoderecognition.bargrddetector.GradientDirection-float-}
```
public static float calculateGradientAngle(GradientDirection mainDirection, float mainPower, GradientDirection secondaryDirection, float secondaryPower)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mainDirection | [GradientDirection](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientdirection) |  |
| mainPower | float |  |
| secondaryDirection | [GradientDirection](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientdirection) |  |
| secondaryPower | float |  |

**Returns:**
float
### doDirectionalBlur(GradientMetrics gradientMetrics) {#doDirectionalBlur-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-}
```
public static GradientMetrics doDirectionalBlur(GradientMetrics gradientMetrics)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gradientMetrics | [GradientMetrics](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientmetrics) |  |

**Returns:**
[GradientMetrics](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientmetrics)
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




### pointDirectionalBlur(GradientMetrics gradientMetrics, int x, int y) {#pointDirectionalBlur-com.aspose.barcode.barcoderecognition.bargrddetector.GradientMetrics-int-int-}
```
public static float[] pointDirectionalBlur(GradientMetrics gradientMetrics, int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gradientMetrics | [GradientMetrics](../../com.aspose.barcode.barcoderecognition.bargrddetector/gradientmetrics) |  |
| x | int |  |
| y | int |  |

**Returns:**
float[]
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

