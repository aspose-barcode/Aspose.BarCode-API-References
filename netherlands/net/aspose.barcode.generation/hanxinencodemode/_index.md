---
title: "Enum HanXinEncodeMode"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.HanXinEncodeMode enum. Han Xin Code-coderingsmodus. Het wordt aanbevolen om Auto te gebruiken met ASCII-/Chinese tekens of Unicode voor Unicode-tekens."
type: docs
weight: 1360
url: /nl/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Han Xin Code coderingsmodus. Het wordt aanbevolen Auto te gebruiken met ASCII/Chinese tekens of Unicode voor Unicode-tekens.

```csharp
public enum HanXinEncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | In Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode-tekens worden gecodeerd met GB18030-codering volgens de HanXin-barcode-specificatie. |
| Binary | `1` | In de Binaire-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als er een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid. |
| ECI | `2` | In de ECI-modus wordt het volledige bericht opnieuw gecodeerd in de opgegeven ECIEncoding‑codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. |
| Unicode | `3` | Unicode-modus biedt een manier om elke tekstgegevensreferentie weer te geven naar UTF8-codering/karakterset in Han Xin Code. |
| URI | `4` | URI-modus geeft aan dat de gegevens die in Han Xin Code worden weergegeven een Uniform Resource Identifier (URI)-referentie zijn volgens RFC 3986. |
| Extended | `5` | Extended-modus staat combinaties van interne modi toe: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Codetext kan handmatig worden opgebouwd met prefixen en dubbele backslashes, bijv.: @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" of met de HanXinExtCodetextBuilder. Als de codetext een ECI-fragment bevat, mogen daarna alleen de volgende modi in die codetext voorkomen na het ECI-fragment: Auto, Binary, Text, Numeric, URI, ECI. |

## Voorbeelden

```csharp
[C#]
// Auto-modus
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binaire modus
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECI-modus
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicode-modus
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URI-modus
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Extended-modus
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Gebruik van HanXinExtCodetextBuilder voor Extended-modus (dezelfde codetext als in het vorige voorbeeld)
//codetext maken
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

//codetext genereren
var str = codeTextBuilder.GetExtendedCodetext();

//genereren
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


