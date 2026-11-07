---
title: "メソッド"
linktitle: "FormatQrReferenceNumber"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。C++でスペースを挿入してQR参照番号をフォーマットします。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.complexbarcode/payments/formatqrreferencenumber/
---
## Payments::FormatQrReferenceNumber method


QR 参照番号にスペースを挿入してフォーマットします。

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatQrReferenceNumber(System::String refNo)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| refNo | System::String | 空白のない参照番号。 |

### ReturnValue

フォーマットされた参照番号。
## 備考


5桁ごとのグループを作成するためにスペースが挿入されます。5桁未満のグループが必要な場合は、フォーマットされた参照番号の先頭に配置されます。

## 関連項目

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
