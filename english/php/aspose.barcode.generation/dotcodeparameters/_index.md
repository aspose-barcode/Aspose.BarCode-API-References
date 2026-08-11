---
title: "DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "DotCode parameters."
type: docs
weight: 10
url: /php/aspose.barcode.generation/dotcodeparameters/
---

## DotCodeParameters class

**Namespace:** `Aspose.Barcode.Generation`


DotCode parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isReaderInitialization](#isreaderinitialization) | No | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [setReaderInitialization](#setreaderinitialization) | No | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AspectRatio](#aspectratio) | Read/Write | Height/Width ratio of 2D BarCode module. |
| [Columns](#columns) | Read/Write | Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1 |
| [DotCodeEncodeMode](#dotcodeencodemode) | Read/Write | Identifies DotCode encode mode. Default value: Auto. |
| [DotCodeStructuredAppendModeBarcodeId](#dotcodestructuredappendmodebarcodeid) | Read/Write | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [DotCodeStructuredAppendModeBarcodesCount](#dotcodestructuredappendmodebarcodescount) | Read/Write | Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [ECIEncoding](#eciencoding) | Read/Write | Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [EncodeMode](#encodemode) | Read/Write | Identifies DotCode encode mode. Default value: Auto. |
| [Rows](#rows) | Read/Write | Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1 |
| [StructuredAppendModeBarcodeId](#structuredappendmodebarcodeid) | Read/Write | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [StructuredAppendModeBarcodesCount](#structuredappendmodebarcodescount) | Read/Write | Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |

### DotCodeParameters__construct(DotCodeParametersDTO $dotCodeParametersDto) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$dotCodeParametersDto` | `DotCodeParametersDTO` |  |

### isReaderInitializationisReaderInitialization() {#isreaderinitialization}

Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

### setReaderInitializationsetReaderInitialization(bool $value) {#setreaderinitialization}

Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `bool` |  |

### AspectRatio {#aspectratio}

**Access:** Read/Write

Height/Width ratio of 2D BarCode module.

Height/Width ratio of 2D BarCode module.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `float` |  |

### Columns {#columns}

**Access:** Read/Write

Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1

Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### DotCodeEncodeMode {#dotcodeencodemode}

**Access:** Read/Write

Identifies DotCode encode mode. Default value: Auto.

Identifies DotCode encode mode. Default value: Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### DotCodeStructuredAppendModeBarcodeId {#dotcodestructuredappendmodebarcodeid}

**Access:** Read/Write

Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### DotCodeStructuredAppendModeBarcodesCount {#dotcodestructuredappendmodebarcodescount}

**Access:** Read/Write

Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35.

Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### ECIEncoding {#eciencoding}

**Access:** Read/Write

Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1

Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### EncodeMode {#encodemode}

**Access:** Read/Write

Identifies DotCode encode mode. Default value: Auto.

Identifies DotCode encode mode. Default value: Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### Rows {#rows}

**Access:** Read/Write

Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1

Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppendModeBarcodeId {#structuredappendmodebarcodeid}

**Access:** Read/Write

Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppendModeBarcodesCount {#structuredappendmodebarcodescount}

**Access:** Read/Write

Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35.

Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

