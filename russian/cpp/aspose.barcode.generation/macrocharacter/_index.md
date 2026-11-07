---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode для C++ справочник API"
description: " перечисление. Значения макрос-символов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Макрос-символ 05 переводится в \"[)>\\u001E05\\u001D\" как заголовок декодированных данных и \"\\u001E\\u0004\" как трейлер декодированных данных. Макрос-символ 06 переводится в \"[)>\\u001E06\\u001D\" как заголовок декодированных данных и \"\\u001E\\u0004\" как трейлер декодированных данных в C++."
type: docs
weight: 7300
url: /ru/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


Значения макросимволов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Макросимвол 05 переводится в "[)>\u001E05\u001D" как заголовок декодированных данных и "\u001E\u0004" как окончание декодированных данных. Макросимвол 06 переводится в "[)>\u001E06\u001D" как заголовок декодированных данных и "\u001E\u0004" как окончание декодированных данных.

```cpp
enum class MacroCharacter
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Нет | 0 | Никакие макрос-символы не добавляются к данным штрихкода |
| Macro05 | 5 | Макрос-символ 05 добавляется к данным штрихкода в первой позиции. Идентификатор данных GS1 ISO 15434 переводится в "[)>\u001E05\u001D" как заголовок декодированных данных и "\u001E\u0004" как трейлер декодированных данных. |
| Macro06 | 6 | Макрос-символ 06 добавляется к данным штрихкода в первой позиции. Идентификатор данных ASC MH10 ISO 15434 переводится в "[)>\u001E06\u001D" как заголовок декодированных данных и "\u001E\u0004" как трейлер декодированных данных. |

## Примечания


Эти примеры показывают, как кодировать макрос-символы в MicroPdf417 и DataMatrix
```cpp
[C#]
//Чтобы сгенерировать автоматически идентифицированное сообщение GS1 в формате ISO 15434, например "(10)123ABC(10)123ABC", вам необходимо:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Кодирует MicroPdf417 с макросом 05 строку: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Кодирует MicroPdf417 с макросом 06 строку: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
