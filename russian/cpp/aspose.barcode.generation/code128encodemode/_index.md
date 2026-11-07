---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Режим кодирования для штрих‑кодов Code128. Спецификация Code 128 на C++."
type: docs
weight: 5900
url: /ru/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Режим кодирования для штрихкодов Code128. Code 128

спецификация.

```cpp
enum class Code128EncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | Кодировать текст кода в классическом режиме ISO 15417. Этот режим следует использовать во всех обычных случаях. |
| CodeA | 1 | Кодировать текст кода только в наборе 128A. |
| CodeB | 2 | Кодировать текст кода только в наборе 128B. |
| CodeC | 4 | Кодировать текст кода только в наборе 128C. |
| CodeAB | 3 | Кодировать текст кода только в наборах 128A и 128B. |
| CodeAC | 5 | Кодировать текст кода только в наборах 128A и 128C. |
| CodeBC | 6 | Кодировать текст кода только в наборах 128B и 128C. |

## Примечания


Этот код демонстрирует, как генерировать код 128 с различными кодировками
```cpp
[C#]
//Генерировать код 128 с кодировкой ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Генерировать код 128 только с кодировкой Codeset A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
