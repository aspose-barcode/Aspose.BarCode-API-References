---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados."
type: docs
weight: 580
url: /es/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados.

```js
new MailmarkCodetext()
```

Inicializa una nueva instancia de la clase `MailmarkCodetext`.

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Obtiene el tipo de código de barras. |
| [getClass_()](#getclass-) | "0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para potencial) |
| [getConstructedCodetext()](#getconstructedcodetext) | Construye el codetexto a partir de los datos de Mailmark. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | El PC y DP deben cumplir con un formato PAF. Cadena de nueve caracteres que denota internacional "XY11 " (nota los 5 espacios finales) |
| [getFormat()](#getformat) | "0" – Nulo o Prueba "1" – Letra "2" – Letra Grande |
| [getItemID()](#getitemid) | El valor máximo es 99999999. |
| [getSupplychainID()](#getsupplychainid) | Los valores máximos son 99 para Barcode C y 999999 para Barcode L. |
| [getVersionID()](#getversionid) | Actualmente "1" – Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro) |
| [initFromString(constructedCodetext)](#initfromstring) | Inicializa los datos de Mailmark a partir del codetexto construido. |
| [setClass_()](#setclass-) | "0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para potencial) |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | El PC y DP deben cumplir con un formato PAF. Cadena de nueve caracteres que denota internacional "XY11 " (nota los 5 espacios finales) |
| [setFormat()](#setformat) | "0" – Nulo o Prueba "1" – LetraN "2" – Letra Grande |
| [setItemID()](#setitemid) | El valor máximo es 99999999. |
| [setSupplychainID()](#setsupplychainid) | Los valores máximos son 99 para Barcode C y 999999 para Barcode L. |
| [setVersionID()](#setversionid) | Actualmente "1" – Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro) |

### getBarcodeType() {#getbarcodetype}

Obtiene el tipo de código de barras.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para uso futuro potencial) "5" - Deferred (Retail) "6" - Air (Retail) (para uso futuro potencial) "7" - Surface (Retail) (para uso futuro potencial) "8" - Premium (Network Access) "9" - Standard (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

Construye el codetexto a partir de los datos de Mailmark.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

El PC y DP deben cumplir con un formato PAF. Cadena de nueve caracteres que denota internacional "XY11 " (nota los 5 espacios finales) o un patrón de caracteres que denota un código de clasificación doméstico. Un código de clasificación doméstico consta de un código postal externo, un código postal interno y un sufijo de punto de entrega.

### getFormat() {#getformat}

"0" – Nulo o Prueba "1" – Letra "2" – Letra Grande

### getItemID() {#getitemid}

El valor máximo es 99999999.

### getSupplychainID() {#getsupplychainid}

Los valores máximos son 99 para Barcode C y 999999 para Barcode L.

### getVersionID() {#getversionid}

Actualmente "1" – Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro)

### initFromString(constructedCodetext) {#initfromstring}

Inicializa los datos de Mailmark a partir del codetexto construido.

| Parámetro | Descripción |
| --- | --- |
| constructedCodetext | Codetext construido. |

### setClass_() {#setclass-}

"0" - Nulo o Prueba "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (para uso futuro potencial) "5" - Deferred (Retail) "6" - Air (Retail) (para uso futuro potencial) "7" - Surface (Retail) (para uso futuro potencial) "8" - Premium (Network Access) "9" - Standard (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

El PC y DP deben cumplir con un formato PAF. Cadena de nueve caracteres que denota internacional "XY11 " (nota los 5 espacios finales) o un patrón de caracteres que denota un código de clasificación doméstico. Un código de clasificación doméstico consta de un código postal externo, un código postal interno y un sufijo de punto de entrega.

### setFormat() {#setformat}

"0" – Nulo o Prueba "1" – LetraN "2" – Letra Grande

### setItemID() {#setitemid}

El valor máximo es 99999999.

### setSupplychainID() {#setsupplychainid}

Los valores máximos son 99 para Barcode C y 999999 para Barcode L.

### setVersionID() {#setversionid}

Actualmente "1" – Para el código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro)
