---
title: "メソッド"
linktitle: "FormatIban"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。C++でスペースを挿入してIBANまたは債権者参照をフォーマットします。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.complexbarcode/payments/formatiban/
---
## Payments::FormatIban method


IBAN または債権者参照にスペースを挿入してフォーマットします

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatIban(System::String iban)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| iban | System::String | スペースのないIBANまたは債権者参照。 |

### ReturnValue

フォーマットされたIBANまたは債権者参照。
## 備考


4文字/数字ごとのグループを形成するためにスペースが挿入されます。4文字/数字未満のグループが必要な場合は、末尾に配置されます。

## 関連項目

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
