---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3."
type: docs
weight: 700
url: /es/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construye codetext |
| [getCountryCode()](#getcountrycode) | Identifica el código de país de 3 dígitos. |
| [getHashCode()](#gethashcode) | Devuelve el código hash de esta instancia. |
| [getPostalCode()](#getpostalcode) | Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o de 6 símbolos alfanuméricos en el modo 3. |
| [getSecondMessage()](#getsecondmessage) | Identifica el segundo mensaje del código de barras. |
| [getServiceCategory()](#getservicecategory) | Identifica la categoría de servicio de 3 dígitos. |
| [initFromString(constructedCodetext)](#initfromstring) | Inicializa la instancia a partir del codetext construido. |
| [setCountryCode()](#setcountrycode) | Identifica el código de país de 3 dígitos. |
| [setPostalCode()](#setpostalcode) | Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o de 6 símbolos alfanuméricos en el modo 3. |
| [setSecondMessage()](#setsecondmessage) | Identifica el segundo mensaje del código de barras. |
| [setServiceCategory()](#setservicecategory) | Identifica la categoría de servicio de 3 dígitos. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor para comparar con esta instancia |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Construye codetext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Identifica el código de país de 3 dígitos.

### getHashCode() {#gethashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o de 6 símbolos alfanuméricos en el modo 3.

### getSecondMessage() {#getsecondmessage}

Identifica el segundo mensaje del código de barras.

### getServiceCategory() {#getservicecategory}

Identifica la categoría de servicio de 3 dígitos.

### initFromString(constructedCodetext) {#initfromstring}

Inicializa la instancia a partir del codetext construido.

| Parámetro | Descripción |
| --- | --- |
| constructedCodetext | Codetext construido. |

### setCountryCode() {#setcountrycode}

Identifica el código de país de 3 dígitos.

### setPostalCode() {#setpostalcode}

Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o de 6 símbolos alfanuméricos en el modo 3.

### setSecondMessage() {#setsecondmessage}

Identifica el segundo mensaje del código de barras.

### setServiceCategory() {#setservicecategory}

Identifica la categoría de servicio de 3 dígitos.
