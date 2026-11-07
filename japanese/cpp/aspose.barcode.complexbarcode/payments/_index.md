---
title: "Aspose::BarCode::ComplexBarcode::Payments クラス"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::Payments クラス。C++ におけるスイス決済標準に関連するフィールド検証。"
type: docs
weight: 2400
url: /ja/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Swiss Payment標準に関連するフィールド検証です。

```cpp
class Payments
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | スイス決済標準 2018 に適合するように文字列値をクリーンアップします。 |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | 文字列の前に "RF" を付加し、モジュロ 97 のチェックサムを付けて、生の文字列から ISO11649 債権者参照を作成します |
| static [FormatIban](./formatiban/)(System::String) | IBAN または債権者参照にスペースを挿入してフォーマットします |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | QR 参照番号にスペースを挿入してフォーマットします。 |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | 文字列が有効な IBAN 番号かどうかを検証します |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | 文字列が有効な ISO 11649 参照番号かどうかを検証します |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | 文字列が有効な QR 参照かどうかを検証します。 |
| [Payments](./payments/)() |  |
## 関連項目

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
