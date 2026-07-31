---
title: "SwissQRBill Class"
linktitle: "SwissQRBill"
articleTitle: "SwissQRBill"
second_title: "Aspose.BarCode for Python via Java"
description: "SwissQR bill data."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/swissqrbill/
---

## SwissQRBill class

**Module:** `aspose_barcode.complex_barcode.swiss_qr_bill`


SwissQR bill data.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./swissqrbill/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](./__eq__/) | `bool` | No | Determines whether the specified object is equal to the current object. |
| [__hash__](./__hash__/) | `int` | No | Returns the hash code for the current instance. |
| [create_and_set_creditor_reference](./create_and_set_creditor_reference/) | `None` | No | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. Whitespace is removed from the reference |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [account](./account/) | `Optional[str]` | Gets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number. |
| [alternative_schemes](./alternative_schemes/) | `List[AlternativeScheme]` | Gets the alternative payment schemes. A maximum of two schemes with parameters are allowed. |
| [amount](./amount/) | `float` | Gets the payment amount. Valid values are between 0.01 and 999,999,999.99. |
| [bill_information](./bill_information/) | `Optional[str]` | Gets the additional structured bill information. |
| [creditor](./creditor/) | `Optional[Address]` | Gets the creditor address. |
| [currency](./currency/) | `Optional[str]` | Gets the payment currency. Valid values are "CHF" and "EUR". |
| [debtor](./debtor/) | `Optional[Address]` | Gets the debtor address. The debtor is optional. If it is omitted, both setting this field to None or setting an address with all None or empty values is ok. |
| [reference](./reference/) | `Optional[str]` | Gets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting. |
| [unstructured_message](./unstructured_message/) | `Optional[str]` | Gets the additional unstructured message. |
| [version](./version/) | `QrBillStandardVersion` | Gets the version of the SwissQR bill standard. |
