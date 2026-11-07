---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder クラス"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++ で Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder クラスを使用する方法。"
type: docs
weight: 1900
url: /ja/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | 定義されたエンコードモードで codetext を拡張 codetext アイテムに追加します |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 拡張チャネル識別子を使用してコードテキストを追加します |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | 定義されたエンコードモードで拡張チャネル識別子を使用して codetext を追加します |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 拡張コードテキスト項目にプレーンコードテキストを追加します |
| virtual [Clear](../extcodetextbuilder/clear/)() | 拡張コードテキスト項目をクリアします |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 拡張コードテキストリストから拡張コードテキストを生成します。 |
## 備考


EncodeMode の ExtendedCodetext モード用の 2D DataMatrix バーコード向け拡張 codetext ジェネレータ


```cpp
[C#]
//拡張コードテキストモード

//コードテキストを作成
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//コードテキストを生成
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## 関連項目

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
