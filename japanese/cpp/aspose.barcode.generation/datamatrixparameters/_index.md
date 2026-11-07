---
title: "Aspose::BarCode::Generation::DataMatrixParameters クラス"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::DataMatrixParameters クラスです。C++ の DataMatrix パラメータです。"
type: docs
weight: 2000
url: /ja/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


DataMatrix パラメータ。

```cpp
class DataMatrixParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [get_EccType](./get_ecctype/)() const | Datamatrix の ECC タイプを取得します。デフォルト値: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI エンコーディングを取得します。EncodeMode が Auto のときに使用されます。デフォルト値: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Datamatrix バーコードのエンコードモードです。デフォルト値: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | シンボル内に含まれるデータをリーダー初期化用のプログラムとして解釈するようリーダーに指示するために使用されます。デフォルト値: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | マクロ文字 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを取得するために使用されます。[DataMatrixEccType.Ecc200](../datamatrixecctype/) または [DataMatrixEccType.EccAuto](../datamatrixecctype/) のみで使用可能です。[EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) では使用できません。デフォルト値: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Datamatrix バーコードの構造化付加モードのバーコード ID です。デフォルト値: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Datamatrix バーコードの構造化付加モードのバーコード数です。デフォルト値: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Datamatrix バーコードの構造化付加モードのファイル ID。デフォルト値: 0 |
| [get_Version](./get_version/)() const | Datamatrix シンボルサイズを取得します。デフォルト値: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Datamatrix ECC タイプを設定します。デフォルト値: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI エンコーディングを設定します。EncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Datamatrix バーコードのエンコードモードです。デフォルト値: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | シンボル内に含まれるデータをリーダー初期化用のプログラムとして解釈するようリーダーに指示するために使用されます。デフォルト値: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | マクロ文字 05 と 06 の値は、特別なモードでよりコンパクトなエンコードを取得するために使用されます。[DataMatrixEccType.Ecc200](../datamatrixecctype/) または [DataMatrixEccType.EccAuto](../datamatrixecctype/) のみで使用可能です。[EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) では使用できません。デフォルト値: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Datamatrix バーコードの構造化付加モードのバーコード ID です。デフォルト値: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Datamatrix バーコードの構造化付加モードのバーコード数です。デフォルト値: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Datamatrix バーコードの構造化付加モードのファイル ID。デフォルト値: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Datamatrix シンボルサイズを設定します。デフォルト値: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | この [DataMatrixParameters](./) の人間が読みやすい文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
