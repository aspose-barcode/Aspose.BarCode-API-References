---
title: "Quadrangle"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Memorizza un insieme di quattro Points che rappresentano una regione Quadrangle."
type: docs
weight: 39
url: /it/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Memorizza un insieme di quattro  Point s che rappresentano una regione  Quadrangle.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Inizializza una nuova istanza della classe  Quadrangle  con i punti descrittivi. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EMPTY](#EMPTY) | Rappresenta una classe  Quadrangle  con le sue proprietà lasciate non inizializzate. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Determina se il  Quadrangle  specificato è contenuto o interseca questa classe  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Determina se il punto specificato è contenuto all'interno di questa classe  Quadrangle . |
| [contains(Point pt)](#contains-java.awt.Point-) | Determina se il  Point  specificato è contenuto all'interno di questa classe  Quadrangle . |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Determina se il  Rectangle  specificato è contenuto o interseca questa classe  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore  Quadrangle  specificato. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Crea un  Rectangle  che delimita questo  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Ottiene il punto  Point  dell'angolo in basso a sinistra della regione  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Ottiene il punto  Point  dell'angolo in alto a sinistra della regione  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Ottiene il punto  Point  dell'angolo in basso a destra della regione  Quadrangle |
| [getRightTop()](#getRightTop--) | Ottiene il punto  Point  dell'angolo in alto a destra della regione  Quadrangle |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isEmpty--) | Verifica se tutti i  Point  di questo  Quadrangle  hanno valori zero. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Ottiene il punto  Point  dell'angolo in basso a sinistra della regione  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Ottiene il punto  Point  dell'angolo in alto a sinistra della regione  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Ottiene il punto  Point  dell'angolo in basso a destra della regione  Quadrangle |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Ottiene il punto  Point  dell'angolo in alto a destra della regione  Quadrangle |
| [toString()](#toString--) | Restituisce una rappresentazione della stringa leggibile dall'uomo di questo  Quadrangle . |
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


Inizializza una nuova istanza della classe  Quadrangle  con i punti descrittivi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftTop | java.awt.Point | Un  Point  che rappresenta l'angolo sinistro-superiore del Quadrangle. |
| rightTop | java.awt.Point | Un  Point  che rappresenta l'angolo destro-superiore del Quadrangle. |
| rightBottom | java.awt.Point | Un  Point  che rappresenta l'angolo destro-inferiore del Quadrangle. |
| leftBottom | java.awt.Point | Un  Point  che rappresenta l'angolo sinistro-inferiore del Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Rappresenta una classe  Quadrangle  con le sue proprietà lasciate non inizializzate.

Valore:  Quadrangle

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


Determina se il  Quadrangle  specificato è contenuto o interseca questa classe  Quadrangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Il  Quadrangle  da testare. |

**Returns:**
boolean - Restituisce  **true**  se  Quadrangle  è contenuto o interseca questa  Quadrangle  class; altrimenti,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina se il punto specificato è contenuto all'interno di questa classe  Quadrangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | Il punto x coordinate. |
| y | int | Il punto y coordinate. |

**Returns:**
boolean - Restituisce  **true**  se il punto è contenuto all'interno di questa  Quadrangle  class; altrimenti,  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Determina se il  Point  specificato è contenuto all'interno di questa classe  Quadrangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | java.awt.Point | Il  Point  da testare. |

**Returns:**
boolean - Restituisce  **true**  se  Point  è contenuto all'interno di questa  Quadrangle  class; altrimenti,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determina se il  Rectangle  specificato è contenuto o interseca questa classe  Quadrangle .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | java.awt.Rectangle | Il  Rectangle  da testare. |

**Returns:**
boolean - Restituisce  **true**  se  Rectangle  è contenuto o interseca questa  Quadrangle  class; altrimenti,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore  Quadrangle  specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un  Quadrangle  valore da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Crea un  Rectangle  che delimita questo  Quadrangle

**Returns:**
java.awt.Rectangle - restituisce il Rectangle che delimita questo Quadrangle
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


Ottiene il punto  Point  dell'angolo in basso a sinistra della regione  Quadrangle

Valore: un Point dell'angolo in basso a sinistra della regione Quadrangle

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Ottiene il punto  Point  dell'angolo in alto a sinistra della regione  Quadrangle

Valore: un Point dell'angolo in alto a sinistra della regione Quadrangle

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Ottiene il punto  Point  dell'angolo in basso a destra della regione  Quadrangle

Valore: un Point dell'angolo in basso a destra della regione Quadrangle

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Ottiene il punto  Point  dell'angolo in alto a destra della regione  Quadrangle

Valore: un Point dell'angolo in alto a destra della regione Quadrangle

**Returns:**
java.awt.Point
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

Valore: restituisce **true** se tutti i Point di questo Quadrangle hanno valore zero; altrimenti, **false**.

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


Ottiene il punto  Point  dell'angolo in basso a sinistra della regione  Quadrangle

Valore: un Point dell'angolo in basso a sinistra della regione Quadrangle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Ottiene il punto  Point  dell'angolo in alto a sinistra della regione  Quadrangle

Valore: un Point dell'angolo in alto a sinistra della regione Quadrangle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Ottiene il punto  Point  dell'angolo in basso a destra della regione  Quadrangle

Valore: un Point dell'angolo in basso a destra della regione Quadrangle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Ottiene il punto  Point  dell'angolo in alto a destra della regione  Quadrangle

Valore: un Point dell'angolo in alto a destra della regione Quadrangle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione della stringa leggibile dall'uomo di questo  Quadrangle .

**Returns:**
java.lang.String - Una stringa che rappresenta questo Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

