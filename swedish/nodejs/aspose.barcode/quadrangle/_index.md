---
title: "Fyrhörning"
linktitle: "Fyrhörning"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar en uppsättning av fyra punkter som representerar ett fyrhörningsområde."
type: docs
weight: 850
url: /sv/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Lagrar en uppsättning av fyra punkter som representerar ett fyrhörningsområde.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Initierar en ny instans av strukturen Quadrangle med de beskrivande punkterna.

| Parameter | Beskrivning |
| --- | --- |
| leftTop | En punkt som representerar det vänster-övre hörnet av Quadrangle. |
| rightTop | En punkt som representerar det högra-övre hörnet av Quadrangle. |
| rightBottom | En punkt som representerar det högra-nedre hörnet av Quadrangle. |
| leftBottom | En punkt som representerar det vänster-nedre hörnet av Quadrangle. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [contains(pt)](#contains) | Bestämmer om den angivna punkten finns inom denna Quadrangle-struktur. |
| [containsPoint(x, y)](#containspoint) | Bestämmer om den angivna punkten finns inom denna Quadrangle-struktur. |
| [containsQuadrangle(quad)](#containsquadrangle) | Bestämmer om den angivna Quadrangle är innehållen i eller skär denna Quadrangle-struktur. |
| [containsRectangle(rect)](#containsrectangle) | Bestämmer om den angivna rektangeln är innehållen i eller skär denna Quadrangle-struktur. |
| [equals(other)](#equals) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet Quadrangle-värde. |
| [getBoundingRectangle()](#getboundingrectangle) | Skapar en rektangel som avgränsar denna Quadrangle |
| [getLeftBottom()](#getleftbottom) | Hämtar vänster-nedre hörnpunkt för Quadrangle-regionVärde: En vänster-nedre hörnpunkt för Quadrangle-region |
| [getLeftTop()](#getlefttop) | Hämtar vänster-övre hörnpunkt för Quadrangle-regionVärde: En vänster-övre hörnpunkt för Quadrangle-region |
| [getRightBottom()](#getrightbottom) | Hämtar höger-nedre hörnpunkt för Quadrangle-regionVärde: En höger-nedre hörnpunkt för Quadrangle-region |
| [getRightTop()](#getrighttop) | Hämtar höger-övre hörnpunkt för Quadrangle-regionVärde: En höger-övre hörnpunkt för Quadrangle-region |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [isEmpty()](#isempty) | Testar om alla punkter i denna fyrhörning har värden noll.Värde: Returnerar true om alla punkter i denna fyrhörning har |
| [setLeftBottom()](#setleftbottom) | Ställer in vänster‑nedre hörnpunkt för fyrhörningsregionen.Värde: En vänster‑nedre hörnpunkt för fyrhörningsregionen |
| [setLeftTop()](#setlefttop) | Ställer in vänster‑övre hörnpunkt för fyrhörningsregionen.Värde: En vänster‑övre hörnpunkt för fyrhörningsregionen |
| [setRightBottom()](#setrightbottom) | Ställer in höger‑nedre hörnpunkt för fyrhörningsregionen.Värde: En höger‑nedre hörnpunkt för fyrhörningsregionen |
| [setRightTop()](#setrighttop) | Ställer in höger‑övre hörnpunkt för fyrhörningsregionen.Värde: En höger‑övre hörnpunkt för fyrhörningsregionen |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av denna fyrhörning. |

### contains(pt) {#contains}

Bestämmer om den angivna punkten finns inom denna Quadrangle-struktur.

| Parameter | Beskrivning |
| --- | --- |
| pt | Punkten att testa. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Bestämmer om den angivna punkten finns inom denna Quadrangle-struktur.

| Parameter | Beskrivning |
| --- | --- |
| x | x‑punktens koordinat. |
| y | y‑punktens koordinat. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Bestämmer om den angivna Quadrangle är innehållen i eller skär denna Quadrangle-struktur.

| Parameter | Beskrivning |
| --- | --- |
| quad | Fyrhörningen att testa. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Bestämmer om den angivna rektangeln är innehållen i eller skär denna Quadrangle-struktur.

| Parameter | Beskrivning |
| --- | --- |
| rect | Rektangeln att testa. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Returnerar ett värde som indikerar om denna instans är lika med ett angivet Quadrangle-värde.

| Parameter | Beskrivning |
| --- | --- |
| annat | Ett fyrhörningsvärde att jämföra med detta objekt. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Skapar en rektangel som avgränsar denna Quadrangle

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Hämtar vänster-nedre hörnpunkt för Quadrangle-regionVärde: En vänster-nedre hörnpunkt för Quadrangle-region

### getLeftTop() {#getlefttop}

Hämtar vänster-övre hörnpunkt för Quadrangle-regionVärde: En vänster-övre hörnpunkt för Quadrangle-region

### getRightBottom() {#getrightbottom}

Hämtar höger-nedre hörnpunkt för Quadrangle-regionVärde: En höger-nedre hörnpunkt för Quadrangle-region

### getRightTop() {#getrighttop}

Hämtar höger-övre hörnpunkt för Quadrangle-regionVärde: En höger-övre hörnpunkt för Quadrangle-region

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Testar om alla punkter i denna fyrhörning har värden noll.Värde: Returnerar true om alla punkter i denna fyrhörning har värden noll; annars false.

### setLeftBottom() {#setleftbottom}

Ställer in vänster‑nedre hörnpunkt för fyrhörningsregionen.Värde: En vänster‑nedre hörnpunkt för fyrhörningsregionen

### setLeftTop() {#setlefttop}

Ställer in vänster‑övre hörnpunkt för fyrhörningsregionen.Värde: En vänster‑övre hörnpunkt för fyrhörningsregionen

### setRightBottom() {#setrightbottom}

Ställer in höger‑nedre hörnpunkt för fyrhörningsregionen.Värde: En höger‑nedre hörnpunkt för fyrhörningsregionen

### setRightTop() {#setrighttop}

Ställer in höger‑övre hörnpunkt för fyrhörningsregionen.Värde: En höger‑övre hörnpunkt för fyrhörningsregionen

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av denna fyrhörning.

**Returns:** A string that represents this Quadrangle.
