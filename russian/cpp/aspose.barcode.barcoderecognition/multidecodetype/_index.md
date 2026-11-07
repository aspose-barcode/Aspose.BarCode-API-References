---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType класс"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType класс. Составной тип декодирования в C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Тип декодирования Composite.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Methods

| Method | Описание |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Добавляет еще один [SingleDecodeType](../singledecodetype/) к [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Проверяет, содержит ли это все типы из типов штрихкодов. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Содержит ли любой из типов |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [MultiDecodeType](./). |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Возвращает значение, указывающее, содержит ли эта коллекция типов декодирования только указанное значение [SingleDecodeType](../singledecodetype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [MultiDecodeType](./). |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Возвращает значение, указывающее, равен ли этот экземпляр заданному значению [BaseDecodeType](../basedecodetype/). |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Исключает [SingleDecodeType](../singledecodetype/) из [MultiDecodeType](./) и возвращает новый экземпляр [MultiDecodeType](./). |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Возвращает количество одиночных типов. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| [GetSingleTypes](./getsingletypes/)() | Представляет список одиночных типов. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Инициализирует новый экземпляр класса [MultiDecodeType](./). |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Инициализирует новый экземпляр класса [MultiDecodeType](./). |
| [ToString](./tostring/)() const override | Переопределенный метод, представляющий [MultiDecodeType](./) в виде строки. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Преобразует строковое представление [MultiDecodeType](./) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Преобразует строковое представление [SingleDecodeType](../singledecodetype/) в его экземпляр. Возвращаемое значение указывает, успешно ли выполнено преобразование или нет. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Преобразует строковое представление [BaseDecodeType](../basedecodetype/) в его экземпляр, определив конкретный тип. Возвращаемое значение указывает, удалось ли преобразование или нет. |
## Примечания


Этот пример показывает, как создавать составные типы MultiDecode, которые комбинируют [SingleDecodeType](../singledecodetype/) и типы MultiDecode.
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## См. также

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
