---
title: "Aspose::BarCode::Generation::DotCodeParameters class"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::DotCodeParameters クラス。C++ における DotCode パラメータ。"
type: docs
weight: 2200
url: /ja/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


DotCode パラメータ。

```cpp
class DotCodeParameters : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [get_Columns](./get_columns/)() const | 列数を識別します。DotCodeシンボルの行数と列数の合計は奇数でなければなりません。列数は最低でも5である必要があります。デフォルト値: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | ECIエンコーディングを識別します。DotCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | DotCode エンコードモードを識別します。デフォルト値: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | コードがバーコードリーダーの初期化または再プログラミングの指示として、リーダーに以下のデータを解釈させるために使用されるかどうかを示します。デフォルト値は false です。 |
| [get_Rows](./get_rows/)() const | 行数を識別します。DotCodeシンボルの行数と列数の合計は奇数でなければなりません。行数は最低でも5である必要があります。デフォルト値: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | DotCode 構造付加モードバーコードの ID を識別します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。 |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | DotCode 構造付加モードのバーコード数を識別します。デフォルト値は -1 です。カウントは 1 から 35 の範囲でなければなりません。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) モジュールの高さ/幅比率。 |
| [set_Columns](./set_columns/)(int32_t) | 列数を識別します。DotCodeシンボルの行数と列数の合計は奇数でなければなりません。列数は最低でも5である必要があります。デフォルト値: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECIエンコーディングを識別します。DotCodeEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | DotCode エンコードモードを識別します。デフォルト値: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | コードがバーコードリーダーの初期化または再プログラミングの指示として、リーダーに以下のデータを解釈させるために使用されるかどうかを示します。デフォルト値は false です。 |
| [set_Rows](./set_rows/)(int32_t) | 行数を識別します。DotCodeシンボルの行数と列数の合計は奇数でなければなりません。行数は最低でも5である必要があります。デフォルト値: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | DotCode 構造付加モードバーコードの ID を識別します。ID は 1 から開始し、バーコード数以下である必要があります。デフォルト値は -1 です。 |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | DotCode 構造付加モードのバーコード数を識別します。デフォルト値は -1 です。カウントは 1 から 35 の範囲でなければなりません。 |
| [ToString](./tostring/)() const override | この [DotCodeParameters](./) の人間が読みやすい文字列表現を返します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
