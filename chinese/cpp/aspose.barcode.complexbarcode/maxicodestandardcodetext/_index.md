---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext 类"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext 类。用于在 C++ 中对模式 4、5 和 6 的 MaxiCode 编码文本进行编码和解码的类。"
type: docs
weight: 2000
url: /zh/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


用于对模式 4、5 和 6 的 MaxiCode 代码文本进行编码和解码的类。

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 返回一个值，指示此实例是否等于指定的 [MaxiCodeStandardCodetext](./) 值。 |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | 获取 MaxiCode 编码模式。默认值：Auto。 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | 标识邮政编码。模式 2 时必须为 9 位数字，模式 3 时必须为 6 个字母数字符号。 |
| [get_Message](./get_message/)() const | 获取消息。 |
| [get_Mode](./get_mode/)() | 获取 MaxiCode 模式。标准编码文本只能用于模式 4、5 和 6。 |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | 获取条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 构造编码文本 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [GetMode](./getmode/)() const override | 设置 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [InitFromString](./initfromstring/)(System::String) override | 从构造的编码文本初始化实例。 |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | 设置 MaxiCode 编码模式。默认值：Auto。 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | 此示例展示了如何将原始 MaxiCode 代码文本解码为 [MaxiCodeStructuredCodetext](./) 实例。 |
| [set_Message](./set_message/)(System::String) | 设置消息。 |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | 设置 MaxiCode 模式。标准编码文本只能用于模式 4、5 和 6。 |
## 备注


//模式 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = \"测试消息\"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //模式 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = \"测试消息\"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //模式 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = \"测试消息\"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## 另见

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
