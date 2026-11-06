---
title: "Quadrangle"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Speichert eine Menge von vier Punkten, die einen Quadrangle-Bereich darstellen."
type: docs
weight: 41
url: /de/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Speichert ein Set von vier Punkten, die eine Viereck-Region darstellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Initialisiert eine neue Instanz der  Quadrangle  Struktur mit den beschreibenden Punkten. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EMPTY](#EMPTY) | Stellt eine  Quadrangle  Klasse dar, deren Eigenschaften nicht initialisiert sind. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Bestimmt, ob der angegebene  Point  innerhalb dieser  Quadrangle  Klasse enthalten ist. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Bestimmt, ob das angegebene  Rectangle  in dieser  Quadrangle  Klasse enthalten oder geschnitten wird. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Bestimmt, ob das angegebene  Quadrangle  in dieser  Quadrangle  Klasse enthalten oder geschnitten wird. |
| [contains(int x, int y)](#contains-int-int-) | Bestimmt, ob der angegebene Punkt innerhalb dieser  Quadrangle  Klasse enthalten ist. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen  Quadrangle  Wert ist. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Erstellt ein  Rectangle  das diesen  Quadrangle  begrenzt |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Liefert den linken unteren Eckpunkt  Point  des  Quadrangle  Bereichs |
| [getLeftTop()](#getLeftTop--) | Liefert den linken oberen Eckpunkt  Point  des  Quadrangle  Bereichs |
| [getRightBottom()](#getRightBottom--) | Liefert den rechten unteren Eckpunkt  Point  des  Quadrangle  Bereichs |
| [getRightTop()](#getRightTop--) | Liefert den rechten oberen Eckpunkt  Point  des  Quadrangle  Bereichs |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isEmpty--) | Prüft, ob alle  Point s dieses  Quadrangle  den Wert Null haben. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Liefert den linken unteren Eckpunkt  Point  des  Quadrangle  Bereichs |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Liefert den linken oberen Eckpunkt  Point  des  Quadrangle  Bereichs |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Liefert den rechten unteren Eckpunkt  Point  des  Quadrangle  Bereichs |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Liefert den rechten oberen Eckpunkt  Point  des  Quadrangle  Bereichs |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses  Quadrangle  zurück. |
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


Initialisiert eine neue Instanz der  Quadrangle  Struktur mit den beschreibenden Punkten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftTop | android.graphics.Point | Ein  Point  der den linken oberen Eckpunkt des Quadrangle darstellt. |
| rightTop | android.graphics.Point | Ein Punkt, der die rechte obere Ecke des Quadrangles darstellt. |
| rightBottom | android.graphics.Point | Ein Punkt, der die rechte untere Ecke des Quadrangles darstellt. |
| leftBottom | android.graphics.Point | Ein Punkt, der die linke untere Ecke des Quadrangles darstellt. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Stellt eine  Quadrangle  Klasse dar, deren Eigenschaften nicht initialisiert sind.

Wert: Quadrangle

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


Bestimmt, ob der angegebene  Point  innerhalb dieser  Quadrangle  Klasse enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | android.graphics.Point | Der Punkt zum Testen. |

**Returns:**
boolean - Gibt **true** zurück, wenn Punkt innerhalb dieser Quadrangle‑Klasse enthalten ist; andernfalls **false**.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Bestimmt, ob das angegebene  Rectangle  in dieser  Quadrangle  Klasse enthalten oder geschnitten wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | android.graphics.Rect | Das Rechteck zum Testen. |

**Returns:**
boolean - Gibt **true** zurück, wenn Rechteck in dieser Quadrangle‑Klasse enthalten oder geschnitten ist; andernfalls **false**.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Bestimmt, ob das angegebene  Quadrangle  in dieser  Quadrangle  Klasse enthalten oder geschnitten wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Das Quadrangle zum Testen. |

**Returns:**
boolean - Gibt **true** zurück, wenn Quadrangle in dieser Quadrangle‑Klasse enthalten oder geschnitten ist; andernfalls **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser  Quadrangle  Klasse enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Punktes. |
| y | int | Die y‑Koordinate des Punktes. |

**Returns:**
boolean - Gibt **true** zurück, wenn Punkt innerhalb dieser Quadrangle‑Klasse enthalten ist; andernfalls **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen  Quadrangle  Wert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein Quadrangle-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**, wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Erstellt ein  Rectangle  das diesen  Quadrangle  begrenzt

**Returns:**
android.graphics.Rect - gibt das Rechteck zurück, das dieses Quadrangle umschließt
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


Liefert den linken unteren Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein Punkt in der linken unteren Ecke der Quadrangle-Region

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Liefert den linken oberen Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein Punkt in der linken oberen Ecke der Quadrangle-Region

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Liefert den rechten unteren Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein Punkt in der rechten unteren Ecke der Quadrangle-Region

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Liefert den rechten oberen Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein rechter oberer Eckpunkt des Quadrangle-Bereichs

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Integer‑Hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Prüft, ob alle  Point s dieses  Quadrangle  den Wert Null haben.

Wert: Gibt **true** zurück, wenn alle Punkte dieses Quadrangle den Wert null haben; andernfalls **false**.

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


Liefert den linken unteren Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein Punkt in der linken unteren Ecke der Quadrangle-Region

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Liefert den linken oberen Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein Punkt in der linken oberen Ecke der Quadrangle-Region

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Liefert den rechten unteren Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein Punkt in der rechten unteren Ecke der Quadrangle-Region

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Liefert den rechten oberen Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein rechter oberer Eckpunkt des Quadrangle-Bereichs

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Point |  |

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
public final void wait(long arg0)
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

