---
title: "Aspose::BarCode::Generation::MaxiCodeParameters クラス"
linktitle: "MaxiCodeParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::MaxiCodeParameters クラス。C++ の MaxiCode パラメータ。"
type: docs
weight: 3600
url: /ja/cpp/aspose.barcode.generation/maxicodeparameters/
---
## MaxiCodeParameters class


MaxiCode パラメータ。

```cpp
class MaxiCodeParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [get_ECIEncoding](./get_eciencoding/)() const | ECIエンコーディングを取得します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | MaxiCode エンコードモードを取得します。デフォルト値: Auto。 |
| [get_Mode](./get_mode/)() const | MaxiCode エンコードモードを取得します。 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | 構造化付加モードでの MaxiCode バーコード ID を取得します。ID は 1 から 8 の間の値である必要があります。デフォルト値: 0 |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | 構造化付加モードでの MaxiCode バーコード数を取得します。カウント数は 2 から 8 の間の値（最大バーコード数）である必要があります。デフォルト値: -1 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECIエンコーディングを設定します。MaxiCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(MaxiCodeEncodeMode) | MaxiCode エンコードモードを設定します。デフォルト値: Auto。 |
| [set_Mode](./set_mode/)(MaxiCodeMode) | MaxiCode エンコードモードを設定します。 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | 構造化付加モードでの MaxiCode バーコード ID を設定します。ID は 1 から 8 の間の値である必要があります。デフォルト値: 0 |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | 構造化付加モードでの MaxiCode バーコード数を設定します。カウント数は 2 から 8 の間の値（最大バーコード数）である必要があります。デフォルト値: -1 |
| [ToString](./tostring/)() const override | この [MaxiCodeParameters](./) の人間が読める文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
