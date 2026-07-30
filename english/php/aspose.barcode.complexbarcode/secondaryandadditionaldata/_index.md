---
title: "SecondaryAndAdditionalData Class"
linktitle: "SecondaryAndAdditionalData"
articleTitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for storing HIBC LIC secondary and additional data."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Class for storing HIBC LIC secondary and additional data.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./secondaryandadditionaldata/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [construct](./construct/) | Yes |  |
| [parseFromString](./parsefromstring/) | No | Instantiates secondary and additional supplemental data from string format according HIBC LIC specification. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [DateOfManufacture](./dateofmanufacture/) | Read/Write | Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue |
| [ExpiryDate](./expirydate/) | Read/Write | Identifies expiry date. Will be used if ExpiryDateFormat is not set to None. |
| [ExpiryDateFormat](./expirydateformat/) | Read/Write | Identifies expiry date format. |
| [LotNumber](./lotnumber/) | Read/Write | Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 sybmols length. . |
| [Quantity](./quantity/) | Read/Write | Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1 |
| [SerialNumber](./serialnumber/) | Read/Write | Identifies serial number. Serial number must be alphanumeric string up to 18 sybmols length. |
