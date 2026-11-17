---
title: "method"
linktitle: "CreateIso11649Reference"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。通过在原始字符串前添加 \"RF\" 并计算模 97 校验和，在 C++ 中从原始字符串创建 ISO11649 债权人参考。"
type: docs
weight: 500
url: /zh/cpp/aspose.barcode.complexbarcode/payments/createiso11649reference/
---
## Payments::CreateIso11649Reference method


通过在原始字符串前添加 "RF" 并计算模 97 校验和，创建 ISO11649 债权人参考号。

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::CreateIso11649Reference(System::String rawReference)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| rawReference | System::String | 原始参考。 |

### ReturnValue

已创建的债权人参考号。
## 备注


已从参考号中移除空白字符。

## 另见

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
