---
title: RectangleVertexes
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes/
---
**Inheritance:**
java.lang.Object
```
public class RectangleVertexes
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RectangleVertexes()](#RectangleVertexes--) |  |
| [RectangleVertexes(RectangleVertexes vertexes)](#RectangleVertexes-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-) |  |
| [RectangleVertexes(System.Drawing.Point leftTop, System.Drawing.Point rightTop, System.Drawing.Point leftBottom, System.Drawing.Point rightBottom)](#RectangleVertexes-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [RectangleVertexes(System.Drawing.Rectangle rectangle)](#RectangleVertexes-com.aspose.ms.System.Drawing.Rectangle-) |  |
## Fields

| Field | Description |
| --- | --- |
| [leftBottom](#leftBottom) |  |
| [leftTop](#leftTop) |  |
| [rightBottom](#rightBottom) |  |
| [rightTop](#rightTop) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fullRect()](#fullRect--) | Calculates the smallest rectangle containing all points |
| [fullRectangleVertexes()](#fullRectangleVertexes--) |  |
| [getClass()](#getClass--) |  |
| [getHeightLeft()](#getHeightLeft--) | Left height |
| [getHeightRight()](#getHeightRight--) | Right height |
| [getWidthBottom()](#getWidthBottom--) | Bottom width |
| [getWidthTop()](#getWidthTop--) | Top width |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [regionTransformation(ByteBitmap byteBitmap, float dimensionX, float dimensionY)](#regionTransformation-com.aspose.barcode.common.bitmaps.ByteBitmap-float-float-) | Create region transformation |
| [toArray()](#toArray--) |  |
| [toList()](#toList--) | Converts points to a generic list |
| [toRectange()](#toRectange--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleVertexes() {#RectangleVertexes--}
```
public RectangleVertexes()
```


### RectangleVertexes(RectangleVertexes vertexes) {#RectangleVertexes-com.aspose.barcode.barcoderecognition.recognition.RectangleVertexes-}
```
public RectangleVertexes(RectangleVertexes vertexes)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vertexes | [RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes) |  |

### RectangleVertexes(System.Drawing.Point leftTop, System.Drawing.Point rightTop, System.Drawing.Point leftBottom, System.Drawing.Point rightBottom) {#RectangleVertexes-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public RectangleVertexes(System.Drawing.Point leftTop, System.Drawing.Point rightTop, System.Drawing.Point leftBottom, System.Drawing.Point rightBottom)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftTop | com.aspose.ms.System.Drawing.Point |  |
| rightTop | com.aspose.ms.System.Drawing.Point |  |
| leftBottom | com.aspose.ms.System.Drawing.Point |  |
| rightBottom | com.aspose.ms.System.Drawing.Point |  |

### RectangleVertexes(System.Drawing.Rectangle rectangle) {#RectangleVertexes-com.aspose.ms.System.Drawing.Rectangle-}
```
public RectangleVertexes(System.Drawing.Rectangle rectangle)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### leftBottom {#leftBottom}
```
public System.Drawing.Point leftBottom
```


### leftTop {#leftTop}
```
public System.Drawing.Point leftTop
```


### rightBottom {#rightBottom}
```
public System.Drawing.Point rightBottom
```


### rightTop {#rightTop}
```
public System.Drawing.Point rightTop
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
### fullRect() {#fullRect--}
```
public System.Drawing.Rectangle fullRect()
```


Calculates the smallest rectangle containing all points

**Returns:**
com.aspose.ms.System.Drawing.Rectangle - 
### fullRectangleVertexes() {#fullRectangleVertexes--}
```
public RectangleVertexes fullRectangleVertexes()
```




**Returns:**
[RectangleVertexes](../../com.aspose.barcode.barcoderecognition.recognition/rectanglevertexes)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeightLeft() {#getHeightLeft--}
```
public int getHeightLeft()
```


Left height

**Returns:**
int
### getHeightRight() {#getHeightRight--}
```
public int getHeightRight()
```


Right height

**Returns:**
int
### getWidthBottom() {#getWidthBottom--}
```
public int getWidthBottom()
```


Bottom width

**Returns:**
int
### getWidthTop() {#getWidthTop--}
```
public int getWidthTop()
```


Top width

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




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




### regionTransformation(ByteBitmap byteBitmap, float dimensionX, float dimensionY) {#regionTransformation-com.aspose.barcode.common.bitmaps.ByteBitmap-float-float-}
```
public RegionalTransformation2D regionTransformation(ByteBitmap byteBitmap, float dimensionX, float dimensionY)
```


Create region transformation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| dimensionX | float | Dimension X |
| dimensionY | float | Dimension Y |

**Returns:**
[RegionalTransformation2D](../../com.aspose.barcode.barcoderecognition.internal/regionaltransformation2d) - A transformation
### toArray() {#toArray--}
```
public System.Drawing.Point[] toArray()
```




**Returns:**
com.aspose.ms.System.Drawing.Point[]
### toList() {#toList--}
```
public System.Collections.Generic.List<System.Drawing.Point> toList()
```


Converts points to a generic list

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - 
### toRectange() {#toRectange--}
```
public System.Drawing.Rectangle toRectange()
```




**Returns:**
com.aspose.ms.System.Drawing.Rectangle
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

