---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros de generación de imágenes de códigos de barras."
type: docs
weight: 160
url: /es/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

Parámetros de generación de imágenes de códigos de barras.

```js
new BaseGenerationParameters()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | Color de fondo de la imagen del código de barras. Valor predeterminado: #FFFFFF |
| [getBarcode()](#getbarcode) | Obtiene los BarcodeParameters que contienen todas las propiedades del código de barras. |
| [getBorder()](#getborder) | Obtiene los BorderParameters que contienen todas las propiedades de configuración para el borde del código de barras. |
| [getCaptionAbove()](#getcaptionabove) | Subtítulo encima de la imagen BarCode. Ver CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | Subtítulo debajo de la imagen BarCode. Ver CaptionParameters. |
| [getImage()](#getimage) | Parámetros de imagen. Ver ImageParameters. |
| [getImageHeight()](#getimageheight) | Altura de la imagen BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getimagewidth) | Anchura de la imagen BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getresolution) | Obtiene la resolución de la imagen BarCode. Un valor para ambas dimensiones. Valor predeterminado: 96 dpi. El parámetro Resolution |
| [getRotationAngle()](#getrotationangle) | Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si Ro |
| [getUseAntiAlias()](#getuseantialias) | Obtiene un valor que indica si se utiliza el modo antialiasing para renderizar la imagen |
| [setAutoSizeMode()](#setautosizemode) | Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | Color de fondo de la imagen del código de barras. Valor predeterminado: #FFFFFF |
| [setImageHeight()](#setimageheight) | Altura de la imagen BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setImageWidth()](#setimagewidth) | Anchura de la imagen BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. |
| [setResolution()](#setresolution) | Establece la resolución de la imagen del código de barras. Un valor para ambas dimensiones. Valor predeterminado: 96 ppp. El parámetro Resolution |
| [setRotationAngle()](#setrotationangle) | Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si Ro |
| [setUseAntiAlias()](#setuseantialias) | Establece un valor que indica si se utiliza el modo antialiasing para renderizar la imagen |

### getAutoSizeMode() {#getautosizemode}

Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

Color de fondo de la imagen del código de barras. Valor predeterminado: #FFFFFF

### getBarcode() {#getbarcode}

Obtiene los BarcodeParameters que contienen todas las propiedades del código de barras.

### getBorder() {#getborder}

Obtiene los BorderParameters que contienen todas las propiedades de configuración para el borde del código de barras.

### getCaptionAbove() {#getcaptionabove}

Subtítulo encima de la imagen BarCode. Ver CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

Subtítulo debajo de la imagen BarCode. Ver CaptionParameters.

### getImage() {#getimage}

Parámetros de imagen. Ver ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

Altura de la imagen BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### getImageWidth() {#getimagewidth}

Anchura de la imagen BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### getResolution() {#getresolution}

Obtiene la resolución de la imagen del código de barras. Un valor para ambas dimensiones. Valor predeterminado: 96 ppp. El valor del parámetro Resolution es menor o igual a 0.

### getRotationAngle() {#getrotationangle}

Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen . Valor predeterminado: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

Obtiene un valor que indica si se utiliza el modo antialiasing para renderizar la imagen

### setAutoSizeMode() {#setautosizemode}

Especifica los diferentes tipos de modos de dimensionado automático. Valor predeterminado: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

Color de fondo de la imagen del código de barras. Valor predeterminado: #FFFFFF

### setImageHeight() {#setimageheight}

Altura de la imagen BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### setImageWidth() {#setimagewidth}

Anchura de la imagen BarCode cuando la propiedad AutoSizeMode está configurada a AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### setResolution() {#setresolution}

Establece la resolución de la imagen del código de barras. Un valor para ambas dimensiones. Valor predeterminado: 96 ppp. El valor del parámetro Resolution es menor o igual a 0.

### setRotationAngle() {#setrotationangle}

Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

Establece un valor que indica si se utiliza el modo antialiasing para renderizar la imagen
