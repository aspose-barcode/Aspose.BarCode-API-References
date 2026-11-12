---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Paramètres ITF."
type: docs
weight: 540
url: /fr/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

Paramètres ITF.

```js
new ITFParameters()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | Obtient l'épaisseur d'une bordure ITF (barre porteuse) en unités. Valeur par défaut : 12pt. |
| [getBorderType()](#getbordertype) | Type de bordure du code-barres ITF. Valeur par défaut : ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | Obtient l'épaisseur d'une bordure ITF (barre porteuse) en unités. Valeur par défaut : 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | Type de bordure du code-barres ITF. Valeur par défaut : ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | Taille des zones silencieuses en xDimension. Valeur par défaut : 10, ce qui signifie que si xDimension = 2px alors les zones silencieuses seront de 20px. |
| [setBorderThickness(value)](#setborderthickness) | Définit l'épaisseur d'une bordure ITF (barre porteuse) en unités. Valeur par défaut : 12pt. |
| [setBorderType()](#setbordertype) | Type de bordure du code-barres ITF. Valeur par défaut : ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | Définit l'épaisseur d'une bordure ITF (barre porteuse) en unités. Valeur par défaut : 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | Type de bordure du code-barres ITF. Valeur par défaut : ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | Taille des zones silencieuses en xDimension. Valeur par défaut : 10, ce qui signifie que si xDimension = 2px alors les zones silencieuses seront de 20px. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet ITFParameters. |

### getBorderThickness() {#getborderthickness}

Obtient l'épaisseur d'une bordure ITF (barre porteuse) en unités. Valeur par défaut : 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

Type de bordure du code-barres ITF. Valeur par défaut : ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

Obtient l'épaisseur d'une bordure ITF (barre porteuse) en unités. Valeur par défaut : 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

Type de bordure du code-barres ITF. Valeur par défaut : ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

Taille des zones silencieuses en xDimension. Valeur par défaut : 10, ce qui signifie que si xDimension = 2px alors les zones silencieuses seront de 20px.

**Throws:** IllegalArgumentException
La valeur du paramètre QuietZoneCoef est inférieure à 10.

### setBorderThickness(value) {#setborderthickness}

Définit l'épaisseur d'une bordure ITF (barre porteuse) en unités. Valeur par défaut : 12pt.

| Paramètre | Description |
| --- | --- |
| valeur | une épaisseur de bordure ITF (barre porteuse) en unités. |

### setBorderType() {#setbordertype}

Type de bordure du code-barres ITF. Valeur par défaut : ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

Définit l'épaisseur d'une bordure ITF (barre porteuse) en unités. Valeur par défaut : 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

Type de bordure du code-barres ITF. Valeur par défaut : ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

Taille des zones silencieuses en xDimension. Valeur par défaut : 10, ce qui signifie que si xDimension = 2px alors les zones silencieuses seront de 20px.

**Throws:** IllegalArgumentException
La valeur du paramètre QuietZoneCoef est inférieure à 10.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de cet ITFParameters.

**Returns:** A string that represents this ITFParameters.
