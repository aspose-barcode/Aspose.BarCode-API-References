---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder クラス"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++ で Aspose::BarCode::Generation::AztecExtCodetextBuilder クラスを使用する方法。"
type: docs
weight: 200
url: /ja/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 拡張チャネル識別子を使用してコードテキストを追加します |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 拡張コードテキスト項目にプレーンコードテキストを追加します |
| virtual [Clear](../extcodetextbuilder/clear/)() | 拡張コードテキスト項目をクリアします |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 拡張コードテキストリストから拡張コードテキストを生成します。 |
## 備考


AztecEncodeMode の ExtendedCodetext モード用の Aztec バーコード向け拡張コードテキストジェネレータ

可視テキストから管理文字を削除するように、[BarcodeGenerator](../barcodegenerator/) の TwoDDisplayText プロパティを使用します。

このサンプルは、拡張モードで [AztecExtCodetextBuilder](./) を使用する方法を示しています。
```cpp
[C#]
//コードテキストを作成
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//コードテキストを生成
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## 関連項目

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
