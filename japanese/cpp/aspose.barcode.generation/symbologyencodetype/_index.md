---
title: "Aspose::BarCode::Generation::SymbologyEncodeType クラス"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::SymbologyEncodeType クラス。シンボロジー エンコード タイプ。C++ でインスタンスを取得するには EncodeTypes を参照してください。"
type: docs
weight: 4900
url: /ja/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


シンボロジー エンコード タイプ。[EncodeTypes](../encodetypes/) を参照してインスタンスを取得してください。

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | このインスタンスが指定された [BaseEncodeType](../baseencodetype/) の値と等しいかどうかを示す値を返します。 |
| [get_Classification](../baseencodetype/get_classification/)() const | このシンボロジーの分類を取得します。 |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | エンコード タイプのインデックスを取得します。 |
| [get_TypeName](../baseencodetype/get_typename/)() const | エンコード タイプの名前を取得します。 |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [GetString](../baseencodetype/getstring/)() | [BaseEncodeType](../baseencodetype/) のインスタンスを同等の文字列表現に変換します。文字列形式は: "Index:0; Name:Codabar" です。 |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | [BaseEncodeType](../baseencodetype/) のインスタンスを同等の文字列表現に変換します。文字列形式は: "Index:-1; Name:None" です。 |
| static [Parse](../baseencodetype/parse/)(System::String) | [BaseEncodeType](../baseencodetype/) の名前の文字列表現をインスタンスに変換します。 |
| [ToString](../baseencodetype/tostring/)() const override | 指定された [BaseEncodeType](../baseencodetype/) の名前を文字列として返します。 |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | [BaseEncodeType](../baseencodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
## 備考


This sample shows how to get instance of [SymbologyEncodeType](./) class.
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## 関連項目

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
