---
title: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters クラス"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters クラス。C++で認識されたDataMatrixバーコードの特別なデータを格納します"
type: docs
weight: 1500
url: /ja/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)で認識されたバーコードの特別なデータを格納します

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | コードがバーコードリーダーの初期化または再プログラミングの指示として、リーダーに以下のデータを解釈させるために使用されるかどうかを示します。デフォルト値は false です。 |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)構造化追加モードバーコードのIDを取得します。IDは1から開始し、バーコード数以下である必要があります。デフォルト値は-1です。 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)構造化追加モードのバーコード数を取得します。デフォルト値は-1です。カウントは1から35までの値である必要があります。 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)構造化追加モードバーコードのIDを取得します。IDは1から開始し、バーコード数以下である必要があります。デフォルト値は-1です。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ToString](./tostring/)() const override | この [DataMatrixExtendedParameters](./) の人間が読みやすい文字列表現を返します |
## 備考


このサンプルは、[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) の生データを取得する方法を示しています
```cpp
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

## 関連項目

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
