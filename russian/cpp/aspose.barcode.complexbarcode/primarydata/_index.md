---
title: "Aspose::BarCode::ComplexBarcode::PrimaryData класс"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::PrimaryData класс. Класс для хранения первичных данных HIBC LIC в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


Класс для хранения первичных данных HIBC LIC.

```cpp
class PrimaryData : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [PrimaryData](./). |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() const | Определяет дату кода идентификации маркировщика. Код идентификации маркировщика должен быть 4‑символьной буквенно-цифровой строкой, при этом первый символ всегда должен быть буквенным. |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() const | Определяет номер продукта или каталога. Номер продукта или каталога должен быть буквенно-цифровой строкой длиной до 18 символов. |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() const | Определяет идентификатор единицы измерения. Идентификатор единицы измерения должен быть целым числом от 0 до 9. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [ParseFromString](./parsefromstring/)(System::String) | Создаёт экземпляр первичных данных из строкового формата в соответствии со спецификацией HIBC LIC. |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | Определяет дату кода идентификации маркировщика. Код идентификации маркировщика должен быть 4‑символьной буквенно-цифровой строкой, при этом первый символ всегда должен быть буквенным. |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | Определяет номер продукта или каталога. Номер продукта или каталога должен быть буквенно-цифровой строкой длиной до 18 символов. |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | Определяет идентификатор единицы измерения. Идентификатор единицы измерения должен быть целым числом от 0 до 9. |
| [ToString](./tostring/)() const override | Преобразует данные в строковый формат в соответствии со спецификацией HIBC LIC. |
## См. также

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
