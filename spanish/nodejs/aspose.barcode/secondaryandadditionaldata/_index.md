---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para almacenar datos secundarios y adicionales HIBC LIC."
type: docs
weight: 880
url: /es/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Clase para almacenar datos secundarios y adicionales HIBC LIC.

```js
new SecondaryAndAdditionalData()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor `SecondaryAndAdditionalData` especificado. |
| [getDateOfManufacture()](#getdateofmanufacture) | Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Defa |
| [getExpiryDate()](#getexpirydate) | Identifica la fecha de caducidad. Se usará si ExpiryDateFormat no está configurado en None. |
| [getExpiryDateFormat()](#getexpirydateformat) | Identifica el formato de la fecha de caducidad. |
| [getLotNumber()](#getlotnumber) | Identifica el número de lote o partida. El número de lote/partida debe ser una cadena alfanumérica con una longitud máxima de 18 símbolos. . |
| [getQuantity()](#getquantity) | Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Defa |
| [getSerialNumber()](#getserialnumber) | Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | Instancia datos suplementarios secundarios y adicionales a partir del formato de cadena según la especificación HIBC LIC. |
| [setDateOfManufacture()](#setdateofmanufacture) | Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Defa |
| [setExpiryDate()](#setexpirydate) | Identifica la fecha de caducidad. Se usará si ExpiryDateFormat no está configurado en None. |
| [setExpiryDateFormat()](#setexpirydateformat) | Identifica el formato de la fecha de caducidad. |
| [setLotNumber()](#setlotnumber) | Identifica el número de lote o partida. El número de lote/partida debe ser una cadena alfanumérica con una longitud máxima de 18 símbolos. . |
| [setQuantity()](#setquantity) | Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Defa |
| [setSerialNumber()](#setserialnumber) | Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud. |
| [toString()](#tostring) | Convierte los datos al formato de cadena según la especificación HIBC LIC. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor `SecondaryAndAdditionalData` especificado.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor `SecondaryAndAdditionalData` para comparar con esta instancia. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Valor predeterminado: DateTime.MinValue

### getExpiryDate() {#getexpirydate}

Identifica la fecha de caducidad. Se usará si ExpiryDateFormat no está configurado en None.

### getExpiryDateFormat() {#getexpirydateformat}

Identifica el formato de la fecha de caducidad.

### getLotNumber() {#getlotnumber}

Identifica el número de lote o partida. El número de lote/partida debe ser una cadena alfanumérica con una longitud máxima de 18 símbolos. .

### getQuantity() {#getquantity}

Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1

### getSerialNumber() {#getserialnumber}

Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

Instancia datos suplementarios secundarios y adicionales a partir del formato de cadena según la especificación HIBC LIC.

| Parámetro | Descripción |
| --- | --- |
| secondaryDataCodetext | Cadena formateada. |

### setDateOfManufacture() {#setdateofmanufacture}

Identifica la fecha de fabricación. La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo. Valor predeterminado: DateTime.MinValue

### setExpiryDate() {#setexpirydate}

Identifica la fecha de caducidad. Se usará si ExpiryDateFormat no está configurado en None.

### setExpiryDateFormat() {#setexpirydateformat}

Identifica el formato de la fecha de caducidad.

### setLotNumber() {#setlotnumber}

Identifica el número de lote o partida. El número de lote/partida debe ser una cadena alfanumérica con una longitud máxima de 18 símbolos. .

### setQuantity() {#setquantity}

Identifica la cantidad, debe ser un valor entero de 0 a 500. La cantidad puede establecerse en -1 para no usar este campo. Valor predeterminado: -1

### setSerialNumber() {#setserialnumber}

Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos de longitud.

### toString() {#tostring}

Convierte los datos al formato de cadena según la especificación HIBC LIC.

**Returns:** Formatted string.
