---
title: "method"
linktitle: "CreateIso11649Reference"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Создаёт кредиторскую ссылку ISO11649 из необработанной строки, добавляя к строке префикс \"RF\" и контрольную сумму по модулю 97 в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.barcode.complexbarcode/payments/createiso11649reference/
---
## Payments::CreateIso11649Reference method


Создаёт кредиторскую ссылку ISO11649 из исходной строки, добавляя к строке префикс "RF" и контрольную сумму по модулю 97

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::CreateIso11649Reference(System::String rawReference)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| rawReference | System::String | Необработанная ссылка. |

### ReturnValue

Созданный кредиторский референс.
## Примечания


Пробелы удаляются из ссылки.

## См. также

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
