---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "Aztec parameters."
type: docs
weight: 10
url: /php/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

**Namespace:** `Aspose.Barcode.Generation`


Aztec parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isReaderInitialization](#isreaderinitialization) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [setReaderInitialization](#setreaderinitialization) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AspectRatio](#aspectratio) | Read/Write | Height/Width ratio of 2D BarCode module. |
| [AztecEncodeMode](#aztecencodemode) | Read/Write | Gets a Aztec encode mode. Default value: Auto. |
| [AztecErrorLevel](#aztecerrorlevel) | Read/Write | Level of error correction of Aztec types of barcode. Value should between 5 to 95. |
| [AztecSymbolMode](#aztecsymbolmode) | Read/Write | Gets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto. |
| [ECIEncoding](#eciencoding) | Read/Write | Gets ECI encoding. Used when AztecEncodeMode is Auto. Default value: ISO-8859-1 |
| [EncodeMode](#encodemode) | Read/Write | Gets a Aztec encode mode. Default value: Auto. |
| [ErrorLevel](#errorlevel) | Read/Write | Level of error correction of Aztec types of barcode. Value should between 5 to 95. |
| [LayersCount](#layerscount) | Read/Write | Gets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto). |
| [StructuredAppendBarcodeId](#structuredappendbarcodeid) | Read/Write | Barcode ID for Structured Append mode of Aztec barcode. Barcode ID should be in range from 1 to barcodes count. Default value: 0 |
| [StructuredAppendBarcodesCount](#structuredappendbarcodescount) | Read/Write | Barcodes count for Structured Append mode of Aztec barcode. Barcodes count should be in range from 1 to 26. Default value: 0 |
| [StructuredAppendFileId](#structuredappendfileid) | Read/Write | File ID for Structured Append mode of Aztec barcode (optional field). File ID should not contain spaces. Default value: empty string |
| [SymbolMode](#symbolmode) | Read/Write | Gets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto. |

### AztecParameters__construct(AztecParametersDTO $aztecParametersDto) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$aztecParametersDto` | `AztecParametersDTO` |  |

### isReaderInitializationisReaderInitialization() {#isreaderinitialization}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

### setReaderInitializationsetReaderInitialization(bool $value) {#setreaderinitialization}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

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

### AztecEncodeMode {#aztecencodemode}

**Access:** Read/Write

Gets a Aztec encode mode. Default value: Auto.

Sets a Aztec encode mode. Default value: Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### AztecErrorLevel {#aztecerrorlevel}

**Access:** Read/Write

Level of error correction of Aztec types of barcode. Value should between 5 to 95.

Level of error correction of Aztec types of barcode. Value should between 5 to 95.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### AztecSymbolMode {#aztecsymbolmode}

**Access:** Read/Write

Gets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto.

Sets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### ECIEncoding {#eciencoding}

**Access:** Read/Write

Gets ECI encoding. Used when AztecEncodeMode is Auto. Default value: ISO-8859-1

Gets ECI encoding. Used when AztecEncodeMode is Auto. Default value: ISO-8859-1

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### EncodeMode {#encodemode}

**Access:** Read/Write

**Returns:** a Aztec encode mode.

Gets a Aztec encode mode. Default value: Auto.

Sets a Aztec encode mode. Default value: Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` | a Aztec encode mode. |

### ErrorLevel {#errorlevel}

**Access:** Read/Write

Level of error correction of Aztec types of barcode. Value should between 5 to 95.

Level of error correction of Aztec types of barcode. Value should between 5 to 95.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### LayersCount {#layerscount}

**Access:** Read/Write

Gets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto).

Sets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto).

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppendBarcodeId {#structuredappendbarcodeid}

**Access:** Read/Write

Barcode ID for Structured Append mode of Aztec barcode. Barcode ID should be in range from 1 to barcodes count. Default value: 0

Barcode ID for Structured Append mode of Aztec barcode. Barcode ID should be in range from 1 to barcodes count. Default value: 0

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppendBarcodesCount {#structuredappendbarcodescount}

**Access:** Read/Write

Barcodes count for Structured Append mode of Aztec barcode. Barcodes count should be in range from 1 to 26. Default value: 0

Barcodes count for Structured Append mode of Aztec barcode. Barcodes count should be in range from 1 to 26. Default value: 0

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppendFileId {#structuredappendfileid}

**Access:** Read/Write

File ID for Structured Append mode of Aztec barcode (optional field). File ID should not contain spaces. Default value: empty string

File ID for Structured Append mode of Aztec barcode (optional field). File ID should not contain spaces. Default value: empty string

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### SymbolMode {#symbolmode}

**Access:** Read/Write

Gets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto.

Sets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

