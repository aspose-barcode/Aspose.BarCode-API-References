---
title: "method"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。验证该字符串是否为有效的 QR 参考（C++）。"
type: docs
weight: 600
url: /zh/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


验证字符串是否为有效的 QR 参考。

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| reference | System::String | 待验证的 QR 参考号。 |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## 备注


有效的 QR 参考即为有效的 ISR 参考。

该字符串会检查有效字符、有效长度和有效校验位。空白字符会被忽略。

## 另见

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
