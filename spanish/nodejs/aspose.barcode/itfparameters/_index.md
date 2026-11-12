---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros de ITF."
type: docs
weight: 540
url: /es/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

Parámetros de ITF.

```js
new ITFParameters()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | Obtiene el grosor de un borde ITF (barra portadora) en unidades. Valor predeterminado: 12pt. |
| [getBorderType()](#getbordertype) | Tipo de borde del código de barras ITF. Valor predeterminado: ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | Obtiene el grosor de un borde ITF (barra portadora) en unidades. Valor predeterminado: 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | Tipo de borde del código de barras ITF. Valor predeterminado: ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | Tamaño de las zonas silenciosas en xDimension. Valor predeterminado: 10, lo que significa que si xDimension = 2px, las zonas silenciosas serán 20px. |
| [setBorderThickness(value)](#setborderthickness) | Establece el grosor de un borde ITF (barra portadora) en unidades. Valor predeterminado: 12pt. |
| [setBorderType()](#setbordertype) | Tipo de borde del código de barras ITF. Valor predeterminado: ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | Establece el grosor de un borde ITF (barra portadora) en unidades. Valor predeterminado: 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | Tipo de borde del código de barras ITF. Valor predeterminado: ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | Tamaño de las zonas silenciosas en xDimension. Valor predeterminado: 10, lo que significa que si xDimension = 2px, las zonas silenciosas serán 20px. |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este ITFParameters. |

### getBorderThickness() {#getborderthickness}

Obtiene el grosor de un borde ITF (barra portadora) en unidades. Valor predeterminado: 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

Tipo de borde del código de barras ITF. Valor predeterminado: ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

Obtiene el grosor de un borde ITF (barra portadora) en unidades. Valor predeterminado: 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

Tipo de borde del código de barras ITF. Valor predeterminado: ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

Tamaño de las zonas silenciosas en xDimension. Valor predeterminado: 10, lo que significa que si xDimension = 2px, las zonas silenciosas serán 20px.

**Throws:** IllegalArgumentException
El valor del parámetro QuietZoneCoef es menor que 10.

### setBorderThickness(value) {#setborderthickness}

Establece el grosor de un borde ITF (barra portadora) en unidades. Valor predeterminado: 12pt.

| Parámetro | Descripción |
| --- | --- |
| valor | un grosor de borde ITF (barra portadora) en unidades. |

### setBorderType() {#setbordertype}

Tipo de borde del código de barras ITF. Valor predeterminado: ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

Establece el grosor de un borde ITF (barra portadora) en unidades. Valor predeterminado: 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

Tipo de borde del código de barras ITF. Valor predeterminado: ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

Tamaño de las zonas silenciosas en xDimension. Valor predeterminado: 10, lo que significa que si xDimension = 2px, las zonas silenciosas serán 20px.

**Throws:** IllegalArgumentException
El valor del parámetro QuietZoneCoef es menor que 10.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este ITFParameters.

**Returns:** A string that represents this ITFParameters.
