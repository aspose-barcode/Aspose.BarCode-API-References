---
title: "Aspose::BarCode::Generation::BaseEncodeType class"
linktitle: "BaseEncodeType"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::BaseEncodeType class. Базовый класс для SymbologyEncodeType на C++."
type: docs
weight: 600
url: /ru/cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


Базовый класс для [SymbologyEncodeType](../symbologyencodetype/).

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<BaseEncodeType>>
```

## Methods

| Method | Описание |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | Возвращает значение, указывающее, равно ли данный экземпляр указанному значению [BaseEncodeType](./). |
| [get_Classification](./get_classification/)() const | Получает классификацию этой символьной системы. |
| [get_TypeIndex](./get_typeindex/)() const | Получает индекс типа кодирования |
| [get_TypeName](./get_typename/)() const | Получает имя типа кодирования |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [GetString](./getstring/)() | Преобразует экземпляр [BaseEncodeType](./) в его строковое представление. Формат строки: "Index:0; Name:Codabar". |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | Преобразует экземпляр [BaseEncodeType](./) в его строковое представление. Формат строки: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Преобразует строковое представление имени [BaseEncodeType](./) в его экземпляр. |
| [ToString](./tostring/)() const override | Возвращает имя данного [BaseEncodeType](./) в виде строки. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Преобразует строковое представление [BaseEncodeType](./) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Преобразует строковое представление [BaseEncodeType](./) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование. |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
