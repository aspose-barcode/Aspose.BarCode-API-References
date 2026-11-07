---
title: "method"
linktitle: "FormatQrReferenceNumber"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Форматирует QR‑референс, вставляя пробелы в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode.complexbarcode/payments/formatqrreferencenumber/
---
## Payments::FormatQrReferenceNumber method


Форматирует номер QR‑ссылки, вставляя пробелы.

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatQrReferenceNumber(System::String refNo)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| refNo | System::String | Номер ссылки без пробелов. |

### ReturnValue

отформатированный номер ссылки.
## Примечания


Пробелы вставляются для создания групп по 5 цифр. Если требуется группа из менее чем 5 цифр, она появляется в начале отформатированного номера ссылки.

## См. также

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
