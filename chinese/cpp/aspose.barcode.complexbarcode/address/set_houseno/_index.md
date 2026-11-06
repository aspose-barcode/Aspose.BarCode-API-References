---
title: "method"
linktitle: "set_HouseNo"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。 在 C++ 中设置门牌号。"
type: docs
weight: 1100
url: /zh/cpp/aspose.barcode.complexbarcode/address/set_houseno/
---
## Address::set_HouseNo method


设置门牌号。

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_HouseNo(System::String value)
```

## 备注


设置此字段会将地址类型设置为 [AddressType::Structured](../../addresstype/)，除非它已经是 [AddressType::CombinedElements](../../addresstype/)，在这种情况下它会变为 [AddressType::Conflicting](../../addresstype/)。

此字段仅用于结构化地址，可选。

门牌号。
## 另见

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
