---
title: "枚举"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: " enum. Han Xin Code 编码模式。建议在 C++ 中对 ASCII / 中文字符使用 Auto，或对 Unicode 字符使用 Unicode。"
type: docs
weight: 6900
url: /zh/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Han Xin Code 编码模式。建议在 ASCII / 中文字符或 Unicode 字符时使用 Auto。

```cpp
enum class HanXinEncodeMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。Unicode 字符根据 HanXin 条码规范使用 GB18030 编码。 |
| 二进制 | 1 | 在二进制模式下，CodeText 以最大数据紧凑度进行编码。如果发现 Unicode 字符，则会抛出异常。 |
| ECI | 2 | 在 ECI 模式下，整个消息会使用指定的 ECIEncoding 重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则会抛出异常。请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。 |
| Unicode | 3 | Unicode 模式设计了一种在 Han Xin Code 中使用 UTF8 编码/字符集表示任何文本数据的方法。 |
| URI | 4 | URI 模式表示在 Han Xin Code 中表示的数据是符合 RFC 3986 的统一资源标识符（URI）引用。 |
| Extended | 5 | Extended 模式允许组合内部模式：Auto、Binary、Text、Numeric、URI、Unicode、ECI、[Common](../../aspose.barcode.common/) Chinese Region One、[Common](../../aspose.barcode.common/) Chinese Region Two、GB18030 Two Byte、GB18030 Four Byte。Codetext 可以手动使用前缀和双反斜杠构建，例如：\":abc\\000009:ΑΒΓΔΕ:ab\\c\"，或使用 [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/)。如果 codetext 包含 ECI 片段，则在该 ECI 片段之后的 codetext 只能包含以下模式：Auto、Binary、Text、Numeric、URI、ECI。 |

## 备注



```cpp
[C#]
// 自动模式
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binary 模式
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

// Extended 模式
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// 使用 HanXinExtCodetextBuilder 进行 Extended 模式（与前例相同的 codetext）
//创建码文本
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

//生成码文本
var str = codeTextBuilder.GetExtendedCodetext();

//生成
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
