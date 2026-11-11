---
title: "列挙体 HanXinEncodeMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Generation.HanXinEncodeMode 列挙体。Han Xin Code のエンコードモードです。Unicode文字にはUnicode、ASCII / Chinese characters には Auto の使用が推奨されます。"
type: docs
weight: 1360
url: /ja/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Han Xin Code のエンコードモードです。Unicode文字にはUnicode、ASCII / Chinese characters には Auto の使用が推奨されます。

```csharp
public enum HanXinEncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | Autoモードでは、CodeTextは最大のデータ圧縮でエンコードされます。Unicode文字はHan Xinバーコード仕様に従ってGB18030エンコーディングでエンコードされます。 |
| Binary | `1` | Binaryモードでは、CodeTextは最大のデータ圧縮でエンコードされます。Unicode文字が見つかった場合、例外がスローされます。 |
| ECI | `2` | ECIモードでは、メッセージ全体が指定されたECIEncodingで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、一部の古い（2006年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |
| Unicode | `3` | Unicodeモードは、Han Xin Code においてUTF8エンコーディング/文字セットへの任意のテキストデータ参照を表す方法を設計します。 |
| URI | `4` | URIモードは、Han Xin Code に表されるデータがRFC 3986のUniform Resource Identifier（URI）参照であることを示します。 |
| Extended | `5` | 拡張モードは、内部モードの組み合わせを許可します: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte。Codetextはプレフィックスと二重バックスラッシュを使用して手動で構築できます。例: @\"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c\" または HanXinExtCodetextBuilder を使用します。CodetextにECIフラグメントが含まれる場合、ECIフラグメント以降のCodetextでは以下のモードのみ使用可能です: Auto, Binary, Text, Numeric, URI, ECI。 |

## 例

```csharp
[C#]
// Autoモード
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binaryモード
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECIモード
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicodeモード
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URIモード
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Extendedモード
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// 拡張モードで HanXinExtCodetextBuilder を使用する（前の例と同じCodetext）
//コードテキストを作成する
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

//コードテキストを生成する
var str = codeTextBuilder.GetExtendedCodetext();

//生成する
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### 関連項目

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


