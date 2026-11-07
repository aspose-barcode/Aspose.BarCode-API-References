---
title: "Aspose::BarCode::Generation::BaseEncodeType クラス"
linktitle: "BaseEncodeType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::BaseEncodeType クラス。C++ における SymbologyEncodeType の基底クラスです。"
type: docs
weight: 600
url: /ja/cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


[SymbologyEncodeType](../symbologyencodetype/) の基底クラスです。

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<BaseEncodeType>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | このインスタンスが指定された [BaseEncodeType](./) の値と等しいかどうかを示す値を返します。 |
| [get_Classification](./get_classification/)() const | このシンボロジーの分類を取得します。 |
| [get_TypeIndex](./get_typeindex/)() const | エンコード タイプのインデックスを取得します。 |
| [get_TypeName](./get_typename/)() const | エンコード タイプの名前を取得します。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [GetString](./getstring/)() | [BaseEncodeType](./) のインスタンスを等価な文字列表現に変換します。文字列形式は次のとおりです: "Index:0; Name:Codabar"。 |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | [BaseEncodeType](./) のインスタンスを等価な文字列表現に変換します。文字列形式は次のとおりです: "Index:-1; Name:None"。 |
| static [Parse](./parse/)(System::String) | [BaseEncodeType](./) の名前の文字列表現をインスタンスに変換します。 |
| [ToString](./tostring/)() const override | 指定された [BaseEncodeType](./) の名前を文字列として返します。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](./) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | [BaseEncodeType](./) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
