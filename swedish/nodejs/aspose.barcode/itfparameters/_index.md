---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "ITF-parametrar."
type: docs
weight: 540
url: /sv/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

ITF-parametrar.

```js
new ITFParameters()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | Hämtar tjockleken på en ITF-kant (bärare) i enhetsvärde. Standardvärde: 12pt. |
| [getBorderType()](#getbordertype) | Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | Hämtar tjockleken på en ITF-kant (bärare) i enhetsvärde. Standardvärde: 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | Storlek på tysta zoner i xDimension. Standardvärde: 10, vilket betyder att om xDimension = 2px blir tysta zoner 20px. |
| [setBorderThickness(value)](#setborderthickness) | Ställer in tjockleken på en ITF-kant (bärare) i enhetsvärde. Standardvärde: 12pt. |
| [setBorderType()](#setbordertype) | Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | Ställer in tjockleken på en ITF-kant (bärare) i enhetsvärde. Standardvärde: 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | Storlek på tysta zoner i xDimension. Standardvärde: 10, vilket betyder att om xDimension = 2px blir tysta zoner 20px. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av dessa ITFParameters. |

### getBorderThickness() {#getborderthickness}

Hämtar tjockleken på en ITF-kant (bärare) i enhetsvärde. Standardvärde: 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

Hämtar tjockleken på en ITF-kant (bärare) i enhetsvärde. Standardvärde: 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

Storlek på tysta zoner i xDimension. Standardvärde: 10, vilket betyder att om xDimension = 2px blir tysta zoner 20px.

**Throws:** IllegalArgumentException
QuietZoneCoef‑parametervärdet är mindre än 10.

### setBorderThickness(value) {#setborderthickness}

Ställer in tjockleken på en ITF-kant (bärare) i enhetsvärde. Standardvärde: 12pt.

| Parameter | Beskrivning |
| --- | --- |
| värde | en ITF-kant (bärare) tjocklek i enhetsvärde. |

### setBorderType() {#setbordertype}

Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

Ställer in tjockleken på en ITF-kant (bärare) i enhetsvärde. Standardvärde: 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

Storlek på tysta zoner i xDimension. Standardvärde: 10, vilket betyder att om xDimension = 2px blir tysta zoner 20px.

**Throws:** IllegalArgumentException
QuietZoneCoef‑parametervärdet är mindre än 10.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av dessa ITFParameters.

**Returns:** A string that represents this ITFParameters.
