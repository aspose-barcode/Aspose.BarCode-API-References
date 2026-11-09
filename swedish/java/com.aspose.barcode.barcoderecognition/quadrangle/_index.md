---
title: "Quadrangle"
second_title: "Aspose.BarCode för Java API-referens"
description: "Lagrar en uppsättning av fyra Points som representerar ett Quadrangle‑område."
type: docs
weight: 39
url: /sv/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Lagrar en uppsättning av fyra  Point  som representerar ett  Quadrangle ‑område.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Initierar en ny instans av  Quadrangle  -klassen med de beskrivande punkterna. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EMPTY](#EMPTY) | Representerar en  Quadrangle  -klass med dess egenskaper oinitierade. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Bestämmer om den angivna  Quadrangle  är innehållen eller skär detta  Quadrangle  -klass. |
| [contains(int x, int y)](#contains-int-int-) | Bestämmer om den angivna punkten är innehållen i detta  Quadrangle  -klass. |
| [contains(Point pt)](#contains-java.awt.Point-) | Bestämmer om den angivna  Point  är innehållen i detta  Quadrangle  -klass. |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Bestämmer om den angivna  Rectangle  är innehållen eller skär detta  Quadrangle  -klass. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet  Quadrangle  -värde. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Skapar  Rectangle  som avgränsar detta  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Hämtar vänster‑nedre hörn  Point  för  Quadrangle  -regionen |
| [getLeftTop()](#getLeftTop--) | Hämtar vänster‑övre hörn  Point  för  Quadrangle  -regionen |
| [getRightBottom()](#getRightBottom--) | Hämtar höger‑nedre hörn  Point  för  Quadrangle  -regionen |
| [getRightTop()](#getRightTop--) | Hämtar höger‑övre hörn  Point  för  Quadrangle  -regionen |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [isEmpty()](#isEmpty--) | Testar om alla  Point  i detta  Quadrangle  har värdena noll. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Hämtar vänster‑nedre hörn  Point  för  Quadrangle  -regionen |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Hämtar vänster‑övre hörn  Point  för  Quadrangle  -regionen |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Hämtar höger‑nedre hörn  Point  för  Quadrangle  -regionen |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Hämtar höger‑övre hörn  Point  för  Quadrangle  -regionen |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta  Quadrangle . |
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


Initierar en ny instans av  Quadrangle  -klassen med de beskrivande punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftTop | java.awt.Point | En  Point  som representerar det vänstra övre hörnet av Quadrangle. |
| rightTop | java.awt.Point | En  Point  som representerar det högra övre hörnet av Quadrangle. |
| rightBottom | java.awt.Point | En  Point  som representerar det högra nedre hörnet av Quadrangle. |
| leftBottom | java.awt.Point | En  Point  som representerar det vänstra nedre hörnet av Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Representerar en  Quadrangle  -klass med dess egenskaper oinitierade.

Värde:  Quadrangle

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


Bestämmer om den angivna  Quadrangle  är innehållen eller skär detta  Quadrangle  -klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Den  Quadrangle  att testa. |

**Returns:**
boolean - Returnerar  **true**  om  Quadrangle  är innehållen eller skär detta  Quadrangle  klass; annars,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestämmer om den angivna punkten är innehållen i detta  Quadrangle  -klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den x-punkts koordinat. |
| y | int | Den y-punkts koordinat. |

**Returns:**
boolean - Returnerar  **true**  om punkt är innehållen inom detta  Quadrangle  klass; annars,  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Bestämmer om den angivna  Point  är innehållen i detta  Quadrangle  -klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | java.awt.Point | Den  Point  att testa. |

**Returns:**
boolean - Returnerar  **true**  om  Point  är innehållen inom detta  Quadrangle  klass; annars,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Bestämmer om den angivna  Rectangle  är innehållen eller skär detta  Quadrangle  -klass.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | java.awt.Rectangle | Den  Rectangle  att testa. |

**Returns:**
boolean - Returnerar  **true**  om  Rectangle  är innehållen eller skär detta  Quadrangle  klass; annars,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om denna instans är lika med ett angivet  Quadrangle  -värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett  Quadrangle  värde att jämföra med detta objekt. |

**Returns:**
boolesk -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Skapar  Rectangle  som avgränsar detta  Quadrangle

**Returns:**
java.awt.Rectangle - returnerar Rectangle som avgränsar denna Quadrangle
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


Hämtar vänster‑nedre hörn  Point  för  Quadrangle  -regionen

Värde: Ett vänster-nedre hörn Point av Quadrangle region

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Hämtar vänster‑övre hörn  Point  för  Quadrangle  -regionen

Värde: Ett vänster-övre hörn Point av Quadrangle region

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Hämtar höger‑nedre hörn  Point  för  Quadrangle  -regionen

Värde: Ett höger-nedre hörn Point av Quadrangle region

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Hämtar höger‑övre hörn  Point  för  Quadrangle  -regionen

Värde: Ett höger-övre hörn Point av Quadrangle region

**Returns:**
java.awt.Point
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


Testar om alla  Point  i detta  Quadrangle  har värdena noll.

Värde: Returnerar **true** om alla Point i denna Quadrangle har värdet noll; annars **false**.

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


Hämtar vänster‑nedre hörn  Point  för  Quadrangle  -regionen

Värde: Ett vänster-nedre hörn Point av Quadrangle region

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Hämtar vänster‑övre hörn  Point  för  Quadrangle  -regionen

Värde: Ett vänster-övre hörn Point av Quadrangle region

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Hämtar höger‑nedre hörn  Point  för  Quadrangle  -regionen

Värde: Ett höger-nedre hörn Point av Quadrangle region

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Hämtar höger‑övre hörn  Point  för  Quadrangle  -regionen

Värde: Ett höger-övre hörn Point av Quadrangle region

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta  Quadrangle .

**Returns:**
java.lang.String - En sträng som representerar denna Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

