---
title: "メソッド"
linktitle: "get_Street"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。C++で通りを取得します。"
type: docs
weight: 800
url: /ja/cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


通り名を取得します。

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street() const
```

## 備考


通りは住宅番号なしで指定する必要があります。

このフィールドを設定すると、すでに [AddressType::CombinedElements](../../addresstype/) でない限り、住所タイプが [AddressType::Structured](../../addresstype/) に設定され、すでに [AddressType::CombinedElements](../../addresstype/) の場合は [AddressType::Conflicting](../../addresstype/) になります。

このフィールドは構造化された住所でのみ使用され、オプションです。

通り。
## 関連項目

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
