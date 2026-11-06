---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill 类"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill 类。C++ 中的 SwissQR 账单数据。"
type: docs
weight: 2700
url: /zh/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR 账单数据

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | 创建并设置 ISO11649 债权人参考号，方法是将原始字符串前缀为 "RF" 并添加模 97 校验和。 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | 确定指定的对象是否等于当前对象。 |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | 确定指定的账单是否等于当前账单。 |
| [get_Account](./get_account/)() const | 获取债权人的账户号码。 |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | 获取或设置替代支付方案。 |
| [get_Amount](./get_amount/)() const | 获取付款金额。 |
| [get_BillInformation](./get_billinformation/)() const | 获取附加的结构化账单信息。 |
| [get_Creditor](./get_creditor/)() const | 获取债权人地址。 |
| [get_Currency](./get_currency/)() const | 获取付款货币。 |
| [get_Debtor](./get_debtor/)() const | 获取债务人地址。 |
| [get_Reference](./get_reference/)() const | 获取债权人付款参考。 |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | 获取附加的非结构化消息。 |
| [get_Version](./get_version/)() const | 获取 SwissQR 账单标准的版本。 |
| [GetHashCode](./gethashcode/)() const override | 获取此实例的哈希码。 |
| [set_Account](./set_account/)(System::String) | 设置债权人的账户号码。 |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | 获取或设置替代支付方案。 |
| [set_Amount](./set_amount/)(System::Decimal) | 设置付款金额。 |
| [set_BillInformation](./set_billinformation/)(System::String) | 设置附加的结构化账单信息。 |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | 设置债权人地址。 |
| [set_Currency](./set_currency/)(System::String) | 设置付款货币。 |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | 设置债务人地址。 |
| [set_Reference](./set_reference/)(System::String) | 设置债权人付款参考。 |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | 设置附加的非结构化消息。 |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | 设置 SwissQR 账单标准的版本。 |
## Typedefs

| 类型别名 | 描述 |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR 账单标准版本 |
## 另见

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
