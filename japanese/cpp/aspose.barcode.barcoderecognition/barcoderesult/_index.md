---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult クラス"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult クラス。C++ で認識されたバーコードデータを、SingleDecodeType 型、System::String codetext、BarCodeRegionParameters region などのパラメータとして格納します。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


認識されたバーコードデータを、[SingleDecodeType](../singledecodetype/) 型、**System::String** codetext、[BarCodeRegionParameters](../barcoderegionparameters/) region などのパラメータとして格納します

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | [BarCodeResult](./) クラスのコピーを作成します。 |
| [Clone](./clone/)() override | [BarCodeResult](./) クラスのコピーを作成します。 |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | このインスタンスが指定された [BarCodeResult](./) の値と等しいかどうかを示す値を返します。 |
| [get_CodeBytes](./get_codebytes/)() const | エンコードされたコードバイトを取得します |
| [get_CodeText](./get_codetext/)() const | コードテキストを取得します |
| [get_CodeType](./get_codetype/)() const | バーコードのタイプを取得します |
| [get_CodeTypeName](./get_codetypename/)() | バーコードタイプの名前を取得します |
| [get_Confidence](./get_confidence/)() const | 認識されたバーコードの信頼度レベルを取得します |
| [get_Extended](./get_extended/)() const | 認識されたバーコードの拡張パラメータを取得します |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | 認識されたバーコードの ISO/IEC シンボル品質評価結果を取得します。 |
| [get_ReadingQuality](./get_readingquality/)() const | 読み取り品質を取得します。1D および郵便バーコードで機能します。 |
| [get_Region](./get_region/)() const | バーコード領域を取得します |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | エンコードされたコードテキストを取得します。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [BarCodeResult](./) の人間が読みやすい文字列表現を返します。 |
## 備考


このサンプルは [BarCodeResult](./) の取得方法を示しています。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
