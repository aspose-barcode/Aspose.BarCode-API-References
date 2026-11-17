---
title: "Aspose::BarCode::Generation::DotCodeParameters 类"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::DotCodeParameters 类。C++ 中的 DotCode 参数。"
type: docs
weight: 2200
url: /zh/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


DotCode 参数。

```cpp
class DotCodeParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [get_Columns](./get_columns/)() const | 标识列数。DotCode 符号的行数与列数之和必须为奇数。列数必须至少为 5。默认值：-1 |
| [get_ECIEncoding](./get_eciencoding/)() const | 标识 ECI 编码。当 DotCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | 标识 DotCode 编码模式。默认值：Auto。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。 |
| [get_Rows](./get_rows/)() const | 标识行数。DotCode 符号的行数与列数之和必须为奇数。行数必须至少为 5。默认值：-1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。 |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | 标识 DotCode 结构化追加模式条码的数量。默认值为 -1。数量必须在 1 到 35 之间。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [set_Columns](./set_columns/)(int32_t) | 标识列数。DotCode 符号的行数与列数之和必须为奇数。列数必须至少为 5。默认值：-1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 标识 ECI 编码。当 DotCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | 标识 DotCode 编码模式。默认值：Auto。 |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | 指示代码是否用于指示读取器将以下数据解释为条码读取器的初始化或重新编程指令。默认值为 false。 |
| [set_Rows](./set_rows/)(int32_t) | 标识行数。DotCode 符号的行数与列数之和必须为奇数。行数必须至少为 5。默认值：-1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | 标识 DotCode 结构化追加模式条码的 ID。ID 从 1 开始，且必须小于或等于条码数量。默认值为 -1。 |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | 标识 DotCode 结构化追加模式条码的数量。默认值为 -1。数量必须在 1 到 35 之间。 |
| [ToString](./tostring/)() const override | 返回此 [DotCodeParameters](./) 的可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
