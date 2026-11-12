---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Paramètres Codetext."
type: docs
weight: 270
url: /fr/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

Paramètres Codetext.

```js
new CodetextParameters()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getAlignment()](#getalignment) | Obtient l'alignement du texte du code. Valeur par défaut : TextAlignment.CENTER. |
| [getColor()](#getcolor) | Spécifiez la couleur du CodeText affiché. Valeur par défaut : BLACK. |
| [getFont()](#getfont) | Spécifiez la police du CodeText affiché. Valeur par défaut : Arial 5pt regular. Ignoré si FontMode est défini sur FontMode.AUTO. |
| [getFontMode()](#getfontmode) | Spécifiez le FontMode. Si FontMode est défini sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension. It i |
| [getLocation()](#getlocation) | Spécifiez l'emplacement du CodeText affiché, définissez CodeLocation.NONE pour masquer le CodeText. Valeur par défaut : CodeLocation.BELOW. |
| [getNoWrap()](#getnowrap) | Spécifiez le retour à la ligne (sauts de ligne) dans le texte. Valeur par défaut : false. |
| [getSpace()](#getspace) | Espace entre le CodeText et le code-barres en unités. Valeur par défaut : 2pt. Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, |
| [getTwoDDisplayText()](#gettwoddisplaytext) | Texte qui sera affiché à la place du codetext dans les codes-barres 2D. Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | Définit l'alignement du texte du code. Valeur par défaut : TextAlignment.CENTER. |
| [setColor()](#setcolor) | Spécifiez la couleur du CodeText affiché. Valeur par défaut : BLACK. |
| [setFont()](#setfont) | Spécifiez la police du CodeText affiché. Valeur par défaut : Arial 5pt regular. Ignoré si FontMode est défini sur FontMode.AUTO. |
| [setFontMode()](#setfontmode) | Spécifiez le FontMode. Si FontMode est défini sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension. It i |
| [setLocation()](#setlocation) | Spécifiez l'emplacement du CodeText affiché, définissez CodeLocation.NONE pour masquer le CodeText. Valeur par défaut : CodeLocation.NONE. |
| [setNoWrap()](#setnowrap) | Spécifiez le retour à la ligne (sauts de ligne) dans le texte. Valeur par défaut : false. |
| [setSpace()](#setspace) | Espace entre le CodeText et le code-barres en unités. Valeur par défaut : 2pt. Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, |
| [setTwoDDisplayText()](#settwoddisplaytext) | Texte qui sera affiché à la place du codetext dans les codes-barres 2D. Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible de ces CodetextParameters. |

### getAlignment() {#getalignment}

Obtient l'alignement du texte du code. Valeur par défaut : TextAlignment.CENTER.

### getColor() {#getcolor}

Spécifiez la couleur du CodeText affiché. Valeur par défaut : BLACK.

### getFont() {#getfont}

Spécifiez la police du CodeText affiché. Valeur par défaut : Arial 5pt regular. Ignoré si FontMode est défini sur FontMode.AUTO.

### getFontMode() {#getfontmode}

Spécifiez le FontMode. Si FontMode est défini sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension. Il est recommandé d'utiliser FontMode.AUTO notamment dans AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. Valeur par défaut : FontMode.AUTO.

### getLocation() {#getlocation}

Spécifiez l'emplacement du CodeText affiché, définissez CodeLocation.NONE pour masquer le CodeText. Valeur par défaut : CodeLocation.BELOW.

### getNoWrap() {#getnowrap}

Spécifiez le retour à la ligne (sauts de ligne) dans le texte. Valeur par défaut : false.

### getSpace() {#getspace}

Espace entre le CodeText et le code-barres en unités. Valeur par défaut : 2pt. Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### getTwoDDisplayText() {#gettwoddisplaytext}

Texte qui sera affiché à la place du codetext dans les codes-barres 2D. Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

Définit l'alignement du texte du code. Valeur par défaut : TextAlignment.CENTER.

### setColor() {#setcolor}

Spécifiez la couleur du CodeText affiché. Valeur par défaut : BLACK.

### setFont() {#setfont}

Spécifiez la police du CodeText affiché. Valeur par défaut : Arial 5pt regular. Ignoré si FontMode est défini sur FontMode.AUTO.

### setFontMode() {#setfontmode}

Spécifiez le FontMode. Si FontMode est défini sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension. Il est recommandé d'utiliser FontMode.AUTO notamment dans AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. Valeur par défaut : FontMode.AUTO.

### setLocation() {#setlocation}

Spécifiez l'emplacement du CodeText affiché, définissez CodeLocation.NONE pour masquer le CodeText. Valeur par défaut : CodeLocation.NONE.

### setNoWrap() {#setnowrap}

Spécifiez le retour à la ligne (sauts de ligne) dans le texte. Valeur par défaut : false.

### setSpace() {#setspace}

Espace entre le CodeText et le code-barres en unités. Valeur par défaut : 2pt. Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### setTwoDDisplayText() {#settwoddisplaytext}

Texte qui sera affiché à la place du codetext dans les codes-barres 2D. Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible de ces CodetextParameters.

**Returns:** A string that represents this CodetextParameters.
