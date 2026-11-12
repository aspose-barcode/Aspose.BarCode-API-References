---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance."
type: docs
weight: 860
url: /fr/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings à l'aide de préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxBarCodes ou vous pouvez configurer manuellement les options séparées. La valeur par défaut de QualitySettings est NormalQuality.

```js
new QualitySettings()
```

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | Préréglage de qualité de reconnaissance HighPerformance. Les codes-barres de haute qualité sont bien reconnus dans ce mode. |
| [getHighQuality()](#gethighquality) *(static)* | Préréglage de qualité de reconnaissance HighQuality. Ce préréglage est conçu pour les codes-barres de faible qualité. |
| [getMaxQuality()](#getmaxquality) *(static)* | Préréglage de qualité de reconnaissance MaxQuality. Ce préréglage est développé pour reconnaître tous les codes-barres possibles, même les barcodes incorrects |
| [getNormalQuality()](#getnormalquality) *(static)* | Préréglage de qualité de reconnaissance NormalQuality. Convient à la plupart des codes-barres |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Permet au moteur de reconnaître les codes-barres qui ont une somme de contrôle incorrecte ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes-barres endommagés |
| [getBarcodeQuality()](#getbarcodequality) | Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée. Élément de code-barres de qualité inférieure r |
| [getComplexBackground()](#getcomplexbackground) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur les images couleur. |
| [getDeconvolution()](#getdeconvolution) | Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction |
| [getInverseImage()](#getinverseimage) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images aux couleurs inversées (luminance). |
| [getMinimalXDimension()](#getminimalxdimension) | Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Permet au moteur de reconnaître les codes-barres qui ont une somme de contrôle incorrecte ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes-barres endommagés |
| [setBarcodeQuality(value)](#setbarcodequality) | Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée. Élément de code-barres de qualité inférieure r |
| [setComplexBackground(value)](#setcomplexbackground) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur les images couleur. |
| [setDeconvolution(value)](#setdeconvolution) | Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction |
| [setInverseImage(value)](#setinverseimage) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images aux couleurs inversées (luminance). |
| [setMinimalXDimension(value)](#setminimalxdimension) | Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre. |

### getHighPerformance() (static) {#gethighperformance}

Préréglage de qualité de reconnaissance HighPerformance. Les codes-barres de haute qualité sont bien reconnus dans ce mode.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

Préréglage de qualité de reconnaissance HighQuality. Ce préréglage est conçu pour les codes-barres de faible qualité.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

Préréglage de qualité de reconnaissance MaxQuality. Ce préréglage est développé pour reconnaître tous les codes-barres possibles, même les codes-barres incorrects. Cet exemple montre comment utiliser le mode MaxQuality reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Valeur : préréglage de qualité de reconnaissance MaxQuality.

### getNormalQuality() (static) {#getnormalquality}

Préréglage de qualité de reconnaissance NormalQuality. Convient à la plupart des codes-barres

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Permet au moteur de reconnaître les codes-barres qui ont une somme de contrôle incorrecte ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes-barres endommagés avec un texte incorrect.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Mode qui active les méthodes permettant de reconnaître les éléments du code-barres avec la qualité sélectionnée. Un élément de code-barres de qualité inférieure nécessite des méthodes plus intensives, ce qui ralentit la reconnaissance.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur les images couleur.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction qui peut restaurer une image dégradée (convoluée) par n'importe quelle fonction naturelle comme le flou, lors de la capture de l'image par la caméra. Comme nous ne pouvons pas détecter la fonction qui corrompt l'image, nous devons examiner les fonctions les mieux connues comme le net ou la morphologie mathématique.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images aux couleurs inversées (luminance).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Permet au moteur de reconnaître les codes-barres qui ont une somme de contrôle incorrecte ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes-barres endommagés avec un texte incorrect.

| Paramètre | Description |
| --- | --- |
| valeur | Permet au moteur de reconnaître les codes-barres incorrects. |

### setBarcodeQuality(value) {#setbarcodequality}

Mode qui active les méthodes permettant de reconnaître les éléments du code-barres avec la qualité sélectionnée. Un élément de code-barres de qualité inférieure nécessite des méthodes plus intensives, ce qui ralentit la reconnaissance.

| Paramètre | Description |
| --- | --- |
| valeur | Mode qui active les méthodes permettant de reconnaître les éléments du code-barres avec la qualité sélectionnée. |

### setComplexBackground(value) {#setcomplexbackground}

Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur les images couleur.

| Paramètre | Description |
| --- | --- |
| valeur | Reconnaissance supplémentaire des codes-barres couleur sur des images couleur. |

### setDeconvolution(value) {#setdeconvolution}

Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction qui peut restaurer une image dégradée (convoluée) par n'importe quelle fonction naturelle comme le flou, lors de la capture de l'image par la caméra. Comme nous ne pouvons pas détecter la fonction qui corrompt l'image, nous devons examiner les fonctions les mieux connues comme le net ou la morphologie mathématique.

| Paramètre | Description |
| --- | --- |
| valeur | Mode de déconvolution qui définit le niveau de dégradation de l'image. |

### setInverseImage(value) {#setinverseimage}

Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images aux couleurs inversées (luminance).

| Paramètre | Description |
| --- | --- |
| valeur | Reconnaissance supplémentaire des codes-barres sur des images aux couleurs inversées |

### setMinimalXDimension(value) {#setminimalxdimension}

Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension.

| Paramètre | Description |
| --- | --- |
| valeur | Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre.

| Paramètre | Description |
| --- | --- |
| valeur | (de 1 à l'infini) de l'élément minimal du code-barres : cellule de matrice ou barre. |
