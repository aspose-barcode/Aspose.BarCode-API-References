---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Han Xin Code kodningsläge. Det rekommenderas att använda Auto med ASCII‑/kinesiska tecken eller Unicode för Unicode‑tecken i C++."
type: docs
weight: 6900
url: /sv/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Han Xin Code kodningsläge. Det rekommenderas att använda Auto med ASCII / kinesiska tecken eller Unicode för Unicode-tecken.

```cpp
enum class HanXinEncodeMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | I Auto‑läge kodas CodeText med maximal datakomprimering. Unicode‑tecken kodas med GB18030‑kodning enligt HanXin‑streckkodsspecifikationen. |
| Binär | 1 | I Binär‑läge kodas CodeText med maximal datakomprimering. Om ett Unicode‑tecken hittas kastas ett undantag. |
| ECI | 2 | I ECI‑läge omkodas hela meddelandet i den angivna ECIEncoding‑kodningen med insättning av en ECI‑identifierare. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge. |
| Unicode | 3 | Unicode‑läge utformar ett sätt att representera all textdata med hänvisning till UTF8‑kodning/teckenuppsättning i Han Xin Code. |
| URI | 4 | URI‑läge indikerar att data som representeras i Han Xin Code är Uniform Resource Identifier (URI) enligt RFC 3986. |
| Extended | 5 | Extended‑läge tillåter kombinationer av interna lägen: Auto, Binary, Text, Numeric, URI, Unicode, ECI, [Common](../../aspose.barcode.common/) Chinese Region One, [Common](../../aspose.barcode.common/) Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Kodtext kan byggas manuellt med prefix och dubbla bakåtsnedstreck, t.ex.: ":abc\000009:ΑΒΓΔΕ:ab\c" eller med hjälp av [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/). Om kodtexten innehåller ett ECI‑fragment, kan endast följande lägen finnas i kodtexten efter ECI‑fragmentet: Auto, Binary, Text, Numeric, URI, ECI. |

## Anmärkningar



```cpp
[C#]
// Auto‑läge
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binary‑läge
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECI‑läge
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicode‑läge
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URI‑läge
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Extended‑läge
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Använder HanXinExtCodetextBuilder för Extended‑läge (samma kodtext som i föregående exempel)
//skapa kodtext
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

//generera kodtext
var str = codeTextBuilder.GetExtendedCodetext();

//generera
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
