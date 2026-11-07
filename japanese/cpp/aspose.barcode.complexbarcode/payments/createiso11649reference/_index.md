---
title: "メソッド"
linktitle: "CreateIso11649Reference"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。文字列の先頭に \"RF\" と modulo 97 のチェックサムを付加して、生の文字列から ISO11649 債権者リファレンスをC++で作成します。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.complexbarcode/payments/createiso11649reference/
---
## Payments::CreateIso11649Reference method


文字列の前に "RF" を付加し、モジュロ 97 のチェックサムを付けて、生の文字列から ISO11649 債権者参照を作成します

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::CreateIso11649Reference(System::String rawReference)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rawReference | System::String | 元のリファレンス。 |

### ReturnValue

作成された債権者参照。
## 備考


参照から空白が削除されます。

## 関連項目

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
