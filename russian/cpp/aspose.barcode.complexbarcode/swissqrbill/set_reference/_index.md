---
title: "method"
linktitle: "set_Reference"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Устанавливает ссылку платежа кредитора в C++."
type: docs
weight: 1200
url: /ru/cpp/aspose.barcode.complexbarcode/swissqrbill/set_reference/
---
## SwissQRBill::set_Reference method


Задаёт платёжный реквизит кредитора.

```cpp
void Aspose::BarCode::ComplexBarcode::SwissQRBill::set_Reference(System::String value)
```

## Примечания


Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне CHxx30000xxxxxx до CHxx31999xxxxx.

Если указана, ссылка должна быть либо действительной ссылкой SwissQR (соответствующей форме ISR), либо действительной ссылкой кредитора согласно ISO 11649 (\"RFxxxx\"). Обе могут содержать пробелы для форматирования.

Ссылка платежа кредитора.
## См. также

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
