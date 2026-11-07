---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext class"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext класс. Представляет GS1 codetext для кодирования и декодирования в виде упорядоченной последовательности элементов идентификатора приложения. Исходный порядок и повторяющиеся идентификаторы приложения сохраняются. Скобочная запись имеет форму (AI)value(AI)value. Буквальная открывающая скобка ''('' внутри значения должна быть записана как (; это единственная поддерживаемая последовательность экранирования. Закрывающая скобка '')'' внутри значения не требует экранирования в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Представляет GS1‑кодтекст для кодирования и декодирования в виде упорядоченной последовательности элементов идентификаторов приложений. Порядок исходных элементов и повторяющиеся идентификаторы приложений сохраняются. Квадратное представление имеет форму (AI)значение(AI)значение. Буквальная открывающая скобка '(' внутри значения должна записываться как (; это единственная поддерживаемая escape‑последовательность. Закрывающая скобка ')' внутри значения экранирования не требует.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Описание |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Добавляет проверенный элемент Application Identifier. |
| [get_BarcodeType](./get_barcodetype/)() const | Получает тип штрихкода, используемый для кодирования этого GS1 codetext. Поддерживаемые типы: GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR и типы GS1 DataBar. Значение по умолчанию — GS1Code128. |
| [get_Count](./get_count/)() | Возвращает количество элементов Application Identifier. |
| [get_Elements](./get_elements/)() | Возвращает копию всех элементов в порядке источника. |
| [GetAll](./getall/)(System::String) | Получает все значения для идентификатора приложения в исходном порядке. |
| [GetBarcodeType](./getbarcodetype/)() override | Получает тип штрихкода, используемый для кодирования этого GS1 codetext. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Создаёт скобочный GS1 codetext в форме (AI)value(AI)value. Буквальные открывающие скобки в значениях экранируются как (. |
| [GetFirst](./getfirst/)(System::String) | Получает первое значение для идентификатора приложения. |
| [GS1Codetext](./gs1codetext/)() | Инициализирует пустой GS1 codetext. |
| [idx_get](./idx_get/)(int32_t) | Получает элемент по его позиции в упорядоченной последовательности. |
| [InitFromString](./initfromstring/)(System::String) override | Инициализирует этот экземпляр из скобочного GS1 codetext в форме (AI)value(AI)value. Существующие элементы заменяются только после успешного разбора предоставленного codetext. |
| static [Parse](./parse/)(System::String) | Разбирает строку скобочного GS1 элемента в форме (AI)value(AI)value. Буквальная '(' внутри значения должна быть записана как (; другие последовательности экранирования не поддерживаются, а ')' не требует экранирования. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Устанавливает тип штрихкода, используемый для кодирования этого GS1 codetext. Поддерживаемые типы: GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR и типы GS1 DataBar. Значение по умолчанию — GS1Code128. |
| [ToString](./tostring/)() const override | Возвращает скобочную репрезентацию GS1 в форме (AI)value(AI)value. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Пытается разобрать строку элемента GS1 в скобочной форме (AI)value(AI)value и возвращает структурированные ошибки проверки. Буквальный '(' внутри значения должен быть записан как (; другие последовательности экранирования не поддерживаются, а ')' не требует экранирования. |
| static [Validate](./validate/)(System::String) | Проверяет строку элемента GS1 в скобочной форме (AI)value(AI)value без создания объекта. Буквальный '(' внутри значения должен быть записан как (; другие последовательности экранирования не поддерживаются, а ')' не требует экранирования. |
## См. также

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
