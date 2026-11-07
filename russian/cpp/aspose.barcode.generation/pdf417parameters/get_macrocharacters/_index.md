---
title: "method"
linktitle: "get_MacroCharacters"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с MicroPdf417 и кодирует режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None в C++."
type: docs
weight: 3900
url: /ru/cpp/aspose.barcode.generation/pdf417parameters/get_macrocharacters/
---
## Pdf417Parameters::get_MacroCharacters method


Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с MicroPdf417 и кодирует режимы 916 и 917 MicroPdf417. Значение по умолчанию: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
MacroCharacter Aspose::BarCode::Generation::Pdf417Parameters::get_MacroCharacters() const
```

## Примечания


Эти примеры показывают, как кодировать Macro Characters в MicroPdf417
```cpp
[C#]
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

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
