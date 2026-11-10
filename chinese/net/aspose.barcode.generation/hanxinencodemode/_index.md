---
title: "枚举 HanXinEncodeMode"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.HanXinEncodeMode 枚举。汉信码编码模式。建议对 ASCII/中文字符使用 Auto，或对 Unicode 字符使用 Unicode。"
type: docs
weight: 1360
url: /zh/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Han Xin Code 编码模式。建议在使用 ASCII / 中文字符时使用 Auto，或在 Unicode 字符时使用 Unicode。

```csharp
public enum HanXinEncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 在 Auto 模式下，CodeText 以最高数据紧凑度进行编码。Unicode 字符根据汉信条码规范使用 GB18030 编码。 |
| Binary | `1` | 在 Binary 模式下，CodeText 以最高的数据紧凑度进行编码。如果发现 Unicode 字符，则会抛出异常。 |
| ECI | `2` | 在 ECI 模式下，整个消息会在指定的 ECIEncoding 编码中重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。请注意，某些旧的（2006 年前）扫描仪可能不支持此模式。 |
| Unicode | `3` | Unicode 模式设计了一种在汉信码中使用 UTF8 编码/字符集表示任何文本数据的方式。 |
| URI | `4` | URI 模式表示在汉信码中表示的数据是符合 RFC 3986 的统一资源标识符（URI）引用。 |
| Extended | `5` | 扩展模式允许内部模式的组合：Auto、Binary、Text、Numeric、URI、Unicode、ECI、Common Chinese Region One、Common Chinese Region Two、GB18030 Two Byte、GB18030 Four Byte。可以使用前缀和双反斜杠手动构建代码文本，例如：@\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\"，或使用 HanXinExtCodetextBuilder。如果代码文本包含 ECI 片段，则在该 ECI 片段之后的代码文本只能包含以下模式：Auto、Binary、Text、Numeric、URI、ECI。 |

## 示例

```csharp
[C#]
// Auto 模式
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// 二进制模式
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECI 模式
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicode 模式
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URI 模式
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// 扩展模式
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// 使用 HanXinExtCodetextBuilder 进行扩展模式（与前面示例相同的代码文本）
//创建代码文本
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

//生成代码文本
var str = codeTextBuilder.GetExtendedCodetext();

//生成
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


