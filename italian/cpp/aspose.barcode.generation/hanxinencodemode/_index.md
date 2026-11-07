---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Modalità di codifica Han Xin Code. Si consiglia di usare Auto con caratteri ASCII / cinesi o Unicode per i caratteri Unicode in C++."
type: docs
weight: 6900
url: /it/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Modalità di codifica Han Xin Code. Si consiglia di utilizzare Auto con caratteri ASCII / Cinesi o Unicode per i caratteri Unicode.

```cpp
enum class HanXinEncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | In modalità Auto, il CodeText è codificato con la massima compattezza dei dati. I caratteri Unicode sono codificati usando la codifica GB18030 secondo la specifica del codice a barre HanXin. |
| Binario | 1 | In modalità Binario, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene generata un'eccezione. |
| ECI | 2 | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione. Si prega di notare che alcuni scanner vecchi (pre 2006) potrebbero non supportare questa modalità. |
| Unicode | 3 | La modalità Unicode definisce un modo per rappresentare qualsiasi dato testuale facendo riferimento alla codifica/carattere UTF8 nel Han Xin Code. |
| URI | 4 | La modalità URI indica che i dati rappresentati nel Han Xin Code sono un Uniform Resource Identifier (URI) secondo la RFC 3986. |
| Extended | 5 | La modalità Extended consente combinazioni di modalità interne: Auto, Binary, Text, Numeric, URI, Unicode, ECI, [Common](../../aspose.barcode.common/) Chinese Region One, [Common](../../aspose.barcode.common/) Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Il Codetext può essere costruito manualmente con prefissi e doppi backslash, ad esempio: ":abc\\000009:ΑΒΓΔΕ:ab\\c" o utilizzando il [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/). Se il Codetext contiene un frammento ECI, solo le seguenti modalità possono essere presenti in quel Codetext dopo il frammento ECI: Auto, Binary, Text, Numeric, URI, ECI. |

## Osservazioni



```cpp
[C#]
// Modalità Auto
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Modalità Binary
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// Modalità ECI
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Modalità Unicode
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// Modalità URI
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Modalità Extended
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Utilizzo di HanXinExtCodetextBuilder per la modalità Extended (stesso codetext dell'esempio precedente)
//crea codetext
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

//genera codetext
var str = codeTextBuilder.GetExtendedCodetext();

//genera
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
