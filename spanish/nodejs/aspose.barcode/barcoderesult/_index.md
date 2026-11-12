---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena datos de códigos de barras reconocidos como tipo SingleDecodeType, texto de código `string`, región BarCodeRegionParameters y otros parámetros"
type: docs
weight: 110
url: /es/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Almacena datos de códigos de barras reconocidos como tipo SingleDecodeType, texto de código `string`, región BarCodeRegionParameters y otros parámetros

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [deepClone()](#deepclone) | Crea una copia de la clase BarCodeResult. |
| [equals(other)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor BarCodeResult especificado. |
| [getCodeBytes()](#getcodebytes) | Obtiene los bytes del código codificado Valor: Los bytes del código del código de barras |
| [getCodeText(encoding)](#getcodetext) | Obtiene el texto del código con codificación. Este ejemplo muestra cómo usar `getCodeText`: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Obtiene el tipo de código de barras Valor: La información del tipo del código de barras reconocido |
| [getCodeTypeName()](#getcodetypename) | Obtiene el nombre del tipo de código de barras Valor: El nombre del tipo del código de barras reconocido |
| [getConfidence()](#getconfidence) | Obtiene el nivel de confianza del reconocimiento del código de barras reconocido Valor: BarCodeConfidence.Strong no tiene falsos ni errores de re |
| [getExtended()](#getextended) | Obtiene los parámetros extendidos del código de barras reconocido Valor: Los parámetros extendidos del código de barras reconocido |
| [getReadingQuality()](#getreadingquality) | Obtiene la calidad de lectura. Funciona para códigos de barras 1D y postales. Valor: El porcentaje de calidad de lectura |
| [getRegion()](#getregion) | Obtiene la región del código de barras Valor: La región del código de barras reconocido |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este BarCodeResult. |

### deepClone() {#deepclone}

Crea una copia de la clase BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor BarCodeResult especificado.

| Parámetro | Descripción |
| --- | --- |
| otro | Un valor BarCodeResult para comparar con esta instancia. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Obtiene los bytes del código codificado Valor: Los bytes del código del código de barras

### getCodeText(encoding) {#getcodetext}

Obtiene el texto del código con codificación. Este ejemplo muestra cómo usar `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText(\"車種名\", \"932\"); gen.save(\"barcode.png\", BarCodeImageFormat.PNG); let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText(\"932\")); }

| Parámetro | Descripción |
| --- | --- |
| codificación | La codificación para el texto del código. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Obtiene el tipo de código de barras Valor: La información del tipo del código de barras reconocido

### getCodeTypeName() {#getcodetypename}

Obtiene el nombre del tipo de código de barras Valor: El nombre del tipo del código de barras reconocido

### getConfidence() {#getconfidence}

Obtiene el nivel de confianza del reconocimiento del código de barras reconocido Valor: BarCodeConfidence.Strong no tiene falsos ni errores de reconocimiento, BarCodeConfidence.Moderate a veces puede tener falsos o texto de código incorrecto porque este nivel de confianza se aplica a códigos de barras con checksum débil o incluso sin él, BarCodeConfidence.NONE siempre tiene texto de código incorrecto y podría ser reconocimientos falsos

### getExtended() {#getextended}

Obtiene los parámetros extendidos del código de barras reconocido Valor: Los parámetros extendidos del código de barras reconocido

### getReadingQuality() {#getreadingquality}

Obtiene la calidad de lectura. Funciona para códigos de barras 1D y postales. Valor: El porcentaje de calidad de lectura

### getRegion() {#getregion}

Obtiene la región del código de barras Valor: La región del código de barras reconocido

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este BarCodeResult.

**Returns:** A string that represents this BarCodeResult.
