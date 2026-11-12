---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Datos de factura SwissQR"
type: docs
weight: 920
url: /es/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

Datos de factura SwissQR

```js
new SwissQRBill()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Crea y establece una referencia de acreedor ISO11649 a partir de una cadena cruda añadiendo el prefijo "RF" y el módulo 97 che |
| [equals(obj)](#equals) | Determina si el objeto especificado es igual al objeto actual. |
| [getAccount()](#getaccount) | Obtiene el número de cuenta del acreedor. Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein. Espacio |
| [getAlternativeSchemes()](#getalternativeschemes) | Obtiene o establece los esquemas de pago alternativos. Se permite un máximo de dos esquemas con parámetros. |
| [getAmount()](#getamount) | Obtiene el monto del pago. Los valores válidos están entre 0,01 y 999.999.999,99. |
| [getBillInformation()](#getbillinformation) | Obtiene la información adicional estructurada de la factura. |
| [getCreditor()](#getcreditor) | Obtiene la dirección del acreedor. |
| [getCurrency()](#getcurrency) | Obtiene la moneda del pago. Los valores válidos son "CHF" y "EUR". |
| [getDebtor()](#getdebtor) | Obtiene la dirección del deudor. El deudor es opcional. Si se omite, tanto establecer este campo a null como establecer una dirección |
| [getReference()](#getreference) | Obtiene la referencia de pago del acreedor. La referencia es obligatoria para los IBAN SwissQR, i.e.IBANs en el rango CHxx30000xxxxx |
| [getUnstructuredMessage()](#getunstructuredmessage) | Obtiene el mensaje adicional no estructurado. |
| [getVersion()](#getversion) | Obtiene la versión del estándar de factura SwissQR. |
| [hashCode()](#hashcode) | Obtiene el código hash de esta instancia. |
| [setAccount(value:)](#setaccount) | Establece el número de cuenta del acreedor. Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein. Espacio |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Obtiene o establece los esquemas de pago alternativos. Se permite un máximo de dos esquemas con parámetros. |
| [setAmount(value)](#setamount) | Establece el importe del pago. Los valores válidos están entre 0.01 y 999,999,999.99. |
| [setBillInformation(value:)](#setbillinformation) | Establece la información de factura estructurada adicional. |
| [setCreditor(value:)](#setcreditor) | Establece la dirección del acreedor. |
| [setCurrency(value)](#setcurrency) | Establece la moneda del pago. |
| [setDebtor(value:)](#setdebtor) | Establece la dirección del deudor. El deudor es opcional. Si se omite, tanto establecer este campo a null como establecer una dirección |
| [setReference(value)](#setreference) | Establece la referencia de pago del acreedor. La referencia es obligatoria para los IBAN SwissQR, i.e.IBANs en el rango CHxx30000xxxxx |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Establece el mensaje adicional no estructurado. |
| [setVersion(value)](#setversion) | Establece la versión del estándar de factura SwissQR. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Crea y establece una referencia de acreedor ISO11649 a partir de una cadena sin procesar prefijando la cadena con "RF" y el checksum módulo 97. Se eliminan los espacios en blanco de la referencia.

| Parámetro | Descripción |
| --- | --- |
| rawReference | La referencia sin procesar. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Determina si el objeto especificado es igual al objeto actual.

| Parámetro | Descripción |
| --- | --- |
| obj | El objeto a comparar con el objeto actual. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Obtiene el número de cuenta del acreedor. Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein. Se permiten espacios en el número de cuenta.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Obtiene o establece los esquemas de pago alternativos. Se permite un máximo de dos esquemas con parámetros.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Obtiene el monto del pago. Los valores válidos están entre 0,01 y 999.999.999,99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Obtiene la información adicional estructurada de la factura.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Obtiene la dirección del acreedor.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Obtiene la moneda del pago. Los valores válidos son "CHF" y "EUR".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Obtiene la dirección del deudor. El deudor es opcional. Si se omite, tanto establecer este campo a null como establecer una dirección con todos los valores null o vacíos está bien.

**Returns:** The debtor address.

### getReference() {#getreference}

Obtiene la referencia de pago del acreedor. La referencia es obligatoria para los IBAN SwissQR, i.e.IBANs en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx. Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente al formulario de referencia ISR) o una referencia de acreedor válida según ISO 11649 ("RFxxxx"). Ambas pueden contener espacios para el formato.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Obtiene el mensaje adicional no estructurado.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Obtiene la versión del estándar de factura SwissQR.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Obtiene el código hash de esta instancia.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Establece el número de cuenta del acreedor. Los números de cuenta deben ser IBAN válidos de un banco de Suiza o Liechtenstein. Se permiten espacios en el número de cuenta.

| Parámetro | Descripción |
| --- | --- |
| valor: | El número de cuenta del acreedor. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Obtiene o establece los esquemas de pago alternativos. Se permite un máximo de dos esquemas con parámetros.

| Parámetro | Descripción |
| --- | --- |
| valor: | Los esquemas de pago alternativos. |

### setAmount(value) {#setamount}

Establece el importe del pago. Los valores válidos están entre 0.01 y 999,999,999.99.

| Parámetro | Descripción |
| --- | --- |
| valor | El importe del pago. |

### setBillInformation(value:) {#setbillinformation}

Establece la información de factura estructurada adicional.

| Parámetro | Descripción |
| --- | --- |
| valor: | La información de factura estructurada. |

### setCreditor(value:) {#setcreditor}

Establece la dirección del acreedor.

| Parámetro | Descripción |
| --- | --- |
| valor: | La dirección del acreedor. |

### setCurrency(value) {#setcurrency}

Establece la moneda del pago.

| Parámetro | Descripción |
| --- | --- |
| valor | Los valores válidos son "CHF" y "EUR". |

### setDebtor(value:) {#setdebtor}

Establece la dirección del deudor. El deudor es opcional. Si se omite, tanto establecer este campo a null como establecer una dirección con todos los valores null o vacíos es correcto.

| Parámetro | Descripción |
| --- | --- |
| valor: | La dirección del deudor. |

### setReference(value) {#setreference}

Establece la referencia de pago del acreedor. La referencia es obligatoria para los IBAN SwissQR, es decir, los IBAN en el rango CHxx30000xxxxxx hasta CHxx31999xxxxx. Si se especifica, la referencia debe ser una referencia SwissQR válida (correspondiente al formulario de referencia ISR) o una referencia de acreedor válida según la ISO 11649 ("RFxxxx"). Ambas pueden contener espacios para el formato.

| Parámetro | Descripción |
| --- | --- |
| valor | La referencia de pago del acreedor. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Establece el mensaje adicional no estructurado.

| Parámetro | Descripción |
| --- | --- |
| valor: | El mensaje no estructurado. |

### setVersion(value) {#setversion}

Establece la versión del estándar de factura SwissQR.

| Parámetro | Descripción |
| --- | --- |
| valor | La versión estándar de la factura SwissQR. |
