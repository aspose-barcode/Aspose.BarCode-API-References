---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink 类"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink 类。表示用于编码和解码的 GS1 Digital Link 代码文本，作为应用标识符元素的有序序列。源顺序和重复的应用标识符会被保留。构造的代码文本是未压缩的 GS1 Digital Link URI。在 C++ 中解析时，非 GS1 查询参数和 URI 片段会被忽略。"
type: docs
weight: 600
url: /zh/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


表示用于编码和解码的 GS1 Digital Link 代码文本，作为应用标识符元素的有序序列。保留源顺序和重复的应用标识符。构建的代码文本是未压缩的 GS1 Digital Link URI。解析时会忽略非 GS1 的查询参数和 URI 片段。

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Add](./add/)(System::String, System::String) | 追加一个已验证的应用标识符元素。 |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | 通过从 GS1 代码文本复制所有元素并选择唯一可用的主键来创建 GS1 Digital Link。 |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | 通过从 GS1 代码文本复制所有元素并使用指定的主键来创建 GS1 Digital Link。 |
| [get_BarcodeType](./get_barcodetype/)() const | 获取用于编码此 GS1 Digital Link 的条形码类型。支持的类型有 QR、DataMatrix、Aztec、Pdf417、MicroPdf417、DotCode、HanXin、CodablockF 和 Code128。默认值为 QR。 |
| [get_Count](./get_count/)() | 获取应用标识符元素的数量。 |
| [get_Elements](./get_elements/)() | 获取按源顺序排列的所有元素的副本。 |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | 获取用作 Digital Link 主键的应用标识符。Null 表示在构建 URI 时会自动选择主键。 |
| [get_UriStem](./get_uristem/)() const | 获取在 GS1 主键路径段之前的绝对 URI 前缀。该前缀不包含查询字符串或片段。 |
| [GetAll](./getall/)(System::String) | 获取应用标识符的所有值，按源顺序。 |
| [GetBarcodeType](./getbarcodetype/)() override | 获取用于编码此 GS1 数字链接的条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 构建未压缩的 GS1 数字链接 URI。 |
| [GetFirst](./getfirst/)(System::String) | 获取应用标识符的第一个值。 |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | 使用指定的 URI 主干初始化一个空的 GS1 数字链接。当恰好只有一个主键候选时，主键会自动选择。 |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | 使用指定的 URI 主干和主键初始化一个空的 GS1 数字链接。 |
| [idx_get](./idx_get/)(int32_t) | 按有序序列中的位置获取元素。 |
| [InitFromString](./initfromstring/)(System::String) override | 从未压缩的 GS1 数字链接 URI 初始化此实例。仅在成功解析提供的 URI 后才会替换现有状态。所选的条形码类型将被保留。 |
| static [Parse](./parse/)(System::String) | 解析未压缩的 GS1 数字链接 URI。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 设置用于编码此 GS1 数字链接的条形码类型。支持的类型有 QR、DataMatrix、Aztec、Pdf417、MicroPdf417、DotCode、HanXin、CodablockF 和 Code128。默认值为 QR。 |
| [ToGS1Codetext](./togs1codetext/)() | 创建一个独立的 GS1 编码文本，包含当前的 GS1 元素。不包括仅限 URI 的信息。 |
| [ToString](./tostring/)() const override | 返回未压缩的 GS1 数字链接 URI。 |
| [ToUriString](./touristring/)() | 将当前对象状态格式化为未压缩的 GS1 数字链接 URI。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | 尝试解析未压缩的 GS1 数字链接 URI 并返回结构化的验证错误。 |
| static [Validate](./validate/)(System::String) | 在不构建对象的情况下验证未压缩的 GS1 数字链接 URI。 |
## 另见

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
