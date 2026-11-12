---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert ein Set von vier Punkten, das ein Quadrangle‑Gebiet darstellt."
type: docs
weight: 850
url: /de/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Speichert ein Set von vier Punkten, das ein Quadrangle‑Gebiet darstellt.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Initialisiert eine neue Instanz der Quadrangle-Struktur mit den beschreibenden Punkten.

| Parameter | Beschreibung |
| --- | --- |
| leftTop | Ein Punkt, der die linke obere Ecke des Quadrangle darstellt. |
| rightTop | Ein Punkt, der die rechte obere Ecke des Quadrangle darstellt. |
| rightBottom | Ein Punkt, der die rechte untere Ecke des Quadrangle darstellt. |
| leftBottom | Ein Punkt, der die linke untere Ecke des Quadrangle darstellt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [contains(pt)](#contains) | Bestimmt, ob der angegebene Punkt innerhalb dieser Quadrangle-Struktur enthalten ist. |
| [containsPoint(x, y)](#containspoint) | Bestimmt, ob der angegebene Punkt innerhalb dieser Quadrangle-Struktur enthalten ist. |
| [containsQuadrangle(quad)](#containsquadrangle) | Bestimmt, ob das angegebene Quadrangle in dieser Quadrangle-Struktur enthalten ist oder diese schneidet. |
| [containsRectangle(rect)](#containsrectangle) | Bestimmt, ob das angegebene Rechteck in dieser Quadrangle-Struktur enthalten ist oder diese schneidet. |
| [equals(other)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Quadrangle-Wert gleich ist. |
| [getBoundingRectangle()](#getboundingrectangle) | Erstellt ein Rechteck, das dieses Quadrangle umschließt |
| [getLeftBottom()](#getleftbottom) | Liefert den Punkt der linken unteren Ecke des Quadrangle regionValue: Ein Punkt der linken unteren Ecke des Quadrangle-Bereichs. |
| [getLeftTop()](#getlefttop) | Liefert den Punkt der linken oberen Ecke des Quadrangle regionValue: Ein Punkt der linken oberen Ecke des Quadrangle-Bereichs. |
| [getRightBottom()](#getrightbottom) | Liefert den Punkt der rechten unteren Ecke des Quadrangle regionValue: Ein Punkt der rechten unteren Ecke des Quadrangle-Bereichs. |
| [getRightTop()](#getrighttop) | Liefert den Punkt der rechten oberen Ecke des Quadrangle regionValue: Ein Punkt der rechten oberen Ecke des Quadrangle-Bereichs. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isempty) | Prüft, ob alle Punkte dieses Quadrangles den Wert Null haben. Wert: Gibt true zurück, wenn alle Punkte dieses Quadrangles den Wert Null haben. |
| [setLeftBottom()](#setleftbottom) | Setzt den linken unteren Eckpunkt des Quadrangle-Bereichs. Wert: Ein linker unterer Eckpunkt des Quadrangle-Bereichs. |
| [setLeftTop()](#setlefttop) | Setzt den linken oberen Eckpunkt des Quadrangle-Bereichs. Wert: Ein linker oberer Eckpunkt des Quadrangle-Bereichs. |
| [setRightBottom()](#setrightbottom) | Setzt den rechten unteren Eckpunkt des Quadrangle-Bereichs. Wert: Ein rechter unterer Eckpunkt des Quadrangle-Bereichs. |
| [setRightTop()](#setrighttop) | Setzt den rechten oberen Eckpunkt des Quadrangle-Bereichs. Wert: Ein rechter oberer Eckpunkt des Quadrangle-Bereichs. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Quadrangles zurück. |

### contains(pt) {#contains}

Bestimmt, ob der angegebene Punkt innerhalb dieser Quadrangle-Struktur enthalten ist.

| Parameter | Beschreibung |
| --- | --- |
| pt | Der zu testende Punkt. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Bestimmt, ob der angegebene Punkt innerhalb dieser Quadrangle-Struktur enthalten ist.

| Parameter | Beschreibung |
| --- | --- |
| x | Die x‑Koordinate des Punktes. |
| y | Die y‑Koordinate des Punktes. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Bestimmt, ob das angegebene Quadrangle in dieser Quadrangle-Struktur enthalten ist oder diese schneidet.

| Parameter | Beschreibung |
| --- | --- |
| quad | Das zu testende Quadrangle. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Bestimmt, ob das angegebene Rechteck in dieser Quadrangle-Struktur enthalten ist oder diese schneidet.

| Parameter | Beschreibung |
| --- | --- |
| rect | Das zu testende Rechteck. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Quadrangle-Wert gleich ist.

| Parameter | Beschreibung |
| --- | --- |
| andere | Ein Quadrangle-Wert zum Vergleich mit dieser Instanz. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Erstellt ein Rechteck, das dieses Quadrangle umschließt

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Liefert den Punkt der linken unteren Ecke des Quadrangle regionValue: Ein Punkt der linken unteren Ecke des Quadrangle-Bereichs.

### getLeftTop() {#getlefttop}

Liefert den Punkt der linken oberen Ecke des Quadrangle regionValue: Ein Punkt der linken oberen Ecke des Quadrangle-Bereichs.

### getRightBottom() {#getrightbottom}

Liefert den Punkt der rechten unteren Ecke des Quadrangle regionValue: Ein Punkt der rechten unteren Ecke des Quadrangle-Bereichs.

### getRightTop() {#getrighttop}

Liefert den Punkt der rechten oberen Ecke des Quadrangle regionValue: Ein Punkt der rechten oberen Ecke des Quadrangle-Bereichs.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Prüft, ob alle Punkte dieses Quadrangles den Wert Null haben. Wert: Gibt true zurück, wenn alle Punkte dieses Quadrangles den Wert Null haben; andernfalls false.

### setLeftBottom() {#setleftbottom}

Setzt den linken unteren Eckpunkt des Quadrangle-Bereichs. Wert: Ein linker unterer Eckpunkt des Quadrangle-Bereichs.

### setLeftTop() {#setlefttop}

Setzt den linken oberen Eckpunkt des Quadrangle-Bereichs. Wert: Ein linker oberer Eckpunkt des Quadrangle-Bereichs.

### setRightBottom() {#setrightbottom}

Setzt den rechten unteren Eckpunkt des Quadrangle-Bereichs. Wert: Ein rechter unterer Eckpunkt des Quadrangle-Bereichs.

### setRightTop() {#setrighttop}

Setzt den rechten oberen Eckpunkt des Quadrangle-Bereichs. Wert: Ein rechter oberer Eckpunkt des Quadrangle-Bereichs.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses Quadrangles zurück.

**Returns:** A string that represents this Quadrangle.
