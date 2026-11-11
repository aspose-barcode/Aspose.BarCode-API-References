---
title: "Класс MultiDecodeType"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.BarCodeRecognition.MultiDecodeType. Составной тип декодирования"
type: docs
weight: 320
url: /ru/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Составной тип декодирования.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Инициализирует новый экземпляр класса `MultiDecodeType`. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Инициализирует новый экземпляр класса `MultiDecodeType`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Возвращает количество одиночных типов. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Добавляет ещё один [`SingleDecodeType`](../singledecodetype/) к MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Проверьте, содержит ли это все типы из типов штрихкодов. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Содержит ли любой из типов |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению [`BaseDecodeType`](../basedecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `MultiDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `MultiDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Возвращает значение, указывающее, содержит ли эта коллекция типов декодирования только указанное значение [`SingleDecodeType`](../singledecodetype/). |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Исключает [`SingleDecodeType`](../singledecodetype/) из MultiDecodeType и возвращает новый экземпляр MultiDecodeType. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Представляет список одиночных типов. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Переопределённый метод, представляющий MultiDecodeType в виде строки. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Преобразует строковое представление MultiDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли преобразование или нет. |

## Примеры

Этот пример показывает, как создавать составные типы MultiDecode, которые комбинируют SingleDecodeType и MultiDecode.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### См. также

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


