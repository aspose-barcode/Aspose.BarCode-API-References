---
title: "Класс GS1DigitalLink"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink class. Представляет кодовый текст GS1 Digital Link для кодирования и декодирования в виде упорядоченной последовательности элементов идентификаторов приложений. Порядок источника и повторяющиеся идентификаторы приложений сохраняются. Сконструированный кодовый текст представляет собой несжатый URI GS1 Digital Link. Параметры запроса и фрагменты URI, не относящиеся к GS1, игнорируются при разборе."
type: docs
weight: 540
url: /ru/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Представляет кодовый текст GS1 Digital Link для кодирования и декодирования в виде упорядоченной последовательности элементов идентификаторов приложений. Порядок источника и повторяющиеся идентификаторы приложений сохраняются. Сконструированный кодовый текст представляет собой несжатый URI GS1 Digital Link. Параметры запроса и фрагменты URI, не относящиеся к GS1, игнорируются при разборе.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Инициализирует пустой GS1 Digital Link с указанным стемом URI. Первичный ключ выбирается автоматически, когда присутствует ровно один кандидат на первичный ключ. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Инициализирует пустой GS1 Digital Link с указанным стемом URI и первичным ключом. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Получает или задает тип штрихкода, используемый для кодирования этого GS1 Digital Link. Поддерживаемые типы: QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF и Code128. Значение по умолчанию — QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Получает количество элементов идентификаторов приложений. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Получает копию всех элементов в порядке их появления в источнике. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Получает элемент по его позиции в упорядоченной последовательности. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Получает идентификатор приложения, используемый в качестве первичного ключа Digital Link. Null означает, что первичный ключ выбирается автоматически при построении URI. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Получает абсолютный префикс URI до сегмента пути первичного ключа GS1. Стем не содержит строку запроса или фрагмент. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Создаёт GS1 Digital Link, копируя все элементы из кодового текста GS1 и выбирая единственный доступный первичный ключ. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Создаёт GS1 Digital Link, копируя все элементы из кодового текста GS1 и используя указанный первичный ключ. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Разбирает несжатый URI GS1 Digital Link. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Добавляет проверенный элемент идентификатора приложения. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Получает все значения идентификатора приложения в порядке их появления в источнике. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Получает тип штрихкода, используемый для кодирования этого GS1 Digital Link. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Создаёт несжатый URI GS1 Digital Link. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Получает первое значение идентификатора приложения. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Инициализирует этот экземпляр из несжатого URI GS1 Digital Link. Существующее состояние заменяется только после успешного разбора предоставленного URI. Выбранный тип штрихкода сохраняется. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Создает независимый GS1 codetext, содержащий текущие элементы GS1. Информация только URI не включается. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Возвращает несжатый GS1 Digital Link URI. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Форматирует текущее состояние объекта как несжатый GS1 Digital Link URI. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Пытается разобрать несжатый GS1 Digital Link URI и возвращает структурированные ошибки проверки. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Проверяет несжатый GS1 Digital Link URI без создания объекта. |

### См. также

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


