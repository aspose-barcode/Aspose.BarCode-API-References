---
title: "method"
linktitle: "get_AddressLine1"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。 在 C++ 中获取地址行 1。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode.complexbarcode/address/get_addressline1/
---
## Address::get_AddressLine1 method


获取地址第一行。

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine1() const
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
