---
title: "Quadrangle"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Stocke un ensemble de quatre Points qui représentent une région Quadrangle."
type: docs
weight: 39
url: /fr/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Stocke un ensemble de quatre Points qui représentent une région Quadrangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Initialise une nouvelle instance de la classe  Quadrangle  avec les points descriptifs. |
## Champs

| Champ | Description |
| --- | --- |
| [EMPTY](#EMPTY) | Représente une classe  Quadrangle  dont les propriétés sont laissées non initialisées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Détermine si le  Quadrangle  spécifié est contenu ou intersecte cette classe  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Détermine si le point spécifié est contenu dans cette classe  Quadrangle . |
| [contains(Point pt)](#contains-java.awt.Point-) | Détermine si le  Point  spécifié est contenu dans cette classe  Quadrangle . |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Détermine si le  Rectangle  spécifié est contenu ou intersecte cette classe  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur  Quadrangle  spécifiée. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Crée un  Rectangle  englobant ce  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Obtient le coin inférieur gauche  Point  de la région  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Obtient le coin supérieur gauche  Point  de la région  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Obtient le coin inférieur droit  Point  de la région  Quadrangle |
| [getRightTop()](#getRightTop--) | Obtient le coin supérieur droit  Point  de la région  Quadrangle |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isEmpty--) | Teste si tous les  Point s de ce  Quadrangle  ont des valeurs zéro. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Obtient le coin inférieur gauche  Point  de la région  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Obtient le coin supérieur gauche  Point  de la région  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Obtient le coin inférieur droit  Point  de la région  Quadrangle |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Obtient le coin supérieur droit  Point  de la région  Quadrangle |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce  Quadrangle . |
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


Initialise une nouvelle instance de la classe  Quadrangle  avec les points descriptifs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftTop | java.awt.Point | Un  Point  qui représente le coin supérieur gauche du Quadrangle. |
| rightTop | java.awt.Point | Un  Point  qui représente le coin supérieur droit du Quadrangle. |
| rightBottom | java.awt.Point | Un  Point  qui représente le coin inférieur droit du Quadrangle. |
| leftBottom | java.awt.Point | Un  Point  qui représente le coin inférieur gauche du Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Représente une classe  Quadrangle  dont les propriétés sont laissées non initialisées.

Valeur:  Quadrangle

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


Détermine si le  Quadrangle  spécifié est contenu ou intersecte cette classe  Quadrangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Le  Quadrangle  à tester. |

**Returns:**
boolean - Renvoie  **true**  si le  Quadrangle  est contenu ou intersecte cette classe  Quadrangle ; sinon,  **false** .
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
boolean - Renvoie  **true**  si le point est contenu dans cette classe  Quadrangle ; sinon,  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Détermine si le  Point  spécifié est contenu dans cette classe  Quadrangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | java.awt.Point | Le  Point  à tester. |

**Returns:**
boolean - Renvoie  **true**  si le  Point  est contenu dans cette classe  Quadrangle ; sinon,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Détermine si le  Rectangle  spécifié est contenu ou intersecte cette classe  Quadrangle .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | java.awt.Rectangle | Le  Rectangle  à tester. |

**Returns:**
boolean - Renvoie  **true**  si le  Rectangle  est contenu ou intersecte cette classe  Quadrangle ; sinon,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur  Quadrangle  spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une  Quadrangle  valeur à comparer à cette instance. |

**Returns:**
booléen -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Crée un  Rectangle  englobant ce  Quadrangle

**Returns:**
java.awt.Rectangle - renvoie le Rectangle englobant ce Quadrangle
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


Obtient le coin inférieur gauche  Point  de la région  Quadrangle

Valeur : Un point du coin inférieur gauche de la région du Quadrangle

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Obtient le coin supérieur gauche  Point  de la région  Quadrangle

Valeur : Un point du coin supérieur gauche de la région du Quadrangle

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Obtient le coin inférieur droit  Point  de la région  Quadrangle

Valeur : Un point du coin inférieur droit de la région du Quadrangle

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Obtient le coin supérieur droit  Point  de la région  Quadrangle

Valeur : Un point du coin supérieur droit de la région du Quadrangle

**Returns:**
java.awt.Point
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


Teste si tous les  Point s de ce  Quadrangle  ont des valeurs zéro.

Valeur : Renvoie **true** si tous les Points de ce Quadrangle ont des valeurs zéro ; sinon, **false**.

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


Obtient le coin inférieur gauche  Point  de la région  Quadrangle

Valeur : Un point du coin inférieur gauche de la région du Quadrangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Obtient le coin supérieur gauche  Point  de la région  Quadrangle

Valeur : Un point du coin supérieur gauche de la région du Quadrangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Obtient le coin inférieur droit  Point  de la région  Quadrangle

Valeur : Un point du coin inférieur droit de la région du Quadrangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Obtient le coin supérieur droit  Point  de la région  Quadrangle

Valeur : Un point du coin supérieur droit de la région du Quadrangle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce  Quadrangle .

**Returns:**
java.lang.String - Une chaîne qui représente ce Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

