---
title: "メソッド"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。文字列の値をクリーンアップし、C++でスイス決済基準2018に適合させます。"
type: docs
weight: 100
url: /ja/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


スイス決済標準 2018 に適合するように文字列値をクリーンアップします。

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | System::String | クリーンアップする文字列の値。 |
| result | Payments::CleaningResult\& | クリーンアップされた文字列とフラグが設定される結果。 |
## 備考


サポートされていない文字（スイス決済基準2018、章2.4.1および付録Dによる）は、スペース（サポートされていない空白）またはドット（その他すべてのサポートされていない文字）に置き換えられます。先頭と末尾の空白は削除されます。

0xff を超える文字が検出された場合、文字列はまず正規化され、2つのコードポイントで表現されたウムラウトやアクセント付きの文字が（可能であれば）単一のコードポイントに結合されます。その結果、一部が有効になることがあります。

結果の文字列がすべて空白の場合、**null** が返されます。

## 関連項目

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
