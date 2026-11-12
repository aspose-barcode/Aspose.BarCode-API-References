---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase base para codificar y decodificar el texto incrustado en el código MaxiCode."
type: docs
weight: 600
url: /es/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Clase base para codificar y decodificar el texto incrustado en el código MaxiCode. Este ejemplo muestra cómo decodificar el codetexto bruto de MaxiCode a una instancia de MaxiCodeCodetext.

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Obtiene el tipo de código de barras. |
| [getECIEncoding()](#geteciencoding) | Obtiene la codificación ECI. Se usa cuando MaxiCodeEncodeMode es AUTO. |
| [getEncodeMode()](#getencodemode) | Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Obtiene un modo de codificación MaxiCode. |
| [getMode()](#getmode) | Obtiene el modo MaxiCode. |
| [setECIEncoding()](#seteciencoding) | Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es AUTO. |
| [setEncodeMode(value)](#setencodemode) | Establece un modo de codificación MaxiCode. Valor predeterminado: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Establece un modo de codificación MaxiCode. |

### getBarcodeType() {#getbarcodetype}

Obtiene el tipo de código de barras.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Obtiene la codificación ECI. Se usa cuando MaxiCodeEncodeMode es AUTO.

### getEncodeMode() {#getencodemode}

Obtiene un modo de codificación MaxiCode. Valor predeterminado: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Obtiene un modo de codificación MaxiCode.

### getMode() {#getmode}

Obtiene el modo MaxiCode.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es AUTO.

### setEncodeMode(value) {#setencodemode}

Establece un modo de codificación MaxiCode. Valor predeterminado: Auto.

| Parámetro | Descripción |
| --- | --- |
| valor | un modo de codificación MaxiCode. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Establece un modo de codificación MaxiCode.
