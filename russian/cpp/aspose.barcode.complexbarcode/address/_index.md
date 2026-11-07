---
title: "Класс Aspose::BarCode::ComplexBarcode::Address"
linktitle: "Адрес"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::ComplexBarcode::Address. Адрес кредитора или должника на C++."
type: docs
weight: 100
url: /ru/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Methods

| Method | Описание |
| --- | --- |
| [Address](./address/)() | Создаёт экземпляр [Address](./) |
| [Clear](./clear/)() | Очищает все поля и устанавливает тип в [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Определяет, равен ли указанный объект текущему объекту. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Определяет, равен ли указанный адрес текущему адресу. |
| [get_AddressLine1](./get_addressline1/)() const | Получает первую строку адреса. |
| [get_AddressLine2](./get_addressline2/)() const | Получает вторую строку адреса. |
| [get_CountryCode](./get_countrycode/)() const | Получает двухбуквенный код страны ISO. |
| [get_HouseNo](./get_houseno/)() const | Получает номер дома. |
| [get_Name](./get_name/)() const | Получает имя, либо имя и фамилию физического лица, либо название компании юридического лица. |
| [get_PostalCode](./get_postalcode/)() const | Получает почтовый индекс. |
| [get_Street](./get_street/)() const | Получает улицу. |
| [get_Town](./get_town/)() const | Получает город или населённый пункт. |
| [get_Type](./get_type/)() const | Получает тип адреса. |
| [GetHashCode](./gethashcode/)() const override | Получает хеш-код для этого экземпляра. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Устанавливает первую строку адреса. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Устанавливает вторую строку адреса. |
| [set_CountryCode](./set_countrycode/)(System::String) | Устанавливает двухбуквенный код страны ISO. |
| [set_HouseNo](./set_houseno/)(System::String) | Устанавливает номер дома. |
| [set_Name](./set_name/)(System::String) | Устанавливает имя, либо имя и фамилию физического лица, либо название компании юридического лица. |
| [set_PostalCode](./set_postalcode/)(System::String) | Устанавливает почтовый индекс. |
| [set_Street](./set_street/)(System::String) | Устанавливает улицу. |
| [set_Town](./set_town/)(System::String) | Устанавливает город или населённый пункт. |
## Примечания


Вы можете либо установить улицу, номер дома, почтовый индекс и город (тип *structured address*), либо строки адреса 1 и 2 (тип *combined address elements*). Тип автоматически устанавливается, как только заполнено любое из этих полей. До заполнения полей тип адреса считается *undetermined*. Если заполнены поля обоих типов, тип адреса становится *conflicting*. Имя и код страны должны всегда указываться, если только все поля не пусты.
## См. также

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
