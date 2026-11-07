---
title: "Класс Aspose::BarCode::BarCodeRecognition::SingleDecodeType."
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::BarCodeRecognition::SingleDecodeType. Тип одиночного декодирования. См. тип декодирования, чтобы получить экземпляр в C++."
type: docs
weight: 3200
url: /ru/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Тип одиночного декодирования. См. тип декодирования, чтобы получить экземпляр.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Methods

| Method | Описание |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Возвращает значение, указывающее, включен ли этот экземпляр в указанный список. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Возвращает значение, указывающее, равен ли этот экземпляр заданному значению [SingleDecodeType](./). |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Возвращает значение, указывающее, содержит ли указанная коллекция [MultiDecodeType](../multidecodetype/) только этот тип декодирования. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Возвращает значение, указывающее, равен ли этот экземпляр заданному значению [SingleDecodeType](./). |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Возвращает значение, указывающее, равен ли этот экземпляр заданному значению [BaseDecodeType](../basedecodetype/). |
| [get_TypeIndex](./get_typeindex/)() const | Получает индекс типа декодирования. |
| [get_TypeName](./get_typename/)() const | Получает имя типа декодирования. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [GetString](./getstring/)() | Преобразует экземпляр [SingleDecodeType](./) в его эквивалентное строковое представление. Формат строки: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Преобразует экземпляр [SingleDecodeType](./) в его эквивалентное строковое представление. Формат строки: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Преобразует строковое представление имени [SingleDecodeType](./) в его экземпляр. |
| [ToString](./tostring/)() const override | Возвращает имя данного [SingleDecodeType](./) в виде строки. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Преобразует строковое представление [SingleDecodeType](./) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Преобразует строковое представление [MultiDecodeType](../multidecodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Преобразует строковое представление [BaseDecodeType](../basedecodetype/) в его экземпляр, определив конкретный тип. Возвращаемое значение указывает, удалось ли преобразование или нет. |
## Примечания


Этот пример показывает, как получить экземпляр типа одиночного декодирования.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## См. также

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
