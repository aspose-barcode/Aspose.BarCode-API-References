---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for PHP via Java"
description: "Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3. This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3. This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.


## Methods

| Name | Static | Description |
| --- | --- | --- |
| [initFromString](#initfromstring) | No | Initializes instance from constructed codetext. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [ConstructedCodetext](#constructedcodetext) | Read-only | Constructs codetext |
| [CountryCode](#countrycode) | Read/Write | Identifies 3 digit country code. |
| [PostalCode](#postalcode) | Read/Write | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [SecondMessage](#secondmessage) | Read/Write | Identifies second message of the barcode. |
| [ServiceCategory](#servicecategory) | Read/Write | Identifies 3 digit service category. |
### initFromStringinitFromString(string $constructedCodetext) {#initfromstring}

Initializes instance from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$constructedCodetext` | `string` |  |

### ConstructedCodetext {#constructedcodetext}

**Access:** Read-only

**Returns:** string Constructed codetext

Constructs codetext

### CountryCode {#countrycode}

**Access:** Read/Write

Identifies 3 digit country code.

Identifies 3 digit country code.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### PostalCode {#postalcode}

**Access:** Read/Write

Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3.

Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### SecondMessage {#secondmessage}

**Access:** Read/Write

Identifies second message of the barcode.

Identifies second message of the barcode.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `MaxiCodeSecondMessage` |  |

### ServiceCategory {#servicecategory}

**Access:** Read/Write

Identifies 3 digit service category.

Identifies 3 digit service category.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

