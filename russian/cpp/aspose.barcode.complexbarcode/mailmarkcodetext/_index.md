---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class. Класс для кодирования и декодирования текста, встроенного в 4‑состоянийный код Royal Mailmark, в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Класс для кодирования и декодирования текста, встроенного в 4‑состояний код Royal Mailmark.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Null или Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (для возможного будущего использования) "5" - Deferred (Retail) "6" - Air (Retail) (для возможного будущего использования) "7" - Surface (Retail) (для возможного будущего использования) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC и DP должны соответствовать формату PAF. Девятисимвольная строка, обозначающая международный "XY11     " (обратите внимание на 5 завершающих пробелов) или шаблон символов, обозначающий внутренний сортировочный код. Внутренний сортировочный код состоит из внешнего почтового индекса, внутреннего почтового индекса и суффикса точки доставки. |
| [get_Format](./get_format/)() const | "0" – Null или Test "1" – Письмо "2" – Большое письмо |
| [get_ItemID](./get_itemid/)() const | Максимальное значение равно 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | Максимальные значения: 99 для Barcode C и 999999 для Barcode L. |
| [get_VersionID](./get_versionid/)() const | В настоящее время "1" – Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования) |
| [GetBarcodeType](./getbarcodetype/)() override | Получает тип штрихкода. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Создать кодовый текст из данных Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | Инициализирует данные Mailmark из построенного кодового текста. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Инициализирует новый экземпляр класса [MailmarkCodetext](./). |
| [set_Class](./set_class/)(System::String) | "0" - Null или Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (для возможного будущего использования) "5" - Deferred (Retail) "6" - Air (Retail) (для возможного будущего использования) "7" - Surface (Retail) (для возможного будущего использования) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC и DP должны соответствовать формату PAF. Девятисимвольная строка, обозначающая международный "XY11     " (обратите внимание на 5 завершающих пробелов) или шаблон символов, обозначающий внутренний сортировочный код. Внутренний сортировочный код состоит из внешнего почтового индекса, внутреннего почтового индекса и суффикса точки доставки. |
| [set_Format](./set_format/)(int32_t) | "0" – Null или Test "1" – Письмо "2" – Большое письмо |
| [set_ItemID](./set_itemid/)(int32_t) | Максимальное значение равно 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Максимальные значения: 99 для Barcode C и 999999 для Barcode L. |
| [set_VersionID](./set_versionid/)(int32_t) | В настоящее время "1" – Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования) |
## См. также

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
