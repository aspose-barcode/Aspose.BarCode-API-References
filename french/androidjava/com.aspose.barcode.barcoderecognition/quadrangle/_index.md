---
title: Quadrangle
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Stocke un ensemble de quatre Points qui représentent une région Quadrangle.
type: docs
weight: 43
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Stocke un ensemble de quatre Points qui représentent une région Quadrangle
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Initialise une nouvelle instance de la structure  Quadrangle  avec les points décrivant. |
## Champs

| Champ | Description |
| --- | --- |
| [EMPTY](#EMPTY) | Représente une classe  Quadrangle  avec ses propriétés laissées non initialisées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Détermine si le  Point  spécifié est contenu dans cette classe  Quadrangle . |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Détermine si le  Rectangle  spécifié est contenu ou intersecte cette classe  Quadrangle . |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Détermine si le  Quadrangle  spécifié est contenu ou intersecte cette classe  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Détermine si le point spécifié est contenu dans cette classe  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur  Quadrangle  spécifiée. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Crée un  Rectangle  englobant ce  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Obtient le point du coin inférieur gauche de la région  Quadrangle  |
| [getLeftTop()](#getLeftTop--) | Obtient le coin supérieur gauche du Point de la région Quadrangle |
| [getRightBottom()](#getRightBottom--) | Obtient le coin inférieur droit du Point de la région Quadrangle |
| [getRightTop()](#getRightTop--) | Obtient le coin supérieur droit du Point de la région Quadrangle |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isEmpty--) | Teste si tous les Points de ce Quadrangle ont des valeurs zéro. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Obtient le point du coin inférieur gauche de la région  Quadrangle  |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Obtient le coin supérieur gauche du Point de la région Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Obtient le coin inférieur droit du Point de la région Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Obtient le coin supérieur droit du Point de la région Quadrangle |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible de ce Quadrangle. |
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


Initialise une nouvelle instance de la structure  Quadrangle  avec les points décrivant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftTop | android.graphics.Point | Un Point qui représente le coin supérieur gauche du Quadrangle. |
| rightTop | android.graphics.Point | Un Point qui représente le coin supérieur droit du Quadrangle. |
| rightBottom | android.graphics.Point | Un Point qui représente le coin inférieur droit du Quadrangle. |
| leftBottom | android.graphics.Point | Un Point qui représente le coin inférieur gauche du Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Représente une classe  Quadrangle  avec ses propriétés laissées non initialisées.

Valeur : Quadrangle

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


Détermine si le  Point  spécifié est contenu dans cette classe  Quadrangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | android.graphics.Point | Le Point à tester. |

**Returns:**
boolean - Renvoie **true** si le Point est contenu dans cette classe Quadrangle ; sinon, **false**.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Détermine si le  Rectangle  spécifié est contenu ou intersecte cette classe  Quadrangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | android.graphics.Rect | Le Rectangle à tester. |

**Returns:**
boolean - Renvoie **true** si le Rectangle est contenu ou intersecte cette classe Quadrangle ; sinon, **false**.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Détermine si le  Quadrangle  spécifié est contenu ou intersecte cette classe  Quadrangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Le Quadrangle à tester. |

**Returns:**
boolean - Renvoie **true** si le Quadrangle est contenu ou intersecte cette classe Quadrangle ; sinon, **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Détermine si le point spécifié est contenu dans cette classe  Quadrangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | Le point x coordonnée. |
| y | int | Le point y coordonnée. |

**Returns:**
booléen - Retourne  **true**  si le point est contenu dans cette classe  Quadrangle ; sinon,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur  Quadrangle  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur  Quadrangle  à comparer à cette instance. |

**Returns:**
boolean -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Crée un  Rectangle  englobant ce  Quadrangle

**Returns:**
android.graphics.Rect - renvoie  Rectangle  englobant ce  Quadrangle
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


Obtient le point du coin inférieur gauche de la région  Quadrangle 

Valeur : Un coin inférieur gauche  Point  de la région  Quadrangle

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Obtient le coin supérieur gauche du Point de la région Quadrangle

Valeur : Un coin supérieur gauche  Point  de la région  Quadrangle

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Obtient le coin inférieur droit du Point de la région Quadrangle

Valeur : Un coin inférieur droit  Point  de la région  Quadrangle

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Obtient le coin supérieur droit du Point de la région Quadrangle

Valeur : Un coin supérieur droit  Point  de la région  Quadrangle

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Teste si tous les Points de ce Quadrangle ont des valeurs zéro.

Valeur : Retourne  **true**  si tous les  Point s de ce  Quadrangle  ont des valeurs zéro ; sinon,  **false** .

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


Obtient le point du coin inférieur gauche de la région  Quadrangle 

Valeur : Un coin inférieur gauche  Point  de la région  Quadrangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Obtient le coin supérieur gauche du Point de la région Quadrangle

Valeur : Un coin supérieur gauche  Point  de la région  Quadrangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Obtient le coin inférieur droit du Point de la région Quadrangle

Valeur : Un coin inférieur droit  Point  de la région  Quadrangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Obtient le coin supérieur droit du Point de la région Quadrangle

Valeur : Un coin supérieur droit  Point  de la région  Quadrangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible de ce Quadrangle.

**Returns:**
java.lang.String - Une chaîne qui représente ce  Quadrangle .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

