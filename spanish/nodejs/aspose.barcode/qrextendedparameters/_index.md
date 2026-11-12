---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena información de QR Structured Append del código de barras reconocido"
type: docs
weight: 810
url: /es/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Almacena información de QR Structured Append del código de barras reconocido

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de QRExtendedParameters. |
| [getErrorLevel()](#geterrorlevel) | Nivel de corrección de errores Reed-Solomon del código de barras reconocido. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Versión del MicroQR Code reconocido. De M1 a M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Nivel de corrección de errores Reed-Solomon del código de barras reconocido. De bajo a alto: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Obtiene el índice del código de barras en modo de anexado estructurado QR. El índice comienza en 0. El valor predeterminado es -1.Valor: La cantidad de |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Obtiene la cantidad de códigos de barras en modo de anexado estructurado QR. El valor predeterminado es -1.Valor: La cantidad del anexado estructurado QR |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Obtiene los datos de paridad del modo de anexado estructurado QR. El valor predeterminado es -1.Valor: El índice del modo de anexado estructurado QR |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Versión del QR Code reconocido. De Version1 a Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Versión del RectMicroQR Code reconocido. De R7x43 a R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Obtiene el índice del código de barras en modo de anexado estructurado QR. El índice comienza en 0. El valor predeterminado es -1. Valor: La cantidad de |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Obtiene la cantidad de códigos de barras en modo de anexado estructurado QR. El valor predeterminado es -1. Valor: La cantidad del anexado estructurado QR |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Obtiene los datos de paridad del modo de anexado estructurado QR. El valor predeterminado es -1. Valor: El índice del modo de anexado estructurado QR |
| [getVersion()](#getversion) | Versión del QR Code reconocido. De Version1 a Version40. |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [isEmpty()](#isempty) | Prueba si todos los parámetros tienen solo valores predeterminados Valor |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este QRExtendedParameters. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado de QRExtendedParameters.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor de objeto para comparar con esta instancia. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Nivel de corrección de errores Reed-Solomon del código de barras reconocido. De bajo a alto: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Versión del MicroQR Code reconocido. De M1 a M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Nivel de corrección de errores Reed-Solomon del código de barras reconocido. De bajo a alto: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Obtiene el índice del código de barras en modo de anexado estructurado QR. El índice comienza en 0. El valor predeterminado es -1.Valor: La cantidad del código de barras en modo de anexado estructurado QR.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Obtiene la cantidad de códigos de barras en modo de anexado estructurado QR. El valor predeterminado es -1.Valor: La cantidad del código de barras en modo de anexado estructurado QR.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Obtiene los datos de paridad del modo de anexado estructurado QR. El valor predeterminado es -1.Valor: El índice del código de barras en modo de anexado estructurado QR.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Versión del QR Code reconocido. De Version1 a Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Versión del RectMicroQR Code reconocido. De R7x43 a R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Obtiene el índice del código de barras en modo de anexado estructurado QR. El índice comienza en 0. El valor predeterminado es -1. Valor: La cantidad del código de barras en modo de anexado estructurado QR.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Obtiene la cantidad de códigos de barras en modo de anexado estructurado QR. El valor predeterminado es -1. Valor: La cantidad del código de barras en modo de anexado estructurado QR.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Obtiene los datos de paridad del modo de anexado estructurado QR. El valor predeterminado es -1. Valor: El índice del código de barras en modo de anexado estructurado QR.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Versión del QR Code reconocido. De Version1 a Version40.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Prueba si todos los parámetros tienen solo valores predeterminados Valor

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
