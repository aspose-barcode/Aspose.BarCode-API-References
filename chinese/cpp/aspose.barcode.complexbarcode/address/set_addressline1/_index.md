---
title: "method"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。 在 C++ 中设置地址行 1。"
type: docs
weight: 500
url: /zh/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


设置地址第一行。

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## 备注


[Address](../) line 1 contains street name, house number or P.O. box. 

设置此字段会将地址类型设置为 [AddressType::CombinedElements](../../addresstype/)，除非它已经是 [AddressType::Structured](../../addresstype/)，在这种情况下它会变为 [AddressType::Conflicting](../../addresstype/)。

此字段仅用于组合元素地址，可选。

地址行 1。
## 另见

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
