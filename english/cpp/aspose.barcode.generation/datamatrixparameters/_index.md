---
title: Aspose::BarCode::Generation::DataMatrixParameters class
linktitle: DataMatrixParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::DataMatrixParameters class. DataMatrix parameters in C++.'
type: docs
weight: 1800
url: /cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


DataMatrix parameters.

```cpp
class DataMatrixParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [get_Columns](./get_columns/)() const | Columns count. |
| [get_DataMatrixEcc](./get_datamatrixecc/)() const | Gets a Datamatrix ECC type. Default value: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_DataMatrixEncodeMode](./get_datamatrixencodemode/)() const | Encode mode of Datamatrix barcode. Default value: [DataMatrixEncodeMode.Auto](../datamatrixencodemode/). |
| [get_DataMatrixVersion](./get_datamatrixversion/)() const | Gets a Datamatrix symbol size. Default value: [DataMatrixVersion.Auto](../datamatrixversion/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Gets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1. |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with [DataMatrixEccType.Ecc200](../datamatrixecctype/) or [DataMatrixEccType.EccAuto](../datamatrixecctype/). Cannot be used with [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) Default value: MacroCharacters.None. |
| [get_Rows](./get_rows/)() const | Rows count. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | File ID for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [set_AspectRatio](./set_aspectratio/)(float) | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [set_Columns](./set_columns/)(int32_t) | Columns count. |
| [set_DataMatrixEcc](./set_datamatrixecc/)(DataMatrixEccType) | Sets a Datamatrix ECC type. Default value: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_DataMatrixEncodeMode](./set_datamatrixencodemode/)(Aspose::BarCode::Generation::DataMatrixEncodeMode) | Encode mode of Datamatrix barcode. Default value: [DataMatrixEncodeMode.Auto](../datamatrixencodemode/). |
| [set_DataMatrixVersion](./set_datamatrixversion/)(Aspose::BarCode::Generation::DataMatrixVersion) | Sets a Datamatrix symbol size. Default value: [DataMatrixVersion.Auto](../datamatrixversion/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Sets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1. |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with [DataMatrixEccType.Ecc200](../datamatrixecctype/) or [DataMatrixEccType.EccAuto](../datamatrixecctype/). Cannot be used with [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) Default value: MacroCharacters.None. |
| [set_Rows](./set_rows/)(int32_t) | Rows count. |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | File ID for Structured Append mode of Datamatrix barcode. Default value: 0. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [DataMatrixParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
