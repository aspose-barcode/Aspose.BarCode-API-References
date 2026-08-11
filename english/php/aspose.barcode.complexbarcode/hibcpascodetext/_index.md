---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for encoding and decoding the text embedded in the HIBC PAS code."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/hibcpascodetext/
---

## HIBCPASCodetext class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Class for encoding and decoding the text embedded in the HIBC PAS code.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [addHIBCPASRecord](#addhibcpasrecord) | No | Adds new record |
| [addRecord](#addrecord) | No | Adds new record |
| [clear](#clear) | No | Clears records list |
| [construct](#construct) | Yes | HIBCPASRecord constructor |
| [initFromString](#initfromstring) | No | Initializes instance from constructed codetext. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [BarcodeType](#barcodetype) | Read/Write | Gets barcode type. |
| [ConstructedCodetext](#constructedcodetext) | Read-only | Constructs codetext |
| [DataLocation](#datalocation) | Read/Write | Identifies data location. |
| [Records](#records) | Read-only | Gets records list |

### HIBCPASCodetext__construct() {#constructor}

### addHIBCPASRecordaddHIBCPASRecord(HIBCPASRecord $record) {#addhibcpasrecord}

Adds new record

| Parameter | Type | Description |
| --- | --- | --- |
| `$record` | `HIBCPASRecord` |  |

**Returns:** void

### addRecordaddRecord(int $dataType, string $data) {#addrecord}

Adds new record

| Parameter | Type | Description |
| --- | --- | --- |
| `$dataType` | `int` |  |
| `$data` | `string` |  |

### clearclear() {#clear}

Clears records list

### constructconstruct($HIBCPASCodetextDto) (static) {#construct}

HIBCPASRecord constructor

| Parameter | Type | Description |
| --- | --- | --- |
| `$HIBCPASCodetextDto` | `` |  |

### initFromStringinitFromString(string $constructedCodetext) {#initfromstring}

Initializes instance from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$constructedCodetext` | `string` |  |

**Returns:** void

### BarcodeType {#barcodetype}

**Access:** Read/Write

**Returns:** int Barcode type.

Gets barcode type.

Gets or sets barcode type. HIBC PAS codetext can be encoded using HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS and HIBCQRPAS encode types. Default value: HIBCCode39PAS.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### ConstructedCodetext {#constructedcodetext}

**Access:** Read-only

**Returns:** string Constructed codetext

Constructs codetext

### DataLocation {#datalocation}

**Access:** Read/Write

Identifies data location.

Identifies data location.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### Records {#records}

**Access:** Read-only

**Returns:** List of records

Gets records list

