---
title: Address
second_title: Справочник по API Aspose.BarCode для .NET
description: Адрес кредитора или должника.
type: docs
weight: 300
url: /ru/net/aspose.barcode.complexbarcode/address/
---
## Address class

Адрес кредитора или должника.

Вы можете указать улицу, номер дома, почтовый индекс и город (введитеструктурированный адрес ) или адресная строка 1 и 2 (введитекомбинированные элементы адреса ). Тип устанавливается автоматически set после установки любого из этих полей. Перед настройкой полей тип адресанеопределенный . Если установлены поля обоих типов, тип адреса становитсяпротиворечивый . Имя и код страны должны быть установлены всегда, если только все поля не пусты.

```csharp
public sealed class Address : IEquatable<Address>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Address](address)() | Создает экземпляр Address |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1) { get; set; } | Получает или задает адресную строку 1. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2) { get; set; } | Получает или задает адресную строку 2. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode) { get; set; } | Получает или задает двухбуквенный код страны ISO. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno) { get; set; } | Получает или задает номер дома. |
| [Name](../../aspose.barcode.complexbarcode/address/name) { get; set; } | Получает или задает имя, либо имя и фамилию физического лица, либо название компании юридического лица. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode) { get; set; } | Получает или задает почтовый индекс. |
| [Street](../../aspose.barcode.complexbarcode/address/street) { get; set; } | Получает или задает улицу. |
| [Town](../../aspose.barcode.complexbarcode/address/town) { get; set; } | Получает или задает город или город. |
| [Type](../../aspose.barcode.complexbarcode/address/type) { get; } | Получает тип адреса. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear)() | Очищает все поля и устанавливает типUndetermined . |
| [Equals](../../aspose.barcode.complexbarcode/address/equals#equals)(Address) | Определяет, равен ли указанный адрес текущему адресу. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals#equals_1)(object) | Определяет, равен ли указанный объект текущему объекту. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode)() | Получает хэш-код для этого экземпляра. |

### Смотрите также

* пространство имен [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->