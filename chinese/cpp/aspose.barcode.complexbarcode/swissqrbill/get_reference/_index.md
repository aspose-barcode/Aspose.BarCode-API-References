---
title: "method"
linktitle: "get_Reference"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。获取 C++ 中的债权人付款参考。"
type: docs
weight: 1100
url: /zh/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


获取债权人付款参考。

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## 备注


对于 SwissQR IBAN（即范围在 CHxx30000xxxxxx 到 CHxx31999xxxxx 之间的 IBAN），参考号是必需的。

如果指定，参考号必须是有效的 SwissQR 参考（对应 ISR 参考格式）或符合 ISO 11649（\"RFxxxx\"）的有效债权人参考。两者都可以包含空格用于格式化。

债权人付款参考。
## 另见

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
