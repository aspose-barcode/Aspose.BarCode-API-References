---
title: "メソッド"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で住所行 1 を設定します。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


住所行 1 を設定します。

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## 備考


[Address](../) line 1 contains street name, house number or P.O. box. 

このフィールドを設定すると、すでに [AddressType::Structured](../../addresstype/) でない限り、住所タイプが [AddressType::CombinedElements](../../addresstype/) に設定され、すでに [AddressType::Structured](../../addresstype/) の場合は [AddressType::Conflicting](../../addresstype/) になります。

このフィールドは結合要素の住所でのみ使用され、オプションです。

住所行 1。
## 関連項目

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
