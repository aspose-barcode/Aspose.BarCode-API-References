---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder クラス"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++ で Aspose::BarCode::Generation::HanXinExtCodetextBuilder クラスを使用する方法。"
type: docs
weight: 2800
url: /ja/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Auto モードでコードテキスト フラグメントを追加します |
| [AddBinary](./addbinary/)(System::String) | Binary モードでコードテキスト フラグメントを追加します |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | [Common](../../aspose.barcode.common/) Chinese Region One モードでコードテキスト フラグメントを追加します |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | [Common](../../aspose.barcode.common/) Chinese Region Two モードでコードテキスト フラグメントを追加します |
| [AddECI](./addeci/)(System::String, int32_t) | ECI モードでコードテキスト フラグメントを追加します |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | GB18030 Four Byte モードでコードテキスト フラグメントを追加します |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | GB18030 Two Byte モードでコードテキスト フラグメントを追加します |
| [AddNumeric](./addnumeric/)(System::String) | Numeric モードでコードテキスト フラグメントを追加します |
| [AddText](./addtext/)(System::String) | Text モードでコードテキスト フラグメントを追加します |
| [AddUnicode](./addunicode/)(System::String) | Unicode モードでコードテキスト フラグメントを追加します |
| [AddURI](./adduri/)(System::String) | URI モードでコードテキスト フラグメントを追加します |
| [GetExtendedCodetext](./getextendedcodetext/)() | Extended モードのコードテキスト ビルダーからコードテキストを返します |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## 備考


EncodeMode の拡張モード用 Han Xin Code の拡張コードテキスト ジェネレーター


```cpp
[C#]
//拡張コードテキストモード
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

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabc";

//コードテキストを生成
var str = codeTextBuilder.GetExtendedCodetext();

//生成
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

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
