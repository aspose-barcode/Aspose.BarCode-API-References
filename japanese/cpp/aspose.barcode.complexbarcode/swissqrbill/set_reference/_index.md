---
title: "メソッド"
linktitle: "set_Reference"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++で債権者の支払参照を設定します。"
type: docs
weight: 1200
url: /ja/cpp/aspose.barcode.complexbarcode/swissqrbill/set_reference/
---
## SwissQRBill::set_Reference method


債権者の支払参照を設定します。

```cpp
void Aspose::BarCode::ComplexBarcode::SwissQRBill::set_Reference(System::String value)
```

## 備考


SwissQR IBAN（例：CHxx30000xxxxxx から CHxx31999xxxxx の範囲）では参照が必須です。

指定する場合、参照は有効な SwissQR 参照（ISR 参照形式に相当）または ISO 11649（\"RFxxxx\"）に基づく有効な債権者参照のいずれかでなければなりません。どちらも書式設定のためにスペースを含むことができます。

債権者支払参照。
## 関連項目

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
