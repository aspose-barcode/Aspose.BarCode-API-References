---
title: "Aspose::BarCode::Generation::MaxiCodeParameters class"
linktitle: "MaxiCodeParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::MaxiCodeParameters class. C++ 中的 MaxiCode 参数。"
type: docs
weight: 3600
url: /zh/cpp/aspose.barcode.generation/maxicodeparameters/
---
## MaxiCodeParameters class


MaxiCode 参数。

```cpp
class MaxiCodeParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [get_ECIEncoding](./get_eciencoding/)() const | 获取 MaxiCode 编码模式。默认值：Auto。 |
| [get_EncodeMode](./get_encodemode/)() const | 标识邮政编码。模式 2 时必须为 9 位数字，模式 3 时必须为 6 个字母数字符号。 |
| [get_Mode](./get_mode/)() const | 获取 MaxiCode 编码模式。 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | 获取结构化追加模式下的 MaxiCode 条形码 ID。ID 必须是 1 到 8 之间的值。默认值：0 |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | 获取结构化追加模式下的 MaxiCode 条形码数量。计数必须是 2 到 8 之间的值（最大条形码数量）。默认值：-1 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 设置 MaxiCode 编码模式。默认值：Auto。 |
| [set_EncodeMode](./set_encodemode/)(MaxiCodeEncodeMode) | 此示例展示了如何将原始 MaxiCode 代码文本解码为 [MaxiCodeStructuredCodetext](./) 实例。 |
| [set_Mode](./set_mode/)(MaxiCodeMode) | 设置 MaxiCode 编码模式。 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | 在结构化追加模式下设置 MaxiCode 条形码 ID。ID 必须是 1 到 8 之间的值。默认值：0 |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | 在结构化追加模式下设置 MaxiCode 条形码数量。计数必须是 2 到 8 之间的值（最大条形码数量）。默认值：-1 |
| [ToString](./tostring/)() const override | 返回此 [MaxiCodeParameters](./) 的人类可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
