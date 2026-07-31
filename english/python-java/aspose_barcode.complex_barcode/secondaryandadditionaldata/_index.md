---
title: "SecondaryAndAdditionalData Class"
linktitle: "SecondaryAndAdditionalData"
articleTitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Python via Java"
description: "Class for storing HIBC LIC secondary and additional data."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

**Module:** `aspose_barcode.complex_barcode.secondary_and_additional_data`


Class for storing HIBC LIC secondary and additional data.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./secondaryandadditionaldata/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](./__eq__/) | `bool` | No | Returns a value indicating whether this instance is equal to a specified SecondaryAndAdditionalData value. |
| [__hash__](./__hash__/) | `int` | No | Returns the hash code for the current instance. |
| [__str__](./__str__/) | `str` | No | Converts data to string format according HIBC LIC specification. |
| [parse_from_string](./parse_from_string/) | `None` | No | Instantiates secondary and additional supplemental data from string format according HIBC LIC specification. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [date_of_manufacture](./date_of_manufacture/) | `datetime` | Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue |
| [expiry_date](./expiry_date/) | `datetime` | Identifies expiry date format. |
| [expiry_date_format](./expiry_date_format/) | `HIBCLICDateFormat` | Identifies expiry date format. |
| [lot_number](./lot_number/) | `Optional[str]` | Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 sybmols length. |
| [quantity](./quantity/) | `int` | Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1 |
| [serial_number](./serial_number/) | `Optional[str]` | Identifies serial number. Serial number must be alphanumeric string up to 18 sybmols length. |
