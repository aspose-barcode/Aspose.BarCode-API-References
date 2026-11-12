---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "ITF parameters."
type: docs
weight: 540
url: /nl/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

ITF parameters.

```js
new ITFParameters()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | Haalt een ITF-rand (bearer bar) dikte op in eenheid. Standaardwaarde: 12pt. |
| [getBorderType()](#getbordertype) | Randtype van ITF-barcode. Standaardwaarde: ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | Haalt een ITF-rand (bearer bar) dikte op in eenheid. Standaardwaarde: 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | Randtype van ITF-barcode. Standaardwaarde: ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | Grootte van de stille zones in xDimension. Standaardwaarde: 10, wat betekent dat als xDimension = 2px, de stille zones 20px zullen zijn. |
| [setBorderThickness(value)](#setborderthickness) | Stelt een ITF-rand (bearer bar) dikte in in eenheid. Standaardwaarde: 12pt. |
| [setBorderType()](#setbordertype) | Randtype van ITF-barcode. Standaardwaarde: ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | Stelt een ITF-rand (bearer bar) dikte in in eenheid. Standaardwaarde: 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | Randtype van ITF-barcode. Standaardwaarde: ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | Grootte van de stille zones in xDimension. Standaardwaarde: 10, wat betekent dat als xDimension = 2px, de stille zones 20px zullen zijn. |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze ITFParameters. |

### getBorderThickness() {#getborderthickness}

Haalt een ITF-rand (bearer bar) dikte op in eenheid. Standaardwaarde: 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

Randtype van ITF-barcode. Standaardwaarde: ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

Haalt een ITF-rand (bearer bar) dikte op in eenheid. Standaardwaarde: 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

Randtype van ITF-barcode. Standaardwaarde: ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

Grootte van de stille zones in xDimension. Standaardwaarde: 10, wat betekent dat als xDimension = 2px, de stille zones 20px zullen zijn.

**Throws:** IllegalArgumentException
De QuietZoneCoef-parameterwaarde is kleiner dan 10.

### setBorderThickness(value) {#setborderthickness}

Stelt een ITF-rand (bearer bar) dikte in in eenheid. Standaardwaarde: 12pt.

| Parameter | Beschrijving |
| --- | --- |
| waarde | een ITF-rand (bearer bar) dikte in eenheid. |

### setBorderType() {#setbordertype}

Randtype van ITF-barcode. Standaardwaarde: ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

Stelt een ITF-rand (bearer bar) dikte in in eenheid. Standaardwaarde: 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

Randtype van ITF-barcode. Standaardwaarde: ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

Grootte van de stille zones in xDimension. Standaardwaarde: 10, wat betekent dat als xDimension = 2px, de stille zones 20px zullen zijn.

**Throws:** IllegalArgumentException
De QuietZoneCoef-parameterwaarde is kleiner dan 10.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze ITFParameters.

**Returns:** A string that represents this ITFParameters.
