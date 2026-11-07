---
title: "メソッド"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。文字列が有効なQRリファレンスかどうかをC++で検証します。"
type: docs
weight: 600
url: /ja/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


文字列が有効な QR 参照かどうかを検証します。

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| reference | System::String | 検証するQRリファレンス番号。 |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## 備考


有効なQRリファレンスは有効なISRリファレンスです。

文字列は有効な文字、有効な長さ、および有効なチェックディジットがチェックされます。空白は無視されます。

## 関連項目

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
