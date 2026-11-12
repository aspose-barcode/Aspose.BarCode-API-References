---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena datos especiales del código de barras DataMatrix reconocido Esta muestra muestra cómo obtener valores sin procesar de DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /es/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Almacena datos especiales del código de barras DataMatrix reconocido Esta muestra muestra cómo obtener valores sin procesar de DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado `DataMatrixExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Obtiene el ID del código de barras DataMatrix en modo Structured Append. El ID comienza en 1 y debe ser menor o igual al número de códigos de barras cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Obtiene la cantidad de códigos de barras en modo Structured Append de DataMatrix. El valor predeterminado es -1. La cantidad debe ser un valor de 1 a 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Obtiene el ID del código de barras DataMatrix en modo Structured Append. El ID comienza en 1 y debe ser menor o igual al número de códigos de barras cou |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [isReaderProgramming()](#isreaderprogramming) | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado `DataMatrixExtendedParameters`.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor System.Object para comparar con esta instancia. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Obtiene el ID del código de barras DataMatrix en modo Structured Append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. Valor: El ID del código de barras DataMatrix en modo Structured Append.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Obtiene el recuento de códigos de barras en modo de anexado estructurado de DataMatrix. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. Valor: El recuento del código de barras en modo de anexado estructurado de DataMatrix.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Obtiene el ID del código de barras DataMatrix en modo Structured Append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. Valor: El ID del código de barras DataMatrix en modo Structured Append.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
