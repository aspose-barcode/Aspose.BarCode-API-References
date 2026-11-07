---
title: "メソッド"
linktitle: "set_PostalCode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で郵便番号を設定します。"
type: docs
weight: 1300
url: /ja/cpp/aspose.barcode.complexbarcode/address/set_postalcode/
---
## Address::set_PostalCode method


郵便番号を設定します。

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_PostalCode(System::String value)
```

## 備考


このフィールドを設定すると、すでに [AddressType::CombinedElements](../../addresstype/) でない限り、住所タイプが [AddressType::Structured](../../addresstype/) に設定され、すでに [AddressType::CombinedElements](../../addresstype/) の場合は [AddressType::Conflicting](../../addresstype/) になります。

このフィールドは構造化アドレスでのみ使用されます。このタイプでは必須です。

郵便番号。
## 関連項目

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
