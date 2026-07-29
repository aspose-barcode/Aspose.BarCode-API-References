---
title: "SwissQRBill Class"
linktitle: "SwissQRBill"
articleTitle: "SwissQRBill"
second_title: "Aspose.BarCode for PHP via Java"
description: "SwissQR bill data"
type: docs
weight: 10
url: /php/aspose/barcode/complexbarcode/swissqrbill/
---

## SwissQRBill class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


SwissQR bill data


## Constructors

| Name | Description |
| --- | --- |
| [__construct](/php/aspose/barcode/complexbarcode/swissqrbill/swissqrbill/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [createAndSetCreditorReference](/php/aspose/barcode/complexbarcode/swissqrbill/createandsetcreditorreference/) | No | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. Whitespace is removed from the reference |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [Account](/php/aspose/barcode/complexbarcode/swissqrbill/account/) | Read/Write | Gets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number. Value: The creditor account number. |
| [AlternativeSchemes](/php/aspose/barcode/complexbarcode/swissqrbill/alternativeschemes/) | Read/Write | Gets ors sets the alternative payment schemes. A maximum of two schemes with parameters are allowed. |
| [Amount](/php/aspose/barcode/complexbarcode/swissqrbill/amount/) | Read/Write | Gets the payment amount. Valid values are between 0.01 and 999,999,999.99. Value: The payment amount. |
| [BillInformation](/php/aspose/barcode/complexbarcode/swissqrbill/billinformation/) | Read/Write | Gets the additional structured bill information. |
| [Creditor](/php/aspose/barcode/complexbarcode/swissqrbill/creditor/) | Read/Write | Gets the creditor address. |
| [Currency](/php/aspose/barcode/complexbarcode/swissqrbill/currency/) | Read/Write | Gets the payment currency. Valid values are "CHF" and "EUR". Value: The payment currency. |
| [Debtor](/php/aspose/barcode/complexbarcode/swissqrbill/debtor/) | Read/Write | Gets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address with all null or empty values is ok. return Address The debtor address. |
| [Reference](/php/aspose/barcode/complexbarcode/swissqrbill/reference/) | Read/Write | Gets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting. |
| [UnstructuredMessage](/php/aspose/barcode/complexbarcode/swissqrbill/unstructuredmessage/) | Read/Write | Gets the additional unstructured message. |
| [Version](/php/aspose/barcode/complexbarcode/swissqrbill/version/) | Read/Write | Gets the version of the SwissQR bill standard. Value: The SwissQR bill standard version. |
