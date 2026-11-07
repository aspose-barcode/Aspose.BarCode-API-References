---
title: "method"
linktitle: "Parse"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Разбирает строку элемента GS1 в скобках в виде (AI)value(AI)value. Буквальный ''('' внутри значения должен быть записан как (; другие последовательности экранирования не поддерживаются, а '')'' экранировать не требуется в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.barcode.complexbarcode/gs1codetext/parse/
---
## GS1Codetext::Parse method


Разбирает строку скобочного GS1 элемента в форме (AI)value(AI)value. Буквальная '(' внутри значения должна быть записана как (; другие последовательности экранирования не поддерживаются, а ')' не требует экранирования.

```cpp
static System::SharedPtr<GS1Codetext> Aspose::BarCode::ComplexBarcode::GS1Codetext::Parse(System::String value)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| value | System::String | Строка элемента GS1 в скобках для разбора. |

### ReturnValue

Разобранный код текста GS1.

## См. также

* Class [GS1Codetext](../)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
