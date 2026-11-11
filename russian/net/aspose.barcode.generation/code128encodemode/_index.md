---
title: "Перечисление Code128EncodeMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.Generation.Code128EncodeMode. Режим кодирования для штрихкодов Code128. Спецификация Code 128"
type: docs
weight: 1120
url: /ru/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Режим кодирования для штрихкодов Code128. Спецификация [Code 128](https://en.wikipedia.org/wiki/Code_128).

```csharp
public enum Code128EncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | Кодировать текст кода в классическом режиме ISO 15417. Этот режим следует использовать во всех обычных случаях. |
| CodeA | `1` | Кодировать текст кода только в наборе 128A. |
| CodeB | `2` | Кодировать текст кода только в наборе 128B. |
| CodeC | `4` | Кодировать текст кода только в наборе 128C. |
| CodeAB | `3` | Кодировать текст кода только в наборах 128A и 128B. |
| CodeAC | `5` | Кодировать текст кода только в наборах 128A и 128C. |
| CodeBC | `6` | Кодировать текст кода только в наборах 128B и 128C. |

## Примеры

Этот код демонстрирует, как генерировать code 128 с различными кодировками

```csharp
[C#]
//Генерировать code 128 с кодировкой ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Генерировать код 128 только с кодировкой Codeset A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### См. также

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


