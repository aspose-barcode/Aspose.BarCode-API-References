---
title: "Einheit"
linktitle: "Einheit"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Gibt den Größenwert in verschiedenen Einheiten an (Pixel, Zoll usw.)."
type: docs
weight: 960
url: /de/nodejs/aspose.barcode/unit/
---

## Unit class

Gibt den Größenwert in verschiedenen Einheiten an (Pixel, Zoll usw.).

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein Unit‑Objekt sein muss, denselben Wert haben. |
| [getDocument()](#getdocument) | Liefert den Größenwert in Dokumenteinheiten. |
| [getInches()](#getinches) | Liefert den Größenwert in Zoll. |
| [getMillimeters()](#getmillimeters) | Liefert den Größenwert in Millimetern. |
| [getPixels()](#getpixels) | Liefert den Größenwert in Pixeln. |
| [getPoint()](#getpoint) | Liefert den Größenwert in Punkten. |
| [setDocument()](#setdocument) | Setzt den Größenwert in Dokumenteinheiten. |
| [setInches()](#setinches) | Setzt den Größenwert in Zoll. |
| [setMillimeters()](#setmillimeters) | Setzt den Größenwert in Millimetern. |
| [setPixels()](#setpixels) | Setzt den Größenwert in Pixeln. |
| [setPoint()](#setpoint) | Setzt den Größenwert in Punkten. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser Einheit zurück. |

### equals(obj) {#equals}

Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein Unit‑Objekt sein muss, denselben Wert haben.

| Parameter | Beschreibung |
| --- | --- |
| obj | Die Einheit, die mit dieser Instanz verglichen wird. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Liefert den Größenwert in Dokumenteinheiten.

### getInches() {#getinches}

Liefert den Größenwert in Zoll.

### getMillimeters() {#getmillimeters}

Liefert den Größenwert in Millimetern.

### getPixels() {#getpixels}

Liefert den Größenwert in Pixeln.

### getPoint() {#getpoint}

Liefert den Größenwert in Punkten.

### setDocument() {#setdocument}

Setzt den Größenwert in Dokumenteinheiten.

### setInches() {#setinches}

Setzt den Größenwert in Zoll.

### setMillimeters() {#setmillimeters}

Setzt den Größenwert in Millimetern.

### setPixels() {#setpixels}

Setzt den Größenwert in Pixeln.

### setPoint() {#setpoint}

Setzt den Größenwert in Punkten.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser Einheit zurück.

**Returns:** A string that represents this Unit.
