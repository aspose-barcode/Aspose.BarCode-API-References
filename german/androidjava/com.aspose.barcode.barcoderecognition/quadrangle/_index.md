---
title: Quadrangle
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Speichert ein Set von vier Punkten, die einen Quadrangle-Bereich darstellen.
type: docs
weight: 43
url: /de/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Speichert ein Set von vier  Point s, die eine  Quadrangle  Region darstellen.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Initialisiert eine neue Instanz der  Quadrangle  Struktur mit den beschreibenden Punkten. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EMPTY](#EMPTY) | Stellt eine  Quadrangle  Klasse dar, deren Eigenschaften nicht initialisiert sind. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Bestimmt, ob der angegebene  Point  innerhalb dieser  Quadrangle  Klasse liegt. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Bestimmt, ob das angegebene  Rectangle  in dieser  Quadrangle  Klasse enthalten ist oder sie schneidet. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Bestimmt, ob das angegebene  Quadrangle  in dieser  Quadrangle  Klasse enthalten ist oder sie schneidet. |
| [contains(int x, int y)](#contains-int-int-) | Bestimmt, ob der angegebene Punkt innerhalb dieser  Quadrangle  Klasse liegt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen  Quadrangle  Wert ist. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Erstellt ein  Rectangle  das diese  Quadrangle  begrenzt |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Ermittelt den linken unteren Eckpunkt  Point  des  Quadrangle  Bereichs |
| [getLeftTop()](#getLeftTop--) | Ermittelt die linke obere Ecke des Point der Quadrangle-Region |
| [getRightBottom()](#getRightBottom--) | Ermittelt die rechte untere Ecke des Point der Quadrangle-Region |
| [getRightTop()](#getRightTop--) | Ermittelt die rechte obere Ecke des Point der Quadrangle-Region |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isEmpty--) | Prüft, ob alle Point dieses Quadrangle den Wert Null haben. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Ermittelt den linken unteren Eckpunkt  Point  des  Quadrangle  Bereichs |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Ermittelt die linke obere Ecke des Point der Quadrangle-Region |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Ermittelt die rechte untere Ecke des Point der Quadrangle-Region |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Ermittelt die rechte obere Ecke des Point der Quadrangle-Region |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Quadrangle zurück. |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| leftTop | android.graphics.Point | Ein Point, der die linke obere Ecke des Quadrangle darstellt. |
| rightTop | android.graphics.Point | Ein Point, der die rechte obere Ecke des Quadrangle darstellt. |
| rightBottom | android.graphics.Point | Ein Point, der die rechte untere Ecke des Quadrangle darstellt. |
| leftBottom | android.graphics.Point | Ein Point, der die linke untere Ecke des Quadrangle darstellt. |

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


Bestimmt, ob der angegebene  Point  innerhalb dieser  Quadrangle  Klasse liegt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pt | android.graphics.Point | Der Point zum Testen. |

**Returns:**
boolean – Gibt **true** zurück, wenn Point innerhalb dieser Quadrangle‑Klasse enthalten ist; andernfalls **false**.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Bestimmt, ob das angegebene  Rectangle  in dieser  Quadrangle  Klasse enthalten ist oder sie schneidet.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| rect | android.graphics.Rect | Das Rectangle zum Testen. |

**Returns:**
boolean – Gibt **true** zurück, wenn Rectangle in dieser Quadrangle‑Klasse enthalten oder schneidet; andernfalls **false**.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Bestimmt, ob das angegebene  Quadrangle  in dieser  Quadrangle  Klasse enthalten ist oder sie schneidet.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Das Quadrangle zum Testen. |

**Returns:**
boolean – Gibt **true** zurück, wenn Quadrangle in dieser Quadrangle‑Klasse enthalten oder schneidet; andernfalls **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser  Quadrangle  Klasse liegt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Punktkoordinate. |
| y | int | Die y-Punkt-Koordinate. |

**Returns:**
boolean - Gibt **true** zurück, wenn der Punkt innerhalb dieser Quadrangle-Klasse enthalten ist; andernfalls **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen  Quadrangle  Wert ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein Quadrangle-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Erstellt ein  Rectangle  das diese  Quadrangle  begrenzt

**Returns:**
android.graphics.Rect - gibt das Rectangle zurück, das dieses Quadrangle umschließt.
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


Ermittelt den linken unteren Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein Punkt der linken unteren Ecke der Quadrangle-Region.

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Ermittelt die linke obere Ecke des Point der Quadrangle-Region

Wert: Ein Punkt der linken oberen Ecke der Quadrangle-Region.

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Ermittelt die rechte untere Ecke des Point der Quadrangle-Region

Wert: Ein Punkt der rechten unteren Ecke der Quadrangle-Region.

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Ermittelt die rechte obere Ecke des Point der Quadrangle-Region

Wert: Ein Punkt der rechten oberen Ecke der Quadrangle-Region.

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Prüft, ob alle Point dieses Quadrangle den Wert Null haben.

Wert: Gibt **true** zurück, wenn alle Punkte dieses Quadrangle den Wert Null haben; andernfalls **false**.

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


Ermittelt den linken unteren Eckpunkt  Point  des  Quadrangle  Bereichs

Wert: Ein Punkt der linken unteren Ecke der Quadrangle-Region.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Ermittelt die linke obere Ecke des Point der Quadrangle-Region

Wert: Ein Punkt der linken oberen Ecke der Quadrangle-Region.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Ermittelt die rechte untere Ecke des Point der Quadrangle-Region

Wert: Ein Punkt der rechten unteren Ecke der Quadrangle-Region.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Ermittelt die rechte obere Ecke des Point der Quadrangle-Region

Wert: Ein Punkt der rechten oberen Ecke der Quadrangle-Region.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Quadrangle zurück.

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

