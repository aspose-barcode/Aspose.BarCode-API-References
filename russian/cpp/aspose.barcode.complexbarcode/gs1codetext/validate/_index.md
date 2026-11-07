---
title: "method"
linktitle: "Validate"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Проверяет строку элемента GS1 в скобках в виде (AI)value(AI)value без создания объекта. Буквальный ''('' внутри значения должен быть записан как (; другие последовательности экранирования не поддерживаются, а '')'' экранировать не требуется в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.barcode.complexbarcode/gs1codetext/validate/
---
## GS1Codetext::Validate method


Проверяет строку элемента GS1 в скобочной форме (AI)value(AI)value без создания объекта. Буквальный '(' внутри значения должен быть записан как (; другие последовательности экранирования не поддерживаются, а ')' не требует экранирования.

```cpp
static System::SharedPtr<Common::GS1ValidationResult> Aspose::BarCode::ComplexBarcode::GS1Codetext::Validate(System::String value)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| value | System::String | Строка элемента GS1 в скобках для проверки. |

### ReturnValue

Структурированный результат проверки.

## См. также

* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
