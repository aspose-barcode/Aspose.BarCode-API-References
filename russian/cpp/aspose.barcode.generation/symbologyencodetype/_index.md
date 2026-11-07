---
title: "Класс Aspose::BarCode::Generation::SymbologyEncodeType"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::Generation::SymbologyEncodeType. Тип кодирования символьной системы. См. EncodeTypes для получения экземпляра в C++."
type: docs
weight: 4900
url: /ru/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Тип кодирования символьной системы. См. [EncodeTypes](../encodetypes/) для получения экземпляра.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Methods

| Method | Описание |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [BaseEncodeType](../baseencodetype/). |
| [get_Classification](../baseencodetype/get_classification/)() const | Получает классификацию этой символьной системы. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Получает индекс типа кодирования |
| [get_TypeName](../baseencodetype/get_typename/)() const | Получает имя типа кодирования |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [GetString](../baseencodetype/getstring/)() | Преобразует экземпляр [BaseEncodeType](../baseencodetype/) в его эквивалентное строковое представление. Формат строки: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Преобразует экземпляр [BaseEncodeType](../baseencodetype/) в его эквивалентное строковое представление. Формат строки: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Преобразует строковое представление имени [BaseEncodeType](../baseencodetype/) в его экземпляр. |
| [ToString](../baseencodetype/tostring/)() const override | Возвращает имя данного [BaseEncodeType](../baseencodetype/) в виде строки. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Преобразует строковое представление [BaseEncodeType](../baseencodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Преобразует строковое представление [BaseEncodeType](../baseencodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование. |
## Примечания


Этот пример показывает, как получить экземпляр класса [SymbologyEncodeType](./).
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## См. также

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
