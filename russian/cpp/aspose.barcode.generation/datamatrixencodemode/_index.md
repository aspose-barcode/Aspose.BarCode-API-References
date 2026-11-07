---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Режим кодирования кодировщика DataMatrix, по умолчанию Auto в C++."
type: docs
weight: 6300
url: /ru/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


Режим кодирования кодировщика DataMatrix, по умолчанию Auto

```cpp
enum class DataMatrixEncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | В режиме Auto текст кода (CodeText) кодируется с максимальной компактностью данных. Символы Unicode перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| ASCII | 1 | Кодирует один буквенно-цифровой или два числовых символа на байт. |
| C40 | 8 | Использует кодирование C40. Кодирует буквенно-цифровые символы верхнего регистра, нижний регистр и специальные символы. |
| Текст | 9 | Использует кодирование Text. Кодирует буквенно-цифровые символы нижнего регистра, верхний регистр и специальные символы. |
| EDIFACT | 10 | Использует кодирование EDIFACT. Использует шесть бит на символ, кодирует цифры, буквы верхнего регистра и многие знаки препинания, но не поддерживает буквы нижнего регистра. |
| ANSIX12 | 11 | Использует кодирование ANSI X12. |
| Расширенный | 13 |  |
| Base256 | 14 | Кодировать 8‑битные значения |
| Бинарный | 15 | В бинарном режиме текст кода (CodeText) кодируется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение. |
| ECI | 16 | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |

## Примечания


Этот пример показывает, как использовать codetext в расширенном режиме.
```cpp
[C#]
//Режим Auto
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Режим байтов
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Режим расширенного текста кода
//создать текст кода
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//генерировать текст кода
string codetext = textBuilder.GetExtendedCodetext();

//генерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
