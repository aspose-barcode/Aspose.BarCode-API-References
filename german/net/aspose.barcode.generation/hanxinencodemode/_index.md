---
title: "Aufzählung HanXinEncodeMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.HanXinEncodeMode Aufzählung. Han Xin Code-Kodierungsmodus. Es wird empfohlen, Auto mit ASCII-/Chinesischen Zeichen oder Unicode für Unicode-Zeichen zu verwenden."
type: docs
weight: 1360
url: /de/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Kodierungsmodus für Han Xin Code. Es wird empfohlen, Auto mit ASCII-/Chinesischen Zeichen oder Unicode für Unicode-Zeichen zu verwenden.

```csharp
public enum HanXinEncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Im Auto-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Unicode-Zeichen werden gemäß der HanXin-Barcode-Spezifikation mit GB18030-Kodierung kodiert. |
| Binary | `1` | Im Binär-Modus wird der CodeText mit maximaler Datenkompaktheit kodiert. Wird ein Unicode-Zeichen gefunden, wird eine Ausnahme ausgelöst. |
| ECI | `2` | Im ECI-Modus wird die gesamte Nachricht in der angegebenen ECIEncoding-Kodierung mit dem Einfügen eines ECI-Identifikators neu kodiert. Wird ein Zeichen gefunden, das von der ausgewählten ECI-Kodierung nicht unterstützt wird, wird eine Ausnahme ausgelöst. Bitte beachten Sie, dass einige ältere (vor 2006) Scanner diesen Modus möglicherweise nicht unterstützen. |
| Unicode | `3` | Der Unicode-Modus bietet eine Methode, beliebige Textdaten in Bezug auf UTF8-Kodierung/Zeichensatz im Han Xin Code darzustellen. |
| URI | `4` | Der URI-Modus zeigt an, dass die im Han Xin Code dargestellten Daten ein Uniform Resource Identifier (URI)-Verweis gemäß RFC 3986 sind. |
| Extended | `5` | Der erweiterte Modus erlaubt Kombinationen interner Modi: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Der Codetext kann manuell mit Präfixen und doppelten Backslashes erstellt werden, z.B.: @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" oder mit dem HanXinExtCodetextBuilder. Enthält der Codetext ein ECI-Fragment, dürfen danach im Codetext nur die folgenden Modi verwendet werden: Auto, Binary, Text, Numeric, URI, ECI. |

## Beispiele

```csharp
[C#]
// Auto-Modus
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binary-Modus
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECI-Modus
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicode-Modus
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URI-Modus
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Erweiterter Modus
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Verwendung von HanXinExtCodetextBuilder für den erweiterten Modus (derselbe Codetext wie im vorherigen Beispiel)
//Codetext erstellen
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

//Codetext generieren
var str = codeTextBuilder.GetExtendedCodetext();

//generieren
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


