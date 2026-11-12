---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Parametri ITF."
type: docs
weight: 540
url: /it/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

Parametri ITF.

```js
new ITFParameters()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | Ottiene lo spessore di un bordo ITF (barra portante) in unità. Valore predefinito: 12pt. |
| [getBorderType()](#getbordertype) | Tipo di bordo del codice a barre ITF. Valore predefinito: ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | Ottiene lo spessore di un bordo ITF (barra portante) in unità. Valore predefinito: 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | Tipo di bordo del codice a barre ITF. Valore predefinito: ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | Dimensione delle zone silenziose in xDimension. Valore predefinito: 10, il che significa che se xDimension = 2px le zone silenziose saranno 20px. |
| [setBorderThickness(value)](#setborderthickness) | Imposta lo spessore di un bordo ITF (barra portante) in unità. Valore predefinito: 12pt. |
| [setBorderType()](#setbordertype) | Tipo di bordo del codice a barre ITF. Valore predefinito: ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | Imposta lo spessore di un bordo ITF (barra portante) in unità. Valore predefinito: 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | Tipo di bordo del codice a barre ITF. Valore predefinito: ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | Dimensione delle zone silenziose in xDimension. Valore predefinito: 10, il che significa che se xDimension = 2px le zone silenziose saranno 20px. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo ITFParameters. |

### getBorderThickness() {#getborderthickness}

Ottiene lo spessore di un bordo ITF (barra portante) in unità. Valore predefinito: 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

Tipo di bordo del codice a barre ITF. Valore predefinito: ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

Ottiene lo spessore di un bordo ITF (barra portante) in unità. Valore predefinito: 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

Tipo di bordo del codice a barre ITF. Valore predefinito: ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

Dimensione delle zone silenziose in xDimension. Valore predefinito: 10, il che significa che se xDimension = 2px le zone silenziose saranno 20px.

**Throws:** IllegalArgumentException
Il valore del parametro QuietZoneCoef è inferiore a 10.

### setBorderThickness(value) {#setborderthickness}

Imposta lo spessore di un bordo ITF (barra portante) in unità. Valore predefinito: 12pt.

| Parametro | Descrizione |
| --- | --- |
| valore | uno spessore di bordo ITF (barra portante) in unità. |

### setBorderType() {#setbordertype}

Tipo di bordo del codice a barre ITF. Valore predefinito: ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

Imposta lo spessore di un bordo ITF (barra portante) in unità. Valore predefinito: 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

Tipo di bordo del codice a barre ITF. Valore predefinito: ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

Dimensione delle zone silenziose in xDimension. Valore predefinito: 10, il che significa che se xDimension = 2px le zone silenziose saranno 20px.

**Throws:** IllegalArgumentException
Il valore del parametro QuietZoneCoef è inferiore a 10.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo ITFParameters.

**Returns:** A string that represents this ITFParameters.
