---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Parameter zur Barcode-Bilderzeugung."
type: docs
weight: 160
url: /de/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

Parameter zur Barcode-Bilderzeugung.

```js
new BaseGenerationParameters()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | Gibt die verschiedenen Typen von automatischen Größenmodi an. Standardwert: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | Hintergrundfarbe des Barcode‑Bildes. Standardwert: #FFFFFF |
| [getBarcode()](#getbarcode) | Ruft die BarcodeParameters ab, die alle Barcode‑Eigenschaften enthalten. |
| [getBorder()](#getborder) | Ruft die BorderParameters ab, die alle Konfigurationseigenschaften für den Barcode‑Rand enthalten. |
| [getCaptionAbove()](#getcaptionabove) | Beschriftung über dem BarCode‑Bild. Siehe CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | Beschriftung unter dem BarCode‑Bild. Siehe CaptionParameters. |
| [getImage()](#getimage) | Bildparameter. Siehe ImageParameters. |
| [getImageHeight()](#getimageheight) | BarCode‑Bildhöhe, wenn die AutoSizeMode‑Eigenschaft auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist. |
| [getImageWidth()](#getimagewidth) | BarCode‑Bildbreite, wenn die AutoSizeMode‑Eigenschaft auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist. |
| [getResolution()](#getresolution) | Ruft die Auflösung des BarCode‑Bildes ab. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. Der Resolution‑Parameter |
| [getRotationAngle()](#getrotationangle) | BarCode-Bilddrehwinkel, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn Ro |
| [getUseAntiAlias()](#getuseantialias) | Gibt einen Wert zurück, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird |
| [setAutoSizeMode()](#setautosizemode) | Gibt die verschiedenen Typen von automatischen Größenmodi an. Standardwert: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | Hintergrundfarbe des Barcode‑Bildes. Standardwert: #FFFFFF |
| [setImageHeight()](#setimageheight) | BarCode‑Bildhöhe, wenn die AutoSizeMode‑Eigenschaft auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist. |
| [setImageWidth()](#setimagewidth) | BarCode‑Bildbreite, wenn die AutoSizeMode‑Eigenschaft auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist. |
| [setResolution()](#setresolution) | Legt die Auflösung des BarCode-Bildes fest. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. Der Resolution-Parameter |
| [setRotationAngle()](#setrotationangle) | BarCode-Bilddrehwinkel, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn Ro |
| [setUseAntiAlias()](#setuseantialias) | Legt einen Wert fest, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird |

### getAutoSizeMode() {#getautosizemode}

Gibt die verschiedenen Typen von automatischen Größenmodi an. Standardwert: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

Hintergrundfarbe des Barcode‑Bildes. Standardwert: #FFFFFF

### getBarcode() {#getbarcode}

Ruft die BarcodeParameters ab, die alle Barcode‑Eigenschaften enthalten.

### getBorder() {#getborder}

Ruft die BorderParameters ab, die alle Konfigurationseigenschaften für den Barcode‑Rand enthalten.

### getCaptionAbove() {#getcaptionabove}

Beschriftung über dem BarCode‑Bild. Siehe CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

Beschriftung unter dem BarCode‑Bild. Siehe CaptionParameters.

### getImage() {#getimage}

Bildparameter. Siehe ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

BarCode‑Bildhöhe, wenn die AutoSizeMode‑Eigenschaft auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

### getImageWidth() {#getimagewidth}

BarCode‑Bildbreite, wenn die AutoSizeMode‑Eigenschaft auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

### getResolution() {#getresolution}

Gibt die Auflösung des BarCode-Bildes zurück. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. Der Wert des Resolution-Parameters ist kleiner oder gleich 0.

### getRotationAngle() {#getrotationangle}

BarCode-Bilddrehwinkel, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

Gibt einen Wert zurück, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird

### setAutoSizeMode() {#setautosizemode}

Gibt die verschiedenen Typen von automatischen Größenmodi an. Standardwert: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

Hintergrundfarbe des Barcode‑Bildes. Standardwert: #FFFFFF

### setImageHeight() {#setimageheight}

BarCode‑Bildhöhe, wenn die AutoSizeMode‑Eigenschaft auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

### setImageWidth() {#setimagewidth}

BarCode‑Bildbreite, wenn die AutoSizeMode‑Eigenschaft auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

### setResolution() {#setresolution}

Legt die Auflösung des BarCode-Bildes fest. Ein Wert für beide Dimensionen. Standardwert: 96 dpi. Der Wert des Resolution-Parameters ist kleiner oder gleich 0.

### setRotationAngle() {#setrotationangle}

BarCode-Bilddrehwinkel, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

Legt einen Wert fest, der angibt, ob der Anti-Aliasing-Modus zum Rendern des Bildes verwendet wird
