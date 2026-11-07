---
title: "method"
linktitle: "FormatIban"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Форматирует IBAN или кредиторскую ссылку, вставляя пробелы в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode.complexbarcode/payments/formatiban/
---
## Payments::FormatIban method


Форматирует IBAN или кредиторскую ссылку, вставляя пробелы

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatIban(System::String iban)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| iban | System::String | IBAN или кредиторская ссылка без пробелов. |

### ReturnValue

Отформатированный IBAN или кредиторская ссылка.
## Примечания


Пробелы вставляются для формирования групп по 4 буквы/цифры. Если нужна группа из менее чем 4 букв/цифр, она появляется в конце.

## См. также

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
