---
title: "method"
linktitle: "FormatIban"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。通过在 C++ 中插入空格来格式化 IBAN 或债权人参考号。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode.complexbarcode/payments/formatiban/
---
## Payments::FormatIban method


通过插入空格来格式化 IBAN 或债权人参考号

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatIban(System::String iban)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| iban | System::String | 没有空格的 IBAN 或债权人参考号。 |

### ReturnValue

已格式化的 IBAN 或债权人参考号。
## 备注


插入空格以形成每组 4 个字母/数字的分组。如果需要少于 4 个字母/数字的分组，它会出现在末尾。

## 另见

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
