---
title: "メソッド"
linktitle: "get_AddressLine2"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で住所行 2 を取得します。"
type: docs
weight: 600
url: /ja/cpp/aspose.barcode.complexbarcode/address/get_addressline2/
---
## Address::get_AddressLine2 method


住所行 2 を取得します。

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine2() const
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
