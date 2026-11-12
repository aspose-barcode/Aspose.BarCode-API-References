---
title: "PdfParameters"
linktitle: "PdfParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Enveloppe des paramètres PDF."
type: docs
weight: 780
url: /fr/nodejs/aspose.barcode/pdfparameters/
---

## PdfParameters class

Enveloppe des paramètres PDF. Attend une instance sous-jacente `mwObject` qui fournit les méthodes getter/setter correspondantes retournant/acceptant des chaînes CMYK comme "30_100_0_30" ou `null`.

```js
new PdfParameters(mwObject)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mwObject | objet | – instance de la classe Java PdfParameters |

## Méthodes

| Nom | Description |
| --- | --- |
| [_initializeWrapperMembers()](#-initializewrappermembers) | initialiseur no-op |
| [getCMYKBackColor()](#getcmykbackcolor) | Valeur de couleur d'arrière-plan CMYK. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [getCMYKBarColor()](#getcmykbarcolor) | Valeur de couleur CMYK du code-barres. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [getCMYKCaptionAboveColor()](#getcmykcaptionabovecolor) | Valeur de couleur CMYK de la légende supérieure. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [getCMYKCaptionBelowColor()](#getcmykcaptionbelowcolor) | Valeur de couleur CMYK de la légende inférieure. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [getCMYKCodetextColor()](#getcmykcodetextcolor) | Valeur de couleur CMYK du Codetext. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [isTextAsPath()](#istextaspath) | Les chemins sont-ils utilisés à la place du texte (à utiliser si les caractères Unicode ne s'affichent pas) Valeur par défaut : false. |
| [setCMYKBackColor(value)](#setcmykbackcolor) | Valeur de couleur d'arrière-plan CMYK. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [setCMYKBarColor(value)](#setcmykbarcolor) | Valeur de couleur CMYK du code-barres. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [setCMYKCaptionAboveColor(value)](#setcmykcaptionabovecolor) | Valeur de couleur CMYK de la légende supérieure. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [setCMYKCaptionBelowColor(value)](#setcmykcaptionbelowcolor) | Valeur de couleur CMYK de la légende inférieure. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [setCMYKCodetextColor(value)](#setcmykcodetextcolor) | Valeur de couleur CMYK du Codetext. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée. |
| [setTextAsPath()](#settextaspath) | Les chemins sont-ils utilisés à la place du texte (à utiliser si les caractères Unicode ne s'affichent pas) Valeur par défaut : false. |

### _initializeWrapperMembers() {#-initializewrappermembers}

initialiseur no-op

### getCMYKBackColor() {#getcmykbackcolor}

Valeur de couleur d'arrière-plan CMYK. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

**Returns:** CMYKColor\|null

### getCMYKBarColor() {#getcmykbarcolor}

Valeur de couleur CMYK du code-barres. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

**Returns:** CMYKColor\|null

### getCMYKCaptionAboveColor() {#getcmykcaptionabovecolor}

Valeur de couleur CMYK de la légende supérieure. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

**Returns:** CMYKColor\|null

### getCMYKCaptionBelowColor() {#getcmykcaptionbelowcolor}

Valeur de couleur CMYK de la légende inférieure. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

**Returns:** CMYKColor\|null

### getCMYKCodetextColor() {#getcmykcodetextcolor}

Valeur de couleur CMYK du Codetext. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

**Returns:** CMYKColor\|null

### isTextAsPath() {#istextaspath}

Les chemins sont-ils utilisés à la place du texte (à utiliser si les caractères Unicode ne s'affichent pas) Valeur par défaut : false.

### setCMYKBackColor(value) {#setcmykbackcolor}

Valeur de couleur d'arrière-plan CMYK. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | CMYKColor\\ | null |  |

### setCMYKBarColor(value) {#setcmykbarcolor}

Valeur de couleur CMYK du code-barres. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | CMYKColor\\ | null |  |

### setCMYKCaptionAboveColor(value) {#setcmykcaptionabovecolor}

Valeur de couleur CMYK de la légende supérieure. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | CMYKColor\\ | null |  |

### setCMYKCaptionBelowColor(value) {#setcmykcaptionbelowcolor}

Valeur de couleur CMYK de la légende inférieure. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | CMYKColor\\ | null |  |

### setCMYKCodetextColor(value) {#setcmykcodetextcolor}

Valeur de couleur CMYK du Codetext. Null signifie que la couleur CMYK n'est pas utilisée, à la place la couleur RGB normale est utilisée.

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | CMYKColor\\ | null |  |

### setTextAsPath() {#settextaspath}

Les chemins sont-ils utilisés à la place du texte (à utiliser si les caractères Unicode ne s'affichent pas) Valeur par défaut : false.
