---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras."
type: docs
weight: 90
url: /es/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader encapsula una imagen que puede contener uno o varios códigos de barras, y luego puede ejecutar la operación ReadBarCodes para detectar códigos de barras.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Inicializa una nueva instancia de BarCodeReader

| Parámetro | Descripción |
| --- | --- |
| imagen | codificado como cadena base64 o ruta a la imagen |
| áreas | matriz de objetos del tipo Rectangle |
| decodeTypes | la matriz de objetos por DecodeType |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Exporta las propiedades de BarCode al archivo xml especificado |
| [containsAny()](#containsany) | Determina si alguno de los tipos de decodificación proporcionados está incluido en |
| [exportToXml(xmlFile)](#exporttoxml) | Exporta las propiedades de BarCode al archivo xml especificado |
| [getBarCodeReadType()](#getbarcodereadtype) | Obtiene el tipo de decodificación del código de barras de entrada |
| [getBarcodeSettings()](#getbarcodesettings) | Los principales parámetros de decodificación de BarCode. Contiene parámetros que influyen en los datos reconocidos. |
| [getFoundBarCodes()](#getfoundbarcodes) | Obtiene la matriz BarCodeResult reconocida |
| [getFoundCount()](#getfoundcount) | Obtiene el recuento de códigos de barras reconocidos |
| [getQualitySettings()](#getqualitysettings) | QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante em |
| [getTimeout()](#gettimeout) | Obtiene el tiempo de espera del proceso de reconocimiento en milisegundos. |
| [readBarCodes()](#readbarcodes) | Lee BarCodeResult de la imagen. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Establece la imagen bitmap y las áreas para el reconocimiento. Debe llamarse antes del método ReadBarCodes(). |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Establece la matriz de tipo SingleDecodeType para el reconocimiento. Debe llamarse antes del método readBarCodes(). |
| [setQualitySettings()](#setqualitysettings) | QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante em |
| [setTimeout(value)](#settimeout) | Establece el tiempo de espera del proceso de reconocimiento en milisegundos. |

### importFromXml(xmlFile) (static) {#importfromxml}

Exporta las propiedades de BarCode al archivo xml especificado

| Parámetro | Descripción |
| --- | --- |
| xmlFile | El nombre del archivo |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Determina si alguno de los tipos de decodificación proporcionados está incluido en

| Parámetro | Descripción |
| --- | --- |
| ...decodeTypes | Tipos a verificar. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Exporta las propiedades de BarCode al archivo xml especificado

| Parámetro | Descripción |
| --- | --- |
| xmlFile | El nombre del archivo |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Obtiene el tipo de decodificación del código de barras de entrada

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

Los principales parámetros de decodificación de BarCode. Contiene parámetros que influyen en los datos reconocidos.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Obtiene la matriz BarCodeResult reconocida

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

Obtiene el recuento de códigos de barras reconocidos

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

Obtiene el tiempo de espera del proceso de reconocimiento en milisegundos.

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

Lee BarCodeResult de la imagen.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

Establece la imagen bitmap y las áreas para el reconocimiento. Debe llamarse antes del método ReadBarCodes().

| Parámetro | Descripción |
| --- | --- |
| imageResource | La imagen para el reconocimiento. |
| áreas | lista de áreas para el reconocimiento |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

Establece la matriz de tipo SingleDecodeType para el reconocimiento. Debe llamarse antes del método readBarCodes().

| Parámetro | Descripción |
| --- | --- |
| types | La matriz de tipo SingleDecodeType para leer. |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.

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

### setTimeout(value) {#settimeout}

Establece el tiempo de espera del proceso de reconocimiento en milisegundos.

| Parámetro | Descripción |
| --- | --- |
| valor | El tiempo de espera. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
