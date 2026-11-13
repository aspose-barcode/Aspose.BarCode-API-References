---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Parametrar för generering av streckkodsbilder."
type: docs
weight: 160
url: /sv/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

Parametrar för generering av streckkodsbilder.

```js
new BaseGenerationParameters()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | Anger de olika typerna av automatiska storleksinställningslägen. Standardvärde: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | Bakgrundsfärg för streckkodbilden. Standardvärde: #FFFFFF |
| [getBarcode()](#getbarcode) | Hämtar BarcodeParameters som innehåller alla streckkodsegenskaper. |
| [getBorder()](#getborder) | Hämtar BorderParameters som innehåller alla konfigurationsegenskaper för streckkodens kant. |
| [getCaptionAbove()](#getcaptionabove) | Rubrik ovanför BarCode-bilden. Se CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | Rubrik under BarCode-bilden. Se CaptionParameters. |
| [getImage()](#getimage) | Bildparametrar. Se ImageParameters. |
| [getImageHeight()](#getimageheight) | BarCode-bildens höjd när AutoSizeMode-egenskapen är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getimagewidth) | BarCode-bildens bredd när AutoSizeMode-egenskapen är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getresolution) | Hämtar upplösningen för BarCode-bilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi. Upplösningsparametern |
| [getRotationAngle()](#getrotationangle) | BarCode-bildens rotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om Ro |
| [getUseAntiAlias()](#getuseantialias) | Hämtar ett värde som indikerar om anti-aliasing-läge används för att rendera bilden |
| [setAutoSizeMode()](#setautosizemode) | Anger de olika typerna av automatiska storleksinställningslägen. Standardvärde: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | Bakgrundsfärg för streckkodbilden. Standardvärde: #FFFFFF |
| [setImageHeight()](#setimageheight) | BarCode-bildens höjd när AutoSizeMode-egenskapen är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. |
| [setImageWidth()](#setimagewidth) | BarCode-bildens bredd när AutoSizeMode-egenskapen är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. |
| [setResolution()](#setresolution) | Ställer in upplösningen för BarCode-bilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi. Upplösningsparametern |
| [setRotationAngle()](#setrotationangle) | BarCode-bildens rotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om Ro |
| [setUseAntiAlias()](#setuseantialias) | Ställer in ett värde som indikerar om anti-aliasing-läge används för att rendera bilden |

### getAutoSizeMode() {#getautosizemode}

Anger de olika typerna av automatiska storleksinställningslägen. Standardvärde: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

Bakgrundsfärg för streckkodbilden. Standardvärde: #FFFFFF

### getBarcode() {#getbarcode}

Hämtar BarcodeParameters som innehåller alla streckkodsegenskaper.

### getBorder() {#getborder}

Hämtar BorderParameters som innehåller alla konfigurationsegenskaper för streckkodens kant.

### getCaptionAbove() {#getcaptionabove}

Rubrik ovanför BarCode-bilden. Se CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

Rubrik under BarCode-bilden. Se CaptionParameters.

### getImage() {#getimage}

Bildparametrar. Se ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

BarCode-bildens höjd när AutoSizeMode-egenskapen är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

### getImageWidth() {#getimagewidth}

BarCode-bildens bredd när AutoSizeMode-egenskapen är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

### getResolution() {#getresolution}

Hämtar upplösningen för BarCode-bilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi. Upplösningsparametervärdet är mindre än eller lika med 0.

### getRotationAngle() {#getrotationangle}

BarCode-bildens rotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0 kan det öka svårigheten för skannern att läsa bilden. Standardvärde: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

Hämtar ett värde som indikerar om anti-aliasing-läge används för att rendera bilden

### setAutoSizeMode() {#setautosizemode}

Anger de olika typerna av automatiska storleksinställningslägen. Standardvärde: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

Bakgrundsfärg för streckkodbilden. Standardvärde: #FFFFFF

### setImageHeight() {#setimageheight}

BarCode-bildens höjd när AutoSizeMode-egenskapen är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

### setImageWidth() {#setimagewidth}

BarCode-bildens bredd när AutoSizeMode-egenskapen är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

### setResolution() {#setresolution}

Ställer in upplösningen för BarCode-bilden. Ett värde för båda dimensionerna. Standardvärde: 96 dpi. Upplösningsparametervärdet är mindre än eller lika med 0.

### setRotationAngle() {#setrotationangle}

BarCode-bildens rotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0 kan det öka svårigheten för skannern att läsa bilden. Standardvärde: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

Ställer in ett värde som indikerar om anti-aliasing-läge används för att rendera bilden
