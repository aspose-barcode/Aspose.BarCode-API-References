---
title: "Quadrangle"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Slaat een set van vier Punten op die een Quadrangle‑gebied vertegenwoordigen."
type: docs
weight: 39
url: /nl/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Slaat een set van vier Point s op die een Quadrangle-regio vertegenwoordigen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Initialiseert een nieuw exemplaar van de  Quadrangle  klasse met de beschrijvende punten. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [EMPTY](#EMPTY) | Stelt een  Quadrangle  klasse voor met zijn eigenschappen niet geïnitialiseerd. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Bepaalt of de opgegeven  Quadrangle  zich bevindt binnen of snijdt deze  Quadrangle  klasse. |
| [contains(int x, int y)](#contains-int-int-) | Bepaalt of het opgegeven punt zich bevindt binnen deze  Quadrangle  klasse. |
| [contains(Point pt)](#contains-java.awt.Point-) | Bepaalt of het opgegeven  Point  zich bevindt binnen deze  Quadrangle  klasse. |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Bepaalt of de opgegeven  Rectangle  zich bevindt binnen of snijdt deze  Quadrangle  klasse. |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven  Quadrangle  waarde. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Maakt een  Rectangle  die deze  Quadrangle  omsluit |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Haalt de linksonderhoek  Point  van het  Quadrangle  gebied op |
| [getLeftTop()](#getLeftTop--) | Haalt de linkerbovenhoek  Point  van het  Quadrangle  gebied op |
| [getRightBottom()](#getRightBottom--) | Haalt de rechteronderhoek  Point  van het  Quadrangle  gebied op |
| [getRightTop()](#getRightTop--) | Haalt de rechterbovenhoek  Point  van het  Quadrangle  gebied op |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isEmpty--) | Test of alle  Point s van deze  Quadrangle  een waarde van nul hebben. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Haalt de linksonderhoek  Point  van het  Quadrangle  gebied op |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Haalt de linkerbovenhoek  Point  van het  Quadrangle  gebied op |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Haalt de rechteronderhoek  Point  van het  Quadrangle  gebied op |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Haalt de rechterbovenhoek  Point  van het  Quadrangle  gebied op |
| [toString()](#toString--) | Retourneert een menselijk leesbare stringrepresentatie van deze  Quadrangle . |
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


Initialiseert een nieuw exemplaar van de  Quadrangle  klasse met de beschrijvende punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| leftTop | java.awt.Point | Een  Point  die de linkerbovenhoek van de Quadrangle vertegenwoordigt. |
| rightTop | java.awt.Point | Een  Point  die de rechterbovenhoek van de Quadrangle vertegenwoordigt. |
| rightBottom | java.awt.Point | Een  Point  die de rechteronderhoek van de Quadrangle vertegenwoordigt. |
| leftBottom | java.awt.Point | Een  Point  die de linkeronderhoek van de Quadrangle vertegenwoordigt. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Stelt een  Quadrangle  klasse voor met zijn eigenschappen niet geïnitialiseerd.

Waarde:  Quadrangle

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


Bepaalt of de opgegeven  Quadrangle  zich bevindt binnen of snijdt deze  Quadrangle  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | De  Quadrangle  om te testen. |

**Returns:**
boolean - Retourneert  **true**  als  Quadrangle  is opgenomen of intersecteert deze  Quadrangle  klasse; anders,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bepaalt of het opgegeven punt zich bevindt binnen deze  Quadrangle  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | Het x-punt coördinaat. |
| y | int | Het y-punt coördinaat. |

**Returns:**
boolean - Retourneert  **true**  als punt is opgenomen binnen deze  Quadrangle  klasse; anders,  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Bepaalt of het opgegeven  Point  zich bevindt binnen deze  Quadrangle  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | java.awt.Point | De  Point  om te testen. |

**Returns:**
boolean - Retourneert  **true**  als  Point  is opgenomen binnen deze  Quadrangle  klasse; anders,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Bepaalt of de opgegeven  Rectangle  zich bevindt binnen of snijdt deze  Quadrangle  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | java.awt.Rectangle | De  Rectangle  om te testen. |

**Returns:**
boolean - Retourneert  **true**  als  Rectangle  is opgenomen of intersecteert deze  Quadrangle  klasse; anders,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven  Quadrangle  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een  Quadrangle  waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Maakt een  Rectangle  die deze  Quadrangle  omsluit

**Returns:**
java.awt.Rectangle - retourneert een Rectangle die dit Quadrangle begrenst
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


Haalt de linksonderhoek  Point  van het  Quadrangle  gebied op

Waarde: Een linksonderhoek Point van Quadrangle regio

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Haalt de linkerbovenhoek  Point  van het  Quadrangle  gebied op

Waarde: Een linkerbovenhoek Point van Quadrangle regio

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Haalt de rechteronderhoek  Point  van het  Quadrangle  gebied op

Waarde: Een rechteronderhoek Point van Quadrangle regio

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Haalt de rechterbovenhoek  Point  van het  Quadrangle  gebied op

Waarde: Een rechterbovenhoek Point van Quadrangle regio

**Returns:**
java.awt.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Test of alle  Point s van deze  Quadrangle  een waarde van nul hebben.

Waarde: Retourneert **true** als alle Point(s) van dit Quadrangle waarden van nul hebben; anders **false**.

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


Haalt de linksonderhoek  Point  van het  Quadrangle  gebied op

Waarde: Een linksonderhoek Point van Quadrangle regio

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Haalt de linkerbovenhoek  Point  van het  Quadrangle  gebied op

Waarde: Een linkerbovenhoek Point van Quadrangle regio

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Haalt de rechteronderhoek  Point  van het  Quadrangle  gebied op

Waarde: Een rechteronderhoek Point van Quadrangle regio

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Haalt de rechterbovenhoek  Point  van het  Quadrangle  gebied op

Waarde: Een rechterbovenhoek Point van Quadrangle regio

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare stringrepresentatie van deze  Quadrangle .

**Returns:**
java.lang.String - Een string die dit Quadrangle vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

