---
title: "GS1Codetext.TryParse"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Метод GS1Codetext. Пытается разобрать строку элемента GS1 в скобках в виде AIvalueAIvalue и возвращает структурированные ошибки проверки. Буквальный  внутри значения должен быть записан как  , другие последовательности экранирования не поддерживаются, и  не требует экранирования."
type: docs
weight: 140
url: /ru/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Пытается разобрать строку элемента GS1 в скобочном виде (AI)value(AI)value и возвращает структурированные ошибки проверки. Буквальная '(' внутри значения должна быть записана как \(. Другие последовательности экранирования не поддерживаются, а ')' экранировать не требуется.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | String | Строка элемента GS1 в скобках для разбора. |
| result | GS1Codetext& | Когда этот метод возвращает true, содержит разобранный текст GS1; в противном случае null. |
| validationResult | GS1ValidationResult& | Содержит результат проверки, или null, когда *value* равно null. |

### Возвращаемое значение

True, когда разбор успешен; иначе false.

### См. также

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


