---
title: "Класс GS1Codetext"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext class. Представляет GS1 codetext для кодирования и декодирования как упорядоченную последовательность элементов идентификаторов приложений. Порядок источника и повторяющиеся идентификаторы приложений сохраняются. Скалярное представление имеет форму AIvalueAIvalue. Буквальная открывающая скобка  внутри значения должна быть записана как  — это единственная поддерживаемая последовательность экранирования. Закрывающая скобка  внутри значения экранировать не требуется."
type: docs
weight: 530
url: /ru/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Представляет GS1 codetext для кодирования и декодирования как упорядоченную последовательность элементов идентификаторов приложений. Порядок источника и повторяющиеся идентификаторы приложений сохраняются. Скалярное представление имеет форму (AI)value(AI)value. Буквальная открывающая скобка '(' внутри значения должна быть записана как \(. Это единственная поддерживаемая последовательность экранирования. Закрывающая скобка ')' внутри значения экранировать не требуется.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Получает или задает тип штрихкода, используемый для кодирования этого GS1 codetext. Поддерживаемые типы: GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR и типы GS1 DataBar. Значение по умолчанию — GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Получает количество элементов идентификаторов приложений. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Получает копию всех элементов в порядке их появления в источнике. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Получает элемент по его позиции в упорядоченной последовательности. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Разбирает строку элемента GS1 в скобочном виде (AI)value(AI)value. Буквальная '(' внутри значения должна быть записана как \(. Другие последовательности экранирования не поддерживаются, а ')' экранировать не требуется. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Добавляет проверенный элемент идентификатора приложения. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Получает все значения идентификатора приложения в порядке их появления в источнике. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Получает тип штрихкода, используемый для кодирования этого GS1 codetext. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Создает скобочный GS1 codetext в виде (AI)value(AI)value. Буквальные открывающие скобки в значениях экранируются как \. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Получает первое значение идентификатора приложения. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Инициализирует этот экземпляр из скобочного GS1 codetext в виде (AI)value(AI)value. Существующие элементы заменяются только после успешного разбора предоставленного codetext. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Возвращает скобочное представление GS1 в виде (AI)value(AI)value. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Пытается разобрать строку элемента GS1 в скобочном виде (AI)value(AI)value и возвращает структурированные ошибки проверки. Буквальная '(' внутри значения должна быть записана как \(. Другие последовательности экранирования не поддерживаются, а ')' экранировать не требуется. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Проверяет строку элемента GS1 в скобочном виде (AI)value(AI)value без создания объекта. Буквальная '(' внутри значения должна быть записана как \(. Другие последовательности экранирования не поддерживаются, а ')' экранировать не требуется. |

### См. также

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


