---
title: "Unit"
linktitle: "Unit"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Specifica il valore di dimensione in diverse unità (Pixel, Pollici, ecc.)."
type: docs
weight: 960
url: /it/nodejs/aspose.barcode/unit/
---

## Unit class

Specifica il valore di dimensione in diverse unità (Pixel, Pollici, ecc.).

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Determina se questa istanza e un oggetto specificato, che deve essere anche un oggetto Unit, hanno lo stesso valore. |
| [getDocument()](#getdocument) | Ottiene il valore della dimensione in unità di documento. |
| [getInches()](#getinches) | Ottiene il valore della dimensione in pollici. |
| [getMillimeters()](#getmillimeters) | Ottiene il valore della dimensione in millimetri. |
| [getPixels()](#getpixels) | Ottiene il valore della dimensione in pixel. |
| [getPoint()](#getpoint) | Ottiene il valore della dimensione in punti. |
| [setDocument()](#setdocument) | Imposta il valore della dimensione in unità di documento. |
| [setInches()](#setinches) | Imposta il valore della dimensione in pollici. |
| [setMillimeters()](#setmillimeters) | Imposta il valore della dimensione in millimetri. |
| [setPixels()](#setpixels) | Imposta il valore della dimensione in pixel. |
| [setPoint()](#setpoint) | Imposta il valore della dimensione in punti. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo Unit. |

### equals(obj) {#equals}

Determina se questa istanza e un oggetto specificato, che deve essere anche un oggetto Unit, hanno lo stesso valore.

| Parametro | Descrizione |
| --- | --- |
| obj | L'Unit da confrontare con questa istanza. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Ottiene il valore della dimensione in unità di documento.

### getInches() {#getinches}

Ottiene il valore della dimensione in pollici.

### getMillimeters() {#getmillimeters}

Ottiene il valore della dimensione in millimetri.

### getPixels() {#getpixels}

Ottiene il valore della dimensione in pixel.

### getPoint() {#getpoint}

Ottiene il valore della dimensione in punti.

### setDocument() {#setdocument}

Imposta il valore della dimensione in unità di documento.

### setInches() {#setinches}

Imposta il valore della dimensione in pollici.

### setMillimeters() {#setmillimeters}

Imposta il valore della dimensione in millimetri.

### setPixels() {#setpixels}

Imposta il valore della dimensione in pixel.

### setPoint() {#setpoint}

Imposta il valore della dimensione in punti.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo Unit.

**Returns:** A string that represents this Unit.
