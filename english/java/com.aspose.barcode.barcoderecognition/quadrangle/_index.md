---
title: Quadrangle
second_title: Aspose.BarCode for Java API Reference
description: Stores a set of four Points that represent a Quadrangle region.
type: docs
weight: 35
url: /java/com.aspose.barcode.barcoderecognition/quadrangle/
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
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Initializes a new instance of the  Quadrangle  class with the describing points. |
## Fields

| Field | Description |
| --- | --- |
| [EMPTY](#EMPTY) | Represents a  Quadrangle  class with its properties left uninitialized. |
## Methods

| Method | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Determines if the specified  Quadrangle  is contained or intersect this  Quadrangle  class. |
| [contains(int x, int y)](#contains-int-int-) | Determines if the specified point is contained within this  Quadrangle  class. |
| [contains(Point pt)](#contains-java.awt.Point-) | Determines if the specified  Point  is contained within this  Quadrangle  class. |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Determines if the specified  Rectangle  is contained or intersect this  Quadrangle  class. |
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
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Gets left-bottom corner  Point  of  Quadrangle  region |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Gets left-top corner  Point  of  Quadrangle  region |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Gets right-bottom corner  Point  of  Quadrangle  region |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Gets right-top corner  Point  of  Quadrangle  region |
| [toString()](#toString--) | Returns a human-readable string representation of this  Quadrangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Initializes a new instance of the  Quadrangle  class with the describing points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftTop | java.awt.Point | A  Point  that represents the left-top corner of the Quadrangle. |
| rightTop | java.awt.Point | A  Point  that represents the right-top corner of the Quadrangle. |
| rightBottom | java.awt.Point | A  Point  that represents the right-bottom corner of the Quadrangle. |
| leftBottom | java.awt.Point | A  Point  that represents the left-bottom corner of the Quadrangle. |

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
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Determines if the specified  Point  is contained within this  Quadrangle  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | java.awt.Point | The  Point  to test. |

**Returns:**
boolean - Returns  **true**  if  Point  is contained within this  Quadrangle  class; otherwise,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determines if the specified  Rectangle  is contained or intersect this  Quadrangle  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | The  Rectangle  to test. |

**Returns:**
boolean - Returns  **true**  if  Rectangle  is contained or intersect this  Quadrangle  class; otherwise,  **false** .
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
public Rectangle getBoundingRectangle()
```


Creates  Rectangle  bounding this  Quadrangle 

**Returns:**
java.awt.Rectangle - returns  Rectangle  bounding this  Quadrangle 
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
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Gets left-top corner  Point  of  Quadrangle  region

Value: A left-top corner  Point  of  Quadrangle  region

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Gets right-bottom corner  Point  of  Quadrangle  region

Value: A right-bottom corner  Point  of  Quadrangle  region

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Gets right-top corner  Point  of  Quadrangle  region

Value: A right-top corner  Point  of  Quadrangle  region

**Returns:**
java.awt.Point
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




### setLeftBottom(Point value) {#setLeftBottom-java.awt.Point-}
```
public void setLeftBottom(Point value)
```


Gets left-bottom corner  Point  of  Quadrangle  region

Value: A left-bottom corner  Point  of  Quadrangle  region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Gets left-top corner  Point  of  Quadrangle  region

Value: A left-top corner  Point  of  Quadrangle  region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Gets right-bottom corner  Point  of  Quadrangle  region

Value: A right-bottom corner  Point  of  Quadrangle  region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Gets right-top corner  Point  of  Quadrangle  region

Value: A right-top corner  Point  of  Quadrangle  region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Point |  |

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

