---
title: "Класс Aspose::BarCode::BarCodeRecognition::BaseDecodeType."
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::BarCodeRecognition::BaseDecodeType. Базовый класс для MultiDecodeType и SingleDecodeType в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Базовый класс для [MultiDecodeType](../multidecodetype/) и [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Methods

| Method | Описание |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Определяет, включен ли любой из указанных типов декодирования в |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Возвращает значение, указывающее, равен ли этот экземпляр заданному значению [SingleDecodeType](../singledecodetype/). |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Возвращает значение, указывающее, равен ли этот экземпляр заданному значению [MultiDecodeType](../multidecodetype/). |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению [BaseDecodeType](./). |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код для данного экземпляра. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Преобразует строковое представление [SingleDecodeType](../singledecodetype/) в его экземпляр. Возвращаемое значение указывает, успешно ли выполнено преобразование или нет. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Преобразует строковое представление [MultiDecodeType](../multidecodetype/) в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Преобразует строковое представление [BaseDecodeType](./) в его экземпляр, определив конкретный тип. Возвращаемое значение указывает, успешно ли выполнено преобразование или нет. |
## Примечания


Этот пример показывает, как использовать [BaseDecodeType](./) вместе с [SingleDecodeType](../singledecodetype/) и [MultiDecodeType](../multidecodetype/).
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
