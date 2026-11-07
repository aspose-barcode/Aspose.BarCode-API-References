---
title: "Aspose::BarCode::Generation::AztecParameters クラス"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::AztecParameters クラス。C++ の Aztec パラメータ。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec パラメーター。

```cpp
class AztecParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI エンコーディングを取得します。AztecEncodeMode が Auto のときに使用されます。デフォルト値: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Aztec エンコードモードを取得します。デフォルト値: Auto。 |
| [get_ErrorLevel](./get_errorlevel/)() const | Aztec タイプのバーコードの誤り訂正レベル。値は 5 から 95 の間である必要があります。 |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | リーダーにシンボル内のデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [get_LayersCount](./get_layerscount/)() const | Aztec シンボルのレイヤー数を取得します。レイヤー数は Compact モードでは 1 から 3、Full Range モードでは 1 から 32 の範囲である必要があります。既定値: 0（自動）。 |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec バーコードの Structured Append モード用のバーコード ID。バーコード ID は 1 からバーコード数までの範囲である必要があります。既定値: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec バーコードの Structured Append モード用のバーコード数。バーコード数は 1 から 26 の範囲である必要があります。既定値: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec バーコードの Structured Append モード用のファイル ID（オプションフィールド）。ファイル ID にスペースを含めてはいけません。既定値: 空文字列 |
| [get_SymbolMode](./get_symbolmode/)() const | Aztec シンボルモードを取得します。既定値: [AztecSymbolMode.Auto](../aztecencodemode/)。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI エンコーディングを設定します。AztecEncodeMode が Auto のときに使用されます。既定値: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Aztec エンコードモードを設定します。既定値: Auto。 |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Aztec タイプのバーコードの誤り訂正レベル。値は 5 から 95 の間である必要があります。 |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | リーダーにシンボル内のデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [set_LayersCount](./set_layerscount/)(int32_t) | Aztec シンボルのレイヤー数を設定します。レイヤー数は Compact モードでは 1 から 3、Full Range モードでは 1 から 32 の範囲である必要があります。既定値: 0（自動）。 |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Aztec バーコードの Structured Append モード用のバーコード ID。バーコード ID は 1 からバーコード数までの範囲である必要があります。既定値: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Aztec バーコードの Structured Append モード用のバーコード数。バーコード数は 1 から 26 の範囲である必要があります。既定値: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Aztec バーコードの Structured Append モード用のファイル ID（オプションフィールド）。ファイル ID にスペースを含めてはいけません。既定値: 空文字列 |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Aztec シンボルモードを設定します。既定値: [AztecSymbolMode.Auto](../aztecencodemode/)。 |
| [ToString](./tostring/)() const override | この [AztecParameters](./) の人間が読みやすい文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
