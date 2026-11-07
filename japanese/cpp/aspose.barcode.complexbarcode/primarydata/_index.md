---
title: "Aspose::BarCode::ComplexBarcode::PrimaryData class"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::PrimaryData クラス。C++ で HIBC LIC の一次データを保存するためのクラスです。"
type: docs
weight: 2500
url: /ja/cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


HIBC LICの主要データを格納するクラスです。

```cpp
class PrimaryData : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [PrimaryData](./) の値と等しいかどうかを示す値を返します。 |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() const | ラベラー識別コードの日付を識別します。ラベラー識別コードは 4 文字の英数字文字列で、最初の文字は必ずアルファベットでなければなりません。 |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() const | 製品またはカタログ番号を識別します。製品またはカタログ番号は最大 18 文字の英数字文字列である必要があります。 |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() const | 測定単位 ID を識別します。測定単位 ID は 0 から 9 の整数値でなければなりません。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [ParseFromString](./parsefromstring/)(System::String) | HIBC LIC 仕様に従って文字列形式から一次データをインスタンス化します。 |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | ラベラー識別コードの日付を識別します。ラベラー識別コードは 4 文字の英数字文字列で、最初の文字は必ずアルファベットでなければなりません。 |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | 製品またはカタログ番号を識別します。製品またはカタログ番号は最大 18 文字の英数字文字列である必要があります。 |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | 測定単位 ID を識別します。測定単位 ID は 0 から 9 の整数値でなければなりません。 |
| [ToString](./tostring/)() const override | HIBC LIC 仕様に従ってデータを文字列形式に変換します。 |
## 関連項目

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
