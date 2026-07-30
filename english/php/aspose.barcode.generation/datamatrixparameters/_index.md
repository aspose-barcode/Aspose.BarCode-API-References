---
title: "DataMatrixParameters Class"
linktitle: "DataMatrixParameters"
articleTitle: "DataMatrixParameters"
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
| [__construct](./datamatrixparameters/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isReaderProgramming](./isreaderprogramming/) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false |
| [setReaderProgramming](./setreaderprogramming/) | No | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AspectRatio](./aspectratio/) | Read/Write | Height/Width ratio of 2D BarCode module. |
| [Columns](./columns/) | Read/Write | Columns count. |
| [DataMatrixEcc](./datamatrixecc/) | Read/Write | Gets a Datamatrix ECC type. Default value: DataMatrixEccType::ECC_200. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | Read/Write | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode::AUTO. |
| [DataMatrixVersion](./datamatrixversion/) | Read/Write | Gets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto. |
| [ECIEncoding](./eciencoding/) | Read/Write | Gets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1 |
| [EccType](./ecctype/) | Read/Write | Gets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200. |
| [EncodeMode](./encodemode/) | Read/Write | Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto. |
| [MacroCharacters](./macrocharacters/) | Read/Write | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.Ecc200 or DataMatrixEccType.EccAuto. Cannot be used with EncodeTypes::GS_1_DATA_MATRIX Default value: MacroCharacter::NONE. |
| [Rows](./rows/) | Read/Write | Rows count. |
| [StructuredAppendBarcodeId](./structuredappendbarcodeid/) | Read/Write | Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [StructuredAppendBarcodesCount](./structuredappendbarcodescount/) | Read/Write | Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [StructuredAppendFileId](./structuredappendfileid/) | Read/Write | File ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [Version](./version/) | Read/Write | Gets a Datamatrix symbol size. Default value: Version.Auto. |
