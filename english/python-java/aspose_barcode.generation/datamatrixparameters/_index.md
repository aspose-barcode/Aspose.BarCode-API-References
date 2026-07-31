---
title: "DataMatrixParameters Class"
linktitle: "DataMatrixParameters"
articleTitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for Python via Java"
description: "DataMatrix parameters."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

**Module:** `aspose_barcode.generation.data_matrix_parameters`


DataMatrix parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./datamatrixparameters/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__str__](./__str__/) | `str` | No | Returns a human-readable string representation of this DataMatrixParameters. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [aspect_ratio](./aspect_ratio/) | `float` | Height/Width ratio of 2D BarCode module. |
| [columns](./columns/) | `int` | Columns count. |
| [data_matrix_ecc](./data_matrix_ecc/) | `DataMatrixEccType` | Gets a Datamatrix ECC type. Default value: DataMatrixEccType.ECC_200. |
| [data_matrix_encode_mode](./data_matrix_encode_mode/) | `DataMatrixEncodeMode` | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.AUTO. |
| [data_matrix_version](./data_matrix_version/) | `DataMatrixVersion` | Gets Datamatrix symbol size. |
| [ecc_type](./ecc_type/) | `DataMatrixEccType` |  |
| [eci_encoding](./eci_encoding/) | `ECIEncodings` | Gets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1. |
| [encode_mode](./encode_mode/) | `DataMatrixEncodeMode` |  |
| [macro_characters](./macro_characters/) | `MacroCharacter` | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.Ecc200 or DataMatrixEccType.EccAuto. Cannot be used with EncodeTypes.GS_1_DATA_MATRIX Default value: MacroCharacter.NONE. |
| [reader_programming](./reader_programming/) | `bool` | Used to instruct the reader to interpret the data contained within the symbol. |
| [rows](./rows/) | `int` | Rows count. |
| [structured_append_barcode_id](./structured_append_barcode_id/) | `int` | Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [structured_append_barcodes_count](./structured_append_barcodes_count/) | `int` | Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [structured_append_file_id](./structured_append_file_id/) | `int` | File ID for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [version](./version/) | `DataMatrixVersion` |  |
