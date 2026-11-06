---
title: "Quadrangle"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "Slaat een set van vier Points op die een Quadrangle-regio vertegenwoordigen."
type: docs
weight: 41
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Slaat een set van vier punten op die een vierhoekig gebied vertegenwoordigen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Initialiseert een nieuw exemplaar van de Quadrangle structuur met de beschrijvende punten. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [EMPTY](#EMPTY) | Stelt een Quadrangle klasse voor met zijn eigenschappen niet geïnitialiseerd. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Bepaalt of het opgegeven Point zich bevindt binnen deze Quadrangle klasse. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Bepaalt of het opgegeven Rectangle zich bevindt binnen of intersecteert met deze Quadrangle klasse. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Bepaalt of het opgegeven Quadrangle zich bevindt binnen of intersecteert met deze Quadrangle klasse. |
| [contains(int x, int y)](#contains-int-int-) | Bepaalt of het opgegeven punt zich bevindt binnen deze Quadrangle klasse. |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of dit exemplaar gelijk is aan een opgegeven Quadrangle waarde. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Maakt een Rectangle dat deze Quadrangle omsluit |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Haalt het linksonderhoek Point van de Quadrangle regio op |
| [getLeftTop()](#getLeftTop--) | Haalt het linkerbovenhoek Point van de Quadrangle regio op |
| [getRightBottom()](#getRightBottom--) | Haalt het rechteronderhoek Point van de Quadrangle regio op |
| [getRightTop()](#getRightTop--) | Haalt het rechterbovenhoek Point van de Quadrangle regio op |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isEmpty--) | Test of alle Point s van deze Quadrangle nulwaarden hebben. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Haalt het linksonderhoek Point van de Quadrangle regio op |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Haalt het linkerbovenhoek Point van de Quadrangle regio op |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Haalt het rechteronderhoek Point van de Quadrangle regio op |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Haalt het rechterbovenhoek Point van de Quadrangle regio op |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Quadrangle . |
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


Initialiseert een nieuw exemplaar van de Quadrangle structuur met de beschrijvende punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| leftTop | android.graphics.Point | Een Point dat de linkerbovenhoek van de Quadrangle vertegenwoordigt. |
| rightTop | android.graphics.Point | Een Point die de rechterbovenhoek van de Quadrangle vertegenwoordigt. |
| rightBottom | android.graphics.Point | Een Point die de rechteronderhoek van de Quadrangle vertegenwoordigt. |
| leftBottom | android.graphics.Point | Een Point die de linkeronderhoek van de Quadrangle vertegenwoordigt. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Stelt een Quadrangle klasse voor met zijn eigenschappen niet geïnitialiseerd.

Waarde:  Quadrangle

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


Bepaalt of het opgegeven Point zich bevindt binnen deze Quadrangle klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | android.graphics.Point | De Point om te testen. |

**Returns:**
boolean - Retourneert **true** als Point zich binnen deze Quadrangle klasse bevindt; anders **false** .
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Bepaalt of het opgegeven Rectangle zich bevindt binnen of intersecteert met deze Quadrangle klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | android.graphics.Rect | De Rectangle om te testen. |

**Returns:**
boolean - Retourneert **true** als Rectangle zich binnen of snijdt deze Quadrangle klasse; anders **false** .
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Bepaalt of het opgegeven Quadrangle zich bevindt binnen of intersecteert met deze Quadrangle klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | De Quadrangle om te testen. |

**Returns:**
boolean - Retourneert **true** als Quadrangle zich binnen of snijdt deze Quadrangle klasse; anders **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bepaalt of het opgegeven punt zich bevindt binnen deze Quadrangle klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-puntcoördinaat. |
| y | int | De y-puntcoördinaat. |

**Returns:**
boolean - Retourneert **true** als punt zich binnen deze Quadrangle klasse bevindt; anders **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of dit exemplaar gelijk is aan een opgegeven Quadrangle waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een Quadrangle waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Maakt een Rectangle dat deze Quadrangle omsluit

**Returns:**
android.graphics.Rect - retourneert Rectangle die deze Quadrangle omsluit
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


Haalt het linksonderhoek Point van de Quadrangle regio op

Waarde: Een linkeronderhoek Point van Quadrangle regio

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Haalt het linkerbovenhoek Point van de Quadrangle regio op

Waarde: Een linkerbovenhoek Point van Quadrangle regio

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Haalt het rechteronderhoek Point van de Quadrangle regio op

Waarde: Een rechteronderhoek Point van Quadrangle regio

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Haalt het rechterbovenhoek Point van de Quadrangle regio op

Waarde: Een rechterbovenhoek Punt van vierhoek regio

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bit ondertekend geheel getal hashcode.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Test of alle Point s van deze Quadrangle nulwaarden hebben.

Waarde: Retourneert **true** als alle Punten van deze Vierhoek nulwaarden hebben; anders **false**.

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


Haalt het linksonderhoek Point van de Quadrangle regio op

Waarde: Een linkeronderhoek Point van Quadrangle regio

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Haalt het linkerbovenhoek Point van de Quadrangle regio op

Waarde: Een linkerbovenhoek Point van Quadrangle regio

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Haalt het rechteronderhoek Point van de Quadrangle regio op

Waarde: Een rechteronderhoek Point van Quadrangle regio

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Haalt het rechterbovenhoek Point van de Quadrangle regio op

Waarde: Een rechterbovenhoek Punt van vierhoek regio

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Quadrangle .

**Returns:**
java.lang.String - Een string die deze Vierhoek vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

