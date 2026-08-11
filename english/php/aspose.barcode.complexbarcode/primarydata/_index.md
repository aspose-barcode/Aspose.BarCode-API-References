---
title: "PrimaryData"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for storing HIBC LIC primary data."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/primarydata/
---

## PrimaryData class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Class for storing HIBC LIC primary data.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [construct](#construct) | Yes |  |
| [parseFromString](#parsefromstring) | No | Instantiates primary data from string format according HIBC LIC specification. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [LabelerIdentificationCode](#labeleridentificationcode) | Read/Write | Identifies date of labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic. |
| [ProductOrCatalogNumber](#productorcatalognumber) | Read/Write | Identifies product or catalog number. Product or catalog number must be alphanumeric string up to 18 sybmols length. |
| [UnitOfMeasureID](#unitofmeasureid) | Read/Write | Identifies unit of measure ID. Unit of measure ID must be integer value from 0 to 9. |

### PrimaryData__construct() {#constructor}

### constructconstruct($java_class) (static) {#construct}

| Parameter | Type | Description |
| --- | --- | --- |
| `$java_class` | `` |  |

### parseFromStringparseFromString(string $primaryDataCodetext) {#parsefromstring}

Instantiates primary data from string format according HIBC LIC specification.

| Parameter | Type | Description |
| --- | --- | --- |
| `$primaryDataCodetext` | `string` | Formatted string. |

### LabelerIdentificationCode {#labeleridentificationcode}

**Access:** Read/Write

Identifies date of labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic.

Identifies date of labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### ProductOrCatalogNumber {#productorcatalognumber}

**Access:** Read/Write

Identifies product or catalog number. Product or catalog number must be alphanumeric string up to 18 sybmols length.

Identifies product or catalog number. Product or catalog number must be alphanumeric string up to 18 sybmols length.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### UnitOfMeasureID {#unitofmeasureid}

**Access:** Read/Write

Identifies unit of measure ID. Unit of measure ID must be integer value from 0 to 9.

Identifies unit of measure ID. Unit of measure ID must be integer value from 0 to 9.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

