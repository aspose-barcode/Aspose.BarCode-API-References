---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros de Aztec."
type: docs
weight: 70
url: /es/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Parámetros de Aztec.

```js
new AztecParameters()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Relación altura/ancho del módulo de código de barras 2D. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Obtiene un modo de codificación Aztec. Valor predeterminado: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Obtiene un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | Obtiene la codificación ECI. Se usa cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Obtiene un modo de codificación Aztec. Valor predeterminado: Auto. |
| [getErrorLevel()](#geterrorlevel) | Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95. |
| [getLayersCount()](#getlayerscount) | Obtiene el recuento de capas del símbolo Aztec. El recuento de capas debe estar en el rango de 1 a 3 para el modo Compact y en el rango de 1 a 3 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | ID de código de barras para el modo Structured Append del código de barras Aztec. El ID de código de barras debe estar en el rango de 1 al número de códigos de barras. Predeterminado |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Recuento de códigos de barras para el modo Structured Append del código de barras Aztec. El recuento de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Identificador de archivo para el modo Structured Append del código de barras Aztec (campo opcional). El identificador de archivo no debe contener espacios. Valor predeterminado: |
| [getSymbolMode()](#getsymbolmode) | Obtiene un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [setAspectRatio()](#setaspectratio) | Relación altura/ancho del módulo de código de barras 2D. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Establece un modo de codificación Aztec. Valor predeterminado: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Establece un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | Establece la codificación ECI. Se usa cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Establece un modo de codificación Aztec. Valor predeterminado: Auto. |
| [setErrorLevel()](#seterrorlevel) | Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95. |
| [setLayersCount()](#setlayerscount) | Establece el número de capas del símbolo Aztec. El número de capas debe estar en el rango de 1 a 3 para el modo Compact y en el rango de 1 a 3 |
| [setReaderInitialization()](#setreaderinitialization) | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | ID de código de barras para el modo Structured Append del código de barras Aztec. El ID de código de barras debe estar en el rango de 1 al número de códigos de barras. Predeterminado |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Recuento de códigos de barras para el modo Structured Append del código de barras Aztec. El recuento de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Identificador de archivo para el modo Structured Append del código de barras Aztec (campo opcional). El identificador de archivo no debe contener espacios. Valor predeterminado: |
| [setSymbolMode(value)](#setsymbolmode) | Establece un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto. |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este `AztecParameters`. |

### getAspectRatio() {#getaspectratio}

Relación altura/ancho del módulo de código de barras 2D.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Obtiene un modo de codificación Aztec. Valor predeterminado: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Obtiene un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

Obtiene la codificación ECI. Se usa cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1

### getEncodeMode() {#getencodemode}

Obtiene un modo de codificación Aztec. Valor predeterminado: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95.

### getLayersCount() {#getlayerscount}

Obtiene el número de capas del símbolo Aztec. El número de capas debe estar en el rango de 1 a 3 para el modo Compact y en el rango de 1 a 32 para el modo Full Range. Valor predeterminado: 0 (auto).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Identificador de código de barras para el modo Structured Append del código de barras Aztec. El identificador de código de barras debe estar en el rango de 1 al recuento de códigos de barras. Valor predeterminado: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Recuento de códigos de barras para el modo Structured Append del código de barras Aztec. El recuento de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Identificador de archivo para el modo Structured Append del código de barras Aztec (campo opcional). El identificador de archivo no debe contener espacios. Valor predeterminado: cadena vacía

### getSymbolMode() {#getsymbolmode}

Obtiene un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector.

### setAspectRatio() {#setaspectratio}

Relación altura/ancho del módulo de código de barras 2D.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Establece un modo de codificación Aztec. Valor predeterminado: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Establece un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

Establece la codificación ECI. Se usa cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Establece un modo de codificación Aztec. Valor predeterminado: Auto.

| Parámetro | Descripción |
| --- | --- |
| valor | un modo de codificación Aztec. |

### setErrorLevel() {#seterrorlevel}

Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95.

### setLayersCount() {#setlayerscount}

Establece el número de capas del símbolo Aztec. El número de capas debe estar en el rango de 1 a 3 para el modo Compact y en el rango de 1 a 32 para el modo Full Range. Valor predeterminado: 0 (auto).

### setReaderInitialization() {#setreaderinitialization}

Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Identificador de código de barras para el modo Structured Append del código de barras Aztec. El identificador de código de barras debe estar en el rango de 1 al recuento de códigos de barras. Valor predeterminado: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Recuento de códigos de barras para el modo Structured Append del código de barras Aztec. El recuento de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Identificador de archivo para el modo Structured Append del código de barras Aztec (campo opcional). El identificador de archivo no debe contener espacios. Valor predeterminado: cadena vacía

### setSymbolMode(value) {#setsymbolmode}

Establece un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto.

| Parámetro | Descripción |
| --- | --- |
| valor | un modo de símbolo Aztec. |

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este `AztecParameters`.

**Returns:** A string that represents this `AztecParameters`.
