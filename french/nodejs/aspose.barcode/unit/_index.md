---
title: "Unit"
linktitle: "Unit"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Spécifie la valeur de taille dans différentes unités (Pixel, Inches, etc)."
type: docs
weight: 960
url: /fr/nodejs/aspose.barcode/unit/
---

## Unit class

Spécifie la valeur de taille dans différentes unités (Pixel, Inches, etc).

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

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Détermine si cette instance et un objet spécifié, qui doit également être un objet Unit, ont la même valeur. |
| [getDocument()](#getdocument) | Obtient la valeur de taille en unités de document. |
| [getInches()](#getinches) | Obtient la valeur de taille en pouces. |
| [getMillimeters()](#getmillimeters) | Obtient la valeur de taille en millimètres. |
| [getPixels()](#getpixels) | Obtient la valeur de taille en pixels. |
| [getPoint()](#getpoint) | Obtient la valeur de taille en points. |
| [setDocument()](#setdocument) | Définit la valeur de taille en unités de document. |
| [setInches()](#setinches) | Définit la valeur de taille en pouces. |
| [setMillimeters()](#setmillimeters) | Définit la valeur de taille en millimètres. |
| [setPixels()](#setpixels) | Définit la valeur de taille en pixels. |
| [setPoint()](#setpoint) | Définit la valeur de taille en points. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible de cet Unit. |

### equals(obj) {#equals}

Détermine si cette instance et un objet spécifié, qui doit également être un objet Unit, ont la même valeur.

| Paramètre | Description |
| --- | --- |
| obj | L'Unit à comparer à cette instance. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Obtient la valeur de taille en unités de document.

### getInches() {#getinches}

Obtient la valeur de taille en pouces.

### getMillimeters() {#getmillimeters}

Obtient la valeur de taille en millimètres.

### getPixels() {#getpixels}

Obtient la valeur de taille en pixels.

### getPoint() {#getpoint}

Obtient la valeur de taille en points.

### setDocument() {#setdocument}

Définit la valeur de taille en unités de document.

### setInches() {#setinches}

Définit la valeur de taille en pouces.

### setMillimeters() {#setmillimeters}

Définit la valeur de taille en millimètres.

### setPixels() {#setpixels}

Définit la valeur de taille en pixels.

### setPoint() {#setpoint}

Définit la valeur de taille en points.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible de cet Unit.

**Returns:** A string that represents this Unit.
