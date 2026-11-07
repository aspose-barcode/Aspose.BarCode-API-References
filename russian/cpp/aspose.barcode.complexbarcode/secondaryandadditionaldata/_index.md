---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Класс для хранения вторичных и дополнительных данных HIBC LIC на C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Класс для хранения вторичных и дополнительных данных HIBC LIC.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному [SecondaryAndAdditionalData](./). |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Определяет дату производства. Дату производства можно установить в DateTime.MinValue, чтобы не использовать это поле. Значение по умолчанию: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Определяет дату истечения срока. Будет использоваться, если ExpiryDateFormat не установлен в None. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Определяет формат даты истечения срока. |
| [get_LotNumber](./get_lotnumber/)() const | Определяет номер партии или лота. Номер партии/лота должен быть буквенно-цифровой строкой длиной до 18 символов. |
| [get_Quantity](./get_quantity/)() const | Определяет количество, должно быть целым числом от 0 до 500. Количество можно установить в -1, чтобы не использовать это поле. Значение по умолчанию: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Определяет серийный номер. Серийный номер должен быть буквенно-цифровой строкой длиной до 18 символов. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ParseFromString](./parsefromstring/)(System::String) | Создаёт вторичные и дополнительные вспомогательные данные из строкового формата в соответствии со спецификацией HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Определяет дату производства. Дату производства можно установить в DateTime.MinValue, чтобы не использовать это поле. Значение по умолчанию: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Определяет дату истечения срока. Будет использоваться, если ExpiryDateFormat не установлен в None. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Определяет формат даты истечения срока. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Определяет номер партии или лота. Номер партии/лота должен быть буквенно-цифровой строкой длиной до 18 символов. |
| [set_Quantity](./set_quantity/)(int32_t) | Определяет количество, должно быть целым числом от 0 до 500. Количество можно установить в -1, чтобы не использовать это поле. Значение по умолчанию: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Определяет серийный номер. Серийный номер должен быть буквенно-цифровой строкой длиной до 18 символов. |
| [ToString](./tostring/)() const override | Преобразует данные в строковый формат в соответствии со спецификацией HIBC LIC. |
## См. также

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
