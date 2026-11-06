---
title: "method"
linktitle: "set_Street"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。设置 C++ 中的街道。"
type: docs
weight: 900
url: /zh/cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


设置街道。

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
```

## 备注


街道必须在不包含门牌号的情况下指定。

设置此字段会将地址类型设置为 [AddressType::Structured](../../addresstype/)，除非它已经是 [AddressType::CombinedElements](../../addresstype/)，在这种情况下它会变为 [AddressType::Conflicting](../../addresstype/)。

此字段仅用于结构化地址，可选。

街道。
## 另见

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
