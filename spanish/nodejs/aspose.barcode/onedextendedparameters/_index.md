---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena datos especiales del código de barras 1D reconocido, como texto de código separado y suma de verificación."
type: docs
weight: 720
url: /es/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Almacena datos especiales del código de barras 1D reconocido, como texto de código separado y suma de verificación.

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor OneDExtendedParameters especificado. |
| [getCheckSum()](#getchecksum) | Obtiene el checksum para códigos de barras 1D. Valor: El checksum para el código de barras 1D. |
| [getValue()](#getvalue) | Obtiene el codetext de los códigos de barras 1D sin checksum. Valor: El codetext de los códigos de barras 1D sin checksum. |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [isEmpty()](#isempty) | Prueba si todos los parámetros tienen solo valores predeterminados Valor: Devuelve `true ` si todos los parámetros tienen solo valores predeterminados; o |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este OneDExtendedParameters. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor OneDExtendedParameters especificado.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor System.Object para comparar con esta instancia. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Obtiene el checksum para códigos de barras 1D. Valor: El checksum para el código de barras 1D.

### getValue() {#getvalue}

Obtiene el codetext de los códigos de barras 1D sin checksum. Valor: El codetext de los códigos de barras 1D sin checksum.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Prueba si todos los parámetros tienen solo valores predeterminados. Valor: Devuelve `true ` si todos los parámetros tienen solo valores predeterminados; de lo contrario, `false `.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este OneDExtendedParameters.

**Returns:** A string that represents this OneDExtendedParameters.
