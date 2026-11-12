---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat een set van vier punten op die een vierhoekgebied vertegenwoordigen."
type: docs
weight: 850
url: /nl/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Slaat een set van vier punten op die een vierhoekgebied vertegenwoordigen.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Initialiseert een nieuwe instantie van de Quadrangle-structuur met de beschrijvende punten.

| Parameter | Beschrijving |
| --- | --- |
| leftTop | Een Punt dat de linkerbovenhoek van de Quadrangle vertegenwoordigt. |
| rightTop | Een Punt dat de rechterbovenhoek van de Quadrangle vertegenwoordigt. |
| rightBottom | Een Punt dat de rechteronderhoek van de Quadrangle vertegenwoordigt. |
| leftBottom | Een Punt dat de linkeronderhoek van de Quadrangle vertegenwoordigt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [contains(pt)](#contains) | Bepaalt of het opgegeven Punt zich binnen deze Quadrangle-structuur bevindt. |
| [containsPoint(x, y)](#containspoint) | Bepaalt of het opgegeven punt zich binnen deze Quadrangle-structuur bevindt. |
| [containsQuadrangle(quad)](#containsquadrangle) | Bepaalt of de opgegeven Quadrangle zich binnen deze Quadrangle-structuur bevindt of deze intersecteert. |
| [containsRectangle(rect)](#containsrectangle) | Bepaalt of het opgegeven Rechthoek zich binnen deze Quadrangle-structuur bevindt of deze intersecteert. |
| [equals(other)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven Quadrangle-waarde. |
| [getBoundingRectangle()](#getboundingrectangle) | Maakt een Rechthoek die deze Quadrangle omsluit |
| [getLeftBottom()](#getleftbottom) | Haalt het linksonderhoek Punt van het Quadrangle-gebied opWaarde: Een linksonderhoek Punt van het Quadrangle-gebied |
| [getLeftTop()](#getlefttop) | Haalt het linkerbovenhoek Punt van het Quadrangle-gebied opWaarde: Een linkerbovenhoek Punt van het Quadrangle-gebied |
| [getRightBottom()](#getrightbottom) | Haalt het rechteronderhoek Punt van het Quadrangle-gebied opWaarde: Een rechteronderhoek Punt van het Quadrangle-gebied |
| [getRightTop()](#getrighttop) | Haalt het rechterbovenhoek Punt van het Quadrangle-gebied opWaarde: Een rechterbovenhoek Punt van het Quadrangle-gebied |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isempty) | Test of alle Punten van deze Quadrangle nulwaarden hebben. Waarde: Retourneert true als alle Punten van deze Quadrangle nulwaarden hebben |
| [setLeftBottom()](#setleftbottom) | Stelt linksonderhoekpunt van Quadrangle-regio in. Waarde: Een linksonderhoekpunt van Quadrangle-regio |
| [setLeftTop()](#setlefttop) | Stelt linkerbovenhoekpunt van Quadrangle-regio in. Waarde: Een linkerbovenhoekpunt van Quadrangle-regio |
| [setRightBottom()](#setrightbottom) | Stelt rechteronderhoekpunt van Quadrangle-regio in. Waarde: Een rechteronderhoekpunt van Quadrangle-regio |
| [setRightTop()](#setrighttop) | Stelt rechterbovenhoekpunt van Quadrangle-regio in. Waarde: Een rechterbovenhoekpunt van Quadrangle-regio |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Quadrangle. |

### contains(pt) {#contains}

Bepaalt of het opgegeven Punt zich binnen deze Quadrangle-structuur bevindt.

| Parameter | Beschrijving |
| --- | --- |
| pt | Het punt om te testen. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Bepaalt of het opgegeven punt zich binnen deze Quadrangle-structuur bevindt.

| Parameter | Beschrijving |
| --- | --- |
| x | De x-puntcoördinaat. |
| y | De y-puntcoördinaat. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Bepaalt of de opgegeven Quadrangle zich binnen deze Quadrangle-structuur bevindt of deze intersecteert.

| Parameter | Beschrijving |
| --- | --- |
| quad | De Quadrangle om te testen. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Bepaalt of het opgegeven Rechthoek zich binnen deze Quadrangle-structuur bevindt of deze intersecteert.

| Parameter | Beschrijving |
| --- | --- |
| rect | De rechthoek om te testen. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven Quadrangle-waarde.

| Parameter | Beschrijving |
| --- | --- |
| overig | Een Quadrangle-waarde om te vergelijken met deze instantie. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Maakt een Rechthoek die deze Quadrangle omsluit

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Haalt het linksonderhoek Punt van het Quadrangle-gebied opWaarde: Een linksonderhoek Punt van het Quadrangle-gebied

### getLeftTop() {#getlefttop}

Haalt het linkerbovenhoek Punt van het Quadrangle-gebied opWaarde: Een linkerbovenhoek Punt van het Quadrangle-gebied

### getRightBottom() {#getrightbottom}

Haalt het rechteronderhoek Punt van het Quadrangle-gebied opWaarde: Een rechteronderhoek Punt van het Quadrangle-gebied

### getRightTop() {#getrighttop}

Haalt het rechterbovenhoek Punt van het Quadrangle-gebied opWaarde: Een rechterbovenhoek Punt van het Quadrangle-gebied

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Test of alle Punten van deze Quadrangle nulwaarden hebben. Waarde: Retourneert true als alle Punten van deze Quadrangle nulwaarden hebben; anders false.

### setLeftBottom() {#setleftbottom}

Stelt linksonderhoekpunt van Quadrangle-regio in. Waarde: Een linksonderhoekpunt van Quadrangle-regio

### setLeftTop() {#setlefttop}

Stelt linkerbovenhoekpunt van Quadrangle-regio in. Waarde: Een linkerbovenhoekpunt van Quadrangle-regio

### setRightBottom() {#setrightbottom}

Stelt rechteronderhoekpunt van Quadrangle-regio in. Waarde: Een rechteronderhoekpunt van Quadrangle-regio

### setRightTop() {#setrighttop}

Stelt rechterbovenhoekpunt van Quadrangle-regio in. Waarde: Een rechterbovenhoekpunt van Quadrangle-regio

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Quadrangle.

**Returns:** A string that represents this Quadrangle.
