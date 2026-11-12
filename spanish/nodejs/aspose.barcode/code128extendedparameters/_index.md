---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena datos especiales del código de barras Code128 reconocido. Representa la región del código de barras reconocido y el ángulo del código de barras."
type: docs
weight: 240
url: /es/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Almacena datos especiales del código de barras Code128 reconocido. Representa la región del código de barras reconocido y el ángulo del código de barras.

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de Code128ExtendedParameters. |
| [getCode128DataPortions()](#getcode128dataportions) | Obtiene la matriz Code128DataPortion del código de barras Code128 reconocido. Valor de Code128DataPortion. |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este Code128ExtendedParameters. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado de Code128ExtendedParameters.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor System.Object para comparar con esta instancia. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Obtiene la matriz Code128DataPortion del código de barras Code128 reconocido. Valor de Code128DataPortion.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este Code128ExtendedParameters.

**Returns:** A string that represents this Code128ExtendedParameters.
