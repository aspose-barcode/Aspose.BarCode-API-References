---
title: "クラス DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters クラス。DataMatrix 認識バーコードの特別なデータを格納します"
type: docs
weight: 220
url: /ja/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

認識された DataMatrix バーコードの特別なデータを格納します

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | すべてのパラメーターがデフォルト値のみであるかテストします |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | コードがリーダーに対し、以下のデータをバーコードリーダーの初期化または再プログラミングの指示として解釈させるために使用されるかどうかを示します。デフォルト値は false です。 |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | DataMatrix 構造付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | DataMatrix 構造付加モードのバーコード数を取得します。デフォルト値は -1 です。カウントは 1 から 35 の範囲である必要があります。 |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | DataMatrix 構造付加モードバーコードの ID を取得します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | このインスタンスが指定された `DataMatrixExtendedParameters` の値と等しいかどうかを示す値を返します。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | この `DataMatrixExtendedParameters` の人間が読みやすい文字列表現を返します。 |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | 最初の `DataMatrixExtendedParameters` の値が2番目と等しいかどうかを示す値を返します。 |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | 最初の `DataMatrixExtendedParameters` の値が2番目と異なるかどうかを示す値を返します。 |

## 例

このサンプルは DataMatrix の生データを取得する方法を示しています。

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### 関連項目

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


