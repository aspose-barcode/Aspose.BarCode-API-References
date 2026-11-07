---
title: "method"
linktitle: "get_Reference"
second_title: "Aspose.BarCode для C++ справочник API"
description: " method. Получает ссылку платежа кредитора в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


Получает платёжный реквизит кредитора.

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## Примечания


Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне CHxx30000xxxxxx до CHxx31999xxxxx.

Если указана, ссылка должна быть либо действительной ссылкой SwissQR (соответствующей форме ISR), либо действительной ссылкой кредитора согласно ISO 11649 (\"RFxxxx\"). Обе могут содержать пробелы для форматирования.

Ссылка платежа кредитора.
## См. также

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
