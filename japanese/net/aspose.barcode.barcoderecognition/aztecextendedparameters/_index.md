---
title: "クラス AztecExtendedParameters"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters クラス。Aztec 認識バーコードの特別なデータを格納します"
type: docs
weight: 40
url: /ja/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Aztec 認識バーコードの特別なデータを格納します

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | すべてのパラメーターがデフォルト値のみであるかテストします |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | コードがリーダーに対し、以下のデータをバーコードリーダーの初期化または再プログラミングの指示として解釈させるために使用されるかどうかを示します。デフォルト値は false です。 |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Aztec 構造化付加モードバーコードの ID を取得します。ID は 1 から始まり、バーコード数以下である必要があります。デフォルト値は 0 です。 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Aztec 構造化付加モードのバーコード数を取得します。デフォルト値は 0 です。カウントは 1 から 26 の範囲でなければなりません。 |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Aztec 構造化付加モードのファイル ID を取得します。デフォルト値は空文字列です |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | このインスタンスが指定された `AztecExtendedParameters` 値と等しいかどうかを示す値を返します。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | この `AztecExtendedParameters` の人間が読める文字列表現を返します。 |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | 最初の `AztecExtendedParameters` 値が2番目と等しいかどうかを示す値を返します。 |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | 最初の `AztecExtendedParameters` 値が2番目と異なるかどうかを示す値を返します。 |

## 例

このサンプルは Aztec の生データ値の取得方法を示しています

```csharp
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

### 関連項目

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


