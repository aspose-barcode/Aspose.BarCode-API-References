---
title: "Quadrangle"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Memorizza un insieme di quattro Point che rappresentano una regione Quadrangle."
type: docs
weight: 41
url: /it/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Memorizza un insieme di quattro Point che rappresentano una regione Quadrangle.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Inizializza una nuova istanza della struttura  Quadrangle  con i punti descrittivi. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EMPTY](#EMPTY) | Rappresenta una classe  Quadrangle  con le sue proprietà non inizializzate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Determina se il  Point  specificato è contenuto all'interno di questa classe  Quadrangle . |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Determina se il  Rectangle  specificato è contenuto o interseca questa classe  Quadrangle . |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Determina se il  Quadrangle  specificato è contenuto o interseca questa classe  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Determina se il punto specificato è contenuto all'interno di questa classe  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore  Quadrangle  specificato. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Crea un  Rectangle  che delimita questo  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Ottiene il  Point  dell'angolo sinistro-inferiore della regione  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Ottiene il  Point  dell'angolo sinistro-superiore della regione  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Ottiene il  Point  dell'angolo destro-inferiore della regione  Quadrangle |
| [getRightTop()](#getRightTop--) | Ottiene il  Point  dell'angolo destro-superiore della regione  Quadrangle |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i  Point  di questo  Quadrangle  hanno valori zero. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Ottiene il  Point  dell'angolo sinistro-inferiore della regione  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Ottiene il  Point  dell'angolo sinistro-superiore della regione  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Ottiene il  Point  dell'angolo destro-inferiore della regione  Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Ottiene il  Point  dell'angolo destro-superiore della regione  Quadrangle |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo  Quadrangle . |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftTop | android.graphics.Point | Un  Point  che rappresenta l'angolo sinistro-superiore del Quadrangle. |
| rightTop | android.graphics.Point | Un  Point  che rappresenta l'angolo destro-superiore del Quadrangle. |
| rightBottom | android.graphics.Point | Un  Point  che rappresenta l'angolo destro-inferiore del Quadrangle. |
| leftBottom | android.graphics.Point | Un  Point  che rappresenta l'angolo sinistro-inferiore del Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Rappresenta una classe  Quadrangle  con le sue proprietà non inizializzate.

Valore:  Quadrangle

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | android.graphics.Point | Il  Point  da testare. |

**Returns:**
boolean - Restituisce  **true**  se  Point  è contenuto all'interno di questa classe  Quadrangle; altrimenti,  **false** .
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Determina se il  Rectangle  specificato è contenuto o interseca questa classe  Quadrangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | android.graphics.Rect | Il  Rectangle  da testare. |

**Returns:**
boolean - Restituisce  **true**  se  Rectangle  è contenuto o interseca questa classe  Quadrangle; altrimenti,  **false** .
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Determina se il  Quadrangle  specificato è contenuto o interseca questa classe  Quadrangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Il  Quadrangle  da testare. |

**Returns:**
boolean - Restituisce  **true**  se  Quadrangle  è contenuto o interseca questa classe  Quadrangle; altrimenti,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina se il punto specificato è contenuto all'interno di questa classe  Quadrangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto. |
| y | int | La coordinata y del punto. |

**Returns:**
boolean - Restituisce  **true**  se il punto è contenuto all'interno di questa classe  Quadrangle; altrimenti,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore  Quadrangle  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore  Quadrangle  da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Crea un  Rectangle  che delimita questo  Quadrangle

**Returns:**
android.graphics.Rect - restituisce  Rectangle  che delimita questo  Quadrangle
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


Ottiene il  Point  dell'angolo sinistro-inferiore della regione  Quadrangle

Valore: Un  Point  dell'angolo sinistro-inferiore della regione Quadrangle

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Ottiene il  Point  dell'angolo sinistro-superiore della regione  Quadrangle

Valore: Un  Point  dell'angolo sinistro-superiore della regione Quadrangle

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Ottiene il  Point  dell'angolo destro-inferiore della regione  Quadrangle

Valore: Un  Point  dell'angolo destro-inferiore della regione Quadrangle

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Ottiene il  Point  dell'angolo destro-superiore della regione  Quadrangle

Valore: Un punto dell'angolo in alto a destra della regione del Quadrilatero

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


Verifica se tutti i  Point  di questo  Quadrangle  hanno valori zero.

Valore: Restituisce **true** se tutti i punti di questo Quadrilatero hanno valore zero; altrimenti, **false**.

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


Ottiene il  Point  dell'angolo sinistro-inferiore della regione  Quadrangle

Valore: Un  Point  dell'angolo sinistro-inferiore della regione Quadrangle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Ottiene il  Point  dell'angolo sinistro-superiore della regione  Quadrangle

Valore: Un  Point  dell'angolo sinistro-superiore della regione Quadrangle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Ottiene il  Point  dell'angolo destro-inferiore della regione  Quadrangle

Valore: Un  Point  dell'angolo destro-inferiore della regione Quadrangle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Ottiene il  Point  dell'angolo destro-superiore della regione  Quadrangle

Valore: Un punto dell'angolo in alto a destra della regione del Quadrilatero

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo  Quadrangle .

**Returns:**
java.lang.String - Una stringa che rappresenta questo Quadrilatero.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

