---
title: "クラス HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder クラス。EncodeMode の拡張モード用の漢信コード（Han Xin Code）向け拡張コードテキストジェネレータです。"
type: docs
weight: 1380
url: /ja/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

EncodeMode の拡張モード用の漢信コード（Han Xin Code）向け拡張コードテキストジェネレータ

```csharp
public class HanXinExtCodetextBuilder
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Auto モードでコードテキストフラグメントを追加します |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Binary モードでコードテキストフラグメントを追加します |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Common Chinese Region One モードでコードテキストフラグメントを追加します |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Common Chinese Region Two モードでコードテキストフラグメントを追加します |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | ECI モードでコードテキストフラグメントを追加します |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | GB18030 Four Byte モードでコードテキストフラグメントを追加します |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | GB18030 Two Byte モードでコードテキストフラグメントを追加します |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Numeric モードでコードテキストフラグメントを追加します |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Text モードでコードテキストフラグメントを追加します |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Unicode モードでコードテキストフラグメントを追加します |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | URI モードでコードテキストフラグメントを追加します |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | 拡張モードのコードテキストビルダーからコードテキストを返します |

## 例

```csharp
[C#]
//拡張コードテキストモード
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

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabc";

//コードテキストを生成する
var str = codeTextBuilder.GetExtendedCodetext();

//生成する
using (var bg = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    bg.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    var img = bg.GenerateBarCodeImage();
    using (var r = new BarCodeReader(img, DecodeType.HanXin))
     {
        var found = r.ReadBarCodes();
        Assert.AreEqual(1, found.Length);
        Assert.AreEqual(expectedStr, found[0].CodeText);
      }
}
```

### 関連項目

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


