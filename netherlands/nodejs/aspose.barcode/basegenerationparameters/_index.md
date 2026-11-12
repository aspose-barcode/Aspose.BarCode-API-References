---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Barcode-beeldgeneratieparameters."
type: docs
weight: 160
url: /nl/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

Barcode-beeldgeneratieparameters.

```js
new BaseGenerationParameters()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: #FFFFFF |
| [getBarcode()](#getbarcode) | Haalt de BarcodeParameters op die alle barcode‑eigenschappen bevat. |
| [getBorder()](#getborder) | Haalt de BorderParameters op die alle configuratie‑eigenschappen voor de barcode‑rand bevat. |
| [getCaptionAbove()](#getcaptionabove) | Bijschrift boven de BarCode-afbeelding. Zie CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | Bijschrift onder de BarCode-afbeelding. Zie CaptionParameters. |
| [getImage()](#getimage) | Afbeeldingsparameters. Zie ImageParameters. |
| [getImageHeight()](#getimageheight) | BarCode-afbeeldingshoogte wanneer de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getimagewidth) | BarCode-afbeeldingsbreedte wanneer de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getresolution) | Haalt de resolutie van de BarCode-afbeelding op. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. De Resolution‑parameter |
| [getRotationAngle()](#getrotationangle) | BarCode-afbeeldingsrotatiehoek, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als Ro |
| [getUseAntiAlias()](#getuseantialias) | Haalt een waarde op die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven |
| [setAutoSizeMode()](#setautosizemode) | Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: #FFFFFF |
| [setImageHeight()](#setimageheight) | BarCode-afbeeldingshoogte wanneer de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. |
| [setImageWidth()](#setimagewidth) | BarCode-afbeeldingsbreedte wanneer de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. |
| [setResolution()](#setresolution) | Stelt de resolutie van de BarCode-afbeelding in. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. De Resolution-parameter |
| [setRotationAngle()](#setrotationangle) | BarCode-afbeeldingsrotatiehoek, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als Ro |
| [setUseAntiAlias()](#setuseantialias) | Stelt een waarde in die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven |

### getAutoSizeMode() {#getautosizemode}

Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: #FFFFFF

### getBarcode() {#getbarcode}

Haalt de BarcodeParameters op die alle barcode‑eigenschappen bevat.

### getBorder() {#getborder}

Haalt de BorderParameters op die alle configuratie‑eigenschappen voor de barcode‑rand bevat.

### getCaptionAbove() {#getcaptionabove}

Bijschrift boven de BarCode-afbeelding. Zie CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

Bijschrift onder de BarCode-afbeelding. Zie CaptionParameters.

### getImage() {#getimage}

Afbeeldingsparameters. Zie ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

BarCode-afbeeldingshoogte wanneer de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

### getImageWidth() {#getimagewidth}

BarCode-afbeeldingsbreedte wanneer de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

### getResolution() {#getresolution}

Haalt de resolutie van de BarCode-afbeelding op. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. De Resolution-parameterwaarde is kleiner dan of gelijk aan 0.

### getRotationAngle() {#getrotationangle}

BarCode-afbeeldingsrotatiehoek, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen vergroten. Standaardwaarde: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

Haalt een waarde op die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven

### setAutoSizeMode() {#setautosizemode}

Specificeert de verschillende typen automatische formaatmodi. Standaardwaarde: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

Achtergrondkleur van de barcode-afbeelding. Standaardwaarde: #FFFFFF

### setImageHeight() {#setimageheight}

BarCode-afbeeldingshoogte wanneer de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

### setImageWidth() {#setimagewidth}

BarCode-afbeeldingsbreedte wanneer de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

### setResolution() {#setresolution}

Stelt de resolutie van de BarCode-afbeelding in. Eén waarde voor beide dimensies. Standaardwaarde: 96 dpi. De Resolution-parameterwaarde is kleiner dan of gelijk aan 0.

### setRotationAngle() {#setrotationangle}

BarCode-afbeeldingsrotatiehoek, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen vergroten. Standaardwaarde: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

Stelt een waarde in die aangeeft of anti-aliasing-modus wordt gebruikt om de afbeelding weer te geven
