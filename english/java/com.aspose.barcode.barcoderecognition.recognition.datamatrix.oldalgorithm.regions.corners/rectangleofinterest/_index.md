---
title: RectangleOfInterest
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions.corners/rectangleofinterest/
---
**Inheritance:**
java.lang.Object
```
public class RectangleOfInterest
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RectangleOfInterest()](#RectangleOfInterest--) |  |
## Fields

| Field | Description |
| --- | --- |
| [AllowDamagedBorder](#AllowDamagedBorder) |  |
| [Blur](#Blur) | A blur in the rectangle |
| [DetectedVertexes](#DetectedVertexes) | Rectangle vertexes. |
| [MinModule](#MinModule) | The smallest module in the rectangle |
| [X0](#X0) |  |
| [X0Bottom](#X0Bottom) |  |
| [X0Top](#X0Top) |  |
| [X1](#X1) |  |
| [X1Bottom](#X1Bottom) |  |
| [X1Top](#X1Top) |  |
| [Y0](#Y0) |  |
| [Y0Left](#Y0Left) |  |
| [Y0Right](#Y0Right) |  |
| [Y1](#Y1) |  |
| [Y1Left](#Y1Left) |  |
| [Y1Right](#Y1Right) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPossibleOrientation()](#getPossibleOrientation--) |  |
| [getRectangle()](#getRectangle--) |  |
| [getSize()](#getSize--) |  |
| [grow(int x, int y)](#grow-int-int-) |  |
| [hashCode()](#hashCode--) |  |
| [isRecognized()](#isRecognized--) |  |
| [locateVertexes(float[] angle)](#locateVertexes-float---) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reduceRight(int x)](#reduceRight-int-) | Reduce rectangle in the right by x. |
| [setPossibleOrientation(int value)](#setPossibleOrientation-int-) |  |
| [setRecognized(boolean value)](#setRecognized-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleOfInterest() {#RectangleOfInterest--}
```
public RectangleOfInterest()
```


### AllowDamagedBorder {#AllowDamagedBorder}
```
public boolean AllowDamagedBorder
```


### Blur {#Blur}
```
public float Blur
```


A blur in the rectangle

### DetectedVertexes {#DetectedVertexes}
```
public RectangleVertexes DetectedVertexes
```


Rectangle vertexes. It is calculated when bits are created

### MinModule {#MinModule}
```
public float MinModule
```


The smallest module in the rectangle

### X0 {#X0}
```
public int X0
```


### X0Bottom {#X0Bottom}
```
public System.Drawing.Point X0Bottom
```


### X0Top {#X0Top}
```
public System.Drawing.Point X0Top
```


### X1 {#X1}
```
public int X1
```


### X1Bottom {#X1Bottom}
```
public System.Drawing.Point X1Bottom
```


### X1Top {#X1Top}
```
public System.Drawing.Point X1Top
```


### Y0 {#Y0}
```
public int Y0
```


### Y0Left {#Y0Left}
```
public System.Drawing.Point Y0Left
```


### Y0Right {#Y0Right}
```
public System.Drawing.Point Y0Right
```


### Y1 {#Y1}
```
public int Y1
```


### Y1Left {#Y1Left}
```
public System.Drawing.Point Y1Left
```


### Y1Right {#Y1Right}
```
public System.Drawing.Point Y1Right
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPossibleOrientation() {#getPossibleOrientation--}
```
public final int getPossibleOrientation()
```




**Returns:**
int
### getRectangle() {#getRectangle--}
```
public final System.Drawing.Rectangle getRectangle()
```




**Returns:**
com.aspose.ms.System.Drawing.Rectangle
### getSize() {#getSize--}
```
public final float getSize()
```




**Returns:**
float
### grow(int x, int y) {#grow-int-int-}
```
public final void grow(int x, int y)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int |  |
| y | int |  |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isRecognized() {#isRecognized--}
```
public final boolean isRecognized()
```




**Returns:**
boolean
### locateVertexes(float[] angle) {#locateVertexes-float---}
```
public final RectangleVertexes locateVertexes(float[] angle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float[] |  |

**Returns:**
[RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reduceRight(int x) {#reduceRight-int-}
```
public final void reduceRight(int x)
```


Reduce rectangle in the right by x.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | new right x-coordinate |

### setPossibleOrientation(int value) {#setPossibleOrientation-int-}
```
public final void setPossibleOrientation(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRecognized(boolean value) {#setRecognized-boolean-}
```
public final void setRecognized(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

