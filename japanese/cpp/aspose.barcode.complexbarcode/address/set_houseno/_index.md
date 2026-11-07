---
title: "メソッド"
linktitle: "set_HouseNo"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で住宅番号を設定します。"
type: docs
weight: 1100
url: /ja/cpp/aspose.barcode.complexbarcode/address/set_houseno/
---
## Address::set_HouseNo method


番地を設定します。

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_HouseNo(System::String value)
```

## 備考


このフィールドを設定すると、すでに [AddressType::CombinedElements](../../addresstype/) でない限り、住所タイプが [AddressType::Structured](../../addresstype/) に設定され、すでに [AddressType::CombinedElements](../../addresstype/) の場合は [AddressType::Conflicting](../../addresstype/) になります。

このフィールドは構造化された住所でのみ使用され、オプションです。

住宅番号。
## 関連項目

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
