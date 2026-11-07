---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters クラス"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters クラス。C++ で認識された DotCode バーコードの特別なデータを保存します。"
type: docs
weight: 2000
url: /ja/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


DotCode 認識バーコードの特殊データを格納します

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | コードがバーコードリーダーの初期化または再プログラミングの指示として、リーダーに以下のデータを解釈させるために使用されるかどうかを示します。デフォルト値は false です。 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | DotCode 構造化付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコードの数以下でなければなりません。デフォルト値は -1 です。 |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | DotCode 構造化付加モードのバーコード数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の範囲でなければなりません。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [DotCodeExtendedParameters](./) の人間が読みやすい文字列表現を返します。 |
## 備考


このサンプルは DotCode の生データ取得方法を示しています。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## 関連項目

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
