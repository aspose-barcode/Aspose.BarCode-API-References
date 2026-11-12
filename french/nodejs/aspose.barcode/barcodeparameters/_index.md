---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Paramètres de génération de code-barres."
type: docs
weight: 140
url: /fr/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Paramètres de génération de code-barres.

```js
new BarcodeParameters()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | Paramètres du code-barres AustralianPost. |
| [getAztec()](#getaztec) | Paramètres Aztec. |
| [getBarColor()](#getbarcolor) | Couleur des barres. |
| [getBarHeight()](#getbarheight) | Hauteur des barres des codes-barres 1D en valeur d'unité. Ignorée si la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | Obtenir la valeur de réduction des barres utilisée pour compenser la diffusion d'encre lors de l'impression. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| [getCodabar()](#getcodabar) | Paramètres Codabar. |
| [getCodablock()](#getcodablock) | Paramètres Codablock. |
| [getCode16K()](#getcode16k) | Paramètres Code16K. |
| [getCode128()](#getcode128) | Paramètres Code128. |
| [getCodeTextParameters()](#getcodetextparameters) | Paramètres Codetext. |
| [getCoupon()](#getcoupon) | Paramètres du coupon. Utilisé pour UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Paramètres Databar. |
| [getDataMatrix()](#getdatamatrix) | Paramètres DataMatrix. |
| [getDotCode()](#getdotcode) | Paramètres DotCode. |
| [getEnableEscape()](#getenableescape) | Indique si le caractère \" est interprété comme caractère d'échappement dans la propriété CodeText. Utilisé pour Pdf417, DataMatrix, C |
| [getFilledBars()](#getfilledbars) | Obtient une valeur indiquant si les barres sont remplies. Seulement pour les codes-barres 1D. Valeur par défaut : true. |
| [getGS1CompositeBar()](#getgs1compositebar) | Paramètres du GS1 Composite Bar. Cet exemple montre comment créer et enregistrer une image GS1 Composite Bar. Notez que le codetext 1D |
| [getHanXin()](#gethanxin) | Paramètres HanXin. |
| [getITF()](#getitf) | Paramètres ITF. |
| [getMaxiCode()](#getmaxicode) | Paramètres MaxiCode. |
| [getPadding()](#getpadding) | Marges du code-barres. Valeur par défaut : 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | Paramètres PatchCode. |
| [getPdf417()](#getpdf417) | Paramètres PDF417. |
| [getPostal()](#getpostal) | Paramètres postaux. Utilisé pour Postnet, Planet. |
| [getQR()](#getqr) | Paramètres QR. |
| [getSupplement()](#getsupplement) | Paramètres de supplément. Utilisé pour Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Rapport Barres larges / Barres étroites. Valeur par défaut : 3, c’est‑à‑dire que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, |
| [getXDimension()](#getxdimension) | La x-dimension est la plus petite largeur de l’unité des barres ou espaces du BarCode. L’augmenter augmentera l’ensemble du code-barres i |
| [isChecksumEnabled()](#ischecksumenabled) | Activer le chiffre de contrôle lors de la génération des codes-barres 1D. La valeur par défaut est traitée comme Oui pour les symbologies qui doivent contenir un chiffre de contrôle, comme N |
| [setBarColor(value)](#setbarcolor) | Couleur des barres. |
| [setBarHeight()](#setbarheight) | Hauteur des barres des codes-barres 1D en valeur d'unité. Ignorée si la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | Définit la valeur de réduction des barres utilisée pour compenser la diffusion d'encre lors de l'impression. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| [setChecksumEnabled()](#setchecksumenabled) | Activer le chiffre de contrôle lors de la génération des codes-barres 1D. La valeur par défaut est traitée comme Oui pour les symbologies qui doivent contenir un chiffre de contrôle, comme N |
| [setEnableEscape()](#setenableescape) | Indique si le caractère \" est interprété comme caractère d'échappement dans la propriété CodeText. Utilisé pour Pdf417, DataMatrix, C |
| [setFilledBars()](#setfilledbars) | Définit une valeur indiquant si les barres sont remplies. Seulement pour les codes-barres 1D. Valeur par défaut : true. |
| [setGS1CompositeBar()](#setgs1compositebar) | Paramètres du GS1 Composite Bar. Cet exemple montre comment créer et enregistrer une image GS1 Composite Bar. Notez que le codetext 1D |
| [setPadding()](#setpadding) | Marges du code-barres. Valeur par défaut : 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Rapport Barres larges / Barres étroites. Valeur par défaut : 3, c’est‑à‑dire que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, P |
| [setXDimension()](#setxdimension) | La x-dimension est la plus petite largeur de l’unité des barres ou espaces du BarCode. L’augmenter augmentera l’ensemble du code-barres i |

### getAustralianPost() {#getaustralianpost}

Paramètres du code-barres AustralianPost.

### getAztec() {#getaztec}

Paramètres Aztec.

### getBarColor() {#getbarcolor}

Couleur des barres.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Hauteur des barres des codes-barres 1D en valeur d'unité. Ignorée si la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Obtenir la valeur de réduction des barres utilisée pour compenser la diffusion d'encre lors de l'impression.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128.

### getCodabar() {#getcodabar}

Paramètres Codabar.

### getCodablock() {#getcodablock}

Paramètres Codablock.

### getCode16K() {#getcode16k}

Paramètres Code16K.

### getCode128() {#getcode128}

Paramètres Code128.

### getCodeTextParameters() {#getcodetextparameters}

Paramètres Codetext.

### getCoupon() {#getcoupon}

Paramètres du coupon. Utilisé pour UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Paramètres Databar.

### getDataMatrix() {#getdatamatrix}

Paramètres DataMatrix.

### getDotCode() {#getdotcode}

Paramètres DotCode.

### getEnableEscape() {#getenableescape}

Indique si le caractère \" est interprété comme caractère d'échappement dans la propriété CodeText. Utilisé pour Pdf417, DataMatrix, Code128 uniquement. Si EnableEscape est vrai, \" sera interprété comme un caractère d'échappement spécial. Sinon, \" agit comme des caractères normaux. Aspose.BarCode prend en charge la saisie de codes ASCII décimaux et de mnémoniques pour les caractères de contrôle ASCII. Par exemple, \\013 et \\\\CR représentent CR.

### getFilledBars() {#getfilledbars}

Obtient une valeur indiquant si les barres sont remplies. Seulement pour les codes-barres 1D. Valeur par défaut : true.

### getGS1CompositeBar() {#getgs1compositebar}

Paramètres du GS1 Composite Bar. Cet exemple montre comment créer et enregistrer une image GS1 Composite Bar. Notez que le codetext 1D et le codetext 2D sont séparés par le symbole '/'

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

Paramètres HanXin.

### getITF() {#getitf}

Paramètres ITF.

### getMaxiCode() {#getmaxicode}

Paramètres MaxiCode.

### getPadding() {#getpadding}

Marges du code-barres. Valeur par défaut : 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

Paramètres PatchCode.

### getPdf417() {#getpdf417}

Paramètres PDF417.

### getPostal() {#getpostal}

Paramètres postaux. Utilisé pour Postnet, Planet.

### getQR() {#getqr}

Paramètres QR.

### getSupplement() {#getsupplement}

Paramètres de supplément. Utilisé pour Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Rapport Barres larges / Barres étroites. Valeur par défaut : 3, c’est‑à‑dit que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. La valeur du paramètre WideNarrowRatio est inférieure ou égale à 0.

### getXDimension() {#getxdimension}

La x-dimension est la plus petite largeur de l’unité des barres ou espaces du BarCode. L’augmenter augmentera la largeur de toute l’image du code-barres. Ignorée si la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Activer la somme de contrôle lors de la génération des codes-barres 1D. La valeur par défaut est considérée comme Oui pour les symbologies qui doivent contenir une somme de contrôle, et Non là où la somme de contrôle n'est possible que facultativement. La somme de contrôle est possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. La somme de contrôle est toujours utilisée : le reste des symbologies

### setBarColor(value) {#setbarcolor}

Couleur des barres.

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | String | pour la couleur de la barre Valeur par défaut : #000000. |

### setBarHeight() {#setbarheight}

Hauteur des barres des codes-barres 1D en valeur d'unité. Ignorée si la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Définit la valeur de réduction des barres utilisée pour compenser la diffusion d'encre lors de l'impression.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128.

### setChecksumEnabled() {#setchecksumenabled}

Activer la somme de contrôle lors de la génération des codes-barres 1D. La valeur par défaut est considérée comme Oui pour les symbologies qui doivent contenir une somme de contrôle, et Non là où la somme de contrôle n'est possible que facultativement. La somme de contrôle est possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. La somme de contrôle est toujours utilisée : le reste des symbologies

### setEnableEscape() {#setenableescape}

Indique si le caractère "\\" est interprété comme caractère d'échappement dans la propriété CodeText. Utilisé uniquement pour Pdf417, DataMatrix, Code128. Si EnableEscape est vrai, "\\" sera interprété comme un caractère d'échappement spécial. Sinon, "\\" agit comme un caractère normal. Aspose.BarCode prend en charge le code ascii décimal et le mnémonique pour les caractères de contrôle ASCII. Par exemple, \\013 et \\\\CR représentent CR.

### setFilledBars() {#setfilledbars}

Définit une valeur indiquant si les barres sont remplies. Seulement pour les codes-barres 1D. Valeur par défaut : true.

### setGS1CompositeBar() {#setgs1compositebar}

Paramètres du GS1 Composite Bar. Cet exemple montre comment créer et enregistrer une image GS1 Composite Bar. Notez que le codetext 1D et le codetext 2D sont séparés par le symbole '/'

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

Marges du code-barres. Valeur par défaut : 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Ratio des barres larges aux barres étroites. Valeur par défaut : 3, c’est‑à‑dire que les barres larges sont trois fois plus larges que les barres étroites. Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. La valeur du paramètre WideNarrowRatio doit être inférieure ou égale à 0.

### setXDimension() {#setxdimension}

La x-dimension est la plus petite largeur de l’unité des barres ou espaces du BarCode. L’augmenter augmentera la largeur de toute l’image du code-barres. Ignorée si la propriété AutoSizeMode est définie sur AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
