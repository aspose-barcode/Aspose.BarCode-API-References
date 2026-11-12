---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena información adicional de DataBar del código de barras reconocido"
type: docs
weight: 310
url: /es/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Almacena información adicional de DataBar del código de barras reconocido

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de DataBarExtendedParameters. |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Obtiene el indicador de componente compuesto DataBar 2D. El valor predeterminado es false. |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado de DataBarExtendedParameters.

| Parámetro | Descripción |
| --- | --- |
| obj | Valor de DataBarExtendedParameters para comparar con esta instancia. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Obtiene el indicador de componente compuesto DataBar 2D. El valor predeterminado es false.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este.

**Returns:** A string that represents this .
