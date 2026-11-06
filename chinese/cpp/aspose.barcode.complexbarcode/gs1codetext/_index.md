---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext 类"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext 类。表示用于编码和解码的 GS1 编码文本，作为应用标识符元素的有序序列。保留源顺序和重复的应用标识符。括号表示形式为 (AI)value(AI)value。值中的字面左括号 '(' 必须写成 (；这是唯一支持的转义序列。值中的右括号 ')' 在 C++ 中无需转义。"
type: docs
weight: 500
url: /zh/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


表示用于编码和解码的 GS1 代码文本，作为应用标识符元素的有序序列。保留源顺序和重复的应用标识符。括号表示形式为 (AI)value(AI)value。值中的字面左括号 '(' 必须写成 (; 这是唯一支持的转义序列。值中的右括号 ')' 不需要转义。

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Add](./add/)(System::String, System::String) | 追加一个已验证的应用标识符元素。 |
| [get_BarcodeType](./get_barcodetype/)() const | 获取用于编码此 GS1 编码文本的条形码类型。支持的类型有 GS1Aztec、GS1CodablockF、GS1Code128、GS1DataMatrix、GS1DotCode、GS1HanXin、GS1MicroPdf417、GS1QR 和 GS1 DataBar 类型。默认值为 GS1Code128。 |
| [get_Count](./get_count/)() | 获取应用标识符元素的数量。 |
| [get_Elements](./get_elements/)() | 获取按源顺序排列的所有元素的副本。 |
| [GetAll](./getall/)(System::String) | 获取应用标识符的所有值，按源顺序。 |
| [GetBarcodeType](./getbarcodetype/)() override | 获取用于编码此 GS1 编码文本的条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 构建括号形式的 GS1 编码文本，格式为 (AI)value(AI)value。值中的字面左括号需转义为 (。 |
| [GetFirst](./getfirst/)(System::String) | 获取应用标识符的第一个值。 |
| [GS1Codetext](./gs1codetext/)() | 初始化一个空的 GS1 编码文本。 |
| [idx_get](./idx_get/)(int32_t) | 按有序序列中的位置获取元素。 |
| [InitFromString](./initfromstring/)(System::String) override | 从括号形式的 GS1 编码文本 (AI)value(AI)value 初始化此实例。仅在成功解析提供的编码文本后才会替换现有元素。 |
| static [Parse](./parse/)(System::String) | 解析括号形式的 GS1 元素字符串，格式为 (AI)value(AI)value。值中的字面 '(' 必须写成 (；不支持其他转义序列，')' 不需要转义。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | 设置用于编码此 GS1 编码文本的条形码类型。支持的类型有 GS1Aztec、GS1CodablockF、GS1Code128、GS1DataMatrix、GS1DotCode、GS1HanXin、GS1MicroPdf417、GS1QR 和 GS1 DataBar 类型。默认值为 GS1Code128。 |
| [ToString](./tostring/)() const override | 返回括号形式的 GS1 表示，格式为 (AI)value(AI)value。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | 尝试解析括号形式的 GS1 元素字符串，格式为 (AI)value(AI)value，并返回结构化的验证错误。值中的文字 '(' 必须写成 (；不支持其他转义序列，')' 不需要转义。 |
| static [Validate](./validate/)(System::String) | 验证括号形式的 GS1 元素字符串，格式为 (AI)value(AI)value，且不构造对象。值中的文字 '(' 必须写成 (；不支持其他转义序列，')' 不需要转义。 |
## 另见

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
