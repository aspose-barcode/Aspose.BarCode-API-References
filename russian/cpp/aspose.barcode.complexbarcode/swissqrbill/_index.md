---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill класс"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill класс. Данные SwissQR счета на C++."
type: docs
weight: 2700
url: /ru/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


Данные счета SwissQR

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## Methods

| Method | Описание |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | Создаёт и задаёт ссылку кредитора ISO11649 из необработанной строки, добавляя к строке префикс "RF" и контрольную сумму по модулю 97. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Определяет, равен ли указанный объект текущему объекту. |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | Определяет, равен ли указанный счёт текущему счёту. |
| [get_Account](./get_account/)() const | Получает номер счёта кредитора. |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | Получает или задаёт альтернативные схемы оплаты. |
| [get_Amount](./get_amount/)() const | Получает сумму платежа. |
| [get_BillInformation](./get_billinformation/)() const | Получает дополнительную структурированную информацию о счёте. |
| [get_Creditor](./get_creditor/)() const | Получает адрес кредитора. |
| [get_Currency](./get_currency/)() const | Получает валюту платежа. |
| [get_Debtor](./get_debtor/)() const | Получает адрес должника. |
| [get_Reference](./get_reference/)() const | Получает платёжный реквизит кредитора. |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | Получает дополнительное неструктурированное сообщение. |
| [get_Version](./get_version/)() const | Получает версию стандарта SwissQR счёта. |
| [GetHashCode](./gethashcode/)() const override | Получает хеш-код для этого экземпляра. |
| [set_Account](./set_account/)(System::String) | Задаёт номер счёта кредитора. |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | Получает или задаёт альтернативные схемы оплаты. |
| [set_Amount](./set_amount/)(System::Decimal) | Задаёт сумму платежа. |
| [set_BillInformation](./set_billinformation/)(System::String) | Задаёт дополнительную структурированную информацию о счёте. |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | Задаёт адрес кредитора. |
| [set_Currency](./set_currency/)(System::String) | Задаёт валюту платежа. |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | Задаёт адрес должника. |
| [set_Reference](./set_reference/)(System::String) | Задаёт платёжный реквизит кредитора. |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | Устанавливает дополнительное неструктурированное сообщение. |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | Устанавливает версию стандарта счета SwissQR. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | Версия стандарта счета SwissQR |
## См. также

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
