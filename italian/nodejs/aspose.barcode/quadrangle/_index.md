---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza un insieme di quattro punti che rappresentano una regione quadrilatero."
type: docs
weight: 850
url: /it/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Memorizza un insieme di quattro punti che rappresentano una regione quadrilatero.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Inizializza una nuova istanza della struttura Quadrangle con i punti descrittivi.

| Parametro | Descrizione |
| --- | --- |
| leftTop | Un Point che rappresenta l'angolo sinistro-superiore del Quadrangle. |
| rightTop | Un Point che rappresenta l'angolo destro-superiore del Quadrangle. |
| rightBottom | Un Point che rappresenta l'angolo destro-inferiore del Quadrangle. |
| leftBottom | Un Point che rappresenta l'angolo sinistro-inferiore del Quadrangle. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [contains(pt)](#contains) | Determina se il Point specificato è contenuto all'interno di questa struttura Quadrangle. |
| [containsPoint(x, y)](#containspoint) | Determina se il punto specificato è contenuto all'interno di questa struttura Quadrangle. |
| [containsQuadrangle(quad)](#containsquadrangle) | Determina se il Quadrangle specificato è contenuto o interseca questa struttura Quadrangle. |
| [containsRectangle(rect)](#containsrectangle) | Determina se il Rectangle specificato è contenuto o interseca questa struttura Quadrangle. |
| [equals(other)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore Quadrangle specificato. |
| [getBoundingRectangle()](#getboundingrectangle) | Crea un Rectangle che delimita questo Quadrangle |
| [getLeftBottom()](#getleftbottom) | Ottiene il Point dell'angolo sinistro-inferiore della regione QuadrangleValue: Un Point dell'angolo sinistro-inferiore della regione Quadrangle. |
| [getLeftTop()](#getlefttop) | Ottiene il Point dell'angolo sinistro-superiore della regione QuadrangleValue: Un Point dell'angolo sinistro-superiore della regione Quadrangle. |
| [getRightBottom()](#getrightbottom) | Ottiene il Point dell'angolo destro-inferiore della regione QuadrangleValue: Un Point dell'angolo destro-inferiore della regione Quadrangle. |
| [getRightTop()](#getrighttop) | Ottiene il Point dell'angolo destro-superiore della regione QuadrangleValue: Un Point dell'angolo destro-superiore della regione Quadrangle. |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isempty) | Verifica se tutti i punti di questo Quadrangle hanno valori zero. Valore: restituisce true se tutti i punti di questo Quadrangle hanno |
| [setLeftBottom()](#setleftbottom) | Imposta il punto dell'angolo in basso a sinistra della regione Quadrangle. Valore: un punto dell'angolo in basso a sinistra della regione Quadrangle |
| [setLeftTop()](#setlefttop) | Imposta il punto dell'angolo in alto a sinistra della regione Quadrangle. Valore: un punto dell'angolo in alto a sinistra della regione Quadrangle |
| [setRightBottom()](#setrightbottom) | Imposta il punto dell'angolo in basso a destra della regione Quadrangle. Valore: un punto dell'angolo in basso a destra della regione Quadrangle |
| [setRightTop()](#setrighttop) | Imposta il punto dell'angolo in alto a destra della regione Quadrangle. Valore: un punto dell'angolo in alto a destra della regione Quadrangle |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo Quadrangle. |

### contains(pt) {#contains}

Determina se il Point specificato è contenuto all'interno di questa struttura Quadrangle.

| Parametro | Descrizione |
| --- | --- |
| pt | Il punto da testare. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Determina se il punto specificato è contenuto all'interno di questa struttura Quadrangle.

| Parametro | Descrizione |
| --- | --- |
| x | La coordinata x del punto. |
| y | La coordinata y del punto. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Determina se il Quadrangle specificato è contenuto o interseca questa struttura Quadrangle.

| Parametro | Descrizione |
| --- | --- |
| quad | Il Quadrangle da testare. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Determina se il Rectangle specificato è contenuto o interseca questa struttura Quadrangle.

| Parametro | Descrizione |
| --- | --- |
| rect | Il Rectangle da testare. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore Quadrangle specificato.

| Parametro | Descrizione |
| --- | --- |
| altro | Un valore Quadrangle da confrontare con questa istanza. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Crea un Rectangle che delimita questo Quadrangle

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Ottiene il Point dell'angolo sinistro-inferiore della regione QuadrangleValue: Un Point dell'angolo sinistro-inferiore della regione Quadrangle.

### getLeftTop() {#getlefttop}

Ottiene il Point dell'angolo sinistro-superiore della regione QuadrangleValue: Un Point dell'angolo sinistro-superiore della regione Quadrangle.

### getRightBottom() {#getrightbottom}

Ottiene il Point dell'angolo destro-inferiore della regione QuadrangleValue: Un Point dell'angolo destro-inferiore della regione Quadrangle.

### getRightTop() {#getrighttop}

Ottiene il Point dell'angolo destro-superiore della regione QuadrangleValue: Un Point dell'angolo destro-superiore della regione Quadrangle.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Verifica se tutti i punti di questo Quadrangle hanno valori zero. Valore: restituisce true se tutti i punti di questo Quadrangle hanno valori zero; altrimenti, false.

### setLeftBottom() {#setleftbottom}

Imposta il punto dell'angolo in basso a sinistra della regione Quadrangle. Valore: un punto dell'angolo in basso a sinistra della regione Quadrangle

### setLeftTop() {#setlefttop}

Imposta il punto dell'angolo in alto a sinistra della regione Quadrangle. Valore: un punto dell'angolo in alto a sinistra della regione Quadrangle

### setRightBottom() {#setrightbottom}

Imposta il punto dell'angolo in basso a destra della regione Quadrangle. Valore: un punto dell'angolo in basso a destra della regione Quadrangle

### setRightTop() {#setrighttop}

Imposta il punto dell'angolo in alto a destra della regione Quadrangle. Valore: un punto dell'angolo in alto a destra della regione Quadrangle

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo Quadrangle.

**Returns:** A string that represents this Quadrangle.
