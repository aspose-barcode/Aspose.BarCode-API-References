---
title: "Aspose::BarCode::Generation::AztecParameters 类"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::AztecParameters 类。C++ 中的 Aztec 参数。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec 参数。

```cpp
class AztecParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [get_ECIEncoding](./get_eciencoding/)() const | 获取 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1。 |
| [get_EncodeMode](./get_encodemode/)() const | 获取 Aztec 编码模式。默认值：Auto。 |
| [get_ErrorLevel](./get_errorlevel/)() const | Aztec 条码的错误纠正级别。值应在 5 到 95 之间。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [get_LayersCount](./get_layerscount/)() const | 获取 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 范围内，完整范围模式下应在 1 到 32 范围内。默认值：0（自动）。 |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec 条码的结构化追加模式的条码 ID。条码 ID 应在 1 到条码总数之间。默认值：0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec 条码的结构化追加模式的条码数量。条码数量应在 1 到 26 之间。默认值：0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec 条码结构化追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串 |
| [get_SymbolMode](./get_symbolmode/)() const | 获取 Aztec 符号模式。默认值：[AztecSymbolMode.Auto](../aztecencodemode/)。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 设置 ECI 编码。当 AztecEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | 设置 Aztec 编码模式。默认值：Auto。 |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Aztec 条码的错误纠正级别。值应在 5 到 95 之间。 |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [set_LayersCount](./set_layerscount/)(int32_t) | 设置 Aztec 符号的层数。紧凑模式下层数应在 1 到 3 范围内，完整范围模式下应在 1 到 32 范围内。默认值：0（自动）。 |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Aztec 条码的结构化追加模式的条码 ID。条码 ID 应在 1 到条码总数之间。默认值：0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Aztec 条码的结构化追加模式的条码数量。条码数量应在 1 到 26 之间。默认值：0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Aztec 条码结构化追加模式的文件 ID（可选字段）。文件 ID 不应包含空格。默认值：空字符串 |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | 设置 Aztec 符号模式。默认值：[AztecSymbolMode.Auto](../aztecencodemode/)。 |
| [ToString](./tostring/)() const override | 返回此 [AztecParameters](./) 的可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
