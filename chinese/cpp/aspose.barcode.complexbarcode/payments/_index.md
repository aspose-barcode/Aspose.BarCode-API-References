---
title: "Aspose::BarCode::ComplexBarcode::Payments 类"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::Payments 类。与瑞士支付标准相关的字段验证，适用于 C++。"
type: docs
weight: 2400
url: /zh/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


与瑞士支付标准相关的字段验证。

```cpp
class Payments
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | 清理字符串值，使其符合 2018 年瑞士支付标准。 |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | 通过在原始字符串前添加 "RF" 并计算模 97 校验和，创建 ISO11649 债权人参考号。 |
| static [FormatIban](./formatiban/)(System::String) | 通过插入空格来格式化 IBAN 或债权人参考号 |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | 通过插入空格来格式化 QR 参考号。 |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | 验证字符串是否为有效的 IBAN 号码 |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | 验证字符串是否为有效的 ISO 11649 参考号 |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | 验证字符串是否为有效的 QR 参考。 |
| [Payments](./payments/)() |  |
## 另见

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
