---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "ITF-Parameter."
type: docs
weight: 540
url: /de/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

ITF-Parameter.

```js
new ITFParameters()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | Liefert die Dicke einer ITF-Grenze (Trägerbalken) in Einheit. Standardwert: 12pt. |
| [getBorderType()](#getbordertype) | Grenztyp des ITF-Barcodes. Standardwert: ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | Liefert die Dicke einer ITF-Grenze (Trägerbalken) in Einheit. Standardwert: 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | Randtyp des ITF-Barcodes. Standardwert: ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | Größe der Ruhebereiche in xDimension. Standardwert: 10, was bedeutet, dass wenn xDimension = 2px, die Ruhebereiche 20px betragen. |
| [setBorderThickness(value)](#setborderthickness) | Legt die Dicke eines ITF border (bearer bar) in Einheit fest. Standardwert: 12pt. |
| [setBorderType()](#setbordertype) | Grenztyp des ITF-Barcodes. Standardwert: ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | Legt die Dicke eines ITF border (bearer bar) in Einheit fest. Standardwert: 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | Randtyp des ITF-Barcodes. Standardwert: ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | Größe der Ruhebereiche in xDimension. Standardwert: 10, was bedeutet, dass wenn xDimension = 2px, die Ruhebereiche 20px betragen. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses ITFParameters zurück. |

### getBorderThickness() {#getborderthickness}

Liefert die Dicke einer ITF-Grenze (Trägerbalken) in Einheit. Standardwert: 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

Grenztyp des ITF-Barcodes. Standardwert: ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

Liefert die Dicke einer ITF-Grenze (Trägerbalken) in Einheit. Standardwert: 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

Randtyp des ITF-Barcodes. Standardwert: ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

Größe der Ruhebereiche in xDimension. Standardwert: 10, was bedeutet, dass wenn xDimension = 2px, die Ruhebereiche 20px betragen.

**Throws:** IllegalArgumentException
Der Parameterwert QuietZoneCoef ist kleiner als 10.

### setBorderThickness(value) {#setborderthickness}

Legt die Dicke eines ITF border (bearer bar) in Einheit fest. Standardwert: 12pt.

| Parameter | Beschreibung |
| --- | --- |
| Wert | eine ITF border (bearer bar) Dicke in Einheit. |

### setBorderType() {#setbordertype}

Grenztyp des ITF-Barcodes. Standardwert: ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

Legt die Dicke eines ITF border (bearer bar) in Einheit fest. Standardwert: 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

Randtyp des ITF-Barcodes. Standardwert: ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

Größe der Ruhebereiche in xDimension. Standardwert: 10, was bedeutet, dass wenn xDimension = 2px, die Ruhebereiche 20px betragen.

**Throws:** IllegalArgumentException
Der Parameterwert QuietZoneCoef ist kleiner als 10.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses ITFParameters zurück.

**Returns:** A string that represents this ITFParameters.
