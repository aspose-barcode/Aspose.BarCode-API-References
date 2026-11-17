---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext 类"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext 类。该类用于在 C++ 中对嵌入 4 状态 Royal Mailmark 代码的文本进行编码和解码。"
type: docs
weight: 1500
url: /zh/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


用于对嵌入在 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Class](./get_class/)() const | \"0\" - 空或测试 \"1\" - 1C（零售） \"2\" - 2C（零售） \"3\" - 3C（零售） \"4\" - 高级（RetailPublishing 邮件）（供将来使用） \"5\" - 延迟（零售） \"6\" - 航空（零售）（供将来使用） \"7\" - 地面（零售）（供将来使用） \"8\" - 高级（网络访问） \"9\" - 标准（网络访问） |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 \"XY11     \"（注意后面的 5 个空格），或表示国内分拣码的字符模式。国内分拣码由外部邮编、内部邮编和投递点后缀组成。 |
| [get_Format](./get_format/)() const | \"0\" – 空或测试 \"1\" – 信件 \"2\" – 大信件 |
| [get_ItemID](./get_itemid/)() const | 最大值为 99999999。 |
| [get_SupplychainID](./get_supplychainid/)() const | Barcode C 的最大值为 99，Barcode L 的最大值为 999999。 |
| [get_VersionID](./get_versionid/)() const | 当前 \"1\" – 用于 Mailmark 条码（0 以及 2 到 9 和 A 到 Z 预留供将来使用） |
| [GetBarcodeType](./getbarcodetype/)() override | 获取条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 从 Mailmark 数据构建代码文本。 |
| [InitFromString](./initfromstring/)(System::String) override | 从构建的代码文本初始化 Mailmark 数据。 |
| [MailmarkCodetext](./mailmarkcodetext/)() | 初始化 [MailmarkCodetext](./) 类的新实例。 |
| [set_Class](./set_class/)(System::String) | \"0\" - 空或测试 \"1\" - 1C（零售） \"2\" - 2C（零售） \"3\" - 3C（零售） \"4\" - 高级（RetailPublishing 邮件）（供将来使用） \"5\" - 延迟（零售） \"6\" - 航空（零售）（供将来使用） \"7\" - 地面（零售）（供将来使用） \"8\" - 高级（网络访问） \"9\" - 标准（网络访问） |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 \"XY11     \"（注意后面的 5 个空格），或表示国内分拣码的字符模式。国内分拣码由外部邮编、内部邮编和投递点后缀组成。 |
| [set_Format](./set_format/)(int32_t) | \"0\" – 空或测试 \"1\" – 信件 \"2\" – 大信件 |
| [set_ItemID](./set_itemid/)(int32_t) | 最大值为 99999999。 |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Barcode C 的最大值为 99，Barcode L 的最大值为 999999。 |
| [set_VersionID](./set_versionid/)(int32_t) | 当前 \"1\" – 用于 Mailmark 条码（0 以及 2 到 9 和 A 到 Z 预留供将来使用） |
## 另见

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
