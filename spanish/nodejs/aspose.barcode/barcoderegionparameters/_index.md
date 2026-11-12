---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Representa la región del código de barras reconocido y el ángulo del código de barras"
type: docs
weight: 100
url: /es/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Representa la región del código de barras reconocido y el ángulo del código de barras

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de BarCodeRegionParameters. |
| [getAngle()](#getangle) | Obtiene el ángulo del código de barras (0-360). Valor: El ángulo para el código de barras (0-360). |
| [getPoints()](#getpoints) | Obtiene la matriz Points que delimita la región del código de barras Valor: Devuelve la matriz Points que delimita la región del código de barras |
| [getQuadrangle()](#getquadrangle) | Obtiene el Quadrangle que delimita la región del código de barras Valor: Devuelve el Quadrangle que delimita la región del código de barras |
| [getRectangle()](#getrectangle) | Obtiene el Rectangle que delimita la región del código de barras Valor: Devuelve el Rectangle que delimita la región del código de barras |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [toString()](#tostring) | Devuelve una representación en cadena legible por humanos de este BarCodeRegionParameters. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado de BarCodeRegionParameters.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor System.Object para comparar con esta instancia. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Obtiene el ángulo del código de barras (0-360). Valor: El ángulo para el código de barras (0-360).

### getPoints() {#getpoints}

Obtiene la matriz Points que delimita la región del código de barras Valor: Devuelve la matriz Points que delimita la región del código de barras

### getQuadrangle() {#getquadrangle}

Obtiene el Quadrangle que delimita la región del código de barras Valor: Devuelve el Quadrangle que delimita la región del código de barras

### getRectangle() {#getrectangle}

Obtiene el Rectangle que delimita la región del código de barras Valor: Devuelve el Rectangle que delimita la región del código de barras

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Devuelve una representación en cadena legible por humanos de este BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.
