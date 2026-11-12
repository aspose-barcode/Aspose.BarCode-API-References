---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para codificar y decodificar el texto incrustado en el código HIBC PAS."
type: docs
weight: 480
url: /es/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Clase para codificar y decodificar el texto incrustado en el código HIBC PAS.

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | Constructor de HIBCPASRecord |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Agrega un nuevo registro |
| [addRecord(dataType, data)](#addrecord) | Agrega un nuevo registro |
| [clear()](#clear) | Borra la lista de registros |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor `HIBCPASCodetext` especificado. |
| [getBarcodeType()](#getbarcodetype) | Obtiene el tipo de código de barras. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construye codetext |
| [getDataLocation()](#getdatalocation) | Identifica la ubicación de los datos. |
| [getRecords()](#getrecords) | Obtiene la lista de registros |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [initFromString(constructedCodetext)](#initfromstring) | Inicializa la instancia a partir del codetext construido. |
| [setBarcodeType()](#setbarcodetype) | Obtiene o establece el tipo de código de barras. El codetext HIBC PAS puede codificarse usando HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Identifica la ubicación de los datos. |

### _fromMwObject() (static) {#-frommwobject}

Constructor de HIBCPASRecord

### addHIBCPASRecord(record) {#addhibcpasrecord}

Agrega un nuevo registro

| Parámetro | Descripción |
| --- | --- |
| registro | Registro a agregar |

### addRecord(dataType, data) {#addrecord}

Agrega un nuevo registro

| Parámetro | Descripción |
| --- | --- |
| dataType | Tipo de datos |
| datos | Cadena de datos |

### clear() {#clear}

Borra la lista de registros

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor `HIBCPASCodetext` especificado.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor `HIBCPASCodetext` para comparar con esta instancia. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Obtiene el tipo de código de barras.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Construye codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Identifica la ubicación de los datos.

### getRecords() {#getrecords}

Obtiene la lista de registros

**Returns:** List of records

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Inicializa la instancia a partir del codetext construido.

| Parámetro | Descripción |
| --- | --- |
| constructedCodetext | Codetext construido. |

### setBarcodeType() {#setbarcodetype}

Obtiene o establece el tipo de código de barras. El codetext HIBC PAS puede codificarse usando los tipos de codificación HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS y HIBCQRPAS. Valor predeterminado: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Identifica la ubicación de los datos.
