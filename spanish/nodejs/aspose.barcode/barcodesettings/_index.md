---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Los principales parámetros de decodificación de BarCode."
type: docs
weight: 150
url: /es/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

Los principales parámetros de decodificación de BarCode. Contiene parámetros que influyen en los datos reconocidos.

```js
new BarcodeSettings(settings)
```

Constructor de copia de BarcodeSettings

| Parámetro | Descripción |
| --- | --- |
| configuración | La fuente de los datos |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Obtiene los parámetros de decodificación de AustraliaPost |
| [getChecksumValidation()](#getchecksumvalidation) | Habilita la validación de suma de verificación durante el reconocimiento de códigos de barras 1D y postales. El valor predeterminado se trata como Sí para las simbologías que |
| [getDetectEncoding()](#getdetectencoding) | La bandera que obliga al motor a detectar la codificación del texto del código para juegos de caracteres Unicode. El valor predeterminado es verdadero. |
| [getStripFNC()](#getstripfnc) | Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. El valor predeterminado es falso. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Devuelve solo los tipos de códigos de barras especificados explícitamente para el reconocimiento. Cuando está habilitado, los códigos de barras reconocidos de otros compatibles |
| [setChecksumValidation(value)](#setchecksumvalidation) | Habilita la validación de suma de verificación durante el reconocimiento de códigos de barras 1D y postales. El valor predeterminado se trata como Sí para las simbologías que |
| [setDetectEncoding()](#setdetectencoding) | La bandera que obliga al motor a detectar la codificación del texto del código para juegos de caracteres Unicode. El valor predeterminado es verdadero. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Devuelve solo los tipos de códigos de barras especificados explícitamente para el reconocimiento. Cuando está habilitado, los códigos de barras reconocidos de otros compatibles |
| [setStripFNC(value)](#setstripfnc) | Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. El valor predeterminado es falso. |

### getAustraliaPost() {#getaustraliapost}

Obtiene los parámetros de decodificación de AustraliaPost

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Habilita la validación de suma de verificación durante el reconocimiento de códigos de barras 1D y postales. El valor predeterminado se trata como Sí para las simbologías que deben contener suma de verificación, como No donde la suma de verificación solo es posible. Suma de verificación nunca usada: Codabar, PatchCode, Pharmacode, DataLogic2of5. Suma de verificación posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Suma de verificación siempre usada: Resto de simbologías

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

La bandera que obliga al motor a detectar la codificación del texto del código para juegos de caracteres Unicode. El valor predeterminado es verdadero.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. El valor predeterminado es falso.

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

Devuelve solo los tipos de códigos de barras especificados explícitamente para el reconocimiento. Cuando está habilitado, los códigos de barras reconocidos de otros tipos compatibles o equivalentes se filtran. El valor predeterminado es falso. Ejemplo: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Habilita la validación de suma de verificación durante el reconocimiento de códigos de barras 1D y postales. El valor predeterminado se trata como Sí para las simbologías que deben contener suma de verificación, como No donde la suma de verificación solo es posible. Suma de verificación nunca usada: Codabar, PatchCode, Pharmacode, DataLogic2of5. Suma de verificación posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Suma de verificación siempre usada: Resto de simbologías

| Parámetro | Descripción |
| --- | --- |
| valor | Habilita la validación de suma de verificación durante el reconocimiento de códigos de barras 1D y postales. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

La bandera que obliga al motor a detectar la codificación del texto del código para juegos de caracteres Unicode. El valor predeterminado es verdadero.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

Devuelve solo los tipos de códigos de barras especificados explícitamente para el reconocimiento. Cuando está habilitado, los códigos de barras reconocidos de otros tipos compatibles o equivalentes se filtran. El valor predeterminado es falso. Ejemplo: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. El valor predeterminado es falso.

| Parámetro | Descripción |
| --- | --- |
| valor | Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. El valor predeterminado es falso. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
