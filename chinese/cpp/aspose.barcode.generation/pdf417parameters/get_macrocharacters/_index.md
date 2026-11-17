---
title: "method"
linktitle: "get_MacroCharacters"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值：MacroCharacters.None，在 C++ 中。"
type: docs
weight: 3900
url: /zh/cpp/aspose.barcode.generation/pdf417parameters/get_macrocharacters/
---
## Pdf417Parameters::get_MacroCharacters method


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 MicroPdf417 一起使用，并对 916 和 917 MicroPdf417 模式进行编码。默认值： [MacroCharacters.None](../../barcodeclassifications/)。

```cpp
MacroCharacter Aspose::BarCode::Generation::Pdf417Parameters::get_MacroCharacters() const
```

## 备注


这些示例展示了如何在 MicroPdf417 中编码宏字符
```cpp
[C#]
//使用 05 宏对 MicroPdf417 进行编码，字符串为："[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//使用 06 宏对 MicroPdf417 进行编码，字符串为："[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## 另见

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
