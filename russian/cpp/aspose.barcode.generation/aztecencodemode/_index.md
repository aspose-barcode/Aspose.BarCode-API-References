---
title: "enum"
linktitle: "AztecEncodeMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: "перечисление. Режим кодирования для штрих‑кодов Aztec в C++."
type: docs
weight: 5300
url: /ru/cpp/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enum


Режим кодирования для штрихкодов Aztec.

```cpp
enum class AztecEncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | В режиме Auto текст кода (CodeText) кодируется с максимальной компактностью данных. Символы Unicode перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| Расширенный | 3 |  |
| Бинарный | 4 | В бинарном режиме текст кода (CodeText) кодируется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение. |
| ECI | 5 | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |

## Примечания



```cpp
[C#]
//Режим Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Режим Extended
//создать текст кода
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//генерировать текст кода
string codetext = textBuilder.GetExtendedCodetext();

//генерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
