---
title: "Quadrangle"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Lagrar en uppsättning av fyra Points som representerar ett Quadrangle-område."
type: docs
weight: 41
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Lagrar en uppsättning av fyra  Point s som representerar ett  Quadrangle  område.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Initierar en ny instans av  Quadrangle  strukturen med de beskrivande punkterna. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EMPTY](#EMPTY) | Representerar en  Quadrangle  klass med dess egenskaper oinitierade. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Bestämmer om den angivna  Point  finns inom denna  Quadrangle  klass. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Bestämmer om den angivna  Rectangle  är innehållen eller skär detta  Quadrangle  klass. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Bestämmer om den angivna  Quadrangle  är innehållen eller skär detta  Quadrangle  klass. |
| [contains(int x, int y)](#contains-int-int-) | Bestämmer om den angivna punkten finns inom denna  Quadrangle  klass. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet  Quadrangle  värde. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Skapar  Rectangle  som omger detta  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Hämtar vänster-nedre hörn  Point  av  Quadrangle  region |
| [getLeftTop()](#getLeftTop--) | Hämtar vänster-övre hörn  Point  av  Quadrangle  region |
| [getRightBottom()](#getRightBottom--) | Hämtar höger-nedre hörn  Point  av  Quadrangle  region |
| [getRightTop()](#getRightTop--) | Hämtar höger-övre hörn  Point  av  Quadrangle  region |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Testar om alla  Point s i detta  Quadrangle  har värdena noll. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Hämtar vänster-nedre hörn  Point  av  Quadrangle  region |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Hämtar vänster-övre hörn  Point  av  Quadrangle  region |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Hämtar höger-nedre hörn  Point  av  Quadrangle  region |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Hämtar höger-övre hörn  Point  av  Quadrangle  region |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta  Quadrangle . |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftTop | android.graphics.Point | En  Point  som representerar vänster-övre hörnet av Quadrangle. |
| rightTop | android.graphics.Point | En  Point  som representerar det högra övre hörnet av Quadrangle. |
| rightBottom | android.graphics.Point | En  Point  som representerar det högra nedre hörnet av Quadrangle. |
| leftBottom | android.graphics.Point | En  Point  som representerar det vänstra nedre hörnet av Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Representerar en  Quadrangle  klass med dess egenskaper oinitierade.

Värde:  Quadrangle

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | android.graphics.Point | Den  Point  som ska testas. |

**Returns:**
boolean - Returnerar  **true**  om  Point  finns inom denna  Quadrangle  klass; annars,  **false** .
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Bestämmer om den angivna  Rectangle  är innehållen eller skär detta  Quadrangle  klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | android.graphics.Rect | Den  Rectangle  som ska testas. |

**Returns:**
boolean - Returnerar  **true**  om  Rectangle  finns inom eller skär denna  Quadrangle  klass; annars,  **false** .
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Bestämmer om den angivna  Quadrangle  är innehållen eller skär detta  Quadrangle  klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Den  Quadrangle  som ska testas. |

**Returns:**
boolean - Returnerar  **true**  om  Quadrangle  finns inom eller skär denna  Quadrangle  klass; annars,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestämmer om den angivna punkten finns inom denna  Quadrangle  klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den x‑punktkoordinaten. |
| y | int | Den y‑punktkoordinaten. |

**Returns:**
boolean - Returnerar  **true**  om punkt är inom denna  Quadrangle  klass; annars,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om denna instans är lika med ett angivet  Quadrangle  värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett  Quadrangle  värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Skapar  Rectangle  som omger detta  Quadrangle

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


Hämtar vänster-övre hörn  Point  av  Quadrangle  region

Värde: En vänster-övre hörn  Point  av  Quadrangle  regionen

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Hämtar höger-nedre hörn  Point  av  Quadrangle  region

Värde: En höger-nedre hörn  Point  av  Quadrangle  regionen

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Hämtar höger-övre hörn  Point  av  Quadrangle  region

Värde: En övre högra hörnpunkt av fyrhörningsområde

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bit signerad heltals‑hashkod.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Testar om alla  Point s i detta  Quadrangle  har värdena noll.

Värde: Returnerar **true** om alla punkter i denna fyrhörning har värdet noll; annars **false**.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Hämtar vänster-övre hörn  Point  av  Quadrangle  region

Värde: En vänster-övre hörn  Point  av  Quadrangle  regionen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Hämtar höger-nedre hörn  Point  av  Quadrangle  region

Värde: En höger-nedre hörn  Point  av  Quadrangle  regionen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Hämtar höger-övre hörn  Point  av  Quadrangle  region

Värde: En övre högra hörnpunkt av fyrhörningsområde

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta  Quadrangle .

**Returns:**
java.lang.String - En sträng som representerar denna fyrhörning.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

