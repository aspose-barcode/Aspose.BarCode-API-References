---
title: "Enhet"
linktitle: "Enhet"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Anger storleksvärdet i olika enheter (pixel, tum osv.)."
type: docs
weight: 960
url: /sv/nodejs/aspose.barcode/unit/
---

## Unit class

Anger storleksvärdet i olika enheter (pixel, tum osv.).

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Bestämmer om detta objekt och ett angivet objekt, som också måste vara ett Enhet-objekt, har samma värde. |
| [getDocument()](#getdocument) | Hämtar storleksvärde i dokumentenheter. |
| [getInches()](#getinches) | Hämtar storleksvärde i tum. |
| [getMillimeters()](#getmillimeters) | Hämtar storleksvärde i millimeter. |
| [getPixels()](#getpixels) | Hämtar storleksvärde i pixlar. |
| [getPoint()](#getpoint) | Hämtar storleksvärde i punkt. |
| [setDocument()](#setdocument) | Ställer in storleksvärde i dokumentenheter. |
| [setInches()](#setinches) | Ställer in storleksvärde i tum. |
| [setMillimeters()](#setmillimeters) | Ställer in storleksvärde i millimeter. |
| [setPixels()](#setpixels) | Ställer in storleksvärde i pixlar. |
| [setPoint()](#setpoint) | Ställer in storleksvärde i punkt. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av denna Unit. |

### equals(obj) {#equals}

Bestämmer om detta objekt och ett angivet objekt, som också måste vara ett Enhet-objekt, har samma värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Den Unit att jämföra med detta objekt. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Hämtar storleksvärde i dokumentenheter.

### getInches() {#getinches}

Hämtar storleksvärde i tum.

### getMillimeters() {#getmillimeters}

Hämtar storleksvärde i millimeter.

### getPixels() {#getpixels}

Hämtar storleksvärde i pixlar.

### getPoint() {#getpoint}

Hämtar storleksvärde i punkt.

### setDocument() {#setdocument}

Ställer in storleksvärde i dokumentenheter.

### setInches() {#setinches}

Ställer in storleksvärde i tum.

### setMillimeters() {#setmillimeters}

Ställer in storleksvärde i millimeter.

### setPixels() {#setpixels}

Ställer in storleksvärde i pixlar.

### setPoint() {#setpoint}

Ställer in storleksvärde i punkt.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av denna Unit.

**Returns:** A string that represents this Unit.
