---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena datos especiales del código de barras DotCode reconocido. Este ejemplo muestra cómo obtener los valores sin procesar de DotCode"
type: docs
weight: 380
url: /es/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Almacena datos especiales del código de barras DotCode reconocido. Este ejemplo muestra cómo obtener los valores sin procesar de DotCode

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `DotCodeExtendedParameters`. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Obtiene el ID del código de barras DotCode en modo de anexado estructurado. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Obtiene el recuento de códigos de barras DotCode en modo de anexado estructurado. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. Valor: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Obtiene el ID del código de barras DotCode en modo de anexado estructurado. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Obtiene el recuento de códigos de barras DotCode en modo de anexado estructurado. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. Valor: |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [isReaderInitialization()](#isreaderinitialization) | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado de `DotCodeExtendedParameters`.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor System.Object para comparar con esta instancia. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Obtiene el ID del código de barras DotCode en modo de anexado estructurado. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. Valor: El ID del código de barras DotCode en modo de anexado estructurado.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Obtiene el recuento de códigos de barras DotCode en modo de anexado estructurado. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. Valor: El recuento del código de barras DotCode en modo de anexado estructurado.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Obtiene el ID del código de barras DotCode en modo de anexado estructurado. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. Valor: El ID del código de barras DotCode en modo de anexado estructurado.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Obtiene el recuento de códigos de barras DotCode en modo de anexado estructurado. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. Valor: El recuento del código de barras DotCode en modo de anexado estructurado.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
