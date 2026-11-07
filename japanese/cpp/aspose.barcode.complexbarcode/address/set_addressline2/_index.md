---
title: "メソッド"
linktitle: "set_AddressLine2"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で住所行 2 を設定します。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


住所行 2 を設定します。

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## 備考


[Address](../) line 2 contains postal code and town. 

このフィールドを設定すると、すでに [AddressType::Structured](../../addresstype/) でない限り、住所タイプが [AddressType::CombinedElements](../../addresstype/) に設定され、すでに [AddressType::Structured](../../addresstype/) の場合は [AddressType::Conflicting](../../addresstype/) になります。

このフィールドは結合要素の住所でのみ使用されます。このタイプでは必須です。

住所行 2。
## 関連項目

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
