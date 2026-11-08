---
title: "Quadrangle"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Speichert ein Set von vier Points, die eine Quadrangle-Region darstellen."
type: docs
weight: 39
url: /de/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Speichert ein Set von vier Point s, die eine Quadrangle Region darstellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Initialisiert eine neue Instanz der  Quadrangle  Klasse mit den beschreibenden Punkten. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EMPTY](#EMPTY) | Stellt eine  Quadrangle  Klasse dar, deren Eigenschaften nicht initialisiert sind. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Bestimmt, ob das angegebene  Quadrangle  enthalten ist oder diese  Quadrangle  Klasse schneidet. |
| [contains(int x, int y)](#contains-int-int-) | Bestimmt, ob der angegebene Punkt innerhalb dieser  Quadrangle  Klasse enthalten ist. |
| [contains(Point pt)](#contains-java.awt.Point-) | Bestimmt, ob das angegebene  Point  innerhalb dieser  Quadrangle  Klasse enthalten ist. |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Bestimmt, ob das angegebene  Rectangle  enthalten ist oder diese  Quadrangle  Klasse schneidet. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen  Quadrangle  Wert entspricht. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Erstellt ein  Rectangle  das diese  Quadrangle  begrenzt. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Liefert den linken unteren Eckpunkt  Point  der  Quadrangle  Region |
| [getLeftTop()](#getLeftTop--) | Liefert den linken oberen Eckpunkt  Point  der  Quadrangle  Region |
| [getRightBottom()](#getRightBottom--) | Liefert den rechten unteren Eckpunkt  Point  der  Quadrangle  Region |
| [getRightTop()](#getRightTop--) | Liefert den rechten oberen Eckpunkt  Point  der  Quadrangle  Region |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isEmpty--) | Testet, ob alle  Point s dieses  Quadrangle  den Wert Null haben. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Liefert den linken unteren Eckpunkt  Point  der  Quadrangle  Region |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Liefert den linken oberen Eckpunkt  Point  der  Quadrangle  Region |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Liefert den rechten unteren Eckpunkt  Point  der  Quadrangle  Region |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Liefert den rechten oberen Eckpunkt  Point  der  Quadrangle  Region |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses  Quadrangle  zurück. |
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


Initialisiert eine neue Instanz der  Quadrangle  Klasse mit den beschreibenden Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftTop | java.awt.Point | Ein  Point  der die linke obere Ecke des Quadrangle darstellt. |
| rightTop | java.awt.Point | Ein  Point  der die rechte obere Ecke des Quadrangle darstellt. |
| rightBottom | java.awt.Point | Ein  Point  der die rechte untere Ecke des Quadrangle darstellt. |
| leftBottom | java.awt.Point | Ein  Point  der die linke untere Ecke des Quadrangle darstellt. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Stellt eine  Quadrangle  Klasse dar, deren Eigenschaften nicht initialisiert sind.

Wert:  Quadrangle

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


Bestimmt, ob das angegebene  Quadrangle  enthalten ist oder diese  Quadrangle  Klasse schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Das  Quadrangle  zum Testen. |

**Returns:**
boolean - Gibt  **true**  zurück, wenn  Quadrangle  in dieser  Quadrangle  Klasse enthalten oder geschnitten ist; andernfalls  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser  Quadrangle  Klasse enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Punktkoordinate. |
| y | int | Die y-Punktkoordinate. |

**Returns:**
boolean - Gibt  **true**  zurück, wenn der Punkt innerhalb dieser  Quadrangle  Klasse enthalten ist; andernfalls  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Bestimmt, ob das angegebene  Point  innerhalb dieser  Quadrangle  Klasse enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | java.awt.Point | Der  Point  zum Testen. |

**Returns:**
boolean - Gibt  **true**  zurück, wenn  Point  innerhalb dieser  Quadrangle  Klasse enthalten ist; andernfalls  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Bestimmt, ob das angegebene  Rectangle  enthalten ist oder diese  Quadrangle  Klasse schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | java.awt.Rectangle | Das  Rectangle  zum Testen. |

**Returns:**
boolean - Gibt  **true**  zurück, wenn  Rectangle  in dieser  Quadrangle  Klasse enthalten oder geschnitten ist; andernfalls  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen  Quadrangle  Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein  Quadrangle  Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolesch -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Erstellt ein  Rectangle  das diese  Quadrangle  begrenzt.

**Returns:**
java.awt.Rectangle - gibt das Rectangle zurück, das dieses Quadrangle begrenzt
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


Liefert den linken unteren Eckpunkt  Point  der  Quadrangle  Region

Wert: Ein linke‑untere Ecke Punkt des Quadrangle‑Gebiets

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Liefert den linken oberen Eckpunkt  Point  der  Quadrangle  Region

Wert: Ein linke‑obere Ecke Punkt des Quadrangle‑Gebiets

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Liefert den rechten unteren Eckpunkt  Point  der  Quadrangle  Region

Wert: Ein rechte‑untere Ecke Punkt des Quadrangle‑Gebiets

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Liefert den rechten oberen Eckpunkt  Point  der  Quadrangle  Region

Wert: Ein rechte‑obere Ecke Punkt des Quadrangle‑Gebiets

**Returns:**
java.awt.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Ganzzahl-Hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Testet, ob alle  Point s dieses  Quadrangle  den Wert Null haben.

Wert: Gibt **true** zurück, wenn alle Punkte dieses Quadrangle den Wert null haben; andernfalls **false**.

**Returns:**
boolesch
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


Liefert den linken unteren Eckpunkt  Point  der  Quadrangle  Region

Wert: Ein linke‑untere Ecke Punkt des Quadrangle‑Gebiets

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Liefert den linken oberen Eckpunkt  Point  der  Quadrangle  Region

Wert: Ein linke‑obere Ecke Punkt des Quadrangle‑Gebiets

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Liefert den rechten unteren Eckpunkt  Point  der  Quadrangle  Region

Wert: Ein rechte‑untere Ecke Punkt des Quadrangle‑Gebiets

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Liefert den rechten oberen Eckpunkt  Point  der  Quadrangle  Region

Wert: Ein rechte‑obere Ecke Punkt des Quadrangle‑Gebiets

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses  Quadrangle  zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses Quadrangle darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

