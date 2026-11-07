---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode для C++ справочник API"
description: " method. Пытается разобрать строку элемента GS1 в скобках в виде (AI)value(AI)value и возвращает структурированные ошибки проверки. Буквальный ''('' внутри значения должен быть записан как (; другие последовательности экранирования не поддерживаются, а '')'' не требует экранирования в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Пытается разобрать строку элемента GS1 в скобочной форме (AI)value(AI)value и возвращает структурированные ошибки проверки. Буквальный '(' внутри значения должен быть записан как (; другие последовательности экранирования не поддерживаются, а ')' не требует экранирования.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| value | System::String | Строка элемента GS1 в скобках для разбора. |
| result | System::SharedPtr\<GS1Codetext\>\& | Когда этот метод возвращает true, содержит разобранный код текста GS1; иначе null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Содержит результат проверки, или null, когда *value*  равно null. |

### ReturnValue

True, когда разбор успешен; иначе false.

## См. также

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
