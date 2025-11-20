---
title: Enum HanXinEncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.HanXinEncodeMode enum. Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters
type: docs
weight: 1240
url: /net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters.

```csharp
public enum HanXinEncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are encoded using GB18030 encoding according to HanXin barcode specification. |
| Binary | `1` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | `2` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| Unicode | `3` | Unicode mode designs a way to represent any text data reference to UTF8 encoding/charset in Han Xin Code. |
| URI | `4` | URI mode indicates the data represented in Han Xin Code is Uniform Resource Identifier (URI) reference to RFC 3986. |
| Extended | `5` | Extended mode allow combinations of internal modes: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Codetext can be built manually with prefixes and doubled backslashes, e.g.: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" or using the HanXinExtCodetextBuilder. If the codetext contains an ECI fragment, then only the following modes can be in that codetext after ECI fragment: Auto, Binary, Text, Numeric, URI, ECI. |

## Examples

```csharp
[C#]
// Auto mode
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binary mode
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.HanXinEncodeMode = HanXinEncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECI mode
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.HanXinEncodeMode = HanXinEncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.HanXinECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicode mode
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.HanXinEncodeMode = HanXinEncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URI mode
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.HanXinEncodeMode = HanXinEncodeMode.URI;
    generator.Save("test.bmp");
}

// Extended mode
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.HanXinEncodeMode = HanXinEncodeMode.Extended;
    generator.Save("test.bmp");
}

// Using HanXinExtCodetextBuilder for Extended mode (same codetext as in previous example)
//create codetext
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

//generate codetext
var str = codeTextBuilder.GetExtendedCodetext();

//generate
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.HanXinEncodeMode = HanXinEncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


