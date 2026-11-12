---
title: "DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros de DotCode."
type: docs
weight: 390
url: /es/nodejs/aspose.barcode/dotcodeparameters/
---

## DotCodeParameters class

Parámetros de DotCode.

```js
new DotCodeParameters()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Relación altura/ancho del módulo de código de barras 2D. |
| [getColumns()](#getcolumns) | Identifica el recuento de columnas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. Número o |
| [getDotCodeEncodeMode()](#getdotcodeencodemode) ~~(deprecated)~~ | Identifica el modo de codificación DotCode. Valor predeterminado: Auto. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Identifica la ID del código de barras en modo de apéndice estructurado DotCode. La ID comienza en 1 y debe ser menor o igual que los códigos de barras |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. |
| [getECIEncoding()](#geteciencoding) | Identifica la codificación ECI. Se usa cuando DotCodeEncodeMode es AUTO. Valor predeterminado: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Identifica el modo de codificación DotCode. Valor predeterminado: Auto. |
| [getRows()](#getrows) | Identifica el recuento de filas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. Número de r |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Identifica la ID del código de barras en modo de apéndice estructurado DotCode. La ID comienza en 1 y debe ser menor o igual que los códigos de barras |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. |
| [isReaderInitialization()](#isreaderinitialization) | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o |
| [setAspectRatio()](#setaspectratio) | Relación altura/ancho del módulo de código de barras 2D. |
| [setColumns()](#setcolumns) | Identifica el recuento de columnas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. Número o |
| [setDotCodeEncodeMode()](#setdotcodeencodemode) ~~(deprecated)~~ | Identifica el modo de codificación DotCode. Valor predeterminado: Auto. |
| [setDotCodeStructuredAppendModeBarcodeId()](#setdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Identifica la ID del código de barras en modo de apéndice estructurado DotCode. La ID comienza en 1 y debe ser menor o igual que los códigos de barras |
| [setDotCodeStructuredAppendModeBarcodesCount()](#setdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. |
| [setECIEncoding()](#seteciencoding) | Identifica la codificación ECI. Se usa cuando DotCodeEncodeMode es AUTO. Valor predeterminado: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | Identifica el modo de codificación DotCode. Valor predeterminado: Auto. |
| [setReaderInitialization()](#setreaderinitialization) | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o |
| [setRows()](#setrows) | Identifica el recuento de filas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. Número de r |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Identifica la ID del código de barras en modo de apéndice estructurado DotCode. La ID comienza en 1 y debe ser menor o igual que los códigos de barras |
| [setStructuredAppendModeBarcodesCount()](#setstructuredappendmodebarcodescount) | Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este DotCodeParameters. |

### getAspectRatio() {#getaspectratio}

Relación altura/ancho del módulo de código de barras 2D.

### getColumns() {#getcolumns}

Identifica el recuento de columnas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de columnas debe ser al menos 5. Valor predeterminado: -1

### getDotCodeEncodeMode() {#getdotcodeencodemode}

> **Deprecated.** See method description for replacement.

Identifica el modo de codificación DotCode. Valor predeterminado: Auto.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Identifica el ID del código de barras DotCode en modo structured append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35.

### getECIEncoding() {#geteciencoding}

Identifica la codificación ECI. Se usa cuando DotCodeEncodeMode es AUTO. Valor predeterminado: ISO-8859-1

### getEncodeMode() {#getencodemode}

Identifica el modo de codificación DotCode. Valor predeterminado: Auto.

### getRows() {#getrows}

Identifica el recuento de filas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de filas debe ser al menos 5. Valor predeterminado: -1

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Identifica el ID del código de barras DotCode en modo structured append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35.

### isReaderInitialization() {#isreaderinitialization}

Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false.

### setAspectRatio() {#setaspectratio}

Relación altura/ancho del módulo de código de barras 2D.

### setColumns() {#setcolumns}

Identifica el recuento de columnas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de columnas debe ser al menos 5. Valor predeterminado: -1

### setDotCodeEncodeMode() {#setdotcodeencodemode}

> **Deprecated.** See method description for replacement.

Identifica el modo de codificación DotCode. Valor predeterminado: Auto.

### setDotCodeStructuredAppendModeBarcodeId() {#setdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Identifica el ID del código de barras DotCode en modo structured append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

### setDotCodeStructuredAppendModeBarcodesCount() {#setdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35.

### setECIEncoding() {#seteciencoding}

Identifica la codificación ECI. Se usa cuando DotCodeEncodeMode es AUTO. Valor predeterminado: ISO-8859-1

### setEncodeMode() {#setencodemode}

Identifica el modo de codificación DotCode. Valor predeterminado: Auto.

### setReaderInitialization() {#setreaderinitialization}

Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false.

### setRows() {#setrows}

Identifica el recuento de filas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de filas debe ser al menos 5. Valor predeterminado: -1

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Identifica el ID del código de barras DotCode en modo structured append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

### setStructuredAppendModeBarcodesCount() {#setstructuredappendmodebarcodescount}

Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este DotCodeParameters.

**Returns:** A string that represents this DotCodeParameters.
