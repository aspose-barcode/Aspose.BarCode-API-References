---
title: "メソッド"
linktitle: "set_Town"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で町または市を設定します。"
type: docs
weight: 1500
url: /ja/cpp/aspose.barcode.complexbarcode/address/set_town/
---
## Address::set_Town method


町または市を設定します。

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Town(System::String value)
```

## 備考


このフィールドを設定すると、すでに [AddressType::CombinedElements](../../addresstype/) でない限り、住所タイプが [AddressType::Structured](../../addresstype/) に設定され、すでに [AddressType::CombinedElements](../../addresstype/) の場合は [AddressType::Conflicting](../../addresstype/) になります。

このフィールドは構造化アドレスでのみ使用されます。このタイプでは必須です。

町または市。
## 関連項目

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
