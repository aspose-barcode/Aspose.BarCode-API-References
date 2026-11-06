---
title: "method"
linktitle: "get_Town"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。获取 C++ 中的城镇或城市。"
type: docs
weight: 1400
url: /zh/cpp/aspose.barcode.complexbarcode/address/get_town/
---
## Address::get_Town method


获取城镇或城市。

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Town() const
```

## 备注


设置此字段会将地址类型设置为 [AddressType::Structured](../../addresstype/)，除非它已经是 [AddressType::CombinedElements](../../addresstype/)，在这种情况下它会变为 [AddressType::Conflicting](../../addresstype/)。

此字段仅用于结构化地址。对于此类型，它是必需的。

城镇或城市。
## 另见

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
