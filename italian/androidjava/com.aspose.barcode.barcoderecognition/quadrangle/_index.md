---
title: Quadrangle
second_title: Aspose.BarCode per Android via Java API Reference
description: Memorizza un insieme di quattro Points che rappresentano una regione Quadrangle.
type: docs
weight: 43
url: /it/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Memorizza un insieme di quattro Point che rappresentano una regione Quadrangle.
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Inizializza una nuova istanza della struttura  Quadrangle  con i punti descrittivi. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EMPTY](#EMPTY) | Rappresenta una classe  Quadrangle  con le sue proprietà non inizializzate. |
## Methods

| Method | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Determina se il  Point  specificato è contenuto all'interno di questa classe  Quadrangle . |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Determina se il  Rectangle  specificato è contenuto o interseca questa classe  Quadrangle . |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Determina se il  Quadrangle  specificato è contenuto o interseca questa classe  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Determina se il punto specificato è contenuto all'interno di questa classe  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore  Quadrangle  specificato. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Crea un  Rectangle  che delimita questo  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Ottiene il punto  Point  dell'angolo inferiore sinistro della regione  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Ottiene l'angolo in alto a sinistra Point della regione Quadrangle |
| [getRightBottom()](#getRightBottom--) | Ottiene l'angolo in basso a destra Point della regione Quadrangle |
| [getRightTop()](#getRightTop--) | Ottiene l'angolo in alto a destra Point della regione Quadrangle |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i Point di questo Quadrangle hanno valori zero. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Ottiene il punto  Point  dell'angolo inferiore sinistro della regione  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Ottiene l'angolo in alto a sinistra Point della regione Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Ottiene l'angolo in basso a destra Point della regione Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Ottiene l'angolo in alto a destra Point della regione Quadrangle |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile da un umano di questo Quadrangle. |
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


Inizializza una nuova istanza della struttura  Quadrangle  con i punti descrittivi.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| leftTop | android.graphics.Point | Un Point che rappresenta l'angolo in alto a sinistra del Quadrangle. |
| rightTop | android.graphics.Point | Un Point che rappresenta l'angolo in alto a destra del Quadrangle. |
| rightBottom | android.graphics.Point | Un Point che rappresenta l'angolo in basso a destra del Quadrangle. |
| leftBottom | android.graphics.Point | Un Point che rappresenta l'angolo in basso a sinistra del Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Rappresenta una classe  Quadrangle  con le sue proprietà non inizializzate.

Valore: Quadrangle

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


Determina se il  Point  specificato è contenuto all'interno di questa classe  Quadrangle .

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| pt | android.graphics.Point | Il Point da testare. |

**Returns:**
boolean - Restituisce **true** se il Point è contenuto all'interno di questa classe Quadrangle; altrimenti, **false**.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Determina se il  Rectangle  specificato è contenuto o interseca questa classe  Quadrangle .

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| rect | android.graphics.Rect | Il Rectangle da testare. |

**Returns:**
boolean - Restituisce **true** se il Rectangle è contenuto o interseca questa classe Quadrangle; altrimenti, **false**.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Determina se il  Quadrangle  specificato è contenuto o interseca questa classe  Quadrangle .

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Il Quadrangle da testare. |

**Returns:**
boolean - Restituisce **true** se il Quadrangle è contenuto o interseca questa classe Quadrangle; altrimenti, **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina se il punto specificato è contenuto all'interno di questa classe  Quadrangle .

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto. |
| y | int | La coordinata y del punto. |

**Returns:**
boolean - Restituisce **true** se il punto è contenuto all'interno di questa classe Quadrangle; altrimenti, **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore  Quadrangle  specificato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore Quadrangle da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Crea un  Rectangle  che delimita questo  Quadrangle

**Returns:**
android.graphics.Rect - restituisce Rectangle che delimita questo Quadrangle
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


Ottiene il punto  Point  dell'angolo inferiore sinistro della regione  Quadrangle

Valore: Un punto Point dell'angolo sinistro-inferiore della regione Quadrangle

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Ottiene l'angolo in alto a sinistra Point della regione Quadrangle

Valore: Un punto Point dell'angolo sinistro-superiore della regione Quadrangle

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Ottiene l'angolo in basso a destra Point della regione Quadrangle

Valore: Un punto Point dell'angolo destro-inferiore della regione Quadrangle

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Ottiene l'angolo in alto a destra Point della regione Quadrangle

Valore: Un punto Point dell'angolo destro-superiore della regione Quadrangle

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Verifica se tutti i Point di questo Quadrangle hanno valori zero.

Valore: Restituisce **true** se tutti i Point di questo Quadrangle hanno valore zero; altrimenti, **false**.

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


Ottiene il punto  Point  dell'angolo inferiore sinistro della regione  Quadrangle

Valore: Un punto Point dell'angolo sinistro-inferiore della regione Quadrangle

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Ottiene l'angolo in alto a sinistra Point della regione Quadrangle

Valore: Un punto Point dell'angolo sinistro-superiore della regione Quadrangle

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Ottiene l'angolo in basso a destra Point della regione Quadrangle

Valore: Un punto Point dell'angolo destro-inferiore della regione Quadrangle

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Ottiene l'angolo in alto a destra Point della regione Quadrangle

Valore: Un punto Point dell'angolo destro-superiore della regione Quadrangle

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile da un umano di questo Quadrangle.

**Returns:**
java.lang.String - Una stringa che rappresenta questo Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

