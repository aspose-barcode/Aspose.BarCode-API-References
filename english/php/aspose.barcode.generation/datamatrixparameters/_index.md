---
title: "DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "DataMatrix parameters."
type: docs
weight: 10
url: /php/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

**Namespace:** `Aspose.Barcode.Generation`


DataMatrix parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isReaderProgramming](#isreaderprogramming) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false |
| [setReaderProgramming](#setreaderprogramming) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AspectRatio](#aspectratio) | Read/Write | Height/Width ratio of 2D BarCode module. |
| [Columns](#columns) | Read/Write | Columns count. |
| [DataMatrixEcc](#datamatrixecc) | Read/Write | Gets a Datamatrix ECC type. Default value: DataMatrixEccType::ECC_200. |
| [DataMatrixEncodeMode](#datamatrixencodemode) | Read/Write | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode::AUTO. |
| [DataMatrixVersion](#datamatrixversion) | Read/Write | Gets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto. |
| [ECIEncoding](#eciencoding) | Read/Write | Gets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1 |
| [EccType](#ecctype) | Read/Write | Gets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200. |
| [EncodeMode](#encodemode) | Read/Write | Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto. |
| [MacroCharacters](#macrocharacters) | Read/Write | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.Ecc200 or DataMatrixEccType.EccAuto. Cannot be used with EncodeTypes::GS_1_DATA_MATRIX Default value: MacroCharacter::NONE. |
| [Rows](#rows) | Read/Write | Rows count. |
| [StructuredAppendBarcodeId](#structuredappendbarcodeid) | Read/Write | Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [StructuredAppendBarcodesCount](#structuredappendbarcodescount) | Read/Write | Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [StructuredAppendFileId](#structuredappendfileid) | Read/Write | File ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [Version](#version) | Read/Write | Gets a Datamatrix symbol size. Default value: Version.Auto. |

### DataMatrixParameters__construct(DataMatrixParametersDTO $dataMatrixParametersDto) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$dataMatrixParametersDto` | `DataMatrixParametersDTO` |  |

### isReaderProgrammingisReaderProgramming() {#isreaderprogramming}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false

### setReaderProgrammingsetReaderProgramming(bool $value) {#setreaderprogramming}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false

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

Columns count.

Columns count.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### DataMatrixEcc {#datamatrixecc}

**Access:** Read/Write

Gets a Datamatrix ECC type. Default value: DataMatrixEccType::ECC_200.

Sets a Datamatrix ECC type. Default value: DataMatrixEccType::ECC_200.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### DataMatrixEncodeMode {#datamatrixencodemode}

**Access:** Read/Write

Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode::AUTO.

Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode::AUTO.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### DataMatrixVersion {#datamatrixversion}

**Access:** Read/Write

Gets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto.

Sets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### ECIEncoding {#eciencoding}

**Access:** Read/Write

Gets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1

Sets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### EccType {#ecctype}

**Access:** Read/Write

**Returns:** a Datamatrix ECC type.

Gets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

Sets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` | a Datamatrix ECC type. |

### EncodeMode {#encodemode}

**Access:** Read/Write

Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto.

Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### MacroCharacters {#macrocharacters}

**Access:** Read/Write

ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.Ecc200 or DataMatrixEccType.EccAuto. Cannot be used with EncodeTypes::GS_1_DATA_MATRIX Default value: MacroCharacter::NONE.

ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.Ecc200 or DataMatrixEccType.EccAuto. Cannot be used with EncodeTypes::GS_1_DATA_MATRIX Default value: MacroCharacter::NONE.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### Rows {#rows}

**Access:** Read/Write

Rows count.

Rows count.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppendBarcodeId {#structuredappendbarcodeid}

**Access:** Read/Write

Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0

Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppendBarcodesCount {#structuredappendbarcodescount}

**Access:** Read/Write

Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0

Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppendFileId {#structuredappendfileid}

**Access:** Read/Write

File ID for Structured Append mode of Datamatrix barcode. Default value: 0

File ID for Structured Append mode of Datamatrix barcode. Default value: 0

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### Version {#version}

**Access:** Read/Write

**Returns:** a Datamatrix symbol size.

Gets a Datamatrix symbol size. Default value: Version.Auto.

Sets a Datamatrix symbol size. Default value: Version.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` | a Datamatrix symbol size. |

