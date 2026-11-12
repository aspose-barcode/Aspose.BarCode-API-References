---
title: "Unit"
linktitle: "Unit"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Especifica el valor de tamaño en diferentes unidades (Pixel, Inches, etc.)."
type: docs
weight: 960
url: /es/nodejs/aspose.barcode/unit/
---

## Unit class

Especifica el valor de tamaño en diferentes unidades (Pixel, Inches, etc.).

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Determina si esta instancia y un objeto especificado, que también debe ser un objeto Unit, tienen el mismo valor. |
| [getDocument()](#getdocument) | Obtiene el valor del tamaño en unidades de documento. |
| [getInches()](#getinches) | Obtiene el valor del tamaño en pulgadas. |
| [getMillimeters()](#getmillimeters) | Obtiene el valor del tamaño en milímetros. |
| [getPixels()](#getpixels) | Obtiene el valor del tamaño en píxeles. |
| [getPoint()](#getpoint) | Obtiene el valor del tamaño en puntos. |
| [setDocument()](#setdocument) | Establece el valor del tamaño en unidades de documento. |
| [setInches()](#setinches) | Establece el valor del tamaño en pulgadas. |
| [setMillimeters()](#setmillimeters) | Establece el valor del tamaño en milímetros. |
| [setPixels()](#setpixels) | Establece el valor del tamaño en píxeles. |
| [setPoint()](#setpoint) | Establece el valor del tamaño en puntos. |
| [toString()](#tostring) | Devuelve una representación de cadena legible para humanos de este Unit. |

### equals(obj) {#equals}

Determina si esta instancia y un objeto especificado, que también debe ser un objeto Unit, tienen el mismo valor.

| Parámetro | Descripción |
| --- | --- |
| obj | El Unit para comparar con esta instancia. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Obtiene el valor del tamaño en unidades de documento.

### getInches() {#getinches}

Obtiene el valor del tamaño en pulgadas.

### getMillimeters() {#getmillimeters}

Obtiene el valor del tamaño en milímetros.

### getPixels() {#getpixels}

Obtiene el valor del tamaño en píxeles.

### getPoint() {#getpoint}

Obtiene el valor del tamaño en puntos.

### setDocument() {#setdocument}

Establece el valor del tamaño en unidades de documento.

### setInches() {#setinches}

Establece el valor del tamaño en pulgadas.

### setMillimeters() {#setmillimeters}

Establece el valor del tamaño en milímetros.

### setPixels() {#setpixels}

Establece el valor del tamaño en píxeles.

### setPoint() {#setpoint}

Establece el valor del tamaño en puntos.

### toString() {#tostring}

Devuelve una representación de cadena legible para humanos de este Unit.

**Returns:** A string that represents this Unit.
