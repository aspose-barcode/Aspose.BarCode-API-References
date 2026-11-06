---
title: "枚举"
linktitle: "宏字符"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 枚举。宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。05 宏字符被翻译为 \"[)>\\u001E05\\u001D\" 作为解码数据头部，\"\\u001E\\u0004\" 作为解码数据尾部。06 宏字符被翻译为 \"[)>\\u001E06\\u001D\" 作为解码数据头部，\"\\u001E\\u0004\" 作为解码数据尾部，适用于 C++。"
type: docs
weight: 7300
url: /zh/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。05 宏字符被转换为 "[)>\u001E05\u001D" 作为解码数据头部，"\u001E\u0004" 作为解码数据尾部。06 宏字符被转换为 "[)>\u001E06\u001D" 作为解码数据头部，"\u001E\u0004" 作为解码数据尾部。

```cpp
enum class MacroCharacter
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 无 | 0 | 宏字符不添加到条形码数据中 |
| 宏05 | 5 | 05 宏字符在首位添加到条形码数据中。GS1 数据标识符 ISO 15434 字符被翻译为 "[)>\u001E05\u001D" 作为解码数据头部，"\u001E\u0004" 作为解码数据尾部。 |
| 宏06 | 6 | 06 宏字符在首位添加到条形码数据中。ASC MH10 数据标识符 ISO 15434 字符被翻译为 "[)>\u001E06\u001D" 作为解码数据头部，"\u001E\u0004" 作为解码数据尾部。 |

## 备注


这些示例展示了如何在 MicroPdf417 和 DataMatrix 中编码宏字符
```cpp
[C#]
//要在 ISO 15434 格式中生成自动识别的 GS1 消息，例如 "(10)123ABC(10)123ABC"，您需要：
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

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

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
