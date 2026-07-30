---
title: "SwissQRBill Class"
linktitle: "SwissQRBill"
articleTitle: "SwissQRBill"
second_title: "Aspose.BarCode for PHP via Java"
description: "SwissQR bill data"
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/swissqrbill/
---

## SwissQRBill class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


SwissQR bill data


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./swissqrbill/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [createAndSetCreditorReference](./createandsetcreditorreference/) | No | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. Whitespace is removed from the reference |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [Account](./account/) | Read/Write | Gets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number. Value: The creditor account number. |
| [AlternativeSchemes](./alternativeschemes/) | Read/Write | Gets ors sets the alternative payment schemes. A maximum of two schemes with parameters are allowed. |
| [Amount](./amount/) | Read/Write | Gets the payment amount. Valid values are between 0.01 and 999,999,999.99. Value: The payment amount. |
| [BillInformation](./billinformation/) | Read/Write | Gets the additional structured bill information. |
| [Creditor](./creditor/) | Read/Write | Gets the creditor address. |
| [Currency](./currency/) | Read/Write | Gets the payment currency. Valid values are "CHF" and "EUR". Value: The payment currency. |
| [Debtor](./debtor/) | Read/Write | Gets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address with all null or empty values is ok. return Address The debtor address. |
| [Reference](./reference/) | Read/Write | Gets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting. |
| [UnstructuredMessage](./unstructuredmessage/) | Read/Write | Gets the additional unstructured message. |
| [Version](./version/) | Read/Write | Gets the version of the SwissQR bill standard. Value: The SwissQR bill standard version. |
