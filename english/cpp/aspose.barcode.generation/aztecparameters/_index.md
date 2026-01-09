---
title: Aspose::BarCode::Generation::AztecParameters class
linktitle: AztecParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::AztecParameters class. Aztec parameters in C++.'
type: docs
weight: 300
url: /cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec parameters.

```cpp
class AztecParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [get_AztecEncodeMode](./get_aztecencodemode/)() | Gets a Aztec encode mode. Default value: Auto. |
| [get_AztecErrorLevel](./get_aztecerrorlevel/)() | Level of error correction of Aztec types of barcode. Value should between 5 to 95. |
| [get_AztecSymbolMode](./get_aztecsymbolmode/)() | Gets a Aztec Symbol mode. Default value: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Gets ECI encoding. Used when AztecEncodeMode is Auto. Default value: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Gets a Aztec encode mode. Default value: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() | Level of error correction of Aztec types of barcode. Value should between 5 to 95. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [get_LayersCount](./get_layerscount/)() const | Gets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Barcode ID for Structured Append mode of Aztec barcode. Barcode ID should be in range from 1 to barcodes count. Default value: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Barcodes count for Structured Append mode of Aztec barcode. Barcodes count should be in range from 1 to 26. Default value: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | File ID for Structured Append mode of Aztec barcode (optional field). File ID should not contain spaces. Default value: empty string |
| [get_SymbolMode](./get_symbolmode/)() const | Gets a Aztec Symbol mode. Default value: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [set_AztecEncodeMode](./set_aztecencodemode/)(Aspose::BarCode::Generation::AztecEncodeMode) | Sets a Aztec encode mode. Default value: Auto. |
| [set_AztecErrorLevel](./set_aztecerrorlevel/)(int32_t) | Level of error correction of Aztec types of barcode. Value should between 5 to 95. |
| [set_AztecSymbolMode](./set_aztecsymbolmode/)(Aspose::BarCode::Generation::AztecSymbolMode) | Sets a Aztec Symbol mode. Default value: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Sets ECI encoding. Used when AztecEncodeMode is Auto. Default value: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Aspose::BarCode::Generation::AztecEncodeMode) | Sets a Aztec encode mode. Default value: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Level of error correction of Aztec types of barcode. Value should between 5 to 95. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Sets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Barcode ID for Structured Append mode of Aztec barcode. Barcode ID should be in range from 1 to barcodes count. Default value: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Barcodes count for Structured Append mode of Aztec barcode. Barcodes count should be in range from 1 to 26. Default value: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | File ID for Structured Append mode of Aztec barcode (optional field). File ID should not contain spaces. Default value: empty string |
| [set_SymbolMode](./set_symbolmode/)(Aspose::BarCode::Generation::AztecSymbolMode) | Sets a Aztec Symbol mode. Default value: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [AztecParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
