---
title: "method"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。清理字符串值，使其符合 2018 年瑞士支付标准（C++）。"
type: docs
weight: 100
url: /zh/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


清理字符串值，使其符合 2018 年瑞士支付标准。

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| value | System::String | 待清理的字符串值。 |
| result | Payments::CleaningResult\& | 结果将填充清理后的字符串和标志。 |
## 备注


不支持的字符（根据 2018 年瑞士支付标准，第 2.4.1 章和附录 D）将被替换为空格（不支持的空白）或点（所有其他不支持的字符）。前导和尾随空白将被移除。

如果检测到超出 0xff 的字符，字符串将首先被规范化，使带变音符或重音的字母（由两个代码点表示）合并为单个代码点（如果可能），其中一些可能会变为有效。

如果结果字符串全部为空白，返回 **null**。

## 另见

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
