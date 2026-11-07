---
title: "Aspose::BarCode::ComplexBarcode::Payments класс"
linktitle: "Payments"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::Payments класс. Проверка полей, связанных со швейцарскими стандартами платежей, на C++."
type: docs
weight: 2400
url: /ru/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


Проверка полей, связанных со швейцарскими стандартами платежей.

```cpp
class Payments
```

## Methods

| Method | Описание |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Очищает строковое значение, чтобы оно соответствовало швейцарским стандартам платежей 2018 года. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Создаёт кредиторскую ссылку ISO11649 из исходной строки, добавляя к строке префикс "RF" и контрольную сумму по модулю 97 |
| static [FormatIban](./formatiban/)(System::String) | Форматирует IBAN или кредиторскую ссылку, вставляя пробелы |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Форматирует номер QR‑ссылки, вставляя пробелы. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Проверяет, является ли строка действительным номером IBAN |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Проверяет, является ли строка действительным номером ссылки ISO 11649 |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Проверяет, является ли строка действительной QR‑ссылкой. |
| [Payments](./payments/)() |  |
## См. также

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
