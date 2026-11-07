---
title: "method"
linktitle: "CleanValue"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Очищает строковое значение, делая его пригодным для Швейцарских платёжных стандартов 2018 в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Очищает строковое значение, чтобы оно соответствовало швейцарским стандартам платежей 2018 года.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| value | System::String | Строковое значение для очистки. |
| result | Payments::CleaningResult\& | Результат, который будет заполнен очищенной строкой и флагом. |
## Примечания


Неподдерживаемые символы(в соответствии со Швейцарскими платёжными стандартами 2018, гл. 2.4.1 и приложением D) заменяются пробелами(неподдерживаемый пробел) или точками (все остальные неподдерживаемые символы). Начальные и конечные пробелы удаляются.

Если обнаружены символы за пределами 0xff, строка сначала нормализуется так, чтобы буквы с умляутами или акцентами, представленные двумя кодовыми точками, объединялись в одну кодовую точку(если возможно), некоторые из которых могут стать допустимыми.

Если получившаяся строка состоит только из пробелов, **null** возвращается.

## См. также

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
