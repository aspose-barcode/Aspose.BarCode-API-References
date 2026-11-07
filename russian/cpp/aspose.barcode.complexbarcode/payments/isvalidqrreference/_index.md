---
title: "method"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Проверяет, является ли строка действительным QR‑референсом в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


Проверяет, является ли строка действительной QR‑ссылкой.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| reference | System::String | Номер QR‑референса для проверки. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## Примечания


Действительный QR‑референс является действительным ISR‑референсом.

Строка проверяется на допустимые символы, допустимую длину и корректную контрольную цифру. Пробелы игнорируются.

## См. также

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
