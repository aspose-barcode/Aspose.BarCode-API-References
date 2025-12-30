---
title: Quadrangle
second_title: Aspose.BarCode for Android via Java API Reference
description: Stores a set of four Points that represent a Quadrangle region.
type: docs
weight: 42
url: /androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Stores a set of four  Point s that represent a  Quadrangle  region.
## Constructors

| Constructor | Description |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Initializes a new instance of the  Quadrangle  structure with the describing points. |
## Fields

| Field | Description |
| --- | --- |
| [EMPTY](#EMPTY) | Represents a  Quadrangle  class with its properties left uninitialized. |
## Methods

| Method | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Determines if the specified  Point  is contained within this  Quadrangle  class. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Determines if the specified  Rectangle  is contained or intersect this  Quadrangle  class. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Determines if the specified  Quadrangle  is contained or intersect this  Quadrangle  class. |
| [contains(int x, int y)](#contains-int-int-) | Determines if the specified point is contained within this  Quadrangle  class. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  Quadrangle  value. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Creates  Rectangle  bounding this  Quadrangle  |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Gets left-bottom corner  Point  of  Quadrangle  region |
| [getLeftTop()](#getLeftTop--) | Gets left-top corner  Point  of  Quadrangle  region |
| [getRightBottom()](#getRightBottom--) | Gets right-bottom corner  Point  of  Quadrangle  region |
| [getRightTop()](#getRightTop--) | Gets right-top corner  Point  of  Quadrangle  region |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [isEmpty()](#isEmpty--) | Tests whether all  Point s of this  Quadrangle  have values of zero. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Gets left-bottom corner  Point  of  Quadrangle  region |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Gets left-top corner  Point  of  Quadrangle  region |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Gets right-bottom corner  Point  of  Quadrangle  region |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Gets right-top corner  Point  of  Quadrangle  region |
| [toString()](#toString--) | Returns a human-readable string representation of this  Quadrangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Initializes a new instance of the  Quadrangle  structure with the describing points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftTop | android.graphics.Point | A  Point  that represents the left-top corner of the Quadrangle. |
| rightTop | android.graphics.Point | A  Point  that represents the right-top corner of the Quadrangle. |
| rightBottom | android.graphics.Point | A  Point  that represents the right-bottom corner of the Quadrangle. |
| leftBottom | android.graphics.Point | A  Point  that represents the left-bottom corner of the Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Represents a  Quadrangle  class with its properties left uninitialized.

Value:  Quadrangle 

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


Determines if the specified  Point  is contained within this  Quadrangle  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | android.graphics.Point | The  Point  to test. |

**Returns:**
boolean - Returns  **true**  if  Point  is contained within this  Quadrangle  class; otherwise,  **false** .
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Determines if the specified  Rectangle  is contained or intersect this  Quadrangle  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | android.graphics.Rect | The  Rectangle  to test. |

**Returns:**
boolean - Returns  **true**  if  Rectangle  is contained or intersect this  Quadrangle  class; otherwise,  **false** .
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Determines if the specified  Quadrangle  is contained or intersect this  Quadrangle  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | The  Quadrangle  to test. |

**Returns:**
boolean - Returns  **true**  if  Quadrangle  is contained or intersect this  Quadrangle  class; otherwise,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determines if the specified point is contained within this  Quadrangle  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x point cordinate. |
| y | int | The y point cordinate. |

**Returns:**
boolean - Returns  **true**  if point is contained within this  Quadrangle  class; otherwise,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified  Quadrangle  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | An  Quadrangle  value to compare to this instance. |

**Returns:**
boolean -  **true**  if obj has the same value as this instance; otherwise,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Creates  Rectangle  bounding this  Quadrangle 

**Returns:**
android.graphics.Rect - returns  Rectangle  bounding this  Quadrangle 
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


Gets left-bottom corner  Point  of  Quadrangle  region

Value: A left-bottom corner  Point  of  Quadrangle  region

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Gets left-top corner  Point  of  Quadrangle  region

Value: A left-top corner  Point  of  Quadrangle  region

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Gets right-bottom corner  Point  of  Quadrangle  region

Value: A right-bottom corner  Point  of  Quadrangle  region

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Gets right-top corner  Point  of  Quadrangle  region

Value: A right-top corner  Point  of  Quadrangle  region

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this instance.

**Returns:**
int - A 32-bit signed integer hash code.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Tests whether all  Point s of this  Quadrangle  have values of zero.

Value: Returns  **true**  if all  Point s of this  Quadrangle  have values of zero; otherwise,  **false** .

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




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


Gets left-bottom corner  Point  of  Quadrangle  region

Value: A left-bottom corner  Point  of  Quadrangle  region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Gets left-top corner  Point  of  Quadrangle  region

Value: A left-top corner  Point  of  Quadrangle  region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Gets right-bottom corner  Point  of  Quadrangle  region

Value: A right-bottom corner  Point  of  Quadrangle  region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Gets right-top corner  Point  of  Quadrangle  region

Value: A right-top corner  Point  of  Quadrangle  region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  Quadrangle .

**Returns:**
java.lang.String - A string that represents this  Quadrangle .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

