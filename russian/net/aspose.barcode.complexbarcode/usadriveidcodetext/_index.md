---
title: "Класс USADriveIdCodetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext класс. Класс для кодирования и декодирования текста, встроенного в код PDF417 водительского удостоверения США"
type: docs
weight: 810
url: /ru/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Класс для кодирования и декодирования текста, встроенного в код PDF417 водительского удостоверения США

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | Номер версии AAMVA 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Этот номер уникально идентифицирует юрисдикцию-выдающего и может быть получен путем обращения к ISO Issuing Authority(AAMVA). Полный 6-значный IIN должен быть закодирован. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Поля, специфичные для юрисдикции |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Номер версии юрисдикции 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Обязательные элементы (поля) карты |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Номер 00-99 подфайлов |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Опциональные элементы (поля) карты |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Содержит информацию о следующих подфайлах, типах, смещениях и длинах. Важно: задайте только тип, смещение и длина будут установлены автоматически. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Возвращает тип штрихкода USA DL (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Построить codetext из данных USA DL |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Инициализировать объект USA DL из codetext |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Сохраняет в XML |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Обязательные элементы (поля) карты |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Опциональные элементы (поля) карты |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | Свойства подфайла USA DL, смещение и длина устанавливаются автоматически. |

### См. также

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


