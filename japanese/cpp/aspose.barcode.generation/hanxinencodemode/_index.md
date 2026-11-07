---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " 列挙型。Han Xin Code のエンコードモードです。C++ では、ASCII / 中国語文字の場合は Auto、Unicode 文字の場合は Unicode の使用が推奨されます。"
type: docs
weight: 6900
url: /ja/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Han Xin Code エンコーディングモード。ASCII / 中国語文字と共に Auto を使用するか、Unicode 文字には Unicode を使用することを推奨します。

```cpp
enum class HanXinEncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | Auto モードでは、CodeText が最大限にデータを圧縮してエンコードされます。Unicode 文字は HanXin バーコード仕様に従い、GB18030 エンコーディングでエンコードされます。 |
| バイナリ | 1 | バイナリモードでは、CodeText が最大限のデータ圧縮でエンコードされます。Unicode 文字が見つかった場合、例外がスローされます。 |
| ECI | 2 | ECI モードでは、メッセージ全体が指定された ECIEncoding で再エンコードされ、ECI 識別子が挿入されます。選択された ECI エンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、一部の古い（2006 年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |
| Unicode | 3 | Unicode モードは、Han Xin Code で任意のテキストデータを UTF8 エンコーディング/文字セットで表現する方法を提供します。 |
| URI | 4 | URI モードは、Han Xin Code で表現されるデータが RFC 3986 に準拠した Uniform Resource Identifier (URI) であることを示します。 |
| Extended | 5 | 拡張モードでは、内部モードの組み合わせを許可します: Auto、Binary、Text、Numeric、URI、Unicode、ECI、[Common](../../aspose.barcode.common/) Chinese Region One、[Common](../../aspose.barcode.common/) Chinese Region Two、GB18030 Two Byte、GB18030 Four Byte。Codetext はプレフィックスと二重バックスラッシュで手動構築でき、例: \":abc\\000009:ΑΒΓΔΕ:ab\\c\" または [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/) を使用します。Codetext に ECI フラグメントが含まれる場合、ECI フラグメント以降の Codetext では次のモードのみ使用可能です: Auto、Binary、Text、Numeric、URI、ECI。 |

## 備考



```cpp
[C#]
// Auto モード
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binary モード
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECI モード
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicode モード
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URI モード
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// 拡張モード
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// 拡張モードで HanXinExtCodetextBuilder を使用する（前の例と同じ codetext）
//コードテキストを作成
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

//コードテキストを生成
var str = codeTextBuilder.GetExtendedCodetext();

//生成
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
