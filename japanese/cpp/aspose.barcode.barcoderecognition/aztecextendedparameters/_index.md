---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters クラス。C++ で認識された Aztec バーコードの特別なデータを格納します。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Aztec 認識バーコードの特殊データを格納します

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | コードがバーコードリーダーの初期化または再プログラミングの指示として、リーダーに以下のデータを解釈させるために使用されるかどうかを示します。デフォルト値は false です。 |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec 構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は 0 です。 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec 構造化付加モードのバーコード数を取得します。デフォルト値は 0 です。カウントは 1 から 26 の範囲である必要があります。 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec 構造化付加モードのファイル ID を取得します。デフォルト値は空文字列です |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [AztecExtendedParameters](./) の人間が読みやすい文字列表現を返します。 |
## 備考


このサンプルは Aztec の生データを取得する方法を示しています。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## 関連項目

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
