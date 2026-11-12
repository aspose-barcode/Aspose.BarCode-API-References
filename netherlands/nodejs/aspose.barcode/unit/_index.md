---
title: "Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Specificeert de groottewaarde in verschillende eenheden (pixel, inches, enz.)."
type: docs
weight: 960
url: /nl/nodejs/aspose.barcode/unit/
---

## Unit class

Specificeert de groottewaarde in verschillende eenheden (pixel, inches, enz.).

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

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Bepaalt of deze instantie en een opgegeven object, dat ook een Unit‑object moet zijn, dezelfde waarde hebben. |
| [getDocument()](#getdocument) | Haalt de groottewaarde op in documenteenheden. |
| [getInches()](#getinches) | Haalt de groottewaarde op in inches. |
| [getMillimeters()](#getmillimeters) | Haalt de groottewaarde op in millimeters. |
| [getPixels()](#getpixels) | Haalt de groottewaarde op in pixels. |
| [getPoint()](#getpoint) | Haalt de groottewaarde op in point. |
| [setDocument()](#setdocument) | Stelt de groottewaarde in in documenteenheden. |
| [setInches()](#setinches) | Stelt de groottewaarde in in inches. |
| [setMillimeters()](#setmillimeters) | Stelt de groottewaarde in in millimeters. |
| [setPixels()](#setpixels) | Stelt de groottewaarde in in pixels. |
| [setPoint()](#setpoint) | Stelt de groottewaarde in in point. |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Unit. |

### equals(obj) {#equals}

Bepaalt of deze instantie en een opgegeven object, dat ook een Unit‑object moet zijn, dezelfde waarde hebben.

| Parameter | Beschrijving |
| --- | --- |
| obj | De Unit om te vergelijken met deze instantie. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Haalt de groottewaarde op in documenteenheden.

### getInches() {#getinches}

Haalt de groottewaarde op in inches.

### getMillimeters() {#getmillimeters}

Haalt de groottewaarde op in millimeters.

### getPixels() {#getpixels}

Haalt de groottewaarde op in pixels.

### getPoint() {#getpoint}

Haalt de groottewaarde op in point.

### setDocument() {#setdocument}

Stelt de groottewaarde in in documenteenheden.

### setInches() {#setinches}

Stelt de groottewaarde in in inches.

### setMillimeters() {#setmillimeters}

Stelt de groottewaarde in in millimeters.

### setPixels() {#setpixels}

Stelt de groottewaarde in in pixels.

### setPoint() {#setpoint}

Stelt de groottewaarde in in point.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Unit.

**Returns:** A string that represents this Unit.
