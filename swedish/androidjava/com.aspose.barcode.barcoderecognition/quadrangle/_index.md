---
title: Quadrangle
second_title: Aspose.BarCode for Android via Java API-referens
description: Lagrar en uppsättning av fyra Points som representerar en Quadrangle-region.
type: docs
weight: 43
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Lagrar en uppsättning av fyra  Point s som representerar ett  Quadrangle  område.
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Initierar en ny instans av  Quadrangle  strukturen med de beskrivande punkterna. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EMPTY](#EMPTY) | Representerar en  Quadrangle  klass med dess egenskaper oinitierade. |
## Methods

| Method | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Bestämmer om den angivna  Point  finns inom denna  Quadrangle  klass. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Bestämmer om den angivna  Rectangle  är innehållen i eller skär denna  Quadrangle  klass. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Bestämmer om den angivna  Quadrangle  är innehållen i eller skär denna  Quadrangle  klass. |
| [contains(int x, int y)](#contains-int-int-) | Bestämmer om den angivna punkten finns inom denna  Quadrangle  klass. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet  Quadrangle  värde. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Skapar  Rectangle  som avgränsar denna  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Hämtar vänster-nedre hörn  Point  av  Quadrangle  region |
| [getLeftTop()](#getLeftTop--) | Gets left-top corner  Point  of  Quadrangle  region |
| [getRightBottom()](#getRightBottom--) | Gets right-bottom corner  Point  of  Quadrangle  region |
| [getRightTop()](#getRightTop--) | Gets right-top corner  Point  of  Quadrangle  region |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Tests whether all  Point s of this  Quadrangle  have values of zero. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Hämtar vänster-nedre hörn  Point  av  Quadrangle  region |
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


Initierar en ny instans av  Quadrangle  strukturen med de beskrivande punkterna.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| leftTop | android.graphics.Point | A  Point  that represents the left-top corner of the Quadrangle. |
| rightTop | android.graphics.Point | A  Point  that represents the right-top corner of the Quadrangle. |
| rightBottom | android.graphics.Point | A  Point  that represents the right-bottom corner of the Quadrangle. |
| leftBottom | android.graphics.Point | A  Point  that represents the left-bottom corner of the Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Representerar en  Quadrangle  klass med dess egenskaper oinitierade.

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


Bestämmer om den angivna  Point  finns inom denna  Quadrangle  klass.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| pt | android.graphics.Point | The  Point  to test. |

**Returns:**
boolean - Returns  **true**  if  Point  is contained within this  Quadrangle  class; otherwise,  **false** .
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Bestämmer om den angivna  Rectangle  är innehållen i eller skär denna  Quadrangle  klass.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| rect | android.graphics.Rect | The  Rectangle  to test. |

**Returns:**
boolean - Returns  **true**  if  Rectangle  is contained or intersect this  Quadrangle  class; otherwise,  **false** .
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Bestämmer om den angivna  Quadrangle  är innehållen i eller skär denna  Quadrangle  klass.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | The  Quadrangle  to test. |

**Returns:**
boolean - Returns  **true**  if  Quadrangle  is contained or intersect this  Quadrangle  class; otherwise,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestämmer om den angivna punkten finns inom denna  Quadrangle  klass.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| x | int | The x point cordinate. |
| y | int | Den y-punktskoordinaten. |

**Returns:**
boolean - Returnerar  **true**  om punkten finns inom denna  Quadrangle  klass; annars,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om denna instans är lika med ett angivet  Quadrangle  värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett  Quadrangle  värde att jämföra med denna instans. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Skapar  Rectangle  som avgränsar denna  Quadrangle

**Returns:**
android.graphics.Rect - returnerar  Rectangle  som avgränsar denna  Quadrangle
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


Hämtar vänster-nedre hörn  Point  av  Quadrangle  region

Värde: En vänster-nedre hörn  Point  av  Quadrangle  regionen

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Gets left-top corner  Point  of  Quadrangle  region

Värde: En vänster-övre hörn  Point  av  Quadrangle  regionen

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Gets right-bottom corner  Point  of  Quadrangle  region

Värde: En höger-nedre hörn  Point  av  Quadrangle  regionen

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Gets right-top corner  Point  of  Quadrangle  region

Värde: En höger-övre hörn  Point  av  Quadrangle  regionen

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Tests whether all  Point s of this  Quadrangle  have values of zero.

Värde: Returnerar  **true**  om alla  Point s i denna  Quadrangle  har värdena noll; annars,  **false** .

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


Hämtar vänster-nedre hörn  Point  av  Quadrangle  region

Värde: En vänster-nedre hörn  Point  av  Quadrangle  regionen

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Gets left-top corner  Point  of  Quadrangle  region

Värde: En vänster-övre hörn  Point  av  Quadrangle  regionen

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Gets right-bottom corner  Point  of  Quadrangle  region

Värde: En höger-nedre hörn  Point  av  Quadrangle  regionen

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Gets right-top corner  Point  of  Quadrangle  region

Värde: En höger-övre hörn  Point  av  Quadrangle  regionen

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  Quadrangle .

**Returns:**
java.lang.String - En sträng som representerar denna  Quadrangle .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

