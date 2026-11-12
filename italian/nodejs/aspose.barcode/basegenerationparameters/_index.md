---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Parametri di generazione dell'immagine Barcode."
type: docs
weight: 160
url: /it/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

Parametri di generazione dell'immagine Barcode.

```js
new BaseGenerationParameters()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | Colore di sfondo dell'immagine del codice a barre. Valore predefinito: #FFFFFF |
| [getBarcode()](#getbarcode) | Ottiene i BarcodeParameters che contengono tutte le proprietà del codice a barre. |
| [getBorder()](#getborder) | Ottiene i BorderParameters che contengono tutte le proprietà di configurazione per il bordo del codice a barre. |
| [getCaptionAbove()](#getcaptionabove) | Didascalia sopra l'immagine BarCode. Vedi CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | Didascalia sotto l'immagine BarCode. Vedi CaptionParameters. |
| [getImage()](#getimage) | Parametri immagine. Vedi ImageParameters. |
| [getImageHeight()](#getimageheight) | Altezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getimagewidth) | Larghezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getresolution) | Ottiene la risoluzione dell'immagine BarCode. Un valore per entrambe le dimensioni. Valore predefinito: 96 dpi. Il parametro Resolution |
| [getRotationAngle()](#getrotationangle) | Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione. If Ro |
| [getUseAntiAlias()](#getuseantialias) | Restituisce un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine |
| [setAutoSizeMode()](#setautosizemode) | Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | Colore di sfondo dell'immagine del codice a barre. Valore predefinito: #FFFFFF |
| [setImageHeight()](#setimageheight) | Altezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setImageWidth()](#setimagewidth) | Larghezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setResolution()](#setresolution) | Imposta la risoluzione dell'immagine BarCode. Un valore per entrambe le dimensioni. Valore predefinito: 96 dpi. Il parametro Resolution |
| [setRotationAngle()](#setrotationangle) | Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione. If Ro |
| [setUseAntiAlias()](#setuseantialias) | Imposta un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine |

### getAutoSizeMode() {#getautosizemode}

Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

Colore di sfondo dell'immagine del codice a barre. Valore predefinito: #FFFFFF

### getBarcode() {#getbarcode}

Ottiene i BarcodeParameters che contengono tutte le proprietà del codice a barre.

### getBorder() {#getborder}

Ottiene i BorderParameters che contengono tutte le proprietà di configurazione per il bordo del codice a barre.

### getCaptionAbove() {#getcaptionabove}

Didascalia sopra l'immagine BarCode. Vedi CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

Didascalia sotto l'immagine BarCode. Vedi CaptionParameters.

### getImage() {#getimage}

Parametri immagine. Vedi ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

Altezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### getImageWidth() {#getimagewidth}

Larghezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### getResolution() {#getresolution}

Restituisce la risoluzione dell'immagine BarCode. Un valore per entrambe le dimensioni. Valore predefinito: 96 dpi. Il valore del parametro Resolution è minore o uguale a 0.

### getRotationAngle() {#getrotationangle}

Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione. Se RotationAngle NON è uguale a 90, 180, 270 o 0, potrebbe aumentare la difficoltà per lo scanner nel leggere l'immagine . Valore predefinito: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

Restituisce un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine

### setAutoSizeMode() {#setautosizemode}

Specifica i diversi tipi di modalità di dimensionamento automatico. Valore predefinito: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

Colore di sfondo dell'immagine del codice a barre. Valore predefinito: #FFFFFF

### setImageHeight() {#setimageheight}

Altezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### setImageWidth() {#setimagewidth}

Larghezza dell'immagine BarCode quando la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### setResolution() {#setresolution}

Imposta la risoluzione dell'immagine BarCode. Un valore per entrambe le dimensioni. Valore predefinito: 96 dpi. Il valore del parametro Resolution è minore o uguale a 0.

### setRotationAngle() {#setrotationangle}

Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione. Se RotationAngle NON è uguale a 90, 180, 270 o 0, potrebbe aumentare la difficoltà per lo scanner nel leggere l'immagine. Valore predefinito: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

Imposta un valore che indica se è utilizzata la modalità anti-aliasing per renderizzare l'immagine
