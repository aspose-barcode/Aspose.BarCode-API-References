---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento."
type: docs
weight: 860
url: /es/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | Preset de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo. |
| [getHighQuality()](#gethighquality) *(static)* | Preset de calidad de reconocimiento HighQuality. Este preset está desarrollado para códigos de barras de baja calidad. |
| [getMaxQuality()](#getmaxquality) *(static)* | Preset de calidad de reconocimiento MaxQuality. Este preset está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos. |
| [getNormalQuality()](#getnormalquality) *(static)* | Preset de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras. |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Permite al motor reconocer códigos de barras que tienen checksum incorrecto o valores incorrectos. El modo puede usarse para reconocer códigos dañados. |
| [getBarcodeQuality()](#getbarcodequality) | Modo que permite a los métodos reconocer elementos de código de barras con la calidad seleccionada. Elemento de código de barras con calidad inferior r |
| [getComplexBackground()](#getcomplexbackground) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes en color. |
| [getDeconvolution()](#getdeconvolution) | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente la deconvolución es una función |
| [getInverseImage()](#getinverseimage) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| [getMinimalXDimension()](#getminimalxdimension) | Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Permite al motor reconocer códigos de barras que tienen checksum incorrecto o valores incorrectos. El modo puede usarse para reconocer códigos dañados. |
| [setBarcodeQuality(value)](#setbarcodequality) | Modo que permite a los métodos reconocer elementos de código de barras con la calidad seleccionada. Elemento de código de barras con calidad inferior r |
| [setComplexBackground(value)](#setcomplexbackground) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes en color. |
| [setDeconvolution(value)](#setdeconvolution) | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente la deconvolución es una función |
| [setInverseImage(value)](#setinverseimage) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| [setMinimalXDimension(value)](#setminimalxdimension) | Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |

### getHighPerformance() (static) {#gethighperformance}

Preset de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

Preset de calidad de reconocimiento HighQuality. Este preset está desarrollado para códigos de barras de baja calidad.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos. Este ejemplo muestra cómo usar el modo MaxQuality reader = new BarCodeReader(\"test.png\"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Valor: preajuste de calidad de reconocimiento MaxQuality.

### getNormalQuality() (static) {#getnormalquality}

Preset de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Permite al motor reconocer códigos de barras que tienen checksum incorrecto o valores incorrectos. El modo puede usarse para reconocer códigos de barras dañados con texto incorrecto.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Modo que habilita métodos para reconocer elementos del código de barras con la calidad seleccionada. Un elemento del código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes en color.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, durante la captura de la imagen con la cámara. Como no podemos detectar la función de la imagen que corrompe la imagen, debemos comprobar las funciones más conocidas como sharp o morfología matemática.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Permite al motor reconocer códigos de barras que tienen checksum incorrecto o valores incorrectos. El modo puede usarse para reconocer códigos de barras dañados con texto incorrecto.

| Parámetro | Descripción |
| --- | --- |
| valor | Permite al motor reconocer códigos de barras incorrectos. |

### setBarcodeQuality(value) {#setbarcodequality}

Modo que habilita métodos para reconocer elementos del código de barras con la calidad seleccionada. Un elemento del código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento.

| Parámetro | Descripción |
| --- | --- |
| valor | Modo que habilita métodos para reconocer elementos del código de barras con la calidad seleccionada. |

### setComplexBackground(value) {#setcomplexbackground}

Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes en color.

| Parámetro | Descripción |
| --- | --- |
| valor | Reconocimiento adicional de códigos de barras de color en imágenes a color. |

### setDeconvolution(value) {#setdeconvolution}

Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, durante la captura de la imagen con la cámara. Como no podemos detectar la función de la imagen que corrompe la imagen, debemos comprobar las funciones más conocidas como sharp o morfología matemática.

| Parámetro | Descripción |
| --- | --- |
| valor | Modo de deconvolución que define el nivel de degradación de la imagen. |

### setInverseImage(value) {#setinverseimage}

Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia).

| Parámetro | Descripción |
| --- | --- |
| valor | Reconocimiento adicional de códigos de barras en imágenes con colores inversos |

### setMinimalXDimension(value) {#setminimalxdimension}

Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension.

| Parámetro | Descripción |
| --- | --- |
| valor | Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra.

| Parámetro | Descripción |
| --- | --- |
| valor | (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |
