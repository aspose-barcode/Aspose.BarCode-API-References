---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "SwissQR bill data"
type: docs
weight: 920
url: /nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR bill data

```js
new SwissQRBill()
```

## Methods

| Name | Description |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 che |
| [equals(obj)](#equals) | Determines whether the specified object is equal to the current object. |
| [getAccount()](#getaccount) | Gets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Space |
| [getAlternativeSchemes()](#getalternativeschemes) | Gets ors sets the alternative payment schemes. A maximum of two schemes with parameters are allowed. |
| [getAmount()](#getamount) | Gets the payment amount. Valid values are between 0.01 and 999,999,999.99. |
| [getBillInformation()](#getbillinformation) | Gets the additional structured bill information. |
| [getCreditor()](#getcreditor) | Gets the creditor address. |
| [getCurrency()](#getcurrency) | Gets the payment currency. Valid values are "CHF" and "EUR". |
| [getDebtor()](#getdebtor) | Gets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address |
| [getReference()](#getreference) | Gets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxx |
| [getUnstructuredMessage()](#getunstructuredmessage) | Gets the additional unstructured message. |
| [getVersion()](#getversion) | Gets the version of the SwissQR bill standard. |
| [hashCode()](#hashcode) | Gets the hash code for this instance. |
| [setAccount(value:)](#setaccount) | Sets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Space |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Gets or sets the alternative payment schemes. A maximum of two schemes with parameters are allowed. |
| [setAmount(value)](#setamount) | Sets the payment amount. Valid values are between 0.01 and 999,999,999.99. |
| [setBillInformation(value:)](#setbillinformation) | Sets the additional structured bill information. |
| [setCreditor(value:)](#setcreditor) | Sets the creditor address. |
| [setCurrency(value)](#setcurrency) | Sets the payment currency. |
| [setDebtor(value:)](#setdebtor) | Sets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address |
| [setReference(value)](#setreference) | Sets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxx |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Sets the additional unstructured message. |
| [setVersion(value)](#setversion) | Sets the version of the SwissQR bill standard. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. Whitespace is removed from the reference

| Parameter | Description |
| --- | --- |
| rawReference | The raw reference. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Determines whether the specified object is equal to the current object.

| Parameter | Description |
| --- | --- |
| obj | The object to compare with the current object. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Gets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Gets ors sets the alternative payment schemes. A maximum of two schemes with parameters are allowed.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Gets the payment amount. Valid values are between 0.01 and 999,999,999.99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Gets the additional structured bill information.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Gets the creditor address.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Gets the payment currency. Valid values are "CHF" and "EUR".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Gets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address with all null or empty values is ok.

**Returns:** The debtor address.

### getReference() {#getreference}

Gets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Gets the additional unstructured message.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Gets the version of the SwissQR bill standard.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Gets the hash code for this instance.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Sets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number.

| Parameter | Description |
| --- | --- |
| value: | The creditor account number. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Gets or sets the alternative payment schemes. A maximum of two schemes with parameters are allowed.

| Parameter | Description |
| --- | --- |
| value: | The alternative payment schemes. |

### setAmount(value) {#setamount}

Sets the payment amount. Valid values are between 0.01 and 999,999,999.99.

| Parameter | Description |
| --- | --- |
| value | The payment amount. |

### setBillInformation(value:) {#setbillinformation}

Sets the additional structured bill information.

| Parameter | Description |
| --- | --- |
| value: | The structured bill information. |

### setCreditor(value:) {#setcreditor}

Sets the creditor address.

| Parameter | Description |
| --- | --- |
| value: | The creditor address. |

### setCurrency(value) {#setcurrency}

Sets the payment currency.

| Parameter | Description |
| --- | --- |
| value | Valid values are "CHF" and "EUR". |

### setDebtor(value:) {#setdebtor}

Sets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address with all null or empty values is ok.

| Parameter | Description |
| --- | --- |
| value: | The debtor address. |

### setReference(value) {#setreference}

Sets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

| Parameter | Description |
| --- | --- |
| value | The creditor payment reference. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Sets the additional unstructured message.

| Parameter | Description |
| --- | --- |
| value: | The unstructured message. |

### setVersion(value) {#setversion}

Sets the version of the SwissQR bill standard.

| Parameter | Description |
| --- | --- |
| value | The SwissQR bill standard version. |
