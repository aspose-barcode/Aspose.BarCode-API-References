---
title: Aspose::BarCode::Generation::DotCodeParameters class
linktitle: DotCodeParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::DotCodeParameters class. DotCode parameters in C++.'
type: docs
weight: 2100
url: /cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


DotCode parameters.

```cpp
class DotCodeParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [get_Columns](./get_columns/)() | Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1 |
| [get_DotCodeEncodeMode](./get_dotcodeencodemode/)() | Identifies DotCode encode mode. Default value: Auto. |
| [get_DotCodeStructuredAppendModeBarcodeId](./get_dotcodestructuredappendmodebarcodeid/)() | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [get_DotCodeStructuredAppendModeBarcodesCount](./get_dotcodestructuredappendmodebarcodescount/)() | Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [get_ECIEncoding](./get_eciencoding/)() const | Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Identifies DotCode encode mode. Default value: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [get_Rows](./get_rows/)() | Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [set_AspectRatio](./set_aspectratio/)(float) | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [set_Columns](./set_columns/)(int32_t) | Identifies columns count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of columns must be at least 5. Default value: -1 |
| [set_DotCodeEncodeMode](./set_dotcodeencodemode/)(Aspose::BarCode::Generation::DotCodeEncodeMode) | Identifies DotCode encode mode. Default value: Auto. |
| [set_DotCodeStructuredAppendModeBarcodeId](./set_dotcodestructuredappendmodebarcodeid/)(int32_t) | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [set_DotCodeStructuredAppendModeBarcodesCount](./set_dotcodestructuredappendmodebarcodescount/)(int32_t) | Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identifies ECI encoding. Used when DotCodeEncodeMode is Auto. Default value: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Aspose::BarCode::Generation::DotCodeEncodeMode) | Identifies DotCode encode mode. Default value: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [set_Rows](./set_rows/)(int32_t) | Identifies rows count. Sum of the number of rows plus the number of columns of a DotCode symbol must be odd. Number of rows must be at least 5. Default value: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Identifies the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Identifies DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [DotCodeParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
