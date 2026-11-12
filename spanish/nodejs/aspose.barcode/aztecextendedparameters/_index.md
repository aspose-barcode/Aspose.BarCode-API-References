---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena datos especiales del código de barras Aztec reconocido. Este ejemplo muestra cómo obtener los valores sin procesar de Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /es/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Almacena datos especiales del código de barras Aztec reconocido. Este ejemplo muestra cómo obtener los valores sin procesar de Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `AztecExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Obtiene el ID del código de barras en modo de anexado estructurado Aztec. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Obtiene el recuento de códigos de barras en modo de anexado estructurado Aztec. El valor predeterminado es 0. El recuento debe ser un valor de 1 a 26. Valor: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Obtiene el ID de archivo del modo de anexado estructurado Aztec. El valor predeterminado es una cadena vacía. Valor: El ID de archivo del modo de anexado estructurado Aztec. |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [isReaderInitialization()](#isreaderinitialization) | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este `AztecExtendedParameters`. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado de `AztecExtendedParameters`.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor System.Object para comparar con esta instancia. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Obtiene el ID del código de barras en modo de anexado estructurado Aztec. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es 0. Valor: El ID del código de barras del modo de anexado estructurado Aztec.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Obtiene el recuento de códigos de barras en modo de anexado estructurado Aztec. El valor predeterminado es 0. El recuento debe ser un valor de 1 a 26. Valor: El recuento de códigos de barras del modo de anexado estructurado Aztec.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Obtiene el ID de archivo del modo de anexado estructurado Aztec. El valor predeterminado es una cadena vacía. Valor: El ID de archivo del modo de anexado estructurado Aztec.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
