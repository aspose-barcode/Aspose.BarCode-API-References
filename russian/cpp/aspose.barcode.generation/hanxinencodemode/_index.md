---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Режим кодирования Han Xin Code. Рекомендуется использовать Auto с символами ASCII/китайскими символами или Unicode для символов Unicode в C++."
type: docs
weight: 6900
url: /ru/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Режим кодирования Han Xin Code. Рекомендуется использовать Auto с символами ASCII/китайскими или Unicode для символов Unicode.

```cpp
enum class HanXinEncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | В режиме Auto текст CodeText кодируется с максимальной компактностью данных. Символы Unicode кодируются с использованием кодировки GB18030 согласно спецификации штрихкода HanXin. |
| Бинарный | 1 | В бинарном режиме текст кода (CodeText) кодируется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение. |
| ECI | 2 | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |
| Unicode | 3 | Режим Unicode предоставляет способ представления любых текстовых данных с ссылкой на кодировку/символьный набор UTF8 в Han Xin Code. |
| URI | 4 | Режим URI указывает, что данные, представленные в Han Xin Code, являются ссылкой Uniform Resource Identifier (URI) согласно RFC 3986. |
| Extended | 5 | Режим Extended позволяет комбинировать внутренние режимы: Auto, Binary, Text, Numeric, URI, Unicode, ECI, [Common](../../aspose.barcode.common/) Chinese Region One, [Common](../../aspose.barcode.common/) Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Текст кода (Codetext) можно создавать вручную с префиксами и удвоенными обратными слешами, например: \":abc\\000009:ΑΒΓΔΕ:ab\\c\" или используя [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/). Если Codetext содержит фрагмент ECI, то после фрагмента ECI в Codetext могут быть только следующие режимы: Auto, Binary, Text, Numeric, URI, ECI. |

## Примечания



```cpp
[C#]
// Режим Auto
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Режим Binary
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// Режим ECI
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Режим Unicode
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// Режим URI
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Режим Extended
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Использование HanXinExtCodetextBuilder для режима Extended (тот же Codetext, что и в предыдущем примере)
//создать текст кода
var codeTextBuilder = new HanXinExtCodetextBuilder();
codeTextBuilder.AddGB18030TwoByte("漄");
codeTextBuilder.AddGB18030FourByte("㐁");
codeTextBuilder.AddCommonChineseRegionOne("全");
codeTextBuilder.AddCommonChineseRegionTwo("螅");
codeTextBuilder.AddNumeric("123");
codeTextBuilder.AddText("qwe");
codeTextBuilder.AddUnicode("ıntəˈnæʃənəl");
codeTextBuilder.AddECI("ΑΒΓΔΕ", 9);
codeTextBuilder.AddAuto("abc");
codeTextBuilder.AddBinary("abc");
codeTextBuilder.AddURI(@"backslashes_should_be_doubled\000555:test");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

//генерировать текст кода
var str = codeTextBuilder.GetExtendedCodetext();

//генерировать
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
