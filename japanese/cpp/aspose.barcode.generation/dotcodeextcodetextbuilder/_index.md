---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder クラス"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++ で Aspose::BarCode::Generation::DotCodeExtCodetextBuilder クラスを使用する方法。"
type: docs
weight: 2100
url: /ja/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | 拡張チャネル識別子を使用してコードテキストを追加します |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | 拡張コードテキスト項目に FNC1 フォーマット識別子を追加します |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | 拡張コードテキスト項目に FNC3 リーダー初期化を追加します |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | 拡張コードテキスト項目に FNC3 シンボル区切りを追加します |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | 拡張コードテキスト項目にプレーンコードテキストを追加します |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | 拡張コードテキスト項目に構造化追加モードを追加します |
| virtual [Clear](../extcodetextbuilder/clear/)() | 拡張コードテキスト項目をクリアします |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | 拡張コードテキストリストから拡張コードテキストを生成します。 |
## 備考


DotCodeEncodeMode の ExtendedCodetext モード用 2D DotCode バーコードの拡張コードテキストジェネレータ


```cpp
[C#]
//拡張コードテキストモード
//コードテキストを作成
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//コードテキストを生成
string codetext = textBuilder.GetExtendedCodetext();

//生成
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## 関連項目

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
