---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Paramètres de génération d'image de code-barres."
type: docs
weight: 160
url: /fr/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

Paramètres de génération d'image de code-barres.

```js
new BaseGenerationParameters()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | Spécifie les différents types de modes de dimensionnement automatique. Valeur par défaut : AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | Couleur d'arrière-plan de l'image du code-barres. Valeur par défaut : #FFFFFF |
| [getBarcode()](#getbarcode) | Obtient les BarcodeParameters qui contiennent toutes les propriétés du code-barres. |
| [getBorder()](#getborder) | Obtient les BorderParameters qui contiennent toutes les propriétés de configuration pour la bordure du code-barres. |
| [getCaptionAbove()](#getcaptionabove) | Légende au-dessus de l'image BarCode. Voir CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | Légende en dessous de l'image BarCode. Voir CaptionParameters. |
| [getImage()](#getimage) | Paramètres d'image. Voir ImageParameters. |
| [getImageHeight()](#getimageheight) | Hauteur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getimagewidth) | Largeur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getresolution) | Obtient la résolution de l'image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi. Le paramètre Resolution |
| [getRotationAngle()](#getrotationangle) | Angle de rotation de l'image BarCode, mesuré en degrés, par ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si Ro |
| [getUseAntiAlias()](#getuseantialias) | Obtient une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image |
| [setAutoSizeMode()](#setautosizemode) | Spécifie les différents types de modes de dimensionnement automatique. Valeur par défaut : AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | Couleur d'arrière-plan de l'image du code-barres. Valeur par défaut : #FFFFFF |
| [setImageHeight()](#setimageheight) | Hauteur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. |
| [setImageWidth()](#setimagewidth) | Largeur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. |
| [setResolution()](#setresolution) | Définit la résolution de l'image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi. Le paramètre Resolution |
| [setRotationAngle()](#setrotationangle) | Angle de rotation de l'image BarCode, mesuré en degrés, par ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si Ro |
| [setUseAntiAlias()](#setuseantialias) | Définit une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image |

### getAutoSizeMode() {#getautosizemode}

Spécifie les différents types de modes de dimensionnement automatique. Valeur par défaut : AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

Couleur d'arrière-plan de l'image du code-barres. Valeur par défaut : #FFFFFF

### getBarcode() {#getbarcode}

Obtient les BarcodeParameters qui contiennent toutes les propriétés du code-barres.

### getBorder() {#getborder}

Obtient les BorderParameters qui contiennent toutes les propriétés de configuration pour la bordure du code-barres.

### getCaptionAbove() {#getcaptionabove}

Légende au-dessus de l'image BarCode. Voir CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

Légende en dessous de l'image BarCode. Voir CaptionParameters.

### getImage() {#getimage}

Paramètres d'image. Voir ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

Hauteur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

### getImageWidth() {#getimagewidth}

Largeur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

### getResolution() {#getresolution}

Obtient la résolution de l'image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi. La valeur du paramètre Resolution est inférieure ou égale à 0.

### getRotationAngle() {#getrotationangle}

Angle de rotation de l'image BarCode, mesuré en degrés, par ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si RotationAngle n'est PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image . Valeur par défaut : 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

Obtient une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image

### setAutoSizeMode() {#setautosizemode}

Spécifie les différents types de modes de dimensionnement automatique. Valeur par défaut : AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

Couleur d'arrière-plan de l'image du code-barres. Valeur par défaut : #FFFFFF

### setImageHeight() {#setimageheight}

Hauteur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

### setImageWidth() {#setimagewidth}

Largeur de l'image BarCode lorsque la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

### setResolution() {#setresolution}

Définit la résolution de l'image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi. La valeur du paramètre Resolution est inférieure ou égale à 0.

### setRotationAngle() {#setrotationangle}

Angle de rotation de l'image BarCode, mesuré en degrés, par ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si RotationAngle n'est PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image. Valeur par défaut : 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

Définit une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image
