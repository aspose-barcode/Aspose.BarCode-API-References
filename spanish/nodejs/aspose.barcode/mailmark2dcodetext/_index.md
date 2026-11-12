---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark."
type: docs
weight: 570
url: /es/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark.

```js
new Mailmark2DCodetext()
```

Crea una instancia predeterminada de la clase Mailmark2DCodetext.

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Obtiene el tipo de código de barras. |
| [getClass_()](#getclass-) | Identifica la clase del artículo. Valores válidos: '1' - 1C (Minorista) '2' - 2C (Minorista) '3' - Economy (Minorista) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Construye el codetexto a partir de los datos de Mailmark. |
| [getCustomerContent()](#getcustomercontent) | Espacio opcional para uso del cliente. Longitud máxima por tipo: Tipo 7: 6 caracteres Tipo 9: 45 caracteres Tipo 29: 25 caracteres |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Modo de codificación del código de barras Datamatrix. Valor predeterminado: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | El tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres |
| [getInformationTypeID()](#getinformationtypeid) | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. Valores válidos: '0' - Doméstico clasificado y no clasificado |
| [getItemID()](#getitemid) | Identifica el elemento único dentro del Supply Chain ID. Cada código de barras Mailmark debe llevar un ID para que pueda ser un |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Contiene el código postal de devolución al remitente pero sin DPS. El PC (sin DPS) debe cumplir con un formato PAF®. |
| [getRTSFlag()](#getrtsflag) | Indicador que muestra qué nivel de servicio de devolución al remitente se está solicitando. |
| [getSupplyChainID()](#getsupplychainid) | Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999. |
| [getUPUCountryID()](#getupucountryid) | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| [getVersionID()](#getversionid) | Identifica la versión del código de barras según cada Information Type ID. Valores válidos: Actualmente '1'. '0' y '2' a '9' un |
| [initFromString(constructedCodetext)](#initfromstring) | Inicializa los datos de Mailmark a partir del codetexto construido. |
| [setClass_(value)](#setclass-) | Identifica la clase del artículo. Valores válidos: '1' - 1C (Minorista) '2' - 2C (Minorista) '3' - Economy (Minorista) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Espacio opcional para uso del cliente. Longitud máxima por tipo: Tipo 7: 6 caracteres Tipo 9: 45 caracteres Tipo 29: 25 caracteres |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Modo de codificación del código de barras Datamatrix. Valor predeterminado: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | El tipo 2D Mailmark define el tamaño del código de barras Data Matrix. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres |
| [setInformationTypeID(value)](#setinformationtypeid) | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. Valores válidos: '0' - Doméstico clasificado y no clasificado |
| [setItemID(value)](#setitemid) | Identifica el elemento único dentro del Supply Chain ID. Cada código de barras Mailmark debe llevar un ID para que pueda ser un |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Contiene el código postal de devolución al remitente pero sin DPS. El PC (sin DPS) debe cumplir con un formato PAF®. |
| [setRTSFlag()](#setrtsflag) | Indicador que muestra qué nivel de servicio de devolución al remitente se está solicitando. |
| [setSupplyChainID(value)](#setsupplychainid) | Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| [setVersionID(value)](#setversionid) | Identifica la versión del código de barras según cada Information Type ID. Valores válidos: Actualmente '1'. '0' y '2' a '9' un |

### getBarcodeType() {#getbarcodetype}

Obtiene el tipo de código de barras.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Identifica la clase del artículo. Valores válidos: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Construye el codetexto a partir de los datos de Mailmark.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Espacio opcional para uso del cliente. Longitud máxima por Tipo: Tipo 7: 6 caracteres Tipo 9: 45 caracteres Tipo 29: 25 caracteres

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Modo de codificación del código de barras Datamatrix. Valor predeterminado: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

El tipo 2D Mailmark define el tamaño del código de barras Data Matrix.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres. Área (1 o 2 caracteres) Distrito (1 o 2 caracteres) Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres). El código postal y el DPS deben cumplir con un formato PAF® válido.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. Valores válidos: '0' - Domestic Sorted & Unsorted 'A' - Online Postage 'B' - Franking 'C' - Consolidation

**Returns:** Information type ID

### getItemID() {#getitemid}

Identifica el elemento único dentro del Supply Chain ID. Cada código de barras Mailmark debe llevar un ID para que pueda ser identificado de forma única durante al menos 90 días. Valor máximo: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Contiene el código postal de devolución al remitente pero sin DPS. El PC (sin DPS) debe cumplir con un formato PAF®.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Indicador que muestra qué nivel de servicio de devolución al remitente se está solicitando.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Identifica el ID de país UPU. Longitud máxima: 4 caracteres.

**Returns:** Country ID

### getVersionID() {#getversionid}

Identifica la versión del código de barras según cada Information Type ID. Valores válidos: Actualmente '1'. '0' y '2' a '9' y 'A' a 'Z' reservados para uso futuro potencial.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Inicializa los datos de Mailmark a partir del codetexto construido.

| Parámetro | Descripción |
| --- | --- |
| constructedCodetext | Codetext construido. |

### setClass_(value) {#setclass-}

Identifica la clase del artículo. Valores válidos: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

| Parámetro | Descripción |
| --- | --- |
| valor | clase del artículo |

### setCustomerContent(value) {#setcustomercontent}

Espacio opcional para uso del cliente. Longitud máxima por Tipo: Tipo 7: 6 caracteres Tipo 9: 45 caracteres Tipo 29: 25 caracteres

| Parámetro | Descripción |
| --- | --- |
| valor | Contenido del cliente |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Modo de codificación del código de barras Datamatrix. Valor predeterminado: DataMatrixEncodeMode.C40.

| Parámetro | Descripción |
| --- | --- |
| valor | Modo de codificación del código de barras Datamatrix. |

### setDataMatrixType(value) {#setdatamatrixtype}

El tipo 2D Mailmark define el tamaño del código de barras Data Matrix.

| Parámetro | Descripción |
| --- | --- |
| valor | Tamaño del código de barras Data Matrix |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres. Área (1 o 2 caracteres) Distrito (1 o 2 caracteres) Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres). El código postal y el DPS deben cumplir con un formato PAF® válido.

| Parámetro | Descripción |
| --- | --- |
| valor | el código postal de la dirección de entrega con DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. Valores válidos: '0' - Domestic Sorted & Unsorted 'A' - Online Postage 'B' - Franking 'C' - Consolidation

| Parámetro | Descripción |
| --- | --- |
| valor | ID de tipo de información |

### setItemID(value) {#setitemid}

Identifica el elemento único dentro del Supply Chain ID. Cada código de barras Mailmark debe llevar un ID para que pueda ser identificado de forma única durante al menos 90 días. Valor máximo: 99999999.

| Parámetro | Descripción |
| --- | --- |
| valor | elemento dentro del Supply Chain ID |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Contiene el código postal de devolución al remitente pero sin DPS. El PC (sin DPS) debe cumplir con un formato PAF®.

| Parámetro | Descripción |
| --- | --- |
| valor | Código postal de devolución al remitente pero sin DPS |

### setRTSFlag() {#setrtsflag}

Indicador que muestra qué nivel de servicio de devolución al remitente se está solicitando.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999.

| Parámetro | Descripción |
| --- | --- |
| valor | ID de cadena de suministro |

### setUPUCountryID(value) {#setupucountryid}

Identifica el ID de país UPU. Longitud máxima: 4 caracteres.

| Parámetro | Descripción |
| --- | --- |
| valor | ID de país |

### setVersionID(value) {#setversionid}

Identifica la versión del código de barras según cada Information Type ID. Valores válidos: Actualmente '1'. '0' y '2' a '9' y 'A' a 'Z' reservados para uso futuro potencial.

| Parámetro | Descripción |
| --- | --- |
| valor | ID de versión |
