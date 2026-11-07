---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder クラス"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++ で Aspose::BarCode::Generation::QrExtCodetextBuilder クラスを使用する方法。"
type: docs
weight: 4300
url: /ja/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | 指定された QR 圧縮モードでコードテキストを拡張コードテキスト項目に追加します。 |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 拡張チャネル識別子を使用してコードテキストを追加します |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | 最初の位置にFNC1を設定します。以前に別のFNC1モードが設定されていた場合、置き換えられます。 |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | 拡張コードテキスト項目にグループ区切り文字 (GS - '\\u001D') を追加します |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | 2番目の位置にFNC1を設定します。以前に別のFNC1モードが設定されていた場合、置き換えられます。 |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 拡張コードテキスト項目にプレーンコードテキストを追加します |
| [Clear](./clear/)() override | 拡張コードテキスト項目をクリアします |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 拡張コードテキストリストから拡張コードテキストを生成します。 |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## 備考


EncodeMode の ExtendedCodetext モード用の 2D QR バーコード向け拡張コードテキストジェネレータ

可視テキストから管理文字を削除するように、[BarcodeGenerator](../barcodegenerator/) の TwoDDisplayText プロパティを使用します。

このサンプルは、拡張モードでFNC1の先頭位置を使用する方法を示しています。
```cpp
[C#]
//コードテキストを作成
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//コードテキストを生成
string codetext = TextBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


このサンプルは、拡張モードでFNC1の第2位置を使用する方法を示しています。
```cpp
[C#]
//コードテキストを作成
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//コードテキストを生成
string codetext = TextBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


このサンプルは、拡張モードでマルチECIモードを使用する方法を示しています。
```cpp
[C#]
//コードテキストを作成
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//コードテキストを生成
string codetext = TextBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## 関連項目

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
