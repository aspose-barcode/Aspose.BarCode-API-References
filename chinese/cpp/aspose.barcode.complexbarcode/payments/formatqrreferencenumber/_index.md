---
title: "method"
linktitle: "FormatQrReferenceNumber"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。通过在 C++ 中插入空格来格式化 QR 参考号。"
type: docs
weight: 700
url: /zh/cpp/aspose.barcode.complexbarcode/payments/formatqrreferencenumber/
---
## Payments::FormatQrReferenceNumber method


通过插入空格来格式化 QR 参考号。

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatQrReferenceNumber(System::String refNo)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| refNo | System::String | 没有空白字符的参考号。 |

### ReturnValue

已格式化的参考号。
## 备注


插入空格以创建每组 5 位数字的分组。如果需要少于 5 位的分组，它会出现在已格式化参考号的开头。

## 另见

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
