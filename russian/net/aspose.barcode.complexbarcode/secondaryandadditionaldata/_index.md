---
title: "Класс SecondaryAndAdditionalData"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Класс Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData. Класс для хранения вторичных и дополнительных данных HIBC LIC."
type: docs
weight: 770
url: /ru/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

Класс для хранения вторичных и дополнительных данных HIBC LIC.

```csharp
public class SecondaryAndAdditionalData
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | Определяет дату производства. Дату производства можно установить в DateTime.MinValue, чтобы не использовать это поле. Значение по умолчанию: DateTime.MinValue. |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | Определяет дату истечения срока. Будет использоваться, если ExpiryDateFormat не установлен в None. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | Определяет формат даты истечения срока. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Определяет номер партии или лота. Номер партии/лота должен быть буквенно-цифровой строкой длиной до 18 символов. |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | Определяет количество, должно быть целым значением от 0 до 500. Количество можно установить в -1, чтобы не использовать это поле. Значение по умолчанию: -1. |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | Определяет серийный номер. Серийный номер должен быть буквенно-цифровой строкой длиной до 18 символов. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `SecondaryAndAdditionalData`. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | Возвращает хеш-код для данного экземпляра. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | Создаёт вторичные и дополнительные вспомогательные данные из строкового формата в соответствии со спецификацией HIBC LIC. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | Преобразует данные в строковый формат в соответствии со спецификацией HIBC LIC. |

### См. также

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


