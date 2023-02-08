---
title: PerspectiveTransformation.Transformation
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.common.algorithms/perspectivetransformation.transformation/
---
**Inheritance:**
java.lang.Object
```
public static class PerspectiveTransformation.Transformation
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Transformation(QuadPointFs Q0, QuadPointFs QP)](#Transformation-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-) | creates Transformation from resulting and exists quadrangles |
| [Transformation(QuadPoints Q0, QuadPoints QP)](#Transformation-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-) | creates Transformation from resulting and exists quadrangles |
## Fields

| Field | Description |
| --- | --- |
| [a11](#a11) |  |
| [a12](#a12) |  |
| [a13](#a13) |  |
| [a21](#a21) |  |
| [a22](#a22) |  |
| [a23](#a23) |  |
| [a31](#a31) |  |
| [a32](#a32) |  |
| [a33](#a33) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getReversedTransformation()](#getReversedTransformation--) | Calculate reverse matrix of transformation and created Transformation object. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(System.Drawing.Point aPoint)](#transform-com.aspose.ms.System.Drawing.Point-) | Transforms point position by affine matrix https://en.wikipedia.org/wiki/3D\_projection |
| [transform(System.Drawing.PointF aPoint)](#transform-com.aspose.ms.System.Drawing.PointF-) | Transforms point position by affine matrix https://en.wikipedia.org/wiki/3D\_projection |
| [transform(System.Drawing.PointF[] aList)](#transform-com.aspose.ms.System.Drawing.PointF---) | Transforms points positions by affine matrix https://en.wikipedia.org/wiki/3D\_projection |
| [transform(System.Drawing.Point[] aList)](#transform-com.aspose.ms.System.Drawing.Point---) | Transforms points positions by affine matrix https://en.wikipedia.org/wiki/3D\_projection |
| [transform(List<System.Drawing.PointF> aList)](#transform-java.util.List-com.aspose.ms.System.Drawing.PointF--) |  |
| [transformPoint(List<System.Drawing.Point> aList)](#transformPoint-java.util.List-com.aspose.ms.System.Drawing.Point--) | Transforms points positions by affine matrix https://en.wikipedia.org/wiki/3D\_projection |
| [transformPointF(List<System.Drawing.PointF> aList)](#transformPointF-java.util.List-com.aspose.ms.System.Drawing.PointF--) | Transforms points positions by affine matrix https://en.wikipedia.org/wiki/3D\_projection |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Transformation(QuadPointFs Q0, QuadPointFs QP) {#Transformation-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPointFs-}
```
public Transformation(QuadPointFs Q0, QuadPointFs QP)
```


creates Transformation from resulting and exists quadrangles

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Q0 | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | resulting quadrangle, in most cases resulting bitmap rectangle. |
| QP | [QuadPointFs](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpointfs) | original quadrangle on recognized image |

### Transformation(QuadPoints Q0, QuadPoints QP) {#Transformation-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-com.aspose.barcode.barcoderecognition.common.algorithms.QuadPoints-}
```
public Transformation(QuadPoints Q0, QuadPoints QP)
```


creates Transformation from resulting and exists quadrangles

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Q0 | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | resulting quadrangle, in most cases resulting bitmap rectangle. |
| QP | [QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints) | original quadrangle on recognized image |

### a11 {#a11}
```
public float a11
```


### a12 {#a12}
```
public float a12
```


### a13 {#a13}
```
public float a13
```


### a21 {#a21}
```
public float a21
```


### a22 {#a22}
```
public float a22
```


### a23 {#a23}
```
public float a23
```


### a31 {#a31}
```
public float a31
```


### a32 {#a32}
```
public float a32
```


### a33 {#a33}
```
public float a33
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
### getReversedTransformation() {#getReversedTransformation--}
```
public PerspectiveTransformation.Transformation getReversedTransformation()
```


Calculate reverse matrix of transformation and created Transformation object. QuadOriginal -> QuadNew = new Transformation(QuadOriginal, QuadNew) Reverse: QuadNew -> QuadOriginal = new Transformation(QuadNew, QuadOriginal) or GetReversedTransformation from Transformation(QuadOriginal, QuadNew)

**Returns:**
[Transformation](../../com.aspose.barcode.barcoderecognition.common.algorithms/transformation) - transformation object for reverse transformation
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
### transform(System.Drawing.Point aPoint) {#transform-com.aspose.ms.System.Drawing.Point-}
```
public System.Drawing.Point transform(System.Drawing.Point aPoint)
```


Transforms point position by affine matrix https://en.wikipedia.org/wiki/3D\_projection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.Point | point |

**Returns:**
com.aspose.ms.System.Drawing.Point - transformed point
### transform(System.Drawing.PointF aPoint) {#transform-com.aspose.ms.System.Drawing.PointF-}
```
public System.Drawing.PointF transform(System.Drawing.PointF aPoint)
```


Transforms point position by affine matrix https://en.wikipedia.org/wiki/3D\_projection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aPoint | com.aspose.ms.System.Drawing.PointF | point |

**Returns:**
com.aspose.ms.System.Drawing.PointF - transformed point
### transform(System.Drawing.PointF[] aList) {#transform-com.aspose.ms.System.Drawing.PointF---}
```
public System.Drawing.PointF[] transform(System.Drawing.PointF[] aList)
```


Transforms points positions by affine matrix https://en.wikipedia.org/wiki/3D\_projection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | com.aspose.ms.System.Drawing.PointF[] | array of points |

**Returns:**
com.aspose.ms.System.Drawing.PointF[] - transformed array of points
### transform(System.Drawing.Point[] aList) {#transform-com.aspose.ms.System.Drawing.Point---}
```
public System.Drawing.Point[] transform(System.Drawing.Point[] aList)
```


Transforms points positions by affine matrix https://en.wikipedia.org/wiki/3D\_projection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | com.aspose.ms.System.Drawing.Point[] | array of points |

**Returns:**
com.aspose.ms.System.Drawing.Point[] - transformed array of points
### transform(List<System.Drawing.PointF> aList) {#transform-java.util.List-com.aspose.ms.System.Drawing.PointF--}
```
public List<System.Drawing.PointF> transform(List<System.Drawing.PointF> aList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.ms.System.Drawing.PointF> |  |

**Returns:**
[List](../../java.util/list)
### transformPoint(List<System.Drawing.Point> aList) {#transformPoint-java.util.List-com.aspose.ms.System.Drawing.Point--}
```
public List<System.Drawing.Point> transformPoint(List<System.Drawing.Point> aList)
```


Transforms points positions by affine matrix https://en.wikipedia.org/wiki/3D\_projection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.ms.System.Drawing.Point> | list of points |

**Returns:**
[List](../../java.util/list) - transformed list of points
### transformPointF(List<System.Drawing.PointF> aList) {#transformPointF-java.util.List-com.aspose.ms.System.Drawing.PointF--}
```
public List<System.Drawing.PointF> transformPointF(List<System.Drawing.PointF> aList)
```


Transforms points positions by affine matrix https://en.wikipedia.org/wiki/3D\_projection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.ms.System.Drawing.PointF> | list of points |

**Returns:**
[List](../../java.util/list) - transformed list of points
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

